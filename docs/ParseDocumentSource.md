# ParseDocumentSource

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ParseDocumentSourceAnyOf](ParseDocumentSourceAnyOf.md) | `kind`, `url` |
| [ParseDocumentSourceAnyOf1](ParseDocumentSourceAnyOf1.md) | `key`, `kind` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `ParseDocumentSourceAnyOf` | `*ParseDocumentSourceAnyOf` |
| `ParseDocumentSourceAnyOf1` | `*ParseDocumentSourceAnyOf1` |

## Methods

### UnmarshalJSON

`func (dst *ParseDocumentSource) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src ParseDocumentSource) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


