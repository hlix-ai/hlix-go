# ChatCompletion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Choices** | **[]interface{}** |  |
**Id** | **string** |  |
**Model** | **string** |  |

## Methods

### NewChatCompletion

`func NewChatCompletion(choices []interface{}, id string, model string, ) *ChatCompletion`

NewChatCompletion instantiates a new ChatCompletion object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewChatCompletionWithDefaults

`func NewChatCompletionWithDefaults() *ChatCompletion`

NewChatCompletionWithDefaults instantiates a new ChatCompletion object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetChoices

`func (o *ChatCompletion) GetChoices() []interface{}`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *ChatCompletion) GetChoicesOk() (*[]interface{}, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *ChatCompletion) SetChoices(v []interface{})`

SetChoices sets Choices field to given value.


### GetId

`func (o *ChatCompletion) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChatCompletion) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChatCompletion) SetId(v string)`

SetId sets Id field to given value.


### GetModel

`func (o *ChatCompletion) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ChatCompletion) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ChatCompletion) SetModel(v string)`

SetModel sets Model field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


