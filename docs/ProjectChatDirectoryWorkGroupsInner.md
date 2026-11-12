# ProjectChatDirectoryWorkGroupsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Chat** | [**NullableProjectChatDirectoryProjectManager**](ProjectChatDirectoryProjectManager.md) |  |
**CycleId** | **NullableString** |  |
**Tasks** | [**[]ProjectChatDirectoryAgentsInner**](ProjectChatDirectoryAgentsInner.md) |  |

## Methods

### NewProjectChatDirectoryWorkGroupsInner

`func NewProjectChatDirectoryWorkGroupsInner(chat NullableProjectChatDirectoryProjectManager, cycleId NullableString, tasks []ProjectChatDirectoryAgentsInner, ) *ProjectChatDirectoryWorkGroupsInner`

NewProjectChatDirectoryWorkGroupsInner instantiates a new ProjectChatDirectoryWorkGroupsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectChatDirectoryWorkGroupsInnerWithDefaults

`func NewProjectChatDirectoryWorkGroupsInnerWithDefaults() *ProjectChatDirectoryWorkGroupsInner`

NewProjectChatDirectoryWorkGroupsInnerWithDefaults instantiates a new ProjectChatDirectoryWorkGroupsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetChat

`func (o *ProjectChatDirectoryWorkGroupsInner) GetChat() ProjectChatDirectoryProjectManager`

GetChat returns the Chat field if non-nil, zero value otherwise.

### GetChatOk

`func (o *ProjectChatDirectoryWorkGroupsInner) GetChatOk() (*ProjectChatDirectoryProjectManager, bool)`

GetChatOk returns a tuple with the Chat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChat

`func (o *ProjectChatDirectoryWorkGroupsInner) SetChat(v ProjectChatDirectoryProjectManager)`

SetChat sets Chat field to given value.


### SetChatNil

`func (o *ProjectChatDirectoryWorkGroupsInner) SetChatNil(b bool)`

 SetChatNil sets the value for Chat to be an explicit nil

### UnsetChat
`func (o *ProjectChatDirectoryWorkGroupsInner) UnsetChat()`

UnsetChat ensures that no value is present for Chat, not even an explicit nil
### GetCycleId

`func (o *ProjectChatDirectoryWorkGroupsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ProjectChatDirectoryWorkGroupsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ProjectChatDirectoryWorkGroupsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ProjectChatDirectoryWorkGroupsInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ProjectChatDirectoryWorkGroupsInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetTasks

`func (o *ProjectChatDirectoryWorkGroupsInner) GetTasks() []ProjectChatDirectoryAgentsInner`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *ProjectChatDirectoryWorkGroupsInner) GetTasksOk() (*[]ProjectChatDirectoryAgentsInner, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *ProjectChatDirectoryWorkGroupsInner) SetTasks(v []ProjectChatDirectoryAgentsInner)`

SetTasks sets Tasks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


