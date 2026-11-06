# CrmBoardStagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Deals** | [**[]CrmBoardStagesInnerDealsInner**](CrmBoardStagesInnerDealsInner.md) |  | 
**Name** | **string** |  | 
**Totals** | **map[string]int32** |  | 

## Methods

### NewCrmBoardStagesInner

`func NewCrmBoardStagesInner(count int32, deals []CrmBoardStagesInnerDealsInner, name string, totals map[string]int32, ) *CrmBoardStagesInner`

NewCrmBoardStagesInner instantiates a new CrmBoardStagesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCrmBoardStagesInnerWithDefaults

`func NewCrmBoardStagesInnerWithDefaults() *CrmBoardStagesInner`

NewCrmBoardStagesInnerWithDefaults instantiates a new CrmBoardStagesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *CrmBoardStagesInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *CrmBoardStagesInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *CrmBoardStagesInner) SetCount(v int32)`

SetCount sets Count field to given value.


### GetDeals

`func (o *CrmBoardStagesInner) GetDeals() []CrmBoardStagesInnerDealsInner`

GetDeals returns the Deals field if non-nil, zero value otherwise.

### GetDealsOk

`func (o *CrmBoardStagesInner) GetDealsOk() (*[]CrmBoardStagesInnerDealsInner, bool)`

GetDealsOk returns a tuple with the Deals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeals

`func (o *CrmBoardStagesInner) SetDeals(v []CrmBoardStagesInnerDealsInner)`

SetDeals sets Deals field to given value.


### GetName

`func (o *CrmBoardStagesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CrmBoardStagesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CrmBoardStagesInner) SetName(v string)`

SetName sets Name field to given value.


### GetTotals

`func (o *CrmBoardStagesInner) GetTotals() map[string]int32`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *CrmBoardStagesInner) GetTotalsOk() (*map[string]int32, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *CrmBoardStagesInner) SetTotals(v map[string]int32)`

SetTotals sets Totals field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


