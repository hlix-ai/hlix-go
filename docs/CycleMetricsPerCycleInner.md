# CycleMetricsPerCycleInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentRuns** | **int32** |  |
**CloudMachineStarts** | **int32** |  |
**CoderRestarts** | **int32** |  |
**CostMicros** | **NullableInt64** |  |
**CycleId** | **string** |  |
**ModelCalls** | **int32** |  |
**StageTimes** | [**[]CycleMetricsPerCycleInnerStageTimesInner**](CycleMetricsPerCycleInnerStageTimesInner.md) |  |
**Status** | **string** |  |
**Title** | **string** |  |
**TokensIn** | **float32** |  |
**TokensOut** | **float32** |  |

## Methods

### NewCycleMetricsPerCycleInner

`func NewCycleMetricsPerCycleInner(agentRuns int32, cloudMachineStarts int32, coderRestarts int32, costMicros NullableInt64, cycleId string, modelCalls int32, stageTimes []CycleMetricsPerCycleInnerStageTimesInner, status string, title string, tokensIn float32, tokensOut float32, ) *CycleMetricsPerCycleInner`

NewCycleMetricsPerCycleInner instantiates a new CycleMetricsPerCycleInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleMetricsPerCycleInnerWithDefaults

`func NewCycleMetricsPerCycleInnerWithDefaults() *CycleMetricsPerCycleInner`

NewCycleMetricsPerCycleInnerWithDefaults instantiates a new CycleMetricsPerCycleInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentRuns

`func (o *CycleMetricsPerCycleInner) GetAgentRuns() int32`

GetAgentRuns returns the AgentRuns field if non-nil, zero value otherwise.

### GetAgentRunsOk

`func (o *CycleMetricsPerCycleInner) GetAgentRunsOk() (*int32, bool)`

GetAgentRunsOk returns a tuple with the AgentRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentRuns

`func (o *CycleMetricsPerCycleInner) SetAgentRuns(v int32)`

SetAgentRuns sets AgentRuns field to given value.


### GetCloudMachineStarts

`func (o *CycleMetricsPerCycleInner) GetCloudMachineStarts() int32`

GetCloudMachineStarts returns the CloudMachineStarts field if non-nil, zero value otherwise.

### GetCloudMachineStartsOk

`func (o *CycleMetricsPerCycleInner) GetCloudMachineStartsOk() (*int32, bool)`

GetCloudMachineStartsOk returns a tuple with the CloudMachineStarts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudMachineStarts

`func (o *CycleMetricsPerCycleInner) SetCloudMachineStarts(v int32)`

SetCloudMachineStarts sets CloudMachineStarts field to given value.


### GetCoderRestarts

`func (o *CycleMetricsPerCycleInner) GetCoderRestarts() int32`

GetCoderRestarts returns the CoderRestarts field if non-nil, zero value otherwise.

### GetCoderRestartsOk

`func (o *CycleMetricsPerCycleInner) GetCoderRestartsOk() (*int32, bool)`

GetCoderRestartsOk returns a tuple with the CoderRestarts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoderRestarts

`func (o *CycleMetricsPerCycleInner) SetCoderRestarts(v int32)`

SetCoderRestarts sets CoderRestarts field to given value.


### GetCostMicros

`func (o *CycleMetricsPerCycleInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *CycleMetricsPerCycleInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *CycleMetricsPerCycleInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *CycleMetricsPerCycleInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *CycleMetricsPerCycleInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCycleId

`func (o *CycleMetricsPerCycleInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *CycleMetricsPerCycleInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *CycleMetricsPerCycleInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetModelCalls

`func (o *CycleMetricsPerCycleInner) GetModelCalls() int32`

GetModelCalls returns the ModelCalls field if non-nil, zero value otherwise.

### GetModelCallsOk

`func (o *CycleMetricsPerCycleInner) GetModelCallsOk() (*int32, bool)`

GetModelCallsOk returns a tuple with the ModelCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelCalls

`func (o *CycleMetricsPerCycleInner) SetModelCalls(v int32)`

SetModelCalls sets ModelCalls field to given value.


### GetStageTimes

`func (o *CycleMetricsPerCycleInner) GetStageTimes() []CycleMetricsPerCycleInnerStageTimesInner`

GetStageTimes returns the StageTimes field if non-nil, zero value otherwise.

### GetStageTimesOk

`func (o *CycleMetricsPerCycleInner) GetStageTimesOk() (*[]CycleMetricsPerCycleInnerStageTimesInner, bool)`

GetStageTimesOk returns a tuple with the StageTimes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageTimes

`func (o *CycleMetricsPerCycleInner) SetStageTimes(v []CycleMetricsPerCycleInnerStageTimesInner)`

SetStageTimes sets StageTimes field to given value.


### GetStatus

`func (o *CycleMetricsPerCycleInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleMetricsPerCycleInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleMetricsPerCycleInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *CycleMetricsPerCycleInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CycleMetricsPerCycleInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CycleMetricsPerCycleInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTokensIn

`func (o *CycleMetricsPerCycleInner) GetTokensIn() float32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *CycleMetricsPerCycleInner) GetTokensInOk() (*float32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *CycleMetricsPerCycleInner) SetTokensIn(v float32)`

SetTokensIn sets TokensIn field to given value.


### GetTokensOut

`func (o *CycleMetricsPerCycleInner) GetTokensOut() float32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *CycleMetricsPerCycleInner) GetTokensOutOk() (*float32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *CycleMetricsPerCycleInner) SetTokensOut(v float32)`

SetTokensOut sets TokensOut field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


