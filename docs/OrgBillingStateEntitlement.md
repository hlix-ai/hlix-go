# OrgBillingStateEntitlement

This model accepts at least one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [OrgBillingStateEntitlementAnyOf](OrgBillingStateEntitlementAnyOf.md) | `kind` |
| [OrgBillingStateEntitlementAnyOf1](OrgBillingStateEntitlementAnyOf1.md) | `kind`, `subscription` |
| [OrgBillingStateEntitlementAnyOf2](OrgBillingStateEntitlementAnyOf2.md) | `credit`, `kind`, `orgCapOnlyMillicents` |
| [OrgBillingStateEntitlementAnyOf3](OrgBillingStateEntitlementAnyOf3.md) | `kind`, `orgCapOnlyMillicents`, `reason` |
| [OrgBillingStateEntitlementAnyOf4](OrgBillingStateEntitlementAnyOf4.md) | `kind`, `reason` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `OrgBillingStateEntitlementAnyOf` | `*OrgBillingStateEntitlementAnyOf` |
| `OrgBillingStateEntitlementAnyOf1` | `*OrgBillingStateEntitlementAnyOf1` |
| `OrgBillingStateEntitlementAnyOf2` | `*OrgBillingStateEntitlementAnyOf2` |
| `OrgBillingStateEntitlementAnyOf3` | `*OrgBillingStateEntitlementAnyOf3` |
| `OrgBillingStateEntitlementAnyOf4` | `*OrgBillingStateEntitlementAnyOf4` |

## Methods

### UnmarshalJSON

`func (dst *OrgBillingStateEntitlement) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src OrgBillingStateEntitlement) MarshalJSON() ([]byte, error)`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


