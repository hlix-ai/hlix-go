# ProjectThreadDirectoryWorkGroupsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CycleId** | **NullableString** |  | 
**Tasks** | [**[]ProjectThreadDirectoryAgentsInner**](ProjectThreadDirectoryAgentsInner.md) |  | 
**Thread** | [**NullableProjectThreadDirectoryConductor**](ProjectThreadDirectoryConductor.md) |  | 

## Methods

### NewProjectThreadDirectoryWorkGroupsInner

`func NewProjectThreadDirectoryWorkGroupsInner(cycleId NullableString, tasks []ProjectThreadDirectoryAgentsInner, thread NullableProjectThreadDirectoryConductor, ) *ProjectThreadDirectoryWorkGroupsInner`

NewProjectThreadDirectoryWorkGroupsInner instantiates a new ProjectThreadDirectoryWorkGroupsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectThreadDirectoryWorkGroupsInnerWithDefaults

`func NewProjectThreadDirectoryWorkGroupsInnerWithDefaults() *ProjectThreadDirectoryWorkGroupsInner`

NewProjectThreadDirectoryWorkGroupsInnerWithDefaults instantiates a new ProjectThreadDirectoryWorkGroupsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCycleId

`func (o *ProjectThreadDirectoryWorkGroupsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ProjectThreadDirectoryWorkGroupsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ProjectThreadDirectoryWorkGroupsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ProjectThreadDirectoryWorkGroupsInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ProjectThreadDirectoryWorkGroupsInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetTasks

`func (o *ProjectThreadDirectoryWorkGroupsInner) GetTasks() []ProjectThreadDirectoryAgentsInner`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *ProjectThreadDirectoryWorkGroupsInner) GetTasksOk() (*[]ProjectThreadDirectoryAgentsInner, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *ProjectThreadDirectoryWorkGroupsInner) SetTasks(v []ProjectThreadDirectoryAgentsInner)`

SetTasks sets Tasks field to given value.


### GetThread

`func (o *ProjectThreadDirectoryWorkGroupsInner) GetThread() ProjectThreadDirectoryConductor`

GetThread returns the Thread field if non-nil, zero value otherwise.

### GetThreadOk

`func (o *ProjectThreadDirectoryWorkGroupsInner) GetThreadOk() (*ProjectThreadDirectoryConductor, bool)`

GetThreadOk returns a tuple with the Thread field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThread

`func (o *ProjectThreadDirectoryWorkGroupsInner) SetThread(v ProjectThreadDirectoryConductor)`

SetThread sets Thread field to given value.


### SetThreadNil

`func (o *ProjectThreadDirectoryWorkGroupsInner) SetThreadNil(b bool)`

 SetThreadNil sets the value for Thread to be an explicit nil

### UnsetThread
`func (o *ProjectThreadDirectoryWorkGroupsInner) UnsetThread()`

UnsetThread ensures that no value is present for Thread, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


