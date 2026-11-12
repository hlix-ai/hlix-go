# DeliverablesAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApplyDeliverablePreparation**](DeliverablesAPI.md#applydeliverablepreparation) | **Post** /v1/api/deliverables/packages/{deliverableId}/preparations/{jobId}/apply | Apply a prepared candidate after concurrent draft edits
[**CreateDeliverablePackage**](DeliverablesAPI.md#createdeliverablepackage) | **Post** /v1/api/deliverables/packages | Create a client review package draft
[**DecideDeliverableApproval**](DeliverablesAPI.md#decidedeliverableapproval) | **Post** /v1/api/deliverables/{cycleId}/approvals/{approvalId}/decide | Record the customer&#39;s decision
[**DecideDeliverablePackageApproval**](DeliverablesAPI.md#decidedeliverablepackageapproval) | **Post** /v1/api/deliverables/packages/{deliverableId}/approvals/{approvalId}/decide | Record a decision on a published package version
[**GenerateDeliverableSuggestions**](DeliverablesAPI.md#generatedeliverablesuggestions) | **Post** /v1/api/deliverables/packages/suggestions | Suggest coherent review milestones
[**GetDeliverable**](DeliverablesAPI.md#getdeliverable) | **Get** /v1/api/deliverables/{cycleId} | Get one deliverable with its derived progress
[**GetDeliverablePackage**](DeliverablesAPI.md#getdeliverablepackage) | **Get** /v1/api/deliverables/packages/{deliverableId} | Read a client review package
[**GetDeliverablePackageRecording**](DeliverablesAPI.md#getdeliverablepackagerecording) | **Get** /v1/api/deliverables/packages/{deliverableId}/recording | Read the published package recording
[**GetDeliverablePreparation**](DeliverablesAPI.md#getdeliverablepreparation) | **Get** /v1/api/deliverables/packages/{deliverableId}/preparations/{jobId} | Read preparation progress and candidate
[**GetDeliverablePreparationRecording**](DeliverablesAPI.md#getdeliverablepreparationrecording) | **Get** /v1/api/deliverables/packages/{deliverableId}/preparations/{jobId}/recording | Read an agency preparation recording
[**GetDeliverableSuggestions**](DeliverablesAPI.md#getdeliverablesuggestions) | **Get** /v1/api/deliverables/packages/suggestions | Read private milestone suggestions
[**ListDeliverableApprovals**](DeliverablesAPI.md#listdeliverableapprovals) | **Get** /v1/api/deliverables/{cycleId}/approvals | List the decisions asked about a deliverable
[**ListDeliverablePackageApprovals**](DeliverablesAPI.md#listdeliverablepackageapprovals) | **Get** /v1/api/deliverables/packages/{deliverableId}/approvals | Read package review decisions
[**ListDeliverablePackages**](DeliverablesAPI.md#listdeliverablepackages) | **Get** /v1/api/deliverables/packages | List client review packages
[**ListDeliverablePreparations**](DeliverablesAPI.md#listdeliverablepreparations) | **Get** /v1/api/deliverables/packages/{deliverableId}/preparations | Read agency preparation history
[**ListDeliverables**](DeliverablesAPI.md#listdeliverables) | **Get** /v1/api/deliverables | List deliverables
[**PublishDeliverable**](DeliverablesAPI.md#publishdeliverable) | **Post** /v1/api/deliverables/{cycleId}/publish | Publish a deliverable to the customer
[**PublishDeliverablePackage**](DeliverablesAPI.md#publishdeliverablepackage) | **Post** /v1/api/deliverables/packages/{deliverableId}/publish | Publish an immutable client review version
[**RequestDeliverableApproval**](DeliverablesAPI.md#requestdeliverableapproval) | **Post** /v1/api/deliverables/{cycleId}/approvals | Ask a reviewer to decide
[**RequestDeliverablePackageApproval**](DeliverablesAPI.md#requestdeliverablepackageapproval) | **Post** /v1/api/deliverables/packages/{deliverableId}/approvals | Request a client review of the published package
[**StartDeliverablePreparation**](DeliverablesAPI.md#startdeliverablepreparation) | **Post** /v1/api/deliverables/packages/{deliverableId}/preparations | Prepare recorded integrated review evidence
[**UnpublishDeliverable**](DeliverablesAPI.md#unpublishdeliverable) | **Post** /v1/api/deliverables/{cycleId}/unpublish | Withdraw a deliverable from the customer
[**UnpublishDeliverablePackage**](DeliverablesAPI.md#unpublishdeliverablepackage) | **Post** /v1/api/deliverables/packages/{deliverableId}/unpublish | Withdraw a review package
[**UpdateDeliverablePackage**](DeliverablesAPI.md#updatedeliverablepackage) | **Put** /v1/api/deliverables/packages/{deliverableId} | Save review package draft
[**UpsertDeliverable**](DeliverablesAPI.md#upsertdeliverable) | **Put** /v1/api/deliverables/{cycleId} | Create or update a deliverable



## ApplyDeliverablePreparation

> DeliverablePackageView ApplyDeliverablePreparation(ctx, deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()

Apply a prepared candidate after concurrent draft edits

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
	deliverableId := "deliverableId_example" // string |
	jobId := "jobId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ApplyDeliverablePreparation(ctx, deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiApplyDeliverablePreparationRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var createDeliverablePackage openapiclient.CreateDeliverablePackage
	if err := json.Unmarshal([]byte("{\"projectId\":\"text\",\"title\":\"text\"}"), &createDeliverablePackage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.CreateDeliverablePackage(ctx).CreateDeliverablePackage(createDeliverablePackage).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateDeliverablePackageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDeliverablePackage** | [**CreateDeliverablePackage**](CreateDeliverablePackage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	cycleId := "cycleId_example" // string |
	approvalId := "approvalId_example" // string |
	var decideDeliverableApproval openapiclient.DecideDeliverableApproval
	if err := json.Unmarshal([]byte("{\"decision\":\"approved\"}"), &decideDeliverableApproval); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.DecideDeliverableApproval(ctx, cycleId, approvalId).DecideDeliverableApproval(decideDeliverableApproval).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDecideDeliverableApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **decideDeliverableApproval** | [**DecideDeliverableApproval**](DecideDeliverableApproval.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DeliverableDecision**](DeliverableDecision.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	approvalId := "approvalId_example" // string |
	var decideDeliverableApproval openapiclient.DecideDeliverableApproval
	if err := json.Unmarshal([]byte("{\"decision\":\"approved\"}"), &decideDeliverableApproval); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.DecideDeliverablePackageApproval(ctx, deliverableId, approvalId).DecideDeliverableApproval(decideDeliverableApproval).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDecideDeliverablePackageApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **decideDeliverableApproval** | [**DecideDeliverableApproval**](DecideDeliverableApproval.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var deliverableSuggestionInput openapiclient.DeliverableSuggestionInput
	if err := json.Unmarshal([]byte("{\"projectId\":\"text\"}"), &deliverableSuggestionInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GenerateDeliverableSuggestions(ctx).DeliverableSuggestionInput(deliverableSuggestionInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGenerateDeliverableSuggestionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deliverableSuggestionInput** | [**DeliverableSuggestionInput**](DeliverableSuggestionInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverableSuggestionsView**](DeliverableSuggestionsView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverable(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDeliverableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DeliverableView**](DeliverableView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePackage(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDeliverablePackageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	revision := "revision_example" // string | The published revision whose recording the page is reviewing
	download := "download_example" // string | Set to `1` to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with `download=1` in its `url`. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePackageRecording(ctx, deliverableId).Revision(revision).Download(download).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDeliverablePackageRecordingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **revision** | **string** | The published revision whose recording the page is reviewing |
 **download** | **string** | Set to &#x60;1&#x60; to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with &#x60;download&#x3D;1&#x60; in its &#x60;url&#x60;. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**PreparationRecordingUrl**](PreparationRecordingUrl.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	jobId := "jobId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePreparation(ctx, deliverableId, jobId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDeliverablePreparationRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePreparationView**](DeliverablePreparationView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	jobId := "jobId_example" // string |
	download := "download_example" // string | Set to `1` to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with `download=1` in its `url`. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverablePreparationRecording(ctx, deliverableId, jobId).Download(download).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDeliverablePreparationRecordingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Set to &#x60;1&#x60; to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with &#x60;download&#x3D;1&#x60; in its &#x60;url&#x60;. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PreparationRecordingUrl**](PreparationRecordingUrl.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string | Project whose completed work is grouped
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.GetDeliverableSuggestions(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetDeliverableSuggestionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Project whose completed work is grouped |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**DeliverableSuggestionsView**](DeliverableSuggestionsView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverableApprovals(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListDeliverableApprovalsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverablePackageApprovals(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListDeliverablePackageApprovalsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string | Limit packages to this project (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverablePackages(ctx).ProjectId(projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListDeliverablePackagesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | Limit packages to this project |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverablePreparations(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListDeliverablePreparationsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]DeliverablePreparationView**](DeliverablePreparationView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.DeliverablesAPI.ListDeliverables(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListDeliverablesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**[]Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.DeliverablesAPI.PublishDeliverable(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPublishDeliverableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.PublishDeliverablePackage(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPublishDeliverablePackageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	cycleId := "cycleId_example" // string |
	var requestDeliverableApproval openapiclient.RequestDeliverableApproval
	if err := json.Unmarshal([]byte("{\"reviewerId\":\"text\"}"), &requestDeliverableApproval); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.RequestDeliverableApproval(ctx, cycleId).RequestDeliverableApproval(requestDeliverableApproval).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRequestDeliverableApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **requestDeliverableApproval** | [**RequestDeliverableApproval**](RequestDeliverableApproval.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	var requestDeliverableApproval openapiclient.RequestDeliverableApproval
	if err := json.Unmarshal([]byte("{\"reviewerId\":\"text\"}"), &requestDeliverableApproval); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.RequestDeliverablePackageApproval(ctx, deliverableId).RequestDeliverableApproval(requestDeliverableApproval).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRequestDeliverablePackageApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **requestDeliverableApproval** | [**RequestDeliverableApproval**](RequestDeliverableApproval.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverableApproval**](DeliverableApproval.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.StartDeliverablePreparation(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiStartDeliverablePreparationRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePreparationView**](DeliverablePreparationView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.DeliverablesAPI.UnpublishDeliverable(ctx, cycleId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUnpublishDeliverableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UnpublishDeliverablePackage(ctx, deliverableId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUnpublishDeliverablePackageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	deliverableId := "deliverableId_example" // string |
	var deliverablePackageDraft openapiclient.DeliverablePackageDraft
	if err := json.Unmarshal([]byte("{\"title\":\"text\"}"), &deliverablePackageDraft); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UpdateDeliverablePackage(ctx, deliverableId).DeliverablePackageDraft(deliverablePackageDraft).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateDeliverablePackageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deliverablePackageDraft** | [**DeliverablePackageDraft**](DeliverablePackageDraft.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**DeliverablePackageView**](DeliverablePackageView.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	cycleId := "cycleId_example" // string |
	var upsertDeliverable openapiclient.UpsertDeliverable
	if err := json.Unmarshal([]byte("{\"title\":\"text\"}"), &upsertDeliverable); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeliverablesAPI.UpsertDeliverable(ctx, cycleId).UpsertDeliverable(upsertDeliverable).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpsertDeliverableRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **upsertDeliverable** | [**UpsertDeliverable**](UpsertDeliverable.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**Deliverable**](Deliverable.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

