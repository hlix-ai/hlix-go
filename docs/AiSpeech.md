# AiSpeech

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | **string** |  |
**CorrelationId** | **string** |  |
**Key** | **string** |  |
**Model** | **string** |  |
**Provider** | Pointer to **string** |  | [optional]
**Url** | **string** |  |
**Usage** | Pointer to [**AiGeneratedImagesUsage**](AiGeneratedImagesUsage.md) |  | [optional]

## Methods

### NewAiSpeech

`func NewAiSpeech(contentType string, correlationId string, key string, model string, url string, ) *AiSpeech`

NewAiSpeech instantiates a new AiSpeech object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAiSpeechWithDefaults

`func NewAiSpeechWithDefaults() *AiSpeech`

NewAiSpeechWithDefaults instantiates a new AiSpeech object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetContentType

`func (o *AiSpeech) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *AiSpeech) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *AiSpeech) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetCorrelationId

`func (o *AiSpeech) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AiSpeech) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AiSpeech) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetKey

`func (o *AiSpeech) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AiSpeech) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AiSpeech) SetKey(v string)`

SetKey sets Key field to given value.


### GetModel

`func (o *AiSpeech) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiSpeech) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiSpeech) SetModel(v string)`

SetModel sets Model field to given value.


### GetProvider

`func (o *AiSpeech) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AiSpeech) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AiSpeech) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *AiSpeech) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetUrl

`func (o *AiSpeech) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AiSpeech) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AiSpeech) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetUsage

`func (o *AiSpeech) GetUsage() AiGeneratedImagesUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AiSpeech) GetUsageOk() (*AiGeneratedImagesUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AiSpeech) SetUsage(v AiGeneratedImagesUsage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *AiSpeech) HasUsage() bool`

HasUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


