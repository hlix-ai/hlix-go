# ChangeFilePatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Binary** | **bool** |  |
**Patch** | **NullableString** |  |
**PatchTruncated** | **bool** |  |
**Path** | **string** |  |
**RepoKey** | **string** |  |

## Methods

### NewChangeFilePatch

`func NewChangeFilePatch(binary bool, patch NullableString, patchTruncated bool, path string, repoKey string, ) *ChangeFilePatch`

NewChangeFilePatch instantiates a new ChangeFilePatch object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewChangeFilePatchWithDefaults

`func NewChangeFilePatchWithDefaults() *ChangeFilePatch`

NewChangeFilePatchWithDefaults instantiates a new ChangeFilePatch object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBinary

`func (o *ChangeFilePatch) GetBinary() bool`

GetBinary returns the Binary field if non-nil, zero value otherwise.

### GetBinaryOk

`func (o *ChangeFilePatch) GetBinaryOk() (*bool, bool)`

GetBinaryOk returns a tuple with the Binary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinary

`func (o *ChangeFilePatch) SetBinary(v bool)`

SetBinary sets Binary field to given value.


### GetPatch

`func (o *ChangeFilePatch) GetPatch() string`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *ChangeFilePatch) GetPatchOk() (*string, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *ChangeFilePatch) SetPatch(v string)`

SetPatch sets Patch field to given value.


### SetPatchNil

`func (o *ChangeFilePatch) SetPatchNil(b bool)`

 SetPatchNil sets the value for Patch to be an explicit nil

### UnsetPatch
`func (o *ChangeFilePatch) UnsetPatch()`

UnsetPatch ensures that no value is present for Patch, not even an explicit nil
### GetPatchTruncated

`func (o *ChangeFilePatch) GetPatchTruncated() bool`

GetPatchTruncated returns the PatchTruncated field if non-nil, zero value otherwise.

### GetPatchTruncatedOk

`func (o *ChangeFilePatch) GetPatchTruncatedOk() (*bool, bool)`

GetPatchTruncatedOk returns a tuple with the PatchTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatchTruncated

`func (o *ChangeFilePatch) SetPatchTruncated(v bool)`

SetPatchTruncated sets PatchTruncated field to given value.


### GetPath

`func (o *ChangeFilePatch) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ChangeFilePatch) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ChangeFilePatch) SetPath(v string)`

SetPath sets Path field to given value.


### GetRepoKey

`func (o *ChangeFilePatch) GetRepoKey() string`

GetRepoKey returns the RepoKey field if non-nil, zero value otherwise.

### GetRepoKeyOk

`func (o *ChangeFilePatch) GetRepoKeyOk() (*string, bool)`

GetRepoKeyOk returns a tuple with the RepoKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoKey

`func (o *ChangeFilePatch) SetRepoKey(v string)`

SetRepoKey sets RepoKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


