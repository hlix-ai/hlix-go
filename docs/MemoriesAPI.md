# MemoriesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMemory**](MemoriesAPI.md#creatememory) | **Post** /v1/api/memories | Write a memory
[**DeleteMemory**](MemoriesAPI.md#deletememory) | **Delete** /v1/api/memories/{id} | Delete a memory
[**ExtractCycleMemories**](MemoriesAPI.md#extractcyclememories) | **Post** /v1/api/memories/extract/{cycleId} | Extract memories from a finished cycle
[**GetMemory**](MemoriesAPI.md#getmemory) | **Get** /v1/api/memories/{id} | Get one memory
[**GetProjectKnowledge**](MemoriesAPI.md#getprojectknowledge) | **Get** /v1/api/memories/project/{projectId} | Read learned knowledge and recording availability for one project
[**ListMemories**](MemoriesAPI.md#listmemories) | **Get** /v1/api/memories | List the workspace&#39;s memories
[**SearchMemories**](MemoriesAPI.md#searchmemories) | **Get** /v1/api/memories/search/{scope}/{scopeId} | Search one scope by meaning
[**UpdateMemory**](MemoriesAPI.md#updatememory) | **Patch** /v1/api/memories/{id} | Update a memory



## CreateMemory

> Memory CreateMemory(ctx).CreateMemory(createMemory).XOrganizationId(xOrganizationId).Execute()

Write a memory

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
	var createMemory openapiclient.CreateMemory
	if err := json.Unmarshal([]byte("{\"category\":\"convention\",\"key\":\"text\",\"scope\":\"org\",\"scopeId\":\"text\",\"value\":\"text\"}"), &createMemory); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.CreateMemory(ctx).CreateMemory(createMemory).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.CreateMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMemory`: Memory
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.CreateMemory`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateMemoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createMemory** | [**CreateMemory**](CreateMemory.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Memory**](Memory.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMemory

> MessageAck DeleteMemory(ctx, id).Scope(scope).ScopeId(scopeId).XOrganizationId(xOrganizationId).Execute()

Delete a memory

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
	scope := "scope_example" // string | `org` | `project` | `cycle` | `task` | `agent`. (optional)
	scopeId := "scopeId_example" // string | The scoped entity's id. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.DeleteMemory(ctx, id).Scope(scope).ScopeId(scopeId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.DeleteMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteMemory`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.DeleteMemory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteMemoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **scope** | **string** | &#x60;org&#x60; | &#x60;project&#x60; | &#x60;cycle&#x60; | &#x60;task&#x60; | &#x60;agent&#x60;. |
 **scopeId** | **string** | The scoped entity&#39;s id. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExtractCycleMemories

> MessageAck ExtractCycleMemories(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()

Extract memories from a finished cycle

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
	cycleId := "cycleId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.ExtractCycleMemories(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.ExtractCycleMemories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExtractCycleMemories`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.ExtractCycleMemories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiExtractCycleMemoriesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MessageAck**](MessageAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMemory

> Memory GetMemory(ctx, id).Scope(scope).ScopeId(scopeId).XOrganizationId(xOrganizationId).Execute()

Get one memory

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
	scope := "scope_example" // string | `org` | `project` | `cycle` | `task` | `agent`. (optional)
	scopeId := "scopeId_example" // string | The scoped entity's id. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.GetMemory(ctx, id).Scope(scope).ScopeId(scopeId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.GetMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMemory`: Memory
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.GetMemory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetMemoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **scope** | **string** | &#x60;org&#x60; | &#x60;project&#x60; | &#x60;cycle&#x60; | &#x60;task&#x60; | &#x60;agent&#x60;. |
 **scopeId** | **string** | The scoped entity&#39;s id. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Memory**](Memory.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetProjectKnowledge

> ProjectKnowledge GetProjectKnowledge(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Read learned knowledge and recording availability for one project

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
	projectId := "projectId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.GetProjectKnowledge(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.GetProjectKnowledge``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectKnowledge`: ProjectKnowledge
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.GetProjectKnowledge`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectKnowledgeRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ProjectKnowledge**](ProjectKnowledge.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListMemories

> []Memory ListMemories(ctx).Scope(scope).ScopeId(scopeId).Status(status).Q(q).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

List the workspace's memories

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
	scope := "scope_example" // string | `org` | `project` | `cycle` | `task` | `agent`. (optional)
	scopeId := "scopeId_example" // string | The scoped entity's id. (optional)
	status := "status_example" // string | `tentative` | `approved` | `archived`. (optional)
	q := "q_example" // string | Filter memory text by substring. For semantic search with similarity scores, use `/memories/search/{scope}/{scopeId}`. (optional)
	limit := "limit_example" // string | Page size, clamped to 1–500; 100 when omitted or not an integer. (optional)
	offset := "offset_example" // string | Rows to skip. Ask for the next page with `offset` + `limit` until a page comes back shorter than `limit`. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.ListMemories(ctx).Scope(scope).ScopeId(scopeId).Status(status).Q(q).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.ListMemories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMemories`: []Memory
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.ListMemories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListMemoriesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **scope** | **string** | &#x60;org&#x60; | &#x60;project&#x60; | &#x60;cycle&#x60; | &#x60;task&#x60; | &#x60;agent&#x60;. |
 **scopeId** | **string** | The scoped entity&#39;s id. |
 **status** | **string** | &#x60;tentative&#x60; | &#x60;approved&#x60; | &#x60;archived&#x60;. |
 **q** | **string** | Filter memory text by substring. For semantic search with similarity scores, use &#x60;/memories/search/{scope}/{scopeId}&#x60;. |
 **limit** | **string** | Page size, clamped to 1–500; 100 when omitted or not an integer. |
 **offset** | **string** | Rows to skip. Ask for the next page with &#x60;offset&#x60; + &#x60;limit&#x60; until a page comes back shorter than &#x60;limit&#x60;. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]Memory**](Memory.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchMemories

> []Memory SearchMemories(ctx, scope, scopeId).Q(q).Status(status).Limit(limit).XOrganizationId(xOrganizationId).Execute()

Search one scope by meaning

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
	scope := "scope_example" // string |
	scopeId := "scopeId_example" // string |
	q := "q_example" // string | The text to rank against. Omitted, the scope's memories come back unranked. (optional)
	status := "status_example" // string | `tentative` | `approved` | `archived`. (optional)
	limit := "limit_example" // string | Page size, clamped to 1–500. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.SearchMemories(ctx, scope, scopeId).Q(q).Status(status).Limit(limit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.SearchMemories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchMemories`: []Memory
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.SearchMemories`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**scope** | **string** |  |
**scopeId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSearchMemoriesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **q** | **string** | The text to rank against. Omitted, the scope&#39;s memories come back unranked. |
 **status** | **string** | &#x60;tentative&#x60; | &#x60;approved&#x60; | &#x60;archived&#x60;. |
 **limit** | **string** | Page size, clamped to 1–500. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]Memory**](Memory.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMemory

> Memory UpdateMemory(ctx, id).UpdateMemory(updateMemory).Scope(scope).ScopeId(scopeId).XOrganizationId(xOrganizationId).Execute()

Update a memory

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
	var updateMemory openapiclient.UpdateMemory
	if err := json.Unmarshal([]byte("{}"), &updateMemory); err != nil {
		panic(err)
	}
	scope := "scope_example" // string | `org` | `project` | `cycle` | `task` | `agent`. (optional)
	scopeId := "scopeId_example" // string | The scoped entity's id. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MemoriesAPI.UpdateMemory(ctx, id).UpdateMemory(updateMemory).Scope(scope).ScopeId(scopeId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MemoriesAPI.UpdateMemory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMemory`: Memory
	fmt.Fprintf(os.Stdout, "Response from `MemoriesAPI.UpdateMemory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateMemoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateMemory** | [**UpdateMemory**](UpdateMemory.md) |  |
 **scope** | **string** | &#x60;org&#x60; | &#x60;project&#x60; | &#x60;cycle&#x60; | &#x60;task&#x60; | &#x60;agent&#x60;. |
 **scopeId** | **string** | The scoped entity&#39;s id. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Memory**](Memory.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

