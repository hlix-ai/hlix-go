# MentionInboxItemsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentId** | **NullableString** |  |
**Author** | [**MentionInboxItemsInnerAuthor**](MentionInboxItemsInnerAuthor.md) |  |
**ChatId** | **string** |  |
**CreatedAt** | **string** |  |
**CycleId** | **NullableString** |  |
**Id** | **string** |  |
**MessageId** | **string** |  |
**ProjectId** | **NullableString** |  |
**ProjectName** | **NullableString** |  |
**Snippet** | **string** |  |
**TaskId** | **NullableString** |  |

## Methods

### NewMentionInboxItemsInner

`func NewMentionInboxItemsInner(agentId NullableString, author MentionInboxItemsInnerAuthor, chatId string, createdAt string, cycleId NullableString, id string, messageId string, projectId NullableString, projectName NullableString, snippet string, taskId NullableString, ) *MentionInboxItemsInner`

NewMentionInboxItemsInner instantiates a new MentionInboxItemsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMentionInboxItemsInnerWithDefaults

`func NewMentionInboxItemsInnerWithDefaults() *MentionInboxItemsInner`

NewMentionInboxItemsInnerWithDefaults instantiates a new MentionInboxItemsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentId

`func (o *MentionInboxItemsInner) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *MentionInboxItemsInner) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *MentionInboxItemsInner) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.


### SetAgentIdNil

`func (o *MentionInboxItemsInner) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *MentionInboxItemsInner) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetAuthor

`func (o *MentionInboxItemsInner) GetAuthor() MentionInboxItemsInnerAuthor`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *MentionInboxItemsInner) GetAuthorOk() (*MentionInboxItemsInnerAuthor, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *MentionInboxItemsInner) SetAuthor(v MentionInboxItemsInnerAuthor)`

SetAuthor sets Author field to given value.


### GetChatId

`func (o *MentionInboxItemsInner) GetChatId() string`

GetChatId returns the ChatId field if non-nil, zero value otherwise.

### GetChatIdOk

`func (o *MentionInboxItemsInner) GetChatIdOk() (*string, bool)`

GetChatIdOk returns a tuple with the ChatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatId

`func (o *MentionInboxItemsInner) SetChatId(v string)`

SetChatId sets ChatId field to given value.


### GetCreatedAt

`func (o *MentionInboxItemsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MentionInboxItemsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MentionInboxItemsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *MentionInboxItemsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *MentionInboxItemsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *MentionInboxItemsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *MentionInboxItemsInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *MentionInboxItemsInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetId

`func (o *MentionInboxItemsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MentionInboxItemsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MentionInboxItemsInner) SetId(v string)`

SetId sets Id field to given value.


### GetMessageId

`func (o *MentionInboxItemsInner) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *MentionInboxItemsInner) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *MentionInboxItemsInner) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.


### GetProjectId

`func (o *MentionInboxItemsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *MentionInboxItemsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *MentionInboxItemsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *MentionInboxItemsInner) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *MentionInboxItemsInner) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetProjectName

`func (o *MentionInboxItemsInner) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *MentionInboxItemsInner) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *MentionInboxItemsInner) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### SetProjectNameNil

`func (o *MentionInboxItemsInner) SetProjectNameNil(b bool)`

 SetProjectNameNil sets the value for ProjectName to be an explicit nil

### UnsetProjectName
`func (o *MentionInboxItemsInner) UnsetProjectName()`

UnsetProjectName ensures that no value is present for ProjectName, not even an explicit nil
### GetSnippet

`func (o *MentionInboxItemsInner) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *MentionInboxItemsInner) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *MentionInboxItemsInner) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetTaskId

`func (o *MentionInboxItemsInner) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *MentionInboxItemsInner) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *MentionInboxItemsInner) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *MentionInboxItemsInner) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *MentionInboxItemsInner) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


