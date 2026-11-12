# CoderAccountsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelCoderAccountConnect**](CoderAccountsAPI.md#cancelcoderaccountconnect) | **Delete** /v1/api/coder-accounts/connect/{sessionId} | Cancel subscription sign-in
[**CompleteCoderAccountConnect**](CoderAccountsAPI.md#completecoderaccountconnect) | **Post** /v1/api/coder-accounts/connect/{sessionId}/complete | Finish subscription sign-in or poll device authorization
[**CreateCoderAccount**](CoderAccountsAPI.md#createcoderaccount) | **Post** /v1/api/coder-accounts | Import a subscription credential or custom API key
[**DeleteCoderAccount**](CoderAccountsAPI.md#deletecoderaccount) | **Delete** /v1/api/coder-accounts/{id} | Remove an account and its credential
[**GetCoderAccountModels**](CoderAccountsAPI.md#getcoderaccountmodels) | **Get** /v1/api/coder-accounts/{id}/models | Read cached models advertised by an account
[**ListCoderAccounts**](CoderAccountsAPI.md#listcoderaccounts) | **Get** /v1/api/coder-accounts | List safe coder accounts
[**ReconnectCoderAccount**](CoderAccountsAPI.md#reconnectcoderaccount) | **Put** /v1/api/coder-accounts/{id}/credential | Replace an account credential
[**RefreshCoderAccountModels**](CoderAccountsAPI.md#refreshcoderaccountmodels) | **Post** /v1/api/coder-accounts/{id}/models/refresh | Refresh an API account&#39;s advertised models
[**StartCoderAccountConnect**](CoderAccountsAPI.md#startcoderaccountconnect) | **Post** /v1/api/coder-accounts/connect | Start subscription sign-in
[**TestCoderAccount**](CoderAccountsAPI.md#testcoderaccount) | **Post** /v1/api/coder-accounts/{id}/test | Check a Claude or Codex API key
[**UpdateCoderAccount**](CoderAccountsAPI.md#updatecoderaccount) | **Patch** /v1/api/coder-accounts/{id} | Rename, share or enable an account



## CancelCoderAccountConnect

> DeletedAck CancelCoderAccountConnect(ctx, sessionId).XOrganizationId(xOrganizationId).Execute()

Cancel subscription sign-in

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
	sessionId := "sessionId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.CancelCoderAccountConnect(ctx, sessionId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.CancelCoderAccountConnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelCoderAccountConnect`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.CancelCoderAccountConnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCancelCoderAccountConnectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeletedAck**](DeletedAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompleteCoderAccountConnect

> CoderConnectResult CompleteCoderAccountConnect(ctx, sessionId).CompleteCoderConnect(completeCoderConnect).XOrganizationId(xOrganizationId).Execute()

Finish subscription sign-in or poll device authorization

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
	sessionId := "sessionId_example" // string |
	var completeCoderConnect openapiclient.CompleteCoderConnect
	if err := json.Unmarshal([]byte("{}"), &completeCoderConnect); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.CompleteCoderAccountConnect(ctx, sessionId).CompleteCoderConnect(completeCoderConnect).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.CompleteCoderAccountConnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompleteCoderAccountConnect`: CoderConnectResult
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.CompleteCoderAccountConnect`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**sessionId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCompleteCoderAccountConnectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **completeCoderConnect** | [**CompleteCoderConnect**](CompleteCoderConnect.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderConnectResult**](CoderConnectResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCoderAccount

> CoderAccount CreateCoderAccount(ctx).CreateCoderAccount(createCoderAccount).XOrganizationId(xOrganizationId).Execute()

Import a subscription credential or custom API key

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
	var createCoderAccount openapiclient.CreateCoderAccount
	if err := json.Unmarshal([]byte("{\"coder\":\"claude-code\",\"credential\":\"text\",\"kind\":\"subscription\",\"label\":\"text\"}"), &createCoderAccount); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.CreateCoderAccount(ctx).CreateCoderAccount(createCoderAccount).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.CreateCoderAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCoderAccount`: CoderAccount
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.CreateCoderAccount`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateCoderAccountRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCoderAccount** | [**CreateCoderAccount**](CreateCoderAccount.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCoderAccount

> DeletedAck DeleteCoderAccount(ctx, id).XOrganizationId(xOrganizationId).Execute()

Remove an account and its credential

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
	resp, r, err := apiClient.CoderAccountsAPI.DeleteCoderAccount(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.DeleteCoderAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCoderAccount`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.DeleteCoderAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteCoderAccountRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeletedAck**](DeletedAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCoderAccountModels

> CoderAccountModelCatalog GetCoderAccountModels(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read cached models advertised by an account

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
	resp, r, err := apiClient.CoderAccountsAPI.GetCoderAccountModels(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.GetCoderAccountModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCoderAccountModels`: CoderAccountModelCatalog
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.GetCoderAccountModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCoderAccountModelsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccountModelCatalog**](CoderAccountModelCatalog.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCoderAccounts

> []CoderAccount ListCoderAccounts(ctx).XOrganizationId(xOrganizationId).Execute()

List safe coder accounts

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
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.ListCoderAccounts(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.ListCoderAccounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCoderAccounts`: []CoderAccount
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.ListCoderAccounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListCoderAccountsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReconnectCoderAccount

> CoderAccount ReconnectCoderAccount(ctx, id).ReconnectCoderAccount(reconnectCoderAccount).XOrganizationId(xOrganizationId).Execute()

Replace an account credential

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
	var reconnectCoderAccount openapiclient.ReconnectCoderAccount
	if err := json.Unmarshal([]byte("{\"credential\":\"text\"}"), &reconnectCoderAccount); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.ReconnectCoderAccount(ctx, id).ReconnectCoderAccount(reconnectCoderAccount).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.ReconnectCoderAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReconnectCoderAccount`: CoderAccount
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.ReconnectCoderAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiReconnectCoderAccountRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reconnectCoderAccount** | [**ReconnectCoderAccount**](ReconnectCoderAccount.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefreshCoderAccountModels

> CoderAccountModelCatalog RefreshCoderAccountModels(ctx, id).XOrganizationId(xOrganizationId).Execute()

Refresh an API account's advertised models

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
	resp, r, err := apiClient.CoderAccountsAPI.RefreshCoderAccountModels(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.RefreshCoderAccountModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefreshCoderAccountModels`: CoderAccountModelCatalog
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.RefreshCoderAccountModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRefreshCoderAccountModelsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccountModelCatalog**](CoderAccountModelCatalog.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartCoderAccountConnect

> CoderConnect StartCoderAccountConnect(ctx).StartCoderConnect(startCoderConnect).XOrganizationId(xOrganizationId).Execute()

Start subscription sign-in

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
	var startCoderConnect openapiclient.StartCoderConnect
	if err := json.Unmarshal([]byte("{\"coder\":\"claude-code\",\"label\":\"text\"}"), &startCoderConnect); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.StartCoderAccountConnect(ctx).StartCoderConnect(startCoderConnect).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.StartCoderAccountConnect``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartCoderAccountConnect`: CoderConnect
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.StartCoderAccountConnect`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiStartCoderAccountConnectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startCoderConnect** | [**StartCoderConnect**](StartCoderConnect.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderConnect**](CoderConnect.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestCoderAccount

> CoderAccountProbe TestCoderAccount(ctx, id).XOrganizationId(xOrganizationId).Execute()

Check a Claude or Codex API key

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
	resp, r, err := apiClient.CoderAccountsAPI.TestCoderAccount(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.TestCoderAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestCoderAccount`: CoderAccountProbe
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.TestCoderAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiTestCoderAccountRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccountProbe**](CoderAccountProbe.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCoderAccount

> CoderAccount UpdateCoderAccount(ctx, id).PatchCoderAccount(patchCoderAccount).XOrganizationId(xOrganizationId).Execute()

Rename, share or enable an account

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
	var patchCoderAccount openapiclient.PatchCoderAccount
	if err := json.Unmarshal([]byte("{}"), &patchCoderAccount); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.UpdateCoderAccount(ctx, id).PatchCoderAccount(patchCoderAccount).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CoderAccountsAPI.UpdateCoderAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCoderAccount`: CoderAccount
	fmt.Fprintf(os.Stdout, "Response from `CoderAccountsAPI.UpdateCoderAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateCoderAccountRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchCoderAccount** | [**PatchCoderAccount**](PatchCoderAccount.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

