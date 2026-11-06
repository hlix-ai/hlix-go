# \PluginsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPlugin**](PluginsAPI.md#GetPlugin) | **Get** /v1/api/plugins/{id} | Read a plugin installation
[**GetPluginCatalogDetail**](PluginsAPI.md#GetPluginCatalogDetail) | **Get** /v1/api/plugins/catalog/detail | Read MCP Registry details and a public repository README
[**ImportPluginArchive**](PluginsAPI.md#ImportPluginArchive) | **Post** /v1/api/plugins/import-archive | Preview a standard plugin or Agent Skills ZIP
[**InstallPlugin**](PluginsAPI.md#InstallPlugin) | **Post** /v1/api/plugins | Install a plugin with encrypted inputs
[**ListPluginCatalog**](PluginsAPI.md#ListPluginCatalog) | **Get** /v1/api/plugins/catalog | Browse official MCP Registry recipes
[**ListPlugins**](PluginsAPI.md#ListPlugins) | **Get** /v1/api/plugins | List installed workspace plugins
[**PreviewPlugin**](PluginsAPI.md#PreviewPlugin) | **Post** /v1/api/plugins/preview | Validate a plugin manifest without installing
[**RemovePlugin**](PluginsAPI.md#RemovePlugin) | **Delete** /v1/api/plugins/{id} | Remove a plugin from subsequent runs
[**UpdatePlugin**](PluginsAPI.md#UpdatePlugin) | **Patch** /v1/api/plugins/{id} | Update plugin setup, version or project availability



## GetPlugin

> PluginResponse GetPlugin(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read a plugin installation

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
	resp, r, err := apiClient.PluginsAPI.GetPlugin(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.GetPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlugin`: PluginResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.GetPlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginResponse**](PluginResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPluginCatalogDetail

> PluginCatalogDetailResponse GetPluginCatalogDetail(ctx).Name(name).Version(version).XOrganizationId(xOrganizationId).Execute()

Read MCP Registry details and a public repository README

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
	name := "name_example" // string | Canonical MCP Registry server name.
	version := "version_example" // string | Exact registry version or latest (default). (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.GetPluginCatalogDetail(context.Background()).Name(name).Version(version).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.GetPluginCatalogDetail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPluginCatalogDetail`: PluginCatalogDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.GetPluginCatalogDetail`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPluginCatalogDetailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **string** | Canonical MCP Registry server name. | 
 **version** | **string** | Exact registry version or latest (default). | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginCatalogDetailResponse**](PluginCatalogDetailResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportPluginArchive

> PluginArchivePreviewResponse ImportPluginArchive(ctx).Body(body).XOrganizationId(xOrganizationId).Execute()

Preview a standard plugin or Agent Skills ZIP

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
	body := os.NewFile(1234, "some_file") // *os.File | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.ImportPluginArchive(context.Background()).Body(body).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.ImportPluginArchive``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportPluginArchive`: PluginArchivePreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.ImportPluginArchive`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiImportPluginArchiveRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | ***os.File** |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginArchivePreviewResponse**](PluginArchivePreviewResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/zip
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InstallPlugin

> PluginResponse InstallPlugin(ctx).CreatePlugin(createPlugin).XOrganizationId(xOrganizationId).Execute()

Install a plugin with encrypted inputs

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
	createPlugin := *openapiclient.NewCreatePlugin(map[string]string{"key": "Inner_example"}, *openapiclient.NewCreatePluginManifest("Description_example", "Id_example", []openapiclient.CreatePluginManifestInputsInner{*openapiclient.NewCreatePluginManifestInputsInner("Key_example", "Label_example", false, false)}, []openapiclient.CreatePluginManifestMcpServersInner{*openapiclient.NewCreatePluginManifestMcpServersInner("Name_example", "Transport_example")}, "Name_example", float32(123), []openapiclient.CreatePluginManifestSkillsInner{*openapiclient.NewCreatePluginManifestSkillsInner([]openapiclient.CreatePluginManifestSkillsInnerFilesInner{*openapiclient.NewCreatePluginManifestSkillsInnerFilesInner("Content_example", "Path_example")}, "Slug_example")}, "Version_example"), []string{"ProjectIds_example"}) // CreatePlugin | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.InstallPlugin(context.Background()).CreatePlugin(createPlugin).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.InstallPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InstallPlugin`: PluginResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.InstallPlugin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInstallPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPlugin** | [**CreatePlugin**](CreatePlugin.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginResponse**](PluginResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPluginCatalog

> PluginCatalogResponse ListPluginCatalog(ctx).Search(search).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()

Browse official MCP Registry recipes

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
	search := "search_example" // string | Registry search text. (optional)
	cursor := "cursor_example" // string | Opaque next cursor paired with the same search. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.ListPluginCatalog(context.Background()).Search(search).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.ListPluginCatalog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPluginCatalog`: PluginCatalogResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.ListPluginCatalog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPluginCatalogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **search** | **string** | Registry search text. | 
 **cursor** | **string** | Opaque next cursor paired with the same search. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginCatalogResponse**](PluginCatalogResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPlugins

> PluginListResponse ListPlugins(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()

List installed workspace plugins

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
	projectId := "projectId_example" // string | Only enabled plugins available to this project. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.ListPlugins(context.Background()).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.ListPlugins``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPlugins`: PluginListResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.ListPlugins`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPluginsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Only enabled plugins available to this project. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginListResponse**](PluginListResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreviewPlugin

> PluginPreviewResponse PreviewPlugin(ctx).PreviewPlugin(previewPlugin).XOrganizationId(xOrganizationId).Execute()

Validate a plugin manifest without installing

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
	previewPlugin := *openapiclient.NewPreviewPlugin(*openapiclient.NewCreatePluginManifest("Description_example", "Id_example", []openapiclient.CreatePluginManifestInputsInner{*openapiclient.NewCreatePluginManifestInputsInner("Key_example", "Label_example", false, false)}, []openapiclient.CreatePluginManifestMcpServersInner{*openapiclient.NewCreatePluginManifestMcpServersInner("Name_example", "Transport_example")}, "Name_example", float32(123), []openapiclient.CreatePluginManifestSkillsInner{*openapiclient.NewCreatePluginManifestSkillsInner([]openapiclient.CreatePluginManifestSkillsInnerFilesInner{*openapiclient.NewCreatePluginManifestSkillsInnerFilesInner("Content_example", "Path_example")}, "Slug_example")}, "Version_example")) // PreviewPlugin | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.PreviewPlugin(context.Background()).PreviewPlugin(previewPlugin).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.PreviewPlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreviewPlugin`: PluginPreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.PreviewPlugin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPreviewPluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **previewPlugin** | [**PreviewPlugin**](PreviewPlugin.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginPreviewResponse**](PluginPreviewResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemovePlugin

> PluginRemoveResponse RemovePlugin(ctx, id).XOrganizationId(xOrganizationId).Execute()

Remove a plugin from subsequent runs

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
	resp, r, err := apiClient.PluginsAPI.RemovePlugin(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.RemovePlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePlugin`: PluginRemoveResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.RemovePlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemovePluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginRemoveResponse**](PluginRemoveResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePlugin

> PluginResponse UpdatePlugin(ctx, id).UpdatePlugin(updatePlugin).XOrganizationId(xOrganizationId).Execute()

Update plugin setup, version or project availability

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
	updatePlugin := *openapiclient.NewUpdatePlugin() // UpdatePlugin | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PluginsAPI.UpdatePlugin(context.Background(), id).UpdatePlugin(updatePlugin).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PluginsAPI.UpdatePlugin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePlugin`: PluginResponse
	fmt.Fprintf(os.Stdout, "Response from `PluginsAPI.UpdatePlugin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePluginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePlugin** | [**UpdatePlugin**](UpdatePlugin.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PluginResponse**](PluginResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

