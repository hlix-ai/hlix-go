# ClientBillingAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AdjustClientBillable**](ClientBillingAPI.md#adjustclientbillable) | **Post** /v1/api/client-billing/billables/{id}/adjust | Append a correction to a charge
[**CreateClientBillable**](ClientBillingAPI.md#createclientbillable) | **Post** /v1/api/client-billing/billables | Record a billable
[**GetClientBillable**](ClientBillingAPI.md#getclientbillable) | **Get** /v1/api/client-billing/billables/{id} | Get one ledger row
[**ListClientBillables**](ClientBillingAPI.md#listclientbillables) | **Get** /v1/api/client-billing/billables | List the ledger
[**VoidClientBillable**](ClientBillingAPI.md#voidclientbillable) | **Post** /v1/api/client-billing/billables/{id}/void | Reverse a charge



## AdjustClientBillable

> ClientBillable AdjustClientBillable(ctx, id).AdjustBillable(adjustBillable).XOrganizationId(xOrganizationId).Execute()

Append a correction to a charge

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"encoding/json"
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	id := "id_example" // string |
	var adjustBillable openapiclient.AdjustBillable
	if err := json.Unmarshal([]byte("{\"description\":\"text\",\"quantity\":1,\"unit\":\"text\",\"unitPriceMicros\":1}"), &adjustBillable); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.AdjustClientBillable(ctx, id).AdjustBillable(adjustBillable).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingAPI.AdjustClientBillable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AdjustClientBillable`: ClientBillable
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingAPI.AdjustClientBillable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiAdjustClientBillableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **adjustBillable** | [**AdjustBillable**](AdjustBillable.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientBillable**](ClientBillable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateClientBillable

> ClientBillable CreateClientBillable(ctx).CreateBillable(createBillable).XOrganizationId(xOrganizationId).Execute()

Record a billable

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	createBillable := openapiclient.CreateBillable{CreateBillableOneOf: openapiclient.NewCreateBillableOneOf("ClientAccountId_example", "Currency_example", "Description_example", float32(123), "Source_example", "Unit_example", int64(123))} // CreateBillable |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.CreateClientBillable(ctx).CreateBillable(createBillable).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingAPI.CreateClientBillable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateClientBillable`: ClientBillable
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingAPI.CreateClientBillable`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateClientBillableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createBillable** | [**CreateBillable**](CreateBillable.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientBillable**](ClientBillable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetClientBillable

> ClientBillableView GetClientBillable(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get one ledger row

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	id := "id_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.GetClientBillable(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingAPI.GetClientBillable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetClientBillable`: ClientBillableView
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingAPI.GetClientBillable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetClientBillableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientBillableView**](ClientBillableView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListClientBillables

> []ClientBillableView ListClientBillables(ctx).ClientAccountId(clientAccountId).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()

List the ledger

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	clientAccountId := "clientAccountId_example" // string | Only this customer's rows. (optional)
	projectId := "projectId_example" // string | Limit results to this project. A client collaborator without project access receives an access error rather than an empty ledger. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.ListClientBillables(ctx).ClientAccountId(clientAccountId).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingAPI.ListClientBillables``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListClientBillables`: []ClientBillableView
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingAPI.ListClientBillables`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListClientBillablesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **clientAccountId** | **string** | Only this customer&#39;s rows. |
 **projectId** | **string** | Limit results to this project. A client collaborator without project access receives an access error rather than an empty ledger. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ClientBillableView**](ClientBillableView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VoidClientBillable

> ClientBillable VoidClientBillable(ctx, id).VoidBillable(voidBillable).XOrganizationId(xOrganizationId).Execute()

Reverse a charge

### Example

Replace example resource IDs and request values with your own before running.

```go
package main

import (
	"encoding/json"
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	ctx := context.WithValue(context.Background(), openapiclient.ContextAPIKeys, map[string]openapiclient.APIKey{
		"apiKey": {Key: os.Getenv("HLIX_API_KEY")},
	})
	id := "id_example" // string |
	var voidBillable openapiclient.VoidBillable
	if err := json.Unmarshal([]byte("{\"reason\":\"text\"}"), &voidBillable); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.VoidClientBillable(ctx, id).VoidBillable(voidBillable).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ClientBillingAPI.VoidClientBillable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VoidClientBillable`: ClientBillable
	fmt.Fprintf(os.Stdout, "Response from `ClientBillingAPI.VoidClientBillable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiVoidClientBillableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **voidBillable** | [**VoidBillable**](VoidBillable.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ClientBillable**](ClientBillable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

