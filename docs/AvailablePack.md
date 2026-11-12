# AvailablePack

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentSlugs** | **[]string** |  |
**AlwaysOn** | Pointer to **bool** |  | [optional]
**Category** | **string** |  |
**Description** | **string** |  |
**IsActive** | **bool** |  |
**Keywords** | **[]string** |  |
**Name** | **string** |  |
**ProjectPackId** | **NullableString** |  |
**SkillSlugs** | **[]string** |  |
**Source** | Pointer to **string** |  | [optional]
**System** | Pointer to **bool** |  | [optional]
**Version** | **string** |  |

## Methods

### NewAvailablePack

`func NewAvailablePack(agentSlugs []string, category string, description string, isActive bool, keywords []string, name string, projectPackId NullableString, skillSlugs []string, version string, ) *AvailablePack`

NewAvailablePack instantiates a new AvailablePack object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAvailablePackWithDefaults

`func NewAvailablePackWithDefaults() *AvailablePack`

NewAvailablePackWithDefaults instantiates a new AvailablePack object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentSlugs

`func (o *AvailablePack) GetAgentSlugs() []string`

GetAgentSlugs returns the AgentSlugs field if non-nil, zero value otherwise.

### GetAgentSlugsOk

`func (o *AvailablePack) GetAgentSlugsOk() (*[]string, bool)`

GetAgentSlugsOk returns a tuple with the AgentSlugs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentSlugs

`func (o *AvailablePack) SetAgentSlugs(v []string)`

SetAgentSlugs sets AgentSlugs field to given value.


### GetAlwaysOn

`func (o *AvailablePack) GetAlwaysOn() bool`

GetAlwaysOn returns the AlwaysOn field if non-nil, zero value otherwise.

### GetAlwaysOnOk

`func (o *AvailablePack) GetAlwaysOnOk() (*bool, bool)`

GetAlwaysOnOk returns a tuple with the AlwaysOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlwaysOn

`func (o *AvailablePack) SetAlwaysOn(v bool)`

SetAlwaysOn sets AlwaysOn field to given value.

### HasAlwaysOn

`func (o *AvailablePack) HasAlwaysOn() bool`

HasAlwaysOn returns a boolean if a field has been set.

### GetCategory

`func (o *AvailablePack) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AvailablePack) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AvailablePack) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetDescription

`func (o *AvailablePack) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AvailablePack) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AvailablePack) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetIsActive

`func (o *AvailablePack) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *AvailablePack) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *AvailablePack) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetKeywords

`func (o *AvailablePack) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *AvailablePack) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *AvailablePack) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetName

`func (o *AvailablePack) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AvailablePack) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AvailablePack) SetName(v string)`

SetName sets Name field to given value.


### GetProjectPackId

`func (o *AvailablePack) GetProjectPackId() string`

GetProjectPackId returns the ProjectPackId field if non-nil, zero value otherwise.

### GetProjectPackIdOk

`func (o *AvailablePack) GetProjectPackIdOk() (*string, bool)`

GetProjectPackIdOk returns a tuple with the ProjectPackId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectPackId

`func (o *AvailablePack) SetProjectPackId(v string)`

SetProjectPackId sets ProjectPackId field to given value.


### SetProjectPackIdNil

`func (o *AvailablePack) SetProjectPackIdNil(b bool)`

 SetProjectPackIdNil sets the value for ProjectPackId to be an explicit nil

### UnsetProjectPackId
`func (o *AvailablePack) UnsetProjectPackId()`

UnsetProjectPackId ensures that no value is present for ProjectPackId, not even an explicit nil
### GetSkillSlugs

`func (o *AvailablePack) GetSkillSlugs() []string`

GetSkillSlugs returns the SkillSlugs field if non-nil, zero value otherwise.

### GetSkillSlugsOk

`func (o *AvailablePack) GetSkillSlugsOk() (*[]string, bool)`

GetSkillSlugsOk returns a tuple with the SkillSlugs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkillSlugs

`func (o *AvailablePack) SetSkillSlugs(v []string)`

SetSkillSlugs sets SkillSlugs field to given value.


### GetSource

`func (o *AvailablePack) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AvailablePack) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AvailablePack) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *AvailablePack) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetSystem

`func (o *AvailablePack) GetSystem() bool`

GetSystem returns the System field if non-nil, zero value otherwise.

### GetSystemOk

`func (o *AvailablePack) GetSystemOk() (*bool, bool)`

GetSystemOk returns a tuple with the System field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystem

`func (o *AvailablePack) SetSystem(v bool)`

SetSystem sets System field to given value.

### HasSystem

`func (o *AvailablePack) HasSystem() bool`

HasSystem returns a boolean if a field has been set.

### GetVersion

`func (o *AvailablePack) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *AvailablePack) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *AvailablePack) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


