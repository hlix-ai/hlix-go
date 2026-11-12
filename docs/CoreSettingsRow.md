# CoreSettingsRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Coder** | **NullableString** |  |
**CreatedAt** | **string** |  |
**Effort** | **NullableString** |  |
**Funding** | [**NullableCoreSettingsRowFunding**](CoreSettingsRowFunding.md) |  |
**Id** | **string** |  |
**MaxParallelCycles** | **NullableInt32** |  |
**Model** | **NullableString** |  |
**ProjectId** | **NullableString** |  |
**Slot** | **string** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewCoreSettingsRow

`func NewCoreSettingsRow(coder NullableString, createdAt string, effort NullableString, funding NullableCoreSettingsRowFunding, id string, maxParallelCycles NullableInt32, model NullableString, projectId NullableString, slot string, updatedAt string, ) *CoreSettingsRow`

NewCoreSettingsRow instantiates a new CoreSettingsRow object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCoreSettingsRowWithDefaults

`func NewCoreSettingsRowWithDefaults() *CoreSettingsRow`

NewCoreSettingsRowWithDefaults instantiates a new CoreSettingsRow object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCoder

`func (o *CoreSettingsRow) GetCoder() string`

GetCoder returns the Coder field if non-nil, zero value otherwise.

### GetCoderOk

`func (o *CoreSettingsRow) GetCoderOk() (*string, bool)`

GetCoderOk returns a tuple with the Coder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoder

`func (o *CoreSettingsRow) SetCoder(v string)`

SetCoder sets Coder field to given value.


### SetCoderNil

`func (o *CoreSettingsRow) SetCoderNil(b bool)`

 SetCoderNil sets the value for Coder to be an explicit nil

### UnsetCoder
`func (o *CoreSettingsRow) UnsetCoder()`

UnsetCoder ensures that no value is present for Coder, not even an explicit nil
### GetCreatedAt

`func (o *CoreSettingsRow) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CoreSettingsRow) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CoreSettingsRow) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEffort

`func (o *CoreSettingsRow) GetEffort() string`

GetEffort returns the Effort field if non-nil, zero value otherwise.

### GetEffortOk

`func (o *CoreSettingsRow) GetEffortOk() (*string, bool)`

GetEffortOk returns a tuple with the Effort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffort

`func (o *CoreSettingsRow) SetEffort(v string)`

SetEffort sets Effort field to given value.


### SetEffortNil

`func (o *CoreSettingsRow) SetEffortNil(b bool)`

 SetEffortNil sets the value for Effort to be an explicit nil

### UnsetEffort
`func (o *CoreSettingsRow) UnsetEffort()`

UnsetEffort ensures that no value is present for Effort, not even an explicit nil
### GetFunding

`func (o *CoreSettingsRow) GetFunding() CoreSettingsRowFunding`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *CoreSettingsRow) GetFundingOk() (*CoreSettingsRowFunding, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *CoreSettingsRow) SetFunding(v CoreSettingsRowFunding)`

SetFunding sets Funding field to given value.


### SetFundingNil

`func (o *CoreSettingsRow) SetFundingNil(b bool)`

 SetFundingNil sets the value for Funding to be an explicit nil

### UnsetFunding
`func (o *CoreSettingsRow) UnsetFunding()`

UnsetFunding ensures that no value is present for Funding, not even an explicit nil
### GetId

`func (o *CoreSettingsRow) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CoreSettingsRow) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CoreSettingsRow) SetId(v string)`

SetId sets Id field to given value.


### GetMaxParallelCycles

`func (o *CoreSettingsRow) GetMaxParallelCycles() int32`

GetMaxParallelCycles returns the MaxParallelCycles field if non-nil, zero value otherwise.

### GetMaxParallelCyclesOk

`func (o *CoreSettingsRow) GetMaxParallelCyclesOk() (*int32, bool)`

GetMaxParallelCyclesOk returns a tuple with the MaxParallelCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxParallelCycles

`func (o *CoreSettingsRow) SetMaxParallelCycles(v int32)`

SetMaxParallelCycles sets MaxParallelCycles field to given value.


### SetMaxParallelCyclesNil

`func (o *CoreSettingsRow) SetMaxParallelCyclesNil(b bool)`

 SetMaxParallelCyclesNil sets the value for MaxParallelCycles to be an explicit nil

### UnsetMaxParallelCycles
`func (o *CoreSettingsRow) UnsetMaxParallelCycles()`

UnsetMaxParallelCycles ensures that no value is present for MaxParallelCycles, not even an explicit nil
### GetModel

`func (o *CoreSettingsRow) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CoreSettingsRow) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CoreSettingsRow) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *CoreSettingsRow) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *CoreSettingsRow) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetProjectId

`func (o *CoreSettingsRow) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CoreSettingsRow) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CoreSettingsRow) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *CoreSettingsRow) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *CoreSettingsRow) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetSlot

`func (o *CoreSettingsRow) GetSlot() string`

GetSlot returns the Slot field if non-nil, zero value otherwise.

### GetSlotOk

`func (o *CoreSettingsRow) GetSlotOk() (*string, bool)`

GetSlotOk returns a tuple with the Slot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlot

`func (o *CoreSettingsRow) SetSlot(v string)`

SetSlot sets Slot field to given value.


### GetUpdatedAt

`func (o *CoreSettingsRow) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CoreSettingsRow) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CoreSettingsRow) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


