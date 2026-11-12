# CycleReviewEvidenceFilesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Additions** | **NullableFloat32** |  |
**Deletions** | **NullableFloat32** |  |
**Patch** | **NullableString** |  |
**PatchTruncated** | **bool** |  |
**Path** | **string** |  |
**PreviousPath** | **NullableString** |  |
**Status** | **string** |  |

## Methods

### NewCycleReviewEvidenceFilesInner

`func NewCycleReviewEvidenceFilesInner(additions NullableFloat32, deletions NullableFloat32, patch NullableString, patchTruncated bool, path string, previousPath NullableString, status string, ) *CycleReviewEvidenceFilesInner`

NewCycleReviewEvidenceFilesInner instantiates a new CycleReviewEvidenceFilesInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleReviewEvidenceFilesInnerWithDefaults

`func NewCycleReviewEvidenceFilesInnerWithDefaults() *CycleReviewEvidenceFilesInner`

NewCycleReviewEvidenceFilesInnerWithDefaults instantiates a new CycleReviewEvidenceFilesInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAdditions

`func (o *CycleReviewEvidenceFilesInner) GetAdditions() float32`

GetAdditions returns the Additions field if non-nil, zero value otherwise.

### GetAdditionsOk

`func (o *CycleReviewEvidenceFilesInner) GetAdditionsOk() (*float32, bool)`

GetAdditionsOk returns a tuple with the Additions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditions

`func (o *CycleReviewEvidenceFilesInner) SetAdditions(v float32)`

SetAdditions sets Additions field to given value.


### SetAdditionsNil

`func (o *CycleReviewEvidenceFilesInner) SetAdditionsNil(b bool)`

 SetAdditionsNil sets the value for Additions to be an explicit nil

### UnsetAdditions
`func (o *CycleReviewEvidenceFilesInner) UnsetAdditions()`

UnsetAdditions ensures that no value is present for Additions, not even an explicit nil
### GetDeletions

`func (o *CycleReviewEvidenceFilesInner) GetDeletions() float32`

GetDeletions returns the Deletions field if non-nil, zero value otherwise.

### GetDeletionsOk

`func (o *CycleReviewEvidenceFilesInner) GetDeletionsOk() (*float32, bool)`

GetDeletionsOk returns a tuple with the Deletions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletions

`func (o *CycleReviewEvidenceFilesInner) SetDeletions(v float32)`

SetDeletions sets Deletions field to given value.


### SetDeletionsNil

`func (o *CycleReviewEvidenceFilesInner) SetDeletionsNil(b bool)`

 SetDeletionsNil sets the value for Deletions to be an explicit nil

### UnsetDeletions
`func (o *CycleReviewEvidenceFilesInner) UnsetDeletions()`

UnsetDeletions ensures that no value is present for Deletions, not even an explicit nil
### GetPatch

`func (o *CycleReviewEvidenceFilesInner) GetPatch() string`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *CycleReviewEvidenceFilesInner) GetPatchOk() (*string, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *CycleReviewEvidenceFilesInner) SetPatch(v string)`

SetPatch sets Patch field to given value.


### SetPatchNil

`func (o *CycleReviewEvidenceFilesInner) SetPatchNil(b bool)`

 SetPatchNil sets the value for Patch to be an explicit nil

### UnsetPatch
`func (o *CycleReviewEvidenceFilesInner) UnsetPatch()`

UnsetPatch ensures that no value is present for Patch, not even an explicit nil
### GetPatchTruncated

`func (o *CycleReviewEvidenceFilesInner) GetPatchTruncated() bool`

GetPatchTruncated returns the PatchTruncated field if non-nil, zero value otherwise.

### GetPatchTruncatedOk

`func (o *CycleReviewEvidenceFilesInner) GetPatchTruncatedOk() (*bool, bool)`

GetPatchTruncatedOk returns a tuple with the PatchTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchTruncated

`func (o *CycleReviewEvidenceFilesInner) SetPatchTruncated(v bool)`

SetPatchTruncated sets PatchTruncated field to given value.


### GetPath

`func (o *CycleReviewEvidenceFilesInner) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *CycleReviewEvidenceFilesInner) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *CycleReviewEvidenceFilesInner) SetPath(v string)`

SetPath sets Path field to given value.


### GetPreviousPath

`func (o *CycleReviewEvidenceFilesInner) GetPreviousPath() string`

GetPreviousPath returns the PreviousPath field if non-nil, zero value otherwise.

### GetPreviousPathOk

`func (o *CycleReviewEvidenceFilesInner) GetPreviousPathOk() (*string, bool)`

GetPreviousPathOk returns a tuple with the PreviousPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousPath

`func (o *CycleReviewEvidenceFilesInner) SetPreviousPath(v string)`

SetPreviousPath sets PreviousPath field to given value.


### SetPreviousPathNil

`func (o *CycleReviewEvidenceFilesInner) SetPreviousPathNil(b bool)`

 SetPreviousPathNil sets the value for PreviousPath to be an explicit nil

### UnsetPreviousPath
`func (o *CycleReviewEvidenceFilesInner) UnsetPreviousPath()`

UnsetPreviousPath ensures that no value is present for PreviousPath, not even an explicit nil
### GetStatus

`func (o *CycleReviewEvidenceFilesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleReviewEvidenceFilesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleReviewEvidenceFilesInner) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


