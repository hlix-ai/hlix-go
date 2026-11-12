# CreateCustomSkill

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** |  |
**Description** | **string** |  |
**Enabled** | Pointer to **bool** |  | [optional]
**Name** | **string** |  |
**ProjectIds** | Pointer to **[]string** |  | [optional]
**Slug** | **string** |  |

## Methods

### NewCreateCustomSkill

`func NewCreateCustomSkill(content string, description string, name string, slug string, ) *CreateCustomSkill`

NewCreateCustomSkill instantiates a new CreateCustomSkill object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateCustomSkillWithDefaults

`func NewCreateCustomSkillWithDefaults() *CreateCustomSkill`

NewCreateCustomSkillWithDefaults instantiates a new CreateCustomSkill object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetContent

`func (o *CreateCustomSkill) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateCustomSkill) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateCustomSkill) SetContent(v string)`

SetContent sets Content field to given value.


### GetDescription

`func (o *CreateCustomSkill) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateCustomSkill) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateCustomSkill) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEnabled

`func (o *CreateCustomSkill) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateCustomSkill) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateCustomSkill) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateCustomSkill) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetName

`func (o *CreateCustomSkill) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCustomSkill) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCustomSkill) SetName(v string)`

SetName sets Name field to given value.


### GetProjectIds

`func (o *CreateCustomSkill) GetProjectIds() []string`

GetProjectIds returns the ProjectIds field if non-nil, zero value otherwise.

### GetProjectIdsOk

`func (o *CreateCustomSkill) GetProjectIdsOk() (*[]string, bool)`

GetProjectIdsOk returns a tuple with the ProjectIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectIds

`func (o *CreateCustomSkill) SetProjectIds(v []string)`

SetProjectIds sets ProjectIds field to given value.

### HasProjectIds

`func (o *CreateCustomSkill) HasProjectIds() bool`

HasProjectIds returns a boolean if a field has been set.

### GetSlug

`func (o *CreateCustomSkill) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CreateCustomSkill) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CreateCustomSkill) SetSlug(v string)`

SetSlug sets Slug field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


