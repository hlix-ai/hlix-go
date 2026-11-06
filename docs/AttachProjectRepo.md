# AttachProjectRepo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CloneUrl** | **string** |  | 
**DefaultBranch** | Pointer to **string** |  | [optional] 
**GithubInstallationId** | Pointer to **NullableString** |  | [optional] 
**GithubRepoId** | Pointer to **NullableInt32** |  | [optional] 
**IsPrimary** | Pointer to **bool** |  | [optional] 
**Label** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Owner** | **string** |  | 
**Provider** | Pointer to **string** |  | [optional] 

## Methods

### NewAttachProjectRepo

`func NewAttachProjectRepo(cloneUrl string, name string, owner string, ) *AttachProjectRepo`

NewAttachProjectRepo instantiates a new AttachProjectRepo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAttachProjectRepoWithDefaults

`func NewAttachProjectRepoWithDefaults() *AttachProjectRepo`

NewAttachProjectRepoWithDefaults instantiates a new AttachProjectRepo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCloneUrl

`func (o *AttachProjectRepo) GetCloneUrl() string`

GetCloneUrl returns the CloneUrl field if non-nil, zero value otherwise.

### GetCloneUrlOk

`func (o *AttachProjectRepo) GetCloneUrlOk() (*string, bool)`

GetCloneUrlOk returns a tuple with the CloneUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloneUrl

`func (o *AttachProjectRepo) SetCloneUrl(v string)`

SetCloneUrl sets CloneUrl field to given value.


### GetDefaultBranch

`func (o *AttachProjectRepo) GetDefaultBranch() string`

GetDefaultBranch returns the DefaultBranch field if non-nil, zero value otherwise.

### GetDefaultBranchOk

`func (o *AttachProjectRepo) GetDefaultBranchOk() (*string, bool)`

GetDefaultBranchOk returns a tuple with the DefaultBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBranch

`func (o *AttachProjectRepo) SetDefaultBranch(v string)`

SetDefaultBranch sets DefaultBranch field to given value.

### HasDefaultBranch

`func (o *AttachProjectRepo) HasDefaultBranch() bool`

HasDefaultBranch returns a boolean if a field has been set.

### GetGithubInstallationId

`func (o *AttachProjectRepo) GetGithubInstallationId() string`

GetGithubInstallationId returns the GithubInstallationId field if non-nil, zero value otherwise.

### GetGithubInstallationIdOk

`func (o *AttachProjectRepo) GetGithubInstallationIdOk() (*string, bool)`

GetGithubInstallationIdOk returns a tuple with the GithubInstallationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubInstallationId

`func (o *AttachProjectRepo) SetGithubInstallationId(v string)`

SetGithubInstallationId sets GithubInstallationId field to given value.

### HasGithubInstallationId

`func (o *AttachProjectRepo) HasGithubInstallationId() bool`

HasGithubInstallationId returns a boolean if a field has been set.

### SetGithubInstallationIdNil

`func (o *AttachProjectRepo) SetGithubInstallationIdNil(b bool)`

 SetGithubInstallationIdNil sets the value for GithubInstallationId to be an explicit nil

### UnsetGithubInstallationId
`func (o *AttachProjectRepo) UnsetGithubInstallationId()`

UnsetGithubInstallationId ensures that no value is present for GithubInstallationId, not even an explicit nil
### GetGithubRepoId

`func (o *AttachProjectRepo) GetGithubRepoId() int32`

GetGithubRepoId returns the GithubRepoId field if non-nil, zero value otherwise.

### GetGithubRepoIdOk

`func (o *AttachProjectRepo) GetGithubRepoIdOk() (*int32, bool)`

GetGithubRepoIdOk returns a tuple with the GithubRepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepoId

`func (o *AttachProjectRepo) SetGithubRepoId(v int32)`

SetGithubRepoId sets GithubRepoId field to given value.

### HasGithubRepoId

`func (o *AttachProjectRepo) HasGithubRepoId() bool`

HasGithubRepoId returns a boolean if a field has been set.

### SetGithubRepoIdNil

`func (o *AttachProjectRepo) SetGithubRepoIdNil(b bool)`

 SetGithubRepoIdNil sets the value for GithubRepoId to be an explicit nil

### UnsetGithubRepoId
`func (o *AttachProjectRepo) UnsetGithubRepoId()`

UnsetGithubRepoId ensures that no value is present for GithubRepoId, not even an explicit nil
### GetIsPrimary

`func (o *AttachProjectRepo) GetIsPrimary() bool`

GetIsPrimary returns the IsPrimary field if non-nil, zero value otherwise.

### GetIsPrimaryOk

`func (o *AttachProjectRepo) GetIsPrimaryOk() (*bool, bool)`

GetIsPrimaryOk returns a tuple with the IsPrimary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPrimary

`func (o *AttachProjectRepo) SetIsPrimary(v bool)`

SetIsPrimary sets IsPrimary field to given value.

### HasIsPrimary

`func (o *AttachProjectRepo) HasIsPrimary() bool`

HasIsPrimary returns a boolean if a field has been set.

### GetLabel

`func (o *AttachProjectRepo) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AttachProjectRepo) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AttachProjectRepo) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *AttachProjectRepo) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *AttachProjectRepo) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *AttachProjectRepo) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetName

`func (o *AttachProjectRepo) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AttachProjectRepo) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AttachProjectRepo) SetName(v string)`

SetName sets Name field to given value.


### GetOwner

`func (o *AttachProjectRepo) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *AttachProjectRepo) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *AttachProjectRepo) SetOwner(v string)`

SetOwner sets Owner field to given value.


### GetProvider

`func (o *AttachProjectRepo) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AttachProjectRepo) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AttachProjectRepo) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *AttachProjectRepo) HasProvider() bool`

HasProvider returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


