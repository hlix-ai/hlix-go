# ChatSessionCreatedSession

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **NullableString** |  | 
**ForkedFrom** | [**NullableChatSessionCreatedSessionForkedFrom**](ChatSessionCreatedSessionForkedFrom.md) |  | 
**Id** | **string** |  | 
**IsDefault** | **bool** |  | 
**Model** | **NullableString** |  | 
**Private** | **bool** |  | 
**ThreadId** | **string** |  | 
**Title** | **NullableString** |  | 
**UpdatedAt** | **NullableString** |  | 

## Methods

### NewChatSessionCreatedSession

`func NewChatSessionCreatedSession(createdAt NullableString, forkedFrom NullableChatSessionCreatedSessionForkedFrom, id string, isDefault bool, model NullableString, private bool, threadId string, title NullableString, updatedAt NullableString, ) *ChatSessionCreatedSession`

NewChatSessionCreatedSession instantiates a new ChatSessionCreatedSession object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatSessionCreatedSessionWithDefaults

`func NewChatSessionCreatedSessionWithDefaults() *ChatSessionCreatedSession`

NewChatSessionCreatedSessionWithDefaults instantiates a new ChatSessionCreatedSession object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *ChatSessionCreatedSession) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ChatSessionCreatedSession) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ChatSessionCreatedSession) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *ChatSessionCreatedSession) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ChatSessionCreatedSession) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetForkedFrom

`func (o *ChatSessionCreatedSession) GetForkedFrom() ChatSessionCreatedSessionForkedFrom`

GetForkedFrom returns the ForkedFrom field if non-nil, zero value otherwise.

### GetForkedFromOk

`func (o *ChatSessionCreatedSession) GetForkedFromOk() (*ChatSessionCreatedSessionForkedFrom, bool)`

GetForkedFromOk returns a tuple with the ForkedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForkedFrom

`func (o *ChatSessionCreatedSession) SetForkedFrom(v ChatSessionCreatedSessionForkedFrom)`

SetForkedFrom sets ForkedFrom field to given value.


### SetForkedFromNil

`func (o *ChatSessionCreatedSession) SetForkedFromNil(b bool)`

 SetForkedFromNil sets the value for ForkedFrom to be an explicit nil

### UnsetForkedFrom
`func (o *ChatSessionCreatedSession) UnsetForkedFrom()`

UnsetForkedFrom ensures that no value is present for ForkedFrom, not even an explicit nil
### GetId

`func (o *ChatSessionCreatedSession) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChatSessionCreatedSession) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChatSessionCreatedSession) SetId(v string)`

SetId sets Id field to given value.


### GetIsDefault

`func (o *ChatSessionCreatedSession) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *ChatSessionCreatedSession) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *ChatSessionCreatedSession) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.


### GetModel

`func (o *ChatSessionCreatedSession) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ChatSessionCreatedSession) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ChatSessionCreatedSession) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *ChatSessionCreatedSession) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *ChatSessionCreatedSession) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetPrivate

`func (o *ChatSessionCreatedSession) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ChatSessionCreatedSession) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ChatSessionCreatedSession) SetPrivate(v bool)`

SetPrivate sets Private field to given value.


### GetThreadId

`func (o *ChatSessionCreatedSession) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *ChatSessionCreatedSession) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *ChatSessionCreatedSession) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetTitle

`func (o *ChatSessionCreatedSession) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ChatSessionCreatedSession) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ChatSessionCreatedSession) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *ChatSessionCreatedSession) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ChatSessionCreatedSession) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetUpdatedAt

`func (o *ChatSessionCreatedSession) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ChatSessionCreatedSession) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ChatSessionCreatedSession) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *ChatSessionCreatedSession) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ChatSessionCreatedSession) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


