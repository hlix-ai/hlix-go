# WorkspaceFsResultResult

This model accepts at least one of the alternatives below. JSON null is also accepted. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| `boolean` | — |
| [WorkspaceFsResultResultAnyOf](WorkspaceFsResultResultAnyOf.md) | `content`, `encoding` |
| `array` | — |
| [WorkspaceFsResultResultAnyOf1](WorkspaceFsResultResultAnyOf1.md) | `createdAt`, `modifiedAt`, `name`, `path`, `size`, `type` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `WorkspaceFsResultResultAnyOf` | `*WorkspaceFsResultResultAnyOf` |
| `WorkspaceFsResultResultAnyOf1` | `*WorkspaceFsResultResultAnyOf1` |
| `ArrayOfWorkspaceFsResultResultAnyOf1Inner` | `*[]WorkspaceFsResultResultAnyOf1Inner` |
| `Bool` | `*bool` |

## Methods

### UnmarshalJSON

`func (dst *WorkspaceFsResultResult) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src WorkspaceFsResultResult) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


