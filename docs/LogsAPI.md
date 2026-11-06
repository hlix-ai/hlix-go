# \LogsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListAgentLogs**](LogsAPI.md#ListAgentLogs) | **Get** /v1/api/logs/agent/{agentId} | List the log lines across one agent&#39;s tasks
[**ListAgentRunLogs**](LogsAPI.md#ListAgentRunLogs) | **Get** /v1/api/logs/agent-run/{agentRunId} | List the log lines of one agent run
[**ListCycleLogs**](LogsAPI.md#ListCycleLogs) | **Get** /v1/api/logs/cycle/{cycleId} | List one cycle&#39;s log lines
[**ListProjectLogs**](LogsAPI.md#ListProjectLogs) | **Get** /v1/api/logs/project/{projectId} | List a project&#39;s log lines
[**ListTaskLogs**](LogsAPI.md#ListTaskLogs) | **Get** /v1/api/logs/task/{taskId} | List one task&#39;s log lines
[**ListTraceLogs**](LogsAPI.md#ListTraceLogs) | **Get** /v1/api/logs/trace/{traceId} | List the log lines of one trace



## ListAgentLogs

> []LogEntry ListAgentLogs(ctx, agentId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()

List the log lines across one agent's tasks

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
	agentId := "agentId_example" // string | 
	limit := "limit_example" // string | Page size, clamped to 1–2000; 500 when `before` or `after` is given without it. With none of `limit`, `before` and `after`, the newest 2000 lines are returned (page back with `before`). (optional)
	before := "before_example" // string | A log line id: the page of lines just before it. Without `before` or `after`, a page is the newest lines. Every page is oldest first; ask again with the page's first id until a page comes back shorter than `limit`. (optional)
	after := "after_example" // string | A log line id: the lines after it, oldest first. Ask again with the page's last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ListAgentLogs(context.Background(), agentId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ListAgentLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgentLogs`: []LogEntry
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ListAgentLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**agentId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAgentLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–2000; 500 when &#x60;before&#x60; or &#x60;after&#x60; is given without it. With none of &#x60;limit&#x60;, &#x60;before&#x60; and &#x60;after&#x60;, the newest 2000 lines are returned (page back with &#x60;before&#x60;). | 
 **before** | **string** | A log line id: the page of lines just before it. Without &#x60;before&#x60; or &#x60;after&#x60;, a page is the newest lines. Every page is oldest first; ask again with the page&#39;s first id until a page comes back shorter than &#x60;limit&#x60;. | 
 **after** | **string** | A log line id: the lines after it, oldest first. Ask again with the page&#39;s last id until a page comes back shorter than &#x60;limit&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]LogEntry**](LogEntry.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAgentRunLogs

> []LogEntry ListAgentRunLogs(ctx, agentRunId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()

List the log lines of one agent run

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
	agentRunId := "agentRunId_example" // string | 
	limit := "limit_example" // string | Page size, clamped to 1–2000; 500 when `before` or `after` is given without it. With none of `limit`, `before` and `after`, the newest 2000 lines are returned (page back with `before`). (optional)
	before := "before_example" // string | A log line id: the page of lines just before it. Without `before` or `after`, a page is the newest lines. Every page is oldest first; ask again with the page's first id until a page comes back shorter than `limit`. (optional)
	after := "after_example" // string | A log line id: the lines after it, oldest first. Ask again with the page's last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ListAgentRunLogs(context.Background(), agentRunId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ListAgentRunLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAgentRunLogs`: []LogEntry
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ListAgentRunLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**agentRunId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAgentRunLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–2000; 500 when &#x60;before&#x60; or &#x60;after&#x60; is given without it. With none of &#x60;limit&#x60;, &#x60;before&#x60; and &#x60;after&#x60;, the newest 2000 lines are returned (page back with &#x60;before&#x60;). | 
 **before** | **string** | A log line id: the page of lines just before it. Without &#x60;before&#x60; or &#x60;after&#x60;, a page is the newest lines. Every page is oldest first; ask again with the page&#39;s first id until a page comes back shorter than &#x60;limit&#x60;. | 
 **after** | **string** | A log line id: the lines after it, oldest first. Ask again with the page&#39;s last id until a page comes back shorter than &#x60;limit&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]LogEntry**](LogEntry.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCycleLogs

> []LogEntry ListCycleLogs(ctx, cycleId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()

List one cycle's log lines

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
	limit := "limit_example" // string | Page size, clamped to 1–2000; 500 when `before` or `after` is given without it. With none of `limit`, `before` and `after`, the newest 2000 lines are returned (page back with `before`). (optional)
	before := "before_example" // string | A log line id: the page of lines just before it. Without `before` or `after`, a page is the newest lines. Every page is oldest first; ask again with the page's first id until a page comes back shorter than `limit`. (optional)
	after := "after_example" // string | A log line id: the lines after it, oldest first. Ask again with the page's last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ListCycleLogs(context.Background(), cycleId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ListCycleLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCycleLogs`: []LogEntry
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ListCycleLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**cycleId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCycleLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–2000; 500 when &#x60;before&#x60; or &#x60;after&#x60; is given without it. With none of &#x60;limit&#x60;, &#x60;before&#x60; and &#x60;after&#x60;, the newest 2000 lines are returned (page back with &#x60;before&#x60;). | 
 **before** | **string** | A log line id: the page of lines just before it. Without &#x60;before&#x60; or &#x60;after&#x60;, a page is the newest lines. Every page is oldest first; ask again with the page&#39;s first id until a page comes back shorter than &#x60;limit&#x60;. | 
 **after** | **string** | A log line id: the lines after it, oldest first. Ask again with the page&#39;s last id until a page comes back shorter than &#x60;limit&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]LogEntry**](LogEntry.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectLogs

> []LogEntry ListProjectLogs(ctx, projectId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()

List a project's log lines

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
	limit := "limit_example" // string | Page size, clamped to 1–2000; 500 when `before` or `after` is given without it. With none of `limit`, `before` and `after`, the newest 2000 lines are returned (page back with `before`). (optional)
	before := "before_example" // string | A log line id: the page of lines just before it. Without `before` or `after`, a page is the newest lines. Every page is oldest first; ask again with the page's first id until a page comes back shorter than `limit`. (optional)
	after := "after_example" // string | A log line id: the lines after it, oldest first. Ask again with the page's last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ListProjectLogs(context.Background(), projectId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ListProjectLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectLogs`: []LogEntry
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ListProjectLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–2000; 500 when &#x60;before&#x60; or &#x60;after&#x60; is given without it. With none of &#x60;limit&#x60;, &#x60;before&#x60; and &#x60;after&#x60;, the newest 2000 lines are returned (page back with &#x60;before&#x60;). | 
 **before** | **string** | A log line id: the page of lines just before it. Without &#x60;before&#x60; or &#x60;after&#x60;, a page is the newest lines. Every page is oldest first; ask again with the page&#39;s first id until a page comes back shorter than &#x60;limit&#x60;. | 
 **after** | **string** | A log line id: the lines after it, oldest first. Ask again with the page&#39;s last id until a page comes back shorter than &#x60;limit&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]LogEntry**](LogEntry.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTaskLogs

> []LogEntry ListTaskLogs(ctx, taskId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()

List one task's log lines

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
	taskId := "taskId_example" // string | 
	limit := "limit_example" // string | Page size, clamped to 1–2000; 500 when `before` or `after` is given without it. With none of `limit`, `before` and `after`, the newest 2000 lines are returned (page back with `before`). (optional)
	before := "before_example" // string | A log line id: the page of lines just before it. Without `before` or `after`, a page is the newest lines. Every page is oldest first; ask again with the page's first id until a page comes back shorter than `limit`. (optional)
	after := "after_example" // string | A log line id: the lines after it, oldest first. Ask again with the page's last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ListTaskLogs(context.Background(), taskId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ListTaskLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTaskLogs`: []LogEntry
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ListTaskLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**taskId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListTaskLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–2000; 500 when &#x60;before&#x60; or &#x60;after&#x60; is given without it. With none of &#x60;limit&#x60;, &#x60;before&#x60; and &#x60;after&#x60;, the newest 2000 lines are returned (page back with &#x60;before&#x60;). | 
 **before** | **string** | A log line id: the page of lines just before it. Without &#x60;before&#x60; or &#x60;after&#x60;, a page is the newest lines. Every page is oldest first; ask again with the page&#39;s first id until a page comes back shorter than &#x60;limit&#x60;. | 
 **after** | **string** | A log line id: the lines after it, oldest first. Ask again with the page&#39;s last id until a page comes back shorter than &#x60;limit&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]LogEntry**](LogEntry.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListTraceLogs

> []LogEntry ListTraceLogs(ctx, traceId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()

List the log lines of one trace

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
	traceId := "traceId_example" // string | 
	limit := "limit_example" // string | Page size, clamped to 1–2000; 500 when `before` or `after` is given without it. With none of `limit`, `before` and `after`, the newest 2000 lines are returned (page back with `before`). (optional)
	before := "before_example" // string | A log line id: the page of lines just before it. Without `before` or `after`, a page is the newest lines. Every page is oldest first; ask again with the page's first id until a page comes back shorter than `limit`. (optional)
	after := "after_example" // string | A log line id: the lines after it, oldest first. Ask again with the page's last id until a page comes back shorter than `limit`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LogsAPI.ListTraceLogs(context.Background(), traceId).Limit(limit).Before(before).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LogsAPI.ListTraceLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListTraceLogs`: []LogEntry
	fmt.Fprintf(os.Stdout, "Response from `LogsAPI.ListTraceLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**traceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListTraceLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–2000; 500 when &#x60;before&#x60; or &#x60;after&#x60; is given without it. With none of &#x60;limit&#x60;, &#x60;before&#x60; and &#x60;after&#x60;, the newest 2000 lines are returned (page back with &#x60;before&#x60;). | 
 **before** | **string** | A log line id: the page of lines just before it. Without &#x60;before&#x60; or &#x60;after&#x60;, a page is the newest lines. Every page is oldest first; ask again with the page&#39;s first id until a page comes back shorter than &#x60;limit&#x60;. | 
 **after** | **string** | A log line id: the lines after it, oldest first. Ask again with the page&#39;s last id until a page comes back shorter than &#x60;limit&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]LogEntry**](LogEntry.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

