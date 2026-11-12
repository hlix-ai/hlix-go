# AiMediaJobRead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Job** | [**AiMediaJobAcceptedJob**](AiMediaJobAcceptedJob.md) |  |
**OutputUrl** | **NullableString** |  |

## Methods

### NewAiMediaJobRead

`func NewAiMediaJobRead(job AiMediaJobAcceptedJob, outputUrl NullableString, ) *AiMediaJobRead`

NewAiMediaJobRead instantiates a new AiMediaJobRead object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAiMediaJobReadWithDefaults

`func NewAiMediaJobReadWithDefaults() *AiMediaJobRead`

NewAiMediaJobReadWithDefaults instantiates a new AiMediaJobRead object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetJob

`func (o *AiMediaJobRead) GetJob() AiMediaJobAcceptedJob`

GetJob returns the Job field if non-nil, zero value otherwise.

### GetJobOk

`func (o *AiMediaJobRead) GetJobOk() (*AiMediaJobAcceptedJob, bool)`

GetJobOk returns a tuple with the Job field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJob

`func (o *AiMediaJobRead) SetJob(v AiMediaJobAcceptedJob)`

SetJob sets Job field to given value.


### GetOutputUrl

`func (o *AiMediaJobRead) GetOutputUrl() string`

GetOutputUrl returns the OutputUrl field if non-nil, zero value otherwise.

### GetOutputUrlOk

`func (o *AiMediaJobRead) GetOutputUrlOk() (*string, bool)`

GetOutputUrlOk returns a tuple with the OutputUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputUrl

`func (o *AiMediaJobRead) SetOutputUrl(v string)`

SetOutputUrl sets OutputUrl field to given value.


### SetOutputUrlNil

`func (o *AiMediaJobRead) SetOutputUrlNil(b bool)`

 SetOutputUrlNil sets the value for OutputUrl to be an explicit nil

### UnsetOutputUrl
`func (o *AiMediaJobRead) UnsetOutputUrl()`

UnsetOutputUrl ensures that no value is present for OutputUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


