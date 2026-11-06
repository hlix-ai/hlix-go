# GrowthInboxPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HasMore** | **bool** |  | 
**Items** | [**[]GrowthInboxPageItemsInner**](GrowthInboxPageItemsInner.md) |  | 
**Limit** | **int32** |  | 
**Offset** | **int32** |  | 

## Methods

### NewGrowthInboxPage

`func NewGrowthInboxPage(hasMore bool, items []GrowthInboxPageItemsInner, limit int32, offset int32, ) *GrowthInboxPage`

NewGrowthInboxPage instantiates a new GrowthInboxPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthInboxPageWithDefaults

`func NewGrowthInboxPageWithDefaults() *GrowthInboxPage`

NewGrowthInboxPageWithDefaults instantiates a new GrowthInboxPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHasMore

`func (o *GrowthInboxPage) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *GrowthInboxPage) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *GrowthInboxPage) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.


### GetItems

`func (o *GrowthInboxPage) GetItems() []GrowthInboxPageItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *GrowthInboxPage) GetItemsOk() (*[]GrowthInboxPageItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *GrowthInboxPage) SetItems(v []GrowthInboxPageItemsInner)`

SetItems sets Items field to given value.


### GetLimit

`func (o *GrowthInboxPage) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GrowthInboxPage) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GrowthInboxPage) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *GrowthInboxPage) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *GrowthInboxPage) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *GrowthInboxPage) SetOffset(v int32)`

SetOffset sets Offset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


