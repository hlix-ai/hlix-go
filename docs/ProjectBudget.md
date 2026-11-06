# ProjectBudget

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Defaults** | [**ProjectBudgetDefaults**](ProjectBudgetDefaults.md) |  | 
**Effective** | [**ProjectBudgetEffective**](ProjectBudgetEffective.md) |  | 
**Overrides** | [**ProjectBudgetOverrides**](ProjectBudgetOverrides.md) |  | 
**SpendIsEnforced** | **bool** |  | 
**SpendToDateMicros** | **int64** |  | 
**TotalAgentSpendMicros** | **int64** |  | 
**UnknownCostRuns** | **int32** |  | 

## Methods

### NewProjectBudget

`func NewProjectBudget(defaults ProjectBudgetDefaults, effective ProjectBudgetEffective, overrides ProjectBudgetOverrides, spendIsEnforced bool, spendToDateMicros int64, totalAgentSpendMicros int64, unknownCostRuns int32, ) *ProjectBudget`

NewProjectBudget instantiates a new ProjectBudget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectBudgetWithDefaults

`func NewProjectBudgetWithDefaults() *ProjectBudget`

NewProjectBudgetWithDefaults instantiates a new ProjectBudget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDefaults

`func (o *ProjectBudget) GetDefaults() ProjectBudgetDefaults`

GetDefaults returns the Defaults field if non-nil, zero value otherwise.

### GetDefaultsOk

`func (o *ProjectBudget) GetDefaultsOk() (*ProjectBudgetDefaults, bool)`

GetDefaultsOk returns a tuple with the Defaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaults

`func (o *ProjectBudget) SetDefaults(v ProjectBudgetDefaults)`

SetDefaults sets Defaults field to given value.


### GetEffective

`func (o *ProjectBudget) GetEffective() ProjectBudgetEffective`

GetEffective returns the Effective field if non-nil, zero value otherwise.

### GetEffectiveOk

`func (o *ProjectBudget) GetEffectiveOk() (*ProjectBudgetEffective, bool)`

GetEffectiveOk returns a tuple with the Effective field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffective

`func (o *ProjectBudget) SetEffective(v ProjectBudgetEffective)`

SetEffective sets Effective field to given value.


### GetOverrides

`func (o *ProjectBudget) GetOverrides() ProjectBudgetOverrides`

GetOverrides returns the Overrides field if non-nil, zero value otherwise.

### GetOverridesOk

`func (o *ProjectBudget) GetOverridesOk() (*ProjectBudgetOverrides, bool)`

GetOverridesOk returns a tuple with the Overrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrides

`func (o *ProjectBudget) SetOverrides(v ProjectBudgetOverrides)`

SetOverrides sets Overrides field to given value.


### GetSpendIsEnforced

`func (o *ProjectBudget) GetSpendIsEnforced() bool`

GetSpendIsEnforced returns the SpendIsEnforced field if non-nil, zero value otherwise.

### GetSpendIsEnforcedOk

`func (o *ProjectBudget) GetSpendIsEnforcedOk() (*bool, bool)`

GetSpendIsEnforcedOk returns a tuple with the SpendIsEnforced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpendIsEnforced

`func (o *ProjectBudget) SetSpendIsEnforced(v bool)`

SetSpendIsEnforced sets SpendIsEnforced field to given value.


### GetSpendToDateMicros

`func (o *ProjectBudget) GetSpendToDateMicros() int64`

GetSpendToDateMicros returns the SpendToDateMicros field if non-nil, zero value otherwise.

### GetSpendToDateMicrosOk

`func (o *ProjectBudget) GetSpendToDateMicrosOk() (*int64, bool)`

GetSpendToDateMicrosOk returns a tuple with the SpendToDateMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpendToDateMicros

`func (o *ProjectBudget) SetSpendToDateMicros(v int64)`

SetSpendToDateMicros sets SpendToDateMicros field to given value.


### GetTotalAgentSpendMicros

`func (o *ProjectBudget) GetTotalAgentSpendMicros() int64`

GetTotalAgentSpendMicros returns the TotalAgentSpendMicros field if non-nil, zero value otherwise.

### GetTotalAgentSpendMicrosOk

`func (o *ProjectBudget) GetTotalAgentSpendMicrosOk() (*int64, bool)`

GetTotalAgentSpendMicrosOk returns a tuple with the TotalAgentSpendMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAgentSpendMicros

`func (o *ProjectBudget) SetTotalAgentSpendMicros(v int64)`

SetTotalAgentSpendMicros sets TotalAgentSpendMicros field to given value.


### GetUnknownCostRuns

`func (o *ProjectBudget) GetUnknownCostRuns() int32`

GetUnknownCostRuns returns the UnknownCostRuns field if non-nil, zero value otherwise.

### GetUnknownCostRunsOk

`func (o *ProjectBudget) GetUnknownCostRunsOk() (*int32, bool)`

GetUnknownCostRunsOk returns a tuple with the UnknownCostRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnknownCostRuns

`func (o *ProjectBudget) SetUnknownCostRuns(v int32)`

SetUnknownCostRuns sets UnknownCostRuns field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


