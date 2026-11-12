# ProjectBoard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Activity** | [**[]ProjectBoardActivityInner**](ProjectBoardActivityInner.md) |  |
**Agents** | [**[]ProjectBoardAgentsInner**](ProjectBoardAgentsInner.md) |  |
**Cycles** | [**[]ProjectBoardCyclesInner**](ProjectBoardCyclesInner.md) |  |
**LiveGrowthRunIds** | **[]string** |  |
**Preview** | [**ProjectBoardPreview**](ProjectBoardPreview.md) |  |
**Project** | [**ProjectBoardProject**](ProjectBoardProject.md) |  |
**Tasks** | [**[]ProjectBoardTasksInner**](ProjectBoardTasksInner.md) |  |

## Methods

### NewProjectBoard

`func NewProjectBoard(activity []ProjectBoardActivityInner, agents []ProjectBoardAgentsInner, cycles []ProjectBoardCyclesInner, liveGrowthRunIds []string, preview ProjectBoardPreview, project ProjectBoardProject, tasks []ProjectBoardTasksInner, ) *ProjectBoard`

NewProjectBoard instantiates a new ProjectBoard object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectBoardWithDefaults

`func NewProjectBoardWithDefaults() *ProjectBoard`

NewProjectBoardWithDefaults instantiates a new ProjectBoard object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetActivity

`func (o *ProjectBoard) GetActivity() []ProjectBoardActivityInner`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *ProjectBoard) GetActivityOk() (*[]ProjectBoardActivityInner, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *ProjectBoard) SetActivity(v []ProjectBoardActivityInner)`

SetActivity sets Activity field to given value.


### GetAgents

`func (o *ProjectBoard) GetAgents() []ProjectBoardAgentsInner`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *ProjectBoard) GetAgentsOk() (*[]ProjectBoardAgentsInner, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *ProjectBoard) SetAgents(v []ProjectBoardAgentsInner)`

SetAgents sets Agents field to given value.


### GetCycles

`func (o *ProjectBoard) GetCycles() []ProjectBoardCyclesInner`

GetCycles returns the Cycles field if non-nil, zero value otherwise.

### GetCyclesOk

`func (o *ProjectBoard) GetCyclesOk() (*[]ProjectBoardCyclesInner, bool)`

GetCyclesOk returns a tuple with the Cycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycles

`func (o *ProjectBoard) SetCycles(v []ProjectBoardCyclesInner)`

SetCycles sets Cycles field to given value.


### GetLiveGrowthRunIds

`func (o *ProjectBoard) GetLiveGrowthRunIds() []string`

GetLiveGrowthRunIds returns the LiveGrowthRunIds field if non-nil, zero value otherwise.

### GetLiveGrowthRunIdsOk

`func (o *ProjectBoard) GetLiveGrowthRunIdsOk() (*[]string, bool)`

GetLiveGrowthRunIdsOk returns a tuple with the LiveGrowthRunIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiveGrowthRunIds

`func (o *ProjectBoard) SetLiveGrowthRunIds(v []string)`

SetLiveGrowthRunIds sets LiveGrowthRunIds field to given value.


### GetPreview

`func (o *ProjectBoard) GetPreview() ProjectBoardPreview`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *ProjectBoard) GetPreviewOk() (*ProjectBoardPreview, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *ProjectBoard) SetPreview(v ProjectBoardPreview)`

SetPreview sets Preview field to given value.


### GetProject

`func (o *ProjectBoard) GetProject() ProjectBoardProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectBoard) GetProjectOk() (*ProjectBoardProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectBoard) SetProject(v ProjectBoardProject)`

SetProject sets Project field to given value.


### GetTasks

`func (o *ProjectBoard) GetTasks() []ProjectBoardTasksInner`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *ProjectBoard) GetTasksOk() (*[]ProjectBoardTasksInner, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *ProjectBoard) SetTasks(v []ProjectBoardTasksInner)`

SetTasks sets Tasks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


