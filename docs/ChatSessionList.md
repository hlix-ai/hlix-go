# ChatSessionList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NextCursor** | **NullableString** |  | 
**Sessions** | [**[]ChatSessionCreatedSession**](ChatSessionCreatedSession.md) |  | 

## Methods

### NewChatSessionList

`func NewChatSessionList(nextCursor NullableString, sessions []ChatSessionCreatedSession, ) *ChatSessionList`

NewChatSessionList instantiates a new ChatSessionList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatSessionListWithDefaults

`func NewChatSessionListWithDefaults() *ChatSessionList`

NewChatSessionListWithDefaults instantiates a new ChatSessionList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNextCursor

`func (o *ChatSessionList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ChatSessionList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ChatSessionList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *ChatSessionList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ChatSessionList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetSessions

`func (o *ChatSessionList) GetSessions() []ChatSessionCreatedSession`

GetSessions returns the Sessions field if non-nil, zero value otherwise.

### GetSessionsOk

`func (o *ChatSessionList) GetSessionsOk() (*[]ChatSessionCreatedSession, bool)`

GetSessionsOk returns a tuple with the Sessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessions

`func (o *ChatSessionList) SetSessions(v []ChatSessionCreatedSession)`

SetSessions sets Sessions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


