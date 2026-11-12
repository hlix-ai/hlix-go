# AnalyzeMediaSource

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [AnalyzeMediaSourceAnyOf](AnalyzeMediaSourceAnyOf.md) | `url` |
| [AnalyzeMediaSourceAnyOf1](AnalyzeMediaSourceAnyOf1.md) | `artifactKey` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `AnalyzeMediaSourceAnyOf` | `*AnalyzeMediaSourceAnyOf` |
| `AnalyzeMediaSourceAnyOf1` | `*AnalyzeMediaSourceAnyOf1` |

## Methods

### UnmarshalJSON

`func (dst *AnalyzeMediaSource) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src AnalyzeMediaSource) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


