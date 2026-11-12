# AuditLogAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuditEntry**](AuditLogAPI.md#getauditentry) | **Get** /v1/api/audit-log/{id} | Get one audit entry and its correlated rows
[**ListAuditLog**](AuditLogAPI.md#listauditlog) | **Get** /v1/api/audit-log | List the workspace&#39;s audit trail
[**ListProjectAuditLog**](AuditLogAPI.md#listprojectauditlog) | **Get** /v1/api/audit-log/projects/{projectId} | List one project&#39;s audit trail
[**VerifyAuditChain**](AuditLogAPI.md#verifyauditchain) | **Get** /v1/api/audit-log/verify | Verify the tamper-evidence hash chain



## GetAuditEntry

> AuditEntryDetail GetAuditEntry(ctx, id).XOrganizationId(xOrganizationId).Execute()

Get one audit entry and its correlated rows

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
	id := "id_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogAPI.GetAuditEntry(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetAuditEntryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AuditEntryDetail**](AuditEntryDetail.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	limit := "limit_example" // string | Page size, clamped to 1–200. Defaults to 50. (optional)
	cursor := "cursor_example" // string | The previous page's `nextCursor`, verbatim. Opaque — never construct one. (optional)
	actorType := "actorType_example" // string | `user` | `api_key` | `agent` | `system`. (optional)
	actorId := "actorId_example" // string | Exact id of the actor. (optional)
	action := "action_example" // string | Exact action name, such as `project.create`. Unknown actions are ignored and leave the results unfiltered. (optional)
	category := "category_example" // string | `create` | `read` | `update` | `delete` | `execute` | `auth` | `export`. (optional)
	resourceType := "resourceType_example" // string | Exact resource type, such as `project`. (optional)
	resourceId := "resourceId_example" // string | Exact resource id. (optional)
	outcome := "outcome_example" // string | `success` | `failure` | `denied`. (optional)
	severity := "severity_example" // string | `info` | `notice` | `warning` | `critical`. (optional)
	source := "source_example" // string | Where the action came in: `web` | `api` | `cli` | `telegram` | `linear` | `github` | `webhook` | `internal` | `system`. (optional)
	requestId := "requestId_example" // string | Correlation id of one request. (optional)
	traceId := "traceId_example" // string | Correlation id shared with the other planes. (optional)
	from := "from_example" // string | Inclusive lower bound on `occurredAt`, as an ISO timestamp. Unparseable values are ignored. (optional)
	to := "to_example" // string | Inclusive upper bound on `occurredAt`, ISO. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogAPI.ListAuditLog(ctx).Limit(limit).Cursor(cursor).ActorType(actorType).ActorId(actorId).Action(action).Category(category).ResourceType(resourceType).ResourceId(resourceId).Outcome(outcome).Severity(severity).Source(source).RequestId(requestId).TraceId(traceId).From(from).To(to).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListAuditLogRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | Page size, clamped to 1–200. Defaults to 50. |
 **cursor** | **string** | The previous page&#39;s &#x60;nextCursor&#x60;, verbatim. Opaque — never construct one. |
 **actorType** | **string** | &#x60;user&#x60; | &#x60;api_key&#x60; | &#x60;agent&#x60; | &#x60;system&#x60;. |
 **actorId** | **string** | Exact id of the actor. |
 **action** | **string** | Exact action name, such as &#x60;project.create&#x60;. Unknown actions are ignored and leave the results unfiltered. |
 **category** | **string** | &#x60;create&#x60; | &#x60;read&#x60; | &#x60;update&#x60; | &#x60;delete&#x60; | &#x60;execute&#x60; | &#x60;auth&#x60; | &#x60;export&#x60;. |
 **resourceType** | **string** | Exact resource type, such as &#x60;project&#x60;. |
 **resourceId** | **string** | Exact resource id. |
 **outcome** | **string** | &#x60;success&#x60; | &#x60;failure&#x60; | &#x60;denied&#x60;. |
 **severity** | **string** | &#x60;info&#x60; | &#x60;notice&#x60; | &#x60;warning&#x60; | &#x60;critical&#x60;. |
 **source** | **string** | Where the action came in: &#x60;web&#x60; | &#x60;api&#x60; | &#x60;cli&#x60; | &#x60;telegram&#x60; | &#x60;linear&#x60; | &#x60;github&#x60; | &#x60;webhook&#x60; | &#x60;internal&#x60; | &#x60;system&#x60;. |
 **requestId** | **string** | Correlation id of one request. |
 **traceId** | **string** | Correlation id shared with the other planes. |
 **from** | **string** | Inclusive lower bound on &#x60;occurredAt&#x60;, as an ISO timestamp. Unparseable values are ignored. |
 **to** | **string** | Inclusive upper bound on &#x60;occurredAt&#x60;, ISO. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AuditPage**](AuditPage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	limit := "limit_example" // string | Page size, clamped to 1–200. Defaults to 50. (optional)
	cursor := "cursor_example" // string | The previous page's `nextCursor`, verbatim. Opaque — never construct one. (optional)
	action := "action_example" // string | Exact action name. (optional)
	actorType := "actorType_example" // string | `user` | `api_key` | `agent` | `system`. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AuditLogAPI.ListProjectAuditLog(ctx, projectId).Limit(limit).Cursor(cursor).Action(action).ActorType(actorType).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListProjectAuditLogRequest` request builder.


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

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.AuditLogAPI.VerifyAuditChain(ctx).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiVerifyAuditChainRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AuditChainVerification**](AuditChainVerification.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

