# CreateMcpServerUrl

This model accepts at least one of the alternatives below. JSON null is also accepted. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| `string` | — |
| `string` | — |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `String` | `*string` |

## Methods

### UnmarshalJSON

`func (dst *CreateMcpServerUrl) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateMcpServerUrl) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


