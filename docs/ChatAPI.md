# ChatAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AnswerChatApproval**](ChatAPI.md#answerchatapproval) | **Post** /v1/api/chat/approvals/{requestId} | Answer an approval the agent asked for
[**CheckUrgentChatMessage**](ChatAPI.md#checkurgentchatmessage) | **Post** /v1/api/chat/urgent | Stop only the project&#39;s recent work an urgent message contradicts
[**ConnectChatSocket**](ChatAPI.md#connectchatsocket) | **Post** /v1/api/chat/connect | Get the proof a conversation&#39;s socket upgrade presents
[**ConnectProjectStream**](ChatAPI.md#connectprojectstream) | **Post** /v1/api/projects/{id}/stream/connect | Get the proof a project stream&#39;s socket upgrade presents
[**CreateChat**](ChatAPI.md#createchat) | **Post** /v1/api/chats | Start a chat session with an agent
[**ListChatDirectory**](ChatAPI.md#listchatdirectory) | **Get** /v1/api/chat/directory | Search your private and accessible shared project conversations
[**ListChatMessages**](ChatAPI.md#listchatmessages) | **Get** /v1/api/chat/messages | Read a conversation&#39;s messages, newest page first
[**ListChats**](ChatAPI.md#listchats) | **Get** /v1/api/chats | List the chat sessions of a conversation you may see
[**SendChatTurn**](ChatAPI.md#sendchatturn) | **Post** /v1/api/chat/turns | Send a message to a conversation and return while the agent works
[**SetPrivateChatModel**](ChatAPI.md#setprivatechatmodel) | **Patch** /v1/api/chats/{id}/model | Choose the model for your private conversation
[**StopChatTurn**](ChatAPI.md#stopchatturn) | **Post** /v1/api/chat/stop | Stop the turn a conversation is running
[**StreamChatEvents**](ChatAPI.md#streamchatevents) | **Get** /v1/api/chat/events | Follow a conversation as Server-Sent Events
[**UploadChatAttachment**](ChatAPI.md#uploadchatattachment) | **Post** /v1/api/chat/attachments | Store a file for a chat turn to name



## AnswerChatApproval

> ConversationApprovalResult AnswerChatApproval(ctx, requestId).ConversationApproval(conversationApproval).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Answer an approval the agent asked for

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
	requestId := "requestId_example" // string |
	var conversationApproval openapiclient.ConversationApproval
	if err := json.Unmarshal([]byte("{\"approved\":true,\"chatId\":\"text\"}"), &conversationApproval); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.AnswerChatApproval(ctx, requestId).ConversationApproval(conversationApproval).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.AnswerChatApproval``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AnswerChatApproval`: ConversationApprovalResult
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.AnswerChatApproval`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**requestId** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiAnswerChatApprovalRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **conversationApproval** | [**ConversationApproval**](ConversationApproval.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationApprovalResult**](ConversationApprovalResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckUrgentChatMessage

> ChatUrgentResponse CheckUrgentChatMessage(ctx).ChatUrgent(chatUrgent).XOrganizationId(xOrganizationId).Execute()

Stop only the project's recent work an urgent message contradicts

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
	var chatUrgent openapiclient.ChatUrgent
	if err := json.Unmarshal([]byte("{\"content\":\"text\",\"projectId\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &chatUrgent); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.CheckUrgentChatMessage(ctx).ChatUrgent(chatUrgent).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.CheckUrgentChatMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckUrgentChatMessage`: ChatUrgentResponse
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.CheckUrgentChatMessage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCheckUrgentChatMessageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatUrgent** | [**ChatUrgent**](ChatUrgent.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ChatUrgentResponse**](ChatUrgentResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConnectChatSocket

> ConversationConnection ConnectChatSocket(ctx).ConversationConnect(conversationConnect).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the proof a conversation's socket upgrade presents

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
	var conversationConnect openapiclient.ConversationConnect
	if err := json.Unmarshal([]byte("{\"chatId\":\"text\"}"), &conversationConnect); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ConnectChatSocket(ctx).ConversationConnect(conversationConnect).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ConnectChatSocket``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConnectChatSocket`: ConversationConnection
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ConnectChatSocket`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiConnectChatSocketRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **conversationConnect** | [**ConversationConnect**](ConversationConnect.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationConnection**](ConversationConnection.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConnectProjectStream

> ConversationConnection ConnectProjectStream(ctx, id).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Get the proof a project stream's socket upgrade presents

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
	resp, r, err := apiClient.ChatAPI.ConnectProjectStream(ctx, id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ConnectProjectStream``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConnectProjectStream`: ConversationConnection
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ConnectProjectStream`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiConnectProjectStreamRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationConnection**](ConversationConnection.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateChat

> ConversationChatCreated CreateChat(ctx).ConversationChatCreate(conversationChatCreate).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Start a chat session with an agent

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
	var conversationChatCreate openapiclient.ConversationChatCreate
	if err := json.Unmarshal([]byte("{\"chatId\":\"text\",\"id\":\"123e4567-e89b-42d3-a456-426614174000\"}"), &conversationChatCreate); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.CreateChat(ctx).ConversationChatCreate(conversationChatCreate).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.CreateChat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateChat`: ConversationChatCreated
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.CreateChat`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiCreateChatRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **conversationChatCreate** | [**ConversationChatCreate**](ConversationChatCreate.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationChatCreated**](ConversationChatCreated.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChatDirectory

> ChatDirectoryResponse ListChatDirectory(ctx).Q(q).Visibility(visibility).ProjectId(projectId).Page(page).PageSize(pageSize).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Search your private and accessible shared project conversations

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
	q := "q_example" // string | Search title, project or agent name. Up to 200 characters. (optional)
	visibility := "visibility_example" // string | all (default), private or shared. (optional)
	projectId := "projectId_example" // string | Limit shared conversations to an accessible project. (optional)
	page := "page_example" // string | One-based page, default 1. (optional)
	pageSize := "pageSize_example" // string | 1–50 conversations per page, default 20. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListChatDirectory(ctx).Q(q).Visibility(visibility).ProjectId(projectId).Page(page).PageSize(pageSize).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListChatDirectory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChatDirectory`: ChatDirectoryResponse
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListChatDirectory`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListChatDirectoryRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **string** | Search title, project or agent name. Up to 200 characters. |
 **visibility** | **string** | all (default), private or shared. |
 **projectId** | **string** | Limit shared conversations to an accessible project. |
 **page** | **string** | One-based page, default 1. |
 **pageSize** | **string** | 1–50 conversations per page, default 20. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ChatDirectoryResponse**](ChatDirectoryResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChatMessages

> ConversationMessages ListChatMessages(ctx).ChatId(chatId).Limit(limit).Before(before).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read a conversation's messages, newest page first

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
	chatId := "chatId_example" // string | The conversation's address.
	limit := "limit_example" // string | How many transcript entries one page holds, 1 to 200. Default 50. (optional)
	before := "before_example" // string | The `next` of the page you have: read the messages before it. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListChatMessages(ctx).ChatId(chatId).Limit(limit).Before(before).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListChatMessages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChatMessages`: ConversationMessages
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListChatMessages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListChatMessagesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatId** | **string** | The conversation&#39;s address. |
 **limit** | **string** | How many transcript entries one page holds, 1 to 200. Default 50. |
 **before** | **string** | The &#x60;next&#x60; of the page you have: read the messages before it. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationMessages**](ConversationMessages.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChats

> ConversationChats ListChats(ctx).ChatId(chatId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List the chat sessions of a conversation you may see

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
	chatId := "chatId_example" // string | The conversation's address, or one of its sessions'.
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListChats(ctx).ChatId(chatId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListChats``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChats`: ConversationChats
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListChats`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiListChatsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatId** | **string** | The conversation&#39;s address, or one of its sessions&#39;. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationChats**](ConversationChats.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendChatTurn

> ConversationReceipt SendChatTurn(ctx).ConversationSend(conversationSend).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Send a message to a conversation and return while the agent works

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
	var conversationSend openapiclient.ConversationSend
	if err := json.Unmarshal([]byte("{\"chatId\":\"text\",\"message\":\"text\"}"), &conversationSend); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.SendChatTurn(ctx).ConversationSend(conversationSend).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.SendChatTurn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendChatTurn`: ConversationReceipt
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.SendChatTurn`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiSendChatTurnRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **conversationSend** | [**ConversationSend**](ConversationSend.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationReceipt**](ConversationReceipt.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPrivateChatModel

> PrivateChatModelResponse SetPrivateChatModel(ctx, id).ConversationModel(conversationModel).XOrganizationId(xOrganizationId).Execute()

Choose the model for your private conversation

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
	id := "id_example" // string |
	var conversationModel openapiclient.ConversationModel
	if err := json.Unmarshal([]byte("{\"model\":\"text\"}"), &conversationModel); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.SetPrivateChatModel(ctx, id).ConversationModel(conversationModel).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.SetPrivateChatModel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPrivateChatModel`: PrivateChatModelResponse
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.SetPrivateChatModel`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Pass optional parameters through the `apiSetPrivateChatModelRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **conversationModel** | [**ConversationModel**](ConversationModel.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**PrivateChatModelResponse**](PrivateChatModelResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StopChatTurn

> ConversationStopResponse StopChatTurn(ctx).ConversationStop(conversationStop).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Stop the turn a conversation is running

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
	var conversationStop openapiclient.ConversationStop
	if err := json.Unmarshal([]byte("{\"chatId\":\"text\"}"), &conversationStop); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.StopChatTurn(ctx).ConversationStop(conversationStop).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.StopChatTurn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StopChatTurn`: ConversationStopResponse
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.StopChatTurn`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiStopChatTurnRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **conversationStop** | [**ConversationStop**](ConversationStop.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

[**ConversationStopResponse**](ConversationStopResponse.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamChatEvents

> string StreamChatEvents(ctx).ChatId(chatId).From(from).Gen(gen).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Follow a conversation as Server-Sent Events

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
	chatId := "chatId_example" // string | The conversation's address.
	from := "from_example" // string | The next event the client wants; `Last-Event-ID` says the same after a reconnect. (optional)
	gen := "gen_example" // string | The stream generation `from` belongs to; a stale one starts from a snapshot. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.StreamChatEvents(ctx).ChatId(chatId).From(from).Gen(gen).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.StreamChatEvents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamChatEvents`: string
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.StreamChatEvents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiStreamChatEventsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatId** | **string** | The conversation&#39;s address. |
 **from** | **string** | The next event the client wants; &#x60;Last-Event-ID&#x60; says the same after a reconnect. |
 **gen** | **string** | The stream generation &#x60;from&#x60; belongs to; a stale one starts from a snapshot. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |
 **xClientPortal** | **string** | The agency Workspace ID for a signed-in client&#39;s portal requests. A verified user session and portal membership are required; API keys cannot authenticate portal access. This header does not grant agency administration access. |

### Return type

**string**

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/event-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadChatAttachment

> ChatAttachment UploadChatAttachment(ctx).File(file).XOrganizationId(xOrganizationId).Execute()

Store a file for a chat turn to name

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
	file := os.NewFile(1234, "some_file") // *os.File |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.UploadChatAttachment(ctx).File(file).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.UploadChatAttachment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadChatAttachment`: ChatAttachment
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.UploadChatAttachment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Pass optional parameters through the `apiUploadChatAttachmentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ChatAttachment**](ChatAttachment.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

