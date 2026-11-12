# AnthropicMessages

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | **[]interface{}** |  |
**Model** | Pointer to **string** | A model ID from the models endpoint, or &#x60;default&#x60; to use the workspace coder model. &#x60;hlix/default&#x60; and an omitted model field have the same effect. | [optional]
**Stream** | Pointer to **bool** |  | [optional]

## Methods

### NewAnthropicMessages

`func NewAnthropicMessages(messages []interface{}, ) *AnthropicMessages`

NewAnthropicMessages instantiates a new AnthropicMessages object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAnthropicMessagesWithDefaults

`func NewAnthropicMessagesWithDefaults() *AnthropicMessages`

NewAnthropicMessagesWithDefaults instantiates a new AnthropicMessages object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetMessages

`func (o *AnthropicMessages) GetMessages() []interface{}`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *AnthropicMessages) GetMessagesOk() (*[]interface{}, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *AnthropicMessages) SetMessages(v []interface{})`

SetMessages sets Messages field to given value.


### GetModel

`func (o *AnthropicMessages) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AnthropicMessages) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AnthropicMessages) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AnthropicMessages) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetStream

`func (o *AnthropicMessages) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *AnthropicMessages) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *AnthropicMessages) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *AnthropicMessages) HasStream() bool`

HasStream returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


