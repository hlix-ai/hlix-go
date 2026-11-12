# ProjectChatDirectoryAgentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChatId** | **string** |  |
**LastMessageAt** | **NullableString** |  |
**Scope** | [**ProjectChatDirectoryAgentsInnerScope**](ProjectChatDirectoryAgentsInnerScope.md) |  |
**Title** | **NullableString** |  |

## Methods

### NewProjectChatDirectoryAgentsInner

`func NewProjectChatDirectoryAgentsInner(chatId string, lastMessageAt NullableString, scope ProjectChatDirectoryAgentsInnerScope, title NullableString, ) *ProjectChatDirectoryAgentsInner`

NewProjectChatDirectoryAgentsInner instantiates a new ProjectChatDirectoryAgentsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectChatDirectoryAgentsInnerWithDefaults

`func NewProjectChatDirectoryAgentsInnerWithDefaults() *ProjectChatDirectoryAgentsInner`

NewProjectChatDirectoryAgentsInnerWithDefaults instantiates a new ProjectChatDirectoryAgentsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetChatId

`func (o *ProjectChatDirectoryAgentsInner) GetChatId() string`

GetChatId returns the ChatId field if non-nil, zero value otherwise.

### GetChatIdOk

`func (o *ProjectChatDirectoryAgentsInner) GetChatIdOk() (*string, bool)`

GetChatIdOk returns a tuple with the ChatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatId

`func (o *ProjectChatDirectoryAgentsInner) SetChatId(v string)`

SetChatId sets ChatId field to given value.


### GetLastMessageAt

`func (o *ProjectChatDirectoryAgentsInner) GetLastMessageAt() string`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *ProjectChatDirectoryAgentsInner) GetLastMessageAtOk() (*string, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *ProjectChatDirectoryAgentsInner) SetLastMessageAt(v string)`

SetLastMessageAt sets LastMessageAt field to given value.


### SetLastMessageAtNil

`func (o *ProjectChatDirectoryAgentsInner) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *ProjectChatDirectoryAgentsInner) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil
### GetScope

`func (o *ProjectChatDirectoryAgentsInner) GetScope() ProjectChatDirectoryAgentsInnerScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *ProjectChatDirectoryAgentsInner) GetScopeOk() (*ProjectChatDirectoryAgentsInnerScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *ProjectChatDirectoryAgentsInner) SetScope(v ProjectChatDirectoryAgentsInnerScope)`

SetScope sets Scope field to given value.


### GetTitle

`func (o *ProjectChatDirectoryAgentsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProjectChatDirectoryAgentsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProjectChatDirectoryAgentsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *ProjectChatDirectoryAgentsInner) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ProjectChatDirectoryAgentsInner) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


