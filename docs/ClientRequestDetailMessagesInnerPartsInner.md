# ClientRequestDetailMessagesInnerPartsInner

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ClientRequestDetailMessagesInnerPartsInnerOneOf](ClientRequestDetailMessagesInnerPartsInnerOneOf.md) | `text`, `type` |
| [ClientRequestDetailMessagesInnerPartsInnerOneOf1](ClientRequestDetailMessagesInnerPartsInnerOneOf1.md) | `text`, `type` |
| [ClientRequestDetailMessagesInnerPartsInnerOneOf2](ClientRequestDetailMessagesInnerPartsInnerOneOf2.md) | `producer`, `spec`, `type` |
| [ClientRequestDetailMessagesInnerPartsInnerOneOf3](ClientRequestDetailMessagesInnerPartsInnerOneOf3.md) | `state`, `toolCallId`, `toolName`, `type` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `ClientRequestDetailMessagesInnerPartsInnerOneOf` | `*ClientRequestDetailMessagesInnerPartsInnerOneOf` |
| `ClientRequestDetailMessagesInnerPartsInnerOneOf1` | `*ClientRequestDetailMessagesInnerPartsInnerOneOf1` |
| `ClientRequestDetailMessagesInnerPartsInnerOneOf2` | `*ClientRequestDetailMessagesInnerPartsInnerOneOf2` |
| `ClientRequestDetailMessagesInnerPartsInnerOneOf3` | `*ClientRequestDetailMessagesInnerPartsInnerOneOf3` |

## Methods

### ClientRequestDetailMessagesInnerPartsInnerOneOfAsClientRequestDetailMessagesInnerPartsInner

`func ClientRequestDetailMessagesInnerPartsInnerOneOfAsClientRequestDetailMessagesInnerPartsInner(v *ClientRequestDetailMessagesInnerPartsInnerOneOf) ClientRequestDetailMessagesInnerPartsInner`

### ClientRequestDetailMessagesInnerPartsInnerOneOf1AsClientRequestDetailMessagesInnerPartsInner

`func ClientRequestDetailMessagesInnerPartsInnerOneOf1AsClientRequestDetailMessagesInnerPartsInner(v *ClientRequestDetailMessagesInnerPartsInnerOneOf1) ClientRequestDetailMessagesInnerPartsInner`

### ClientRequestDetailMessagesInnerPartsInnerOneOf2AsClientRequestDetailMessagesInnerPartsInner

`func ClientRequestDetailMessagesInnerPartsInnerOneOf2AsClientRequestDetailMessagesInnerPartsInner(v *ClientRequestDetailMessagesInnerPartsInnerOneOf2) ClientRequestDetailMessagesInnerPartsInner`

### ClientRequestDetailMessagesInnerPartsInnerOneOf3AsClientRequestDetailMessagesInnerPartsInner

`func ClientRequestDetailMessagesInnerPartsInnerOneOf3AsClientRequestDetailMessagesInnerPartsInner(v *ClientRequestDetailMessagesInnerPartsInnerOneOf3) ClientRequestDetailMessagesInnerPartsInner`

### UnmarshalJSON

`func (dst *ClientRequestDetailMessagesInnerPartsInner) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src ClientRequestDetailMessagesInnerPartsInner) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *ClientRequestDetailMessagesInnerPartsInner) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj ClientRequestDetailMessagesInnerPartsInner) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


