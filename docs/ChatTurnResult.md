# ChatTurnResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reply** | [**NullableChatTurnResultReply**](ChatTurnResultReply.md) |  | 
**Status** | **string** |  | 
**TurnId** | **string** |  | 

## Methods

### NewChatTurnResult

`func NewChatTurnResult(reply NullableChatTurnResultReply, status string, turnId string, ) *ChatTurnResult`

NewChatTurnResult instantiates a new ChatTurnResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatTurnResultWithDefaults

`func NewChatTurnResultWithDefaults() *ChatTurnResult`

NewChatTurnResultWithDefaults instantiates a new ChatTurnResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReply

`func (o *ChatTurnResult) GetReply() ChatTurnResultReply`

GetReply returns the Reply field if non-nil, zero value otherwise.

### GetReplyOk

`func (o *ChatTurnResult) GetReplyOk() (*ChatTurnResultReply, bool)`

GetReplyOk returns a tuple with the Reply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReply

`func (o *ChatTurnResult) SetReply(v ChatTurnResultReply)`

SetReply sets Reply field to given value.


### SetReplyNil

`func (o *ChatTurnResult) SetReplyNil(b bool)`

 SetReplyNil sets the value for Reply to be an explicit nil

### UnsetReply
`func (o *ChatTurnResult) UnsetReply()`

UnsetReply ensures that no value is present for Reply, not even an explicit nil
### GetStatus

`func (o *ChatTurnResult) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ChatTurnResult) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ChatTurnResult) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTurnId

`func (o *ChatTurnResult) GetTurnId() string`

GetTurnId returns the TurnId field if non-nil, zero value otherwise.

### GetTurnIdOk

`func (o *ChatTurnResult) GetTurnIdOk() (*string, bool)`

GetTurnIdOk returns a tuple with the TurnId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTurnId

`func (o *ChatTurnResult) SetTurnId(v string)`

SetTurnId sets TurnId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


