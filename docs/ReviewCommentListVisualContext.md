# ReviewCommentListVisualContext

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ReviewCommentListVisualContextOneOf](ReviewCommentListVisualContextOneOf.md) | `enabled` |
| [ReviewCommentListVisualContextOneOf1](ReviewCommentListVisualContextOneOf1.md) | `enabled`, `reason`, `reasonCode` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `ReviewCommentListVisualContextOneOf` | `*ReviewCommentListVisualContextOneOf` |
| `ReviewCommentListVisualContextOneOf1` | `*ReviewCommentListVisualContextOneOf1` |

## Methods

### ReviewCommentListVisualContextOneOfAsReviewCommentListVisualContext

`func ReviewCommentListVisualContextOneOfAsReviewCommentListVisualContext(v *ReviewCommentListVisualContextOneOf) ReviewCommentListVisualContext`

### ReviewCommentListVisualContextOneOf1AsReviewCommentListVisualContext

`func ReviewCommentListVisualContextOneOf1AsReviewCommentListVisualContext(v *ReviewCommentListVisualContextOneOf1) ReviewCommentListVisualContext`

### UnmarshalJSON

`func (dst *ReviewCommentListVisualContext) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src ReviewCommentListVisualContext) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *ReviewCommentListVisualContext) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj ReviewCommentListVisualContext) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


