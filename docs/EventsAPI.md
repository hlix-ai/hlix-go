# \EventsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetActivitySummary**](EventsAPI.md#GetActivitySummary) | **Get** /v1/api/events/summary | Summarize recorded workspace activity
[**ListEvents**](EventsAPI.md#ListEvents) | **Get** /v1/api/events | List activity events



## GetActivitySummary

> ActivitySummary GetActivitySummary(ctx).Days(days).ProjectId(projectId).ActorType(actorType).ActorId(actorId).XOrganizationId(xOrganizationId).Execute()

Summarize recorded workspace activity

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
	days := "days_example" // string | UTC calendar-day window: 7, 30, 90 or 365, including today. Summary defaults to 30; omitted on the recent feed means all retained events. (optional)
	projectId := "projectId_example" // string | Only events owned by this project, through its cycle/task/run or explicitly recorded project context. Always workspace-fenced. (optional)
	actorType := "actorType_example" // string | Only events recorded as user, agent or system. (optional)
	actorId := "actorId_example" // string | Only events with this exact recorded actor id. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EventsAPI.GetActivitySummary(context.Background()).Days(days).ProjectId(projectId).ActorType(actorType).ActorId(actorId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EventsAPI.GetActivitySummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetActivitySummary`: ActivitySummary
	fmt.Fprintf(os.Stdout, "Response from `EventsAPI.GetActivitySummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetActivitySummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **days** | **string** | UTC calendar-day window: 7, 30, 90 or 365, including today. Summary defaults to 30; omitted on the recent feed means all retained events. | 
 **projectId** | **string** | Only events owned by this project, through its cycle/task/run or explicitly recorded project context. Always workspace-fenced. | 
 **actorType** | **string** | Only events recorded as user, agent or system. | 
 **actorId** | **string** | Only events with this exact recorded actor id. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ActivitySummary**](ActivitySummary.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListEvents

> []ActivityEvent ListEvents(ctx).Days(days).ProjectId(projectId).ActorType(actorType).ActorId(actorId).CycleId(cycleId).TraceId(traceId).EventType(eventType).EntityType(entityType).EntityId(entityId).Limit(limit).Before(before).BeforeId(beforeId).XOrganizationId(xOrganizationId).Execute()

List activity events

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
	days := "days_example" // string | UTC calendar-day window: 7, 30, 90 or 365, including today. Summary defaults to 30; omitted on the recent feed means all retained events. (optional)
	projectId := "projectId_example" // string | Only events owned by this project, through its cycle/task/run or explicitly recorded project context. Always workspace-fenced. (optional)
	actorType := "actorType_example" // string | Only events recorded as user, agent or system. (optional)
	actorId := "actorId_example" // string | Only events with this exact recorded actor id. (optional)
	cycleId := "cycleId_example" // string | The cycle's own events plus its child tasks'. Checked FIRST — it overrides every other selector. (optional)
	traceId := "traceId_example" // string | Every event of one trace. Checked second, ahead of `eventType` and the entity pair. (optional)
	eventType := "eventType_example" // string | Exact event name, such as `task.merged`. Checked third. (optional)
	entityType := "entityType_example" // string | `cycle` | `task` | `project` | `agent_run` | `pending_request`. Only read together with `entityId`. (optional)
	entityId := "entityId_example" // string | The entity's id. Required with `entityType`. (optional)
	limit := "limit_example" // string | Recent-activity page size, integer 1–500 (default 100). Supplying it, before or an activity filter selects the recent feed. (optional)
	before := "before_example" // string | ISO timestamp from the last event. Include beforeId for complete pagination when events share a timestamp. Without beforeId, preserves the legacy strictly-older behavior. (optional)
	beforeId := "beforeId_example" // string | The last event id from the previous page, together with before. Results are ordered by timestamp and id descending; the database cursor retains full timestamp precision. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EventsAPI.ListEvents(context.Background()).Days(days).ProjectId(projectId).ActorType(actorType).ActorId(actorId).CycleId(cycleId).TraceId(traceId).EventType(eventType).EntityType(entityType).EntityId(entityId).Limit(limit).Before(before).BeforeId(beforeId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EventsAPI.ListEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListEvents`: []ActivityEvent
	fmt.Fprintf(os.Stdout, "Response from `EventsAPI.ListEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **days** | **string** | UTC calendar-day window: 7, 30, 90 or 365, including today. Summary defaults to 30; omitted on the recent feed means all retained events. | 
 **projectId** | **string** | Only events owned by this project, through its cycle/task/run or explicitly recorded project context. Always workspace-fenced. | 
 **actorType** | **string** | Only events recorded as user, agent or system. | 
 **actorId** | **string** | Only events with this exact recorded actor id. | 
 **cycleId** | **string** | The cycle&#39;s own events plus its child tasks&#39;. Checked FIRST — it overrides every other selector. | 
 **traceId** | **string** | Every event of one trace. Checked second, ahead of &#x60;eventType&#x60; and the entity pair. | 
 **eventType** | **string** | Exact event name, such as &#x60;task.merged&#x60;. Checked third. | 
 **entityType** | **string** | &#x60;cycle&#x60; | &#x60;task&#x60; | &#x60;project&#x60; | &#x60;agent_run&#x60; | &#x60;pending_request&#x60;. Only read together with &#x60;entityId&#x60;. | 
 **entityId** | **string** | The entity&#39;s id. Required with &#x60;entityType&#x60;. | 
 **limit** | **string** | Recent-activity page size, integer 1–500 (default 100). Supplying it, before or an activity filter selects the recent feed. | 
 **before** | **string** | ISO timestamp from the last event. Include beforeId for complete pagination when events share a timestamp. Without beforeId, preserves the legacy strictly-older behavior. | 
 **beforeId** | **string** | The last event id from the previous page, together with before. Results are ordered by timestamp and id descending; the database cursor retains full timestamp precision. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]ActivityEvent**](ActivityEvent.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

