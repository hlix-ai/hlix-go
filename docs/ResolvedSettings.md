# ResolvedSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cycle** | [**ResolvedSettingsCycle**](ResolvedSettingsCycle.md) |  |
**ProjectManager** | [**ResolvedSettingsProjectManager**](ResolvedSettingsProjectManager.md) |  |

## Methods

### NewResolvedSettings

`func NewResolvedSettings(cycle ResolvedSettingsCycle, projectManager ResolvedSettingsProjectManager, ) *ResolvedSettings`

NewResolvedSettings instantiates a new ResolvedSettings object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewResolvedSettingsWithDefaults

`func NewResolvedSettingsWithDefaults() *ResolvedSettings`

NewResolvedSettingsWithDefaults instantiates a new ResolvedSettings object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCycle

`func (o *ResolvedSettings) GetCycle() ResolvedSettingsCycle`

GetCycle returns the Cycle field if non-nil, zero value otherwise.

### GetCycleOk

`func (o *ResolvedSettings) GetCycleOk() (*ResolvedSettingsCycle, bool)`

GetCycleOk returns a tuple with the Cycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycle

`func (o *ResolvedSettings) SetCycle(v ResolvedSettingsCycle)`

SetCycle sets Cycle field to given value.


### GetProjectManager

`func (o *ResolvedSettings) GetProjectManager() ResolvedSettingsProjectManager`

GetProjectManager returns the ProjectManager field if non-nil, zero value otherwise.

### GetProjectManagerOk

`func (o *ResolvedSettings) GetProjectManagerOk() (*ResolvedSettingsProjectManager, bool)`

GetProjectManagerOk returns a tuple with the ProjectManager field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectManager

`func (o *ResolvedSettings) SetProjectManager(v ResolvedSettingsProjectManager)`

SetProjectManager sets ProjectManager field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


