# CreateHlixCodeMessage403Response

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ApiError](ApiError.md) | `error` |
| [AnthropicError](AnthropicError.md) | `error`, `type` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `AnthropicError` | `*AnthropicError` |
| `ApiError` | `*ApiError` |

## Methods

### UnmarshalJSON

`func (dst *CreateHlixCodeMessage403Response) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateHlixCodeMessage403Response) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


