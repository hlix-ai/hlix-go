# ProjectCallsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HeartbeatProjectCall**](ProjectCallsAPI.md#heartbeatprojectcall) | **Put** /v1/api/projects/{projectId}/call/{participantId} | Keep the caller&#39;s place in the project&#39;s call
[**JoinProjectCall**](ProjectCallsAPI.md#joinprojectcall) | **Post** /v1/api/projects/{projectId}/call | Join the project&#39;s call
[**LeaveProjectCall**](ProjectCallsAPI.md#leaveprojectcall) | **Post** /v1/api/projects/{projectId}/call/{participantId}/leave | Leave the project&#39;s call



## HeartbeatProjectCall

> ProjectCallState HeartbeatProjectCall(ctx, projectId, participantId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Keep the caller's place in the project's call

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
	participantId := "participantId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectCallsAPI.HeartbeatProjectCall(ctx, projectId, participantId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectCallsAPI.HeartbeatProjectCall``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `HeartbeatProjectCall`: ProjectCallState
	fmt.Fprintf(os.Stdout, "Response from `ProjectCallsAPI.HeartbeatProjectCall`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**participantId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiHeartbeatProjectCallRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectCallState**](ProjectCallState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## JoinProjectCall

> ProjectCallJoin JoinProjectCall(ctx, projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Join the project's call

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
	resp, r, err := apiClient.ProjectCallsAPI.JoinProjectCall(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectCallsAPI.JoinProjectCall``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `JoinProjectCall`: ProjectCallJoin
	fmt.Fprintf(os.Stdout, "Response from `ProjectCallsAPI.JoinProjectCall`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiJoinProjectCallRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectCallJoin**](ProjectCallJoin.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeaveProjectCall

> ProjectCallState LeaveProjectCall(ctx, projectId, participantId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Leave the project's call

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
	participantId := "participantId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectCallsAPI.LeaveProjectCall(ctx, projectId, participantId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectCallsAPI.LeaveProjectCall``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LeaveProjectCall`: ProjectCallState
	fmt.Fprintf(os.Stdout, "Response from `ProjectCallsAPI.LeaveProjectCall`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |
**participantId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiLeaveProjectCallRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ProjectCallState**](ProjectCallState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

