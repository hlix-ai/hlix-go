# ClientBillableRateSnapshot

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ClientBillableRateSnapshotAnyOf](ClientBillableRateSnapshotAnyOf.md) | `basis`, `capturedAt`, `note` |
| [ClientBillableRateSnapshotAnyOf1](ClientBillableRateSnapshotAnyOf1.md) | `basis`, `capturedAt`, `costMicros`, `inputPricePerMTokensMicros`, `markupBps`, `modelIdentifier`, `outputPricePerMTokensMicros`, `tokensIn`, `tokensOut` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `ClientBillableRateSnapshotAnyOf` | `*ClientBillableRateSnapshotAnyOf` |
| `ClientBillableRateSnapshotAnyOf1` | `*ClientBillableRateSnapshotAnyOf1` |

## Methods

### UnmarshalJSON

`func (dst *ClientBillableRateSnapshot) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src ClientBillableRateSnapshot) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


