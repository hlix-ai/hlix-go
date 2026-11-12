# CreateProjectRuntimeDeployment

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [CreateProjectRuntimeDeploymentOneOf](CreateProjectRuntimeDeploymentOneOf.md) | `buildCommand`, `kind`, `outDir`, `repoId` |
| [CreateProjectRuntimeDeploymentOneOf1](CreateProjectRuntimeDeploymentOneOf1.md) | `kind`, `repoId`, `startCommand` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `CreateProjectRuntimeDeploymentOneOf` | `*CreateProjectRuntimeDeploymentOneOf` |
| `CreateProjectRuntimeDeploymentOneOf1` | `*CreateProjectRuntimeDeploymentOneOf1` |

## Methods

### CreateProjectRuntimeDeploymentOneOfAsCreateProjectRuntimeDeployment

`func CreateProjectRuntimeDeploymentOneOfAsCreateProjectRuntimeDeployment(v *CreateProjectRuntimeDeploymentOneOf) CreateProjectRuntimeDeployment`

### CreateProjectRuntimeDeploymentOneOf1AsCreateProjectRuntimeDeployment

`func CreateProjectRuntimeDeploymentOneOf1AsCreateProjectRuntimeDeployment(v *CreateProjectRuntimeDeploymentOneOf1) CreateProjectRuntimeDeployment`

### UnmarshalJSON

`func (dst *CreateProjectRuntimeDeployment) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src CreateProjectRuntimeDeployment) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *CreateProjectRuntimeDeployment) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj CreateProjectRuntimeDeployment) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


