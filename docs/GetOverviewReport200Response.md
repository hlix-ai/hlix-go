# GetOverviewReport200Response

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [AgencyOverviewReport](AgencyOverviewReport.md) | `attention`, `billing`, `customers`, `generatedAt`, `period`, `projects`, `scope`, `summary`, `usage` |
| [ClientOverviewReport](ClientOverviewReport.md) | `generatedAt`, `invoices`, `projects`, `recentActivity`, `scope`, `summary` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `AgencyOverviewReport` | `*AgencyOverviewReport` |
| `ClientOverviewReport` | `*ClientOverviewReport` |

## Methods

### UnmarshalJSON

`func (dst *GetOverviewReport200Response) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src GetOverviewReport200Response) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


