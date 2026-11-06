# GrowthProviderComparisonResultsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BilledMicros** | **int64** |  | 
**CostStatus** | **string** |  | 
**EstimatedCostMicros** | **NullableInt64** |  | 
**Failed** | **int32** |  | 
**Found** | **int32** |  | 
**Pending** | **int32** |  | 
**Provider** | **string** |  | 
**ProviderCostMicros** | **NullableInt64** |  | 
**ReservedMicros** | **int64** |  | 
**SkippedForCap** | **int32** |  | 
**Tried** | **int32** |  | 
**Unknown** | **int32** |  | 
**Verified** | **int32** |  | 

## Methods

### NewGrowthProviderComparisonResultsInner

`func NewGrowthProviderComparisonResultsInner(billedMicros int64, costStatus string, estimatedCostMicros NullableInt64, failed int32, found int32, pending int32, provider string, providerCostMicros NullableInt64, reservedMicros int64, skippedForCap int32, tried int32, unknown int32, verified int32, ) *GrowthProviderComparisonResultsInner`

NewGrowthProviderComparisonResultsInner instantiates a new GrowthProviderComparisonResultsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthProviderComparisonResultsInnerWithDefaults

`func NewGrowthProviderComparisonResultsInnerWithDefaults() *GrowthProviderComparisonResultsInner`

NewGrowthProviderComparisonResultsInnerWithDefaults instantiates a new GrowthProviderComparisonResultsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilledMicros

`func (o *GrowthProviderComparisonResultsInner) GetBilledMicros() int64`

GetBilledMicros returns the BilledMicros field if non-nil, zero value otherwise.

### GetBilledMicrosOk

`func (o *GrowthProviderComparisonResultsInner) GetBilledMicrosOk() (*int64, bool)`

GetBilledMicrosOk returns a tuple with the BilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledMicros

`func (o *GrowthProviderComparisonResultsInner) SetBilledMicros(v int64)`

SetBilledMicros sets BilledMicros field to given value.


### GetCostStatus

`func (o *GrowthProviderComparisonResultsInner) GetCostStatus() string`

GetCostStatus returns the CostStatus field if non-nil, zero value otherwise.

### GetCostStatusOk

`func (o *GrowthProviderComparisonResultsInner) GetCostStatusOk() (*string, bool)`

GetCostStatusOk returns a tuple with the CostStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostStatus

`func (o *GrowthProviderComparisonResultsInner) SetCostStatus(v string)`

SetCostStatus sets CostStatus field to given value.


### GetEstimatedCostMicros

`func (o *GrowthProviderComparisonResultsInner) GetEstimatedCostMicros() int64`

GetEstimatedCostMicros returns the EstimatedCostMicros field if non-nil, zero value otherwise.

### GetEstimatedCostMicrosOk

`func (o *GrowthProviderComparisonResultsInner) GetEstimatedCostMicrosOk() (*int64, bool)`

GetEstimatedCostMicrosOk returns a tuple with the EstimatedCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCostMicros

`func (o *GrowthProviderComparisonResultsInner) SetEstimatedCostMicros(v int64)`

SetEstimatedCostMicros sets EstimatedCostMicros field to given value.


### SetEstimatedCostMicrosNil

`func (o *GrowthProviderComparisonResultsInner) SetEstimatedCostMicrosNil(b bool)`

 SetEstimatedCostMicrosNil sets the value for EstimatedCostMicros to be an explicit nil

### UnsetEstimatedCostMicros
`func (o *GrowthProviderComparisonResultsInner) UnsetEstimatedCostMicros()`

UnsetEstimatedCostMicros ensures that no value is present for EstimatedCostMicros, not even an explicit nil
### GetFailed

`func (o *GrowthProviderComparisonResultsInner) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *GrowthProviderComparisonResultsInner) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *GrowthProviderComparisonResultsInner) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetFound

`func (o *GrowthProviderComparisonResultsInner) GetFound() int32`

GetFound returns the Found field if non-nil, zero value otherwise.

### GetFoundOk

`func (o *GrowthProviderComparisonResultsInner) GetFoundOk() (*int32, bool)`

GetFoundOk returns a tuple with the Found field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFound

`func (o *GrowthProviderComparisonResultsInner) SetFound(v int32)`

SetFound sets Found field to given value.


### GetPending

`func (o *GrowthProviderComparisonResultsInner) GetPending() int32`

GetPending returns the Pending field if non-nil, zero value otherwise.

### GetPendingOk

`func (o *GrowthProviderComparisonResultsInner) GetPendingOk() (*int32, bool)`

GetPendingOk returns a tuple with the Pending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPending

`func (o *GrowthProviderComparisonResultsInner) SetPending(v int32)`

SetPending sets Pending field to given value.


### GetProvider

`func (o *GrowthProviderComparisonResultsInner) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *GrowthProviderComparisonResultsInner) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *GrowthProviderComparisonResultsInner) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetProviderCostMicros

`func (o *GrowthProviderComparisonResultsInner) GetProviderCostMicros() int64`

GetProviderCostMicros returns the ProviderCostMicros field if non-nil, zero value otherwise.

### GetProviderCostMicrosOk

`func (o *GrowthProviderComparisonResultsInner) GetProviderCostMicrosOk() (*int64, bool)`

GetProviderCostMicrosOk returns a tuple with the ProviderCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderCostMicros

`func (o *GrowthProviderComparisonResultsInner) SetProviderCostMicros(v int64)`

SetProviderCostMicros sets ProviderCostMicros field to given value.


### SetProviderCostMicrosNil

`func (o *GrowthProviderComparisonResultsInner) SetProviderCostMicrosNil(b bool)`

 SetProviderCostMicrosNil sets the value for ProviderCostMicros to be an explicit nil

### UnsetProviderCostMicros
`func (o *GrowthProviderComparisonResultsInner) UnsetProviderCostMicros()`

UnsetProviderCostMicros ensures that no value is present for ProviderCostMicros, not even an explicit nil
### GetReservedMicros

`func (o *GrowthProviderComparisonResultsInner) GetReservedMicros() int64`

GetReservedMicros returns the ReservedMicros field if non-nil, zero value otherwise.

### GetReservedMicrosOk

`func (o *GrowthProviderComparisonResultsInner) GetReservedMicrosOk() (*int64, bool)`

GetReservedMicrosOk returns a tuple with the ReservedMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedMicros

`func (o *GrowthProviderComparisonResultsInner) SetReservedMicros(v int64)`

SetReservedMicros sets ReservedMicros field to given value.


### GetSkippedForCap

`func (o *GrowthProviderComparisonResultsInner) GetSkippedForCap() int32`

GetSkippedForCap returns the SkippedForCap field if non-nil, zero value otherwise.

### GetSkippedForCapOk

`func (o *GrowthProviderComparisonResultsInner) GetSkippedForCapOk() (*int32, bool)`

GetSkippedForCapOk returns a tuple with the SkippedForCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkippedForCap

`func (o *GrowthProviderComparisonResultsInner) SetSkippedForCap(v int32)`

SetSkippedForCap sets SkippedForCap field to given value.


### GetTried

`func (o *GrowthProviderComparisonResultsInner) GetTried() int32`

GetTried returns the Tried field if non-nil, zero value otherwise.

### GetTriedOk

`func (o *GrowthProviderComparisonResultsInner) GetTriedOk() (*int32, bool)`

GetTriedOk returns a tuple with the Tried field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTried

`func (o *GrowthProviderComparisonResultsInner) SetTried(v int32)`

SetTried sets Tried field to given value.


### GetUnknown

`func (o *GrowthProviderComparisonResultsInner) GetUnknown() int32`

GetUnknown returns the Unknown field if non-nil, zero value otherwise.

### GetUnknownOk

`func (o *GrowthProviderComparisonResultsInner) GetUnknownOk() (*int32, bool)`

GetUnknownOk returns a tuple with the Unknown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnknown

`func (o *GrowthProviderComparisonResultsInner) SetUnknown(v int32)`

SetUnknown sets Unknown field to given value.


### GetVerified

`func (o *GrowthProviderComparisonResultsInner) GetVerified() int32`

GetVerified returns the Verified field if non-nil, zero value otherwise.

### GetVerifiedOk

`func (o *GrowthProviderComparisonResultsInner) GetVerifiedOk() (*int32, bool)`

GetVerifiedOk returns a tuple with the Verified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerified

`func (o *GrowthProviderComparisonResultsInner) SetVerified(v int32)`

SetVerified sets Verified field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


