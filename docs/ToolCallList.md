# ToolCallList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Calls** | [**[]ToolCallListCallsInner**](ToolCallListCallsInner.md) |  |
**NextCursor** | **NullableString** |  |

## Methods

### NewToolCallList

`func NewToolCallList(calls []ToolCallListCallsInner, nextCursor NullableString, ) *ToolCallList`

NewToolCallList instantiates a new ToolCallList object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewToolCallListWithDefaults

`func NewToolCallListWithDefaults() *ToolCallList`

NewToolCallListWithDefaults instantiates a new ToolCallList object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCalls

`func (o *ToolCallList) GetCalls() []ToolCallListCallsInner`

GetCalls returns the Calls field if non-nil, zero value otherwise.

### GetCallsOk

`func (o *ToolCallList) GetCallsOk() (*[]ToolCallListCallsInner, bool)`

GetCallsOk returns a tuple with the Calls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalls

`func (o *ToolCallList) SetCalls(v []ToolCallListCallsInner)`

SetCalls sets Calls field to given value.


### GetNextCursor

`func (o *ToolCallList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ToolCallList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ToolCallList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *ToolCallList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ToolCallList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


