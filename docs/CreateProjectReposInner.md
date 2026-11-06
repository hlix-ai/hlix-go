# CreateProjectReposInner

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

### NewCreateProjectReposInner

`func NewCreateProjectReposInner(cloneUrl string, name string, owner string, ) *CreateProjectReposInner`

NewCreateProjectReposInner instantiates a new CreateProjectReposInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProjectReposInnerWithDefaults

`func NewCreateProjectReposInnerWithDefaults() *CreateProjectReposInner`

NewCreateProjectReposInnerWithDefaults instantiates a new CreateProjectReposInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCloneUrl

`func (o *CreateProjectReposInner) GetCloneUrl() string`

GetCloneUrl returns the CloneUrl field if non-nil, zero value otherwise.

### GetCloneUrlOk

`func (o *CreateProjectReposInner) GetCloneUrlOk() (*string, bool)`

GetCloneUrlOk returns a tuple with the CloneUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloneUrl

`func (o *CreateProjectReposInner) SetCloneUrl(v string)`

SetCloneUrl sets CloneUrl field to given value.


### GetDefaultBranch

`func (o *CreateProjectReposInner) GetDefaultBranch() string`

GetDefaultBranch returns the DefaultBranch field if non-nil, zero value otherwise.

### GetDefaultBranchOk

`func (o *CreateProjectReposInner) GetDefaultBranchOk() (*string, bool)`

GetDefaultBranchOk returns a tuple with the DefaultBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBranch

`func (o *CreateProjectReposInner) SetDefaultBranch(v string)`

SetDefaultBranch sets DefaultBranch field to given value.

### HasDefaultBranch

`func (o *CreateProjectReposInner) HasDefaultBranch() bool`

HasDefaultBranch returns a boolean if a field has been set.

### GetGithubInstallationId

`func (o *CreateProjectReposInner) GetGithubInstallationId() string`

GetGithubInstallationId returns the GithubInstallationId field if non-nil, zero value otherwise.

### GetGithubInstallationIdOk

`func (o *CreateProjectReposInner) GetGithubInstallationIdOk() (*string, bool)`

GetGithubInstallationIdOk returns a tuple with the GithubInstallationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubInstallationId

`func (o *CreateProjectReposInner) SetGithubInstallationId(v string)`

SetGithubInstallationId sets GithubInstallationId field to given value.

### HasGithubInstallationId

`func (o *CreateProjectReposInner) HasGithubInstallationId() bool`

HasGithubInstallationId returns a boolean if a field has been set.

### SetGithubInstallationIdNil

`func (o *CreateProjectReposInner) SetGithubInstallationIdNil(b bool)`

 SetGithubInstallationIdNil sets the value for GithubInstallationId to be an explicit nil

### UnsetGithubInstallationId
`func (o *CreateProjectReposInner) UnsetGithubInstallationId()`

UnsetGithubInstallationId ensures that no value is present for GithubInstallationId, not even an explicit nil
### GetGithubRepoId

`func (o *CreateProjectReposInner) GetGithubRepoId() int32`

GetGithubRepoId returns the GithubRepoId field if non-nil, zero value otherwise.

### GetGithubRepoIdOk

`func (o *CreateProjectReposInner) GetGithubRepoIdOk() (*int32, bool)`

GetGithubRepoIdOk returns a tuple with the GithubRepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepoId

`func (o *CreateProjectReposInner) SetGithubRepoId(v int32)`

SetGithubRepoId sets GithubRepoId field to given value.

### HasGithubRepoId

`func (o *CreateProjectReposInner) HasGithubRepoId() bool`

HasGithubRepoId returns a boolean if a field has been set.

### SetGithubRepoIdNil

`func (o *CreateProjectReposInner) SetGithubRepoIdNil(b bool)`

 SetGithubRepoIdNil sets the value for GithubRepoId to be an explicit nil

### UnsetGithubRepoId
`func (o *CreateProjectReposInner) UnsetGithubRepoId()`

UnsetGithubRepoId ensures that no value is present for GithubRepoId, not even an explicit nil
### GetIsPrimary

`func (o *CreateProjectReposInner) GetIsPrimary() bool`

GetIsPrimary returns the IsPrimary field if non-nil, zero value otherwise.

### GetIsPrimaryOk

`func (o *CreateProjectReposInner) GetIsPrimaryOk() (*bool, bool)`

GetIsPrimaryOk returns a tuple with the IsPrimary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPrimary

`func (o *CreateProjectReposInner) SetIsPrimary(v bool)`

SetIsPrimary sets IsPrimary field to given value.

### HasIsPrimary

`func (o *CreateProjectReposInner) HasIsPrimary() bool`

HasIsPrimary returns a boolean if a field has been set.

### GetLabel

`func (o *CreateProjectReposInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateProjectReposInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateProjectReposInner) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *CreateProjectReposInner) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *CreateProjectReposInner) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *CreateProjectReposInner) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetName

`func (o *CreateProjectReposInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateProjectReposInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateProjectReposInner) SetName(v string)`

SetName sets Name field to given value.


### GetOwner

`func (o *CreateProjectReposInner) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *CreateProjectReposInner) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *CreateProjectReposInner) SetOwner(v string)`

SetOwner sets Owner field to given value.


### GetProvider

`func (o *CreateProjectReposInner) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateProjectReposInner) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateProjectReposInner) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *CreateProjectReposInner) HasProvider() bool`

HasProvider returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


