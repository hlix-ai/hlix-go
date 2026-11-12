# CompareGrowthProviders

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OperationKey** | **string** |  |
**Providers** | **[]interface{}** |  |
**SampleSize** | Pointer to **int32** |  | [optional] [default to 20]

## Methods

### NewCompareGrowthProviders

`func NewCompareGrowthProviders(operationKey string, providers []interface{}, ) *CompareGrowthProviders`

NewCompareGrowthProviders instantiates a new CompareGrowthProviders object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCompareGrowthProvidersWithDefaults

`func NewCompareGrowthProvidersWithDefaults() *CompareGrowthProviders`

NewCompareGrowthProvidersWithDefaults instantiates a new CompareGrowthProviders object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetOperationKey

`func (o *CompareGrowthProviders) GetOperationKey() string`

GetOperationKey returns the OperationKey field if non-nil, zero value otherwise.

### GetOperationKeyOk

`func (o *CompareGrowthProviders) GetOperationKeyOk() (*string, bool)`

GetOperationKeyOk returns a tuple with the OperationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationKey

`func (o *CompareGrowthProviders) SetOperationKey(v string)`

SetOperationKey sets OperationKey field to given value.


### GetProviders

`func (o *CompareGrowthProviders) GetProviders() []interface{}`

GetProviders returns the Providers field if non-nil, zero value otherwise.

### GetProvidersOk

`func (o *CompareGrowthProviders) GetProvidersOk() (*[]interface{}, bool)`

GetProvidersOk returns a tuple with the Providers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviders

`func (o *CompareGrowthProviders) SetProviders(v []interface{})`

SetProviders sets Providers field to given value.


### GetSampleSize

`func (o *CompareGrowthProviders) GetSampleSize() int32`

GetSampleSize returns the SampleSize field if non-nil, zero value otherwise.

### GetSampleSizeOk

`func (o *CompareGrowthProviders) GetSampleSizeOk() (*int32, bool)`

GetSampleSizeOk returns a tuple with the SampleSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampleSize

`func (o *CompareGrowthProviders) SetSampleSize(v int32)`

SetSampleSize sets SampleSize field to given value.

### HasSampleSize

`func (o *CompareGrowthProviders) HasSampleSize() bool`

HasSampleSize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


