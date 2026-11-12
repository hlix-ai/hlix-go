# ProjectRuntime

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Agents** | Pointer to **[]string** |  | [optional]
**AptPackages** | Pointer to **[]string** |  | [optional]
**Deployment** | Pointer to [**CreateProjectRuntimeDeployment**](CreateProjectRuntimeDeployment.md) |  | [optional]
**EnvOverrides** | Pointer to **map[string]string** |  | [optional]
**Hash** | Pointer to **string** |  | [optional]
**ImageTag** | Pointer to **NullableString** |  | [optional]
**LinearProjectId** | Pointer to **string** |  | [optional]
**LinearTeamId** | Pointer to **string** |  | [optional]
**Notes** | Pointer to **[]string** |  | [optional]
**Preview** | Pointer to [**CreateProjectRuntimePreview**](CreateProjectRuntimePreview.md) |  | [optional]
**Services** | Pointer to [**[]CreateProjectRuntimeServicesInner**](CreateProjectRuntimeServicesInner.md) |  | [optional]
**Setup** | Pointer to **string** |  | [optional]
**Source** | Pointer to **map[string]string** |  | [optional]
**Toolchain** | Pointer to [**CreateProjectRuntimeToolchain**](CreateProjectRuntimeToolchain.md) |  | [optional]
**VerifyCommand** | Pointer to **string** |  | [optional]

## Methods

### NewProjectRuntime

`func NewProjectRuntime() *ProjectRuntime`

NewProjectRuntime instantiates a new ProjectRuntime object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectRuntimeWithDefaults

`func NewProjectRuntimeWithDefaults() *ProjectRuntime`

NewProjectRuntimeWithDefaults instantiates a new ProjectRuntime object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgents

`func (o *ProjectRuntime) GetAgents() []string`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *ProjectRuntime) GetAgentsOk() (*[]string, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *ProjectRuntime) SetAgents(v []string)`

SetAgents sets Agents field to given value.

### HasAgents

`func (o *ProjectRuntime) HasAgents() bool`

HasAgents returns a boolean if a field has been set.

### GetAptPackages

`func (o *ProjectRuntime) GetAptPackages() []string`

GetAptPackages returns the AptPackages field if non-nil, zero value otherwise.

### GetAptPackagesOk

`func (o *ProjectRuntime) GetAptPackagesOk() (*[]string, bool)`

GetAptPackagesOk returns a tuple with the AptPackages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAptPackages

`func (o *ProjectRuntime) SetAptPackages(v []string)`

SetAptPackages sets AptPackages field to given value.

### HasAptPackages

`func (o *ProjectRuntime) HasAptPackages() bool`

HasAptPackages returns a boolean if a field has been set.

### GetDeployment

`func (o *ProjectRuntime) GetDeployment() CreateProjectRuntimeDeployment`

GetDeployment returns the Deployment field if non-nil, zero value otherwise.

### GetDeploymentOk

`func (o *ProjectRuntime) GetDeploymentOk() (*CreateProjectRuntimeDeployment, bool)`

GetDeploymentOk returns a tuple with the Deployment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployment

`func (o *ProjectRuntime) SetDeployment(v CreateProjectRuntimeDeployment)`

SetDeployment sets Deployment field to given value.

### HasDeployment

`func (o *ProjectRuntime) HasDeployment() bool`

HasDeployment returns a boolean if a field has been set.

### GetEnvOverrides

`func (o *ProjectRuntime) GetEnvOverrides() map[string]string`

GetEnvOverrides returns the EnvOverrides field if non-nil, zero value otherwise.

### GetEnvOverridesOk

`func (o *ProjectRuntime) GetEnvOverridesOk() (*map[string]string, bool)`

GetEnvOverridesOk returns a tuple with the EnvOverrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvOverrides

`func (o *ProjectRuntime) SetEnvOverrides(v map[string]string)`

SetEnvOverrides sets EnvOverrides field to given value.

### HasEnvOverrides

`func (o *ProjectRuntime) HasEnvOverrides() bool`

HasEnvOverrides returns a boolean if a field has been set.

### GetHash

`func (o *ProjectRuntime) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *ProjectRuntime) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *ProjectRuntime) SetHash(v string)`

SetHash sets Hash field to given value.

### HasHash

`func (o *ProjectRuntime) HasHash() bool`

HasHash returns a boolean if a field has been set.

### GetImageTag

`func (o *ProjectRuntime) GetImageTag() string`

GetImageTag returns the ImageTag field if non-nil, zero value otherwise.

### GetImageTagOk

`func (o *ProjectRuntime) GetImageTagOk() (*string, bool)`

GetImageTagOk returns a tuple with the ImageTag field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageTag

`func (o *ProjectRuntime) SetImageTag(v string)`

SetImageTag sets ImageTag field to given value.

### HasImageTag

`func (o *ProjectRuntime) HasImageTag() bool`

HasImageTag returns a boolean if a field has been set.

### SetImageTagNil

`func (o *ProjectRuntime) SetImageTagNil(b bool)`

 SetImageTagNil sets the value for ImageTag to be an explicit nil

### UnsetImageTag
`func (o *ProjectRuntime) UnsetImageTag()`

UnsetImageTag ensures that no value is present for ImageTag, not even an explicit nil
### GetLinearProjectId

`func (o *ProjectRuntime) GetLinearProjectId() string`

GetLinearProjectId returns the LinearProjectId field if non-nil, zero value otherwise.

### GetLinearProjectIdOk

`func (o *ProjectRuntime) GetLinearProjectIdOk() (*string, bool)`

GetLinearProjectIdOk returns a tuple with the LinearProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearProjectId

`func (o *ProjectRuntime) SetLinearProjectId(v string)`

SetLinearProjectId sets LinearProjectId field to given value.

### HasLinearProjectId

`func (o *ProjectRuntime) HasLinearProjectId() bool`

HasLinearProjectId returns a boolean if a field has been set.

### GetLinearTeamId

`func (o *ProjectRuntime) GetLinearTeamId() string`

GetLinearTeamId returns the LinearTeamId field if non-nil, zero value otherwise.

### GetLinearTeamIdOk

`func (o *ProjectRuntime) GetLinearTeamIdOk() (*string, bool)`

GetLinearTeamIdOk returns a tuple with the LinearTeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearTeamId

`func (o *ProjectRuntime) SetLinearTeamId(v string)`

SetLinearTeamId sets LinearTeamId field to given value.

### HasLinearTeamId

`func (o *ProjectRuntime) HasLinearTeamId() bool`

HasLinearTeamId returns a boolean if a field has been set.

### GetNotes

`func (o *ProjectRuntime) GetNotes() []string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ProjectRuntime) GetNotesOk() (*[]string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ProjectRuntime) SetNotes(v []string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ProjectRuntime) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetPreview

`func (o *ProjectRuntime) GetPreview() CreateProjectRuntimePreview`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *ProjectRuntime) GetPreviewOk() (*CreateProjectRuntimePreview, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *ProjectRuntime) SetPreview(v CreateProjectRuntimePreview)`

SetPreview sets Preview field to given value.

### HasPreview

`func (o *ProjectRuntime) HasPreview() bool`

HasPreview returns a boolean if a field has been set.

### GetServices

`func (o *ProjectRuntime) GetServices() []CreateProjectRuntimeServicesInner`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ProjectRuntime) GetServicesOk() (*[]CreateProjectRuntimeServicesInner, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ProjectRuntime) SetServices(v []CreateProjectRuntimeServicesInner)`

SetServices sets Services field to given value.

### HasServices

`func (o *ProjectRuntime) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetSetup

`func (o *ProjectRuntime) GetSetup() string`

GetSetup returns the Setup field if non-nil, zero value otherwise.

### GetSetupOk

`func (o *ProjectRuntime) GetSetupOk() (*string, bool)`

GetSetupOk returns a tuple with the Setup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetup

`func (o *ProjectRuntime) SetSetup(v string)`

SetSetup sets Setup field to given value.

### HasSetup

`func (o *ProjectRuntime) HasSetup() bool`

HasSetup returns a boolean if a field has been set.

### GetSource

`func (o *ProjectRuntime) GetSource() map[string]string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ProjectRuntime) GetSourceOk() (*map[string]string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ProjectRuntime) SetSource(v map[string]string)`

SetSource sets Source field to given value.

### HasSource

`func (o *ProjectRuntime) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetToolchain

`func (o *ProjectRuntime) GetToolchain() CreateProjectRuntimeToolchain`

GetToolchain returns the Toolchain field if non-nil, zero value otherwise.

### GetToolchainOk

`func (o *ProjectRuntime) GetToolchainOk() (*CreateProjectRuntimeToolchain, bool)`

GetToolchainOk returns a tuple with the Toolchain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolchain

`func (o *ProjectRuntime) SetToolchain(v CreateProjectRuntimeToolchain)`

SetToolchain sets Toolchain field to given value.

### HasToolchain

`func (o *ProjectRuntime) HasToolchain() bool`

HasToolchain returns a boolean if a field has been set.

### GetVerifyCommand

`func (o *ProjectRuntime) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *ProjectRuntime) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *ProjectRuntime) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.

### HasVerifyCommand

`func (o *ProjectRuntime) HasVerifyCommand() bool`

HasVerifyCommand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


