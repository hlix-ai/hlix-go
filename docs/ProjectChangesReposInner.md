# ProjectChangesReposInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Additions** | **float32** |  | 
**Base** | [**FileContentRef**](FileContentRef.md) |  | 
**Commits** | [**[]ProjectChangesReposInnerCommitsInner**](ProjectChangesReposInnerCommitsInner.md) |  | 
**Deletions** | **float32** |  | 
**Files** | [**[]ProjectChangesInFlightInnerFilesInner**](ProjectChangesInFlightInnerFilesInner.md) |  | 
**FilesChanged** | **float32** |  | 
**FilesTruncated** | **bool** |  | 
**Head** | [**FileContentRef**](FileContentRef.md) |  | 
**Label** | **string** |  | 
**NextPage** | Pointer to **NullableInt32** |  | [optional] 
**RepoKey** | **string** |  | 
**Unavailable** | **NullableString** |  | 

## Methods

### NewProjectChangesReposInner

`func NewProjectChangesReposInner(additions float32, base FileContentRef, commits []ProjectChangesReposInnerCommitsInner, deletions float32, files []ProjectChangesInFlightInnerFilesInner, filesChanged float32, filesTruncated bool, head FileContentRef, label string, repoKey string, unavailable NullableString, ) *ProjectChangesReposInner`

NewProjectChangesReposInner instantiates a new ProjectChangesReposInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectChangesReposInnerWithDefaults

`func NewProjectChangesReposInnerWithDefaults() *ProjectChangesReposInner`

NewProjectChangesReposInnerWithDefaults instantiates a new ProjectChangesReposInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdditions

`func (o *ProjectChangesReposInner) GetAdditions() float32`

GetAdditions returns the Additions field if non-nil, zero value otherwise.

### GetAdditionsOk

`func (o *ProjectChangesReposInner) GetAdditionsOk() (*float32, bool)`

GetAdditionsOk returns a tuple with the Additions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditions

`func (o *ProjectChangesReposInner) SetAdditions(v float32)`

SetAdditions sets Additions field to given value.


### GetBase

`func (o *ProjectChangesReposInner) GetBase() FileContentRef`

GetBase returns the Base field if non-nil, zero value otherwise.

### GetBaseOk

`func (o *ProjectChangesReposInner) GetBaseOk() (*FileContentRef, bool)`

GetBaseOk returns a tuple with the Base field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBase

`func (o *ProjectChangesReposInner) SetBase(v FileContentRef)`

SetBase sets Base field to given value.


### GetCommits

`func (o *ProjectChangesReposInner) GetCommits() []ProjectChangesReposInnerCommitsInner`

GetCommits returns the Commits field if non-nil, zero value otherwise.

### GetCommitsOk

`func (o *ProjectChangesReposInner) GetCommitsOk() (*[]ProjectChangesReposInnerCommitsInner, bool)`

GetCommitsOk returns a tuple with the Commits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommits

`func (o *ProjectChangesReposInner) SetCommits(v []ProjectChangesReposInnerCommitsInner)`

SetCommits sets Commits field to given value.


### GetDeletions

`func (o *ProjectChangesReposInner) GetDeletions() float32`

GetDeletions returns the Deletions field if non-nil, zero value otherwise.

### GetDeletionsOk

`func (o *ProjectChangesReposInner) GetDeletionsOk() (*float32, bool)`

GetDeletionsOk returns a tuple with the Deletions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletions

`func (o *ProjectChangesReposInner) SetDeletions(v float32)`

SetDeletions sets Deletions field to given value.


### GetFiles

`func (o *ProjectChangesReposInner) GetFiles() []ProjectChangesInFlightInnerFilesInner`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *ProjectChangesReposInner) GetFilesOk() (*[]ProjectChangesInFlightInnerFilesInner, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *ProjectChangesReposInner) SetFiles(v []ProjectChangesInFlightInnerFilesInner)`

SetFiles sets Files field to given value.


### GetFilesChanged

`func (o *ProjectChangesReposInner) GetFilesChanged() float32`

GetFilesChanged returns the FilesChanged field if non-nil, zero value otherwise.

### GetFilesChangedOk

`func (o *ProjectChangesReposInner) GetFilesChangedOk() (*float32, bool)`

GetFilesChangedOk returns a tuple with the FilesChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesChanged

`func (o *ProjectChangesReposInner) SetFilesChanged(v float32)`

SetFilesChanged sets FilesChanged field to given value.


### GetFilesTruncated

`func (o *ProjectChangesReposInner) GetFilesTruncated() bool`

GetFilesTruncated returns the FilesTruncated field if non-nil, zero value otherwise.

### GetFilesTruncatedOk

`func (o *ProjectChangesReposInner) GetFilesTruncatedOk() (*bool, bool)`

GetFilesTruncatedOk returns a tuple with the FilesTruncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilesTruncated

`func (o *ProjectChangesReposInner) SetFilesTruncated(v bool)`

SetFilesTruncated sets FilesTruncated field to given value.


### GetHead

`func (o *ProjectChangesReposInner) GetHead() FileContentRef`

GetHead returns the Head field if non-nil, zero value otherwise.

### GetHeadOk

`func (o *ProjectChangesReposInner) GetHeadOk() (*FileContentRef, bool)`

GetHeadOk returns a tuple with the Head field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHead

`func (o *ProjectChangesReposInner) SetHead(v FileContentRef)`

SetHead sets Head field to given value.


### GetLabel

`func (o *ProjectChangesReposInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ProjectChangesReposInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ProjectChangesReposInner) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetNextPage

`func (o *ProjectChangesReposInner) GetNextPage() int32`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *ProjectChangesReposInner) GetNextPageOk() (*int32, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *ProjectChangesReposInner) SetNextPage(v int32)`

SetNextPage sets NextPage field to given value.

### HasNextPage

`func (o *ProjectChangesReposInner) HasNextPage() bool`

HasNextPage returns a boolean if a field has been set.

### SetNextPageNil

`func (o *ProjectChangesReposInner) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *ProjectChangesReposInner) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil
### GetRepoKey

`func (o *ProjectChangesReposInner) GetRepoKey() string`

GetRepoKey returns the RepoKey field if non-nil, zero value otherwise.

### GetRepoKeyOk

`func (o *ProjectChangesReposInner) GetRepoKeyOk() (*string, bool)`

GetRepoKeyOk returns a tuple with the RepoKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoKey

`func (o *ProjectChangesReposInner) SetRepoKey(v string)`

SetRepoKey sets RepoKey field to given value.


### GetUnavailable

`func (o *ProjectChangesReposInner) GetUnavailable() string`

GetUnavailable returns the Unavailable field if non-nil, zero value otherwise.

### GetUnavailableOk

`func (o *ProjectChangesReposInner) GetUnavailableOk() (*string, bool)`

GetUnavailableOk returns a tuple with the Unavailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnavailable

`func (o *ProjectChangesReposInner) SetUnavailable(v string)`

SetUnavailable sets Unavailable field to given value.


### SetUnavailableNil

`func (o *ProjectChangesReposInner) SetUnavailableNil(b bool)`

 SetUnavailableNil sets the value for Unavailable to be an explicit nil

### UnsetUnavailable
`func (o *ProjectChangesReposInner) UnsetUnavailable()`

UnsetUnavailable ensures that no value is present for Unavailable, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


