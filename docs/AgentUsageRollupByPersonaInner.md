# AgentUsageRollupByPersonaInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostMicros** | **NullableInt64** |  | 
**Count** | **int32** |  | 
**IncompleteUsageRuns** | Pointer to **int32** |  | [optional] 
**Persona** | **NullableString** |  | 
**TokensIn** | **int32** |  | 
**TokensOut** | **int32** |  | 

## Methods

### NewAgentUsageRollupByPersonaInner

`func NewAgentUsageRollupByPersonaInner(costMicros NullableInt64, count int32, persona NullableString, tokensIn int32, tokensOut int32, ) *AgentUsageRollupByPersonaInner`

NewAgentUsageRollupByPersonaInner instantiates a new AgentUsageRollupByPersonaInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentUsageRollupByPersonaInnerWithDefaults

`func NewAgentUsageRollupByPersonaInnerWithDefaults() *AgentUsageRollupByPersonaInner`

NewAgentUsageRollupByPersonaInnerWithDefaults instantiates a new AgentUsageRollupByPersonaInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCostMicros

`func (o *AgentUsageRollupByPersonaInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AgentUsageRollupByPersonaInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AgentUsageRollupByPersonaInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AgentUsageRollupByPersonaInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AgentUsageRollupByPersonaInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCount

`func (o *AgentUsageRollupByPersonaInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *AgentUsageRollupByPersonaInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *AgentUsageRollupByPersonaInner) SetCount(v int32)`

SetCount sets Count field to given value.


### GetIncompleteUsageRuns

`func (o *AgentUsageRollupByPersonaInner) GetIncompleteUsageRuns() int32`

GetIncompleteUsageRuns returns the IncompleteUsageRuns field if non-nil, zero value otherwise.

### GetIncompleteUsageRunsOk

`func (o *AgentUsageRollupByPersonaInner) GetIncompleteUsageRunsOk() (*int32, bool)`

GetIncompleteUsageRunsOk returns a tuple with the IncompleteUsageRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompleteUsageRuns

`func (o *AgentUsageRollupByPersonaInner) SetIncompleteUsageRuns(v int32)`

SetIncompleteUsageRuns sets IncompleteUsageRuns field to given value.

### HasIncompleteUsageRuns

`func (o *AgentUsageRollupByPersonaInner) HasIncompleteUsageRuns() bool`

HasIncompleteUsageRuns returns a boolean if a field has been set.

### GetPersona

`func (o *AgentUsageRollupByPersonaInner) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *AgentUsageRollupByPersonaInner) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *AgentUsageRollupByPersonaInner) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *AgentUsageRollupByPersonaInner) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *AgentUsageRollupByPersonaInner) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetTokensIn

`func (o *AgentUsageRollupByPersonaInner) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AgentUsageRollupByPersonaInner) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AgentUsageRollupByPersonaInner) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### GetTokensOut

`func (o *AgentUsageRollupByPersonaInner) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AgentUsageRollupByPersonaInner) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AgentUsageRollupByPersonaInner) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


