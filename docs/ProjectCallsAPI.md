# \ProjectCallsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**HeartbeatProjectCall**](ProjectCallsAPI.md#HeartbeatProjectCall) | **Put** /v1/api/projects/{projectId}/call/{participantId} | Keep the caller&#39;s place in the project&#39;s call
[**JoinProjectCall**](ProjectCallsAPI.md#JoinProjectCall) | **Post** /v1/api/projects/{projectId}/call | Join the project&#39;s call
[**LeaveProjectCall**](ProjectCallsAPI.md#LeaveProjectCall) | **Post** /v1/api/projects/{projectId}/call/{participantId}/leave | Leave the project&#39;s call



## HeartbeatProjectCall

> ProjectCallState HeartbeatProjectCall(ctx, projectId, participantId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Keep the caller's place in the project's call

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
	participantId := "participantId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectCallsAPI.HeartbeatProjectCall(context.Background(), projectId, participantId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiHeartbeatProjectCallRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectCallState**](ProjectCallState.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectCallsAPI.JoinProjectCall(context.Background(), projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiJoinProjectCallRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectCallJoin**](ProjectCallJoin.md)

### Authorization

[apiKey](../README.md#apiKey)

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
	participantId := "participantId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectCallsAPI.LeaveProjectCall(context.Background(), projectId, participantId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiLeaveProjectCallRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ProjectCallState**](ProjectCallState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

