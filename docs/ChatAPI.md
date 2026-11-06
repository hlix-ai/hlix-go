# \ChatAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckUrgentChatMessage**](ChatAPI.md#CheckUrgentChatMessage) | **Post** /v1/api/chat/urgent | Stop only the project&#39;s recent work an urgent message contradicts
[**CreateChatSession**](ChatAPI.md#CreateChatSession) | **Post** /v1/api/chat/sessions | Start a chat session with an agent, or fork one at a message
[**GetChatTurn**](ChatAPI.md#GetChatTurn) | **Get** /v1/api/chat/turns/{turnId} | Read where a sent message stands and the agent&#39;s answer
[**ListChatDirectory**](ChatAPI.md#ListChatDirectory) | **Get** /v1/api/chat/directory | Search your private and accessible shared project conversations
[**ListChatMessages**](ChatAPI.md#ListChatMessages) | **Get** /v1/api/chat/messages | Read the projectless chat transcript
[**ListChatSessionMessages**](ChatAPI.md#ListChatSessionMessages) | **Get** /v1/api/chat/sessions/{id}/messages | Read one chat session&#39;s history
[**ListChatSessions**](ChatAPI.md#ListChatSessions) | **Get** /v1/api/chat/sessions | List your chat sessions with one agent
[**SendChatTurn**](ChatAPI.md#SendChatTurn) | **Post** /v1/api/chat/turns | Send a message to a project and return while the agent works
[**SetPrivateChatModel**](ChatAPI.md#SetPrivateChatModel) | **Patch** /v1/api/chat/sessions/{id}/model | Choose the model for your private conversation
[**StopChatTurn**](ChatAPI.md#StopChatTurn) | **Post** /v1/api/chat/stop | Request cancellation of your exact model turn across replicas
[**UploadChatAttachment**](ChatAPI.md#UploadChatAttachment) | **Post** /v1/api/chat/attachments | Store a file for a chat turn to name



## CheckUrgentChatMessage

> ChatUrgentResponse CheckUrgentChatMessage(ctx).ChatUrgent(chatUrgent).XOrganizationId(xOrganizationId).Execute()

Stop only the project's recent work an urgent message contradicts

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
	chatUrgent := *openapiclient.NewChatUrgent("Content_example", "ProjectId_example") // ChatUrgent | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.CheckUrgentChatMessage(context.Background()).ChatUrgent(chatUrgent).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiCheckUrgentChatMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatUrgent** | [**ChatUrgent**](ChatUrgent.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ChatUrgentResponse**](ChatUrgentResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateChatSession

> ChatSessionCreated CreateChatSession(ctx).ChatSessionCreate(chatSessionCreate).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Start a chat session with an agent, or fork one at a message

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
	chatSessionCreate := *openapiclient.NewChatSessionCreate("SessionId_example") // ChatSessionCreate | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.CreateChatSession(context.Background()).ChatSessionCreate(chatSessionCreate).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.CreateChatSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateChatSession`: ChatSessionCreated
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.CreateChatSession`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateChatSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatSessionCreate** | [**ChatSessionCreate**](ChatSessionCreate.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ChatSessionCreated**](ChatSessionCreated.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetChatTurn

> ChatTurnResult GetChatTurn(ctx, turnId).ProjectId(projectId).ActiveCycleId(activeCycleId).TaskId(taskId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read where a sent message stands and the agent's answer

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
	turnId := "turnId_example" // string | 
	projectId := "projectId_example" // string | The project the turn was sent to.
	activeCycleId := "activeCycleId_example" // string | The cycle, when the turn was sent to one. (optional)
	taskId := "taskId_example" // string | The task, when the turn was sent to one. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.GetChatTurn(context.Background(), turnId).ProjectId(projectId).ActiveCycleId(activeCycleId).TaskId(taskId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.GetChatTurn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetChatTurn`: ChatTurnResult
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.GetChatTurn`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**turnId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetChatTurnRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectId** | **string** | The project the turn was sent to. | 
 **activeCycleId** | **string** | The cycle, when the turn was sent to one. | 
 **taskId** | **string** | The task, when the turn was sent to one. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ChatTurnResult**](ChatTurnResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChatDirectory

> ChatDirectoryResponse ListChatDirectory(ctx).Q(q).Visibility(visibility).ProjectId(projectId).Page(page).PageSize(pageSize).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Search your private and accessible shared project conversations

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
	q := "q_example" // string | Search title, project or agent name. Up to 200 characters. (optional)
	visibility := "visibility_example" // string | all (default), private or shared. (optional)
	projectId := "projectId_example" // string | Limit shared conversations to an accessible project. (optional)
	page := "page_example" // string | One-based page, default 1. (optional)
	pageSize := "pageSize_example" // string | 1–50 conversations per page, default 20. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListChatDirectory(context.Background()).Q(q).Visibility(visibility).ProjectId(projectId).Page(page).PageSize(pageSize).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
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

Other parameters are passed through a pointer to a apiListChatDirectoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **string** | Search title, project or agent name. Up to 200 characters. | 
 **visibility** | **string** | all (default), private or shared. | 
 **projectId** | **string** | Limit shared conversations to an accessible project. | 
 **page** | **string** | One-based page, default 1. | 
 **pageSize** | **string** | 1–50 conversations per page, default 20. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ChatDirectoryResponse**](ChatDirectoryResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChatMessages

> []WireMessage ListChatMessages(ctx).XOrganizationId(xOrganizationId).Execute()

Read the projectless chat transcript

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
	resp, r, err := apiClient.ChatAPI.ListChatMessages(context.Background()).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListChatMessages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChatMessages`: []WireMessage
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListChatMessages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListChatMessagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]WireMessage**](WireMessage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChatSessionMessages

> []WireMessage ListChatSessionMessages(ctx, id).ThreadId(threadId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Read one chat session's history

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
	threadId := "threadId_example" // string | The session live address returned when it was created or listed.
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListChatSessionMessages(context.Background(), id).ThreadId(threadId).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListChatSessionMessages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChatSessionMessages`: []WireMessage
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListChatSessionMessages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListChatSessionMessagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **threadId** | **string** | The session live address returned when it was created or listed. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**[]WireMessage**](WireMessage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListChatSessions

> ChatSessionList ListChatSessions(ctx).ProjectId(projectId).AgentId(agentId).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

List your chat sessions with one agent

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
	projectId := "projectId_example" // string | The project whose manager (or, with `agentId`, team agent) the sessions are with. Omitted: your own workspace assistant. (optional)
	agentId := "agentId_example" // string | The team agent, within `projectId`. (optional)
	limit := "limit_example" // string | How many sessions one page holds, 1 to 100. Default 50. (optional)
	cursor := "cursor_example" // string | The `nextCursor` of the page you have: read the next, older sessions. A session started between two reads can appear on both pages; merge them by `id`. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListChatSessions(context.Background()).ProjectId(projectId).AgentId(agentId).Limit(limit).Cursor(cursor).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListChatSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListChatSessions`: ChatSessionList
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListChatSessions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListChatSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **projectId** | **string** | The project whose manager (or, with &#x60;agentId&#x60;, team agent) the sessions are with. Omitted: your own workspace assistant. | 
 **agentId** | **string** | The team agent, within &#x60;projectId&#x60;. | 
 **limit** | **string** | How many sessions one page holds, 1 to 100. Default 50. | 
 **cursor** | **string** | The &#x60;nextCursor&#x60; of the page you have: read the next, older sessions. A session started between two reads can appear on both pages; merge them by &#x60;id&#x60;. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ChatSessionList**](ChatSessionList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendChatTurn

> ChatTurnAccepted SendChatTurn(ctx).ChatSend(chatSend).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Send a message to a project and return while the agent works

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
	chatSend := *openapiclient.NewChatSend("Message_example", "ProjectId_example") // ChatSend | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.SendChatTurn(context.Background()).ChatSend(chatSend).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.SendChatTurn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendChatTurn`: ChatTurnAccepted
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.SendChatTurn`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendChatTurnRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatSend** | [**ChatSend**](ChatSend.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ChatTurnAccepted**](ChatTurnAccepted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPrivateChatModel

> PrivateChatModelResponse SetPrivateChatModel(ctx, id).PrivateChatModel(privateChatModel).XOrganizationId(xOrganizationId).Execute()

Choose the model for your private conversation

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
	privateChatModel := *openapiclient.NewPrivateChatModel("Model_example") // PrivateChatModel | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.SetPrivateChatModel(context.Background(), id).PrivateChatModel(privateChatModel).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiSetPrivateChatModelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **privateChatModel** | [**PrivateChatModel**](PrivateChatModel.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**PrivateChatModelResponse**](PrivateChatModelResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StopChatTurn

> ChatStopResponse StopChatTurn(ctx).ChatStop(chatStop).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()

Request cancellation of your exact model turn across replicas

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
	chatStop := *openapiclient.NewChatStop("TurnId_example") // ChatStop | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)
	xClientPortal := "xClientPortal_example" // string | Agency organization id for one aggregate client dashboard; server derives only this caller's workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.StopChatTurn(context.Background()).ChatStop(chatStop).XOrganizationId(xOrganizationId).XClientPortal(xClientPortal).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.StopChatTurn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StopChatTurn`: ChatStopResponse
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.StopChatTurn`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStopChatTurnRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **chatStop** | [**ChatStop**](ChatStop.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 
 **xClientPortal** | **string** | Agency organization id for one aggregate client dashboard; server derives only this caller&#39;s workspace relationship and owned account seats. Legacy account ids remain narrowly compatible. Real verified user session required for agency context; administration denied. | 

### Return type

[**ChatStopResponse**](ChatStopResponse.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadChatAttachment

> ChatAttachment UploadChatAttachment(ctx).File(file).XOrganizationId(xOrganizationId).Execute()

Store a file for a chat turn to name

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
	file := os.NewFile(1234, "some_file") // *os.File | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.UploadChatAttachment(context.Background()).File(file).XOrganizationId(xOrganizationId).Execute()
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

Other parameters are passed through a pointer to a apiUploadChatAttachmentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ChatAttachment**](ChatAttachment.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

