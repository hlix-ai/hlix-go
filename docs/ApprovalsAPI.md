# ApprovalsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AskClientQuestion**](ApprovalsAPI.md#askclientquestion) | **Post** /v1/api/approvals/client-question | Ask the customer a question
[**CancelApproval**](ApprovalsAPI.md#cancelapproval) | **Post** /v1/api/approvals/{id}/cancel | Cancel a request nobody will decide
[**GetApproval**](ApprovalsAPI.md#getapproval) | **Get** /v1/api/approvals/{id} | Get one request
[**ListApprovals**](ApprovalsAPI.md#listapprovals) | **Get** /v1/api/approvals | List requests awaiting a decision
[**ResolveApproval**](ApprovalsAPI.md#resolveapproval) | **Post** /v1/api/approvals/{id}/resolve | Approve or deny a request



## AskClientQuestion

> Approval AskClientQuestion(ctx).AskClientQuestion(askClientQuestion).XOrganizationId(xOrganizationId).Execute()

Ask the customer a question

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
	var askClientQuestion openapiclient.AskClientQuestion
	if err := json.Unmarshal([]byte("{\"cycleId\":\"text\",\"question\":\"text\",\"title\":\"text\"}"), &askClientQuestion); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovalsAPI.AskClientQuestion(ctx).AskClientQuestion(askClientQuestion).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovalsAPI.AskClientQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AskClientQuestion`: Approval
	fmt.Fprintf(os.Stdout, "Response from `ApprovalsAPI.AskClientQuestion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiAskClientQuestionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **askClientQuestion** | [**AskClientQuestion**](AskClientQuestion.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Approval**](Approval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelApproval

> Approval CancelApproval(ctx, id).XOrganizationId(xOrganizationId).Execute()

Cancel a request nobody will decide

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
	resp, r, err := apiClient.ApprovalsAPI.CancelApproval(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovalsAPI.CancelApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelApproval`: Approval
	fmt.Fprintf(os.Stdout, "Response from `ApprovalsAPI.CancelApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiCancelApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Approval**](Approval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetApproval

> Approval GetApproval(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one request

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
	resp, r, err := apiClient.ApprovalsAPI.GetApproval(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovalsAPI.GetApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetApproval`: Approval
	fmt.Fprintf(os.Stdout, "Response from `ApprovalsAPI.GetApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**Approval**](Approval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListApprovals

> []ApprovalListItem ListApprovals(ctx).Status(status).CycleId(cycleId).TaskId(taskId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List requests awaiting a decision

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
	status := "status_example" // string | `pending` | `approved` | `denied` | `cancelled`. Omitted, every status is listed. (optional)
	cycleId := "cycleId_example" // string | Only requests raised against this cycle. (optional)
	taskId := "taskId_example" // string | Only requests raised against this task. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovalsAPI.ListApprovals(ctx).Status(status).CycleId(cycleId).TaskId(taskId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovalsAPI.ListApprovals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListApprovals`: []ApprovalListItem
	fmt.Fprintf(os.Stdout, "Response from `ApprovalsAPI.ListApprovals`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListApprovalsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** | &#x60;pending&#x60; | &#x60;approved&#x60; | &#x60;denied&#x60; | &#x60;cancelled&#x60;. Omitted, every status is listed. |
 **cycleId** | **string** | Only requests raised against this cycle. |
 **taskId** | **string** | Only requests raised against this task. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]ApprovalListItem**](ApprovalListItem.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveApproval

> Approval ResolveApproval(ctx, id).ResolveApproval(resolveApproval).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Approve or deny a request

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
	var resolveApproval openapiclient.ResolveApproval
	if err := json.Unmarshal([]byte("{\"status\":\"approved\"}"), &resolveApproval); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ApprovalsAPI.ResolveApproval(ctx, id).ResolveApproval(resolveApproval).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ApprovalsAPI.ResolveApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveApproval`: Approval
	fmt.Fprintf(os.Stdout, "Response from `ApprovalsAPI.ResolveApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiResolveApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resolveApproval** | [**ResolveApproval**](ResolveApproval.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**Approval**](Approval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

