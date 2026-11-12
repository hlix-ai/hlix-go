# CycleReviewEvidence

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Additions** | **NullableFloat32** |  |
**BaseRef** | **NullableString** |  |
**BaseSha** | **NullableString** |  |
**Commits** | **NullableFloat32** |  |
**Comparison** | [**CycleReviewEvidenceComparison**](CycleReviewEvidenceComparison.md) |  |
**CycleId** | **string** |  |
**Deletions** | **NullableFloat32** |  |
**Evaluator** | [**NullableCycleReviewEvidenceEvaluator**](CycleReviewEvidenceEvaluator.md) |  |
**Files** | [**[]CycleReviewEvidenceFilesInner**](CycleReviewEvidenceFilesInner.md) |  |
**FilesChanged** | **NullableFloat32** |  |
**FilesTruncated** | **bool** |  |
**HeadRef** | **NullableString** |  |
**HeadSha** | **NullableString** |  |
**ObservedAt** | **string** |  |
**RepoId** | **NullableString** |  |
**Source** | **string** |  |

## Methods

### NewCycleReviewEvidence

`func NewCycleReviewEvidence(additions NullableFloat32, baseRef NullableString, baseSha NullableString, commits NullableFloat32, comparison CycleReviewEvidenceComparison, cycleId string, deletions NullableFloat32, evaluator NullableCycleReviewEvidenceEvaluator, files []CycleReviewEvidenceFilesInner, filesChanged NullableFloat32, filesTruncated bool, headRef NullableString, headSha NullableString, observedAt string, repoId NullableString, source string, ) *CycleReviewEvidence`

NewCycleReviewEvidence instantiates a new CycleReviewEvidence object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleReviewEvidenceWithDefaults

`func NewCycleReviewEvidenceWithDefaults() *CycleReviewEvidence`

NewCycleReviewEvidenceWithDefaults instantiates a new CycleReviewEvidence object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAdditions

`func (o *CycleReviewEvidence) GetAdditions() float32`

GetAdditions returns the Additions field if non-nil, zero value otherwise.

### GetAdditionsOk

`func (o *CycleReviewEvidence) GetAdditionsOk() (*float32, bool)`

GetAdditionsOk returns a tuple with the Additions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditions

`func (o *CycleReviewEvidence) SetAdditions(v float32)`

SetAdditions sets Additions field to given value.


### SetAdditionsNil

`func (o *CycleReviewEvidence) SetAdditionsNil(b bool)`

 SetAdditionsNil sets the value for Additions to be an explicit nil

### UnsetAdditions
`func (o *CycleReviewEvidence) UnsetAdditions()`

UnsetAdditions ensures that no value is present for Additions, not even an explicit nil
### GetBaseRef

`func (o *CycleReviewEvidence) GetBaseRef() string`

GetBaseRef returns the BaseRef field if non-nil, zero value otherwise.

### GetBaseRefOk

`func (o *CycleReviewEvidence) GetBaseRefOk() (*string, bool)`

GetBaseRefOk returns a tuple with the BaseRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseRef

`func (o *CycleReviewEvidence) SetBaseRef(v string)`

SetBaseRef sets BaseRef field to given value.


### SetBaseRefNil

`func (o *CycleReviewEvidence) SetBaseRefNil(b bool)`

 SetBaseRefNil sets the value for BaseRef to be an explicit nil

### UnsetBaseRef
`func (o *CycleReviewEvidence) UnsetBaseRef()`

UnsetBaseRef ensures that no value is present for BaseRef, not even an explicit nil
### GetBaseSha

`func (o *CycleReviewEvidence) GetBaseSha() string`

GetBaseSha returns the BaseSha field if non-nil, zero value otherwise.

### GetBaseShaOk

`func (o *CycleReviewEvidence) GetBaseShaOk() (*string, bool)`

GetBaseShaOk returns a tuple with the BaseSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseSha

`func (o *CycleReviewEvidence) SetBaseSha(v string)`

SetBaseSha sets BaseSha field to given value.


### SetBaseShaNil

`func (o *CycleReviewEvidence) SetBaseShaNil(b bool)`

 SetBaseShaNil sets the value for BaseSha to be an explicit nil

### UnsetBaseSha
`func (o *CycleReviewEvidence) UnsetBaseSha()`

UnsetBaseSha ensures that no value is present for BaseSha, not even an explicit nil
### GetCommits

`func (o *CycleReviewEvidence) GetCommits() float32`

GetCommits returns the Commits field if non-nil, zero value otherwise.

### GetCommitsOk

`func (o *CycleReviewEvidence) GetCommitsOk() (*float32, bool)`

GetCommitsOk returns a tuple with the Commits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommits

`func (o *CycleReviewEvidence) SetCommits(v float32)`

SetCommits sets Commits field to given value.


### SetCommitsNil

`func (o *CycleReviewEvidence) SetCommitsNil(b bool)`

 SetCommitsNil sets the value for Commits to be an explicit nil

### UnsetCommits
`func (o *CycleReviewEvidence) UnsetCommits()`

UnsetCommits ensures that no value is present for Commits, not even an explicit nil
### GetComparison

`func (o *CycleReviewEvidence) GetComparison() CycleReviewEvidenceComparison`

GetComparison returns the Comparison field if non-nil, zero value otherwise.

### GetComparisonOk

`func (o *CycleReviewEvidence) GetComparisonOk() (*CycleReviewEvidenceComparison, bool)`

GetComparisonOk returns a tuple with the Comparison field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComparison

`func (o *CycleReviewEvidence) SetComparison(v CycleReviewEvidenceComparison)`

SetComparison sets Comparison field to given value.


### GetCycleId

`func (o *CycleReviewEvidence) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *CycleReviewEvidence) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *CycleReviewEvidence) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetDeletions

`func (o *CycleReviewEvidence) GetDeletions() float32`

GetDeletions returns the Deletions field if non-nil, zero value otherwise.

### GetDeletionsOk

`func (o *CycleReviewEvidence) GetDeletionsOk() (*float32, bool)`

GetDeletionsOk returns a tuple with the Deletions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletions

`func (o *CycleReviewEvidence) SetDeletions(v float32)`

SetDeletions sets Deletions field to given value.


### SetDeletionsNil

`func (o *CycleReviewEvidence) SetDeletionsNil(b bool)`

 SetDeletionsNil sets the value for Deletions to be an explicit nil

### UnsetDeletions
`func (o *CycleReviewEvidence) UnsetDeletions()`

UnsetDeletions ensures that no value is present for Deletions, not even an explicit nil
### GetEvaluator

`func (o *CycleReviewEvidence) GetEvaluator() CycleReviewEvidenceEvaluator`

GetEvaluator returns the Evaluator field if non-nil, zero value otherwise.

### GetEvaluatorOk

`func (o *CycleReviewEvidence) GetEvaluatorOk() (*CycleReviewEvidenceEvaluator, bool)`

GetEvaluatorOk returns a tuple with the Evaluator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvaluator

`func (o *CycleReviewEvidence) SetEvaluator(v CycleReviewEvidenceEvaluator)`

SetEvaluator sets Evaluator field to given value.


### SetEvaluatorNil

`func (o *CycleReviewEvidence) SetEvaluatorNil(b bool)`

 SetEvaluatorNil sets the value for Evaluator to be an explicit nil

### UnsetEvaluator
`func (o *CycleReviewEvidence) UnsetEvaluator()`

UnsetEvaluator ensures that no value is present for Evaluator, not even an explicit nil
### GetFiles

`func (o *CycleReviewEvidence) GetFiles() []CycleReviewEvidenceFilesInner`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *CycleReviewEvidence) GetFilesOk() (*[]CycleReviewEvidenceFilesInner, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *CycleReviewEvidence) SetFiles(v []CycleReviewEvidenceFilesInner)`

SetFiles sets Files field to given value.


### GetFilesChanged

`func (o *CycleReviewEvidence) GetFilesChanged() float32`

GetFilesChanged returns the FilesChanged field if non-nil, zero value otherwise.

### GetFilesChangedOk

`func (o *CycleReviewEvidence) GetFilesChangedOk() (*float32, bool)`

GetFilesChangedOk returns a tuple with the FilesChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesChanged

`func (o *CycleReviewEvidence) SetFilesChanged(v float32)`

SetFilesChanged sets FilesChanged field to given value.


### SetFilesChangedNil

`func (o *CycleReviewEvidence) SetFilesChangedNil(b bool)`

 SetFilesChangedNil sets the value for FilesChanged to be an explicit nil

### UnsetFilesChanged
`func (o *CycleReviewEvidence) UnsetFilesChanged()`

UnsetFilesChanged ensures that no value is present for FilesChanged, not even an explicit nil
### GetFilesTruncated

`func (o *CycleReviewEvidence) GetFilesTruncated() bool`

GetFilesTruncated returns the FilesTruncated field if non-nil, zero value otherwise.

### GetFilesTruncatedOk

`func (o *CycleReviewEvidence) GetFilesTruncatedOk() (*bool, bool)`

GetFilesTruncatedOk returns a tuple with the FilesTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesTruncated

`func (o *CycleReviewEvidence) SetFilesTruncated(v bool)`

SetFilesTruncated sets FilesTruncated field to given value.


### GetHeadRef

`func (o *CycleReviewEvidence) GetHeadRef() string`

GetHeadRef returns the HeadRef field if non-nil, zero value otherwise.

### GetHeadRefOk

`func (o *CycleReviewEvidence) GetHeadRefOk() (*string, bool)`

GetHeadRefOk returns a tuple with the HeadRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadRef

`func (o *CycleReviewEvidence) SetHeadRef(v string)`

SetHeadRef sets HeadRef field to given value.


### SetHeadRefNil

`func (o *CycleReviewEvidence) SetHeadRefNil(b bool)`

 SetHeadRefNil sets the value for HeadRef to be an explicit nil

### UnsetHeadRef
`func (o *CycleReviewEvidence) UnsetHeadRef()`

UnsetHeadRef ensures that no value is present for HeadRef, not even an explicit nil
### GetHeadSha

`func (o *CycleReviewEvidence) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *CycleReviewEvidence) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *CycleReviewEvidence) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### SetHeadShaNil

`func (o *CycleReviewEvidence) SetHeadShaNil(b bool)`

 SetHeadShaNil sets the value for HeadSha to be an explicit nil

### UnsetHeadSha
`func (o *CycleReviewEvidence) UnsetHeadSha()`

UnsetHeadSha ensures that no value is present for HeadSha, not even an explicit nil
### GetObservedAt

`func (o *CycleReviewEvidence) GetObservedAt() string`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *CycleReviewEvidence) GetObservedAtOk() (*string, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *CycleReviewEvidence) SetObservedAt(v string)`

SetObservedAt sets ObservedAt field to given value.


### GetRepoId

`func (o *CycleReviewEvidence) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *CycleReviewEvidence) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *CycleReviewEvidence) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.


### SetRepoIdNil

`func (o *CycleReviewEvidence) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *CycleReviewEvidence) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetSource

`func (o *CycleReviewEvidence) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CycleReviewEvidence) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CycleReviewEvidence) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


