# AgentUsageRollupByRoleInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentKind** | **string** |  |
**CostMicros** | **NullableInt64** |  |
**Count** | **int32** |  |
**IncompleteUsageRuns** | Pointer to **int32** |  | [optional]
**TokensIn** | **int32** |  |
**TokensOut** | **int32** |  |

## Methods

### NewAgentUsageRollupByRoleInner

`func NewAgentUsageRollupByRoleInner(agentKind string, costMicros NullableInt64, count int32, tokensIn int32, tokensOut int32, ) *AgentUsageRollupByRoleInner`

NewAgentUsageRollupByRoleInner instantiates a new AgentUsageRollupByRoleInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgentUsageRollupByRoleInnerWithDefaults

`func NewAgentUsageRollupByRoleInnerWithDefaults() *AgentUsageRollupByRoleInner`

NewAgentUsageRollupByRoleInnerWithDefaults instantiates a new AgentUsageRollupByRoleInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentKind

`func (o *AgentUsageRollupByRoleInner) GetAgentKind() string`

GetAgentKind returns the AgentKind field if non-nil, zero value otherwise.

### GetAgentKindOk

`func (o *AgentUsageRollupByRoleInner) GetAgentKindOk() (*string, bool)`

GetAgentKindOk returns a tuple with the AgentKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentKind

`func (o *AgentUsageRollupByRoleInner) SetAgentKind(v string)`

SetAgentKind sets AgentKind field to given value.


### GetCostMicros

`func (o *AgentUsageRollupByRoleInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AgentUsageRollupByRoleInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AgentUsageRollupByRoleInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AgentUsageRollupByRoleInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AgentUsageRollupByRoleInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCount

`func (o *AgentUsageRollupByRoleInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *AgentUsageRollupByRoleInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *AgentUsageRollupByRoleInner) SetCount(v int32)`

SetCount sets Count field to given value.


### GetIncompleteUsageRuns

`func (o *AgentUsageRollupByRoleInner) GetIncompleteUsageRuns() int32`

GetIncompleteUsageRuns returns the IncompleteUsageRuns field if non-nil, zero value otherwise.

### GetIncompleteUsageRunsOk

`func (o *AgentUsageRollupByRoleInner) GetIncompleteUsageRunsOk() (*int32, bool)`

GetIncompleteUsageRunsOk returns a tuple with the IncompleteUsageRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompleteUsageRuns

`func (o *AgentUsageRollupByRoleInner) SetIncompleteUsageRuns(v int32)`

SetIncompleteUsageRuns sets IncompleteUsageRuns field to given value.

### HasIncompleteUsageRuns

`func (o *AgentUsageRollupByRoleInner) HasIncompleteUsageRuns() bool`

HasIncompleteUsageRuns returns a boolean if a field has been set.

### GetTokensIn

`func (o *AgentUsageRollupByRoleInner) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AgentUsageRollupByRoleInner) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AgentUsageRollupByRoleInner) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### GetTokensOut

`func (o *AgentUsageRollupByRoleInner) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AgentUsageRollupByRoleInner) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AgentUsageRollupByRoleInner) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


