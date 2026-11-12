# CreateProjectRuntime

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Agents** | Pointer to **[]string** |  | [optional]
**AptPackages** | Pointer to **[]string** |  | [optional]
**Deployment** | Pointer to [**CreateProjectRuntimeDeployment**](CreateProjectRuntimeDeployment.md) |  | [optional]
**EnvOverrides** | Pointer to **map[string]string** |  | [optional]
**Notes** | Pointer to **[]string** |  | [optional]
**Preview** | Pointer to [**CreateProjectRuntimePreview**](CreateProjectRuntimePreview.md) |  | [optional]
**Services** | Pointer to [**[]CreateProjectRuntimeServicesInner**](CreateProjectRuntimeServicesInner.md) |  | [optional]
**Setup** | Pointer to **string** |  | [optional]
**Toolchain** | Pointer to [**CreateProjectRuntimeToolchain**](CreateProjectRuntimeToolchain.md) |  | [optional]
**VerifyCommand** | Pointer to **string** |  | [optional]

## Methods

### NewCreateProjectRuntime

`func NewCreateProjectRuntime() *CreateProjectRuntime`

NewCreateProjectRuntime instantiates a new CreateProjectRuntime object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateProjectRuntimeWithDefaults

`func NewCreateProjectRuntimeWithDefaults() *CreateProjectRuntime`

NewCreateProjectRuntimeWithDefaults instantiates a new CreateProjectRuntime object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgents

`func (o *CreateProjectRuntime) GetAgents() []string`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *CreateProjectRuntime) GetAgentsOk() (*[]string, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *CreateProjectRuntime) SetAgents(v []string)`

SetAgents sets Agents field to given value.

### HasAgents

`func (o *CreateProjectRuntime) HasAgents() bool`

HasAgents returns a boolean if a field has been set.

### GetAptPackages

`func (o *CreateProjectRuntime) GetAptPackages() []string`

GetAptPackages returns the AptPackages field if non-nil, zero value otherwise.

### GetAptPackagesOk

`func (o *CreateProjectRuntime) GetAptPackagesOk() (*[]string, bool)`

GetAptPackagesOk returns a tuple with the AptPackages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAptPackages

`func (o *CreateProjectRuntime) SetAptPackages(v []string)`

SetAptPackages sets AptPackages field to given value.

### HasAptPackages

`func (o *CreateProjectRuntime) HasAptPackages() bool`

HasAptPackages returns a boolean if a field has been set.

### GetDeployment

`func (o *CreateProjectRuntime) GetDeployment() CreateProjectRuntimeDeployment`

GetDeployment returns the Deployment field if non-nil, zero value otherwise.

### GetDeploymentOk

`func (o *CreateProjectRuntime) GetDeploymentOk() (*CreateProjectRuntimeDeployment, bool)`

GetDeploymentOk returns a tuple with the Deployment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployment

`func (o *CreateProjectRuntime) SetDeployment(v CreateProjectRuntimeDeployment)`

SetDeployment sets Deployment field to given value.

### HasDeployment

`func (o *CreateProjectRuntime) HasDeployment() bool`

HasDeployment returns a boolean if a field has been set.

### GetEnvOverrides

`func (o *CreateProjectRuntime) GetEnvOverrides() map[string]string`

GetEnvOverrides returns the EnvOverrides field if non-nil, zero value otherwise.

### GetEnvOverridesOk

`func (o *CreateProjectRuntime) GetEnvOverridesOk() (*map[string]string, bool)`

GetEnvOverridesOk returns a tuple with the EnvOverrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvOverrides

`func (o *CreateProjectRuntime) SetEnvOverrides(v map[string]string)`

SetEnvOverrides sets EnvOverrides field to given value.

### HasEnvOverrides

`func (o *CreateProjectRuntime) HasEnvOverrides() bool`

HasEnvOverrides returns a boolean if a field has been set.

### GetNotes

`func (o *CreateProjectRuntime) GetNotes() []string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *CreateProjectRuntime) GetNotesOk() (*[]string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *CreateProjectRuntime) SetNotes(v []string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *CreateProjectRuntime) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetPreview

`func (o *CreateProjectRuntime) GetPreview() CreateProjectRuntimePreview`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *CreateProjectRuntime) GetPreviewOk() (*CreateProjectRuntimePreview, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *CreateProjectRuntime) SetPreview(v CreateProjectRuntimePreview)`

SetPreview sets Preview field to given value.

### HasPreview

`func (o *CreateProjectRuntime) HasPreview() bool`

HasPreview returns a boolean if a field has been set.

### GetServices

`func (o *CreateProjectRuntime) GetServices() []CreateProjectRuntimeServicesInner`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *CreateProjectRuntime) GetServicesOk() (*[]CreateProjectRuntimeServicesInner, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *CreateProjectRuntime) SetServices(v []CreateProjectRuntimeServicesInner)`

SetServices sets Services field to given value.

### HasServices

`func (o *CreateProjectRuntime) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetSetup

`func (o *CreateProjectRuntime) GetSetup() string`

GetSetup returns the Setup field if non-nil, zero value otherwise.

### GetSetupOk

`func (o *CreateProjectRuntime) GetSetupOk() (*string, bool)`

GetSetupOk returns a tuple with the Setup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetup

`func (o *CreateProjectRuntime) SetSetup(v string)`

SetSetup sets Setup field to given value.

### HasSetup

`func (o *CreateProjectRuntime) HasSetup() bool`

HasSetup returns a boolean if a field has been set.

### GetToolchain

`func (o *CreateProjectRuntime) GetToolchain() CreateProjectRuntimeToolchain`

GetToolchain returns the Toolchain field if non-nil, zero value otherwise.

### GetToolchainOk

`func (o *CreateProjectRuntime) GetToolchainOk() (*CreateProjectRuntimeToolchain, bool)`

GetToolchainOk returns a tuple with the Toolchain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolchain

`func (o *CreateProjectRuntime) SetToolchain(v CreateProjectRuntimeToolchain)`

SetToolchain sets Toolchain field to given value.

### HasToolchain

`func (o *CreateProjectRuntime) HasToolchain() bool`

HasToolchain returns a boolean if a field has been set.

### GetVerifyCommand

`func (o *CreateProjectRuntime) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *CreateProjectRuntime) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *CreateProjectRuntime) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.

### HasVerifyCommand

`func (o *CreateProjectRuntime) HasVerifyCommand() bool`

HasVerifyCommand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


