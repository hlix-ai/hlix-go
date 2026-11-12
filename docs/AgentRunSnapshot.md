# AgentRunSnapshot

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentKind** | **string** |  |
**CompletedAt** | **NullableString** |  |
**Id** | **string** |  |
**InputSnapshot** | **NullableString** |  |
**Model** | **string** |  |
**OutputSnapshot** | **NullableString** |  |
**ParentRunId** | **NullableString** |  |
**PromptKey** | **NullableString** |  |
**StartedAt** | **string** |  |
**Status** | **string** |  |
**TaskId** | **NullableString** |  |

## Methods

### NewAgentRunSnapshot

`func NewAgentRunSnapshot(agentKind string, completedAt NullableString, id string, inputSnapshot NullableString, model string, outputSnapshot NullableString, parentRunId NullableString, promptKey NullableString, startedAt string, status string, taskId NullableString, ) *AgentRunSnapshot`

NewAgentRunSnapshot instantiates a new AgentRunSnapshot object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgentRunSnapshotWithDefaults

`func NewAgentRunSnapshotWithDefaults() *AgentRunSnapshot`

NewAgentRunSnapshotWithDefaults instantiates a new AgentRunSnapshot object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentKind

`func (o *AgentRunSnapshot) GetAgentKind() string`

GetAgentKind returns the AgentKind field if non-nil, zero value otherwise.

### GetAgentKindOk

`func (o *AgentRunSnapshot) GetAgentKindOk() (*string, bool)`

GetAgentKindOk returns a tuple with the AgentKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentKind

`func (o *AgentRunSnapshot) SetAgentKind(v string)`

SetAgentKind sets AgentKind field to given value.


### GetCompletedAt

`func (o *AgentRunSnapshot) GetCompletedAt() string`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AgentRunSnapshot) GetCompletedAtOk() (*string, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AgentRunSnapshot) SetCompletedAt(v string)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *AgentRunSnapshot) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AgentRunSnapshot) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetId

`func (o *AgentRunSnapshot) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentRunSnapshot) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentRunSnapshot) SetId(v string)`

SetId sets Id field to given value.


### GetInputSnapshot

`func (o *AgentRunSnapshot) GetInputSnapshot() string`

GetInputSnapshot returns the InputSnapshot field if non-nil, zero value otherwise.

### GetInputSnapshotOk

`func (o *AgentRunSnapshot) GetInputSnapshotOk() (*string, bool)`

GetInputSnapshotOk returns a tuple with the InputSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputSnapshot

`func (o *AgentRunSnapshot) SetInputSnapshot(v string)`

SetInputSnapshot sets InputSnapshot field to given value.


### SetInputSnapshotNil

`func (o *AgentRunSnapshot) SetInputSnapshotNil(b bool)`

 SetInputSnapshotNil sets the value for InputSnapshot to be an explicit nil

### UnsetInputSnapshot
`func (o *AgentRunSnapshot) UnsetInputSnapshot()`

UnsetInputSnapshot ensures that no value is present for InputSnapshot, not even an explicit nil
### GetModel

`func (o *AgentRunSnapshot) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AgentRunSnapshot) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AgentRunSnapshot) SetModel(v string)`

SetModel sets Model field to given value.


### GetOutputSnapshot

`func (o *AgentRunSnapshot) GetOutputSnapshot() string`

GetOutputSnapshot returns the OutputSnapshot field if non-nil, zero value otherwise.

### GetOutputSnapshotOk

`func (o *AgentRunSnapshot) GetOutputSnapshotOk() (*string, bool)`

GetOutputSnapshotOk returns a tuple with the OutputSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputSnapshot

`func (o *AgentRunSnapshot) SetOutputSnapshot(v string)`

SetOutputSnapshot sets OutputSnapshot field to given value.


### SetOutputSnapshotNil

`func (o *AgentRunSnapshot) SetOutputSnapshotNil(b bool)`

 SetOutputSnapshotNil sets the value for OutputSnapshot to be an explicit nil

### UnsetOutputSnapshot
`func (o *AgentRunSnapshot) UnsetOutputSnapshot()`

UnsetOutputSnapshot ensures that no value is present for OutputSnapshot, not even an explicit nil
### GetParentRunId

`func (o *AgentRunSnapshot) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *AgentRunSnapshot) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *AgentRunSnapshot) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.


### SetParentRunIdNil

`func (o *AgentRunSnapshot) SetParentRunIdNil(b bool)`

 SetParentRunIdNil sets the value for ParentRunId to be an explicit nil

### UnsetParentRunId
`func (o *AgentRunSnapshot) UnsetParentRunId()`

UnsetParentRunId ensures that no value is present for ParentRunId, not even an explicit nil
### GetPromptKey

`func (o *AgentRunSnapshot) GetPromptKey() string`

GetPromptKey returns the PromptKey field if non-nil, zero value otherwise.

### GetPromptKeyOk

`func (o *AgentRunSnapshot) GetPromptKeyOk() (*string, bool)`

GetPromptKeyOk returns a tuple with the PromptKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptKey

`func (o *AgentRunSnapshot) SetPromptKey(v string)`

SetPromptKey sets PromptKey field to given value.


### SetPromptKeyNil

`func (o *AgentRunSnapshot) SetPromptKeyNil(b bool)`

 SetPromptKeyNil sets the value for PromptKey to be an explicit nil

### UnsetPromptKey
`func (o *AgentRunSnapshot) UnsetPromptKey()`

UnsetPromptKey ensures that no value is present for PromptKey, not even an explicit nil
### GetStartedAt

`func (o *AgentRunSnapshot) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *AgentRunSnapshot) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *AgentRunSnapshot) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *AgentRunSnapshot) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AgentRunSnapshot) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AgentRunSnapshot) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *AgentRunSnapshot) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *AgentRunSnapshot) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *AgentRunSnapshot) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *AgentRunSnapshot) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *AgentRunSnapshot) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


