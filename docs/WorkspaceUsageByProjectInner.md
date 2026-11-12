# WorkspaceUsageByProjectInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostMicros** | **NullableInt64** | The price in micros of the usage (cost plus markup). In metered billing it is what the workspace is charged and what the meter is sent; in task billing the workspace pays per accepted task, so it is the price equivalent of the usage, not a charge. Requests on the workspace&#39;s own key or login are in no total. Null when a request has no price yet. |
**ProjectId** | **string** |  |
**ProjectName** | **string** |  |
**Runs** | **float32** |  |

## Methods

### NewWorkspaceUsageByProjectInner

`func NewWorkspaceUsageByProjectInner(costMicros NullableInt64, projectId string, projectName string, runs float32, ) *WorkspaceUsageByProjectInner`

NewWorkspaceUsageByProjectInner instantiates a new WorkspaceUsageByProjectInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewWorkspaceUsageByProjectInnerWithDefaults

`func NewWorkspaceUsageByProjectInnerWithDefaults() *WorkspaceUsageByProjectInner`

NewWorkspaceUsageByProjectInnerWithDefaults instantiates a new WorkspaceUsageByProjectInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCostMicros

`func (o *WorkspaceUsageByProjectInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *WorkspaceUsageByProjectInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *WorkspaceUsageByProjectInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *WorkspaceUsageByProjectInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *WorkspaceUsageByProjectInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetProjectId

`func (o *WorkspaceUsageByProjectInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *WorkspaceUsageByProjectInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *WorkspaceUsageByProjectInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProjectName

`func (o *WorkspaceUsageByProjectInner) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *WorkspaceUsageByProjectInner) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *WorkspaceUsageByProjectInner) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### GetRuns

`func (o *WorkspaceUsageByProjectInner) GetRuns() float32`

GetRuns returns the Runs field if non-nil, zero value otherwise.

### GetRunsOk

`func (o *WorkspaceUsageByProjectInner) GetRunsOk() (*float32, bool)`

GetRunsOk returns a tuple with the Runs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuns

`func (o *WorkspaceUsageByProjectInner) SetRuns(v float32)`

SetRuns sets Runs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


