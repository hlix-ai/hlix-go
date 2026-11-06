# WireMessagePage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveTurnId** | Pointer to **NullableString** |  | [optional] 
**Messages** | [**[]ClientRequestDetailMessagesInner**](ClientRequestDetailMessagesInner.md) |  | 
**NextCursor** | **NullableString** |  | 

## Methods

### NewWireMessagePage

`func NewWireMessagePage(messages []ClientRequestDetailMessagesInner, nextCursor NullableString, ) *WireMessagePage`

NewWireMessagePage instantiates a new WireMessagePage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWireMessagePageWithDefaults

`func NewWireMessagePageWithDefaults() *WireMessagePage`

NewWireMessagePageWithDefaults instantiates a new WireMessagePage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveTurnId

`func (o *WireMessagePage) GetActiveTurnId() string`

GetActiveTurnId returns the ActiveTurnId field if non-nil, zero value otherwise.

### GetActiveTurnIdOk

`func (o *WireMessagePage) GetActiveTurnIdOk() (*string, bool)`

GetActiveTurnIdOk returns a tuple with the ActiveTurnId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveTurnId

`func (o *WireMessagePage) SetActiveTurnId(v string)`

SetActiveTurnId sets ActiveTurnId field to given value.

### HasActiveTurnId

`func (o *WireMessagePage) HasActiveTurnId() bool`

HasActiveTurnId returns a boolean if a field has been set.

### SetActiveTurnIdNil

`func (o *WireMessagePage) SetActiveTurnIdNil(b bool)`

 SetActiveTurnIdNil sets the value for ActiveTurnId to be an explicit nil

### UnsetActiveTurnId
`func (o *WireMessagePage) UnsetActiveTurnId()`

UnsetActiveTurnId ensures that no value is present for ActiveTurnId, not even an explicit nil
### GetMessages

`func (o *WireMessagePage) GetMessages() []ClientRequestDetailMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *WireMessagePage) GetMessagesOk() (*[]ClientRequestDetailMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *WireMessagePage) SetMessages(v []ClientRequestDetailMessagesInner)`

SetMessages sets Messages field to given value.


### GetNextCursor

`func (o *WireMessagePage) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *WireMessagePage) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *WireMessagePage) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *WireMessagePage) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *WireMessagePage) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


