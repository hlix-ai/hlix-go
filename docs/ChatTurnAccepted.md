# ChatTurnAccepted

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveTurnId** | Pointer to **string** |  | [optional] 
**Delivered** | **string** |  | 
**MessageId** | **string** |  | 
**Queued** | Pointer to **bool** |  | [optional] 
**TurnId** | **string** |  | 

## Methods

### NewChatTurnAccepted

`func NewChatTurnAccepted(delivered string, messageId string, turnId string, ) *ChatTurnAccepted`

NewChatTurnAccepted instantiates a new ChatTurnAccepted object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatTurnAcceptedWithDefaults

`func NewChatTurnAcceptedWithDefaults() *ChatTurnAccepted`

NewChatTurnAcceptedWithDefaults instantiates a new ChatTurnAccepted object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveTurnId

`func (o *ChatTurnAccepted) GetActiveTurnId() string`

GetActiveTurnId returns the ActiveTurnId field if non-nil, zero value otherwise.

### GetActiveTurnIdOk

`func (o *ChatTurnAccepted) GetActiveTurnIdOk() (*string, bool)`

GetActiveTurnIdOk returns a tuple with the ActiveTurnId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveTurnId

`func (o *ChatTurnAccepted) SetActiveTurnId(v string)`

SetActiveTurnId sets ActiveTurnId field to given value.

### HasActiveTurnId

`func (o *ChatTurnAccepted) HasActiveTurnId() bool`

HasActiveTurnId returns a boolean if a field has been set.

### GetDelivered

`func (o *ChatTurnAccepted) GetDelivered() string`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *ChatTurnAccepted) GetDeliveredOk() (*string, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *ChatTurnAccepted) SetDelivered(v string)`

SetDelivered sets Delivered field to given value.


### GetMessageId

`func (o *ChatTurnAccepted) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ChatTurnAccepted) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ChatTurnAccepted) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.


### GetQueued

`func (o *ChatTurnAccepted) GetQueued() bool`

GetQueued returns the Queued field if non-nil, zero value otherwise.

### GetQueuedOk

`func (o *ChatTurnAccepted) GetQueuedOk() (*bool, bool)`

GetQueuedOk returns a tuple with the Queued field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueued

`func (o *ChatTurnAccepted) SetQueued(v bool)`

SetQueued sets Queued field to given value.

### HasQueued

`func (o *ChatTurnAccepted) HasQueued() bool`

HasQueued returns a boolean if a field has been set.

### GetTurnId

`func (o *ChatTurnAccepted) GetTurnId() string`

GetTurnId returns the TurnId field if non-nil, zero value otherwise.

### GetTurnIdOk

`func (o *ChatTurnAccepted) GetTurnIdOk() (*string, bool)`

GetTurnIdOk returns a tuple with the TurnId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTurnId

`func (o *ChatTurnAccepted) SetTurnId(v string)`

SetTurnId sets TurnId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


