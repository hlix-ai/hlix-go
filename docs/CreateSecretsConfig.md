# CreateSecretsConfig

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [CreateSecretsConfigOneOf](CreateSecretsConfigOneOf.md) | `config`, `label`, `provider` |
| [CreateSecretsConfigOneOf1](CreateSecretsConfigOneOf1.md) | `config`, `label`, `provider` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `CreateSecretsConfigOneOf` | `*CreateSecretsConfigOneOf` |
| `CreateSecretsConfigOneOf1` | `*CreateSecretsConfigOneOf1` |

## Methods

### CreateSecretsConfigOneOfAsCreateSecretsConfig

`func CreateSecretsConfigOneOfAsCreateSecretsConfig(v *CreateSecretsConfigOneOf) CreateSecretsConfig`

### CreateSecretsConfigOneOf1AsCreateSecretsConfig

`func CreateSecretsConfigOneOf1AsCreateSecretsConfig(v *CreateSecretsConfigOneOf1) CreateSecretsConfig`

### UnmarshalJSON

`func (dst *CreateSecretsConfig) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateSecretsConfig) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *CreateSecretsConfig) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj CreateSecretsConfig) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


