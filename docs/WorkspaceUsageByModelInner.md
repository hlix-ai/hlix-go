# WorkspaceUsageByModelInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostMicros** | **NullableInt64** | The price in micros of the usage (cost plus markup). In metered billing it is what the workspace is charged and what the meter is sent; in task billing the workspace pays per accepted task, so it is the price equivalent of the usage, not a charge. Requests on the workspace&#39;s own key or login are in no total. Null when a request has no price yet. |
**Model** | **string** |  |
**Runs** | **float32** |  |

## Methods

### NewWorkspaceUsageByModelInner

`func NewWorkspaceUsageByModelInner(costMicros NullableInt64, model string, runs float32, ) *WorkspaceUsageByModelInner`

NewWorkspaceUsageByModelInner instantiates a new WorkspaceUsageByModelInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewWorkspaceUsageByModelInnerWithDefaults

`func NewWorkspaceUsageByModelInnerWithDefaults() *WorkspaceUsageByModelInner`

NewWorkspaceUsageByModelInnerWithDefaults instantiates a new WorkspaceUsageByModelInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCostMicros

`func (o *WorkspaceUsageByModelInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *WorkspaceUsageByModelInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *WorkspaceUsageByModelInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *WorkspaceUsageByModelInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *WorkspaceUsageByModelInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetModel

`func (o *WorkspaceUsageByModelInner) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *WorkspaceUsageByModelInner) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *WorkspaceUsageByModelInner) SetModel(v string)`

SetModel sets Model field to given value.


### GetRuns

`func (o *WorkspaceUsageByModelInner) GetRuns() float32`

GetRuns returns the Runs field if non-nil, zero value otherwise.

### GetRunsOk

`func (o *WorkspaceUsageByModelInner) GetRunsOk() (*float32, bool)`

GetRunsOk returns a tuple with the Runs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuns

`func (o *WorkspaceUsageByModelInner) SetRuns(v float32)`

SetRuns sets Runs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


