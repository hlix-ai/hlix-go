# GrowthChainStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByProvider** | [**map[string]GrowthChainStatsByProviderValue**](GrowthChainStatsByProviderValue.md) |  | 
**Chain** | [**NullableGrowthChainStatsChain**](GrowthChainStatsChain.md) |  | 
**WindowDays** | **int32** |  | 

## Methods

### NewGrowthChainStats

`func NewGrowthChainStats(byProvider map[string]GrowthChainStatsByProviderValue, chain NullableGrowthChainStatsChain, windowDays int32, ) *GrowthChainStats`

NewGrowthChainStats instantiates a new GrowthChainStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthChainStatsWithDefaults

`func NewGrowthChainStatsWithDefaults() *GrowthChainStats`

NewGrowthChainStatsWithDefaults instantiates a new GrowthChainStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetByProvider

`func (o *GrowthChainStats) GetByProvider() map[string]GrowthChainStatsByProviderValue`

GetByProvider returns the ByProvider field if non-nil, zero value otherwise.

### GetByProviderOk

`func (o *GrowthChainStats) GetByProviderOk() (*map[string]GrowthChainStatsByProviderValue, bool)`

GetByProviderOk returns a tuple with the ByProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByProvider

`func (o *GrowthChainStats) SetByProvider(v map[string]GrowthChainStatsByProviderValue)`

SetByProvider sets ByProvider field to given value.


### GetChain

`func (o *GrowthChainStats) GetChain() GrowthChainStatsChain`

GetChain returns the Chain field if non-nil, zero value otherwise.

### GetChainOk

`func (o *GrowthChainStats) GetChainOk() (*GrowthChainStatsChain, bool)`

GetChainOk returns a tuple with the Chain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChain

`func (o *GrowthChainStats) SetChain(v GrowthChainStatsChain)`

SetChain sets Chain field to given value.


### SetChainNil

`func (o *GrowthChainStats) SetChainNil(b bool)`

 SetChainNil sets the value for Chain to be an explicit nil

### UnsetChain
`func (o *GrowthChainStats) UnsetChain()`

UnsetChain ensures that no value is present for Chain, not even an explicit nil
### GetWindowDays

`func (o *GrowthChainStats) GetWindowDays() int32`

GetWindowDays returns the WindowDays field if non-nil, zero value otherwise.

### GetWindowDaysOk

`func (o *GrowthChainStats) GetWindowDaysOk() (*int32, bool)`

GetWindowDaysOk returns a tuple with the WindowDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowDays

`func (o *GrowthChainStats) SetWindowDays(v int32)`

SetWindowDays sets WindowDays field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


