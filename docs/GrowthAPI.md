# GrowthAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddGrowthIndexLeads**](GrowthAPI.md#addgrowthindexleads) | **Post** /v1/api/growth/projects/{projectId}/index-leads | Add people and companies from Hlix&#39;s shared index to a growth project
[**AddGrowthSuppressions**](GrowthAPI.md#addgrowthsuppressions) | **Post** /v1/api/growth/suppressions | Add addresses and domains to the do-not-contact list
[**ApproveGrowthBatch**](GrowthAPI.md#approvegrowthbatch) | **Post** /v1/api/growth/projects/{projectId}/batches/{batchId}/approve | Release a researched lead list before its review deadline
[**ApproveGrowthMessage**](GrowthAPI.md#approvegrowthmessage) | **Post** /v1/api/growth/messages/{messageId}/approve | Approve a drafted email, optionally edited, so it sends
[**CancelManagedMailboxHosting**](GrowthAPI.md#cancelmanagedmailboxhosting) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/cancel-hosting | Block new cold sends immediately and request hosting cancellation
[**CancelManagedMailboxWarmup**](GrowthAPI.md#cancelmanagedmailboxwarmup) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/cancel-warmup | Cancel warmup separately from mailbox hosting
[**CheckGrowthMailboxDns**](GrowthAPI.md#checkgrowthmailboxdns) | **Get** /v1/api/growth/mailboxes/{mailboxId}/dns | Check the mailbox domain&#39;s SPF, DKIM and DMARC records
[**ClassifyGrowthMessage**](GrowthAPI.md#classifygrowthmessage) | **Patch** /v1/api/growth/messages/{messageId} | Sort a reply by hand
[**CompareGrowthProviders**](GrowthAPI.md#comparegrowthproviders) | **Post** /v1/api/growth/chains/find_email/compare | Run two email finders on the same sample of the workspace&#39;s leads
[**ConnectGrowthMailbox**](GrowthAPI.md#connectgrowthmailbox) | **Post** /v1/api/growth/mailboxes/connect | Start connecting a Google or Microsoft mailbox to send from
[**ConnectGrowthSendkit**](GrowthAPI.md#connectgrowthsendkit) | **Post** /v1/api/growth/sendkit/connect | Verify and bind the deployment-configured SendKit workspace
[**CreateGrowthPlay**](GrowthAPI.md#creategrowthplay) | **Post** /v1/api/growth/projects/{projectId}/plays | Create one campaign
[**CreateGrowthProject**](GrowthAPI.md#creategrowthproject) | **Post** /v1/api/growth/projects | Create a growth project from a website and start its research run
[**DisconnectGrowthMailbox**](GrowthAPI.md#disconnectgrowthmailbox) | **Delete** /v1/api/growth/mailboxes/{mailboxId} | Disconnect a mailbox and revoke its access
[**DownloadGrowthLeadExport**](GrowthAPI.md#downloadgrowthleadexport) | **Get** /v1/api/growth/projects/{projectId}/lead-exports/{exportId} | Download a project&#39;s lead CSV export
[**ExportGrowthLeads**](GrowthAPI.md#exportgrowthleads) | **Post** /v1/api/growth/projects/{projectId}/leads/export | Export all matching leads to CSV
[**GetGrowthEnrichPrice**](GrowthAPI.md#getgrowthenrichprice) | **Get** /v1/api/growth/enrich | Hlix Enrich price: what one email sent to a lead built on Hlix&#39;s data costs
[**GetGrowthIndexStats**](GrowthAPI.md#getgrowthindexstats) | **Get** /v1/api/growth/index | The size of Hlix&#39;s shared company index and how many of the workspace&#39;s companies it supplied
[**GetGrowthOverview**](GrowthAPI.md#getgrowthoverview) | **Get** /v1/api/growth/projects/{projectId}/overview | A growth project&#39;s outreach, hot leads and spend per day, with its daily budget
[**GetGrowthProject**](GrowthAPI.md#getgrowthproject) | **Get** /v1/api/growth/projects/{projectId} | Show a growth project&#39;s brain, campaigns and last run
[**GetGrowthSendingSchedule**](GrowthAPI.md#getgrowthsendingschedule) | **Get** /v1/api/growth/projects/{projectId}/sending-schedule | Resolve project and campaign sending schedules
[**GetGrowthSendkitConnection**](GrowthAPI.md#getgrowthsendkitconnection) | **Get** /v1/api/growth/sendkit | Inspect the workspace&#39;s SendKit connection and mailbox inventory
[**GetGrowthSettings**](GrowthAPI.md#getgrowthsettings) | **Get** /v1/api/growth/settings | The workspace&#39;s growth settings and this month&#39;s growth spend
[**GetGrowthSpend**](GrowthAPI.md#getgrowthspend) | **Get** /v1/api/growth/projects/{projectId}/spend | Show each campaign&#39;s data-provider spend for today and the last 30 days
[**GetGrowthThread**](GrowthAPI.md#getgrowththread) | **Get** /v1/api/growth/leads/{leadId}/thread | Show a lead&#39;s whole email thread, drafts included
[**GetManagedMailboxConfiguration**](GrowthAPI.md#getmanagedmailboxconfiguration) | **Get** /v1/api/growth/managed-mailboxes/configuration | Read managed mailbox configuration and commercial readiness
[**GetManagedMailboxOrder**](GrowthAPI.md#getmanagedmailboxorder) | **Get** /v1/api/growth/managed-mailboxes/orders/{orderId} | Read a saved managed mailbox order
[**ImportGrowthToolResult**](GrowthAPI.md#importgrowthtoolresult) | **Post** /v1/api/growth/projects/{projectId}/lead-lists/from-tool-call | Import the people a completed tool call returned
[**ImportManagedMailboxes**](GrowthAPI.md#importmanagedmailboxes) | **Post** /v1/api/growth/managed-mailboxes/import | Connect existing InboxKit domains and mailboxes without purchasing them again
[**ListGrowthBatches**](GrowthAPI.md#listgrowthbatches) | **Get** /v1/api/growth/projects/{projectId}/batches | Research lists and their twelve-hour review deadlines
[**ListGrowthChains**](GrowthAPI.md#listgrowthchains) | **Get** /v1/api/growth/chains | Each capability&#39;s data-provider order and how each provider did in the last 7 days
[**ListGrowthCitableProjects**](GrowthAPI.md#listgrowthcitableprojects) | **Get** /v1/api/growth/citable-projects | List the finished delivery projects a growth brain may quote
[**ListGrowthInbox**](GrowthAPI.md#listgrowthinbox) | **Get** /v1/api/growth/projects/{projectId}/inbox | List a growth project&#39;s email threads, one per lead
[**ListGrowthLeads**](GrowthAPI.md#listgrowthleads) | **Get** /v1/api/growth/projects/{projectId}/leads | List a growth project&#39;s leads with their evidence and provenance
[**ListGrowthMailboxes**](GrowthAPI.md#listgrowthmailboxes) | **Get** /v1/api/growth/mailboxes | List the workspace&#39;s sending mailboxes with their warm-up and today&#39;s sends
[**ListGrowthProviders**](GrowthAPI.md#listgrowthproviders) | **Get** /v1/api/growth/providers | List growth data providers and the workspace&#39;s key state
[**ListGrowthSuppressions**](GrowthAPI.md#listgrowthsuppressions) | **Get** /v1/api/growth/suppressions | List the do-not-contact list
[**ListManagedMailboxOrders**](GrowthAPI.md#listmanagedmailboxorders) | **Get** /v1/api/growth/managed-mailboxes/orders | List managed mailbox orders
[**ListManagedMailboxResources**](GrowthAPI.md#listmanagedmailboxresources) | **Get** /v1/api/growth/managed-mailboxes/resources | List managed domains and mailbox resources
[**OrderManagedMailboxes**](GrowthAPI.md#ordermanagedmailboxes) | **Post** /v1/api/growth/managed-mailboxes/orders | Persist a managed mailbox order before provider dispatch
[**PreviewGrowthLeadExport**](GrowthAPI.md#previewgrowthleadexport) | **Post** /v1/api/growth/projects/{projectId}/leads/export/preview | What exporting the matching leads would cost, before exporting
[**QuoteManagedMailboxes**](GrowthAPI.md#quotemanagedmailboxes) | **Post** /v1/api/growth/managed-mailboxes/quotes | Observe domain availability and recurring mailbox prices
[**ReconcileManagedMailboxOrder**](GrowthAPI.md#reconcilemanagedmailboxorder) | **Post** /v1/api/growth/managed-mailboxes/orders/{orderId}/reconcile | Reconcile provider evidence without replaying uncertain purchases
[**RefineGrowthReply**](GrowthAPI.md#refinegrowthreply) | **Post** /v1/api/growth/leads/{leadId}/refine-reply | Refine a reply against the lead thread and sourced project context without sending
[**RemoveGrowthProviderKey**](GrowthAPI.md#removegrowthproviderkey) | **Delete** /v1/api/growth/providers/{provider}/key | Remove the workspace&#39;s own key for a growth provider
[**RemoveGrowthSuppression**](GrowthAPI.md#removegrowthsuppression) | **Delete** /v1/api/growth/suppressions/{suppressionId} | Remove an entry a person added to the do-not-contact list
[**RemoveManagedMailboxDomain**](GrowthAPI.md#removemanagedmailboxdomain) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/remove-domain | Request domain removal without claiming a refund or renewal cancellation
[**RepairManagedMailboxResource**](GrowthAPI.md#repairmanagedmailboxresource) | **Post** /v1/api/growth/managed-mailboxes/resources/{resourceId}/repair | Repair a failed resource step without repurchasing successful resources
[**RerunGrowthProject**](GrowthAPI.md#rerungrowthproject) | **Post** /v1/api/growth/projects/{projectId}/runs | Run the website research again
[**ResearchGrowthPlay**](GrowthAPI.md#researchgrowthplay) | **Post** /v1/api/growth/plays/{playId}/research | Find or resume leads for one campaign without repeating completed research
[**ResolveGrowthMessage**](GrowthAPI.md#resolvegrowthmessage) | **Post** /v1/api/growth/messages/{messageId}/resolve | Record whether an email whose delivery was unknown went out
[**SaveGrowthProviderKey**](GrowthAPI.md#savegrowthproviderkey) | **Put** /v1/api/growth/providers/{provider}/key | Add or replace the workspace&#39;s own key for a growth provider
[**SearchGrowthIndex**](GrowthAPI.md#searchgrowthindex) | **Get** /v1/api/growth/index/search | Search Hlix&#39;s shared index of companies and their people
[**SendGrowthReply**](GrowthAPI.md#sendgrowthreply) | **Post** /v1/api/growth/leads/{leadId}/reply | Answer a lead in their thread from the mailbox that wrote to them
[**SetGrowthAutopilot**](GrowthAPI.md#setgrowthautopilot) | **Put** /v1/api/growth/projects/{projectId}/autopilot | Turn the project&#39;s budget autopilot on or off
[**SetGrowthProjectBudget**](GrowthAPI.md#setgrowthprojectbudget) | **Put** /v1/api/growth/projects/{projectId}/daily-budget | Set or remove what all of a growth project&#39;s campaigns may spend per day
[**UpdateGrowthBrain**](GrowthAPI.md#updategrowthbrain) | **Put** /v1/api/growth/projects/{projectId}/brain | Replace the Company brain
[**UpdateGrowthChain**](GrowthAPI.md#updategrowthchain) | **Put** /v1/api/growth/chains/{capability} | Set the order a capability tries its providers in, or go back to the default
[**UpdateGrowthLead**](GrowthAPI.md#updategrowthlead) | **Patch** /v1/api/growth/leads/{leadId} | Disqualify a lead or return it to the queue
[**UpdateGrowthMailbox**](GrowthAPI.md#updategrowthmailbox) | **Patch** /v1/api/growth/mailboxes/{mailboxId} | Change a mailbox&#39;s daily limit or warm-up start, or pause and resume it
[**UpdateGrowthPlay**](GrowthAPI.md#updategrowthplay) | **Patch** /v1/api/growth/plays/{playId} | Edit or launch a campaign
[**UpdateGrowthProvider**](GrowthAPI.md#updategrowthprovider) | **Patch** /v1/api/growth/providers/{provider} | Turn a growth provider on or off for the workspace, or change its settings
[**UpdateGrowthSendingSchedule**](GrowthAPI.md#updategrowthsendingschedule) | **Patch** /v1/api/growth/projects/{projectId}/sending-schedule | Set or inherit a project&#39;s sending schedule
[**UpdateGrowthSettings**](GrowthAPI.md#updategrowthsettings) | **Patch** /v1/api/growth/settings | Change the hard cap, the sending rules or the booking link
[**UploadGrowthLeadList**](GrowthAPI.md#uploadgrowthleadlist) | **Post** /v1/api/growth/projects/{projectId}/lead-lists | Upload a lead list to a growth project



## AddGrowthIndexLeads

> GrowthLeadListResult AddGrowthIndexLeads(ctx, projectId).AddGrowthIndexLeads(addGrowthIndexLeads).XOrganizationId(xOrganizationId).Execute()

Add people and companies from Hlix's shared index to a growth project

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
	projectId := "projectId_example" // string |
	var addGrowthIndexLeads openapiclient.AddGrowthIndexLeads
	if err := json.Unmarshal([]byte("{}"), &addGrowthIndexLeads); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.AddGrowthIndexLeads(ctx, projectId).AddGrowthIndexLeads(addGrowthIndexLeads).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAddGrowthIndexLeadsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addGrowthIndexLeads** | [**AddGrowthIndexLeads**](AddGrowthIndexLeads.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthLeadListResult**](GrowthLeadListResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var addGrowthSuppressions openapiclient.AddGrowthSuppressions
	if err := json.Unmarshal([]byte("{\"entries\":[\"text\"]}"), &addGrowthSuppressions); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.AddGrowthSuppressions(ctx).AddGrowthSuppressions(addGrowthSuppressions).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAddGrowthSuppressionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **addGrowthSuppressions** | [**AddGrowthSuppressions**](AddGrowthSuppressions.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSuppressionsAdded**](GrowthSuppressionsAdded.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	batchId := "batchId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ApproveGrowthBatch(ctx, projectId, batchId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiApproveGrowthBatchRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthBatchApproved**](GrowthBatchApproved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	messageId := "messageId_example" // string |
	var approveGrowthMessage openapiclient.ApproveGrowthMessage
	if err := json.Unmarshal([]byte("{}"), &approveGrowthMessage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ApproveGrowthMessage(ctx, messageId).ApproveGrowthMessage(approveGrowthMessage).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiApproveGrowthMessageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **approveGrowthMessage** | [**ApproveGrowthMessage**](ApproveGrowthMessage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMessage**](GrowthMessage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resourceId := "resourceId_example" // string |
	var managedMailboxResourceActionInput openapiclient.ManagedMailboxResourceActionInput
	if err := json.Unmarshal([]byte("{\"idempotencyKey\":\"text\"}"), &managedMailboxResourceActionInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CancelManagedMailboxHosting(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCancelManagedMailboxHostingRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resourceId := "resourceId_example" // string |
	var managedMailboxResourceActionInput openapiclient.ManagedMailboxResourceActionInput
	if err := json.Unmarshal([]byte("{\"idempotencyKey\":\"text\"}"), &managedMailboxResourceActionInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CancelManagedMailboxWarmup(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCancelManagedMailboxWarmupRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	mailboxId := "mailboxId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CheckGrowthMailboxDns(ctx, mailboxId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCheckGrowthMailboxDnsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMailboxDns**](GrowthMailboxDns.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	messageId := "messageId_example" // string |
	var classifyGrowthMessage openapiclient.ClassifyGrowthMessage
	if err := json.Unmarshal([]byte("{\"classification\":\"interested\"}"), &classifyGrowthMessage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ClassifyGrowthMessage(ctx, messageId).ClassifyGrowthMessage(classifyGrowthMessage).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiClassifyGrowthMessageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **classifyGrowthMessage** | [**ClassifyGrowthMessage**](ClassifyGrowthMessage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthClassification**](GrowthClassification.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var compareGrowthProviders openapiclient.CompareGrowthProviders
	if err := json.Unmarshal([]byte("{\"operationKey\":\"text\",\"providers\":[\"value\",\"value\"]}"), &compareGrowthProviders); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CompareGrowthProviders(ctx).CompareGrowthProviders(compareGrowthProviders).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCompareGrowthProvidersRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **compareGrowthProviders** | [**CompareGrowthProviders**](CompareGrowthProviders.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProviderComparison**](GrowthProviderComparison.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var connectGrowthMailbox openapiclient.ConnectGrowthMailbox
	if err := json.Unmarshal([]byte("{\"service\":\"google\"}"), &connectGrowthMailbox); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ConnectGrowthMailbox(ctx).ConnectGrowthMailbox(connectGrowthMailbox).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiConnectGrowthMailboxRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **connectGrowthMailbox** | [**ConnectGrowthMailbox**](ConnectGrowthMailbox.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMailboxConnect**](GrowthMailboxConnect.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConnectGrowthSendkit

> GrowthSendkitReadiness ConnectGrowthSendkit(ctx).XOrganizationId(xOrganizationId).Execute()

Verify and bind the deployment-configured SendKit workspace

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
	resp, r, err := apiClient.GrowthAPI.ConnectGrowthSendkit(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ConnectGrowthSendkit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConnectGrowthSendkit`: GrowthSendkitReadiness
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.ConnectGrowthSendkit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiConnectGrowthSendkitRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSendkitReadiness**](GrowthSendkitReadiness.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateGrowthPlay

> GrowthPlay CreateGrowthPlay(ctx, projectId).CreateGrowthPlay(createGrowthPlay).XOrganizationId(xOrganizationId).Execute()

Create one campaign

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
	projectId := "projectId_example" // string |
	var createGrowthPlay openapiclient.CreateGrowthPlay
	if err := json.Unmarshal([]byte("{\"name\":\"text\",\"who\":{\"companySizes\":[\"1-10\"],\"countries\":[\"te\"],\"industries\":[\"text\"],\"roles\":[\"text\"]}}"), &createGrowthPlay); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CreateGrowthPlay(ctx, projectId).CreateGrowthPlay(createGrowthPlay).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateGrowthPlayRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createGrowthPlay** | [**CreateGrowthPlay**](CreateGrowthPlay.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthPlay**](GrowthPlay.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var createGrowthProject openapiclient.CreateGrowthProject
	if err := json.Unmarshal([]byte("{}"), &createGrowthProject); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.CreateGrowthProject(ctx).CreateGrowthProject(createGrowthProject).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateGrowthProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createGrowthProject** | [**CreateGrowthProject**](CreateGrowthProject.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProjectCreated**](GrowthProjectCreated.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	mailboxId := "mailboxId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.DisconnectGrowthMailbox(ctx, mailboxId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDisconnectGrowthMailboxRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMailboxDisconnected**](GrowthMailboxDisconnected.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	exportId := "exportId_example" // string |
	download := "download_example" // string | Use 1 for the authenticated CSV attachment. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.DownloadGrowthLeadExport(ctx, projectId, exportId).Download(download).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiDownloadGrowthLeadExportRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **download** | **string** | Use 1 for the authenticated CSV attachment. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

`*os.File`

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var growthLeadExportFilters openapiclient.GrowthLeadExportFilters
	if err := json.Unmarshal([]byte("{}"), &growthLeadExportFilters); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ExportGrowthLeads(ctx, projectId).GrowthLeadExportFilters(growthLeadExportFilters).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiExportGrowthLeadsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **growthLeadExportFilters** | [**GrowthLeadExportFilters**](GrowthLeadExportFilters.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthLeadExportResult**](GrowthLeadExportResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthEnrichPrice(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthEnrichPriceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthEnrich**](GrowthEnrich.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthIndexStats(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthIndexStatsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthIndexStats**](GrowthIndexStats.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	days := "days_example" // string | 7 (default) or 30 UTC days ending today. (optional)
	campaignId := "campaignId_example" // string | Only this campaign of the project. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthOverview(ctx, projectId).Days(days).CampaignId(campaignId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthOverviewRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **days** | **string** | 7 (default) or 30 UTC days ending today. |
 **campaignId** | **string** | Only this campaign of the project. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthOverview**](GrowthOverview.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthProject(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthState**](GrowthState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthSendingSchedule(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthSendingScheduleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProjectSendingSchedule**](GrowthProjectSendingSchedule.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetGrowthSendkitConnection

> GrowthSendkitReadiness GetGrowthSendkitConnection(ctx).XOrganizationId(xOrganizationId).Execute()

Inspect the workspace's SendKit connection and mailbox inventory

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthSendkitConnection(ctx).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.GetGrowthSendkitConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetGrowthSendkitConnection`: GrowthSendkitReadiness
	fmt.Fprintf(os.Stdout, "Response from `GrowthAPI.GetGrowthSendkitConnection`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiGetGrowthSendkitConnectionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSendkitReadiness**](GrowthSendkitReadiness.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthSettings(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthSettingsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSettingsState**](GrowthSettingsState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetGrowthSpend(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthSpendRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]GrowthPlaySpend**](GrowthPlaySpend.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	leadId := "leadId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetGrowthThread(ctx, leadId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetGrowthThreadRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthThread**](GrowthThread.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.GetManagedMailboxConfiguration(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetManagedMailboxConfigurationRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxConfiguration**](ManagedMailboxConfiguration.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	orderId := "orderId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.GetManagedMailboxOrder(ctx, orderId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetManagedMailboxOrderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var importGrowthToolResult openapiclient.ImportGrowthToolResult
	if err := json.Unmarshal([]byte("{\"callId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &importGrowthToolResult); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ImportGrowthToolResult(ctx, projectId).ImportGrowthToolResult(importGrowthToolResult).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiImportGrowthToolResultRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **importGrowthToolResult** | [**ImportGrowthToolResult**](ImportGrowthToolResult.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthToolResultImport**](GrowthToolResultImport.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImportManagedMailboxes

> ImportManagedMailboxes(ctx).ManagedMailboxImportInput(managedMailboxImportInput).XOrganizationId(xOrganizationId).Execute()

Connect existing InboxKit domains and mailboxes without purchasing them again

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
	var managedMailboxImportInput openapiclient.ManagedMailboxImportInput
	if err := json.Unmarshal([]byte("{}"), &managedMailboxImportInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.GrowthAPI.ImportManagedMailboxes(ctx).ManagedMailboxImportInput(managedMailboxImportInput).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GrowthAPI.ImportManagedMailboxes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiImportManagedMailboxesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managedMailboxImportInput** | [**ManagedMailboxImportInput**](ManagedMailboxImportInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	playId := "playId_example" // string | Only this campaign's research batches. (optional)
	batchId := "batchId_example" // string | One batch, including older emailed lists. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthBatches(ctx, projectId).PlayId(playId).BatchId(batchId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthBatchesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **playId** | **string** | Only this campaign&#39;s research batches. |
 **batchId** | **string** | One batch, including older emailed lists. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthBatchPage**](GrowthBatchPage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.ListGrowthChains(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthChainsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]GrowthChain**](GrowthChain.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.ListGrowthCitableProjects(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthCitableProjectsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]GrowthCitableProject**](GrowthCitableProject.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	filter := "filter_example" // string | Thread filter: `needs_reply` (unanswered replies), `hot` (unanswered interested replies), `replies` (all threads with a reply), `replied`, `sent` (no reply), `review` (drafts awaiting approval) or `unknown` (delivery needs confirmation). (optional)
	limit := "limit_example" // string | Page size, 1–100; default 50. (optional)
	offset := "offset_example" // string | How many threads to skip; default 0. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthInbox(ctx, projectId).Filter(filter).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthInboxRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **filter** | **string** | Thread filter: &#x60;needs_reply&#x60; (unanswered replies), &#x60;hot&#x60; (unanswered interested replies), &#x60;replies&#x60; (all threads with a reply), &#x60;replied&#x60;, &#x60;sent&#x60; (no reply), &#x60;review&#x60; (drafts awaiting approval) or &#x60;unknown&#x60; (delivery needs confirmation). |
 **limit** | **string** | Page size, 1–100; default 50. |
 **offset** | **string** | How many threads to skip; default 0. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthInboxPage**](GrowthInboxPage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	query := "query_example" // string | Search company, contact and evidence text; literal match, up to 200 characters. (optional)
	leadId := "leadId_example" // string | One lead within this project, including all evidence and provenance. (optional)
	playId := "playId_example" // string | Only this campaign's leads. (optional)
	batchId := "batchId_example" // string | Only leads from this research batch. (optional)
	status := "status_example" // string | Only leads in this status: new, queued, contacted, replied, converted, disqualified or opted_out. (optional)
	minFit := "minFit_example" // string | Only leads whose fit score (0–100) is at least this. (optional)
	limit := "limit_example" // string | Page size, 1–200; default 50. (optional)
	offset := "offset_example" // string | How many leads to skip; default 0. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthLeads(ctx, projectId).Query(query).LeadId(leadId).PlayId(playId).BatchId(batchId).Status(status).MinFit(minFit).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthLeadsRequest` request builder.


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

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	includeDisconnected := "includeDisconnected_example" // string | `true` also lists mailboxes that were disconnected; by default only the ones that can send are listed. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthMailboxes(ctx).IncludeDisconnected(includeDisconnected).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthMailboxesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includeDisconnected** | **string** | &#x60;true&#x60; also lists mailboxes that were disconnected; by default only the ones that can send are listed. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMailboxList**](GrowthMailboxList.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.GrowthAPI.ListGrowthProviders(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthProvidersRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	query := "query_example" // string | Only entries whose address or domain contains this. (optional)
	limit := "limit_example" // string | Page size, 1–200; default 50. (optional)
	offset := "offset_example" // string | How many entries to skip; default 0. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListGrowthSuppressions(ctx).Query(query).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListGrowthSuppressionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Only entries whose address or domain contains this. |
 **limit** | **string** | Page size, 1–200; default 50. |
 **offset** | **string** | How many entries to skip; default 0. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSuppressionPage**](GrowthSuppressionPage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	limit := "limit_example" // string | 1–50, defaults to 20. (optional)
	cursor := "cursor_example" // string | nextCursor from the previous page. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListManagedMailboxOrders(ctx).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListManagedMailboxOrdersRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | 1–50, defaults to 20. |
 **cursor** | **string** | nextCursor from the previous page. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrderList**](ManagedMailboxOrderList.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	limit := "limit_example" // string | 1–50, defaults to 20. (optional)
	cursor := "cursor_example" // string | nextCursor from the previous page. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ListManagedMailboxResources(ctx).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListManagedMailboxResourcesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | 1–50, defaults to 20. |
 **cursor** | **string** | nextCursor from the previous page. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxResourceList**](ManagedMailboxResourceList.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var managedMailboxOrderInput openapiclient.ManagedMailboxOrderInput
	if err := json.Unmarshal([]byte("{\"contact\":{\"addressLine1\":\"text\",\"city\":\"text\",\"country\":\"US\",\"email\":\"person@example.com\",\"firstName\":\"text\",\"lastName\":\"text\",\"postalCode\":\"text\",\"state\":\"text\"},\"idempotencyKey\":\"text\",\"quoteId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &managedMailboxOrderInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.OrderManagedMailboxes(ctx).ManagedMailboxOrderInput(managedMailboxOrderInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiOrderManagedMailboxesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managedMailboxOrderInput** | [**ManagedMailboxOrderInput**](ManagedMailboxOrderInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var growthLeadExportFilters openapiclient.GrowthLeadExportFilters
	if err := json.Unmarshal([]byte("{}"), &growthLeadExportFilters); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.PreviewGrowthLeadExport(ctx, projectId).GrowthLeadExportFilters(growthLeadExportFilters).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPreviewGrowthLeadExportRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **growthLeadExportFilters** | [**GrowthLeadExportFilters**](GrowthLeadExportFilters.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthLeadExportPreview**](GrowthLeadExportPreview.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var managedMailboxQuoteInput openapiclient.ManagedMailboxQuoteInput
	if err := json.Unmarshal([]byte("{\"domains\":[{\"mailboxes\":[{\"firstName\":\"text\",\"lastName\":\"text\",\"username\":\"text\"}],\"name\":\"app.example.com\"}]}"), &managedMailboxQuoteInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.QuoteManagedMailboxes(ctx).ManagedMailboxQuoteInput(managedMailboxQuoteInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiQuoteManagedMailboxesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **managedMailboxQuoteInput** | [**ManagedMailboxQuoteInput**](ManagedMailboxQuoteInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxQuote**](ManagedMailboxQuote.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	orderId := "orderId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ReconcileManagedMailboxOrder(ctx, orderId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiReconcileManagedMailboxOrderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	leadId := "leadId_example" // string |
	var refineGrowthReply openapiclient.RefineGrowthReply
	if err := json.Unmarshal([]byte("{\"body\":\"text\",\"instruction\":\"text\"}"), &refineGrowthReply); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RefineGrowthReply(ctx, leadId).RefineGrowthReply(refineGrowthReply).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRefineGrowthReplyRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **refineGrowthReply** | [**RefineGrowthReply**](RefineGrowthReply.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthRefinedReply**](GrowthRefinedReply.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	provider := "provider_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RemoveGrowthProviderKey(ctx, provider).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRemoveGrowthProviderKeyRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	suppressionId := "suppressionId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RemoveGrowthSuppression(ctx, suppressionId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRemoveGrowthSuppressionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSuppressionRemoved**](GrowthSuppressionRemoved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resourceId := "resourceId_example" // string |
	var managedMailboxResourceActionInput openapiclient.ManagedMailboxResourceActionInput
	if err := json.Unmarshal([]byte("{\"idempotencyKey\":\"text\"}"), &managedMailboxResourceActionInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RemoveManagedMailboxDomain(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRemoveManagedMailboxDomainRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resourceId := "resourceId_example" // string |
	var managedMailboxResourceActionInput openapiclient.ManagedMailboxResourceActionInput
	if err := json.Unmarshal([]byte("{\"idempotencyKey\":\"text\"}"), &managedMailboxResourceActionInput); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RepairManagedMailboxResource(ctx, resourceId).ManagedMailboxResourceActionInput(managedMailboxResourceActionInput).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRepairManagedMailboxResourceRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **managedMailboxResourceActionInput** | [**ManagedMailboxResourceActionInput**](ManagedMailboxResourceActionInput.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ManagedMailboxOrder**](ManagedMailboxOrder.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var rerunGrowth openapiclient.RerunGrowth
	if err := json.Unmarshal([]byte("{}"), &rerunGrowth); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.RerunGrowthProject(ctx, projectId).RerunGrowth(rerunGrowth).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiRerunGrowthProjectRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rerunGrowth** | [**RerunGrowth**](RerunGrowth.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthRun**](GrowthRun.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	playId := "playId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ResearchGrowthPlay(ctx, playId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiResearchGrowthPlayRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthResearchResult**](GrowthResearchResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	messageId := "messageId_example" // string |
	var resolveGrowthMessage openapiclient.ResolveGrowthMessage
	if err := json.Unmarshal([]byte("{\"sent\":true}"), &resolveGrowthMessage); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.ResolveGrowthMessage(ctx, messageId).ResolveGrowthMessage(resolveGrowthMessage).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiResolveGrowthMessageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **resolveGrowthMessage** | [**ResolveGrowthMessage**](ResolveGrowthMessage.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMessageResolved**](GrowthMessageResolved.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	provider := "provider_example" // string |
	var saveGrowthProviderKey openapiclient.SaveGrowthProviderKey
	if err := json.Unmarshal([]byte("{\"apiKey\":\"text\"}"), &saveGrowthProviderKey); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SaveGrowthProviderKey(ctx, provider).SaveGrowthProviderKey(saveGrowthProviderKey).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSaveGrowthProviderKeyRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **saveGrowthProviderKey** | [**SaveGrowthProviderKey**](SaveGrowthProviderKey.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	query := "query_example" // string | Text in the company's name, description or domain. (optional)
	countries := "countries_example" // string | Company countries, ISO codes, comma-separated (DE,AT). (optional)
	sizes := "sizes_example" // string | Company size bands, comma-separated (11-50,51-200). (optional)
	title := "title_example" // string | Text in a person's title; only companies with such a person are returned. (optional)
	seniorities := "seniorities_example" // string | Seniority levels, comma-separated (Director,C-Level); only companies with such a person are returned. (optional)
	limit := "limit_example" // string | Companies per page, 1–100; default 25. (optional)
	offset := "offset_example" // string | How many companies to skip, 0–2,000; default 0. Narrow the filters to reach further. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SearchGrowthIndex(ctx).Query(query).Countries(countries).Sizes(sizes).Title(title).Seniorities(seniorities).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSearchGrowthIndexRequest` request builder.


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

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	leadId := "leadId_example" // string |
	var sendGrowthReply openapiclient.SendGrowthReply
	if err := json.Unmarshal([]byte("{\"body\":\"text\"}"), &sendGrowthReply); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SendGrowthReply(ctx, leadId).SendGrowthReply(sendGrowthReply).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSendGrowthReplyRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **sendGrowthReply** | [**SendGrowthReply**](SendGrowthReply.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthReplySent**](GrowthReplySent.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var updateGrowthAutopilot openapiclient.UpdateGrowthAutopilot
	if err := json.Unmarshal([]byte("{\"enabled\":true}"), &updateGrowthAutopilot); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SetGrowthAutopilot(ctx, projectId).UpdateGrowthAutopilot(updateGrowthAutopilot).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetGrowthAutopilotRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthAutopilot** | [**UpdateGrowthAutopilot**](UpdateGrowthAutopilot.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthAutopilot**](GrowthAutopilot.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var updateGrowthProjectBudget openapiclient.UpdateGrowthProjectBudget
	if err := json.Unmarshal([]byte("{\"dailyBudgetMicros\":1}"), &updateGrowthProjectBudget); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.SetGrowthProjectBudget(ctx, projectId).UpdateGrowthProjectBudget(updateGrowthProjectBudget).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSetGrowthProjectBudgetRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthProjectBudget** | [**UpdateGrowthProjectBudget**](UpdateGrowthProjectBudget.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProjectBudget**](GrowthProjectBudget.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var growthBrain openapiclient.GrowthBrain
	if err := json.Unmarshal([]byte("{\"competitors\":[{\"name\":\"text\",\"reason\":\"text\",\"source\":\"https://example.com\"}],\"languages\":[{\"source\":\"https://example.com\",\"value\":\"text\"}],\"neverSay\":[\"text\"],\"offer\":{\"source\":\"https://example.com\",\"value\":\"text\"},\"pricing\":{\"source\":\"https://example.com\",\"value\":\"text\"},\"proof\":[{\"source\":\"https://example.com\",\"value\":\"text\"}]}"), &growthBrain); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthBrain(ctx, projectId).GrowthBrain(growthBrain).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthBrainRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **growthBrain** | [**GrowthBrain**](GrowthBrain.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthBrainRow**](GrowthBrainRow.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	capability := "capability_example" // string |
	var updateGrowthChain openapiclient.UpdateGrowthChain
	if err := json.Unmarshal([]byte("{\"order\":[\"text\"]}"), &updateGrowthChain); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthChain(ctx, capability).UpdateGrowthChain(updateGrowthChain).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthChainRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthChain** | [**UpdateGrowthChain**](UpdateGrowthChain.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthChainUpdated**](GrowthChainUpdated.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateGrowthLead

> GrowthLeadStatus UpdateGrowthLead(ctx, leadId).UpdateGrowthLead(updateGrowthLead).XOrganizationId(xOrganizationId).Execute()

Disqualify a lead or return it to the queue

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
	leadId := "leadId_example" // string |
	var updateGrowthLead openapiclient.UpdateGrowthLead
	if err := json.Unmarshal([]byte("{\"status\":\"disqualified\"}"), &updateGrowthLead); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthLead(ctx, leadId).UpdateGrowthLead(updateGrowthLead).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthLeadRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthLead** | [**UpdateGrowthLead**](UpdateGrowthLead.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthLeadStatus**](GrowthLeadStatus.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	mailboxId := "mailboxId_example" // string |
	var updateGrowthMailbox openapiclient.UpdateGrowthMailbox
	if err := json.Unmarshal([]byte("{}"), &updateGrowthMailbox); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthMailbox(ctx, mailboxId).UpdateGrowthMailbox(updateGrowthMailbox).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthMailboxRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthMailbox** | [**UpdateGrowthMailbox**](UpdateGrowthMailbox.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthMailbox**](GrowthMailbox.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	playId := "playId_example" // string |
	var updateGrowthPlay openapiclient.UpdateGrowthPlay
	if err := json.Unmarshal([]byte("{}"), &updateGrowthPlay); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthPlay(ctx, playId).UpdateGrowthPlay(updateGrowthPlay).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthPlayRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthPlay** | [**UpdateGrowthPlay**](UpdateGrowthPlay.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthPlay**](GrowthPlay.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	provider := "provider_example" // string |
	var updateGrowthProvider openapiclient.UpdateGrowthProvider
	if err := json.Unmarshal([]byte("{}"), &updateGrowthProvider); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthProvider(ctx, provider).UpdateGrowthProvider(updateGrowthProvider).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthProviderRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthProvider** | [**UpdateGrowthProvider**](UpdateGrowthProvider.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProvider**](GrowthProvider.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var updateGrowthSendingSchedule openapiclient.UpdateGrowthSendingSchedule
	if err := json.Unmarshal([]byte("{\"schedule\":{\"countryOverrides\":{\"key\":{\"sendDays\":[1],\"sendEndHour\":1,\"sendStartHour\":1,\"timeZone\":\"text\"}},\"sendDays\":[1],\"sendEndHour\":1,\"sendStartHour\":1,\"timeZone\":\"text\"}}"), &updateGrowthSendingSchedule); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthSendingSchedule(ctx, projectId).UpdateGrowthSendingSchedule(updateGrowthSendingSchedule).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthSendingScheduleRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateGrowthSendingSchedule** | [**UpdateGrowthSendingSchedule**](UpdateGrowthSendingSchedule.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthProjectSendingSchedule**](GrowthProjectSendingSchedule.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var updateGrowthSettings openapiclient.UpdateGrowthSettings
	if err := json.Unmarshal([]byte("{}"), &updateGrowthSettings); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UpdateGrowthSettings(ctx).UpdateGrowthSettings(updateGrowthSettings).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUpdateGrowthSettingsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateGrowthSettings** | [**UpdateGrowthSettings**](UpdateGrowthSettings.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthSettingsState**](GrowthSettingsState.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	projectId := "projectId_example" // string |
	var uploadGrowthLeadList openapiclient.UploadGrowthLeadList
	if err := json.Unmarshal([]byte("{\"csv\":\"text\",\"fileName\":\"text\"}"), &uploadGrowthLeadList); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GrowthAPI.UploadGrowthLeadList(ctx, projectId).UploadGrowthLeadList(uploadGrowthLeadList).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiUploadGrowthLeadListRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **uploadGrowthLeadList** | [**UploadGrowthLeadList**](UploadGrowthLeadList.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**GrowthLeadListResult**](GrowthLeadListResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

