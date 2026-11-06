# \CoderAccountsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelCoderAccountConnect**](CoderAccountsAPI.md#CancelCoderAccountConnect) | **Delete** /v1/api/coder-accounts/connect/{sessionId} | Cancel subscription sign-in
[**CompleteCoderAccountConnect**](CoderAccountsAPI.md#CompleteCoderAccountConnect) | **Post** /v1/api/coder-accounts/connect/{sessionId}/complete | Finish subscription sign-in or poll device authorization
[**CreateCoderAccount**](CoderAccountsAPI.md#CreateCoderAccount) | **Post** /v1/api/coder-accounts | Import a subscription credential or custom API key
[**DeleteCoderAccount**](CoderAccountsAPI.md#DeleteCoderAccount) | **Delete** /v1/api/coder-accounts/{id} | Remove an account and its credential
[**GetCoderAccountModels**](CoderAccountsAPI.md#GetCoderAccountModels) | **Get** /v1/api/coder-accounts/{id}/models | Read cached models advertised by an account
[**ListCoderAccounts**](CoderAccountsAPI.md#ListCoderAccounts) | **Get** /v1/api/coder-accounts | List safe coder accounts
[**ReconnectCoderAccount**](CoderAccountsAPI.md#ReconnectCoderAccount) | **Put** /v1/api/coder-accounts/{id}/credential | Replace an account credential
[**RefreshCoderAccountModels**](CoderAccountsAPI.md#RefreshCoderAccountModels) | **Post** /v1/api/coder-accounts/{id}/models/refresh | Refresh an API account&#39;s advertised models
[**StartCoderAccountConnect**](CoderAccountsAPI.md#StartCoderAccountConnect) | **Post** /v1/api/coder-accounts/connect | Start subscription sign-in
[**TestCoderAccount**](CoderAccountsAPI.md#TestCoderAccount) | **Post** /v1/api/coder-accounts/{id}/test | Check a Claude or Codex API key
[**UpdateCoderAccount**](CoderAccountsAPI.md#UpdateCoderAccount) | **Patch** /v1/api/coder-accounts/{id} | Rename, share or enable an account



## CancelCoderAccountConnect

> DeletedAck CancelCoderAccountConnect(ctx, sessionId).XOrganizationId(xOrganizationId).Execute()

Cancel subscription sign-in

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
	sessionId := "sessionId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.CancelCoderAccountConnect(context.Background(), sessionId).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCancelCoderAccountConnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeletedAck**](DeletedAck.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	sessionId := "sessionId_example" // string | 
	completeCoderConnect := *openapiclient.NewCompleteCoderConnect() // CompleteCoderConnect | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.CompleteCoderAccountConnect(context.Background(), sessionId).CompleteCoderConnect(completeCoderConnect).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCompleteCoderAccountConnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **completeCoderConnect** | [**CompleteCoderConnect**](CompleteCoderConnect.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderConnectResult**](CoderConnectResult.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	createCoderAccount := *openapiclient.NewCreateCoderAccount("Coder_example", "Credential_example", "Kind_example", "Label_example") // CreateCoderAccount | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.CreateCoderAccount(context.Background()).CreateCoderAccount(createCoderAccount).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCreateCoderAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCoderAccount** | [**CreateCoderAccount**](CreateCoderAccount.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	resp, r, err := apiClient.CoderAccountsAPI.DeleteCoderAccount(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiDeleteCoderAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeletedAck**](DeletedAck.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	resp, r, err := apiClient.CoderAccountsAPI.GetCoderAccountModels(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiGetCoderAccountModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderAccountModelCatalog**](CoderAccountModelCatalog.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.ListCoderAccounts(context.Background()).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiListCoderAccountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	reconnectCoderAccount := *openapiclient.NewReconnectCoderAccount("Credential_example") // ReconnectCoderAccount | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.ReconnectCoderAccount(context.Background(), id).ReconnectCoderAccount(reconnectCoderAccount).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiReconnectCoderAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reconnectCoderAccount** | [**ReconnectCoderAccount**](ReconnectCoderAccount.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	resp, r, err := apiClient.CoderAccountsAPI.RefreshCoderAccountModels(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiRefreshCoderAccountModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderAccountModelCatalog**](CoderAccountModelCatalog.md)

### Authorization

[apiKey](../README.md#apiKey)

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

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/hlix-ai/hlix-go"
)

func main() {
	startCoderConnect := *openapiclient.NewStartCoderConnect("Coder_example", "Label_example") // StartCoderConnect | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.StartCoderAccountConnect(context.Background()).StartCoderConnect(startCoderConnect).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiStartCoderAccountConnectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startCoderConnect** | [**StartCoderConnect**](StartCoderConnect.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderConnect**](CoderConnect.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	resp, r, err := apiClient.CoderAccountsAPI.TestCoderAccount(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiTestCoderAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderAccountProbe**](CoderAccountProbe.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	patchCoderAccount := *openapiclient.NewPatchCoderAccount() // PatchCoderAccount | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CoderAccountsAPI.UpdateCoderAccount(context.Background(), id).PatchCoderAccount(patchCoderAccount).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiUpdateCoderAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchCoderAccount** | [**PatchCoderAccount**](PatchCoderAccount.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoderAccount**](CoderAccount.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

