# CreateProject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attachments** | Pointer to [**[]AnalyzeMediaSourceAnyOf1**](AnalyzeMediaSourceAnyOf1.md) |  | [optional]
**Brief** | Pointer to **string** |  | [optional]
**ClaudeMd** | Pointer to **string** |  | [optional]
**GithubRepository** | Pointer to **string** |  | [optional]
**InitialProposalRequired** | Pointer to **bool** | Hold the first build until a person approves the plan. Defaults to false: hlix starts by itself. | [optional]
**Name** | Pointer to **string** |  | [optional]
**Repos** | Pointer to [**[]CreateProjectReposInner**](CreateProjectReposInner.md) |  | [optional]
**Runtime** | Pointer to [**CreateProjectRuntime**](CreateProjectRuntime.md) |  | [optional]
**Stack** | Pointer to **string** |  | [optional]
**Tier** | Pointer to **string** |  | [optional]
**UseWorkspaceBrand** | Pointer to **bool** |  | [optional]

## Methods

### NewCreateProject

`func NewCreateProject() *CreateProject`

NewCreateProject instantiates a new CreateProject object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateProjectWithDefaults

`func NewCreateProjectWithDefaults() *CreateProject`

NewCreateProjectWithDefaults instantiates a new CreateProject object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAttachments

`func (o *CreateProject) GetAttachments() []AnalyzeMediaSourceAnyOf1`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *CreateProject) GetAttachmentsOk() (*[]AnalyzeMediaSourceAnyOf1, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *CreateProject) SetAttachments(v []AnalyzeMediaSourceAnyOf1)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *CreateProject) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetBrief

`func (o *CreateProject) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *CreateProject) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *CreateProject) SetBrief(v string)`

SetBrief sets Brief field to given value.

### HasBrief

`func (o *CreateProject) HasBrief() bool`

HasBrief returns a boolean if a field has been set.

### GetClaudeMd

`func (o *CreateProject) GetClaudeMd() string`

GetClaudeMd returns the ClaudeMd field if non-nil, zero value otherwise.

### GetClaudeMdOk

`func (o *CreateProject) GetClaudeMdOk() (*string, bool)`

GetClaudeMdOk returns a tuple with the ClaudeMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaudeMd

`func (o *CreateProject) SetClaudeMd(v string)`

SetClaudeMd sets ClaudeMd field to given value.

### HasClaudeMd

`func (o *CreateProject) HasClaudeMd() bool`

HasClaudeMd returns a boolean if a field has been set.

### GetGithubRepository

`func (o *CreateProject) GetGithubRepository() string`

GetGithubRepository returns the GithubRepository field if non-nil, zero value otherwise.

### GetGithubRepositoryOk

`func (o *CreateProject) GetGithubRepositoryOk() (*string, bool)`

GetGithubRepositoryOk returns a tuple with the GithubRepository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepository

`func (o *CreateProject) SetGithubRepository(v string)`

SetGithubRepository sets GithubRepository field to given value.

### HasGithubRepository

`func (o *CreateProject) HasGithubRepository() bool`

HasGithubRepository returns a boolean if a field has been set.

### GetInitialProposalRequired

`func (o *CreateProject) GetInitialProposalRequired() bool`

GetInitialProposalRequired returns the InitialProposalRequired field if non-nil, zero value otherwise.

### GetInitialProposalRequiredOk

`func (o *CreateProject) GetInitialProposalRequiredOk() (*bool, bool)`

GetInitialProposalRequiredOk returns a tuple with the InitialProposalRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialProposalRequired

`func (o *CreateProject) SetInitialProposalRequired(v bool)`

SetInitialProposalRequired sets InitialProposalRequired field to given value.

### HasInitialProposalRequired

`func (o *CreateProject) HasInitialProposalRequired() bool`

HasInitialProposalRequired returns a boolean if a field has been set.

### GetName

`func (o *CreateProject) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateProject) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateProject) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateProject) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRepos

`func (o *CreateProject) GetRepos() []CreateProjectReposInner`

GetRepos returns the Repos field if non-nil, zero value otherwise.

### GetReposOk

`func (o *CreateProject) GetReposOk() (*[]CreateProjectReposInner, bool)`

GetReposOk returns a tuple with the Repos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepos

`func (o *CreateProject) SetRepos(v []CreateProjectReposInner)`

SetRepos sets Repos field to given value.

### HasRepos

`func (o *CreateProject) HasRepos() bool`

HasRepos returns a boolean if a field has been set.

### GetRuntime

`func (o *CreateProject) GetRuntime() CreateProjectRuntime`

GetRuntime returns the Runtime field if non-nil, zero value otherwise.

### GetRuntimeOk

`func (o *CreateProject) GetRuntimeOk() (*CreateProjectRuntime, bool)`

GetRuntimeOk returns a tuple with the Runtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntime

`func (o *CreateProject) SetRuntime(v CreateProjectRuntime)`

SetRuntime sets Runtime field to given value.

### HasRuntime

`func (o *CreateProject) HasRuntime() bool`

HasRuntime returns a boolean if a field has been set.

### GetStack

`func (o *CreateProject) GetStack() string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *CreateProject) GetStackOk() (*string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *CreateProject) SetStack(v string)`

SetStack sets Stack field to given value.

### HasStack

`func (o *CreateProject) HasStack() bool`

HasStack returns a boolean if a field has been set.

### GetTier

`func (o *CreateProject) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *CreateProject) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *CreateProject) SetTier(v string)`

SetTier sets Tier field to given value.

### HasTier

`func (o *CreateProject) HasTier() bool`

HasTier returns a boolean if a field has been set.

### GetUseWorkspaceBrand

`func (o *CreateProject) GetUseWorkspaceBrand() bool`

GetUseWorkspaceBrand returns the UseWorkspaceBrand field if non-nil, zero value otherwise.

### GetUseWorkspaceBrandOk

`func (o *CreateProject) GetUseWorkspaceBrandOk() (*bool, bool)`

GetUseWorkspaceBrandOk returns a tuple with the UseWorkspaceBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWorkspaceBrand

`func (o *CreateProject) SetUseWorkspaceBrand(v bool)`

SetUseWorkspaceBrand sets UseWorkspaceBrand field to given value.

### HasUseWorkspaceBrand

`func (o *CreateProject) HasUseWorkspaceBrand() bool`

HasUseWorkspaceBrand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


