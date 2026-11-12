# UpsertSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Coder** | Pointer to **NullableString** |  | [optional]
**Effort** | Pointer to **NullableString** |  | [optional]
**Funding** | Pointer to [**NullableUpsertSettingsFunding**](UpsertSettingsFunding.md) |  | [optional]
**MaxParallelCycles** | Pointer to **NullableInt32** |  | [optional]
**Model** | Pointer to **NullableString** |  | [optional]

## Methods

### NewUpsertSettings

`func NewUpsertSettings() *UpsertSettings`

NewUpsertSettings instantiates a new UpsertSettings object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpsertSettingsWithDefaults

`func NewUpsertSettingsWithDefaults() *UpsertSettings`

NewUpsertSettingsWithDefaults instantiates a new UpsertSettings object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCoder

`func (o *UpsertSettings) GetCoder() string`

GetCoder returns the Coder field if non-nil, zero value otherwise.

### GetCoderOk

`func (o *UpsertSettings) GetCoderOk() (*string, bool)`

GetCoderOk returns a tuple with the Coder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoder

`func (o *UpsertSettings) SetCoder(v string)`

SetCoder sets Coder field to given value.

### HasCoder

`func (o *UpsertSettings) HasCoder() bool`

HasCoder returns a boolean if a field has been set.

### SetCoderNil

`func (o *UpsertSettings) SetCoderNil(b bool)`

 SetCoderNil sets the value for Coder to be an explicit nil

### UnsetCoder
`func (o *UpsertSettings) UnsetCoder()`

UnsetCoder ensures that no value is present for Coder, not even an explicit nil
### GetEffort

`func (o *UpsertSettings) GetEffort() string`

GetEffort returns the Effort field if non-nil, zero value otherwise.

### GetEffortOk

`func (o *UpsertSettings) GetEffortOk() (*string, bool)`

GetEffortOk returns a tuple with the Effort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffort

`func (o *UpsertSettings) SetEffort(v string)`

SetEffort sets Effort field to given value.

### HasEffort

`func (o *UpsertSettings) HasEffort() bool`

HasEffort returns a boolean if a field has been set.

### SetEffortNil

`func (o *UpsertSettings) SetEffortNil(b bool)`

 SetEffortNil sets the value for Effort to be an explicit nil

### UnsetEffort
`func (o *UpsertSettings) UnsetEffort()`

UnsetEffort ensures that no value is present for Effort, not even an explicit nil
### GetFunding

`func (o *UpsertSettings) GetFunding() UpsertSettingsFunding`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *UpsertSettings) GetFundingOk() (*UpsertSettingsFunding, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *UpsertSettings) SetFunding(v UpsertSettingsFunding)`

SetFunding sets Funding field to given value.

### HasFunding

`func (o *UpsertSettings) HasFunding() bool`

HasFunding returns a boolean if a field has been set.

### SetFundingNil

`func (o *UpsertSettings) SetFundingNil(b bool)`

 SetFundingNil sets the value for Funding to be an explicit nil

### UnsetFunding
`func (o *UpsertSettings) UnsetFunding()`

UnsetFunding ensures that no value is present for Funding, not even an explicit nil
### GetMaxParallelCycles

`func (o *UpsertSettings) GetMaxParallelCycles() int32`

GetMaxParallelCycles returns the MaxParallelCycles field if non-nil, zero value otherwise.

### GetMaxParallelCyclesOk

`func (o *UpsertSettings) GetMaxParallelCyclesOk() (*int32, bool)`

GetMaxParallelCyclesOk returns a tuple with the MaxParallelCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxParallelCycles

`func (o *UpsertSettings) SetMaxParallelCycles(v int32)`

SetMaxParallelCycles sets MaxParallelCycles field to given value.

### HasMaxParallelCycles

`func (o *UpsertSettings) HasMaxParallelCycles() bool`

HasMaxParallelCycles returns a boolean if a field has been set.

### SetMaxParallelCyclesNil

`func (o *UpsertSettings) SetMaxParallelCyclesNil(b bool)`

 SetMaxParallelCyclesNil sets the value for MaxParallelCycles to be an explicit nil

### UnsetMaxParallelCycles
`func (o *UpsertSettings) UnsetMaxParallelCycles()`

UnsetMaxParallelCycles ensures that no value is present for MaxParallelCycles, not even an explicit nil
### GetModel

`func (o *UpsertSettings) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *UpsertSettings) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *UpsertSettings) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *UpsertSettings) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *UpsertSettings) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *UpsertSettings) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


