# ConversationSend

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AddressAgent** | Pointer to **bool** |  | [optional]
**Attachments** | Pointer to [**[]ConversationSendAttachmentsInner**](ConversationSendAttachmentsInner.md) |  | [optional]
**ChatId** | **string** |  |
**Context** | Pointer to [**ConversationSendContext**](ConversationSendContext.md) |  | [optional]
**Message** | **string** |  |
**MessageId** | Pointer to **string** |  | [optional]
**Mode** | Pointer to **string** |  | [optional]

## Methods

### NewConversationSend

`func NewConversationSend(chatId string, message string, ) *ConversationSend`

NewConversationSend instantiates a new ConversationSend object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationSendWithDefaults

`func NewConversationSendWithDefaults() *ConversationSend`

NewConversationSendWithDefaults instantiates a new ConversationSend object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAddressAgent

`func (o *ConversationSend) GetAddressAgent() bool`

GetAddressAgent returns the AddressAgent field if non-nil, zero value otherwise.

### GetAddressAgentOk

`func (o *ConversationSend) GetAddressAgentOk() (*bool, bool)`

GetAddressAgentOk returns a tuple with the AddressAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressAgent

`func (o *ConversationSend) SetAddressAgent(v bool)`

SetAddressAgent sets AddressAgent field to given value.

### HasAddressAgent

`func (o *ConversationSend) HasAddressAgent() bool`

HasAddressAgent returns a boolean if a field has been set.

### GetAttachments

`func (o *ConversationSend) GetAttachments() []ConversationSendAttachmentsInner`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ConversationSend) GetAttachmentsOk() (*[]ConversationSendAttachmentsInner, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ConversationSend) SetAttachments(v []ConversationSendAttachmentsInner)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *ConversationSend) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetChatId

`func (o *ConversationSend) GetChatId() string`

GetChatId returns the ChatId field if non-nil, zero value otherwise.

### GetChatIdOk

`func (o *ConversationSend) GetChatIdOk() (*string, bool)`

GetChatIdOk returns a tuple with the ChatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatId

`func (o *ConversationSend) SetChatId(v string)`

SetChatId sets ChatId field to given value.


### GetContext

`func (o *ConversationSend) GetContext() ConversationSendContext`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *ConversationSend) GetContextOk() (*ConversationSendContext, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *ConversationSend) SetContext(v ConversationSendContext)`

SetContext sets Context field to given value.

### HasContext

`func (o *ConversationSend) HasContext() bool`

HasContext returns a boolean if a field has been set.

### GetMessage

`func (o *ConversationSend) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ConversationSend) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ConversationSend) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetMessageId

`func (o *ConversationSend) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ConversationSend) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ConversationSend) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *ConversationSend) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### GetMode

`func (o *ConversationSend) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *ConversationSend) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *ConversationSend) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *ConversationSend) HasMode() bool`

HasMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


