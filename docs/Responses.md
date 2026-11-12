# Responses

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Input** | [**ResponsesInput**](ResponsesInput.md) |  |
**Model** | Pointer to **string** | A model ID from the models endpoint, or &#x60;default&#x60; to use the workspace coder model. &#x60;hlix/default&#x60; and an omitted model field have the same effect. | [optional]
**Stream** | Pointer to **bool** |  | [optional]

## Methods

### NewResponses

`func NewResponses(input ResponsesInput, ) *Responses`

NewResponses instantiates a new Responses object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewResponsesWithDefaults

`func NewResponsesWithDefaults() *Responses`

NewResponsesWithDefaults instantiates a new Responses object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetInput

`func (o *Responses) GetInput() ResponsesInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *Responses) GetInputOk() (*ResponsesInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *Responses) SetInput(v ResponsesInput)`

SetInput sets Input field to given value.


### GetModel

`func (o *Responses) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *Responses) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *Responses) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *Responses) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetStream

`func (o *Responses) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *Responses) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *Responses) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *Responses) HasStream() bool`

HasStream returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


