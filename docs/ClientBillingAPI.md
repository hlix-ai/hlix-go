# \ClientBillingAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AdjustClientBillable**](ClientBillingAPI.md#AdjustClientBillable) | **Post** /v1/api/client-billing/billables/{id}/adjust | Append a correction to a charge
[**CreateClientBillable**](ClientBillingAPI.md#CreateClientBillable) | **Post** /v1/api/client-billing/billables | Record a billable
[**GetClientBillable**](ClientBillingAPI.md#GetClientBillable) | **Get** /v1/api/client-billing/billables/{id} | Get one ledger row
[**ListClientBillables**](ClientBillingAPI.md#ListClientBillables) | **Get** /v1/api/client-billing/billables | List the ledger
[**VoidClientBillable**](ClientBillingAPI.md#VoidClientBillable) | **Post** /v1/api/client-billing/billables/{id}/void | Reverse a charge



## AdjustClientBillable

> ClientBillable AdjustClientBillable(ctx, id).AdjustBillable(adjustBillable).XOrganizationId(xOrganizationId).Execute()

Append a correction to a charge

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	adjustBillable := *openapiclient.NewAdjustBillable("Description_example", float32(123), "Unit_example", int64(123)) // AdjustBillable | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.AdjustClientBillable(context.Background(), id).AdjustBillable(adjustBillable).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiAdjustClientBillableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **adjustBillable** | [**AdjustBillable**](AdjustBillable.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientBillable**](ClientBillable.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	createBillable := openapiclient.CreateBillable{CreateBillableOneOf: openapiclient.NewCreateBillableOneOf("ClientAccountId_example", "Currency_example", "Description_example", float32(123), "Source_example", "Unit_example", int64(123))} // CreateBillable | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.CreateClientBillable(context.Background()).CreateBillable(createBillable).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCreateClientBillableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createBillable** | [**CreateBillable**](CreateBillable.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientBillable**](ClientBillable.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.GetClientBillable(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiGetClientBillableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientBillableView**](ClientBillableView.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	clientAccountId := "clientAccountId_example" // string | Only this customer's rows. (optional)
	projectId := "projectId_example" // string | Only this project's rows. A client collaborator asking about a project it cannot reach is REFUSED rather than answered with an empty list — 'not yours' must not read as 'nothing billed yet'. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.ListClientBillables(context.Background()).ClientAccountId(clientAccountId).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListClientBillablesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **clientAccountId** | **string** | Only this customer&#39;s rows. | 
 **projectId** | **string** | Only this project&#39;s rows. A client collaborator asking about a project it cannot reach is REFUSED rather than answered with an empty list — &#39;not yours&#39; must not read as &#39;nothing billed yet&#39;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]ClientBillableView**](ClientBillableView.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	id := "id_example" // string | 
	voidBillable := *openapiclient.NewVoidBillable("Reason_example") // VoidBillable | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ClientBillingAPI.VoidClientBillable(context.Background(), id).VoidBillable(voidBillable).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiVoidClientBillableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **voidBillable** | [**VoidBillable**](VoidBillable.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ClientBillable**](ClientBillable.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

