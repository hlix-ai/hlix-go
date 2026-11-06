# CreatePluginManifest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** |  | 
**Id** | **string** |  | 
**Inputs** | [**[]CreatePluginManifestInputsInner**](CreatePluginManifestInputsInner.md) |  | 
**McpServers** | [**[]CreatePluginManifestMcpServersInner**](CreatePluginManifestMcpServersInner.md) |  | 
**Name** | **string** |  | 
**SchemaVersion** | **float32** |  | 
**Setup** | Pointer to **string** |  | [optional] 
**Skills** | [**[]CreatePluginManifestSkillsInner**](CreatePluginManifestSkillsInner.md) |  | 
**Source** | Pointer to [**CreatePluginManifestSource**](CreatePluginManifestSource.md) |  | [optional] 
**Version** | **string** |  | 

## Methods

### NewCreatePluginManifest

`func NewCreatePluginManifest(description string, id string, inputs []CreatePluginManifestInputsInner, mcpServers []CreatePluginManifestMcpServersInner, name string, schemaVersion float32, skills []CreatePluginManifestSkillsInner, version string, ) *CreatePluginManifest`

NewCreatePluginManifest instantiates a new CreatePluginManifest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePluginManifestWithDefaults

`func NewCreatePluginManifestWithDefaults() *CreatePluginManifest`

NewCreatePluginManifestWithDefaults instantiates a new CreatePluginManifest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *CreatePluginManifest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreatePluginManifest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreatePluginManifest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *CreatePluginManifest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreatePluginManifest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreatePluginManifest) SetId(v string)`

SetId sets Id field to given value.


### GetInputs

`func (o *CreatePluginManifest) GetInputs() []CreatePluginManifestInputsInner`

GetInputs returns the Inputs field if non-nil, zero value otherwise.

### GetInputsOk

`func (o *CreatePluginManifest) GetInputsOk() (*[]CreatePluginManifestInputsInner, bool)`

GetInputsOk returns a tuple with the Inputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputs

`func (o *CreatePluginManifest) SetInputs(v []CreatePluginManifestInputsInner)`

SetInputs sets Inputs field to given value.


### GetMcpServers

`func (o *CreatePluginManifest) GetMcpServers() []CreatePluginManifestMcpServersInner`

GetMcpServers returns the McpServers field if non-nil, zero value otherwise.

### GetMcpServersOk

`func (o *CreatePluginManifest) GetMcpServersOk() (*[]CreatePluginManifestMcpServersInner, bool)`

GetMcpServersOk returns a tuple with the McpServers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMcpServers

`func (o *CreatePluginManifest) SetMcpServers(v []CreatePluginManifestMcpServersInner)`

SetMcpServers sets McpServers field to given value.


### GetName

`func (o *CreatePluginManifest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreatePluginManifest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreatePluginManifest) SetName(v string)`

SetName sets Name field to given value.


### GetSchemaVersion

`func (o *CreatePluginManifest) GetSchemaVersion() float32`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *CreatePluginManifest) GetSchemaVersionOk() (*float32, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *CreatePluginManifest) SetSchemaVersion(v float32)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetSetup

`func (o *CreatePluginManifest) GetSetup() string`

GetSetup returns the Setup field if non-nil, zero value otherwise.

### GetSetupOk

`func (o *CreatePluginManifest) GetSetupOk() (*string, bool)`

GetSetupOk returns a tuple with the Setup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetup

`func (o *CreatePluginManifest) SetSetup(v string)`

SetSetup sets Setup field to given value.

### HasSetup

`func (o *CreatePluginManifest) HasSetup() bool`

HasSetup returns a boolean if a field has been set.

### GetSkills

`func (o *CreatePluginManifest) GetSkills() []CreatePluginManifestSkillsInner`

GetSkills returns the Skills field if non-nil, zero value otherwise.

### GetSkillsOk

`func (o *CreatePluginManifest) GetSkillsOk() (*[]CreatePluginManifestSkillsInner, bool)`

GetSkillsOk returns a tuple with the Skills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkills

`func (o *CreatePluginManifest) SetSkills(v []CreatePluginManifestSkillsInner)`

SetSkills sets Skills field to given value.


### GetSource

`func (o *CreatePluginManifest) GetSource() CreatePluginManifestSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreatePluginManifest) GetSourceOk() (*CreatePluginManifestSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreatePluginManifest) SetSource(v CreatePluginManifestSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *CreatePluginManifest) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetVersion

`func (o *CreatePluginManifest) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CreatePluginManifest) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CreatePluginManifest) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


