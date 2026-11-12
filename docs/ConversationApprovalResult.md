# ConversationApprovalResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accepted** | Pointer to **bool** |  | [optional]
**ActiveOperationId** | Pointer to **string** |  | [optional]
**Chat** | Pointer to **string** |  | [optional]
**Cursor** | Pointer to [**ConversationApprovalResultCursor**](ConversationApprovalResultCursor.md) |  | [optional]
**Delivered** | Pointer to **string** |  | [optional]
**OperationId** | **string** |  |
**Queued** | Pointer to **bool** |  | [optional]

## Methods

### NewConversationApprovalResult

`func NewConversationApprovalResult(operationId string, ) *ConversationApprovalResult`

NewConversationApprovalResult instantiates a new ConversationApprovalResult object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationApprovalResultWithDefaults

`func NewConversationApprovalResultWithDefaults() *ConversationApprovalResult`

NewConversationApprovalResultWithDefaults instantiates a new ConversationApprovalResult object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAccepted

`func (o *ConversationApprovalResult) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *ConversationApprovalResult) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *ConversationApprovalResult) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.

### HasAccepted

`func (o *ConversationApprovalResult) HasAccepted() bool`

HasAccepted returns a boolean if a field has been set.

### GetActiveOperationId

`func (o *ConversationApprovalResult) GetActiveOperationId() string`

GetActiveOperationId returns the ActiveOperationId field if non-nil, zero value otherwise.

### GetActiveOperationIdOk

`func (o *ConversationApprovalResult) GetActiveOperationIdOk() (*string, bool)`

GetActiveOperationIdOk returns a tuple with the ActiveOperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveOperationId

`func (o *ConversationApprovalResult) SetActiveOperationId(v string)`

SetActiveOperationId sets ActiveOperationId field to given value.

### HasActiveOperationId

`func (o *ConversationApprovalResult) HasActiveOperationId() bool`

HasActiveOperationId returns a boolean if a field has been set.

### GetChat

`func (o *ConversationApprovalResult) GetChat() string`

GetChat returns the Chat field if non-nil, zero value otherwise.

### GetChatOk

`func (o *ConversationApprovalResult) GetChatOk() (*string, bool)`

GetChatOk returns a tuple with the Chat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChat

`func (o *ConversationApprovalResult) SetChat(v string)`

SetChat sets Chat field to given value.

### HasChat

`func (o *ConversationApprovalResult) HasChat() bool`

HasChat returns a boolean if a field has been set.

### GetCursor

`func (o *ConversationApprovalResult) GetCursor() ConversationApprovalResultCursor`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *ConversationApprovalResult) GetCursorOk() (*ConversationApprovalResultCursor, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *ConversationApprovalResult) SetCursor(v ConversationApprovalResultCursor)`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *ConversationApprovalResult) HasCursor() bool`

HasCursor returns a boolean if a field has been set.

### GetDelivered

`func (o *ConversationApprovalResult) GetDelivered() string`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *ConversationApprovalResult) GetDeliveredOk() (*string, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *ConversationApprovalResult) SetDelivered(v string)`

SetDelivered sets Delivered field to given value.

### HasDelivered

`func (o *ConversationApprovalResult) HasDelivered() bool`

HasDelivered returns a boolean if a field has been set.

### GetOperationId

`func (o *ConversationApprovalResult) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *ConversationApprovalResult) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *ConversationApprovalResult) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.


### GetQueued

`func (o *ConversationApprovalResult) GetQueued() bool`

GetQueued returns the Queued field if non-nil, zero value otherwise.

### GetQueuedOk

`func (o *ConversationApprovalResult) GetQueuedOk() (*bool, bool)`

GetQueuedOk returns a tuple with the Queued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueued

`func (o *ConversationApprovalResult) SetQueued(v bool)`

SetQueued sets Queued field to given value.

### HasQueued

`func (o *ConversationApprovalResult) HasQueued() bool`

HasQueued returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


