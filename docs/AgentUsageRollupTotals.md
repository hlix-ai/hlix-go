# AgentUsageRollupTotals

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostMicros** | **NullableInt64** |  | 
**Count** | **int32** |  | 
**IncompleteUsageRuns** | Pointer to **int32** |  | [optional] 
**TokensIn** | **int32** |  | 
**TokensOut** | **int32** |  | 

## Methods

### NewAgentUsageRollupTotals

`func NewAgentUsageRollupTotals(costMicros NullableInt64, count int32, tokensIn int32, tokensOut int32, ) *AgentUsageRollupTotals`

NewAgentUsageRollupTotals instantiates a new AgentUsageRollupTotals object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentUsageRollupTotalsWithDefaults

`func NewAgentUsageRollupTotalsWithDefaults() *AgentUsageRollupTotals`

NewAgentUsageRollupTotalsWithDefaults instantiates a new AgentUsageRollupTotals object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCostMicros

`func (o *AgentUsageRollupTotals) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AgentUsageRollupTotals) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AgentUsageRollupTotals) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AgentUsageRollupTotals) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AgentUsageRollupTotals) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCount

`func (o *AgentUsageRollupTotals) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *AgentUsageRollupTotals) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *AgentUsageRollupTotals) SetCount(v int32)`

SetCount sets Count field to given value.


### GetIncompleteUsageRuns

`func (o *AgentUsageRollupTotals) GetIncompleteUsageRuns() int32`

GetIncompleteUsageRuns returns the IncompleteUsageRuns field if non-nil, zero value otherwise.

### GetIncompleteUsageRunsOk

`func (o *AgentUsageRollupTotals) GetIncompleteUsageRunsOk() (*int32, bool)`

GetIncompleteUsageRunsOk returns a tuple with the IncompleteUsageRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompleteUsageRuns

`func (o *AgentUsageRollupTotals) SetIncompleteUsageRuns(v int32)`

SetIncompleteUsageRuns sets IncompleteUsageRuns field to given value.

### HasIncompleteUsageRuns

`func (o *AgentUsageRollupTotals) HasIncompleteUsageRuns() bool`

HasIncompleteUsageRuns returns a boolean if a field has been set.

### GetTokensIn

`func (o *AgentUsageRollupTotals) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AgentUsageRollupTotals) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AgentUsageRollupTotals) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### GetTokensOut

`func (o *AgentUsageRollupTotals) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AgentUsageRollupTotals) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AgentUsageRollupTotals) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


