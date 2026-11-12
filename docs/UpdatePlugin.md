# UpdatePlugin

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | Pointer to **bool** |  | [optional]
**Inputs** | Pointer to [**map[string]UpdatePluginInputsValue**](UpdatePluginInputsValue.md) |  | [optional]
**Manifest** | Pointer to [**CreatePluginManifest**](CreatePluginManifest.md) |  | [optional]
**ProjectIds** | Pointer to **[]string** |  | [optional]

## Methods

### NewUpdatePlugin

`func NewUpdatePlugin() *UpdatePlugin`

NewUpdatePlugin instantiates a new UpdatePlugin object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpdatePluginWithDefaults

`func NewUpdatePluginWithDefaults() *UpdatePlugin`

NewUpdatePluginWithDefaults instantiates a new UpdatePlugin object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetEnabled

`func (o *UpdatePlugin) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpdatePlugin) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpdatePlugin) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpdatePlugin) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetInputs

`func (o *UpdatePlugin) GetInputs() map[string]UpdatePluginInputsValue`

GetInputs returns the Inputs field if non-nil, zero value otherwise.

### GetInputsOk

`func (o *UpdatePlugin) GetInputsOk() (*map[string]UpdatePluginInputsValue, bool)`

GetInputsOk returns a tuple with the Inputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputs

`func (o *UpdatePlugin) SetInputs(v map[string]UpdatePluginInputsValue)`

SetInputs sets Inputs field to given value.

### HasInputs

`func (o *UpdatePlugin) HasInputs() bool`

HasInputs returns a boolean if a field has been set.

### GetManifest

`func (o *UpdatePlugin) GetManifest() CreatePluginManifest`

GetManifest returns the Manifest field if non-nil, zero value otherwise.

### GetManifestOk

`func (o *UpdatePlugin) GetManifestOk() (*CreatePluginManifest, bool)`

GetManifestOk returns a tuple with the Manifest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifest

`func (o *UpdatePlugin) SetManifest(v CreatePluginManifest)`

SetManifest sets Manifest field to given value.

### HasManifest

`func (o *UpdatePlugin) HasManifest() bool`

HasManifest returns a boolean if a field has been set.

### GetProjectIds

`func (o *UpdatePlugin) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *UpdatePlugin) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *UpdatePlugin) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *UpdatePlugin) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### SetProjectIdsNil

`func (o *UpdatePlugin) SetProjectIdsNil(b bool)`

 SetProjectIdsNil sets the value for ProjectIds to be an explicit nil

### UnsetProjectIds
`func (o *UpdatePlugin) UnsetProjectIds()`

UnsetProjectIds ensures that no value is present for ProjectIds, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


