# WorkspaceUsageByDayInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostMicros** | **NullableInt64** | The price in micros of the usage (cost plus markup). In metered billing it is what the workspace is charged and what the meter is sent; in task billing the workspace pays per accepted task, so it is the price equivalent of the usage, not a charge. Requests on the workspace&#39;s own key or login are in no total. Null when a request has no price yet. |
**Day** | **string** |  |
**IncompleteUsageRuns** | **float32** |  |

## Methods

### NewWorkspaceUsageByDayInner

`func NewWorkspaceUsageByDayInner(costMicros NullableInt64, day string, incompleteUsageRuns float32, ) *WorkspaceUsageByDayInner`

NewWorkspaceUsageByDayInner instantiates a new WorkspaceUsageByDayInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewWorkspaceUsageByDayInnerWithDefaults

`func NewWorkspaceUsageByDayInnerWithDefaults() *WorkspaceUsageByDayInner`

NewWorkspaceUsageByDayInnerWithDefaults instantiates a new WorkspaceUsageByDayInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCostMicros

`func (o *WorkspaceUsageByDayInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *WorkspaceUsageByDayInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *WorkspaceUsageByDayInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *WorkspaceUsageByDayInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *WorkspaceUsageByDayInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetDay

`func (o *WorkspaceUsageByDayInner) GetDay() string`

GetDay returns the Day field if non-nil, zero value otherwise.

### GetDayOk

`func (o *WorkspaceUsageByDayInner) GetDayOk() (*string, bool)`

GetDayOk returns a tuple with the Day field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDay

`func (o *WorkspaceUsageByDayInner) SetDay(v string)`

SetDay sets Day field to given value.


### GetIncompleteUsageRuns

`func (o *WorkspaceUsageByDayInner) GetIncompleteUsageRuns() float32`

GetIncompleteUsageRuns returns the IncompleteUsageRuns field if non-nil, zero value otherwise.

### GetIncompleteUsageRunsOk

`func (o *WorkspaceUsageByDayInner) GetIncompleteUsageRunsOk() (*float32, bool)`

GetIncompleteUsageRunsOk returns a tuple with the IncompleteUsageRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompleteUsageRuns

`func (o *WorkspaceUsageByDayInner) SetIncompleteUsageRuns(v float32)`

SetIncompleteUsageRuns sets IncompleteUsageRuns field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


