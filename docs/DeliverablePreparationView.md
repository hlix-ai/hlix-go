# DeliverablePreparationView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Applied** | **bool** |  |
**CreatedAt** | **string** |  |
**DeliverableId** | **string** |  |
**Error** | **NullableString** |  |
**FinishedAt** | **NullableString** |  |
**Id** | **string** |  |
**RecordingUrl** | **NullableString** |  |
**Result** | [**NullableDeliverablePreparationViewResult**](DeliverablePreparationViewResult.md) |  |
**SourceSha** | **string** |  |
**Stage** | **string** |  |
**Status** | **string** |  |
**VerificationTarget** | **string** |  |

## Methods

### NewDeliverablePreparationView

`func NewDeliverablePreparationView(applied bool, createdAt string, deliverableId string, error_ NullableString, finishedAt NullableString, id string, recordingUrl NullableString, result NullableDeliverablePreparationViewResult, sourceSha string, stage string, status string, verificationTarget string, ) *DeliverablePreparationView`

NewDeliverablePreparationView instantiates a new DeliverablePreparationView object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeliverablePreparationViewWithDefaults

`func NewDeliverablePreparationViewWithDefaults() *DeliverablePreparationView`

NewDeliverablePreparationViewWithDefaults instantiates a new DeliverablePreparationView object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApplied

`func (o *DeliverablePreparationView) GetApplied() bool`

GetApplied returns the Applied field if non-nil, zero value otherwise.

### GetAppliedOk

`func (o *DeliverablePreparationView) GetAppliedOk() (*bool, bool)`

GetAppliedOk returns a tuple with the Applied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplied

`func (o *DeliverablePreparationView) SetApplied(v bool)`

SetApplied sets Applied field to given value.


### GetCreatedAt

`func (o *DeliverablePreparationView) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DeliverablePreparationView) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DeliverablePreparationView) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDeliverableId

`func (o *DeliverablePreparationView) GetDeliverableId() string`

GetDeliverableId returns the DeliverableId field if non-nil, zero value otherwise.

### GetDeliverableIdOk

`func (o *DeliverablePreparationView) GetDeliverableIdOk() (*string, bool)`

GetDeliverableIdOk returns a tuple with the DeliverableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverableId

`func (o *DeliverablePreparationView) SetDeliverableId(v string)`

SetDeliverableId sets DeliverableId field to given value.


### GetError

`func (o *DeliverablePreparationView) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DeliverablePreparationView) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DeliverablePreparationView) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *DeliverablePreparationView) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *DeliverablePreparationView) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFinishedAt

`func (o *DeliverablePreparationView) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *DeliverablePreparationView) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *DeliverablePreparationView) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.


### SetFinishedAtNil

`func (o *DeliverablePreparationView) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *DeliverablePreparationView) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetId

`func (o *DeliverablePreparationView) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeliverablePreparationView) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeliverablePreparationView) SetId(v string)`

SetId sets Id field to given value.


### GetRecordingUrl

`func (o *DeliverablePreparationView) GetRecordingUrl() string`

GetRecordingUrl returns the RecordingUrl field if non-nil, zero value otherwise.

### GetRecordingUrlOk

`func (o *DeliverablePreparationView) GetRecordingUrlOk() (*string, bool)`

GetRecordingUrlOk returns a tuple with the RecordingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordingUrl

`func (o *DeliverablePreparationView) SetRecordingUrl(v string)`

SetRecordingUrl sets RecordingUrl field to given value.


### SetRecordingUrlNil

`func (o *DeliverablePreparationView) SetRecordingUrlNil(b bool)`

 SetRecordingUrlNil sets the value for RecordingUrl to be an explicit nil

### UnsetRecordingUrl
`func (o *DeliverablePreparationView) UnsetRecordingUrl()`

UnsetRecordingUrl ensures that no value is present for RecordingUrl, not even an explicit nil
### GetResult

`func (o *DeliverablePreparationView) GetResult() DeliverablePreparationViewResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *DeliverablePreparationView) GetResultOk() (*DeliverablePreparationViewResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *DeliverablePreparationView) SetResult(v DeliverablePreparationViewResult)`

SetResult sets Result field to given value.


### SetResultNil

`func (o *DeliverablePreparationView) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *DeliverablePreparationView) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetSourceSha

`func (o *DeliverablePreparationView) GetSourceSha() string`

GetSourceSha returns the SourceSha field if non-nil, zero value otherwise.

### GetSourceShaOk

`func (o *DeliverablePreparationView) GetSourceShaOk() (*string, bool)`

GetSourceShaOk returns a tuple with the SourceSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceSha

`func (o *DeliverablePreparationView) SetSourceSha(v string)`

SetSourceSha sets SourceSha field to given value.


### GetStage

`func (o *DeliverablePreparationView) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *DeliverablePreparationView) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *DeliverablePreparationView) SetStage(v string)`

SetStage sets Stage field to given value.


### GetStatus

`func (o *DeliverablePreparationView) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliverablePreparationView) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliverablePreparationView) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetVerificationTarget

`func (o *DeliverablePreparationView) GetVerificationTarget() string`

GetVerificationTarget returns the VerificationTarget field if non-nil, zero value otherwise.

### GetVerificationTargetOk

`func (o *DeliverablePreparationView) GetVerificationTargetOk() (*string, bool)`

GetVerificationTargetOk returns a tuple with the VerificationTarget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerificationTarget

`func (o *DeliverablePreparationView) SetVerificationTarget(v string)`

SetVerificationTarget sets VerificationTarget field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


