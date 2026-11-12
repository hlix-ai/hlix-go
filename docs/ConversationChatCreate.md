# ConversationChatCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChatId** | **string** |  |
**Id** | **string** |  |
**Private** | Pointer to **bool** |  | [optional]

## Methods

### NewConversationChatCreate

`func NewConversationChatCreate(chatId string, id string, ) *ConversationChatCreate`

NewConversationChatCreate instantiates a new ConversationChatCreate object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationChatCreateWithDefaults

`func NewConversationChatCreateWithDefaults() *ConversationChatCreate`

NewConversationChatCreateWithDefaults instantiates a new ConversationChatCreate object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetChatId

`func (o *ConversationChatCreate) GetChatId() string`

GetChatId returns the ChatId field if non-nil, zero value otherwise.

### GetChatIdOk

`func (o *ConversationChatCreate) GetChatIdOk() (*string, bool)`

GetChatIdOk returns a tuple with the ChatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatId

`func (o *ConversationChatCreate) SetChatId(v string)`

SetChatId sets ChatId field to given value.


### GetId

`func (o *ConversationChatCreate) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ConversationChatCreate) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ConversationChatCreate) SetId(v string)`

SetId sets Id field to given value.


### GetPrivate

`func (o *ConversationChatCreate) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ConversationChatCreate) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ConversationChatCreate) SetPrivate(v bool)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ConversationChatCreate) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


