# MentionsAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetProjectMentionRoster**](MentionsAPI.md#getprojectmentionroster) | **Get** /v1/api/projects/{projectId}/mention-roster | List who this project&#39;s conversations can mention
[**ListUnreadMentions**](MentionsAPI.md#listunreadmentions) | **Get** /v1/api/mentions | List the caller&#39;s unread mentions
[**MarkMentionsRead**](MentionsAPI.md#markmentionsread) | **Post** /v1/api/mentions/read | Mark the caller&#39;s mentions read



## GetProjectMentionRoster

> MentionRoster GetProjectMentionRoster(ctx, projectId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List who this project's conversations can mention

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
	resp, r, err := apiClient.MentionsAPI.GetProjectMentionRoster(ctx, projectId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.GetProjectMentionRoster``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProjectMentionRoster`: MentionRoster
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.GetProjectMentionRoster`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiGetProjectMentionRosterRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**MentionRoster**](MentionRoster.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListUnreadMentions

> MentionInbox ListUnreadMentions(ctx).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()

List the caller's unread mentions

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
	limit := "limit_example" // string | Page size, clamped to 1–500; 100 when omitted or not an integer. (optional)
	offset := "offset_example" // string | Mentions to skip, newest first. `total` counts every unread mention, so it says how many pages there are. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.ListUnreadMentions(ctx).Limit(limit).Offset(offset).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.ListUnreadMentions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListUnreadMentions`: MentionInbox
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.ListUnreadMentions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListUnreadMentionsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | Page size, clamped to 1–500; 100 when omitted or not an integer. |
 **offset** | **string** | Mentions to skip, newest first. &#x60;total&#x60; counts every unread mention, so it says how many pages there are. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MentionInbox**](MentionInbox.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkMentionsRead

> MentionReadAck MarkMentionsRead(ctx).MentionRead(mentionRead).XOrganizationId(xOrganizationId).Execute()

Mark the caller's mentions read

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
	var mentionRead openapiclient.MentionRead
	if err := json.Unmarshal([]byte("{\"ids\":[\"text\"]}"), &mentionRead); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.MarkMentionsRead(ctx).MentionRead(mentionRead).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.MarkMentionsRead``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkMentionsRead`: MentionReadAck
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.MarkMentionsRead`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiMarkMentionsReadRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **mentionRead** | [**MentionRead**](MentionRead.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**MentionReadAck**](MentionReadAck.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

