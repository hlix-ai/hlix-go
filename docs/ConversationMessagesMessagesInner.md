# ConversationMessagesMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthorUserId** | Pointer to **string** |  | [optional]
**CreatedAt** | Pointer to **float32** |  | [optional]
**Failed** | Pointer to [**ConversationMessagesMessagesInnerFailed**](ConversationMessagesMessagesInnerFailed.md) |  | [optional]
**Id** | **string** |  |
**IsError** | Pointer to **bool** |  | [optional]
**Presentation** | Pointer to [**ConversationMessagesMessagesInnerPresentation**](ConversationMessagesMessagesInnerPresentation.md) |  | [optional]
**Role** | **string** |  |
**Text** | **string** |  |
**ToolCallId** | Pointer to **string** |  | [optional]
**ToolCalls** | Pointer to [**[]ConversationMessagesMessagesInnerToolCallsInner**](ConversationMessagesMessagesInnerToolCallsInner.md) |  | [optional]
**ToolName** | Pointer to **string** |  | [optional]

## Methods

### NewConversationMessagesMessagesInner

`func NewConversationMessagesMessagesInner(id string, role string, text string, ) *ConversationMessagesMessagesInner`

NewConversationMessagesMessagesInner instantiates a new ConversationMessagesMessagesInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationMessagesMessagesInnerWithDefaults

`func NewConversationMessagesMessagesInnerWithDefaults() *ConversationMessagesMessagesInner`

NewConversationMessagesMessagesInnerWithDefaults instantiates a new ConversationMessagesMessagesInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAuthorUserId

`func (o *ConversationMessagesMessagesInner) GetAuthorUserId() string`

GetAuthorUserId returns the AuthorUserId field if non-nil, zero value otherwise.

### GetAuthorUserIdOk

`func (o *ConversationMessagesMessagesInner) GetAuthorUserIdOk() (*string, bool)`

GetAuthorUserIdOk returns a tuple with the AuthorUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorUserId

`func (o *ConversationMessagesMessagesInner) SetAuthorUserId(v string)`

SetAuthorUserId sets AuthorUserId field to given value.

### HasAuthorUserId

`func (o *ConversationMessagesMessagesInner) HasAuthorUserId() bool`

HasAuthorUserId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ConversationMessagesMessagesInner) GetCreatedAt() float32`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ConversationMessagesMessagesInner) GetCreatedAtOk() (*float32, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ConversationMessagesMessagesInner) SetCreatedAt(v float32)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ConversationMessagesMessagesInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFailed

`func (o *ConversationMessagesMessagesInner) GetFailed() ConversationMessagesMessagesInnerFailed`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *ConversationMessagesMessagesInner) GetFailedOk() (*ConversationMessagesMessagesInnerFailed, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *ConversationMessagesMessagesInner) SetFailed(v ConversationMessagesMessagesInnerFailed)`

SetFailed sets Failed field to given value.

### HasFailed

`func (o *ConversationMessagesMessagesInner) HasFailed() bool`

HasFailed returns a boolean if a field has been set.

### GetId

`func (o *ConversationMessagesMessagesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConversationMessagesMessagesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConversationMessagesMessagesInner) SetId(v string)`

SetId sets Id field to given value.


### GetIsError

`func (o *ConversationMessagesMessagesInner) GetIsError() bool`

GetIsError returns the IsError field if non-nil, zero value otherwise.

### GetIsErrorOk

`func (o *ConversationMessagesMessagesInner) GetIsErrorOk() (*bool, bool)`

GetIsErrorOk returns a tuple with the IsError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsError

`func (o *ConversationMessagesMessagesInner) SetIsError(v bool)`

SetIsError sets IsError field to given value.

### HasIsError

`func (o *ConversationMessagesMessagesInner) HasIsError() bool`

HasIsError returns a boolean if a field has been set.

### GetPresentation

`func (o *ConversationMessagesMessagesInner) GetPresentation() ConversationMessagesMessagesInnerPresentation`

GetPresentation returns the Presentation field if non-nil, zero value otherwise.

### GetPresentationOk

`func (o *ConversationMessagesMessagesInner) GetPresentationOk() (*ConversationMessagesMessagesInnerPresentation, bool)`

GetPresentationOk returns a tuple with the Presentation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresentation

`func (o *ConversationMessagesMessagesInner) SetPresentation(v ConversationMessagesMessagesInnerPresentation)`

SetPresentation sets Presentation field to given value.

### HasPresentation

`func (o *ConversationMessagesMessagesInner) HasPresentation() bool`

HasPresentation returns a boolean if a field has been set.

### GetRole

`func (o *ConversationMessagesMessagesInner) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ConversationMessagesMessagesInner) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ConversationMessagesMessagesInner) SetRole(v string)`

SetRole sets Role field to given value.


### GetText

`func (o *ConversationMessagesMessagesInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ConversationMessagesMessagesInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ConversationMessagesMessagesInner) SetText(v string)`

SetText sets Text field to given value.


### GetToolCallId

`func (o *ConversationMessagesMessagesInner) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *ConversationMessagesMessagesInner) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *ConversationMessagesMessagesInner) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.

### HasToolCallId

`func (o *ConversationMessagesMessagesInner) HasToolCallId() bool`

HasToolCallId returns a boolean if a field has been set.

### GetToolCalls

`func (o *ConversationMessagesMessagesInner) GetToolCalls() []ConversationMessagesMessagesInnerToolCallsInner`

GetToolCalls returns the ToolCalls field if non-nil, zero value otherwise.

### GetToolCallsOk

`func (o *ConversationMessagesMessagesInner) GetToolCallsOk() (*[]ConversationMessagesMessagesInnerToolCallsInner, bool)`

GetToolCallsOk returns a tuple with the ToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCalls

`func (o *ConversationMessagesMessagesInner) SetToolCalls(v []ConversationMessagesMessagesInnerToolCallsInner)`

SetToolCalls sets ToolCalls field to given value.

### HasToolCalls

`func (o *ConversationMessagesMessagesInner) HasToolCalls() bool`

HasToolCalls returns a boolean if a field has been set.

### GetToolName

`func (o *ConversationMessagesMessagesInner) GetToolName() string`

GetToolName returns the ToolName field if non-nil, zero value otherwise.

### GetToolNameOk

`func (o *ConversationMessagesMessagesInner) GetToolNameOk() (*string, bool)`

GetToolNameOk returns a tuple with the ToolName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolName

`func (o *ConversationMessagesMessagesInner) SetToolName(v string)`

SetToolName sets ToolName field to given value.

### HasToolName

`func (o *ConversationMessagesMessagesInner) HasToolName() bool`

HasToolName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


