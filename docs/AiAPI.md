# \AiAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AnalyzeAiMedia**](AiAPI.md#AnalyzeAiMedia) | **Post** /v1/api/ai/media/analyze | Ask a question about an image or a video
[**CreateHlixCodeChatCompletion**](AiAPI.md#CreateHlixCodeChatCompletion) | **Post** /v1/api/ai/w/{workspaceId}/chat/completions | Run an OpenAI-compatible chat completion on the workspace&#39;s own model budget
[**CreateHlixCodeMessage**](AiAPI.md#CreateHlixCodeMessage) | **Post** /v1/api/ai/w/{workspaceId}/v1/messages | Run an Anthropic Messages request on the workspace&#39;s own model budget
[**CreateHlixCodeResponse**](AiAPI.md#CreateHlixCodeResponse) | **Post** /v1/api/ai/w/{workspaceId}/responses | Run an OpenAI Responses request on the workspace&#39;s own model budget
[**GenerateAiImages**](AiAPI.md#GenerateAiImages) | **Post** /v1/api/ai/media/images | Generate images
[**GenerateAiVideo**](AiAPI.md#GenerateAiVideo) | **Post** /v1/api/ai/media/video | Submit a video generation
[**GetAiAsset**](AiAPI.md#GetAiAsset) | **Get** /v1/api/ai/assets/{key} | Fetch one stored AI artifact
[**GetAiBatch**](AiAPI.md#GetAiBatch) | **Get** /v1/api/ai/batches/{id} | Read one batch and a page of its items
[**GetAiDocument**](AiAPI.md#GetAiDocument) | **Get** /v1/api/ai/documents/{id} | Read one parsed document
[**GetAiVideoJob**](AiAPI.md#GetAiVideoJob) | **Get** /v1/api/ai/media/video/{id} | Read one video job
[**ListAiDocuments**](AiAPI.md#ListAiDocuments) | **Get** /v1/api/ai/documents | List recently parsed documents
[**ListHlixCodeModels**](AiAPI.md#ListHlixCodeModels) | **Get** /v1/api/ai/w/{workspaceId}/models | List the models a Hlix Code session may run, and the workspace default
[**ParseAiDocument**](AiAPI.md#ParseAiDocument) | **Post** /v1/api/ai/documents | Parse a document into markdown
[**PollAiBatch**](AiAPI.md#PollAiBatch) | **Post** /v1/api/ai/batches/{id}/poll | Poll one batch now
[**ReviewAiVideoJob**](AiAPI.md#ReviewAiVideoJob) | **Post** /v1/api/ai/media/video/{id}/review | Record a review verdict on a generated video
[**SubmitAiBatch**](AiAPI.md#SubmitAiBatch) | **Post** /v1/api/ai/batches | Submit a batch of offline requests
[**SynthesizeAiSpeech**](AiAPI.md#SynthesizeAiSpeech) | **Post** /v1/api/ai/media/speech | Synthesize speech
[**TranscribeAiAudio**](AiAPI.md#TranscribeAiAudio) | **Post** /v1/api/ai/media/transcriptions | Transcribe stored audio



## AnalyzeAiMedia

> AiTextResult AnalyzeAiMedia(ctx).AnalyzeMedia(analyzeMedia).XOrganizationId(xOrganizationId).Execute()

Ask a question about an image or a video

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
	analyzeMedia := *openapiclient.NewAnalyzeMedia("Kind_example", "Question_example", *openapiclient.NewAnalyzeMediaSource("Url_example", "ArtifactKey_example")) // AnalyzeMedia | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.AnalyzeAiMedia(context.Background()).AnalyzeMedia(analyzeMedia).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.AnalyzeAiMedia``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AnalyzeAiMedia`: AiTextResult
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.AnalyzeAiMedia`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAnalyzeAiMediaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **analyzeMedia** | [**AnalyzeMedia**](AnalyzeMedia.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiTextResult**](AiTextResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateHlixCodeChatCompletion

> ChatCompletion CreateHlixCodeChatCompletion(ctx, workspaceId).ChatCompletions(chatCompletions).XOrganizationId(xOrganizationId).Execute()

Run an OpenAI-compatible chat completion on the workspace's own model budget

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
	workspaceId := "workspaceId_example" // string | 
	chatCompletions := *openapiclient.NewChatCompletions([]interface{}{nil}) // ChatCompletions | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateHlixCodeChatCompletion(context.Background(), workspaceId).ChatCompletions(chatCompletions).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.CreateHlixCodeChatCompletion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateHlixCodeChatCompletion`: ChatCompletion
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.CreateHlixCodeChatCompletion`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateHlixCodeChatCompletionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **chatCompletions** | [**ChatCompletions**](ChatCompletions.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ChatCompletion**](ChatCompletion.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateHlixCodeMessage

> AnthropicMessage CreateHlixCodeMessage(ctx, workspaceId).AnthropicMessages(anthropicMessages).XOrganizationId(xOrganizationId).Execute()

Run an Anthropic Messages request on the workspace's own model budget

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
	workspaceId := "workspaceId_example" // string | 
	anthropicMessages := *openapiclient.NewAnthropicMessages([]interface{}{nil}) // AnthropicMessages | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateHlixCodeMessage(context.Background(), workspaceId).AnthropicMessages(anthropicMessages).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.CreateHlixCodeMessage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateHlixCodeMessage`: AnthropicMessage
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.CreateHlixCodeMessage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateHlixCodeMessageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **anthropicMessages** | [**AnthropicMessages**](AnthropicMessages.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AnthropicMessage**](AnthropicMessage.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateHlixCodeResponse

> ResponsesResult CreateHlixCodeResponse(ctx, workspaceId).Responses(responses).XOrganizationId(xOrganizationId).Execute()

Run an OpenAI Responses request on the workspace's own model budget

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
	workspaceId := "workspaceId_example" // string | 
	responses := *openapiclient.NewResponses(*openapiclient.NewResponsesInput()) // Responses | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateHlixCodeResponse(context.Background(), workspaceId).Responses(responses).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.CreateHlixCodeResponse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateHlixCodeResponse`: ResponsesResult
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.CreateHlixCodeResponse`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateHlixCodeResponseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **responses** | [**Responses**](Responses.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**ResponsesResult**](ResponsesResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateAiImages

> AiGeneratedImages GenerateAiImages(ctx).GenerateImages(generateImages).XOrganizationId(xOrganizationId).Execute()

Generate images

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
	generateImages := *openapiclient.NewGenerateImages("Prompt_example") // GenerateImages | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GenerateAiImages(context.Background()).GenerateImages(generateImages).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.GenerateAiImages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateAiImages`: AiGeneratedImages
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.GenerateAiImages`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateAiImagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateImages** | [**GenerateImages**](GenerateImages.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiGeneratedImages**](AiGeneratedImages.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateAiVideo

> AiMediaJobAccepted GenerateAiVideo(ctx).GenerateVideo(generateVideo).XOrganizationId(xOrganizationId).Execute()

Submit a video generation

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
	generateVideo := *openapiclient.NewGenerateVideo("IdempotencyKey_example", "Prompt_example") // GenerateVideo | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GenerateAiVideo(context.Background()).GenerateVideo(generateVideo).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.GenerateAiVideo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateAiVideo`: AiMediaJobAccepted
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.GenerateAiVideo`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateAiVideoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateVideo** | [**GenerateVideo**](GenerateVideo.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiMediaJobAccepted**](AiMediaJobAccepted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiAsset

> SignedArtifactUrl GetAiAsset(ctx, key).Download(download).XOrganizationId(xOrganizationId).Execute()

Fetch one stored AI artifact

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
	key := "key_example" // string | 
	download := "download_example" // string | Set to `1` to receive the object's own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body's `url` is this same route with `download=1` already appended, so following it is the normal flow; any other value, absent included, answers the JSON. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GetAiAsset(context.Background(), key).Download(download).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.GetAiAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiAsset`: SignedArtifactUrl
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.GetAiAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**key** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAiAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **download** | **string** | Set to &#x60;1&#x60; to receive the object&#39;s own bytes instead of a JSON pointer. It only changes anything when this deployment cannot hand back a signed URL — artifacts stored locally, or a signed download link could not be issued for this request — because a signed URL is always answered as JSON. In that case the JSON body&#39;s &#x60;url&#x60; is this same route with &#x60;download&#x3D;1&#x60; already appended, so following it is the normal flow; any other value, absent included, answers the JSON. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiBatch

> AiBatchRead GetAiBatch(ctx, id).Limit(limit).After(after).XOrganizationId(xOrganizationId).Execute()

Read one batch and a page of its items

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
	limit := "limit_example" // string | How many items to return, 1–1000. Defaults to 200. Rejected rather than clamped: a substituted window is how a paging loop skips rows unnoticed. (optional)
	after := "after_example" // string | The previous page's `nextCursor`, verbatim — the last `customId` it returned. Omit for the first page. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GetAiBatch(context.Background(), id).Limit(limit).After(after).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.GetAiBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiBatch`: AiBatchRead
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.GetAiBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAiBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | How many items to return, 1–1000. Defaults to 200. Rejected rather than clamped: a substituted window is how a paging loop skips rows unnoticed. | 
 **after** | **string** | The previous page&#39;s &#x60;nextCursor&#x60;, verbatim — the last &#x60;customId&#x60; it returned. Omit for the first page. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiBatchRead**](AiBatchRead.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiDocument

> AiDocumentRead GetAiDocument(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read one parsed document

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
	resp, r, err := apiClient.AiAPI.GetAiDocument(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.GetAiDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiDocument`: AiDocumentRead
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.GetAiDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAiDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiDocumentRead**](AiDocumentRead.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiVideoJob

> AiMediaJobRead GetAiVideoJob(ctx, id).XOrganizationId(xOrganizationId).Execute()

Read one video job

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
	resp, r, err := apiClient.AiAPI.GetAiVideoJob(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.GetAiVideoJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiVideoJob`: AiMediaJobRead
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.GetAiVideoJob`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAiVideoJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiMediaJobRead**](AiMediaJobRead.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAiDocuments

> []AiDocument ListAiDocuments(ctx).Limit(limit).XOrganizationId(xOrganizationId).Execute()

List recently parsed documents

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
	limit := "limit_example" // string | How many rows to return, newest first. Clamped to 200; anything unparseable falls back to 50. (optional)
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ListAiDocuments(context.Background()).Limit(limit).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.ListAiDocuments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAiDocuments`: []AiDocument
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.ListAiDocuments`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListAiDocumentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | How many rows to return, newest first. Clamped to 200; anything unparseable falls back to 50. | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**[]AiDocument**](AiDocument.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListHlixCodeModels

> HlixCodeModels ListHlixCodeModels(ctx, workspaceId).XOrganizationId(xOrganizationId).Execute()

List the models a Hlix Code session may run, and the workspace default

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
	workspaceId := "workspaceId_example" // string | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ListHlixCodeModels(context.Background(), workspaceId).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.ListHlixCodeModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListHlixCodeModels`: HlixCodeModels
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.ListHlixCodeModels`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListHlixCodeModelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**HlixCodeModels**](HlixCodeModels.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ParseAiDocument

> AiDocumentParsed ParseAiDocument(ctx).ParseDocument(parseDocument).XOrganizationId(xOrganizationId).Execute()

Parse a document into markdown

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
	parseDocument := *openapiclient.NewParseDocument(*openapiclient.NewParseDocumentSource("Kind_example", "Url_example", "Key_example")) // ParseDocument | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ParseAiDocument(context.Background()).ParseDocument(parseDocument).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.ParseAiDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ParseAiDocument`: AiDocumentParsed
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.ParseAiDocument`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiParseAiDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **parseDocument** | [**ParseDocument**](ParseDocument.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiDocumentParsed**](AiDocumentParsed.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PollAiBatch

> AiBatchPoll PollAiBatch(ctx, id).XOrganizationId(xOrganizationId).Execute()

Poll one batch now

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
	resp, r, err := apiClient.AiAPI.PollAiBatch(context.Background(), id).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.PollAiBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PollAiBatch`: AiBatchPoll
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.PollAiBatch`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPollAiBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiBatchPoll**](AiBatchPoll.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReviewAiVideoJob

> AiMediaJobRead ReviewAiVideoJob(ctx, id).ReviewMediaJob(reviewMediaJob).XOrganizationId(xOrganizationId).Execute()

Record a review verdict on a generated video

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
	reviewMediaJob := *openapiclient.NewReviewMediaJob("State_example") // ReviewMediaJob | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ReviewAiVideoJob(context.Background(), id).ReviewMediaJob(reviewMediaJob).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.ReviewAiVideoJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReviewAiVideoJob`: AiMediaJobRead
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.ReviewAiVideoJob`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReviewAiVideoJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reviewMediaJob** | [**ReviewMediaJob**](ReviewMediaJob.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiMediaJobRead**](AiMediaJobRead.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubmitAiBatch

> AiBatchAccepted SubmitAiBatch(ctx).SubmitBatch(submitBatch).XOrganizationId(xOrganizationId).Execute()

Submit a batch of offline requests

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
	submitBatch := *openapiclient.NewSubmitBatch("Endpoint_example", "IdempotencyKey_example", []openapiclient.SubmitBatchItemsInner{*openapiclient.NewSubmitBatchItemsInner(map[string]interface{}{"key": interface{}(123)}, "CustomId_example")}, "Kind_example", "Model_example", *openapiclient.NewSubmitBatchPolicy(false)) // SubmitBatch | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.SubmitAiBatch(context.Background()).SubmitBatch(submitBatch).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.SubmitAiBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubmitAiBatch`: AiBatchAccepted
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.SubmitAiBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubmitAiBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **submitBatch** | [**SubmitBatch**](SubmitBatch.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiBatchAccepted**](AiBatchAccepted.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SynthesizeAiSpeech

> AiSpeech SynthesizeAiSpeech(ctx).SynthesizeSpeech(synthesizeSpeech).XOrganizationId(xOrganizationId).Execute()

Synthesize speech

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
	synthesizeSpeech := *openapiclient.NewSynthesizeSpeech("Text_example", "Voice_example") // SynthesizeSpeech | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.SynthesizeAiSpeech(context.Background()).SynthesizeSpeech(synthesizeSpeech).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.SynthesizeAiSpeech``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SynthesizeAiSpeech`: AiSpeech
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.SynthesizeAiSpeech`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSynthesizeAiSpeechRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **synthesizeSpeech** | [**SynthesizeSpeech**](SynthesizeSpeech.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiSpeech**](AiSpeech.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TranscribeAiAudio

> AiTextResult TranscribeAiAudio(ctx).TranscribeAudio(transcribeAudio).XOrganizationId(xOrganizationId).Execute()

Transcribe stored audio

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
	transcribeAudio := *openapiclient.NewTranscribeAudio("ArtifactKey_example", "Format_example") // TranscribeAudio | 
	xOrganizationId := "xOrganizationId_example" // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.TranscribeAiAudio(context.Background()).TranscribeAudio(transcribeAudio).XOrganizationId(xOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiAPI.TranscribeAiAudio``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TranscribeAiAudio`: AiTextResult
	fmt.Fprintf(os.Stdout, "Response from `AiAPI.TranscribeAiAudio`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTranscribeAiAudioRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transcribeAudio** | [**TranscribeAudio**](TranscribeAudio.md) |  | 
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. | 

### Return type

[**AiTextResult**](AiTextResult.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

