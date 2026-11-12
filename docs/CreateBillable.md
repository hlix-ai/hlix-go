# CreateBillable

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [CreateBillableOneOf](CreateBillableOneOf.md) | `clientAccountId`, `currency`, `description`, `quantity`, `source`, `unit`, `unitPriceMicros` |
| [CreateBillableOneOf1](CreateBillableOneOf1.md) | `currency`, `cycleId`, `description`, `quantity`, `source`, `unit`, `unitPriceMicros` |
| [CreateBillableOneOf2](CreateBillableOneOf2.md) | `agentRunId`, `currency`, `description`, `source` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `CreateBillableOneOf` | `*CreateBillableOneOf` |
| `CreateBillableOneOf1` | `*CreateBillableOneOf1` |
| `CreateBillableOneOf2` | `*CreateBillableOneOf2` |

## Methods

### CreateBillableOneOfAsCreateBillable

`func CreateBillableOneOfAsCreateBillable(v *CreateBillableOneOf) CreateBillable`

### CreateBillableOneOf1AsCreateBillable

`func CreateBillableOneOf1AsCreateBillable(v *CreateBillableOneOf1) CreateBillable`

### CreateBillableOneOf2AsCreateBillable

`func CreateBillableOneOf2AsCreateBillable(v *CreateBillableOneOf2) CreateBillable`

### UnmarshalJSON

`func (dst *CreateBillable) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateBillable) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *CreateBillable) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj CreateBillable) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


