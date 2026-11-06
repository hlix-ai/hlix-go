# \DeliverablesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApplyDeliverablePreparation**](DeliverablesAPI.md#ApplyDeliverablePreparation) | **Post** /v1/api/deliverables/packages/{deliverableId}/preparations/{jobId}/apply | Apply a prepared candidate after concurrent draft edits
[**CreateDeliverablePackage**](DeliverablesAPI.md#CreateDeliverablePackage) | **Post** /v1/api/deliverables/packages | Create a client review package draft
[**DecideDeliverableApproval**](DeliverablesAPI.md#DecideDeliverableApproval) | **Post** /v1/api/deliverables/{cycleId}/approvals/{approvalId}/decide | Record the customer&#39;s decision
[**DecideDeliverablePackageApproval**](DeliverablesAPI.md#DecideDeliverablePackageApproval) | **Post** /v1/api/deliverables/packages/{deliverableId}/approvals/{approvalId}/decide | Record a decision on a published package version
[**GenerateDeliverableSuggestions**](DeliverablesAPI.md#GenerateDeliverableSuggestions) | **Post** /v1/api/deliverables/packages/suggestions | Suggest coherent review milestones
[**GetDeliverable**](DeliverablesAPI.md#GetDeliverable) | **Get** /v1/api/deliverables/{cycleId} | Get one deliverable with its derived progress
[**GetDeliverablePackage**](DeliverablesAPI.md#GetDeliverablePackage) | **Get** /v1/api/deliverables/packages/{deliverableId} | Read a client review package
[**GetDeliverablePackageRecording**](DeliverablesAPI.md#GetDeliverablePackageRecording) | **Get** /v1/api/deliverables/packages/{deliverableId}/recording | Read the published package recording
[**GetDeliverablePreparation**](DeliverablesAPI.md#GetDeliverablePreparation) | **Get** /v1/api/deliverables/packages/{deliverableId}/preparations/{jobId} | Read preparation progress and candidate
[**GetDeliverablePreparationRecording**](DeliverablesAPI.md#GetDeliverablePreparationRecording) | **Get** /v1/api/deliverables/packages/{deliverableId}/preparations/{jobId}/recording | Read an agency preparation recording
[**GetDeliverableSuggestions**](DeliverablesAPI.md#GetDeliverableSuggestions) | **Get** /v1/api/deliverables/packages/suggestions | Read private milestone suggestions
[**ListDeliverableApprovals**](DeliverablesAPI.md#ListDeliverableApprovals) | **Get** /v1/api/deliverables/{cycleId}/approvals | List the decisions asked about a deliverable
[**ListDeliverablePackageApprovals**](DeliverablesAPI.md#ListDeliverablePackageApprovals) | **Get** /v1/api/deliverables/packages/{deliverableId}/approvals | Read package review decisions
[**ListDeliverablePackages**](DeliverablesAPI.md#ListDeliverablePackages) | **Get** /v1/api/deliverables/packages | List client review packages
[**ListDeliverablePreparations**](DeliverablesAPI.md#ListDeliverablePreparations) | **Get** /v1/api/deliverables/packages/{deliverableId}/preparations | Read agency preparation history
[**ListDeliverables**](DeliverablesAPI.md#ListDeliverables) | **Get** /v1/api/deliverables | List deliverables
[**PublishDeliverable**](DeliverablesAPI.md#PublishDeliverable) | **Post** /v1/api/deliverables/{cycleId}/publish | Publish a deliverable to the customer
[**PublishDeliverablePackage**](DeliverablesAPI.md#PublishDeliverablePackage) | **Post** /v1/api/deliverables/packages/{deliverableId}/publish | Publish an immutable client review version
[**RequestDeliverableApproval**](DeliverablesAPI.md#RequestDeliverableApproval) | **Post** /v1/api/deliverables/{cycleId}/approvals | Ask a reviewer to decide
[**RequestDeliverablePackageApproval**](DeliverablesAPI.md#RequestDeliverablePackageApproval) | **Post** /v1/api/deliverables/packages/{deliverableId}/approvals | Request a client review of the published package
[**StartDeliverablePreparation**](DeliverablesAPI.md#StartDeliverablePreparation) | **Post** /v1/api/deliverables/packages/{deliverableId}/preparations | Prepare recorded integrated review evidence
[**UnpublishDeliverable**](DeliverablesAPI.md#UnpublishDeliverable) | **Post** /v1/api/deliverables/{cycleId}/unpublish | Withdraw a deliverable from the customer
[**UnpublishDeliverablePackage**](DeliverablesAPI.md#UnpublishDeliverablePackage) | **Post** /v1/api/deliverables/packages/{deliverableId}/unpublish | Withdraw a review package
[**UpdateDeliverablePackage**](DeliverablesAPI.md#UpdateDeliverablePackage) | **Put** /v1/api/deliverables/packages/{deliverableId} | Save review package draft
[**UpsertDeliverable**](DeliverablesAPI.md#UpsertDeliverable) | **Put** /v1/api/deliverables/{cycleId} | Create or update a deliverable



## ApplyDeliverablePreparation

> DeliverablePackageView ApplyDeliverablePreparation(ctx, deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()

Apply a prepared candidate after concurrent draft edits

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
	deliverableId := "deliverableId_example" // string | 
	jobId := "jobId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ApplyDeliverablePreparation(context.Background(), deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.ApplyDeliverablePreparation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApplyDeliverablePreparation`: DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.ApplyDeliverablePreparation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApplyDeliverablePreparationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateDeliverablePackage

> DeliverablePackageView CreateDeliverablePackage(ctx).CreateDeliverablePackage(createDeliverablePackage).XOrganizationId(xOrganizationId).Execute()

Create a client review package draft

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
	createDeliverablePackage := *openapiclient.NewCreateDeliverablePackage("ProjectId_example", "Title_example") // CreateDeliverablePackage | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.CreateDeliverablePackage(context.Background()).CreateDeliverablePackage(createDeliverablePackage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.CreateDeliverablePackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeliverablePackage`: DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.CreateDeliverablePackage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeliverablePackageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDeliverablePackage** | [**CreateDeliverablePackage**](CreateDeliverablePackage.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DecideDeliverableApproval

> DeliverableDecision DecideDeliverableApproval(ctx, cycleId, approvalId).DecideDeliverableApproval(decideDeliverableApproval).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Record the customer's decision

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
	cycleId := "cycleId_example" // string | 
	approvalId := "approvalId_example" // string | 
	decideDeliverableApproval := *openapiclient.NewDecideDeliverableApproval("Decision_example") // DecideDeliverableApproval | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.DecideDeliverableApproval(context.Background(), cycleId, approvalId).DecideDeliverableApproval(decideDeliverableApproval).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.DecideDeliverableApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DecideDeliverableApproval`: DeliverableDecision
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.DecideDeliverableApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 
**approvalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDecideDeliverableApprovalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **decideDeliverableApproval** | [**DecideDeliverableApproval**](DecideDeliverableApproval.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DeliverableDecision**](DeliverableDecision.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DecideDeliverablePackageApproval

> DeliverableApproval DecideDeliverablePackageApproval(ctx, deliverableId, approvalId).DecideDeliverableApproval(decideDeliverableApproval).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Record a decision on a published package version

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
	deliverableId := "deliverableId_example" // string | 
	approvalId := "approvalId_example" // string | 
	decideDeliverableApproval := *openapiclient.NewDecideDeliverableApproval("Decision_example") // DecideDeliverableApproval | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.DecideDeliverablePackageApproval(context.Background(), deliverableId, approvalId).DecideDeliverableApproval(decideDeliverableApproval).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.DecideDeliverablePackageApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DecideDeliverablePackageApproval`: DeliverableApproval
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.DecideDeliverablePackageApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 
**approvalId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDecideDeliverablePackageApprovalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **decideDeliverableApproval** | [**DecideDeliverableApproval**](DecideDeliverableApproval.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateDeliverableSuggestions

> DeliverableSuggestionsView GenerateDeliverableSuggestions(ctx).DeliverableSuggestionInput(deliverableSuggestionInput).XOrganizationId(xOrganizationId).Execute()

Suggest coherent review milestones

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
	deliverableSuggestionInput := *openapiclient.NewDeliverableSuggestionInput("ProjectId_example") // DeliverableSuggestionInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GenerateDeliverableSuggestions(context.Background()).DeliverableSuggestionInput(deliverableSuggestionInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GenerateDeliverableSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateDeliverableSuggestions`: DeliverableSuggestionsView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GenerateDeliverableSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateDeliverableSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliverableSuggestionInput** | [**DeliverableSuggestionInput**](DeliverableSuggestionInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverableSuggestionsView**](DeliverableSuggestionsView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliverable

> DeliverableView GetDeliverable(ctx, cycleId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get one deliverable with its derived progress

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
	cycleId := "cycleId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverable(context.Background(), cycleId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GetDeliverable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverable`: DeliverableView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GetDeliverable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DeliverableView**](DeliverableView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliverablePackage

> DeliverablePackageView GetDeliverablePackage(ctx, deliverableId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read a client review package

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
	deliverableId := "deliverableId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePackage(context.Background(), deliverableId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GetDeliverablePackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverablePackage`: DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GetDeliverablePackage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverablePackageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliverablePackageRecording

> PreparationRecordingUrl GetDeliverablePackageRecording(ctx, deliverableId).Revision(revision).Download(download).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read the published package recording

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
	deliverableId := "deliverableId_example" // string | 
	revision := "revision_example" // string | The published revision whose recording the page is reviewing
	download := "download_example" // string | Set to `1` to receive the object's own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body's `url` is this same route with `download=1` already appended, so following it is the normal flow; any other value, absent included, answers the JSON. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePackageRecording(context.Background(), deliverableId).Revision(revision).Download(download).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GetDeliverablePackageRecording``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverablePackageRecording`: PreparationRecordingUrl
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GetDeliverablePackageRecording`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverablePackageRecordingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revision** | **string** | The published revision whose recording the page is reviewing | 
 **download** | **string** | Set to &#x60;1&#x60; to receive the object&#39;s own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body&#39;s &#x60;url&#x60; is this same route with &#x60;download&#x3D;1&#x60; already appended, so following it is the normal flow; any other value, absent included, answers the JSON. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**PreparationRecordingUrl**](PreparationRecordingUrl.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream, text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliverablePreparation

> DeliverablePreparationView GetDeliverablePreparation(ctx, deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()

Read preparation progress and candidate

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
	deliverableId := "deliverableId_example" // string | 
	jobId := "jobId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePreparation(context.Background(), deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GetDeliverablePreparation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverablePreparation`: DeliverablePreparationView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GetDeliverablePreparation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverablePreparationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePreparationView**](DeliverablePreparationView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliverablePreparationRecording

> PreparationRecordingUrl GetDeliverablePreparationRecording(ctx, deliverableId, jobId).Download(download).XOrganizationId(xOrganizationId).Execute()

Read an agency preparation recording

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
	deliverableId := "deliverableId_example" // string | 
	jobId := "jobId_example" // string | 
	download := "download_example" // string | Set to `1` to receive the object's own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body's `url` is this same route with `download=1` already appended, so following it is the normal flow; any other value, absent included, answers the JSON. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePreparationRecording(context.Background(), deliverableId, jobId).Download(download).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GetDeliverablePreparationRecording``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverablePreparationRecording`: PreparationRecordingUrl
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GetDeliverablePreparationRecording`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverablePreparationRecordingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Set to &#x60;1&#x60; to receive the object&#39;s own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body&#39;s &#x60;url&#x60; is this same route with &#x60;download&#x3D;1&#x60; already appended, so following it is the normal flow; any other value, absent included, answers the JSON. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PreparationRecordingUrl**](PreparationRecordingUrl.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream, text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeliverableSuggestions

> DeliverableSuggestionsView GetDeliverableSuggestions(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read private milestone suggestions

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
	projectId := "projectId_example" // string | Project whose completed work is grouped
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverableSuggestions(context.Background()).ProjectId(projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.GetDeliverableSuggestions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeliverableSuggestions`: DeliverableSuggestionsView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.GetDeliverableSuggestions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeliverableSuggestionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Project whose completed work is grouped | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**DeliverableSuggestionsView**](DeliverableSuggestionsView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliverableApprovals

> []DeliverableApproval ListDeliverableApprovals(ctx, cycleId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List the decisions asked about a deliverable

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
	cycleId := "cycleId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverableApprovals(context.Background(), cycleId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.ListDeliverableApprovals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliverableApprovals`: []DeliverableApproval
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.ListDeliverableApprovals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListDeliverableApprovalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliverablePackageApprovals

> []DeliverableApproval ListDeliverablePackageApprovals(ctx, deliverableId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read package review decisions

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
	deliverableId := "deliverableId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverablePackageApprovals(context.Background(), deliverableId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.ListDeliverablePackageApprovals``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliverablePackageApprovals`: []DeliverableApproval
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.ListDeliverablePackageApprovals`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListDeliverablePackageApprovalsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliverablePackages

> []DeliverablePackageView ListDeliverablePackages(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List client review packages

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
	projectId := "projectId_example" // string | Limit packages to this project (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverablePackages(context.Background()).ProjectId(projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.ListDeliverablePackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliverablePackages`: []DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.ListDeliverablePackages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDeliverablePackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Limit packages to this project | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliverablePreparations

> []DeliverablePreparationView ListDeliverablePreparations(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()

Read agency preparation history

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
	deliverableId := "deliverableId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverablePreparations(context.Background(), deliverableId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.ListDeliverablePreparations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliverablePreparations`: []DeliverablePreparationView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.ListDeliverablePreparations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListDeliverablePreparationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]DeliverablePreparationView**](DeliverablePreparationView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeliverables

> []Deliverable ListDeliverables(ctx).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List deliverables

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
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverables(context.Background()).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.ListDeliverables``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeliverables`: []Deliverable
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.ListDeliverables`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListDeliverablesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishDeliverable

> Deliverable PublishDeliverable(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()

Publish a deliverable to the customer

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
	cycleId := "cycleId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.PublishDeliverable(context.Background(), cycleId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.PublishDeliverable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishDeliverable`: Deliverable
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.PublishDeliverable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPublishDeliverableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishDeliverablePackage

> DeliverablePackageView PublishDeliverablePackage(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()

Publish an immutable client review version

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
	deliverableId := "deliverableId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.PublishDeliverablePackage(context.Background(), deliverableId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.PublishDeliverablePackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishDeliverablePackage`: DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.PublishDeliverablePackage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPublishDeliverablePackageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestDeliverableApproval

> DeliverableApproval RequestDeliverableApproval(ctx, cycleId).RequestDeliverableApproval(requestDeliverableApproval).XOrganizationId(xOrganizationId).Execute()

Ask a reviewer to decide

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
	cycleId := "cycleId_example" // string | 
	requestDeliverableApproval := *openapiclient.NewRequestDeliverableApproval("ReviewerId_example") // RequestDeliverableApproval | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.RequestDeliverableApproval(context.Background(), cycleId).RequestDeliverableApproval(requestDeliverableApproval).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.RequestDeliverableApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestDeliverableApproval`: DeliverableApproval
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.RequestDeliverableApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRequestDeliverableApprovalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **requestDeliverableApproval** | [**RequestDeliverableApproval**](RequestDeliverableApproval.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RequestDeliverablePackageApproval

> DeliverableApproval RequestDeliverablePackageApproval(ctx, deliverableId).RequestDeliverableApproval(requestDeliverableApproval).XOrganizationId(xOrganizationId).Execute()

Request a client review of the published package

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
	deliverableId := "deliverableId_example" // string | 
	requestDeliverableApproval := *openapiclient.NewRequestDeliverableApproval("ReviewerId_example") // RequestDeliverableApproval | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.RequestDeliverablePackageApproval(context.Background(), deliverableId).RequestDeliverableApproval(requestDeliverableApproval).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.RequestDeliverablePackageApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RequestDeliverablePackageApproval`: DeliverableApproval
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.RequestDeliverablePackageApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRequestDeliverablePackageApprovalRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **requestDeliverableApproval** | [**RequestDeliverableApproval**](RequestDeliverableApproval.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartDeliverablePreparation

> DeliverablePreparationView StartDeliverablePreparation(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()

Prepare recorded integrated review evidence

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
	deliverableId := "deliverableId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.StartDeliverablePreparation(context.Background(), deliverableId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.StartDeliverablePreparation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StartDeliverablePreparation`: DeliverablePreparationView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.StartDeliverablePreparation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStartDeliverablePreparationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePreparationView**](DeliverablePreparationView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnpublishDeliverable

> Deliverable UnpublishDeliverable(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()

Withdraw a deliverable from the customer

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
	cycleId := "cycleId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UnpublishDeliverable(context.Background(), cycleId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.UnpublishDeliverable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnpublishDeliverable`: Deliverable
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.UnpublishDeliverable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnpublishDeliverableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnpublishDeliverablePackage

> DeliverablePackageView UnpublishDeliverablePackage(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()

Withdraw a review package

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
	deliverableId := "deliverableId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UnpublishDeliverablePackage(context.Background(), deliverableId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.UnpublishDeliverablePackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnpublishDeliverablePackage`: DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.UnpublishDeliverablePackage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnpublishDeliverablePackageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeliverablePackage

> DeliverablePackageView UpdateDeliverablePackage(ctx, deliverableId).DeliverablePackageDraft(deliverablePackageDraft).XOrganizationId(xOrganizationId).Execute()

Save review package draft

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
	deliverableId := "deliverableId_example" // string | 
	deliverablePackageDraft := *openapiclient.NewDeliverablePackageDraft("Title_example") // DeliverablePackageDraft | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UpdateDeliverablePackage(context.Background(), deliverableId).DeliverablePackageDraft(deliverablePackageDraft).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.UpdateDeliverablePackage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeliverablePackage`: DeliverablePackageView
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.UpdateDeliverablePackage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**deliverableId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeliverablePackageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deliverablePackageDraft** | [**DeliverablePackageDraft**](DeliverablePackageDraft.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertDeliverable

> Deliverable UpsertDeliverable(ctx, cycleId).UpsertDeliverable(upsertDeliverable).XOrganizationId(xOrganizationId).Execute()

Create or update a deliverable

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
	cycleId := "cycleId_example" // string | 
	upsertDeliverable := *openapiclient.NewUpsertDeliverable("Title_example") // UpsertDeliverable | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UpsertDeliverable(context.Background(), cycleId).UpsertDeliverable(upsertDeliverable).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeliverablesAPI.UpsertDeliverable``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertDeliverable`: Deliverable
	fmt.Fprintf(os.Stdout, "Response from `DeliverablesAPI.UpsertDeliverable`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpsertDeliverableRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **upsertDeliverable** | [**UpsertDeliverable**](UpsertDeliverable.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

