# ChatStopResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CancelRequested** | **bool** |  | 
**Ok** | **bool** |  | 
**QueuedCanceled** | Pointer to **int32** |  | [optional] 

## Methods

### NewChatStopResponse

`func NewChatStopResponse(cancelRequested bool, ok bool, ) *ChatStopResponse`

NewChatStopResponse instantiates a new ChatStopResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatStopResponseWithDefaults

`func NewChatStopResponseWithDefaults() *ChatStopResponse`

NewChatStopResponseWithDefaults instantiates a new ChatStopResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCancelRequested

`func (o *ChatStopResponse) GetCancelRequested() bool`

GetCancelRequested returns the CancelRequested field if non-nil, zero value otherwise.

### GetCancelRequestedOk

`func (o *ChatStopResponse) GetCancelRequestedOk() (*bool, bool)`

GetCancelRequestedOk returns a tuple with the CancelRequested field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelRequested

`func (o *ChatStopResponse) SetCancelRequested(v bool)`

SetCancelRequested sets CancelRequested field to given value.


### GetOk

`func (o *ChatStopResponse) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *ChatStopResponse) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *ChatStopResponse) SetOk(v bool)`

SetOk sets Ok field to given value.


### GetQueuedCanceled

`func (o *ChatStopResponse) GetQueuedCanceled() int32`

GetQueuedCanceled returns the QueuedCanceled field if non-nil, zero value otherwise.

### GetQueuedCanceledOk

`func (o *ChatStopResponse) GetQueuedCanceledOk() (*int32, bool)`

GetQueuedCanceledOk returns a tuple with the QueuedCanceled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueuedCanceled

`func (o *ChatStopResponse) SetQueuedCanceled(v int32)`

SetQueuedCanceled sets QueuedCanceled field to given value.

### HasQueuedCanceled

`func (o *ChatStopResponse) HasQueuedCanceled() bool`

HasQueuedCanceled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


