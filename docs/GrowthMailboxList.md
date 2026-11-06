# GrowthMailboxList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Configured** | **bool** |  | 
**Items** | [**[]GrowthMailboxListItemsInner**](GrowthMailboxListItemsInner.md) |  | 

## Methods

### NewGrowthMailboxList

`func NewGrowthMailboxList(configured bool, items []GrowthMailboxListItemsInner, ) *GrowthMailboxList`

NewGrowthMailboxList instantiates a new GrowthMailboxList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthMailboxListWithDefaults

`func NewGrowthMailboxListWithDefaults() *GrowthMailboxList`

NewGrowthMailboxListWithDefaults instantiates a new GrowthMailboxList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigured

`func (o *GrowthMailboxList) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *GrowthMailboxList) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *GrowthMailboxList) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetItems

`func (o *GrowthMailboxList) GetItems() []GrowthMailboxListItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *GrowthMailboxList) GetItemsOk() (*[]GrowthMailboxListItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *GrowthMailboxList) SetItems(v []GrowthMailboxListItemsInner)`

SetItems sets Items field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


