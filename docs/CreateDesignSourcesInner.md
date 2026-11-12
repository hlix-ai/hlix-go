# CreateDesignSourcesInner

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [CreateDesignSourcesInnerOneOf](CreateDesignSourcesInnerOneOf.md) | `kind`, `name`, `path` |
| [CreateDesignSourcesInnerOneOf1](CreateDesignSourcesInnerOneOf1.md) | `kind`, `provider`, `url` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `CreateDesignSourcesInnerOneOf` | `*CreateDesignSourcesInnerOneOf` |
| `CreateDesignSourcesInnerOneOf1` | `*CreateDesignSourcesInnerOneOf1` |

## Methods

### CreateDesignSourcesInnerOneOfAsCreateDesignSourcesInner

`func CreateDesignSourcesInnerOneOfAsCreateDesignSourcesInner(v *CreateDesignSourcesInnerOneOf) CreateDesignSourcesInner`

### CreateDesignSourcesInnerOneOf1AsCreateDesignSourcesInner

`func CreateDesignSourcesInnerOneOf1AsCreateDesignSourcesInner(v *CreateDesignSourcesInnerOneOf1) CreateDesignSourcesInner`

### UnmarshalJSON

`func (dst *CreateDesignSourcesInner) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateDesignSourcesInner) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *CreateDesignSourcesInner) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj CreateDesignSourcesInner) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


