# AnthropicMessages

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | **[]interface{}** |  | 
**Model** | Pointer to **string** | An OpenRouter model id, or \&quot;default\&quot; for the model this workspace has chosen for its coder (\&quot;hlix/default\&quot; and omitting the field mean the same thing). GET ../models lists every id that may be sent, and names \&quot;default\&quot; as its own. | [optional] 
**Stream** | Pointer to **bool** |  | [optional] 

## Methods

### NewAnthropicMessages

`func NewAnthropicMessages(messages []interface{}, ) *AnthropicMessages`

NewAnthropicMessages instantiates a new AnthropicMessages object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnthropicMessagesWithDefaults

`func NewAnthropicMessagesWithDefaults() *AnthropicMessages`

NewAnthropicMessagesWithDefaults instantiates a new AnthropicMessages object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


