# AgentUsageRollupByPromptKeyInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostMicros** | **NullableInt64** |  |
**Count** | **int32** |  |
**IncompleteUsageRuns** | Pointer to **int32** |  | [optional]
**PromptKey** | **NullableString** |  |
**TokensIn** | **int32** |  |
**TokensOut** | **int32** |  |

## Methods

### NewAgentUsageRollupByPromptKeyInner

`func NewAgentUsageRollupByPromptKeyInner(costMicros NullableInt64, count int32, promptKey NullableString, tokensIn int32, tokensOut int32, ) *AgentUsageRollupByPromptKeyInner`

NewAgentUsageRollupByPromptKeyInner instantiates a new AgentUsageRollupByPromptKeyInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgentUsageRollupByPromptKeyInnerWithDefaults

`func NewAgentUsageRollupByPromptKeyInnerWithDefaults() *AgentUsageRollupByPromptKeyInner`

NewAgentUsageRollupByPromptKeyInnerWithDefaults instantiates a new AgentUsageRollupByPromptKeyInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCostMicros

`func (o *AgentUsageRollupByPromptKeyInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AgentUsageRollupByPromptKeyInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AgentUsageRollupByPromptKeyInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AgentUsageRollupByPromptKeyInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AgentUsageRollupByPromptKeyInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCount

`func (o *AgentUsageRollupByPromptKeyInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *AgentUsageRollupByPromptKeyInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *AgentUsageRollupByPromptKeyInner) SetCount(v int32)`

SetCount sets Count field to given value.


### GetIncompleteUsageRuns

`func (o *AgentUsageRollupByPromptKeyInner) GetIncompleteUsageRuns() int32`

GetIncompleteUsageRuns returns the IncompleteUsageRuns field if non-nil, zero value otherwise.

### GetIncompleteUsageRunsOk

`func (o *AgentUsageRollupByPromptKeyInner) GetIncompleteUsageRunsOk() (*int32, bool)`

GetIncompleteUsageRunsOk returns a tuple with the IncompleteUsageRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompleteUsageRuns

`func (o *AgentUsageRollupByPromptKeyInner) SetIncompleteUsageRuns(v int32)`

SetIncompleteUsageRuns sets IncompleteUsageRuns field to given value.

### HasIncompleteUsageRuns

`func (o *AgentUsageRollupByPromptKeyInner) HasIncompleteUsageRuns() bool`

HasIncompleteUsageRuns returns a boolean if a field has been set.

### GetPromptKey

`func (o *AgentUsageRollupByPromptKeyInner) GetPromptKey() string`

GetPromptKey returns the PromptKey field if non-nil, zero value otherwise.

### GetPromptKeyOk

`func (o *AgentUsageRollupByPromptKeyInner) GetPromptKeyOk() (*string, bool)`

GetPromptKeyOk returns a tuple with the PromptKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptKey

`func (o *AgentUsageRollupByPromptKeyInner) SetPromptKey(v string)`

SetPromptKey sets PromptKey field to given value.


### SetPromptKeyNil

`func (o *AgentUsageRollupByPromptKeyInner) SetPromptKeyNil(b bool)`

 SetPromptKeyNil sets the value for PromptKey to be an explicit nil

### UnsetPromptKey
`func (o *AgentUsageRollupByPromptKeyInner) UnsetPromptKey()`

UnsetPromptKey ensures that no value is present for PromptKey, not even an explicit nil
### GetTokensIn

`func (o *AgentUsageRollupByPromptKeyInner) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AgentUsageRollupByPromptKeyInner) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AgentUsageRollupByPromptKeyInner) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### GetTokensOut

`func (o *AgentUsageRollupByPromptKeyInner) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AgentUsageRollupByPromptKeyInner) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AgentUsageRollupByPromptKeyInner) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


