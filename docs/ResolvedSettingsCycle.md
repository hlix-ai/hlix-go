# ResolvedSettingsCycle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Effort** | **NullableString** |  | 
**Funding** | [**ResolvedSettingsCycleFunding**](ResolvedSettingsCycleFunding.md) |  | 
**Harness** | **string** |  | 
**HarnessScopeId** | **NullableString** |  | 
**MaxParallelCycles** | **NullableInt32** |  | 
**Model** | **NullableString** |  | 
**Source** | [**ResolvedSettingsCycleSource**](ResolvedSettingsCycleSource.md) |  | 

## Methods

### NewResolvedSettingsCycle

`func NewResolvedSettingsCycle(effort NullableString, funding ResolvedSettingsCycleFunding, harness string, harnessScopeId NullableString, maxParallelCycles NullableInt32, model NullableString, source ResolvedSettingsCycleSource, ) *ResolvedSettingsCycle`

NewResolvedSettingsCycle instantiates a new ResolvedSettingsCycle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResolvedSettingsCycleWithDefaults

`func NewResolvedSettingsCycleWithDefaults() *ResolvedSettingsCycle`

NewResolvedSettingsCycleWithDefaults instantiates a new ResolvedSettingsCycle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEffort

`func (o *ResolvedSettingsCycle) GetEffort() string`

GetEffort returns the Effort field if non-nil, zero value otherwise.

### GetEffortOk

`func (o *ResolvedSettingsCycle) GetEffortOk() (*string, bool)`

GetEffortOk returns a tuple with the Effort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffort

`func (o *ResolvedSettingsCycle) SetEffort(v string)`

SetEffort sets Effort field to given value.


### SetEffortNil

`func (o *ResolvedSettingsCycle) SetEffortNil(b bool)`

 SetEffortNil sets the value for Effort to be an explicit nil

### UnsetEffort
`func (o *ResolvedSettingsCycle) UnsetEffort()`

UnsetEffort ensures that no value is present for Effort, not even an explicit nil
### GetFunding

`func (o *ResolvedSettingsCycle) GetFunding() ResolvedSettingsCycleFunding`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *ResolvedSettingsCycle) GetFundingOk() (*ResolvedSettingsCycleFunding, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *ResolvedSettingsCycle) SetFunding(v ResolvedSettingsCycleFunding)`

SetFunding sets Funding field to given value.


### GetHarness

`func (o *ResolvedSettingsCycle) GetHarness() string`

GetHarness returns the Harness field if non-nil, zero value otherwise.

### GetHarnessOk

`func (o *ResolvedSettingsCycle) GetHarnessOk() (*string, bool)`

GetHarnessOk returns a tuple with the Harness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHarness

`func (o *ResolvedSettingsCycle) SetHarness(v string)`

SetHarness sets Harness field to given value.


### GetHarnessScopeId

`func (o *ResolvedSettingsCycle) GetHarnessScopeId() string`

GetHarnessScopeId returns the HarnessScopeId field if non-nil, zero value otherwise.

### GetHarnessScopeIdOk

`func (o *ResolvedSettingsCycle) GetHarnessScopeIdOk() (*string, bool)`

GetHarnessScopeIdOk returns a tuple with the HarnessScopeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHarnessScopeId

`func (o *ResolvedSettingsCycle) SetHarnessScopeId(v string)`

SetHarnessScopeId sets HarnessScopeId field to given value.


### SetHarnessScopeIdNil

`func (o *ResolvedSettingsCycle) SetHarnessScopeIdNil(b bool)`

 SetHarnessScopeIdNil sets the value for HarnessScopeId to be an explicit nil

### UnsetHarnessScopeId
`func (o *ResolvedSettingsCycle) UnsetHarnessScopeId()`

UnsetHarnessScopeId ensures that no value is present for HarnessScopeId, not even an explicit nil
### GetMaxParallelCycles

`func (o *ResolvedSettingsCycle) GetMaxParallelCycles() int32`

GetMaxParallelCycles returns the MaxParallelCycles field if non-nil, zero value otherwise.

### GetMaxParallelCyclesOk

`func (o *ResolvedSettingsCycle) GetMaxParallelCyclesOk() (*int32, bool)`

GetMaxParallelCyclesOk returns a tuple with the MaxParallelCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxParallelCycles

`func (o *ResolvedSettingsCycle) SetMaxParallelCycles(v int32)`

SetMaxParallelCycles sets MaxParallelCycles field to given value.


### SetMaxParallelCyclesNil

`func (o *ResolvedSettingsCycle) SetMaxParallelCyclesNil(b bool)`

 SetMaxParallelCyclesNil sets the value for MaxParallelCycles to be an explicit nil

### UnsetMaxParallelCycles
`func (o *ResolvedSettingsCycle) UnsetMaxParallelCycles()`

UnsetMaxParallelCycles ensures that no value is present for MaxParallelCycles, not even an explicit nil
### GetModel

`func (o *ResolvedSettingsCycle) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *ResolvedSettingsCycle) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *ResolvedSettingsCycle) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *ResolvedSettingsCycle) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *ResolvedSettingsCycle) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetSource

`func (o *ResolvedSettingsCycle) GetSource() ResolvedSettingsCycleSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ResolvedSettingsCycle) GetSourceOk() (*ResolvedSettingsCycleSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ResolvedSettingsCycle) SetSource(v ResolvedSettingsCycleSource)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


