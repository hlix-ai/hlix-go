# InitialProposalDetailResponseRevisionContentBlocksInner

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [InitialProposalDetailResponseRevisionContentBlocksInnerOneOf](InitialProposalDetailResponseRevisionContentBlocksInnerOneOf.md) | `body`, `id`, `kind`, `title` |
| [InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1](InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1.md) | `id`, `items`, `kind`, `title` |
| [InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2](InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2.md) | `edges`, `id`, `kind`, `nodes`, `summary`, `title` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `InitialProposalDetailResponseRevisionContentBlocksInnerOneOf` | `*InitialProposalDetailResponseRevisionContentBlocksInnerOneOf` |
| `InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1` | `*InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1` |
| `InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2` | `*InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2` |

## Methods

### InitialProposalDetailResponseRevisionContentBlocksInnerOneOfAsInitialProposalDetailResponseRevisionContentBlocksInner

`func InitialProposalDetailResponseRevisionContentBlocksInnerOneOfAsInitialProposalDetailResponseRevisionContentBlocksInner(v *InitialProposalDetailResponseRevisionContentBlocksInnerOneOf) InitialProposalDetailResponseRevisionContentBlocksInner`

### InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1AsInitialProposalDetailResponseRevisionContentBlocksInner

`func InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1AsInitialProposalDetailResponseRevisionContentBlocksInner(v *InitialProposalDetailResponseRevisionContentBlocksInnerOneOf1) InitialProposalDetailResponseRevisionContentBlocksInner`

### InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2AsInitialProposalDetailResponseRevisionContentBlocksInner

`func InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2AsInitialProposalDetailResponseRevisionContentBlocksInner(v *InitialProposalDetailResponseRevisionContentBlocksInnerOneOf2) InitialProposalDetailResponseRevisionContentBlocksInner`

### UnmarshalJSON

`func (dst *InitialProposalDetailResponseRevisionContentBlocksInner) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src InitialProposalDetailResponseRevisionContentBlocksInner) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *InitialProposalDetailResponseRevisionContentBlocksInner) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj InitialProposalDetailResponseRevisionContentBlocksInner) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


