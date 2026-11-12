# ToolsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CallTool**](ToolsAPI.md#calltool) | **Post** /v1/api/tools/{toolId}/call | Create or revisit a durable tool invocation
[**DescribeTool**](ToolsAPI.md#describetool) | **Get** /v1/api/tools/{toolId} | Read the accepted input schema and execution policy
[**GetToolCall**](ToolsAPI.md#gettoolcall) | **Get** /v1/api/tool-calls/{callId} | Read a persisted tool result and cost status
[**GetToolConnection**](ToolsAPI.md#gettoolconnection) | **Get** /v1/api/tools/connections/treg | Read safe Treg connection state
[**ListToolCalls**](ToolsAPI.md#listtoolcalls) | **Get** /v1/api/tool-calls | List recent workspace tool invocations
[**RemoveToolConnection**](ToolsAPI.md#removetoolconnection) | **Delete** /v1/api/tools/connections/treg | Remove a workspace Treg connection
[**SaveToolConnection**](ToolsAPI.md#savetoolconnection) | **Put** /v1/api/tools/connections/treg | Save a workspace Treg connection
[**SearchTools**](ToolsAPI.md#searchtools) | **Get** /v1/api/tools | Search available tools and inspect funding readiness



## CallTool

> ToolCall CallTool(ctx, toolId).ToolCallInput(toolCallInput).XOrganizationId(xOrganizationId).Execute()

Create or revisit a durable tool invocation

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
	toolId := "toolId_example" // string |
	var toolCallInput openapiclient.ToolCallInput
	if err := json.Unmarshal([]byte("{\"idempotencyKey\":\"text\",\"input\":{\"key\":\"value\"}}"), &toolCallInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.CallTool(ctx, toolId).ToolCallInput(toolCallInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCallToolRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **toolCallInput** | [**ToolCallInput**](ToolCallInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolCall**](ToolCall.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	toolId := "toolId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.DescribeTool(ctx, toolId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDescribeToolRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolDescriptor**](ToolDescriptor.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	callId := "callId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.GetToolCall(ctx, callId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetToolCallRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolCall**](ToolCall.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ToolsAPI.GetToolConnection(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetToolConnectionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolConnection**](ToolConnection.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string | Filter by project. (optional)
	limit := "limit_example" // string | 1–100, defaults to 30. (optional)
	cursor := "cursor_example" // string | Opaque nextCursor from the previous page. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.ListToolCalls(ctx).ProjectId(projectId).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListToolCallsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Filter by project. |
 **limit** | **string** | 1–100, defaults to 30. |
 **cursor** | **string** | Opaque nextCursor from the previous page. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolCallList**](ToolCallList.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.ToolsAPI.RemoveToolConnection(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRemoveToolConnectionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolConnection**](ToolConnection.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var saveToolConnection openapiclient.SaveToolConnection
	if err := json.Unmarshal([]byte("{\"apiKey\":\"text\",\"organizationId\":\"123\"}"), &saveToolConnection); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.SaveToolConnection(ctx).SaveToolConnection(saveToolConnection).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSaveToolConnectionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **saveToolConnection** | [**SaveToolConnection**](SaveToolConnection.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolConnection**](ToolConnection.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	query := "query_example" // string | Search text, up to 500 characters. (optional)
	provider := "provider_example" // string | Provider filter. (optional)
	limit := "limit_example" // string | 1–100, defaults to 30. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ToolsAPI.SearchTools(ctx).Query(query).Provider(provider).Limit(limit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSearchToolsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Search text, up to 500 characters. |
 **provider** | **string** | Provider filter. |
 **limit** | **string** | 1–100, defaults to 30. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ToolSearchResult**](ToolSearchResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

