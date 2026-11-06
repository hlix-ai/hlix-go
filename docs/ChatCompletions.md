# ChatCompletions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | **[]interface{}** |  | 
**Model** | Pointer to **string** | An OpenRouter model id, or \&quot;default\&quot; for the model this workspace has chosen for its coder (\&quot;hlix/default\&quot; and omitting the field mean the same thing). GET ../models lists every id that may be sent, and names \&quot;default\&quot; as its own. | [optional] 
**Stream** | Pointer to **bool** |  | [optional] 
**StreamOptions** | Pointer to [**ChatCompletionsStreamOptions**](ChatCompletionsStreamOptions.md) |  | [optional] 

## Methods

### NewChatCompletions

`func NewChatCompletions(messages []interface{}, ) *ChatCompletions`

NewChatCompletions instantiates a new ChatCompletions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatCompletionsWithDefaults

`func NewChatCompletionsWithDefaults() *ChatCompletions`

NewChatCompletionsWithDefaults instantiates a new ChatCompletions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessages

`func (o *ChatCompletions) GetMessages() []interface{}`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ChatCompletions) GetMessagesOk() (*[]interface{}, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ChatCompletions) SetMessages(v []interface{})`

SetMessages sets Messages field to given value.


### GetModel

`func (o *ChatCompletions) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ChatCompletions) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ChatCompletions) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *ChatCompletions) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetStream

`func (o *ChatCompletions) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *ChatCompletions) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *ChatCompletions) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *ChatCompletions) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetStreamOptions

`func (o *ChatCompletions) GetStreamOptions() ChatCompletionsStreamOptions`

GetStreamOptions returns the StreamOptions field if non-nil, zero value otherwise.

### GetStreamOptionsOk

`func (o *ChatCompletions) GetStreamOptionsOk() (*ChatCompletionsStreamOptions, bool)`

GetStreamOptionsOk returns a tuple with the StreamOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreamOptions

`func (o *ChatCompletions) SetStreamOptions(v ChatCompletionsStreamOptions)`

SetStreamOptions sets StreamOptions field to given value.

### HasStreamOptions

`func (o *ChatCompletions) HasStreamOptions() bool`

HasStreamOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


