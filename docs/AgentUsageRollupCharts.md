# AgentUsageRollupCharts

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByModel** | [**[]AgentUsageRollupChartsByModelInner**](AgentUsageRollupChartsByModelInner.md) |  |
**Daily** | [**[]AgentUsageRollupChartsDailyInner**](AgentUsageRollupChartsDailyInner.md) |  |
**FirstRunAt** | **NullableString** |  |
**HasReportedTokens** | **bool** |  |
**TaskTokens** | **float32** |  |
**TasksExecuted** | **int32** |  |

## Methods

### NewAgentUsageRollupCharts

`func NewAgentUsageRollupCharts(byModel []AgentUsageRollupChartsByModelInner, daily []AgentUsageRollupChartsDailyInner, firstRunAt NullableString, hasReportedTokens bool, taskTokens float32, tasksExecuted int32, ) *AgentUsageRollupCharts`

NewAgentUsageRollupCharts instantiates a new AgentUsageRollupCharts object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgentUsageRollupChartsWithDefaults

`func NewAgentUsageRollupChartsWithDefaults() *AgentUsageRollupCharts`

NewAgentUsageRollupChartsWithDefaults instantiates a new AgentUsageRollupCharts object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetByModel

`func (o *AgentUsageRollupCharts) GetByModel() []AgentUsageRollupChartsByModelInner`

GetByModel returns the ByModel field if non-nil, zero value otherwise.

### GetByModelOk

`func (o *AgentUsageRollupCharts) GetByModelOk() (*[]AgentUsageRollupChartsByModelInner, bool)`

GetByModelOk returns a tuple with the ByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByModel

`func (o *AgentUsageRollupCharts) SetByModel(v []AgentUsageRollupChartsByModelInner)`

SetByModel sets ByModel field to given value.


### GetDaily

`func (o *AgentUsageRollupCharts) GetDaily() []AgentUsageRollupChartsDailyInner`

GetDaily returns the Daily field if non-nil, zero value otherwise.

### GetDailyOk

`func (o *AgentUsageRollupCharts) GetDailyOk() (*[]AgentUsageRollupChartsDailyInner, bool)`

GetDailyOk returns a tuple with the Daily field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaily

`func (o *AgentUsageRollupCharts) SetDaily(v []AgentUsageRollupChartsDailyInner)`

SetDaily sets Daily field to given value.


### GetFirstRunAt

`func (o *AgentUsageRollupCharts) GetFirstRunAt() string`

GetFirstRunAt returns the FirstRunAt field if non-nil, zero value otherwise.

### GetFirstRunAtOk

`func (o *AgentUsageRollupCharts) GetFirstRunAtOk() (*string, bool)`

GetFirstRunAtOk returns a tuple with the FirstRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstRunAt

`func (o *AgentUsageRollupCharts) SetFirstRunAt(v string)`

SetFirstRunAt sets FirstRunAt field to given value.


### SetFirstRunAtNil

`func (o *AgentUsageRollupCharts) SetFirstRunAtNil(b bool)`

 SetFirstRunAtNil sets the value for FirstRunAt to be an explicit nil

### UnsetFirstRunAt
`func (o *AgentUsageRollupCharts) UnsetFirstRunAt()`

UnsetFirstRunAt ensures that no value is present for FirstRunAt, not even an explicit nil
### GetHasReportedTokens

`func (o *AgentUsageRollupCharts) GetHasReportedTokens() bool`

GetHasReportedTokens returns the HasReportedTokens field if non-nil, zero value otherwise.

### GetHasReportedTokensOk

`func (o *AgentUsageRollupCharts) GetHasReportedTokensOk() (*bool, bool)`

GetHasReportedTokensOk returns a tuple with the HasReportedTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasReportedTokens

`func (o *AgentUsageRollupCharts) SetHasReportedTokens(v bool)`

SetHasReportedTokens sets HasReportedTokens field to given value.


### GetTaskTokens

`func (o *AgentUsageRollupCharts) GetTaskTokens() float32`

GetTaskTokens returns the TaskTokens field if non-nil, zero value otherwise.

### GetTaskTokensOk

`func (o *AgentUsageRollupCharts) GetTaskTokensOk() (*float32, bool)`

GetTaskTokensOk returns a tuple with the TaskTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskTokens

`func (o *AgentUsageRollupCharts) SetTaskTokens(v float32)`

SetTaskTokens sets TaskTokens field to given value.


### GetTasksExecuted

`func (o *AgentUsageRollupCharts) GetTasksExecuted() int32`

GetTasksExecuted returns the TasksExecuted field if non-nil, zero value otherwise.

### GetTasksExecutedOk

`func (o *AgentUsageRollupCharts) GetTasksExecutedOk() (*int32, bool)`

GetTasksExecutedOk returns a tuple with the TasksExecuted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasksExecuted

`func (o *AgentUsageRollupCharts) SetTasksExecuted(v int32)`

SetTasksExecuted sets TasksExecuted field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


