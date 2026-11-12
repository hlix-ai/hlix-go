# CycleMetricsAutomationQuality

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AutomatedShare** | **NullableFloat32** |  |
**AutomatedStageExits** | **int32** |  |
**CleanAutomatedExits** | **int32** |  |
**HumanStageExits** | **int32** |  |
**QualityAdjustedShare** | **NullableFloat32** |  |
**ReworkedAutomatedExits** | **int32** |  |
**TotalStageExits** | **int32** |  |

## Methods

### NewCycleMetricsAutomationQuality

`func NewCycleMetricsAutomationQuality(automatedShare NullableFloat32, automatedStageExits int32, cleanAutomatedExits int32, humanStageExits int32, qualityAdjustedShare NullableFloat32, reworkedAutomatedExits int32, totalStageExits int32, ) *CycleMetricsAutomationQuality`

NewCycleMetricsAutomationQuality instantiates a new CycleMetricsAutomationQuality object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleMetricsAutomationQualityWithDefaults

`func NewCycleMetricsAutomationQualityWithDefaults() *CycleMetricsAutomationQuality`

NewCycleMetricsAutomationQualityWithDefaults instantiates a new CycleMetricsAutomationQuality object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAutomatedShare

`func (o *CycleMetricsAutomationQuality) GetAutomatedShare() float32`

GetAutomatedShare returns the AutomatedShare field if non-nil, zero value otherwise.

### GetAutomatedShareOk

`func (o *CycleMetricsAutomationQuality) GetAutomatedShareOk() (*float32, bool)`

GetAutomatedShareOk returns a tuple with the AutomatedShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomatedShare

`func (o *CycleMetricsAutomationQuality) SetAutomatedShare(v float32)`

SetAutomatedShare sets AutomatedShare field to given value.


### SetAutomatedShareNil

`func (o *CycleMetricsAutomationQuality) SetAutomatedShareNil(b bool)`

 SetAutomatedShareNil sets the value for AutomatedShare to be an explicit nil

### UnsetAutomatedShare
`func (o *CycleMetricsAutomationQuality) UnsetAutomatedShare()`

UnsetAutomatedShare ensures that no value is present for AutomatedShare, not even an explicit nil
### GetAutomatedStageExits

`func (o *CycleMetricsAutomationQuality) GetAutomatedStageExits() int32`

GetAutomatedStageExits returns the AutomatedStageExits field if non-nil, zero value otherwise.

### GetAutomatedStageExitsOk

`func (o *CycleMetricsAutomationQuality) GetAutomatedStageExitsOk() (*int32, bool)`

GetAutomatedStageExitsOk returns a tuple with the AutomatedStageExits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomatedStageExits

`func (o *CycleMetricsAutomationQuality) SetAutomatedStageExits(v int32)`

SetAutomatedStageExits sets AutomatedStageExits field to given value.


### GetCleanAutomatedExits

`func (o *CycleMetricsAutomationQuality) GetCleanAutomatedExits() int32`

GetCleanAutomatedExits returns the CleanAutomatedExits field if non-nil, zero value otherwise.

### GetCleanAutomatedExitsOk

`func (o *CycleMetricsAutomationQuality) GetCleanAutomatedExitsOk() (*int32, bool)`

GetCleanAutomatedExitsOk returns a tuple with the CleanAutomatedExits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleanAutomatedExits

`func (o *CycleMetricsAutomationQuality) SetCleanAutomatedExits(v int32)`

SetCleanAutomatedExits sets CleanAutomatedExits field to given value.


### GetHumanStageExits

`func (o *CycleMetricsAutomationQuality) GetHumanStageExits() int32`

GetHumanStageExits returns the HumanStageExits field if non-nil, zero value otherwise.

### GetHumanStageExitsOk

`func (o *CycleMetricsAutomationQuality) GetHumanStageExitsOk() (*int32, bool)`

GetHumanStageExitsOk returns a tuple with the HumanStageExits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHumanStageExits

`func (o *CycleMetricsAutomationQuality) SetHumanStageExits(v int32)`

SetHumanStageExits sets HumanStageExits field to given value.


### GetQualityAdjustedShare

`func (o *CycleMetricsAutomationQuality) GetQualityAdjustedShare() float32`

GetQualityAdjustedShare returns the QualityAdjustedShare field if non-nil, zero value otherwise.

### GetQualityAdjustedShareOk

`func (o *CycleMetricsAutomationQuality) GetQualityAdjustedShareOk() (*float32, bool)`

GetQualityAdjustedShareOk returns a tuple with the QualityAdjustedShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualityAdjustedShare

`func (o *CycleMetricsAutomationQuality) SetQualityAdjustedShare(v float32)`

SetQualityAdjustedShare sets QualityAdjustedShare field to given value.


### SetQualityAdjustedShareNil

`func (o *CycleMetricsAutomationQuality) SetQualityAdjustedShareNil(b bool)`

 SetQualityAdjustedShareNil sets the value for QualityAdjustedShare to be an explicit nil

### UnsetQualityAdjustedShare
`func (o *CycleMetricsAutomationQuality) UnsetQualityAdjustedShare()`

UnsetQualityAdjustedShare ensures that no value is present for QualityAdjustedShare, not even an explicit nil
### GetReworkedAutomatedExits

`func (o *CycleMetricsAutomationQuality) GetReworkedAutomatedExits() int32`

GetReworkedAutomatedExits returns the ReworkedAutomatedExits field if non-nil, zero value otherwise.

### GetReworkedAutomatedExitsOk

`func (o *CycleMetricsAutomationQuality) GetReworkedAutomatedExitsOk() (*int32, bool)`

GetReworkedAutomatedExitsOk returns a tuple with the ReworkedAutomatedExits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReworkedAutomatedExits

`func (o *CycleMetricsAutomationQuality) SetReworkedAutomatedExits(v int32)`

SetReworkedAutomatedExits sets ReworkedAutomatedExits field to given value.


### GetTotalStageExits

`func (o *CycleMetricsAutomationQuality) GetTotalStageExits() int32`

GetTotalStageExits returns the TotalStageExits field if non-nil, zero value otherwise.

### GetTotalStageExitsOk

`func (o *CycleMetricsAutomationQuality) GetTotalStageExitsOk() (*int32, bool)`

GetTotalStageExitsOk returns a tuple with the TotalStageExits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalStageExits

`func (o *CycleMetricsAutomationQuality) SetTotalStageExits(v int32)`

SetTotalStageExits sets TotalStageExits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


