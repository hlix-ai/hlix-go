# ProjectReposInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CloneUrl** | **string** |  | 
**ConnectionStatus** | Pointer to **string** |  | [optional] 
**CreatedAt** | **string** |  | 
**DefaultBranch** | **string** |  | 
**DetectedCommands** | [**NullableProjectDetectedCommands**](ProjectDetectedCommands.md) |  | 
**GithubInstallationId** | **NullableString** |  | 
**GithubRepoId** | **NullableInt32** |  | 
**Id** | **string** |  | 
**IsPrimary** | **bool** |  | 
**Label** | **NullableString** |  | 
**Name** | **string** |  | 
**OrganizationId** | **string** |  | 
**Owner** | **string** |  | 
**PreviewCommand** | **NullableString** |  | 
**PreviewPort** | **NullableInt32** |  | 
**ProjectId** | **string** |  | 
**Provider** | **string** |  | 
**SetupCommand** | **NullableString** |  | 
**VerifyCommand** | **NullableString** |  | 

## Methods

### NewProjectReposInner

`func NewProjectReposInner(cloneUrl string, createdAt string, defaultBranch string, detectedCommands NullableProjectDetectedCommands, githubInstallationId NullableString, githubRepoId NullableInt32, id string, isPrimary bool, label NullableString, name string, organizationId string, owner string, previewCommand NullableString, previewPort NullableInt32, projectId string, provider string, setupCommand NullableString, verifyCommand NullableString, ) *ProjectReposInner`

NewProjectReposInner instantiates a new ProjectReposInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectReposInnerWithDefaults

`func NewProjectReposInnerWithDefaults() *ProjectReposInner`

NewProjectReposInnerWithDefaults instantiates a new ProjectReposInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCloneUrl

`func (o *ProjectReposInner) GetCloneUrl() string`

GetCloneUrl returns the CloneUrl field if non-nil, zero value otherwise.

### GetCloneUrlOk

`func (o *ProjectReposInner) GetCloneUrlOk() (*string, bool)`

GetCloneUrlOk returns a tuple with the CloneUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloneUrl

`func (o *ProjectReposInner) SetCloneUrl(v string)`

SetCloneUrl sets CloneUrl field to given value.


### GetConnectionStatus

`func (o *ProjectReposInner) GetConnectionStatus() string`

GetConnectionStatus returns the ConnectionStatus field if non-nil, zero value otherwise.

### GetConnectionStatusOk

`func (o *ProjectReposInner) GetConnectionStatusOk() (*string, bool)`

GetConnectionStatusOk returns a tuple with the ConnectionStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionStatus

`func (o *ProjectReposInner) SetConnectionStatus(v string)`

SetConnectionStatus sets ConnectionStatus field to given value.

### HasConnectionStatus

`func (o *ProjectReposInner) HasConnectionStatus() bool`

HasConnectionStatus returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ProjectReposInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectReposInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectReposInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDefaultBranch

`func (o *ProjectReposInner) GetDefaultBranch() string`

GetDefaultBranch returns the DefaultBranch field if non-nil, zero value otherwise.

### GetDefaultBranchOk

`func (o *ProjectReposInner) GetDefaultBranchOk() (*string, bool)`

GetDefaultBranchOk returns a tuple with the DefaultBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultBranch

`func (o *ProjectReposInner) SetDefaultBranch(v string)`

SetDefaultBranch sets DefaultBranch field to given value.


### GetDetectedCommands

`func (o *ProjectReposInner) GetDetectedCommands() ProjectDetectedCommands`

GetDetectedCommands returns the DetectedCommands field if non-nil, zero value otherwise.

### GetDetectedCommandsOk

`func (o *ProjectReposInner) GetDetectedCommandsOk() (*ProjectDetectedCommands, bool)`

GetDetectedCommandsOk returns a tuple with the DetectedCommands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedCommands

`func (o *ProjectReposInner) SetDetectedCommands(v ProjectDetectedCommands)`

SetDetectedCommands sets DetectedCommands field to given value.


### SetDetectedCommandsNil

`func (o *ProjectReposInner) SetDetectedCommandsNil(b bool)`

 SetDetectedCommandsNil sets the value for DetectedCommands to be an explicit nil

### UnsetDetectedCommands
`func (o *ProjectReposInner) UnsetDetectedCommands()`

UnsetDetectedCommands ensures that no value is present for DetectedCommands, not even an explicit nil
### GetGithubInstallationId

`func (o *ProjectReposInner) GetGithubInstallationId() string`

GetGithubInstallationId returns the GithubInstallationId field if non-nil, zero value otherwise.

### GetGithubInstallationIdOk

`func (o *ProjectReposInner) GetGithubInstallationIdOk() (*string, bool)`

GetGithubInstallationIdOk returns a tuple with the GithubInstallationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubInstallationId

`func (o *ProjectReposInner) SetGithubInstallationId(v string)`

SetGithubInstallationId sets GithubInstallationId field to given value.


### SetGithubInstallationIdNil

`func (o *ProjectReposInner) SetGithubInstallationIdNil(b bool)`

 SetGithubInstallationIdNil sets the value for GithubInstallationId to be an explicit nil

### UnsetGithubInstallationId
`func (o *ProjectReposInner) UnsetGithubInstallationId()`

UnsetGithubInstallationId ensures that no value is present for GithubInstallationId, not even an explicit nil
### GetGithubRepoId

`func (o *ProjectReposInner) GetGithubRepoId() int32`

GetGithubRepoId returns the GithubRepoId field if non-nil, zero value otherwise.

### GetGithubRepoIdOk

`func (o *ProjectReposInner) GetGithubRepoIdOk() (*int32, bool)`

GetGithubRepoIdOk returns a tuple with the GithubRepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGithubRepoId

`func (o *ProjectReposInner) SetGithubRepoId(v int32)`

SetGithubRepoId sets GithubRepoId field to given value.


### SetGithubRepoIdNil

`func (o *ProjectReposInner) SetGithubRepoIdNil(b bool)`

 SetGithubRepoIdNil sets the value for GithubRepoId to be an explicit nil

### UnsetGithubRepoId
`func (o *ProjectReposInner) UnsetGithubRepoId()`

UnsetGithubRepoId ensures that no value is present for GithubRepoId, not even an explicit nil
### GetId

`func (o *ProjectReposInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectReposInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectReposInner) SetId(v string)`

SetId sets Id field to given value.


### GetIsPrimary

`func (o *ProjectReposInner) GetIsPrimary() bool`

GetIsPrimary returns the IsPrimary field if non-nil, zero value otherwise.

### GetIsPrimaryOk

`func (o *ProjectReposInner) GetIsPrimaryOk() (*bool, bool)`

GetIsPrimaryOk returns a tuple with the IsPrimary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPrimary

`func (o *ProjectReposInner) SetIsPrimary(v bool)`

SetIsPrimary sets IsPrimary field to given value.


### GetLabel

`func (o *ProjectReposInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *ProjectReposInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *ProjectReposInner) SetLabel(v string)`

SetLabel sets Label field to given value.


### SetLabelNil

`func (o *ProjectReposInner) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *ProjectReposInner) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetName

`func (o *ProjectReposInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectReposInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectReposInner) SetName(v string)`

SetName sets Name field to given value.


### GetOrganizationId

`func (o *ProjectReposInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ProjectReposInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ProjectReposInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOwner

`func (o *ProjectReposInner) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *ProjectReposInner) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *ProjectReposInner) SetOwner(v string)`

SetOwner sets Owner field to given value.


### GetPreviewCommand

`func (o *ProjectReposInner) GetPreviewCommand() string`

GetPreviewCommand returns the PreviewCommand field if non-nil, zero value otherwise.

### GetPreviewCommandOk

`func (o *ProjectReposInner) GetPreviewCommandOk() (*string, bool)`

GetPreviewCommandOk returns a tuple with the PreviewCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewCommand

`func (o *ProjectReposInner) SetPreviewCommand(v string)`

SetPreviewCommand sets PreviewCommand field to given value.


### SetPreviewCommandNil

`func (o *ProjectReposInner) SetPreviewCommandNil(b bool)`

 SetPreviewCommandNil sets the value for PreviewCommand to be an explicit nil

### UnsetPreviewCommand
`func (o *ProjectReposInner) UnsetPreviewCommand()`

UnsetPreviewCommand ensures that no value is present for PreviewCommand, not even an explicit nil
### GetPreviewPort

`func (o *ProjectReposInner) GetPreviewPort() int32`

GetPreviewPort returns the PreviewPort field if non-nil, zero value otherwise.

### GetPreviewPortOk

`func (o *ProjectReposInner) GetPreviewPortOk() (*int32, bool)`

GetPreviewPortOk returns a tuple with the PreviewPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPort

`func (o *ProjectReposInner) SetPreviewPort(v int32)`

SetPreviewPort sets PreviewPort field to given value.


### SetPreviewPortNil

`func (o *ProjectReposInner) SetPreviewPortNil(b bool)`

 SetPreviewPortNil sets the value for PreviewPort to be an explicit nil

### UnsetPreviewPort
`func (o *ProjectReposInner) UnsetPreviewPort()`

UnsetPreviewPort ensures that no value is present for PreviewPort, not even an explicit nil
### GetProjectId

`func (o *ProjectReposInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectReposInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectReposInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProvider

`func (o *ProjectReposInner) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ProjectReposInner) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ProjectReposInner) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetSetupCommand

`func (o *ProjectReposInner) GetSetupCommand() string`

GetSetupCommand returns the SetupCommand field if non-nil, zero value otherwise.

### GetSetupCommandOk

`func (o *ProjectReposInner) GetSetupCommandOk() (*string, bool)`

GetSetupCommandOk returns a tuple with the SetupCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupCommand

`func (o *ProjectReposInner) SetSetupCommand(v string)`

SetSetupCommand sets SetupCommand field to given value.


### SetSetupCommandNil

`func (o *ProjectReposInner) SetSetupCommandNil(b bool)`

 SetSetupCommandNil sets the value for SetupCommand to be an explicit nil

### UnsetSetupCommand
`func (o *ProjectReposInner) UnsetSetupCommand()`

UnsetSetupCommand ensures that no value is present for SetupCommand, not even an explicit nil
### GetVerifyCommand

`func (o *ProjectReposInner) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *ProjectReposInner) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *ProjectReposInner) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.


### SetVerifyCommandNil

`func (o *ProjectReposInner) SetVerifyCommandNil(b bool)`

 SetVerifyCommandNil sets the value for VerifyCommand to be an explicit nil

### UnsetVerifyCommand
`func (o *ProjectReposInner) UnsetVerifyCommand()`

UnsetVerifyCommand ensures that no value is present for VerifyCommand, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


