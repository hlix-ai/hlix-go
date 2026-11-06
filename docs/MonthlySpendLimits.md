# MonthlySpendLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delivery** | [**MonthlySpendLimitsDelivery**](MonthlySpendLimitsDelivery.md) |  | 
**Growth** | [**MonthlySpendLimitsDelivery**](MonthlySpendLimitsDelivery.md) |  | 
**MonthStart** | **string** |  | 
**ResetsAt** | **string** |  | 

## Methods

### NewMonthlySpendLimits

`func NewMonthlySpendLimits(delivery MonthlySpendLimitsDelivery, growth MonthlySpendLimitsDelivery, monthStart string, resetsAt string, ) *MonthlySpendLimits`

NewMonthlySpendLimits instantiates a new MonthlySpendLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMonthlySpendLimitsWithDefaults

`func NewMonthlySpendLimitsWithDefaults() *MonthlySpendLimits`

NewMonthlySpendLimitsWithDefaults instantiates a new MonthlySpendLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelivery

`func (o *MonthlySpendLimits) GetDelivery() MonthlySpendLimitsDelivery`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *MonthlySpendLimits) GetDeliveryOk() (*MonthlySpendLimitsDelivery, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *MonthlySpendLimits) SetDelivery(v MonthlySpendLimitsDelivery)`

SetDelivery sets Delivery field to given value.


### GetGrowth

`func (o *MonthlySpendLimits) GetGrowth() MonthlySpendLimitsDelivery`

GetGrowth returns the Growth field if non-nil, zero value otherwise.

### GetGrowthOk

`func (o *MonthlySpendLimits) GetGrowthOk() (*MonthlySpendLimitsDelivery, bool)`

GetGrowthOk returns a tuple with the Growth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowth

`func (o *MonthlySpendLimits) SetGrowth(v MonthlySpendLimitsDelivery)`

SetGrowth sets Growth field to given value.


### GetMonthStart

`func (o *MonthlySpendLimits) GetMonthStart() string`

GetMonthStart returns the MonthStart field if non-nil, zero value otherwise.

### GetMonthStartOk

`func (o *MonthlySpendLimits) GetMonthStartOk() (*string, bool)`

GetMonthStartOk returns a tuple with the MonthStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthStart

`func (o *MonthlySpendLimits) SetMonthStart(v string)`

SetMonthStart sets MonthStart field to given value.


### GetResetsAt

`func (o *MonthlySpendLimits) GetResetsAt() string`

GetResetsAt returns the ResetsAt field if non-nil, zero value otherwise.

### GetResetsAtOk

`func (o *MonthlySpendLimits) GetResetsAtOk() (*string, bool)`

GetResetsAtOk returns a tuple with the ResetsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetsAt

`func (o *MonthlySpendLimits) SetResetsAt(v string)`

SetResetsAt sets ResetsAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


