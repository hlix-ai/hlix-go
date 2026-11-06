# \GrowthAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddGrowthIndexLeads**](GrowthAPI.md#AddGrowthIndexLeads) | **Post** /v1/api/growth/projects/{projectId}/index-leads | Add people and companies from Hlix&#39;s shared index to a growth project
[**AddGrowthSuppressions**](GrowthAPI.md#AddGrowthSuppressions) | **Post** /v1/api/growth/suppressions | Add addresses and domains to the do-not-contact list
[**ApproveGrowthBatch**](GrowthAPI.md#ApproveGrowthBatch) | **Post** /v1/api/growth/projects/{projectId}/batches/{batchId}/approve | Release a researched lead list before its review deadline
[**ApproveGrowthMessage**](GrowthAPI.md#ApproveGrowthMessage) | **Post** /v1/api/growth/messages/{messageId}/approve | Approve a drafted email, optionally edited, so it sends
[**CancelManagedMailboxHosting**](GrowthAPI.md#CancelManagedMailboxHosting) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/cancel-hosting | Block new cold sends immediately and request hosting cancellation
[**CancelManagedMailboxWarmup**](GrowthAPI.md#CancelManagedMailboxWarmup) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/cancel-warmup | Cancel warmup separately from mailbox hosting
[**CheckGrowthMailboxDns**](GrowthAPI.md#CheckGrowthMailboxDns) | **Get** /v1/api/growth/mailboxes/{mailboxId}/dns | Check the mailbox domain&#39;s SPF, DKIM and DMARC records
[**ClassifyGrowthMessage**](GrowthAPI.md#ClassifyGrowthMessage) | **Patch** /v1/api/growth/messages/{messageId} | Sort a reply by hand
[**CompareGrowthProviders**](GrowthAPI.md#CompareGrowthProviders) | **Post** /v1/api/growth/chains/find_email/compare | Run two email finders on the same sample of the workspace&#39;s leads
[**ConnectGrowthMailbox**](GrowthAPI.md#ConnectGrowthMailbox) | **Post** /v1/api/growth/mailboxes/connect | Start connecting a Google or Microsoft mailbox to send from
[**CreateGrowthPlay**](GrowthAPI.md#CreateGrowthPlay) | **Post** /v1/api/growth/projects/{projectId}/plays | Create one campaign
[**CreateGrowthProject**](GrowthAPI.md#CreateGrowthProject) | **Post** /v1/api/growth/projects | Create a growth project from a website and start its research run
[**DisconnectGrowthMailbox**](GrowthAPI.md#DisconnectGrowthMailbox) | **Delete** /v1/api/growth/mailboxes/{mailboxId} | Disconnect a mailbox and revoke its access
[**DownloadGrowthLeadExport**](GrowthAPI.md#DownloadGrowthLeadExport) | **Get** /v1/api/growth/projects/{projectId}/lead-exports/{exportId} | Download a project&#39;s lead CSV export
[**ExportGrowthLeads**](GrowthAPI.md#ExportGrowthLeads) | **Post** /v1/api/growth/projects/{projectId}/leads/export | Export all matching leads to CSV
[**GetGrowthEnrichPrice**](GrowthAPI.md#GetGrowthEnrichPrice) | **Get** /v1/api/growth/enrich | Hlix Enrich price: what one email sent to a lead built on Hlix&#39;s data costs
[**GetGrowthIndexStats**](GrowthAPI.md#GetGrowthIndexStats) | **Get** /v1/api/growth/index | The size of Hlix&#39;s shared company index and how many of the workspace&#39;s companies it supplied
[**GetGrowthOverview**](GrowthAPI.md#GetGrowthOverview) | **Get** /v1/api/growth/projects/{projectId}/overview | A growth project&#39;s outreach, hot leads and spend per day, with its daily budget
[**GetGrowthProject**](GrowthAPI.md#GetGrowthProject) | **Get** /v1/api/growth/projects/{projectId} | Show a growth project&#39;s brain, campaigns and last run
[**GetGrowthSendingSchedule**](GrowthAPI.md#GetGrowthSendingSchedule) | **Get** /v1/api/growth/projects/{projectId}/sending-schedule | Resolve project and campaign sending schedules
[**GetGrowthSettings**](GrowthAPI.md#GetGrowthSettings) | **Get** /v1/api/growth/settings | The workspace&#39;s growth settings and this month&#39;s growth spend
[**GetGrowthSpend**](GrowthAPI.md#GetGrowthSpend) | **Get** /v1/api/growth/projects/{projectId}/spend | Show each campaign&#39;s data-provider spend for today and the last 30 days
[**GetGrowthThread**](GrowthAPI.md#GetGrowthThread) | **Get** /v1/api/growth/leads/{leadId}/thread | Show a lead&#39;s whole email thread, drafts included
[**GetManagedMailboxConfiguration**](GrowthAPI.md#GetManagedMailboxConfiguration) | **Get** /v1/api/growth/managed-mailboxes/configuration | Read managed mailbox configuration and commercial readiness
[**GetManagedMailboxOrder**](GrowthAPI.md#GetManagedMailboxOrder) | **Get** /v1/api/growth/managed-mailboxes/orders/{orderId} | Read a saved managed mailbox order
[**ImportGrowthToolResult**](GrowthAPI.md#ImportGrowthToolResult) | **Post** /v1/api/growth/projects/{projectId}/lead-lists/from-tool-call | Import the people a completed tool call returned
[**ListGrowthBatches**](GrowthAPI.md#ListGrowthBatches) | **Get** /v1/api/growth/projects/{projectId}/batches | Research lists and their twelve-hour review deadlines
[**ListGrowthChains**](GrowthAPI.md#ListGrowthChains) | **Get** /v1/api/growth/chains | Each capability&#39;s data-provider order and how each provider did in the last 7 days
[**ListGrowthCitableProjects**](GrowthAPI.md#ListGrowthCitableProjects) | **Get** /v1/api/growth/citable-projects | List the finished delivery projects a growth brain may quote
[**ListGrowthInbox**](GrowthAPI.md#ListGrowthInbox) | **Get** /v1/api/growth/projects/{projectId}/inbox | List a growth project&#39;s email threads, one per lead
[**ListGrowthLeads**](GrowthAPI.md#ListGrowthLeads) | **Get** /v1/api/growth/projects/{projectId}/leads | List a growth project&#39;s leads with their evidence and provenance
[**ListGrowthMailboxes**](GrowthAPI.md#ListGrowthMailboxes) | **Get** /v1/api/growth/mailboxes | List the workspace&#39;s sending mailboxes with their warm-up and today&#39;s sends
[**ListGrowthProviders**](GrowthAPI.md#ListGrowthProviders) | **Get** /v1/api/growth/providers | List growth data providers and the workspace&#39;s key state
[**ListGrowthSuppressions**](GrowthAPI.md#ListGrowthSuppressions) | **Get** /v1/api/growth/suppressions | List the do-not-contact list
[**ListManagedMailboxOrders**](GrowthAPI.md#ListManagedMailboxOrders) | **Get** /v1/api/growth/managed-mailboxes/orders | List managed mailbox orders
[**ListManagedMailboxResources**](GrowthAPI.md#ListManagedMailboxResources) | **Get** /v1/api/growth/managed-mailboxes/resources | List managed domains and mailbox resources
[**OrderManagedMailboxes**](GrowthAPI.md#OrderManagedMailboxes) | **Post** /v1/api/growth/managed-mailboxes/orders | Persist a managed mailbox order before provider dispatch
[**PreviewGrowthLeadExport**](GrowthAPI.md#PreviewGrowthLeadExport) | **Post** /v1/api/growth/projects/{projectId}/leads/export/preview | What exporting the matching leads would cost, before exporting
[**QuoteManagedMailboxes**](GrowthAPI.md#QuoteManagedMailboxes) | **Post** /v1/api/growth/managed-mailboxes/quotes | Observe domain availability and recurring mailbox prices
[**ReconcileManagedMailboxOrder**](GrowthAPI.md#ReconcileManagedMailboxOrder) | **Post** /v1/api/growth/managed-mailboxes/orders/{orderId}/reconcile | Reconcile provider evidence without replaying uncertain purchases
[**RefineGrowthReply**](GrowthAPI.md#RefineGrowthReply) | **Post** /v1/api/growth/leads/{leadId}/refine-reply | Refine a reply against the lead thread and sourced project context without sending
[**RemoveGrowthProviderKey**](GrowthAPI.md#RemoveGrowthProviderKey) | **Delete** /v1/api/growth/providers/{provider}/key | Remove the workspace&#39;s own key for a growth provider
[**RemoveGrowthSuppression**](GrowthAPI.md#RemoveGrowthSuppression) | **Delete** /v1/api/growth/suppressions/{suppressionId} | Remove an entry a person added to the do-not-contact list
[**RemoveManagedMailboxDomain**](GrowthAPI.md#RemoveManagedMailboxDomain) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/remove-domain | Request domain removal without claiming a refund or renewal cancellation
[**RepairManagedMailboxResource**](GrowthAPI.md#RepairManagedMailboxResource) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/repair | Repair a failed resource step without repurchasing successful resources
[**RerunGrowthProject**](GrowthAPI.md#RerunGrowthProject) | **Post** /v1/api/growth/projects/{projectId}/runs | Run the website research again
[**ResearchGrowthPlay**](GrowthAPI.md#ResearchGrowthPlay) | **Post** /v1/api/growth/plays/{playId}/research | Find or resume leads for one campaign without repeating completed research
[**ResolveGrowthMessage**](GrowthAPI.md#ResolveGrowthMessage) | **Post** /v1/api/growth/messages/{messageId}/resolve | Record whether an email whose delivery was unknown went out
[**SaveGrowthProviderKey**](GrowthAPI.md#SaveGrowthProviderKey) | **Put** /v1/api/growth/providers/{provider}/key | Add or replace the workspace&#39;s own key for a growth provider
[**SearchGrowthIndex**](GrowthAPI.md#SearchGrowthIndex) | **Get** /v1/api/growth/index/search | Search Hlix&#39;s shared index of companies and their people
[**SendGrowthReply**](GrowthAPI.md#SendGrowthReply) | **Post** /v1/api/growth/leads/{leadId}/reply | Answer a lead in their thread from the mailbox that wrote to them
[**SetGrowthAutopilot**](GrowthAPI.md#SetGrowthAutopilot) | **Put** /v1/api/growth/projects/{projectId}/autopilot | Turn the project&#39;s budget autopilot on or off
[**SetGrowthProjectBudget**](GrowthAPI.md#SetGrowthProjectBudget) | **Put** /v1/api/growth/projects/{projectId}/daily-budget | Set or remove what all of a growth project&#39;s campaigns may spend per day
[**UpdateGrowthBrain**](GrowthAPI.md#UpdateGrowthBrain) | **Put** /v1/api/growth/projects/{projectId}/brain | Replace the Company brain
[**UpdateGrowthChain**](GrowthAPI.md#UpdateGrowthChain) | **Put** /v1/api/growth/chains/{capability} | Set the order a capability tries its providers in, or go back to the default
[**UpdateGrowthLead**](GrowthAPI.md#UpdateGrowthLead) | **Patch** /v1/api/growth/leads/{leadId} | Disqualify a lead or put it back in line
[**UpdateGrowthMailbox**](GrowthAPI.md#UpdateGrowthMailbox) | **Patch** /v1/api/growth/mailboxes/{mailboxId} | Change a mailbox&#39;s daily limit or warm-up start, or pause and resume it
[**UpdateGrowthPlay**](GrowthAPI.md#UpdateGrowthPlay) | **Patch** /v1/api/growth/plays/{playId} | Edit or launch a campaign
[**UpdateGrowthProvider**](GrowthAPI.md#UpdateGrowthProvider) | **Patch** /v1/api/growth/providers/{provider} | Turn a growth provider on or off for the workspace, or change its settings
[**UpdateGrowthSendingSchedule**](GrowthAPI.md#UpdateGrowthSendingSchedule) | **Patch** /v1/api/growth/projects/{projectId}/sending-schedule | Set or inherit a project&#39;s sending schedule
[**UpdateGrowthSettings**](GrowthAPI.md#UpdateGrowthSettings) | **Patch** /v1/api/growth/settings | Change the hard cap, the sending rules or the booking link
[**UploadGrowthLeadList**](GrowthAPI.md#UploadGrowthLeadList) | **Post** /v1/api/growth/projects/{projectId}/lead-lists | Upload a lead list to a growth project



## AddGrowthIndexLeads

> GrowthLeadListResult AddGrowthIndexLeads(ctx, projectId).AddGrowthIndexLeads(addGrowthIndexLeads).XOrganizationId(xOrganizationId).Execute()

Add people and companies from Hlix's shared index to a growth project

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
	addGrowthIndexLeads := *openapiclient.NewAddGrowthIndexLeads() // AddGrowthIndexLeads | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.AddGrowthIndexLeads(context.Background(), projectId).AddGrowthIndexLeads(addGrowthIndexLeads).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.AddGrowthIndexLeads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddGrowthIndexLeads`: GrowthLeadListResult
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.AddGrowthIndexLeads`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddGrowthIndexLeadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addGrowthIndexLeads** | [**AddGrowthIndexLeads**](AddGrowthIndexLeads.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthLeadListResult**](GrowthLeadListResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddGrowthSuppressions

> GrowthSuppressionsAdded AddGrowthSuppressions(ctx).AddGrowthSuppressions(addGrowthSuppressions).XOrganizationId(xOrganizationId).Execute()

Add addresses and domains to the do-not-contact list

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
	addGrowthSuppressions := *openapiclient.NewAddGrowthSuppressions([]string{"Entries_example"}) // AddGrowthSuppressions | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.AddGrowthSuppressions(context.Background()).AddGrowthSuppressions(addGrowthSuppressions).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.AddGrowthSuppressions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddGrowthSuppressions`: GrowthSuppressionsAdded
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.AddGrowthSuppressions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAddGrowthSuppressionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addGrowthSuppressions** | [**AddGrowthSuppressions**](AddGrowthSuppressions.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthSuppressionsAdded**](GrowthSuppressionsAdded.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApproveGrowthBatch

> GrowthBatchApproved ApproveGrowthBatch(ctx, projectId, batchId).XOrganizationId(xOrganizationId).Execute()

Release a researched lead list before its review deadline

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
	batchId := "batchId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ApproveGrowthBatch(context.Background(), projectId, batchId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ApproveGrowthBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveGrowthBatch`: GrowthBatchApproved
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ApproveGrowthBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**batchId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveGrowthBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthBatchApproved**](GrowthBatchApproved.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApproveGrowthMessage

> GrowthMessage ApproveGrowthMessage(ctx, messageId).ApproveGrowthMessage(approveGrowthMessage).XOrganizationId(xOrganizationId).Execute()

Approve a drafted email, optionally edited, so it sends

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
	messageId := "messageId_example" // string | 
	approveGrowthMessage := *openapiclient.NewApproveGrowthMessage() // ApproveGrowthMessage | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ApproveGrowthMessage(context.Background(), messageId).ApproveGrowthMessage(approveGrowthMessage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ApproveGrowthMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveGrowthMessage`: GrowthMessage
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ApproveGrowthMessage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**messageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveGrowthMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **approveGrowthMessage** | [**ApproveGrowthMessage**](ApproveGrowthMessage.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMessage**](GrowthMessage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelManagedMailboxHosting

> ManagedMailboxOrder CancelManagedMailboxHosting(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()

Block new cold sends immediately and request hosting cancellation

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
	resourceId := "resourceId_example" // string | 
	managedMailboxResourceActionInput := *openapiclient.NewManagedMailboxResourceActionInput("IdempotencyKey_example") // ManagedMailboxResourceActionInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CancelManagedMailboxHosting(context.Background(), resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.CancelManagedMailboxHosting``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelManagedMailboxHosting`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.CancelManagedMailboxHosting`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**resourceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelManagedMailboxHostingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelManagedMailboxWarmup

> ManagedMailboxOrder CancelManagedMailboxWarmup(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()

Cancel warmup separately from mailbox hosting

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
	resourceId := "resourceId_example" // string | 
	managedMailboxResourceActionInput := *openapiclient.NewManagedMailboxResourceActionInput("IdempotencyKey_example") // ManagedMailboxResourceActionInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CancelManagedMailboxWarmup(context.Background(), resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.CancelManagedMailboxWarmup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelManagedMailboxWarmup`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.CancelManagedMailboxWarmup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**resourceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelManagedMailboxWarmupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckGrowthMailboxDns

> GrowthMailboxDns CheckGrowthMailboxDns(ctx, mailboxId).XOrganizationId(xOrganizationId).Execute()

Check the mailbox domain's SPF, DKIM and DMARC records

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
	mailboxId := "mailboxId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CheckGrowthMailboxDns(context.Background(), mailboxId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.CheckGrowthMailboxDns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckGrowthMailboxDns`: GrowthMailboxDns
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.CheckGrowthMailboxDns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**mailboxId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckGrowthMailboxDnsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMailboxDns**](GrowthMailboxDns.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ClassifyGrowthMessage

> GrowthClassification ClassifyGrowthMessage(ctx, messageId).ClassifyGrowthMessage(classifyGrowthMessage).XOrganizationId(xOrganizationId).Execute()

Sort a reply by hand

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
	messageId := "messageId_example" // string | 
	classifyGrowthMessage := *openapiclient.NewClassifyGrowthMessage("Classification_example") // ClassifyGrowthMessage | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ClassifyGrowthMessage(context.Background(), messageId).ClassifyGrowthMessage(classifyGrowthMessage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ClassifyGrowthMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ClassifyGrowthMessage`: GrowthClassification
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ClassifyGrowthMessage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**messageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiClassifyGrowthMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **classifyGrowthMessage** | [**ClassifyGrowthMessage**](ClassifyGrowthMessage.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthClassification**](GrowthClassification.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompareGrowthProviders

> GrowthProviderComparison CompareGrowthProviders(ctx).CompareGrowthProviders(compareGrowthProviders).XOrganizationId(xOrganizationId).Execute()

Run two email finders on the same sample of the workspace's leads

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
	compareGrowthProviders := *openapiclient.NewCompareGrowthProviders("OperationKey_example", []interface{}{nil}) // CompareGrowthProviders | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CompareGrowthProviders(context.Background()).CompareGrowthProviders(compareGrowthProviders).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.CompareGrowthProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompareGrowthProviders`: GrowthProviderComparison
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.CompareGrowthProviders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompareGrowthProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **compareGrowthProviders** | [**CompareGrowthProviders**](CompareGrowthProviders.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProviderComparison**](GrowthProviderComparison.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConnectGrowthMailbox

> GrowthMailboxConnect ConnectGrowthMailbox(ctx).ConnectGrowthMailbox(connectGrowthMailbox).XOrganizationId(xOrganizationId).Execute()

Start connecting a Google or Microsoft mailbox to send from

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
	connectGrowthMailbox := *openapiclient.NewConnectGrowthMailbox("Service_example") // ConnectGrowthMailbox | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ConnectGrowthMailbox(context.Background()).ConnectGrowthMailbox(connectGrowthMailbox).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ConnectGrowthMailbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConnectGrowthMailbox`: GrowthMailboxConnect
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ConnectGrowthMailbox`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiConnectGrowthMailboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectGrowthMailbox** | [**ConnectGrowthMailbox**](ConnectGrowthMailbox.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMailboxConnect**](GrowthMailboxConnect.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateGrowthPlay

> GrowthPlay CreateGrowthPlay(ctx, projectId).CreateGrowthPlay(createGrowthPlay).XOrganizationId(xOrganizationId).Execute()

Create one campaign

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
	createGrowthPlay := *openapiclient.NewCreateGrowthPlay("Name_example", *openapiclient.NewCreateGrowthPlayWho([]string{"CompanySizes_example"}, []string{"Countries_example"}, []string{"Industries_example"}, []string{"Roles_example"})) // CreateGrowthPlay | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CreateGrowthPlay(context.Background(), projectId).CreateGrowthPlay(createGrowthPlay).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.CreateGrowthPlay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGrowthPlay`: GrowthPlay
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.CreateGrowthPlay`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateGrowthPlayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createGrowthPlay** | [**CreateGrowthPlay**](CreateGrowthPlay.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthPlay**](GrowthPlay.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateGrowthProject

> GrowthProjectCreated CreateGrowthProject(ctx).CreateGrowthProject(createGrowthProject).XOrganizationId(xOrganizationId).Execute()

Create a growth project from a website and start its research run

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
	createGrowthProject := *openapiclient.NewCreateGrowthProject() // CreateGrowthProject | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CreateGrowthProject(context.Background()).CreateGrowthProject(createGrowthProject).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.CreateGrowthProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGrowthProject`: GrowthProjectCreated
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.CreateGrowthProject`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateGrowthProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createGrowthProject** | [**CreateGrowthProject**](CreateGrowthProject.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProjectCreated**](GrowthProjectCreated.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DisconnectGrowthMailbox

> GrowthMailboxDisconnected DisconnectGrowthMailbox(ctx, mailboxId).XOrganizationId(xOrganizationId).Execute()

Disconnect a mailbox and revoke its access

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
	mailboxId := "mailboxId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.DisconnectGrowthMailbox(context.Background(), mailboxId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.DisconnectGrowthMailbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DisconnectGrowthMailbox`: GrowthMailboxDisconnected
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.DisconnectGrowthMailbox`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**mailboxId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDisconnectGrowthMailboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMailboxDisconnected**](GrowthMailboxDisconnected.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadGrowthLeadExport

> *os.File DownloadGrowthLeadExport(ctx, projectId, exportId).Download(download).XOrganizationId(xOrganizationId).Execute()

Download a project's lead CSV export

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
	exportId := "exportId_example" // string | 
	download := "download_example" // string | Use 1 for the authenticated CSV attachment. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.DownloadGrowthLeadExport(context.Background(), projectId, exportId).Download(download).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.DownloadGrowthLeadExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadGrowthLeadExport`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.DownloadGrowthLeadExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**exportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadGrowthLeadExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Use 1 for the authenticated CSV attachment. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[***os.File**](*os.File.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportGrowthLeads

> GrowthLeadExportResult ExportGrowthLeads(ctx, projectId).GrowthLeadExportFilters(growthLeadExportFilters).XOrganizationId(xOrganizationId).Execute()

Export all matching leads to CSV

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
	growthLeadExportFilters := *openapiclient.NewGrowthLeadExportFilters() // GrowthLeadExportFilters | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ExportGrowthLeads(context.Background(), projectId).GrowthLeadExportFilters(growthLeadExportFilters).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ExportGrowthLeads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportGrowthLeads`: GrowthLeadExportResult
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ExportGrowthLeads`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiExportGrowthLeadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **growthLeadExportFilters** | [**GrowthLeadExportFilters**](GrowthLeadExportFilters.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthLeadExportResult**](GrowthLeadExportResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthEnrichPrice

> GrowthEnrich GetGrowthEnrichPrice(ctx).XOrganizationId(xOrganizationId).Execute()

Hlix Enrich price: what one email sent to a lead built on Hlix's data costs

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthEnrichPrice(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthEnrichPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthEnrichPrice`: GrowthEnrich
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthEnrichPrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthEnrichPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthEnrich**](GrowthEnrich.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthIndexStats

> GrowthIndexStats GetGrowthIndexStats(ctx).XOrganizationId(xOrganizationId).Execute()

The size of Hlix's shared company index and how many of the workspace's companies it supplied

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthIndexStats(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthIndexStats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthIndexStats`: GrowthIndexStats
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthIndexStats`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthIndexStatsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthIndexStats**](GrowthIndexStats.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthOverview

> GrowthOverview GetGrowthOverview(ctx, projectId).Days(days).CampaignId(campaignId).XOrganizationId(xOrganizationId).Execute()

A growth project's outreach, hot leads and spend per day, with its daily budget

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
	days := "days_example" // string | 7 (default) or 30 UTC days ending today. (optional)
	campaignId := "campaignId_example" // string | Only this campaign of the project. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthOverview(context.Background(), projectId).Days(days).CampaignId(campaignId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthOverview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthOverview`: GrowthOverview
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthOverview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthOverviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **days** | **string** | 7 (default) or 30 UTC days ending today. | 
 **campaignId** | **string** | Only this campaign of the project. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthOverview**](GrowthOverview.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthProject

> GrowthState GetGrowthProject(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Show a growth project's brain, campaigns and last run

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthProject(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthProject`: GrowthState
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthState**](GrowthState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthSendingSchedule

> GrowthProjectSendingSchedule GetGrowthSendingSchedule(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Resolve project and campaign sending schedules

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthSendingSchedule(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthSendingSchedule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthSendingSchedule`: GrowthProjectSendingSchedule
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthSendingSchedule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthSendingScheduleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProjectSendingSchedule**](GrowthProjectSendingSchedule.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthSettings

> GrowthSettingsState GetGrowthSettings(ctx).XOrganizationId(xOrganizationId).Execute()

The workspace's growth settings and this month's growth spend

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthSettings(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthSettings`: GrowthSettingsState
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthSettingsState**](GrowthSettingsState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthSpend

> []GrowthPlaySpend GetGrowthSpend(ctx, projectId).XOrganizationId(xOrganizationId).Execute()

Show each campaign's data-provider spend for today and the last 30 days

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthSpend(context.Background(), projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthSpend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthSpend`: []GrowthPlaySpend
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthSpend`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthSpendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]GrowthPlaySpend**](GrowthPlaySpend.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthThread

> GrowthThread GetGrowthThread(ctx, leadId).XOrganizationId(xOrganizationId).Execute()

Show a lead's whole email thread, drafts included

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
	leadId := "leadId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthThread(context.Background(), leadId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthThread``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthThread`: GrowthThread
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthThread`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**leadId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetGrowthThreadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthThread**](GrowthThread.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedMailboxConfiguration

> ManagedMailboxConfiguration GetManagedMailboxConfiguration(ctx).XOrganizationId(xOrganizationId).Execute()

Read managed mailbox configuration and commercial readiness

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
	resp, r, err := apiClient.GrowthAPI.GetManagedMailboxConfiguration(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetManagedMailboxConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedMailboxConfiguration`: ManagedMailboxConfiguration
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetManagedMailboxConfiguration`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedMailboxConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxConfiguration**](ManagedMailboxConfiguration.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedMailboxOrder

> ManagedMailboxOrder GetManagedMailboxOrder(ctx, orderId).XOrganizationId(xOrganizationId).Execute()

Read a saved managed mailbox order

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
	orderId := "orderId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetManagedMailboxOrder(context.Background(), orderId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetManagedMailboxOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedMailboxOrder`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetManagedMailboxOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedMailboxOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportGrowthToolResult

> GrowthToolResultImport ImportGrowthToolResult(ctx, projectId).ImportGrowthToolResult(importGrowthToolResult).XOrganizationId(xOrganizationId).Execute()

Import the people a completed tool call returned

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
	importGrowthToolResult := *openapiclient.NewImportGrowthToolResult("CallId_example") // ImportGrowthToolResult | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ImportGrowthToolResult(context.Background(), projectId).ImportGrowthToolResult(importGrowthToolResult).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ImportGrowthToolResult``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImportGrowthToolResult`: GrowthToolResultImport
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ImportGrowthToolResult`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiImportGrowthToolResultRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importGrowthToolResult** | [**ImportGrowthToolResult**](ImportGrowthToolResult.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthToolResultImport**](GrowthToolResultImport.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthBatches

> GrowthBatchPage ListGrowthBatches(ctx, projectId).PlayId(playId).BatchId(batchId).XOrganizationId(xOrganizationId).Execute()

Research lists and their twelve-hour review deadlines

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
	playId := "playId_example" // string | Only this campaign's research batches. (optional)
	batchId := "batchId_example" // string | One batch, including older emailed lists. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthBatches(context.Background(), projectId).PlayId(playId).BatchId(batchId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthBatches``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthBatches`: GrowthBatchPage
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthBatches`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthBatchesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **playId** | **string** | Only this campaign&#39;s research batches. | 
 **batchId** | **string** | One batch, including older emailed lists. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthBatchPage**](GrowthBatchPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthChains

> []GrowthChain ListGrowthChains(ctx).XOrganizationId(xOrganizationId).Execute()

Each capability's data-provider order and how each provider did in the last 7 days

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
	resp, r, err := apiClient.GrowthAPI.ListGrowthChains(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthChains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthChains`: []GrowthChain
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthChains`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthChainsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]GrowthChain**](GrowthChain.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthCitableProjects

> []GrowthCitableProject ListGrowthCitableProjects(ctx).XOrganizationId(xOrganizationId).Execute()

List the finished delivery projects a growth brain may quote

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
	resp, r, err := apiClient.GrowthAPI.ListGrowthCitableProjects(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthCitableProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthCitableProjects`: []GrowthCitableProject
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthCitableProjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthCitableProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]GrowthCitableProject**](GrowthCitableProject.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthInbox

> GrowthInboxPage ListGrowthInbox(ctx, projectId).Filter(filter).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

List a growth project's email threads, one per lead

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
	filter := "filter_example" // string | needs_reply (they wrote and nobody answered), hot (needs_reply where the newest reply reads as interested), replies (every thread with a reply), replied, sent (no reply yet), review (emails waiting for approval) or unknown (emails whose delivery a person has to confirm). (optional)
	limit := "limit_example" // string | Page size, 1–100; default 50. (optional)
	offset := "offset_example" // string | How many threads to skip; default 0. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthInbox(context.Background(), projectId).Filter(filter).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthInbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthInbox`: GrowthInboxPage
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthInbox`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthInboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **filter** | **string** | needs_reply (they wrote and nobody answered), hot (needs_reply where the newest reply reads as interested), replies (every thread with a reply), replied, sent (no reply yet), review (emails waiting for approval) or unknown (emails whose delivery a person has to confirm). | 
 **limit** | **string** | Page size, 1–100; default 50. | 
 **offset** | **string** | How many threads to skip; default 0. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthInboxPage**](GrowthInboxPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthLeads

> GrowthLeadPage ListGrowthLeads(ctx, projectId).Query(query).LeadId(leadId).PlayId(playId).BatchId(batchId).Status(status).MinFit(minFit).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

List a growth project's leads with their evidence and provenance

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
	query := "query_example" // string | Search company, contact and evidence text; literal match, up to 200 characters. (optional)
	leadId := "leadId_example" // string | One lead within this project, including all evidence and provenance. (optional)
	playId := "playId_example" // string | Only this campaign's leads. (optional)
	batchId := "batchId_example" // string | Only leads from this research batch. (optional)
	status := "status_example" // string | Only leads in this status: new, queued, contacted, replied, converted, disqualified or opted_out. (optional)
	minFit := "minFit_example" // string | Only leads whose fit score (0–100) is at least this. (optional)
	limit := "limit_example" // string | Page size, 1–200; default 50. (optional)
	offset := "offset_example" // string | How many leads to skip; default 0. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthLeads(context.Background(), projectId).Query(query).LeadId(leadId).PlayId(playId).BatchId(batchId).Status(status).MinFit(minFit).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthLeads``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthLeads`: GrowthLeadPage
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthLeads`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthLeadsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **query** | **string** | Search company, contact and evidence text; literal match, up to 200 characters. | 
 **leadId** | **string** | One lead within this project, including all evidence and provenance. | 
 **playId** | **string** | Only this campaign&#39;s leads. | 
 **batchId** | **string** | Only leads from this research batch. | 
 **status** | **string** | Only leads in this status: new, queued, contacted, replied, converted, disqualified or opted_out. | 
 **minFit** | **string** | Only leads whose fit score (0–100) is at least this. | 
 **limit** | **string** | Page size, 1–200; default 50. | 
 **offset** | **string** | How many leads to skip; default 0. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthLeadPage**](GrowthLeadPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthMailboxes

> GrowthMailboxList ListGrowthMailboxes(ctx).IncludeDisconnected(includeDisconnected).XOrganizationId(xOrganizationId).Execute()

List the workspace's sending mailboxes with their warm-up and today's sends

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
	includeDisconnected := "includeDisconnected_example" // string | `true` also lists mailboxes that were disconnected; by default only the ones that can send are listed. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthMailboxes(context.Background()).IncludeDisconnected(includeDisconnected).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthMailboxes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthMailboxes`: GrowthMailboxList
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthMailboxes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthMailboxesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includeDisconnected** | **string** | &#x60;true&#x60; also lists mailboxes that were disconnected; by default only the ones that can send are listed. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMailboxList**](GrowthMailboxList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthProviders

> []GrowthProvider ListGrowthProviders(ctx).XOrganizationId(xOrganizationId).Execute()

List growth data providers and the workspace's key state

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
	resp, r, err := apiClient.GrowthAPI.ListGrowthProviders(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthProviders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthProviders`: []GrowthProvider
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthProviders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthProvidersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGrowthSuppressions

> GrowthSuppressionPage ListGrowthSuppressions(ctx).Query(query).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

List the do-not-contact list

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
	query := "query_example" // string | Only entries whose address or domain contains this. (optional)
	limit := "limit_example" // string | Page size, 1–200; default 50. (optional)
	offset := "offset_example" // string | How many entries to skip; default 0. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthSuppressions(context.Background()).Query(query).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListGrowthSuppressions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGrowthSuppressions`: GrowthSuppressionPage
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListGrowthSuppressions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListGrowthSuppressionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Only entries whose address or domain contains this. | 
 **limit** | **string** | Page size, 1–200; default 50. | 
 **offset** | **string** | How many entries to skip; default 0. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthSuppressionPage**](GrowthSuppressionPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListManagedMailboxOrders

> ManagedMailboxOrderList ListManagedMailboxOrders(ctx).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()

List managed mailbox orders

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
	limit := "limit_example" // string | 1–50, defaults to 20. (optional)
	cursor := "cursor_example" // string | nextCursor from the previous page. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListManagedMailboxOrders(context.Background()).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListManagedMailboxOrders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListManagedMailboxOrders`: ManagedMailboxOrderList
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListManagedMailboxOrders`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListManagedMailboxOrdersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | 1–50, defaults to 20. | 
 **cursor** | **string** | nextCursor from the previous page. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrderList**](ManagedMailboxOrderList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListManagedMailboxResources

> ManagedMailboxResourceList ListManagedMailboxResources(ctx).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()

List managed domains and mailbox resources

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
	limit := "limit_example" // string | 1–50, defaults to 20. (optional)
	cursor := "cursor_example" // string | nextCursor from the previous page. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListManagedMailboxResources(context.Background()).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ListManagedMailboxResources``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListManagedMailboxResources`: ManagedMailboxResourceList
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ListManagedMailboxResources`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListManagedMailboxResourcesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | 1–50, defaults to 20. | 
 **cursor** | **string** | nextCursor from the previous page. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxResourceList**](ManagedMailboxResourceList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrderManagedMailboxes

> ManagedMailboxOrder OrderManagedMailboxes(ctx).ManagedMailboxOrderInput(managedMailboxOrderInput).XOrganizationId(xOrganizationId).Execute()

Persist a managed mailbox order before provider dispatch

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
	managedMailboxOrderInput := *openapiclient.NewManagedMailboxOrderInput(*openapiclient.NewManagedMailboxOrderInputContact("AddressLine1_example", "City_example", "Country_example", "Email_example", "FirstName_example", "LastName_example", "PostalCode_example", "State_example"), "IdempotencyKey_example", "QuoteId_example") // ManagedMailboxOrderInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.OrderManagedMailboxes(context.Background()).ManagedMailboxOrderInput(managedMailboxOrderInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.OrderManagedMailboxes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrderManagedMailboxes`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.OrderManagedMailboxes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiOrderManagedMailboxesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managedMailboxOrderInput** | [**ManagedMailboxOrderInput**](ManagedMailboxOrderInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreviewGrowthLeadExport

> GrowthLeadExportPreview PreviewGrowthLeadExport(ctx, projectId).GrowthLeadExportFilters(growthLeadExportFilters).XOrganizationId(xOrganizationId).Execute()

What exporting the matching leads would cost, before exporting

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
	growthLeadExportFilters := *openapiclient.NewGrowthLeadExportFilters() // GrowthLeadExportFilters | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.PreviewGrowthLeadExport(context.Background(), projectId).GrowthLeadExportFilters(growthLeadExportFilters).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.PreviewGrowthLeadExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreviewGrowthLeadExport`: GrowthLeadExportPreview
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.PreviewGrowthLeadExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPreviewGrowthLeadExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **growthLeadExportFilters** | [**GrowthLeadExportFilters**](GrowthLeadExportFilters.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthLeadExportPreview**](GrowthLeadExportPreview.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## QuoteManagedMailboxes

> ManagedMailboxQuote QuoteManagedMailboxes(ctx).ManagedMailboxQuoteInput(managedMailboxQuoteInput).XOrganizationId(xOrganizationId).Execute()

Observe domain availability and recurring mailbox prices

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
	managedMailboxQuoteInput := *openapiclient.NewManagedMailboxQuoteInput([]openapiclient.ManagedMailboxQuoteInputDomainsInner{*openapiclient.NewManagedMailboxQuoteInputDomainsInner([]openapiclient.ManagedMailboxQuoteInputDomainsInnerMailboxesInner{*openapiclient.NewManagedMailboxQuoteInputDomainsInnerMailboxesInner("FirstName_example", "LastName_example", "Username_example")}, "Name_example")}) // ManagedMailboxQuoteInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.QuoteManagedMailboxes(context.Background()).ManagedMailboxQuoteInput(managedMailboxQuoteInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.QuoteManagedMailboxes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QuoteManagedMailboxes`: ManagedMailboxQuote
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.QuoteManagedMailboxes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiQuoteManagedMailboxesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managedMailboxQuoteInput** | [**ManagedMailboxQuoteInput**](ManagedMailboxQuoteInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxQuote**](ManagedMailboxQuote.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReconcileManagedMailboxOrder

> ManagedMailboxOrder ReconcileManagedMailboxOrder(ctx, orderId).XOrganizationId(xOrganizationId).Execute()

Reconcile provider evidence without replaying uncertain purchases

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
	orderId := "orderId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ReconcileManagedMailboxOrder(context.Background(), orderId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ReconcileManagedMailboxOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReconcileManagedMailboxOrder`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ReconcileManagedMailboxOrder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**orderId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReconcileManagedMailboxOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RefineGrowthReply

> GrowthRefinedReply RefineGrowthReply(ctx, leadId).RefineGrowthReply(refineGrowthReply).XOrganizationId(xOrganizationId).Execute()

Refine a reply against the lead thread and sourced project context without sending

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
	leadId := "leadId_example" // string | 
	refineGrowthReply := *openapiclient.NewRefineGrowthReply("Body_example", "Instruction_example") // RefineGrowthReply | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RefineGrowthReply(context.Background(), leadId).RefineGrowthReply(refineGrowthReply).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.RefineGrowthReply``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RefineGrowthReply`: GrowthRefinedReply
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.RefineGrowthReply`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**leadId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRefineGrowthReplyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **refineGrowthReply** | [**RefineGrowthReply**](RefineGrowthReply.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthRefinedReply**](GrowthRefinedReply.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveGrowthProviderKey

> GrowthProvider RemoveGrowthProviderKey(ctx, provider).XOrganizationId(xOrganizationId).Execute()

Remove the workspace's own key for a growth provider

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
	provider := "provider_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RemoveGrowthProviderKey(context.Background(), provider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.RemoveGrowthProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveGrowthProviderKey`: GrowthProvider
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.RemoveGrowthProviderKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveGrowthProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveGrowthSuppression

> GrowthSuppressionRemoved RemoveGrowthSuppression(ctx, suppressionId).XOrganizationId(xOrganizationId).Execute()

Remove an entry a person added to the do-not-contact list

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
	suppressionId := "suppressionId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RemoveGrowthSuppression(context.Background(), suppressionId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.RemoveGrowthSuppression``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveGrowthSuppression`: GrowthSuppressionRemoved
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.RemoveGrowthSuppression`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**suppressionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveGrowthSuppressionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthSuppressionRemoved**](GrowthSuppressionRemoved.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveManagedMailboxDomain

> ManagedMailboxOrder RemoveManagedMailboxDomain(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()

Request domain removal without claiming a refund or renewal cancellation

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
	resourceId := "resourceId_example" // string | 
	managedMailboxResourceActionInput := *openapiclient.NewManagedMailboxResourceActionInput("IdempotencyKey_example") // ManagedMailboxResourceActionInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RemoveManagedMailboxDomain(context.Background(), resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.RemoveManagedMailboxDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveManagedMailboxDomain`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.RemoveManagedMailboxDomain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**resourceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveManagedMailboxDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RepairManagedMailboxResource

> ManagedMailboxOrder RepairManagedMailboxResource(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()

Repair a failed resource step without repurchasing successful resources

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
	resourceId := "resourceId_example" // string | 
	managedMailboxResourceActionInput := *openapiclient.NewManagedMailboxResourceActionInput("IdempotencyKey_example") // ManagedMailboxResourceActionInput | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RepairManagedMailboxResource(context.Background(), resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.RepairManagedMailboxResource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairManagedMailboxResource`: ManagedMailboxOrder
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.RepairManagedMailboxResource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**resourceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRepairManagedMailboxResourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RerunGrowthProject

> GrowthRun RerunGrowthProject(ctx, projectId).RerunGrowth(rerunGrowth).XOrganizationId(xOrganizationId).Execute()

Run the website research again

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
	rerunGrowth := *openapiclient.NewRerunGrowth() // RerunGrowth | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RerunGrowthProject(context.Background(), projectId).RerunGrowth(rerunGrowth).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.RerunGrowthProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RerunGrowthProject`: GrowthRun
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.RerunGrowthProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRerunGrowthProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rerunGrowth** | [**RerunGrowth**](RerunGrowth.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthRun**](GrowthRun.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResearchGrowthPlay

> GrowthResearchResult ResearchGrowthPlay(ctx, playId).XOrganizationId(xOrganizationId).Execute()

Find or resume leads for one campaign without repeating completed research

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
	playId := "playId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ResearchGrowthPlay(context.Background(), playId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ResearchGrowthPlay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResearchGrowthPlay`: GrowthResearchResult
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ResearchGrowthPlay`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResearchGrowthPlayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthResearchResult**](GrowthResearchResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResolveGrowthMessage

> GrowthMessageResolved ResolveGrowthMessage(ctx, messageId).ResolveGrowthMessage(resolveGrowthMessage).XOrganizationId(xOrganizationId).Execute()

Record whether an email whose delivery was unknown went out

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
	messageId := "messageId_example" // string | 
	resolveGrowthMessage := *openapiclient.NewResolveGrowthMessage(false) // ResolveGrowthMessage | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ResolveGrowthMessage(context.Background(), messageId).ResolveGrowthMessage(resolveGrowthMessage).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ResolveGrowthMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResolveGrowthMessage`: GrowthMessageResolved
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ResolveGrowthMessage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**messageId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResolveGrowthMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resolveGrowthMessage** | [**ResolveGrowthMessage**](ResolveGrowthMessage.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMessageResolved**](GrowthMessageResolved.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveGrowthProviderKey

> GrowthProvider SaveGrowthProviderKey(ctx, provider).SaveGrowthProviderKey(saveGrowthProviderKey).XOrganizationId(xOrganizationId).Execute()

Add or replace the workspace's own key for a growth provider

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
	provider := "provider_example" // string | 
	saveGrowthProviderKey := *openapiclient.NewSaveGrowthProviderKey("ApiKey_example") // SaveGrowthProviderKey | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SaveGrowthProviderKey(context.Background(), provider).SaveGrowthProviderKey(saveGrowthProviderKey).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.SaveGrowthProviderKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveGrowthProviderKey`: GrowthProvider
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.SaveGrowthProviderKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaveGrowthProviderKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **saveGrowthProviderKey** | [**SaveGrowthProviderKey**](SaveGrowthProviderKey.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchGrowthIndex

> GrowthIndexSearchPage SearchGrowthIndex(ctx).Query(query).Countries(countries).Sizes(sizes).Title(title).Seniorities(seniorities).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

Search Hlix's shared index of companies and their people

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
	query := "query_example" // string | Text in the company's name, description or domain. (optional)
	countries := "countries_example" // string | Company countries, ISO codes, comma-separated (DE,AT). (optional)
	sizes := "sizes_example" // string | Company size bands, comma-separated (11-50,51-200). (optional)
	title := "title_example" // string | Text in a person's title; only companies with such a person are returned. (optional)
	seniorities := "seniorities_example" // string | Seniority levels, comma-separated (Director,C-Level); only companies with such a person are returned. (optional)
	limit := "limit_example" // string | Companies per page, 1–100; default 25. (optional)
	offset := "offset_example" // string | How many companies to skip, 0–2,000; default 0. Narrow the filters to reach further. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SearchGrowthIndex(context.Background()).Query(query).Countries(countries).Sizes(sizes).Title(title).Seniorities(seniorities).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.SearchGrowthIndex``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchGrowthIndex`: GrowthIndexSearchPage
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.SearchGrowthIndex`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchGrowthIndexRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Text in the company&#39;s name, description or domain. | 
 **countries** | **string** | Company countries, ISO codes, comma-separated (DE,AT). | 
 **sizes** | **string** | Company size bands, comma-separated (11-50,51-200). | 
 **title** | **string** | Text in a person&#39;s title; only companies with such a person are returned. | 
 **seniorities** | **string** | Seniority levels, comma-separated (Director,C-Level); only companies with such a person are returned. | 
 **limit** | **string** | Companies per page, 1–100; default 25. | 
 **offset** | **string** | How many companies to skip, 0–2,000; default 0. Narrow the filters to reach further. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthIndexSearchPage**](GrowthIndexSearchPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendGrowthReply

> GrowthReplySent SendGrowthReply(ctx, leadId).SendGrowthReply(sendGrowthReply).XOrganizationId(xOrganizationId).Execute()

Answer a lead in their thread from the mailbox that wrote to them

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
	leadId := "leadId_example" // string | 
	sendGrowthReply := *openapiclient.NewSendGrowthReply("Body_example") // SendGrowthReply | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SendGrowthReply(context.Background(), leadId).SendGrowthReply(sendGrowthReply).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.SendGrowthReply``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendGrowthReply`: GrowthReplySent
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.SendGrowthReply`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**leadId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendGrowthReplyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sendGrowthReply** | [**SendGrowthReply**](SendGrowthReply.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthReplySent**](GrowthReplySent.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetGrowthAutopilot

> GrowthAutopilot SetGrowthAutopilot(ctx, projectId).UpdateGrowthAutopilot(updateGrowthAutopilot).XOrganizationId(xOrganizationId).Execute()

Turn the project's budget autopilot on or off

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
	updateGrowthAutopilot := *openapiclient.NewUpdateGrowthAutopilot(false) // UpdateGrowthAutopilot | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SetGrowthAutopilot(context.Background(), projectId).UpdateGrowthAutopilot(updateGrowthAutopilot).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.SetGrowthAutopilot``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetGrowthAutopilot`: GrowthAutopilot
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.SetGrowthAutopilot`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetGrowthAutopilotRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthAutopilot** | [**UpdateGrowthAutopilot**](UpdateGrowthAutopilot.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthAutopilot**](GrowthAutopilot.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetGrowthProjectBudget

> GrowthProjectBudget SetGrowthProjectBudget(ctx, projectId).UpdateGrowthProjectBudget(updateGrowthProjectBudget).XOrganizationId(xOrganizationId).Execute()

Set or remove what all of a growth project's campaigns may spend per day

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
	updateGrowthProjectBudget := *openapiclient.NewUpdateGrowthProjectBudget(NullableInt64(123)) // UpdateGrowthProjectBudget | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SetGrowthProjectBudget(context.Background(), projectId).UpdateGrowthProjectBudget(updateGrowthProjectBudget).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.SetGrowthProjectBudget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetGrowthProjectBudget`: GrowthProjectBudget
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.SetGrowthProjectBudget`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetGrowthProjectBudgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthProjectBudget** | [**UpdateGrowthProjectBudget**](UpdateGrowthProjectBudget.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProjectBudget**](GrowthProjectBudget.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthBrain

> GrowthBrainRow UpdateGrowthBrain(ctx, projectId).GrowthBrain(growthBrain).XOrganizationId(xOrganizationId).Execute()

Replace the Company brain

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
	growthBrain := *openapiclient.NewGrowthBrain([]openapiclient.GrowthBrainCompetitorsInner{*openapiclient.NewGrowthBrainCompetitorsInner("Name_example", "Reason_example", "Source_example")}, []openapiclient.GrowthBrainLanguagesInner{*openapiclient.NewGrowthBrainLanguagesInner("Source_example", "Value_example")}, []string{"NeverSay_example"}, "TODO", "TODO", []openapiclient.GrowthBrainOffer{nil}) // GrowthBrain | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthBrain(context.Background(), projectId).GrowthBrain(growthBrain).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthBrain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthBrain`: GrowthBrainRow
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthBrain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthBrainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **growthBrain** | [**GrowthBrain**](GrowthBrain.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthBrainRow**](GrowthBrainRow.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthChain

> GrowthChainUpdated UpdateGrowthChain(ctx, capability).UpdateGrowthChain(updateGrowthChain).XOrganizationId(xOrganizationId).Execute()

Set the order a capability tries its providers in, or go back to the default

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
	capability := "capability_example" // string | 
	updateGrowthChain := *openapiclient.NewUpdateGrowthChain([]string{"Order_example"}) // UpdateGrowthChain | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthChain(context.Background(), capability).UpdateGrowthChain(updateGrowthChain).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthChain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthChain`: GrowthChainUpdated
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthChain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**capability** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthChainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthChain** | [**UpdateGrowthChain**](UpdateGrowthChain.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthChainUpdated**](GrowthChainUpdated.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthLead

> GrowthLeadStatus UpdateGrowthLead(ctx, leadId).UpdateGrowthLead(updateGrowthLead).XOrganizationId(xOrganizationId).Execute()

Disqualify a lead or put it back in line

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
	leadId := "leadId_example" // string | 
	updateGrowthLead := *openapiclient.NewUpdateGrowthLead("Status_example") // UpdateGrowthLead | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthLead(context.Background(), leadId).UpdateGrowthLead(updateGrowthLead).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthLead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthLead`: GrowthLeadStatus
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthLead`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**leadId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthLeadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthLead** | [**UpdateGrowthLead**](UpdateGrowthLead.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthLeadStatus**](GrowthLeadStatus.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthMailbox

> GrowthMailbox UpdateGrowthMailbox(ctx, mailboxId).UpdateGrowthMailbox(updateGrowthMailbox).XOrganizationId(xOrganizationId).Execute()

Change a mailbox's daily limit or warm-up start, or pause and resume it

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
	mailboxId := "mailboxId_example" // string | 
	updateGrowthMailbox := *openapiclient.NewUpdateGrowthMailbox() // UpdateGrowthMailbox | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthMailbox(context.Background(), mailboxId).UpdateGrowthMailbox(updateGrowthMailbox).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthMailbox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthMailbox`: GrowthMailbox
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthMailbox`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**mailboxId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthMailboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthMailbox** | [**UpdateGrowthMailbox**](UpdateGrowthMailbox.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthMailbox**](GrowthMailbox.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthPlay

> GrowthPlay UpdateGrowthPlay(ctx, playId).UpdateGrowthPlay(updateGrowthPlay).XOrganizationId(xOrganizationId).Execute()

Edit or launch a campaign

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
	playId := "playId_example" // string | 
	updateGrowthPlay := *openapiclient.NewUpdateGrowthPlay() // UpdateGrowthPlay | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthPlay(context.Background(), playId).UpdateGrowthPlay(updateGrowthPlay).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthPlay``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthPlay`: GrowthPlay
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthPlay`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**playId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthPlayRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthPlay** | [**UpdateGrowthPlay**](UpdateGrowthPlay.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthPlay**](GrowthPlay.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthProvider

> GrowthProvider UpdateGrowthProvider(ctx, provider).UpdateGrowthProvider(updateGrowthProvider).XOrganizationId(xOrganizationId).Execute()

Turn a growth provider on or off for the workspace, or change its settings

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
	provider := "provider_example" // string | 
	updateGrowthProvider := *openapiclient.NewUpdateGrowthProvider() // UpdateGrowthProvider | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthProvider(context.Background(), provider).UpdateGrowthProvider(updateGrowthProvider).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthProvider`: GrowthProvider
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthProvider** | [**UpdateGrowthProvider**](UpdateGrowthProvider.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthSendingSchedule

> GrowthProjectSendingSchedule UpdateGrowthSendingSchedule(ctx, projectId).UpdateGrowthSendingSchedule(updateGrowthSendingSchedule).XOrganizationId(xOrganizationId).Execute()

Set or inherit a project's sending schedule

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
	updateGrowthSendingSchedule := *openapiclient.NewUpdateGrowthSendingSchedule("TODO") // UpdateGrowthSendingSchedule | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthSendingSchedule(context.Background(), projectId).UpdateGrowthSendingSchedule(updateGrowthSendingSchedule).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthSendingSchedule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthSendingSchedule`: GrowthProjectSendingSchedule
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthSendingSchedule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthSendingScheduleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthSendingSchedule** | [**UpdateGrowthSendingSchedule**](UpdateGrowthSendingSchedule.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthProjectSendingSchedule**](GrowthProjectSendingSchedule.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthSettings

> GrowthSettingsState UpdateGrowthSettings(ctx).UpdateGrowthSettings(updateGrowthSettings).XOrganizationId(xOrganizationId).Execute()

Change the hard cap, the sending rules or the booking link

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
	updateGrowthSettings := *openapiclient.NewUpdateGrowthSettings() // UpdateGrowthSettings | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthSettings(context.Background()).UpdateGrowthSettings(updateGrowthSettings).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UpdateGrowthSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateGrowthSettings`: GrowthSettingsState
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UpdateGrowthSettings`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateGrowthSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateGrowthSettings** | [**UpdateGrowthSettings**](UpdateGrowthSettings.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthSettingsState**](GrowthSettingsState.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadGrowthLeadList

> GrowthLeadListResult UploadGrowthLeadList(ctx, projectId).UploadGrowthLeadList(uploadGrowthLeadList).XOrganizationId(xOrganizationId).Execute()

Upload a lead list to a growth project

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
	uploadGrowthLeadList := *openapiclient.NewUploadGrowthLeadList("Csv_example", "FileName_example") // UploadGrowthLeadList | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UploadGrowthLeadList(context.Background(), projectId).UploadGrowthLeadList(uploadGrowthLeadList).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.UploadGrowthLeadList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadGrowthLeadList`: GrowthLeadListResult
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.UploadGrowthLeadList`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadGrowthLeadListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **uploadGrowthLeadList** | [**UploadGrowthLeadList**](UploadGrowthLeadList.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**GrowthLeadListResult**](GrowthLeadListResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

