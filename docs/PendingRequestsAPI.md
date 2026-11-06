# \PendingRequestsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AskClientQuestion**](PendingRequestsAPI.md#AskClientQuestion) | **Post** /v1/api/pending-requests/client-question | Ask the customer a question
[**CancelPendingRequest**](PendingRequestsAPI.md#CancelPendingRequest) | **Post** /v1/api/pending-requests/{id}/cancel | Cancel a request nobody will decide
[**GetPendingRequest**](PendingRequestsAPI.md#GetPendingRequest) | **Get** /v1/api/pending-requests/{id} | Get one request
[**ListPendingRequests**](PendingRequestsAPI.md#ListPendingRequests) | **Get** /v1/api/pending-requests | List requests awaiting a decision
[**ResolvePendingRequest**](PendingRequestsAPI.md#ResolvePendingRequest) | **Post** /v1/api/pending-requests/{id}/resolve | Approve or deny a request



## AskClientQuestion

> PendingRequest AskClientQuestion(ctx).AskClientQuestion(askClientQuestion).XOrganizationId(xOrganizationId).Execute()

Ask the customer a question

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
	askClientQuestion := *openapiclient.NewAskClientQuestion("CycleId_example", "Question_example", "Title_example") // AskClientQuestion | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PendingRequestsAPI.AskClientQuestion(context.Background()).AskClientQuestion(askClientQuestion).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PendingRequestsAPI.AskClientQuestion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AskClientQuestion`: PendingRequest
	fmt.Fprintf(os.Stdout, "Response from `PendingRequestsAPI.AskClientQuestion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAskClientQuestionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **askClientQuestion** | [**AskClientQuestion**](AskClientQuestion.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PendingRequest**](PendingRequest.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelPendingRequest

> PendingRequest CancelPendingRequest(ctx, id).XOrganizationId(xOrganizationId).Execute()

Cancel a request nobody will decide

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
	resp, r, err := apiClient.PendingRequestsAPI.CancelPendingRequest(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PendingRequestsAPI.CancelPendingRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelPendingRequest`: PendingRequest
	fmt.Fprintf(os.Stdout, "Response from `PendingRequestsAPI.CancelPendingRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelPendingRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PendingRequest**](PendingRequest.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPendingRequest

> PendingRequest GetPendingRequest(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one request

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
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PendingRequestsAPI.GetPendingRequest(context.Background(), id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PendingRequestsAPI.GetPendingRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPendingRequest`: PendingRequest
	fmt.Fprintf(os.Stdout, "Response from `PendingRequestsAPI.GetPendingRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPendingRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**PendingRequest**](PendingRequest.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPendingRequests

> []PendingRequestListItem ListPendingRequests(ctx).Status(status).CycleId(cycleId).TaskId(taskId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List requests awaiting a decision

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
	status := "status_example" // string | `pending` | `approved` | `denied` | `cancelled`. Omitted, every status is listed. (optional)
	cycleId := "cycleId_example" // string | Only requests raised against this cycle. (optional)
	taskId := "taskId_example" // string | Only requests raised against this task. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PendingRequestsAPI.ListPendingRequests(context.Background()).Status(status).CycleId(cycleId).TaskId(taskId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PendingRequestsAPI.ListPendingRequests``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPendingRequests`: []PendingRequestListItem
	fmt.Fprintf(os.Stdout, "Response from `PendingRequestsAPI.ListPendingRequests`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListPendingRequestsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **status** | **string** | &#x60;pending&#x60; | &#x60;approved&#x60; | &#x60;denied&#x60; | &#x60;cancelled&#x60;. Omitted, every status is listed. | 
 **cycleId** | **string** | Only requests raised against this cycle. | 
 **taskId** | **string** | Only requests raised against this task. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]PendingRequestListItem**](PendingRequestListItem.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolvePendingRequest

> PendingRequest ResolvePendingRequest(ctx, id).ResolvePendingRequest(resolvePendingRequest).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Approve or deny a request

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
	resolvePendingRequest := *openapiclient.NewResolvePendingRequest("Status_example") // ResolvePendingRequest | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PendingRequestsAPI.ResolvePendingRequest(context.Background(), id).ResolvePendingRequest(resolvePendingRequest).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PendingRequestsAPI.ResolvePendingRequest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolvePendingRequest`: PendingRequest
	fmt.Fprintf(os.Stdout, "Response from `PendingRequestsAPI.ResolvePendingRequest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolvePendingRequestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resolvePendingRequest** | [**ResolvePendingRequest**](ResolvePendingRequest.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**PendingRequest**](PendingRequest.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

