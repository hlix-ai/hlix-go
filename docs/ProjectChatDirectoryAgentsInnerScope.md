# ProjectChatDirectoryAgentsInnerScope

This model accepts exactly one of the alternatives below. Required JSON properties apply to the selected alternative.

## Alternatives

| Alternative | Required JSON properties |
| --- | --- |
| [ProjectChatDirectoryAgentsInnerScopeOneOf](ProjectChatDirectoryAgentsInnerScopeOneOf.md) | `kind`, `projectId` |
| [ProjectChatDirectoryAgentsInnerScopeOneOf1](ProjectChatDirectoryAgentsInnerScopeOneOf1.md) | `cycleId`, `kind`, `projectId` |
| [ProjectChatDirectoryAgentsInnerScopeOneOf2](ProjectChatDirectoryAgentsInnerScopeOneOf2.md) | `kind`, `projectId`, `taskId` |
| [ProjectChatDirectoryAgentsInnerScopeOneOf3](ProjectChatDirectoryAgentsInnerScopeOneOf3.md) | `agentId`, `kind`, `projectId` |

Construct a branch model and assign its pointer field below, or use a wrapping function when one is listed. Use `encoding/json` for JSON serialization.

## Go representation

| Field | Go type |
| --- | --- |
| `ProjectChatDirectoryAgentsInnerScopeOneOf` | `*ProjectChatDirectoryAgentsInnerScopeOneOf` |
| `ProjectChatDirectoryAgentsInnerScopeOneOf1` | `*ProjectChatDirectoryAgentsInnerScopeOneOf1` |
| `ProjectChatDirectoryAgentsInnerScopeOneOf2` | `*ProjectChatDirectoryAgentsInnerScopeOneOf2` |
| `ProjectChatDirectoryAgentsInnerScopeOneOf3` | `*ProjectChatDirectoryAgentsInnerScopeOneOf3` |

## Methods

### ProjectChatDirectoryAgentsInnerScopeOneOfAsProjectChatDirectoryAgentsInnerScope

`func ProjectChatDirectoryAgentsInnerScopeOneOfAsProjectChatDirectoryAgentsInnerScope(v *ProjectChatDirectoryAgentsInnerScopeOneOf) ProjectChatDirectoryAgentsInnerScope`

### ProjectChatDirectoryAgentsInnerScopeOneOf1AsProjectChatDirectoryAgentsInnerScope

`func ProjectChatDirectoryAgentsInnerScopeOneOf1AsProjectChatDirectoryAgentsInnerScope(v *ProjectChatDirectoryAgentsInnerScopeOneOf1) ProjectChatDirectoryAgentsInnerScope`

### ProjectChatDirectoryAgentsInnerScopeOneOf2AsProjectChatDirectoryAgentsInnerScope

`func ProjectChatDirectoryAgentsInnerScopeOneOf2AsProjectChatDirectoryAgentsInnerScope(v *ProjectChatDirectoryAgentsInnerScopeOneOf2) ProjectChatDirectoryAgentsInnerScope`

### ProjectChatDirectoryAgentsInnerScopeOneOf3AsProjectChatDirectoryAgentsInnerScope

`func ProjectChatDirectoryAgentsInnerScopeOneOf3AsProjectChatDirectoryAgentsInnerScope(v *ProjectChatDirectoryAgentsInnerScopeOneOf3) ProjectChatDirectoryAgentsInnerScope`

### UnmarshalJSON

`func (dst *ProjectChatDirectoryAgentsInnerScope) UnmarshalJSON(data []byte) error`

### MarshalJSON

`func (src ProjectChatDirectoryAgentsInnerScope) MarshalJSON() ([]byte, error)`

### GetActualInstance

`func (obj *ProjectChatDirectoryAgentsInnerScope) GetActualInstance() (interface{})`

### GetActualInstanceValue

`func (obj ProjectChatDirectoryAgentsInnerScope) GetActualInstanceValue() (interface{})`

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


