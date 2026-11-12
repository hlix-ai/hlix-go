# CanvasAgentWriteOpsInner

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [CanvasAgentWriteOpsInnerOneOf](CanvasAgentWriteOpsInnerOneOf.md) | `element`, `op` |
| [CanvasAgentOpsOpsInnerOneOf1](CanvasAgentOpsOpsInnerOneOf1.md) | `id`, `op`, `set` |
| [CanvasAgentOpsOpsInnerOneOf2](CanvasAgentOpsOpsInnerOneOf2.md) | `id`, `op` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `CanvasAgentOpsOpsInnerOneOf1` | `*CanvasAgentOpsOpsInnerOneOf1` |
| `CanvasAgentOpsOpsInnerOneOf2` | `*CanvasAgentOpsOpsInnerOneOf2` |
| `CanvasAgentWriteOpsInnerOneOf` | `*CanvasAgentWriteOpsInnerOneOf` |

## Methods

### CanvasAgentOpsOpsInnerOneOf1AsCanvasAgentWriteOpsInner

`func CanvasAgentOpsOpsInnerOneOf1AsCanvasAgentWriteOpsInner(v *CanvasAgentOpsOpsInnerOneOf1) CanvasAgentWriteOpsInner`

### CanvasAgentOpsOpsInnerOneOf2AsCanvasAgentWriteOpsInner

`func CanvasAgentOpsOpsInnerOneOf2AsCanvasAgentWriteOpsInner(v *CanvasAgentOpsOpsInnerOneOf2) CanvasAgentWriteOpsInner`

### CanvasAgentWriteOpsInnerOneOfAsCanvasAgentWriteOpsInner

`func CanvasAgentWriteOpsInnerOneOfAsCanvasAgentWriteOpsInner(v *CanvasAgentWriteOpsInnerOneOf) CanvasAgentWriteOpsInner`

### UnmarshalJSON

`func (dst *CanvasAgentWriteOpsInner) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CanvasAgentWriteOpsInner) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *CanvasAgentWriteOpsInner) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj CanvasAgentWriteOpsInner) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


