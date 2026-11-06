# StartEditBranch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | **string** |  | 
**FromSha** | **string** |  | 
**Repo** | Pointer to **string** |  | [optional] 

## Methods

### NewStartEditBranch

`func NewStartEditBranch(from string, fromSha string, ) *StartEditBranch`

NewStartEditBranch instantiates a new StartEditBranch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStartEditBranchWithDefaults

`func NewStartEditBranchWithDefaults() *StartEditBranch`

NewStartEditBranchWithDefaults instantiates a new StartEditBranch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *StartEditBranch) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *StartEditBranch) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *StartEditBranch) SetFrom(v string)`

SetFrom sets From field to given value.


### GetFromSha

`func (o *StartEditBranch) GetFromSha() string`

GetFromSha returns the FromSha field if non-nil, zero value otherwise.

### GetFromShaOk

`func (o *StartEditBranch) GetFromShaOk() (*string, bool)`

GetFromShaOk returns a tuple with the FromSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromSha

`func (o *StartEditBranch) SetFromSha(v string)`

SetFromSha sets FromSha field to given value.


### GetRepo

`func (o *StartEditBranch) GetRepo() string`

GetRepo returns the Repo field if non-nil, zero value otherwise.

### GetRepoOk

`func (o *StartEditBranch) GetRepoOk() (*string, bool)`

GetRepoOk returns a tuple with the Repo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepo

`func (o *StartEditBranch) SetRepo(v string)`

SetRepo sets Repo field to given value.

### HasRepo

`func (o *StartEditBranch) HasRepo() bool`

HasRepo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


