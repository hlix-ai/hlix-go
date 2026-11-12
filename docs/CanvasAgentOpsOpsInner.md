# CanvasAgentOpsOpsInner

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [CanvasAgentOpsOpsInnerOneOf](CanvasAgentOpsOpsInnerOneOf.md) | `element`, `op` |
| [CanvasAgentOpsOpsInnerOneOf1](CanvasAgentOpsOpsInnerOneOf1.md) | `id`, `op`, `set` |
| [CanvasAgentOpsOpsInnerOneOf2](CanvasAgentOpsOpsInnerOneOf2.md) | `id`, `op` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `CanvasAgentOpsOpsInnerOneOf` | `*CanvasAgentOpsOpsInnerOneOf` |
| `CanvasAgentOpsOpsInnerOneOf1` | `*CanvasAgentOpsOpsInnerOneOf1` |
| `CanvasAgentOpsOpsInnerOneOf2` | `*CanvasAgentOpsOpsInnerOneOf2` |

## Methods

### CanvasAgentOpsOpsInnerOneOfAsCanvasAgentOpsOpsInner

`func CanvasAgentOpsOpsInnerOneOfAsCanvasAgentOpsOpsInner(v *CanvasAgentOpsOpsInnerOneOf) CanvasAgentOpsOpsInner`

### CanvasAgentOpsOpsInnerOneOf1AsCanvasAgentOpsOpsInner

`func CanvasAgentOpsOpsInnerOneOf1AsCanvasAgentOpsOpsInner(v *CanvasAgentOpsOpsInnerOneOf1) CanvasAgentOpsOpsInner`

### CanvasAgentOpsOpsInnerOneOf2AsCanvasAgentOpsOpsInner

`func CanvasAgentOpsOpsInnerOneOf2AsCanvasAgentOpsOpsInner(v *CanvasAgentOpsOpsInnerOneOf2) CanvasAgentOpsOpsInner`

### UnmarshalJSON

`func (dst *CanvasAgentOpsOpsInner) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CanvasAgentOpsOpsInner) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *CanvasAgentOpsOpsInner) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj CanvasAgentOpsOpsInner) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


