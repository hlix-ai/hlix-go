# SynthesizeSpeech

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **string** |  | [optional] 
**Speed** | Pointer to **float32** |  | [optional] 
**Text** | **string** |  | 
**Voice** | **string** |  | 

## Methods

### NewSynthesizeSpeech

`func NewSynthesizeSpeech(text string, voice string, ) *SynthesizeSpeech`

NewSynthesizeSpeech instantiates a new SynthesizeSpeech object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSynthesizeSpeechWithDefaults

`func NewSynthesizeSpeechWithDefaults() *SynthesizeSpeech`

NewSynthesizeSpeechWithDefaults instantiates a new SynthesizeSpeech object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormat

`func (o *SynthesizeSpeech) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *SynthesizeSpeech) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *SynthesizeSpeech) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *SynthesizeSpeech) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetProjectId

`func (o *SynthesizeSpeech) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SynthesizeSpeech) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SynthesizeSpeech) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SynthesizeSpeech) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSpeed

`func (o *SynthesizeSpeech) GetSpeed() float32`

GetSpeed returns the Speed field if non-nil, zero value otherwise.

### GetSpeedOk

`func (o *SynthesizeSpeech) GetSpeedOk() (*float32, bool)`

GetSpeedOk returns a tuple with the Speed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpeed

`func (o *SynthesizeSpeech) SetSpeed(v float32)`

SetSpeed sets Speed field to given value.

### HasSpeed

`func (o *SynthesizeSpeech) HasSpeed() bool`

HasSpeed returns a boolean if a field has been set.

### GetText

`func (o *SynthesizeSpeech) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SynthesizeSpeech) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SynthesizeSpeech) SetText(v string)`

SetText sets Text field to given value.


### GetVoice

`func (o *SynthesizeSpeech) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *SynthesizeSpeech) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *SynthesizeSpeech) SetVoice(v string)`

SetVoice sets Voice field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


