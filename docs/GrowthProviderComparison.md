# GrowthProviderComparison

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OperationKey** | **string** |  |
**Results** | [**[]GrowthProviderComparisonResultsInner**](GrowthProviderComparisonResultsInner.md) |  |
**Sample** | **int32** |  |

## Methods

### NewGrowthProviderComparison

`func NewGrowthProviderComparison(operationKey string, results []GrowthProviderComparisonResultsInner, sample int32, ) *GrowthProviderComparison`

NewGrowthProviderComparison instantiates a new GrowthProviderComparison object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthProviderComparisonWithDefaults

`func NewGrowthProviderComparisonWithDefaults() *GrowthProviderComparison`

NewGrowthProviderComparisonWithDefaults instantiates a new GrowthProviderComparison object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetOperationKey

`func (o *GrowthProviderComparison) GetOperationKey() string`

GetOperationKey returns the OperationKey field if non-nil, zero value otherwise.

### GetOperationKeyOk

`func (o *GrowthProviderComparison) GetOperationKeyOk() (*string, bool)`

GetOperationKeyOk returns a tuple with the OperationKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationKey

`func (o *GrowthProviderComparison) SetOperationKey(v string)`

SetOperationKey sets OperationKey field to given value.


### GetResults

`func (o *GrowthProviderComparison) GetResults() []GrowthProviderComparisonResultsInner`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *GrowthProviderComparison) GetResultsOk() (*[]GrowthProviderComparisonResultsInner, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *GrowthProviderComparison) SetResults(v []GrowthProviderComparisonResultsInner)`

SetResults sets Results field to given value.


### GetSample

`func (o *GrowthProviderComparison) GetSample() int32`

GetSample returns the Sample field if non-nil, zero value otherwise.

### GetSampleOk

`func (o *GrowthProviderComparison) GetSampleOk() (*int32, bool)`

GetSampleOk returns a tuple with the Sample field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSample

`func (o *GrowthProviderComparison) SetSample(v int32)`

SetSample sets Sample field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


