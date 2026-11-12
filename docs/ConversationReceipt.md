# ConversationReceipt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accepted** | **bool** |  |
**ActiveOperationId** | Pointer to **string** |  | [optional]
**Chat** | **string** |  |
**Cursor** | Pointer to [**ConversationApprovalResultCursor**](ConversationApprovalResultCursor.md) |  | [optional]
**Delivered** | Pointer to **string** |  | [optional]
**OperationId** | **string** |  |
**Queued** | **bool** |  |

## Methods

### NewConversationReceipt

`func NewConversationReceipt(accepted bool, chat string, operationId string, queued bool, ) *ConversationReceipt`

NewConversationReceipt instantiates a new ConversationReceipt object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationReceiptWithDefaults

`func NewConversationReceiptWithDefaults() *ConversationReceipt`

NewConversationReceiptWithDefaults instantiates a new ConversationReceipt object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAccepted

`func (o *ConversationReceipt) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *ConversationReceipt) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *ConversationReceipt) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.


### GetActiveOperationId

`func (o *ConversationReceipt) GetActiveOperationId() string`

GetActiveOperationId returns the ActiveOperationId field if non-nil, zero value otherwise.

### GetActiveOperationIdOk

`func (o *ConversationReceipt) GetActiveOperationIdOk() (*string, bool)`

GetActiveOperationIdOk returns a tuple with the ActiveOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveOperationId

`func (o *ConversationReceipt) SetActiveOperationId(v string)`

SetActiveOperationId sets ActiveOperationId field to given value.

### HasActiveOperationId

`func (o *ConversationReceipt) HasActiveOperationId() bool`

HasActiveOperationId returns a boolean if a field has been set.

### GetChat

`func (o *ConversationReceipt) GetChat() string`

GetChat returns the Chat field if non-nil, zero value otherwise.

### GetChatOk

`func (o *ConversationReceipt) GetChatOk() (*string, bool)`

GetChatOk returns a tuple with the Chat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChat

`func (o *ConversationReceipt) SetChat(v string)`

SetChat sets Chat field to given value.


### GetCursor

`func (o *ConversationReceipt) GetCursor() ConversationApprovalResultCursor`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *ConversationReceipt) GetCursorOk() (*ConversationApprovalResultCursor, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *ConversationReceipt) SetCursor(v ConversationApprovalResultCursor)`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *ConversationReceipt) HasCursor() bool`

HasCursor returns a boolean if a field has been set.

### GetDelivered

`func (o *ConversationReceipt) GetDelivered() string`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *ConversationReceipt) GetDeliveredOk() (*string, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *ConversationReceipt) SetDelivered(v string)`

SetDelivered sets Delivered field to given value.

### HasDelivered

`func (o *ConversationReceipt) HasDelivered() bool`

HasDelivered returns a boolean if a field has been set.

### GetOperationId

`func (o *ConversationReceipt) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ConversationReceipt) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ConversationReceipt) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.


### GetQueued

`func (o *ConversationReceipt) GetQueued() bool`

GetQueued returns the Queued field if non-nil, zero value otherwise.

### GetQueuedOk

`func (o *ConversationReceipt) GetQueuedOk() (*bool, bool)`

GetQueuedOk returns a tuple with the Queued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueued

`func (o *ConversationReceipt) SetQueued(v bool)`

SetQueued sets Queued field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


