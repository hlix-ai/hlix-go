# ConversationMessages

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | [**[]ConversationMessagesMessagesInner**](ConversationMessagesMessagesInner.md) |  |
**Next** | **NullableInt32** |  |

## Methods

### NewConversationMessages

`func NewConversationMessages(messages []ConversationMessagesMessagesInner, next NullableInt32, ) *ConversationMessages`

NewConversationMessages instantiates a new ConversationMessages object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewConversationMessagesWithDefaults

`func NewConversationMessagesWithDefaults() *ConversationMessages`

NewConversationMessagesWithDefaults instantiates a new ConversationMessages object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetMessages

`func (o *ConversationMessages) GetMessages() []ConversationMessagesMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ConversationMessages) GetMessagesOk() (*[]ConversationMessagesMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ConversationMessages) SetMessages(v []ConversationMessagesMessagesInner)`

SetMessages sets Messages field to given value.


### GetNext

`func (o *ConversationMessages) GetNext() int32`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *ConversationMessages) GetNextOk() (*int32, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *ConversationMessages) SetNext(v int32)`

SetNext sets Next field to given value.


### SetNextNil

`func (o *ConversationMessages) SetNextNil(b bool)`

 SetNextNil sets the value for Next to be an explicit nil

### UnsetNext
`func (o *ConversationMessages) UnsetNext()`

UnsetNext ensures that no value is present for Next, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


