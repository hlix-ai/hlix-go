# CrmBoard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Forecast** | [**[]CrmBoardForecastInner**](CrmBoardForecastInner.md) |  |
**Funnel** | [**CrmBoardFunnel**](CrmBoardFunnel.md) |  |
**Pipeline** | [**CrmBoardPipeline**](CrmBoardPipeline.md) |  |
**Stages** | [**[]CrmBoardStagesInner**](CrmBoardStagesInner.md) |  |

## Methods

### NewCrmBoard

`func NewCrmBoard(forecast []CrmBoardForecastInner, funnel CrmBoardFunnel, pipeline CrmBoardPipeline, stages []CrmBoardStagesInner, ) *CrmBoard`

NewCrmBoard instantiates a new CrmBoard object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCrmBoardWithDefaults

`func NewCrmBoardWithDefaults() *CrmBoard`

NewCrmBoardWithDefaults instantiates a new CrmBoard object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetForecast

`func (o *CrmBoard) GetForecast() []CrmBoardForecastInner`

GetForecast returns the Forecast field if non-nil, zero value otherwise.

### GetForecastOk

`func (o *CrmBoard) GetForecastOk() (*[]CrmBoardForecastInner, bool)`

GetForecastOk returns a tuple with the Forecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecast

`func (o *CrmBoard) SetForecast(v []CrmBoardForecastInner)`

SetForecast sets Forecast field to given value.


### GetFunnel

`func (o *CrmBoard) GetFunnel() CrmBoardFunnel`

GetFunnel returns the Funnel field if non-nil, zero value otherwise.

### GetFunnelOk

`func (o *CrmBoard) GetFunnelOk() (*CrmBoardFunnel, bool)`

GetFunnelOk returns a tuple with the Funnel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunnel

`func (o *CrmBoard) SetFunnel(v CrmBoardFunnel)`

SetFunnel sets Funnel field to given value.


### GetPipeline

`func (o *CrmBoard) GetPipeline() CrmBoardPipeline`

GetPipeline returns the Pipeline field if non-nil, zero value otherwise.

### GetPipelineOk

`func (o *CrmBoard) GetPipelineOk() (*CrmBoardPipeline, bool)`

GetPipelineOk returns a tuple with the Pipeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipeline

`func (o *CrmBoard) SetPipeline(v CrmBoardPipeline)`

SetPipeline sets Pipeline field to given value.


### GetStages

`func (o *CrmBoard) GetStages() []CrmBoardStagesInner`

GetStages returns the Stages field if non-nil, zero value otherwise.

### GetStagesOk

`func (o *CrmBoard) GetStagesOk() (*[]CrmBoardStagesInner, bool)`

GetStagesOk returns a tuple with the Stages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStages

`func (o *CrmBoard) SetStages(v []CrmBoardStagesInner)`

SetStages sets Stages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


