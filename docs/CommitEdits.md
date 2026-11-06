# CommitEdits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Files** | [**[]CommitEditsFilesInner**](CommitEditsFilesInner.md) |  | 
**HeadSha** | **string** |  | 
**Message** | **string** |  | 
**Ref** | **string** |  | 
**Repo** | Pointer to **string** |  | [optional] 

## Methods

### NewCommitEdits

`func NewCommitEdits(files []CommitEditsFilesInner, headSha string, message string, ref string, ) *CommitEdits`

NewCommitEdits instantiates a new CommitEdits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCommitEditsWithDefaults

`func NewCommitEditsWithDefaults() *CommitEdits`

NewCommitEditsWithDefaults instantiates a new CommitEdits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFiles

`func (o *CommitEdits) GetFiles() []CommitEditsFilesInner`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *CommitEdits) GetFilesOk() (*[]CommitEditsFilesInner, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *CommitEdits) SetFiles(v []CommitEditsFilesInner)`

SetFiles sets Files field to given value.


### GetHeadSha

`func (o *CommitEdits) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *CommitEdits) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *CommitEdits) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### GetMessage

`func (o *CommitEdits) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CommitEdits) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CommitEdits) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRef

`func (o *CommitEdits) GetRef() string`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *CommitEdits) GetRefOk() (*string, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *CommitEdits) SetRef(v string)`

SetRef sets Ref field to given value.


### GetRepo

`func (o *CommitEdits) GetRepo() string`

GetRepo returns the Repo field if non-nil, zero value otherwise.

### GetRepoOk

`func (o *CommitEdits) GetRepoOk() (*string, bool)`

GetRepoOk returns a tuple with the Repo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepo

`func (o *CommitEdits) SetRepo(v string)`

SetRepo sets Repo field to given value.

### HasRepo

`func (o *CommitEdits) HasRepo() bool`

HasRepo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


