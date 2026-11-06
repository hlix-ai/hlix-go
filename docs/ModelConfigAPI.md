# \ModelConfigAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ClearAiSettings**](ModelConfigAPI.md#ClearAiSettings) | **Delete** /v1/api/model-config/{slot} | Clear one workspace settings group
[**ClearProjectAiSettings**](ModelConfigAPI.md#ClearProjectAiSettings) | **Delete** /v1/api/model-config/projects/{projectId}/{slot} | Clear a project&#39;s override of one settings group
[**GetResolvedAiSettings**](ModelConfigAPI.md#GetResolvedAiSettings) | **Get** /v1/api/model-config/resolved | Resolve the workspace&#39;s AI settings, with provenance
[**GetResolvedProjectAiSettings**](ModelConfigAPI.md#GetResolvedProjectAiSettings) | **Get** /v1/api/model-config/projects/{projectId}/resolved | Resolve a project&#39;s AI settings, with provenance
[**ListAiSettings**](ModelConfigAPI.md#ListAiSettings) | **Get** /v1/api/model-config | List the workspace&#39;s AI settings rows
[**ListModelCatalog**](ModelConfigAPI.md#ListModelCatalog) | **Get** /v1/api/model-config/catalog | List current tool-capable chat models
[**SetAiSettings**](ModelConfigAPI.md#SetAiSettings) | **Put** /v1/api/model-config/{slot} | Set one workspace settings group
[**SetProjectAiSettings**](ModelConfigAPI.md#SetProjectAiSettings) | **Put** /v1/api/model-config/projects/{projectId}/{slot} | Set a project&#39;s override of one settings group



## ClearAiSettings

> DeletedAck ClearAiSettings(ctx, slot).XOrganizationId(xOrganizationId).Execute()

Clear one workspace settings group

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
	slot := "slot_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelConfigAPI.ClearAiSettings(context.Background(), slot).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.ClearAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClearAiSettings`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.ClearAiSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slot** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClearAiSettingsRequest struct via the builder pattern


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


## ClearProjectAiSettings

> DeletedAck ClearProjectAiSettings(ctx, projectId, slot).XOrganizationId(xOrganizationId).Execute()

Clear a project's override of one settings group

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
	projectId := "projectId_example" // string | 
	slot := "slot_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelConfigAPI.ClearProjectAiSettings(context.Background(), projectId, slot).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.ClearProjectAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClearProjectAiSettings`: DeletedAck
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.ClearProjectAiSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**slot** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClearProjectAiSettingsRequest struct via the builder pattern


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


## GetResolvedAiSettings

> ResolvedSettings GetResolvedAiSettings(ctx).XOrganizationId(xOrganizationId).Execute()

Resolve the workspace's AI settings, with provenance

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
	resp, r, err := apiClient.ModelConfigAPI.GetResolvedAiSettings(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.GetResolvedAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetResolvedAiSettings`: ResolvedSettings
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.GetResolvedAiSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetResolvedAiSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ResolvedSettings**](ResolvedSettings.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetResolvedProjectAiSettings

> ResolvedSettings GetResolvedProjectAiSettings(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Resolve a project's AI settings, with provenance

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
	projectId := "projectId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelConfigAPI.GetResolvedProjectAiSettings(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.GetResolvedProjectAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetResolvedProjectAiSettings`: ResolvedSettings
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.GetResolvedProjectAiSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetResolvedProjectAiSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ResolvedSettings**](ResolvedSettings.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAiSettings

> []CoreSettingsRow ListAiSettings(ctx).XOrganizationId(xOrganizationId).Execute()

List the workspace's AI settings rows

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
	resp, r, err := apiClient.ModelConfigAPI.ListAiSettings(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.ListAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAiSettings`: []CoreSettingsRow
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.ListAiSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAiSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]CoreSettingsRow**](CoreSettingsRow.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListModelCatalog

> ModelCatalog ListModelCatalog(ctx).XOrganizationId(xOrganizationId).Execute()

List current tool-capable chat models

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
	resp, r, err := apiClient.ModelConfigAPI.ListModelCatalog(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.ListModelCatalog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListModelCatalog`: ModelCatalog
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.ListModelCatalog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListModelCatalogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ModelCatalog**](ModelCatalog.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetAiSettings

> CoreSettingsRow SetAiSettings(ctx, slot).UpsertSettings(upsertSettings).XOrganizationId(xOrganizationId).Execute()

Set one workspace settings group

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
	slot := "slot_example" // string | 
	upsertSettings := *openapiclient.NewUpsertSettings() // UpsertSettings | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelConfigAPI.SetAiSettings(context.Background(), slot).UpsertSettings(upsertSettings).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.SetAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetAiSettings`: CoreSettingsRow
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.SetAiSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**slot** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetAiSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **upsertSettings** | [**UpsertSettings**](UpsertSettings.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoreSettingsRow**](CoreSettingsRow.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetProjectAiSettings

> CoreSettingsRow SetProjectAiSettings(ctx, projectId, slot).UpsertSettings(upsertSettings).XOrganizationId(xOrganizationId).Execute()

Set a project's override of one settings group

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
	projectId := "projectId_example" // string | 
	slot := "slot_example" // string | 
	upsertSettings := *openapiclient.NewUpsertSettings() // UpsertSettings | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ModelConfigAPI.SetProjectAiSettings(context.Background(), projectId, slot).UpsertSettings(upsertSettings).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ModelConfigAPI.SetProjectAiSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetProjectAiSettings`: CoreSettingsRow
	fmt.Fprintf(os.Stdout, "Response from `ModelConfigAPI.SetProjectAiSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**slot** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetProjectAiSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **upsertSettings** | [**UpsertSettings**](UpsertSettings.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**CoreSettingsRow**](CoreSettingsRow.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

