# \ToolsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CallTool**](ToolsAPI.md#CallTool) | **Post** /v1/api/tools/{toolId}/call | Create or revisit a durable tool invocation
[**DescribeTool**](ToolsAPI.md#DescribeTool) | **Get** /v1/api/tools/{toolId} | Read the accepted input schema and execution policy
[**GetToolCall**](ToolsAPI.md#GetToolCall) | **Get** /v1/api/tool-calls/{callId} | Read a persisted tool result and cost status
[**GetToolConnection**](ToolsAPI.md#GetToolConnection) | **Get** /v1/api/tools/connections/treg | Read safe Treg connection state
[**ListToolCalls**](ToolsAPI.md#ListToolCalls) | **Get** /v1/api/tool-calls | List recent workspace tool invocations
[**RemoveToolConnection**](ToolsAPI.md#RemoveToolConnection) | **Delete** /v1/api/tools/connections/treg | Remove a workspace Treg connection
[**SaveToolConnection**](ToolsAPI.md#SaveToolConnection) | **Put** /v1/api/tools/connections/treg | Save a workspace Treg connection
[**SearchTools**](ToolsAPI.md#SearchTools) | **Get** /v1/api/tools | Search available tools and inspect funding readiness



## CallTool

> ToolCall CallTool(ctx, toolId).ToolCallInput(toolCallInput).XOrganizationId(xOrganizationId).Execute()

Create or revisit a durable tool invocation

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
	toolId := "toolId_example" // string | 
	toolCallInput := *openapiclient.NewToolCallInput("IdempotencyKey_example", map[string]interface{}{"key": interface{}(123)}) // ToolCallInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.CallTool(context.Background(), toolId).ToolCallInput(toolCallInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.CallTool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CallTool`: ToolCall
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.CallTool`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**toolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCallToolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **toolCallInput** | [**ToolCallInput**](ToolCallInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolCall**](ToolCall.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DescribeTool

> ToolDescriptor DescribeTool(ctx, toolId).XOrganizationId(xOrganizationId).Execute()

Read the accepted input schema and execution policy

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
	toolId := "toolId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.DescribeTool(context.Background(), toolId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.DescribeTool``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DescribeTool`: ToolDescriptor
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.DescribeTool`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**toolId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDescribeToolRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolDescriptor**](ToolDescriptor.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetToolCall

> ToolCall GetToolCall(ctx, callId).XOrganizationId(xOrganizationId).Execute()

Read a persisted tool result and cost status

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
	callId := "callId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.GetToolCall(context.Background(), callId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.GetToolCall``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetToolCall`: ToolCall
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.GetToolCall`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**callId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetToolCallRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolCall**](ToolCall.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetToolConnection

> ToolConnection GetToolConnection(ctx).XOrganizationId(xOrganizationId).Execute()

Read safe Treg connection state

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
	resp, r, err := apiClient.ToolsAPI.GetToolConnection(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.GetToolConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetToolConnection`: ToolConnection
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.GetToolConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetToolConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolConnection**](ToolConnection.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListToolCalls

> ToolCallList ListToolCalls(ctx).ProjectId(projectId).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()

List recent workspace tool invocations

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
	projectId := "projectId_example" // string | Filter by project. (optional)
	limit := "limit_example" // string | 1–100, defaults to 30. (optional)
	cursor := "cursor_example" // string | Opaque nextCursor from the previous page. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.ListToolCalls(context.Background()).ProjectId(projectId).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.ListToolCalls``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListToolCalls`: ToolCallList
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.ListToolCalls`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListToolCallsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Filter by project. | 
 **limit** | **string** | 1–100, defaults to 30. | 
 **cursor** | **string** | Opaque nextCursor from the previous page. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolCallList**](ToolCallList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveToolConnection

> ToolConnection RemoveToolConnection(ctx).XOrganizationId(xOrganizationId).Execute()

Remove a workspace Treg connection

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
	resp, r, err := apiClient.ToolsAPI.RemoveToolConnection(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.RemoveToolConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveToolConnection`: ToolConnection
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.RemoveToolConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRemoveToolConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolConnection**](ToolConnection.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveToolConnection

> ToolConnection SaveToolConnection(ctx).SaveToolConnection(saveToolConnection).XOrganizationId(xOrganizationId).Execute()

Save a workspace Treg connection

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
	saveToolConnection := *openapiclient.NewSaveToolConnection("ApiKey_example", "OrganizationId_example") // SaveToolConnection | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.SaveToolConnection(context.Background()).SaveToolConnection(saveToolConnection).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.SaveToolConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveToolConnection`: ToolConnection
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.SaveToolConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSaveToolConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveToolConnection** | [**SaveToolConnection**](SaveToolConnection.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolConnection**](ToolConnection.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchTools

> ToolSearchResult SearchTools(ctx).Query(query).Provider(provider).Limit(limit).XOrganizationId(xOrganizationId).Execute()

Search available tools and inspect funding readiness

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
	query := "query_example" // string | Search text, up to 500 characters. (optional)
	provider := "provider_example" // string | Provider filter. (optional)
	limit := "limit_example" // string | 1–100, defaults to 30. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.SearchTools(context.Background()).Query(query).Provider(provider).Limit(limit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ToolsAPI.SearchTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchTools`: ToolSearchResult
	fmt.Fprintf(os.Stdout, "Response from `ToolsAPI.SearchTools`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchToolsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Search text, up to 500 characters. | 
 **provider** | **string** | Provider filter. | 
 **limit** | **string** | 1–100, defaults to 30. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ToolSearchResult**](ToolSearchResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

