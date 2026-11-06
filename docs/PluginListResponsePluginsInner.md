# PluginListResponsePluginsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConfiguredInputs** | **[]string** |  | 
**CreatedAt** | **string** |  | 
**Enabled** | **bool** |  | 
**Id** | **string** |  | 
**Inputs** | **map[string]string** |  | 
**Manifest** | [**CreatePluginManifest**](CreatePluginManifest.md) |  | 
**ProjectIds** | **[]string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewPluginListResponsePluginsInner

`func NewPluginListResponsePluginsInner(configuredInputs []string, createdAt string, enabled bool, id string, inputs map[string]string, manifest CreatePluginManifest, projectIds []string, updatedAt string, ) *PluginListResponsePluginsInner`

NewPluginListResponsePluginsInner instantiates a new PluginListResponsePluginsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginListResponsePluginsInnerWithDefaults

`func NewPluginListResponsePluginsInnerWithDefaults() *PluginListResponsePluginsInner`

NewPluginListResponsePluginsInnerWithDefaults instantiates a new PluginListResponsePluginsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfiguredInputs

`func (o *PluginListResponsePluginsInner) GetConfiguredInputs() []string`

GetConfiguredInputs returns the ConfiguredInputs field if non-nil, zero value otherwise.

### GetConfiguredInputsOk

`func (o *PluginListResponsePluginsInner) GetConfiguredInputsOk() (*[]string, bool)`

GetConfiguredInputsOk returns a tuple with the ConfiguredInputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguredInputs

`func (o *PluginListResponsePluginsInner) SetConfiguredInputs(v []string)`

SetConfiguredInputs sets ConfiguredInputs field to given value.


### GetCreatedAt

`func (o *PluginListResponsePluginsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PluginListResponsePluginsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PluginListResponsePluginsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEnabled

`func (o *PluginListResponsePluginsInner) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *PluginListResponsePluginsInner) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *PluginListResponsePluginsInner) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetId

`func (o *PluginListResponsePluginsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PluginListResponsePluginsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PluginListResponsePluginsInner) SetId(v string)`

SetId sets Id field to given value.


### GetInputs

`func (o *PluginListResponsePluginsInner) GetInputs() map[string]string`

GetInputs returns the Inputs field if non-nil, zero value otherwise.

### GetInputsOk

`func (o *PluginListResponsePluginsInner) GetInputsOk() (*map[string]string, bool)`

GetInputsOk returns a tuple with the Inputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputs

`func (o *PluginListResponsePluginsInner) SetInputs(v map[string]string)`

SetInputs sets Inputs field to given value.


### GetManifest

`func (o *PluginListResponsePluginsInner) GetManifest() CreatePluginManifest`

GetManifest returns the Manifest field if non-nil, zero value otherwise.

### GetManifestOk

`func (o *PluginListResponsePluginsInner) GetManifestOk() (*CreatePluginManifest, bool)`

GetManifestOk returns a tuple with the Manifest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifest

`func (o *PluginListResponsePluginsInner) SetManifest(v CreatePluginManifest)`

SetManifest sets Manifest field to given value.


### GetProjectIds

`func (o *PluginListResponsePluginsInner) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *PluginListResponsePluginsInner) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *PluginListResponsePluginsInner) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.


### SetProjectIdsNil

`func (o *PluginListResponsePluginsInner) SetProjectIdsNil(b bool)`

 SetProjectIdsNil sets the value for ProjectIds to be an explicit nil

### UnsetProjectIds
`func (o *PluginListResponsePluginsInner) UnsetProjectIds()`

UnsetProjectIds ensures that no value is present for ProjectIds, not even an explicit nil
### GetUpdatedAt

`func (o *PluginListResponsePluginsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PluginListResponsePluginsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PluginListResponsePluginsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


