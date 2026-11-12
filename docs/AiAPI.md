# AiAPI

All URIs are relative to *https://server.hlix.ai*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AnalyzeAiMedia**](AiAPI.md#analyzeaimedia) | **Post** /v1/api/ai/media/analyze | Ask a question about an image or a video
[**CreateHlixCodeChatCompletion**](AiAPI.md#createhlixcodechatcompletion) | **Post** /v1/api/ai/w/{workspaceId}/chat/completions | Run an OpenAI-compatible chat completion on the workspace&#39;s own model budget
[**CreateHlixCodeMessage**](AiAPI.md#createhlixcodemessage) | **Post** /v1/api/ai/w/{workspaceId}/v1/messages | Run an Anthropic Messages request on the workspace&#39;s own model budget
[**CreateHlixCodeResponse**](AiAPI.md#createhlixcoderesponse) | **Post** /v1/api/ai/w/{workspaceId}/responses | Run an OpenAI Responses request on the workspace&#39;s own model budget
[**GenerateAiImages**](AiAPI.md#generateaiimages) | **Post** /v1/api/ai/media/images | Generate images
[**GenerateAiVideo**](AiAPI.md#generateaivideo) | **Post** /v1/api/ai/media/video | Submit a video generation
[**GetAiAsset**](AiAPI.md#getaiasset) | **Get** /v1/api/ai/assets/{key} | Fetch one stored AI artifact
[**GetAiBatch**](AiAPI.md#getaibatch) | **Get** /v1/api/ai/batches/{id} | Read one batch and a page of its items
[**GetAiDocument**](AiAPI.md#getaidocument) | **Get** /v1/api/ai/documents/{id} | Read one parsed document
[**GetAiVideoJob**](AiAPI.md#getaivideojob) | **Get** /v1/api/ai/media/video/{id} | Read one video job
[**ListAiDocuments**](AiAPI.md#listaidocuments) | **Get** /v1/api/ai/documents | List recently parsed documents
[**ListHlixCodeModels**](AiAPI.md#listhlixcodemodels) | **Get** /v1/api/ai/w/{workspaceId}/models | List the models a Hlix Code session may run, and the workspace default
[**ParseAiDocument**](AiAPI.md#parseaidocument) | **Post** /v1/api/ai/documents | Parse a document into markdown
[**PollAiBatch**](AiAPI.md#pollaibatch) | **Post** /v1/api/ai/batches/{id}/poll | Poll one batch now
[**ReviewAiVideoJob**](AiAPI.md#reviewaivideojob) | **Post** /v1/api/ai/media/video/{id}/review | Record a review verdict on a generated video
[**SubmitAiBatch**](AiAPI.md#submitaibatch) | **Post** /v1/api/ai/batches | Submit a batch of offline requests
[**SynthesizeAiSpeech**](AiAPI.md#synthesizeaispeech) | **Post** /v1/api/ai/media/speech | Synthesize speech
[**TranscribeAiAudio**](AiAPI.md#transcribeaiaudio) | **Post** /v1/api/ai/media/transcriptions | Transcribe stored audio



## AnalyzeAiMedia

> AiTextResult AnalyzeAiMedia(ctx).AnalyzeMedia(analyzeMedia).XOrganizationId(xOrganizationId).Execute()

Ask a question about an image or a video

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
	var analyzeMedia openapiclient.AnalyzeMedia
	if err := json.Unmarshal([]byte("{\"kind\":\"image\",\"question\":\"text\",\"source\":{\"url\":\"https://example.com\"}}"), &analyzeMedia); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.AnalyzeAiMedia(ctx).AnalyzeMedia(analyzeMedia).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiAnalyzeAiMediaRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **analyzeMedia** | [**AnalyzeMedia**](AnalyzeMedia.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiTextResult**](AiTextResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	workspaceId := "workspaceId_example" // string |
	var chatCompletions openapiclient.ChatCompletions
	if err := json.Unmarshal([]byte("{\"messages\":[\"value\"]}"), &chatCompletions); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateHlixCodeChatCompletion(ctx, workspaceId).ChatCompletions(chatCompletions).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateHlixCodeChatCompletionRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **chatCompletions** | [**ChatCompletions**](ChatCompletions.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ChatCompletion**](ChatCompletion.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	workspaceId := "workspaceId_example" // string |
	var anthropicMessages openapiclient.AnthropicMessages
	if err := json.Unmarshal([]byte("{\"messages\":[\"value\"]}"), &anthropicMessages); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateHlixCodeMessage(ctx, workspaceId).AnthropicMessages(anthropicMessages).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateHlixCodeMessageRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **anthropicMessages** | [**AnthropicMessages**](AnthropicMessages.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AnthropicMessage**](AnthropicMessage.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	workspaceId := "workspaceId_example" // string |
	var responses openapiclient.Responses
	if err := json.Unmarshal([]byte("{\"input\":\"text\"}"), &responses); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.CreateHlixCodeResponse(ctx, workspaceId).Responses(responses).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiCreateHlixCodeResponseRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **responses** | [**Responses**](Responses.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**ResponsesResult**](ResponsesResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var generateImages openapiclient.GenerateImages
	if err := json.Unmarshal([]byte("{\"prompt\":\"text\"}"), &generateImages); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GenerateAiImages(ctx).GenerateImages(generateImages).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGenerateAiImagesRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateImages** | [**GenerateImages**](GenerateImages.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiGeneratedImages**](AiGeneratedImages.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var generateVideo openapiclient.GenerateVideo
	if err := json.Unmarshal([]byte("{\"idempotencyKey\":\"text\",\"prompt\":\"text\"}"), &generateVideo); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GenerateAiVideo(ctx).GenerateVideo(generateVideo).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGenerateAiVideoRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **generateVideo** | [**GenerateVideo**](GenerateVideo.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiMediaJobAccepted**](AiMediaJobAccepted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	key := "key_example" // string |
	download := "download_example" // string | Set to `1` to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with `download=1` in its `url`. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GetAiAsset(ctx, key).Download(download).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetAiAssetRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **download** | **string** | Set to &#x60;1&#x60; to download artifact bytes when a signed URL cannot be issued. The default JSON response then provides this route with &#x60;download&#x3D;1&#x60; in its &#x60;url&#x60;. When a signed URL is available, the endpoint returns that URL as JSON regardless of this parameter. Other values, including an omitted parameter, return JSON. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**SignedArtifactUrl**](SignedArtifactUrl.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	limit := "limit_example" // string | Page size, 1–1000; default 200. Invalid values are rejected rather than clamped. (optional)
	after := "after_example" // string | The previous page's `nextCursor`, verbatim — the last `customId` it returned. Omit for the first page. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.GetAiBatch(ctx, id).Limit(limit).After(after).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetAiBatchRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **string** | Page size, 1–1000; default 200. Invalid values are rejected rather than clamped. |
 **after** | **string** | The previous page&#39;s &#x60;nextCursor&#x60;, verbatim — the last &#x60;customId&#x60; it returned. Omit for the first page. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiBatchRead**](AiBatchRead.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.AiAPI.GetAiDocument(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetAiDocumentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiDocumentRead**](AiDocumentRead.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.AiAPI.GetAiVideoJob(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiGetAiVideoJobRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiMediaJobRead**](AiMediaJobRead.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	limit := "limit_example" // string | How many rows to return, newest first. Clamped to 200; anything unparseable falls back to 50. (optional)
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ListAiDocuments(ctx).Limit(limit).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListAiDocumentsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **string** | How many rows to return, newest first. Clamped to 200; anything unparseable falls back to 50. |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**[]AiDocument**](AiDocument.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	workspaceId := "workspaceId_example" // string |
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ListHlixCodeModels(ctx, workspaceId).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiListHlixCodeModelsRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**HlixCodeModels**](HlixCodeModels.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var parseDocument openapiclient.ParseDocument
	if err := json.Unmarshal([]byte("{\"source\":{\"kind\":\"url\",\"url\":\"https://example.com\"}}"), &parseDocument); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ParseAiDocument(ctx).ParseDocument(parseDocument).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiParseAiDocumentRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **parseDocument** | [**ParseDocument**](ParseDocument.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiDocumentParsed**](AiDocumentParsed.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	resp, r, err := apiClient.AiAPI.PollAiBatch(ctx, id).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiPollAiBatchRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiBatchPoll**](AiBatchPoll.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var reviewMediaJob openapiclient.ReviewMediaJob
	if err := json.Unmarshal([]byte("{\"state\":\"approved\"}"), &reviewMediaJob); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.ReviewAiVideoJob(ctx, id).ReviewMediaJob(reviewMediaJob).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiReviewAiVideoJobRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reviewMediaJob** | [**ReviewMediaJob**](ReviewMediaJob.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiMediaJobRead**](AiMediaJobRead.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var submitBatch openapiclient.SubmitBatch
	if err := json.Unmarshal([]byte("{\"endpoint\":\"/v1/chat/completions\",\"idempotencyKey\":\"text\",\"items\":[{\"body\":{\"key\":\"value\"},\"customId\":\"text\"}],\"kind\":\"backfill\",\"model\":\"claude-fable-5-1\",\"policy\":{\"sensitiveDataApproved\":true}}"), &submitBatch); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.SubmitAiBatch(ctx).SubmitBatch(submitBatch).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSubmitAiBatchRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **submitBatch** | [**SubmitBatch**](SubmitBatch.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiBatchAccepted**](AiBatchAccepted.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var synthesizeSpeech openapiclient.SynthesizeSpeech
	if err := json.Unmarshal([]byte("{\"text\":\"text\",\"voice\":\"text\"}"), &synthesizeSpeech); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.SynthesizeAiSpeech(ctx).SynthesizeSpeech(synthesizeSpeech).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiSynthesizeAiSpeechRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **synthesizeSpeech** | [**SynthesizeSpeech**](SynthesizeSpeech.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiSpeech**](AiSpeech.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

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
	var transcribeAudio openapiclient.TranscribeAudio
	if err := json.Unmarshal([]byte("{\"artifactKey\":\"text\",\"format\":\"wav\"}"), &transcribeAudio); err != nil {
		panic(err)
	}
	xOrganizationId := os.Getenv("HLIX_WORKSPACE_ID") // string | The workspace (organization) to act in. Omitted, the session's active organization is used. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiAPI.TranscribeAiAudio(ctx).TranscribeAudio(transcribeAudio).XOrganizationId(xOrganizationId).Execute()
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

Pass optional parameters through the `apiTranscribeAiAudioRequest` request builder.


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **transcribeAudio** | [**TranscribeAudio**](TranscribeAudio.md) |  |
 **xOrganizationId** | **string** | The workspace (organization) to act in. Omitted, the session&#39;s active organization is used. |

### Return type

[**AiTextResult**](AiTextResult.md)

### Authorization

[apiKey](../README.md#apikey), [sessionCookie](../README.md#sessioncookie)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

