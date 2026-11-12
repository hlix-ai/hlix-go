# ConversationApproval

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Approved** | **bool** |  |
**ChatId** | **string** |  |
**Reason** | Pointer to **string** |  | [optional]

## Methods

### NewConversationApproval

`func NewConversationApproval(approved bool, chatId string, ) *ConversationApproval`

NewConversationApproval instantiates a new ConversationApproval object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationApprovalWithDefaults

`func NewConversationApprovalWithDefaults() *ConversationApproval`

NewConversationApprovalWithDefaults instantiates a new ConversationApproval object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApproved

`func (o *ConversationApproval) GetApproved() bool`

GetApproved returns the Approved field if non-nil, zero value otherwise.

### GetApprovedOk

`func (o *ConversationApproval) GetApprovedOk() (*bool, bool)`

GetApprovedOk returns a tuple with the Approved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApproved

`func (o *ConversationApproval) SetApproved(v bool)`

SetApproved sets Approved field to given value.


### GetChatId

`func (o *ConversationApproval) GetChatId() string`

GetChatId returns the ChatId field if non-nil, zero value otherwise.

### GetChatIdOk

`func (o *ConversationApproval) GetChatIdOk() (*string, bool)`

GetChatIdOk returns a tuple with the ChatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChatId

`func (o *ConversationApproval) SetChatId(v string)`

SetChatId sets ChatId field to given value.


### GetReason

`func (o *ConversationApproval) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ConversationApproval) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ConversationApproval) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *ConversationApproval) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


