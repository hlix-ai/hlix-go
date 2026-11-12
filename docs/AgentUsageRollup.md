# AgentUsageRollup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByPromptKey** | [**[]AgentUsageRollupByPromptKeyInner**](AgentUsageRollupByPromptKeyInner.md) |  |
**ByRole** | [**[]AgentUsageRollupByRoleInner**](AgentUsageRollupByRoleInner.md) |  |
**Charts** | Pointer to [**AgentUsageRollupCharts**](AgentUsageRollupCharts.md) |  | [optional]
**Totals** | [**AgentUsageRollupTotals**](AgentUsageRollupTotals.md) |  |

## Methods

### NewAgentUsageRollup

`func NewAgentUsageRollup(byPromptKey []AgentUsageRollupByPromptKeyInner, byRole []AgentUsageRollupByRoleInner, totals AgentUsageRollupTotals, ) *AgentUsageRollup`

NewAgentUsageRollup instantiates a new AgentUsageRollup object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgentUsageRollupWithDefaults

`func NewAgentUsageRollupWithDefaults() *AgentUsageRollup`

NewAgentUsageRollupWithDefaults instantiates a new AgentUsageRollup object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetByPromptKey

`func (o *AgentUsageRollup) GetByPromptKey() []AgentUsageRollupByPromptKeyInner`

GetByPromptKey returns the ByPromptKey field if non-nil, zero value otherwise.

### GetByPromptKeyOk

`func (o *AgentUsageRollup) GetByPromptKeyOk() (*[]AgentUsageRollupByPromptKeyInner, bool)`

GetByPromptKeyOk returns a tuple with the ByPromptKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByPromptKey

`func (o *AgentUsageRollup) SetByPromptKey(v []AgentUsageRollupByPromptKeyInner)`

SetByPromptKey sets ByPromptKey field to given value.


### GetByRole

`func (o *AgentUsageRollup) GetByRole() []AgentUsageRollupByRoleInner`

GetByRole returns the ByRole field if non-nil, zero value otherwise.

### GetByRoleOk

`func (o *AgentUsageRollup) GetByRoleOk() (*[]AgentUsageRollupByRoleInner, bool)`

GetByRoleOk returns a tuple with the ByRole field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByRole

`func (o *AgentUsageRollup) SetByRole(v []AgentUsageRollupByRoleInner)`

SetByRole sets ByRole field to given value.


### GetCharts

`func (o *AgentUsageRollup) GetCharts() AgentUsageRollupCharts`

GetCharts returns the Charts field if non-nil, zero value otherwise.

### GetChartsOk

`func (o *AgentUsageRollup) GetChartsOk() (*AgentUsageRollupCharts, bool)`

GetChartsOk returns a tuple with the Charts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharts

`func (o *AgentUsageRollup) SetCharts(v AgentUsageRollupCharts)`

SetCharts sets Charts field to given value.

### HasCharts

`func (o *AgentUsageRollup) HasCharts() bool`

HasCharts returns a boolean if a field has been set.

### GetTotals

`func (o *AgentUsageRollup) GetTotals() AgentUsageRollupTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *AgentUsageRollup) GetTotalsOk() (*AgentUsageRollupTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *AgentUsageRollup) SetTotals(v AgentUsageRollupTotals)`

SetTotals sets Totals field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


