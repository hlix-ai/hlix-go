# CreatePlugin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Inputs** | **map[string]string** |  |
**Manifest** | [**CreatePluginManifest**](CreatePluginManifest.md) |  |
**ProjectIds** | **[]string** |  |

## Methods

### NewCreatePlugin

`func NewCreatePlugin(inputs map[string]string, manifest CreatePluginManifest, projectIds []string, ) *CreatePlugin`

NewCreatePlugin instantiates a new CreatePlugin object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreatePluginWithDefaults

`func NewCreatePluginWithDefaults() *CreatePlugin`

NewCreatePluginWithDefaults instantiates a new CreatePlugin object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetInputs

`func (o *CreatePlugin) GetInputs() map[string]string`

GetInputs returns the Inputs field if non-nil, zero value otherwise.

### GetInputsOk

`func (o *CreatePlugin) GetInputsOk() (*map[string]string, bool)`

GetInputsOk returns a tuple with the Inputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputs

`func (o *CreatePlugin) SetInputs(v map[string]string)`

SetInputs sets Inputs field to given value.


### GetManifest

`func (o *CreatePlugin) GetManifest() CreatePluginManifest`

GetManifest returns the Manifest field if non-nil, zero value otherwise.

### GetManifestOk

`func (o *CreatePlugin) GetManifestOk() (*CreatePluginManifest, bool)`

GetManifestOk returns a tuple with the Manifest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifest

`func (o *CreatePlugin) SetManifest(v CreatePluginManifest)`

SetManifest sets Manifest field to given value.


### GetProjectIds

`func (o *CreatePlugin) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *CreatePlugin) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *CreatePlugin) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.


### SetProjectIdsNil

`func (o *CreatePlugin) SetProjectIdsNil(b bool)`

 SetProjectIdsNil sets the value for ProjectIds to be an explicit nil

### UnsetProjectIds
`func (o *CreatePlugin) UnsetProjectIds()`

UnsetProjectIds ensures that no value is present for ProjectIds, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


