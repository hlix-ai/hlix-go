# ProjectCommandDetectionReposInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Detected** | [**NullableProjectCommandDetectionProjectDetected**](ProjectCommandDetectionProjectDetected.md) |  |
**Reason** | **string** |  |
**RepoId** | **string** |  |

## Methods

### NewProjectCommandDetectionReposInner

`func NewProjectCommandDetectionReposInner(detected NullableProjectCommandDetectionProjectDetected, reason string, repoId string, ) *ProjectCommandDetectionReposInner`

NewProjectCommandDetectionReposInner instantiates a new ProjectCommandDetectionReposInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectCommandDetectionReposInnerWithDefaults

`func NewProjectCommandDetectionReposInnerWithDefaults() *ProjectCommandDetectionReposInner`

NewProjectCommandDetectionReposInnerWithDefaults instantiates a new ProjectCommandDetectionReposInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDetected

`func (o *ProjectCommandDetectionReposInner) GetDetected() ProjectCommandDetectionProjectDetected`

GetDetected returns the Detected field if non-nil, zero value otherwise.

### GetDetectedOk

`func (o *ProjectCommandDetectionReposInner) GetDetectedOk() (*ProjectCommandDetectionProjectDetected, bool)`

GetDetectedOk returns a tuple with the Detected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetected

`func (o *ProjectCommandDetectionReposInner) SetDetected(v ProjectCommandDetectionProjectDetected)`

SetDetected sets Detected field to given value.


### SetDetectedNil

`func (o *ProjectCommandDetectionReposInner) SetDetectedNil(b bool)`

 SetDetectedNil sets the value for Detected to be an explicit nil

### UnsetDetected
`func (o *ProjectCommandDetectionReposInner) UnsetDetected()`

UnsetDetected ensures that no value is present for Detected, not even an explicit nil
### GetReason

`func (o *ProjectCommandDetectionReposInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ProjectCommandDetectionReposInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ProjectCommandDetectionReposInner) SetReason(v string)`

SetReason sets Reason field to given value.


### GetRepoId

`func (o *ProjectCommandDetectionReposInner) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *ProjectCommandDetectionReposInner) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *ProjectCommandDetectionReposInner) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


