# CyclesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddCycleTask**](CyclesAPI.md#addcycletask) | **Post** /v1/api/cycles/{id}/tasks | Add a task to a cycle
[**AssignCycle**](CyclesAPI.md#assigncycle) | **Patch** /v1/api/cycles/{id}/assign | Hand a cycle to a teammate
[**ContinueBranchCycle**](CyclesAPI.md#continuebranchcycle) | **Post** /v1/api/cycles/{id}/continue | Admit a branch cycle once its branch is at the pushed commit
[**CreateCycleReviewComment**](CyclesAPI.md#createcyclereviewcomment) | **Post** /v1/api/cycles/{id}/review/comments | Comment on a cycle&#39;s review
[**CreateDirectCycle**](CyclesAPI.md#createdirectcycle) | **Post** /v1/api/cycles/direct | Create a separate cycle
[**DeleteCycle**](CyclesAPI.md#deletecycle) | **Delete** /v1/api/cycles/{id} | Delete a draft or failed cycle
[**DeleteCycleTask**](CyclesAPI.md#deletecycletask) | **Delete** /v1/api/cycles/{id}/tasks/{taskId} | Remove a task from a cycle
[**ExecuteCycle**](CyclesAPI.md#executecycle) | **Post** /v1/api/cycles/{id}/execute | Run a cycle&#39;s lifecycle
[**GetCycle**](CyclesAPI.md#getcycle) | **Get** /v1/api/cycles/{id} | Get one cycle with its tasks
[**GetCycleArtifactUrl**](CyclesAPI.md#getcycleartifacturl) | **Get** /v1/api/cycles/{id}/artifacts/{filename} | Get a signed download URL for one cycle artifact
[**GetCycleE2eReport**](CyclesAPI.md#getcyclee2ereport) | **Get** /v1/api/cycles/{id}/e2e | The cycle&#39;s user-side verification: journeys, outcomes and evidence keys
[**GetCycleReviewEvidence**](CyclesAPI.md#getcyclereviewevidence) | **Get** /v1/api/cycles/{id}/review | Get the verified review evidence for a cycle
[**GetCycleTimeline**](CyclesAPI.md#getcycletimeline) | **Get** /v1/api/cycles/{id}/timeline | List a cycle&#39;s events plus its tasks&#39;
[**GetCycleUsage**](CyclesAPI.md#getcycleusage) | **Get** /v1/api/cycles/{id}/usage | Get the cycle&#39;s cost and token roll-up
[**ListCycleApprovals**](CyclesAPI.md#listcycleapprovals) | **Get** /v1/api/cycles/{id}/approvals | List a cycle&#39;s approvals
[**ListCycleArtifacts**](CyclesAPI.md#listcycleartifacts) | **Get** /v1/api/cycles/{id}/artifacts | List a cycle&#39;s stored artifacts
[**ListCycleEvents**](CyclesAPI.md#listcycleevents) | **Get** /v1/api/cycles/{id}/events | List a cycle&#39;s own events
[**ListCycleMessages**](CyclesAPI.md#listcyclemessages) | **Get** /v1/api/cycles/{id}/messages | Read a cycle&#39;s conversation
[**ListCycleReviewComments**](CyclesAPI.md#listcyclereviewcomments) | **Get** /v1/api/cycles/{id}/review/comments | List the review comments on a cycle
[**ListCycles**](CyclesAPI.md#listcycles) | **Get** /v1/api/cycles | List cycles
[**OpenBranchCycle**](CyclesAPI.md#openbranchcycle) | **Post** /v1/api/cycles/from-branch | Open a cycle from a pushed branch
[**RequestCycleRevision**](CyclesAPI.md#requestcyclerevision) | **Post** /v1/api/cycles/{id}/review/request-revision | Ask the cycle&#39;s build agent to address the open comments
[**SendCycleMessage**](CyclesAPI.md#sendcyclemessage) | **Post** /v1/api/cycles/{id}/messages | Send a message to a cycle&#39;s coder
[**StopCycle**](CyclesAPI.md#stopcycle) | **Post** /v1/api/cycles/{id}/stop | Stop a running cycle
[**SubmitRequest**](CyclesAPI.md#submitrequest) | **Post** /v1/api/requests | Submit a request
[**UpdateCycle**](CyclesAPI.md#updatecycle) | **Patch** /v1/api/cycles/{id} | Update a cycle&#39;s title, description or target branch
[**UpdateCycleReviewComment**](CyclesAPI.md#updatecyclereviewcomment) | **Patch** /v1/api/cycles/{id}/review/comments/{commentId} | Resolve or reopen a cycle review comment
[**UpdateCycleTask**](CyclesAPI.md#updatecycletask) | **Patch** /v1/api/cycles/{id}/tasks/{taskId} | Update a task inside a cycle



## AddCycleTask

> Task AddCycleTask(ctx, id).CreateCycleTask(createCycleTask).XOrganizationId(xOrganizationId).Execute()

Add a task to a cycle

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
	var createCycleTask openapiclient.CreateCycleTask
	if err := json.Unmarshal([]byte("{\"description\":\"text\",\"title\":\"text\"}"), &createCycleTask); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.AddCycleTask(ctx, id).CreateCycleTask(createCycleTask).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.AddCycleTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddCycleTask`: Task
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.AddCycleTask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiAddCycleTaskRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createCycleTask** | [**CreateCycleTask**](CreateCycleTask.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Task**](Task.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AssignCycle

> Cycle AssignCycle(ctx, id).Assign(assign).XOrganizationId(xOrganizationId).Execute()

Hand a cycle to a teammate

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
	var assign openapiclient.Assign
	if err := json.Unmarshal([]byte("{\"userId\":\"text\"}"), &assign); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.AssignCycle(ctx, id).Assign(assign).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.AssignCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AssignCycle`: Cycle
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.AssignCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiAssignCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assign** | [**Assign**](Assign.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Cycle**](Cycle.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ContinueBranchCycle

> BranchCycleOpened ContinueBranchCycle(ctx, id).XOrganizationId(xOrganizationId).Execute()

Admit a branch cycle once its branch is at the pushed commit

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
	resp, r, err := apiClient.CyclesAPI.ContinueBranchCycle(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ContinueBranchCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ContinueBranchCycle`: BranchCycleOpened
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ContinueBranchCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiContinueBranchCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**BranchCycleOpened**](BranchCycleOpened.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCycleReviewComment

> ReviewComment CreateCycleReviewComment(ctx, id).CreateReviewComment(createReviewComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Comment on a cycle's review

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
	var createReviewComment openapiclient.CreateReviewComment
	if err := json.Unmarshal([]byte("{\"body\":\"text\",\"headSha\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\"}"), &createReviewComment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.CreateCycleReviewComment(ctx, id).CreateReviewComment(createReviewComment).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.CreateCycleReviewComment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCycleReviewComment`: ReviewComment
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.CreateCycleReviewComment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCreateCycleReviewCommentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createReviewComment** | [**CreateReviewComment**](CreateReviewComment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ReviewComment**](ReviewComment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDirectCycle

> Cycle CreateDirectCycle(ctx).DirectCycle(directCycle).XOrganizationId(xOrganizationId).Execute()

Create a separate cycle

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
	ctx := context.Background()
	var directCycle openapiclient.DirectCycle
	if err := json.Unmarshal([]byte("{\"description\":\"text\",\"projectId\":\"123e4567-e89b-42d3-a456-426614174000\",\"title\":\"text\"}"), &directCycle); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	configuration.AddDefaultHeader("Cookie", os.Getenv("HLIX_SESSION_COOKIE"))
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.CreateDirectCycle(ctx).DirectCycle(directCycle).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.CreateDirectCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDirectCycle`: Cycle
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.CreateDirectCycle`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateDirectCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **directCycle** | [**DirectCycle**](DirectCycle.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Cycle**](Cycle.md)

### Authorization

Signed-in user session; API keys are not accepted. Set `HLIX_SESSION_COOKIE` to the complete issued Cookie header.

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCycle

> MessageAck DeleteCycle(ctx, id).XOrganizationId(xOrganizationId).Execute()

Delete a draft or failed cycle

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
	resp, r, err := apiClient.CyclesAPI.DeleteCycle(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.DeleteCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCycle`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.DeleteCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteCycleRequest` request builder.


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


## DeleteCycleTask

> MessageAck DeleteCycleTask(ctx, id, taskId).XOrganizationId(xOrganizationId).Execute()

Remove a task from a cycle

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
	taskId := "taskId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.DeleteCycleTask(ctx, id, taskId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.DeleteCycleTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCycleTask`: MessageAck
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.DeleteCycleTask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**taskId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiDeleteCycleTaskRequest` request builder.


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


## ExecuteCycle

> CycleExecutionStarted ExecuteCycle(ctx, id).Mode(mode).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Run a cycle's lifecycle

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
	mode := "mode_example" // string | `machine` (default) or `desktop`. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.ExecuteCycle(ctx, id).Mode(mode).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ExecuteCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExecuteCycle`: CycleExecutionStarted
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ExecuteCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiExecuteCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mode** | **string** | &#x60;machine&#x60; (default) or &#x60;desktop&#x60;. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CycleExecutionStarted**](CycleExecutionStarted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCycle

> CycleDetail GetCycle(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one cycle with its tasks

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
	resp, r, err := apiClient.CyclesAPI.GetCycle(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.GetCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCycle`: CycleDetail
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.GetCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CycleDetail**](CycleDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCycleArtifactUrl

> SignedArtifactUrl GetCycleArtifactUrl(ctx, id, filename).Download(download).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get a signed download URL for one cycle artifact

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
	filename := "filename_example" // string |
	download := "download_example" // string | Set to `1` to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with `download=1` in its `url`. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.GetCycleArtifactUrl(ctx, id, filename).Download(download).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.GetCycleArtifactUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCycleArtifactUrl`: SignedArtifactUrl
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.GetCycleArtifactUrl`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**filename** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCycleArtifactUrlRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Set to &#x60;1&#x60; to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with &#x60;download&#x3D;1&#x60; in its &#x60;url&#x60;. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCycleE2eReport

> CycleE2eReport GetCycleE2eReport(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

The cycle's user-side verification: journeys, outcomes and evidence keys

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
	resp, r, err := apiClient.CyclesAPI.GetCycleE2eReport(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.GetCycleE2eReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCycleE2eReport`: CycleE2eReport
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.GetCycleE2eReport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCycleE2eReportRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CycleE2eReport**](CycleE2eReport.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCycleReviewEvidence

> CycleReviewEvidence GetCycleReviewEvidence(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the verified review evidence for a cycle

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
	resp, r, err := apiClient.CyclesAPI.GetCycleReviewEvidence(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.GetCycleReviewEvidence``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCycleReviewEvidence`: CycleReviewEvidence
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.GetCycleReviewEvidence`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCycleReviewEvidenceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CycleReviewEvidence**](CycleReviewEvidence.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCycleTimeline

> []ActivityEvent GetCycleTimeline(ctx, id).XOrganizationId(xOrganizationId).Execute()

List a cycle's events plus its tasks'

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
	resp, r, err := apiClient.CyclesAPI.GetCycleTimeline(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.GetCycleTimeline``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCycleTimeline`: []ActivityEvent
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.GetCycleTimeline`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCycleTimelineRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ActivityEvent**](ActivityEvent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCycleUsage

> AgentUsageRollup GetCycleUsage(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get the cycle's cost and token roll-up

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
	resp, r, err := apiClient.CyclesAPI.GetCycleUsage(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.GetCycleUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCycleUsage`: AgentUsageRollup
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.GetCycleUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetCycleUsageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AgentUsageRollup**](AgentUsageRollup.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycleApprovals

> []Approval ListCycleApprovals(ctx, id).XOrganizationId(xOrganizationId).Execute()

List a cycle's approvals

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
	resp, r, err := apiClient.CyclesAPI.ListCycleApprovals(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ListCycleApprovals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycleApprovals`: []Approval
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ListCycleApprovals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListCycleApprovalsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]Approval**](Approval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycleArtifacts

> []StoredArtifact ListCycleArtifacts(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List a cycle's stored artifacts

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
	resp, r, err := apiClient.CyclesAPI.ListCycleArtifacts(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ListCycleArtifacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycleArtifacts`: []StoredArtifact
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ListCycleArtifacts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListCycleArtifactsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]StoredArtifact**](StoredArtifact.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycleEvents

> []ActivityEvent ListCycleEvents(ctx, id).XOrganizationId(xOrganizationId).Execute()

List a cycle's own events

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
	resp, r, err := apiClient.CyclesAPI.ListCycleEvents(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ListCycleEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycleEvents`: []ActivityEvent
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ListCycleEvents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListCycleEventsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]ActivityEvent**](ActivityEvent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycleMessages

> []WireMessage ListCycleMessages(ctx, id).AgentId(agentId).Limit(limit).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read a cycle's conversation

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
	agentId := "agentId_example" // string | Read this agent's thread instead of the cycle's. (optional)
	limit := "limit_example" // string | Return only the newest this many messages (1–200). Omit for the full transcript. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.ListCycleMessages(ctx, id).AgentId(agentId).Limit(limit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ListCycleMessages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycleMessages`: []WireMessage
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ListCycleMessages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListCycleMessagesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **agentId** | **string** | Read this agent&#39;s thread instead of the cycle&#39;s. |
 **limit** | **string** | Return only the newest this many messages (1–200). Omit for the full transcript. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]WireMessage**](WireMessage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycleReviewComments

> ReviewCommentList ListCycleReviewComments(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List the review comments on a cycle

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
	resp, r, err := apiClient.CyclesAPI.ListCycleReviewComments(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ListCycleReviewComments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycleReviewComments`: ReviewCommentList
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ListCycleReviewComments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiListCycleReviewCommentsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ReviewCommentList**](ReviewCommentList.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycles

> []CycleSummary ListCycles(ctx).ProjectId(projectId).AssignedUserId(assignedUserId).IncludeArchived(includeArchived).OrderBy(orderBy).Limit(limit).Before(before).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List cycles

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
	projectId := "projectId_example" // string | Limit results to the specified projects. Repeatable. Explicitly selected projects are included even when archived. (optional)
	assignedUserId := "assignedUserId_example" // string | Only cycles owned by this person. `me` resolves to the caller. (optional)
	includeArchived := "includeArchived_example" // string | `false` hides finished cycles (`done`, legacy `pr_created`, `failed` and `canceled`). Omit to include all statuses. (optional)
	orderBy := "orderBy_example" // string | `createdAt` (default, newest first) or `priority` (the Sources Agent's urgency tier first, ties keep createdAt order). (optional)
	limit := "limit_example" // string | Page size, 1–500; 200 when omitted. The list is always one page. (optional)
	before := "before_example" // string | The id of the last cycle of the previous page: the next, older page. Newest-first order only (not with `orderBy=priority`). Ask again with the last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.ListCycles(ctx).ProjectId(projectId).AssignedUserId(assignedUserId).IncludeArchived(includeArchived).OrderBy(orderBy).Limit(limit).Before(before).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.ListCycles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycles`: []CycleSummary
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.ListCycles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListCyclesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Limit results to the specified projects. Repeatable. Explicitly selected projects are included even when archived. |
 **assignedUserId** | **string** | Only cycles owned by this person. &#x60;me&#x60; resolves to the caller. |
 **includeArchived** | **string** | &#x60;false&#x60; hides finished cycles (&#x60;done&#x60;, legacy &#x60;pr_created&#x60;, &#x60;failed&#x60; and &#x60;canceled&#x60;). Omit to include all statuses. |
 **orderBy** | **string** | &#x60;createdAt&#x60; (default, newest first) or &#x60;priority&#x60; (the Sources Agent&#39;s urgency tier first, ties keep createdAt order). |
 **limit** | **string** | Page size, 1–500; 200 when omitted. The list is always one page. |
 **before** | **string** | The id of the last cycle of the previous page: the next, older page. Newest-first order only (not with &#x60;orderBy&#x3D;priority&#x60;). Ask again with the last id until a page comes back shorter than &#x60;limit&#x60;. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]CycleSummary**](CycleSummary.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OpenBranchCycle

> BranchCycleOpened OpenBranchCycle(ctx).OpenBranchCycle(openBranchCycle).XOrganizationId(xOrganizationId).Execute()

Open a cycle from a pushed branch

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
	var openBranchCycle openapiclient.OpenBranchCycle
	if err := json.Unmarshal([]byte("{\"branch\":\"text\",\"commit\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\",\"projectId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &openBranchCycle); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.OpenBranchCycle(ctx).OpenBranchCycle(openBranchCycle).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.OpenBranchCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OpenBranchCycle`: BranchCycleOpened
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.OpenBranchCycle`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiOpenBranchCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **openBranchCycle** | [**OpenBranchCycle**](OpenBranchCycle.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**BranchCycleOpened**](BranchCycleOpened.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestCycleRevision

> ReviewRevisionRequest RequestCycleRevision(ctx, id).RequestRevision(requestRevision).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Ask the cycle's build agent to address the open comments

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
	var requestRevision openapiclient.RequestRevision
	if err := json.Unmarshal([]byte("{\"headSha\":\"aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa\"}"), &requestRevision); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.RequestCycleRevision(ctx, id).RequestRevision(requestRevision).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.RequestCycleRevision``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestCycleRevision`: ReviewRevisionRequest
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.RequestCycleRevision`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiRequestCycleRevisionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **requestRevision** | [**RequestRevision**](RequestRevision.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ReviewRevisionRequest**](ReviewRevisionRequest.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendCycleMessage

> CycleTurn SendCycleMessage(ctx, id).CycleMessage(cycleMessage).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Send a message to a cycle's coder

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
	var cycleMessage openapiclient.CycleMessage
	if err := json.Unmarshal([]byte("{\"content\":\"text\"}"), &cycleMessage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.SendCycleMessage(ctx, id).CycleMessage(cycleMessage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.SendCycleMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendCycleMessage`: CycleTurn
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.SendCycleMessage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSendCycleMessageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cycleMessage** | [**CycleMessage**](CycleMessage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CycleTurn**](CycleTurn.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StopCycle

> CycleStopped StopCycle(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Stop a running cycle

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
	resp, r, err := apiClient.CyclesAPI.StopCycle(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.StopCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StopCycle`: CycleStopped
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.StopCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiStopCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**CycleStopped**](CycleStopped.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubmitRequest

> RequestSubmitted SubmitRequest(ctx).CreateCycle(createCycle).XOrganizationId(xOrganizationId).Execute()

Submit a request

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
	var createCycle openapiclient.CreateCycle
	if err := json.Unmarshal([]byte("{\"description\":\"text\",\"projectId\":\"123e4567-e89b-42d3-a456-426614174000\",\"title\":\"text\"}"), &createCycle); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.SubmitRequest(ctx).CreateCycle(createCycle).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.SubmitRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubmitRequest`: RequestSubmitted
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.SubmitRequest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiSubmitRequestRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCycle** | [**CreateCycle**](CreateCycle.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**RequestSubmitted**](RequestSubmitted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCycle

> Cycle UpdateCycle(ctx, id).UpdateCycle(updateCycle).XOrganizationId(xOrganizationId).Execute()

Update a cycle's title, description or target branch

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
	var updateCycle openapiclient.UpdateCycle
	if err := json.Unmarshal([]byte("{}"), &updateCycle); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.UpdateCycle(ctx, id).UpdateCycle(updateCycle).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.UpdateCycle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCycle`: Cycle
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.UpdateCycle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateCycleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCycle** | [**UpdateCycle**](UpdateCycle.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Cycle**](Cycle.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCycleReviewComment

> ReviewComment UpdateCycleReviewComment(ctx, id, commentId).UpdateReviewComment(updateReviewComment).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Resolve or reopen a cycle review comment

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
	commentId := "commentId_example" // string |
	var updateReviewComment openapiclient.UpdateReviewComment
	if err := json.Unmarshal([]byte("{\"resolution\":\"open\"}"), &updateReviewComment); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.UpdateCycleReviewComment(ctx, id, commentId).UpdateReviewComment(updateReviewComment).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.UpdateCycleReviewComment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCycleReviewComment`: ReviewComment
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.UpdateCycleReviewComment`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**commentId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateCycleReviewCommentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateReviewComment** | [**UpdateReviewComment**](UpdateReviewComment.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ReviewComment**](ReviewComment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCycleTask

> Task UpdateCycleTask(ctx, id, taskId).UpdateCycleTask(updateCycleTask).XOrganizationId(xOrganizationId).Execute()

Update a task inside a cycle

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
	taskId := "taskId_example" // string |
	var updateCycleTask openapiclient.UpdateCycleTask
	if err := json.Unmarshal([]byte("{}"), &updateCycleTask); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CyclesAPI.UpdateCycleTask(ctx, id, taskId).UpdateCycleTask(updateCycleTask).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CyclesAPI.UpdateCycleTask``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCycleTask`: Task
	fmt.Fprintf(os.Stdout, "Response from `CyclesAPI.UpdateCycleTask`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |
**taskId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiUpdateCycleTaskRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateCycleTask** | [**UpdateCycleTask**](UpdateCycleTask.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Task**](Task.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

