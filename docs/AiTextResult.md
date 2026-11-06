# AiTextResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CorrelationId** | **string** |  | 
**Model** | **string** |  | 
**Provider** | Pointer to **string** |  | [optional] 
**Text** | **string** |  | 
**Usage** | [**AiGeneratedImagesUsage**](AiGeneratedImagesUsage.md) |  | 

## Methods

### NewAiTextResult

`func NewAiTextResult(correlationId string, model string, text string, usage AiGeneratedImagesUsage, ) *AiTextResult`

NewAiTextResult instantiates a new AiTextResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiTextResultWithDefaults

`func NewAiTextResultWithDefaults() *AiTextResult`

NewAiTextResultWithDefaults instantiates a new AiTextResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCorrelationId

`func (o *AiTextResult) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AiTextResult) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AiTextResult) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetModel

`func (o *AiTextResult) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiTextResult) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiTextResult) SetModel(v string)`

SetModel sets Model field to given value.


### GetProvider

`func (o *AiTextResult) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AiTextResult) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AiTextResult) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *AiTextResult) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetText

`func (o *AiTextResult) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *AiTextResult) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *AiTextResult) SetText(v string)`

SetText sets Text field to given value.


### GetUsage

`func (o *AiTextResult) GetUsage() AiGeneratedImagesUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AiTextResult) GetUsageOk() (*AiGeneratedImagesUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AiTextResult) SetUsage(v AiGeneratedImagesUsage)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


