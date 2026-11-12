# ProjectChatDirectoryProjectManager

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChatId** | **string** |  |
**LastMessageAt** | **NullableString** |  |
**Scope** | [**ProjectChatDirectoryAgentsInnerScope**](ProjectChatDirectoryAgentsInnerScope.md) |  |
**Title** | **NullableString** |  |

## Methods

### NewProjectChatDirectoryProjectManager

`func NewProjectChatDirectoryProjectManager(chatId string, lastMessageAt NullableString, scope ProjectChatDirectoryAgentsInnerScope, title NullableString, ) *ProjectChatDirectoryProjectManager`

NewProjectChatDirectoryProjectManager instantiates a new ProjectChatDirectoryProjectManager object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectChatDirectoryProjectManagerWithDefaults

`func NewProjectChatDirectoryProjectManagerWithDefaults() *ProjectChatDirectoryProjectManager`

NewProjectChatDirectoryProjectManagerWithDefaults instantiates a new ProjectChatDirectoryProjectManager object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetChatId

`func (o *ProjectChatDirectoryProjectManager) GetChatId() string`

GetChatId returns the ChatId field if non-nil, zero value otherwise.

### GetChatIdOk

`func (o *ProjectChatDirectoryProjectManager) GetChatIdOk() (*string, bool)`

GetChatIdOk returns a tuple with the ChatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatId

`func (o *ProjectChatDirectoryProjectManager) SetChatId(v string)`

SetChatId sets ChatId field to given value.


### GetLastMessageAt

`func (o *ProjectChatDirectoryProjectManager) GetLastMessageAt() string`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *ProjectChatDirectoryProjectManager) GetLastMessageAtOk() (*string, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *ProjectChatDirectoryProjectManager) SetLastMessageAt(v string)`

SetLastMessageAt sets LastMessageAt field to given value.


### SetLastMessageAtNil

`func (o *ProjectChatDirectoryProjectManager) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *ProjectChatDirectoryProjectManager) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil
### GetScope

`func (o *ProjectChatDirectoryProjectManager) GetScope() ProjectChatDirectoryAgentsInnerScope`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *ProjectChatDirectoryProjectManager) GetScopeOk() (*ProjectChatDirectoryAgentsInnerScope, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *ProjectChatDirectoryProjectManager) SetScope(v ProjectChatDirectoryAgentsInnerScope)`

SetScope sets Scope field to given value.


### GetTitle

`func (o *ProjectChatDirectoryProjectManager) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProjectChatDirectoryProjectManager) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProjectChatDirectoryProjectManager) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *ProjectChatDirectoryProjectManager) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ProjectChatDirectoryProjectManager) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


