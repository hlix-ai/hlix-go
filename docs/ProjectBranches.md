# ProjectBranches

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Branches** | [**[]ProjectBranchesBranchesInner**](ProjectBranchesBranchesInner.md) |  | 
**DefaultBranch** | **string** |  | 
**PreviewBranch** | **string** |  | 
**RepoKey** | **string** |  | 

## Methods

### NewProjectBranches

`func NewProjectBranches(branches []ProjectBranchesBranchesInner, defaultBranch string, previewBranch string, repoKey string, ) *ProjectBranches`

NewProjectBranches instantiates a new ProjectBranches object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectBranchesWithDefaults

`func NewProjectBranchesWithDefaults() *ProjectBranches`

NewProjectBranchesWithDefaults instantiates a new ProjectBranches object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBranches

`func (o *ProjectBranches) GetBranches() []ProjectBranchesBranchesInner`

GetBranches returns the Branches field if non-nil, zero value otherwise.

### GetBranchesOk

`func (o *ProjectBranches) GetBranchesOk() (*[]ProjectBranchesBranchesInner, bool)`

GetBranchesOk returns a tuple with the Branches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranches

`func (o *ProjectBranches) SetBranches(v []ProjectBranchesBranchesInner)`

SetBranches sets Branches field to given value.


### GetDefaultBranch

`func (o *ProjectBranches) GetDefaultBranch() string`

GetDefaultBranch returns the DefaultBranch field if non-nil, zero value otherwise.

### GetDefaultBranchOk

`func (o *ProjectBranches) GetDefaultBranchOk() (*string, bool)`

GetDefaultBranchOk returns a tuple with the DefaultBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBranch

`func (o *ProjectBranches) SetDefaultBranch(v string)`

SetDefaultBranch sets DefaultBranch field to given value.


### GetPreviewBranch

`func (o *ProjectBranches) GetPreviewBranch() string`

GetPreviewBranch returns the PreviewBranch field if non-nil, zero value otherwise.

### GetPreviewBranchOk

`func (o *ProjectBranches) GetPreviewBranchOk() (*string, bool)`

GetPreviewBranchOk returns a tuple with the PreviewBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewBranch

`func (o *ProjectBranches) SetPreviewBranch(v string)`

SetPreviewBranch sets PreviewBranch field to given value.


### GetRepoKey

`func (o *ProjectBranches) GetRepoKey() string`

GetRepoKey returns the RepoKey field if non-nil, zero value otherwise.

### GetRepoKeyOk

`func (o *ProjectBranches) GetRepoKeyOk() (*string, bool)`

GetRepoKeyOk returns a tuple with the RepoKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoKey

`func (o *ProjectBranches) SetRepoKey(v string)`

SetRepoKey sets RepoKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


