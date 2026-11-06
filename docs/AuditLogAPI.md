# \AuditLogAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuditEntry**](AuditLogAPI.md#GetAuditEntry) | **Get** /v1/api/audit-log/{id} | Get one audit entry and its correlated rows
[**ListAuditLog**](AuditLogAPI.md#ListAuditLog) | **Get** /v1/api/audit-log | List the workspace&#39;s audit trail
[**ListProjectAuditLog**](AuditLogAPI.md#ListProjectAuditLog) | **Get** /v1/api/audit-log/projects/{projectId} | List one project&#39;s audit trail
[**VerifyAuditChain**](AuditLogAPI.md#VerifyAuditChain) | **Get** /v1/api/audit-log/verify | Verify the tamper-evidence hash chain



## GetAuditEntry

> AuditEntryDetail GetAuditEntry(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get one audit entry and its correlated rows

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
	resp, r, err := apiClient.AuditLogAPI.GetAuditEntry(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditLogAPI.GetAuditEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuditEntry`: AuditEntryDetail
	fmt.Fprintf(os.Stdout, "Response from `AuditLogAPI.GetAuditEntry`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAuditEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AuditEntryDetail**](AuditEntryDetail.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAuditLog

> AuditPage ListAuditLog(ctx).Limit(limit).Cursor(cursor).ActorType(actorType).ActorId(actorId).Action(action).Category(category).ResourceType(resourceType).ResourceId(resourceId).Outcome(outcome).Severity(severity).Source(source).RequestId(requestId).TraceId(traceId).From(from).To(to).XOrganizationId(xOrganizationId).Execute()

List the workspace's audit trail

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
	limit := "limit_example" // string | Page size, clamped to 1–200. Defaults to 50. (optional)
	cursor := "cursor_example" // string | The previous page's `nextCursor`, verbatim. Opaque — never construct one. (optional)
	actorType := "actorType_example" // string | `user` | `api_key` | `agent` | `system`. (optional)
	actorId := "actorId_example" // string | Exact id of the actor. (optional)
	action := "action_example" // string | Exact action name, such as `project.create`. An action the server does not know is IGNORED, not rejected — the page comes back unfiltered. (optional)
	category := "category_example" // string | `create` | `read` | `update` | `delete` | `execute` | `auth` | `export`. (optional)
	resourceType := "resourceType_example" // string | Exact resource type, such as `project`. (optional)
	resourceId := "resourceId_example" // string | Exact resource id. (optional)
	outcome := "outcome_example" // string | `success` | `failure` | `denied`. (optional)
	severity := "severity_example" // string | `info` | `notice` | `warning` | `critical`. (optional)
	source := "source_example" // string | Where the action came in: `web` | `api` | `cli` | `telegram` | `linear` | `github` | `webhook` | `internal` | `system`. (optional)
	requestId := "requestId_example" // string | Correlation id of one request. (optional)
	traceId := "traceId_example" // string | Correlation id shared with the other planes. (optional)
	from := "from_example" // string | Inclusive lower bound on `occurredAt`, ISO. An unparseable value is IGNORED rather than rejected. (optional)
	to := "to_example" // string | Inclusive upper bound on `occurredAt`, ISO. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogAPI.ListAuditLog(context.Background()).Limit(limit).Cursor(cursor).ActorType(actorType).ActorId(actorId).Action(action).Category(category).ResourceType(resourceType).ResourceId(resourceId).Outcome(outcome).Severity(severity).Source(source).RequestId(requestId).TraceId(traceId).From(from).To(to).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditLogAPI.ListAuditLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAuditLog`: AuditPage
	fmt.Fprintf(os.Stdout, "Response from `AuditLogAPI.ListAuditLog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAuditLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | Page size, clamped to 1–200. Defaults to 50. | 
 **cursor** | **string** | The previous page&#39;s &#x60;nextCursor&#x60;, verbatim. Opaque — never construct one. | 
 **actorType** | **string** | &#x60;user&#x60; | &#x60;api_key&#x60; | &#x60;agent&#x60; | &#x60;system&#x60;. | 
 **actorId** | **string** | Exact id of the actor. | 
 **action** | **string** | Exact action name, such as &#x60;project.create&#x60;. An action the server does not know is IGNORED, not rejected — the page comes back unfiltered. | 
 **category** | **string** | &#x60;create&#x60; | &#x60;read&#x60; | &#x60;update&#x60; | &#x60;delete&#x60; | &#x60;execute&#x60; | &#x60;auth&#x60; | &#x60;export&#x60;. | 
 **resourceType** | **string** | Exact resource type, such as &#x60;project&#x60;. | 
 **resourceId** | **string** | Exact resource id. | 
 **outcome** | **string** | &#x60;success&#x60; | &#x60;failure&#x60; | &#x60;denied&#x60;. | 
 **severity** | **string** | &#x60;info&#x60; | &#x60;notice&#x60; | &#x60;warning&#x60; | &#x60;critical&#x60;. | 
 **source** | **string** | Where the action came in: &#x60;web&#x60; | &#x60;api&#x60; | &#x60;cli&#x60; | &#x60;telegram&#x60; | &#x60;linear&#x60; | &#x60;github&#x60; | &#x60;webhook&#x60; | &#x60;internal&#x60; | &#x60;system&#x60;. | 
 **requestId** | **string** | Correlation id of one request. | 
 **traceId** | **string** | Correlation id shared with the other planes. | 
 **from** | **string** | Inclusive lower bound on &#x60;occurredAt&#x60;, ISO. An unparseable value is IGNORED rather than rejected. | 
 **to** | **string** | Inclusive upper bound on &#x60;occurredAt&#x60;, ISO. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AuditPage**](AuditPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjectAuditLog

> AuditPage ListProjectAuditLog(ctx, projectId).Limit(limit).Cursor(cursor).Action(action).ActorType(actorType).XOrganizationId(xOrganizationId).Execute()

List one project's audit trail

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
	limit := "limit_example" // string | Page size, clamped to 1–200. Defaults to 50. (optional)
	cursor := "cursor_example" // string | The previous page's `nextCursor`, verbatim. Opaque — never construct one. (optional)
	action := "action_example" // string | Exact action name. (optional)
	actorType := "actorType_example" // string | `user` | `api_key` | `agent` | `system`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogAPI.ListProjectAuditLog(context.Background(), projectId).Limit(limit).Cursor(cursor).Action(action).ActorType(actorType).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditLogAPI.ListProjectAuditLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjectAuditLog`: AuditPage
	fmt.Fprintf(os.Stdout, "Response from `AuditLogAPI.ListProjectAuditLog`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListProjectAuditLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, clamped to 1–200. Defaults to 50. | 
 **cursor** | **string** | The previous page&#39;s &#x60;nextCursor&#x60;, verbatim. Opaque — never construct one. | 
 **action** | **string** | Exact action name. | 
 **actorType** | **string** | &#x60;user&#x60; | &#x60;api_key&#x60; | &#x60;agent&#x60; | &#x60;system&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AuditPage**](AuditPage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyAuditChain

> AuditChainVerification VerifyAuditChain(ctx).XOrganizationId(xOrganizationId).Execute()

Verify the tamper-evidence hash chain

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
	resp, r, err := apiClient.AuditLogAPI.VerifyAuditChain(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuditLogAPI.VerifyAuditChain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyAuditChain`: AuditChainVerification
	fmt.Fprintf(os.Stdout, "Response from `AuditLogAPI.VerifyAuditChain`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiVerifyAuditChainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AuditChainVerification**](AuditChainVerification.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

