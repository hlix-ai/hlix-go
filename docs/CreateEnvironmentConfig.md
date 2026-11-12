# CreateEnvironmentConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Files** | Pointer to [**[]CreateEnvironmentConfigFilesInner**](CreateEnvironmentConfigFilesInner.md) |  | [optional]
**ManagedPaths** | Pointer to **[]string** |  | [optional]
**McpServers** | Pointer to **[]interface{}** |  | [optional]
**Skills** | Pointer to **[]string** |  | [optional]
**Vars** | Pointer to **map[string]string** |  | [optional]

## Methods

### NewCreateEnvironmentConfig

`func NewCreateEnvironmentConfig() *CreateEnvironmentConfig`

NewCreateEnvironmentConfig instantiates a new CreateEnvironmentConfig object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateEnvironmentConfigWithDefaults

`func NewCreateEnvironmentConfigWithDefaults() *CreateEnvironmentConfig`

NewCreateEnvironmentConfigWithDefaults instantiates a new CreateEnvironmentConfig object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetFiles

`func (o *CreateEnvironmentConfig) GetFiles() []CreateEnvironmentConfigFilesInner`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *CreateEnvironmentConfig) GetFilesOk() (*[]CreateEnvironmentConfigFilesInner, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *CreateEnvironmentConfig) SetFiles(v []CreateEnvironmentConfigFilesInner)`

SetFiles sets Files field to given value.

### HasFiles

`func (o *CreateEnvironmentConfig) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### GetManagedPaths

`func (o *CreateEnvironmentConfig) GetManagedPaths() []string`

GetManagedPaths returns the ManagedPaths field if non-nil, zero value otherwise.

### GetManagedPathsOk

`func (o *CreateEnvironmentConfig) GetManagedPathsOk() (*[]string, bool)`

GetManagedPathsOk returns a tuple with the ManagedPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedPaths

`func (o *CreateEnvironmentConfig) SetManagedPaths(v []string)`

SetManagedPaths sets ManagedPaths field to given value.

### HasManagedPaths

`func (o *CreateEnvironmentConfig) HasManagedPaths() bool`

HasManagedPaths returns a boolean if a field has been set.

### GetMcpServers

`func (o *CreateEnvironmentConfig) GetMcpServers() []interface{}`

GetMcpServers returns the McpServers field if non-nil, zero value otherwise.

### GetMcpServersOk

`func (o *CreateEnvironmentConfig) GetMcpServersOk() (*[]interface{}, bool)`

GetMcpServersOk returns a tuple with the McpServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMcpServers

`func (o *CreateEnvironmentConfig) SetMcpServers(v []interface{})`

SetMcpServers sets McpServers field to given value.

### HasMcpServers

`func (o *CreateEnvironmentConfig) HasMcpServers() bool`

HasMcpServers returns a boolean if a field has been set.

### GetSkills

`func (o *CreateEnvironmentConfig) GetSkills() []string`

GetSkills returns the Skills field if non-nil, zero value otherwise.

### GetSkillsOk

`func (o *CreateEnvironmentConfig) GetSkillsOk() (*[]string, bool)`

GetSkillsOk returns a tuple with the Skills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkills

`func (o *CreateEnvironmentConfig) SetSkills(v []string)`

SetSkills sets Skills field to given value.

### HasSkills

`func (o *CreateEnvironmentConfig) HasSkills() bool`

HasSkills returns a boolean if a field has been set.

### GetVars

`func (o *CreateEnvironmentConfig) GetVars() map[string]string`

GetVars returns the Vars field if non-nil, zero value otherwise.

### GetVarsOk

`func (o *CreateEnvironmentConfig) GetVarsOk() (*map[string]string, bool)`

GetVarsOk returns a tuple with the Vars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVars

`func (o *CreateEnvironmentConfig) SetVars(v map[string]string)`

SetVars sets Vars field to given value.

### HasVars

`func (o *CreateEnvironmentConfig) HasVars() bool`

HasVars returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


