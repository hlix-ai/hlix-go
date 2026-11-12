# CreateHlixCodeChatCompletion403Response

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ApiError](ApiError.md) | `error` |
| [OpenAiError](OpenAiError.md) | `error` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `ApiError` | `*ApiError` |
| `OpenAiError` | `*OpenAiError` |

## Methods

### UnmarshalJSON

`func (dst *CreateHlixCodeChatCompletion403Response) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateHlixCodeChatCompletion403Response) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


