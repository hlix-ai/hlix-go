# ManagedMailboxOrderQuoteItemsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **NullableString** |  | 
**BilledMicros** | **int64** |  | 
**BillingCycle** | **string** |  | 
**BillingSource** | **string** |  | 
**Domain** | **string** |  | 
**Kind** | **string** |  | 
**Quantity** | **int32** |  | 
**RenewalBilledMicros** | **NullableInt64** |  | 
**RenewalCostMicros** | **NullableInt64** |  | 
**TotalCostMicros** | **int64** |  | 
**UnitCostMicros** | **int64** |  | 

## Methods

### NewManagedMailboxOrderQuoteItemsInner

`func NewManagedMailboxOrderQuoteItemsInner(address NullableString, billedMicros int64, billingCycle string, billingSource string, domain string, kind string, quantity int32, renewalBilledMicros NullableInt64, renewalCostMicros NullableInt64, totalCostMicros int64, unitCostMicros int64, ) *ManagedMailboxOrderQuoteItemsInner`

NewManagedMailboxOrderQuoteItemsInner instantiates a new ManagedMailboxOrderQuoteItemsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxOrderQuoteItemsInnerWithDefaults

`func NewManagedMailboxOrderQuoteItemsInnerWithDefaults() *ManagedMailboxOrderQuoteItemsInner`

NewManagedMailboxOrderQuoteItemsInnerWithDefaults instantiates a new ManagedMailboxOrderQuoteItemsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *ManagedMailboxOrderQuoteItemsInner) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ManagedMailboxOrderQuoteItemsInner) SetAddress(v string)`

SetAddress sets Address field to given value.


### SetAddressNil

`func (o *ManagedMailboxOrderQuoteItemsInner) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ManagedMailboxOrderQuoteItemsInner) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetBilledMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) GetBilledMicros() int64`

GetBilledMicros returns the BilledMicros field if non-nil, zero value otherwise.

### GetBilledMicrosOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetBilledMicrosOk() (*int64, bool)`

GetBilledMicrosOk returns a tuple with the BilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) SetBilledMicros(v int64)`

SetBilledMicros sets BilledMicros field to given value.


### GetBillingCycle

`func (o *ManagedMailboxOrderQuoteItemsInner) GetBillingCycle() string`

GetBillingCycle returns the BillingCycle field if non-nil, zero value otherwise.

### GetBillingCycleOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetBillingCycleOk() (*string, bool)`

GetBillingCycleOk returns a tuple with the BillingCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycle

`func (o *ManagedMailboxOrderQuoteItemsInner) SetBillingCycle(v string)`

SetBillingCycle sets BillingCycle field to given value.


### GetBillingSource

`func (o *ManagedMailboxOrderQuoteItemsInner) GetBillingSource() string`

GetBillingSource returns the BillingSource field if non-nil, zero value otherwise.

### GetBillingSourceOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetBillingSourceOk() (*string, bool)`

GetBillingSourceOk returns a tuple with the BillingSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingSource

`func (o *ManagedMailboxOrderQuoteItemsInner) SetBillingSource(v string)`

SetBillingSource sets BillingSource field to given value.


### GetDomain

`func (o *ManagedMailboxOrderQuoteItemsInner) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *ManagedMailboxOrderQuoteItemsInner) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetKind

`func (o *ManagedMailboxOrderQuoteItemsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ManagedMailboxOrderQuoteItemsInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetQuantity

`func (o *ManagedMailboxOrderQuoteItemsInner) GetQuantity() int32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetQuantityOk() (*int32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ManagedMailboxOrderQuoteItemsInner) SetQuantity(v int32)`

SetQuantity sets Quantity field to given value.


### GetRenewalBilledMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) GetRenewalBilledMicros() int64`

GetRenewalBilledMicros returns the RenewalBilledMicros field if non-nil, zero value otherwise.

### GetRenewalBilledMicrosOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetRenewalBilledMicrosOk() (*int64, bool)`

GetRenewalBilledMicrosOk returns a tuple with the RenewalBilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalBilledMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) SetRenewalBilledMicros(v int64)`

SetRenewalBilledMicros sets RenewalBilledMicros field to given value.


### SetRenewalBilledMicrosNil

`func (o *ManagedMailboxOrderQuoteItemsInner) SetRenewalBilledMicrosNil(b bool)`

 SetRenewalBilledMicrosNil sets the value for RenewalBilledMicros to be an explicit nil

### UnsetRenewalBilledMicros
`func (o *ManagedMailboxOrderQuoteItemsInner) UnsetRenewalBilledMicros()`

UnsetRenewalBilledMicros ensures that no value is present for RenewalBilledMicros, not even an explicit nil
### GetRenewalCostMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) GetRenewalCostMicros() int64`

GetRenewalCostMicros returns the RenewalCostMicros field if non-nil, zero value otherwise.

### GetRenewalCostMicrosOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetRenewalCostMicrosOk() (*int64, bool)`

GetRenewalCostMicrosOk returns a tuple with the RenewalCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenewalCostMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) SetRenewalCostMicros(v int64)`

SetRenewalCostMicros sets RenewalCostMicros field to given value.


### SetRenewalCostMicrosNil

`func (o *ManagedMailboxOrderQuoteItemsInner) SetRenewalCostMicrosNil(b bool)`

 SetRenewalCostMicrosNil sets the value for RenewalCostMicros to be an explicit nil

### UnsetRenewalCostMicros
`func (o *ManagedMailboxOrderQuoteItemsInner) UnsetRenewalCostMicros()`

UnsetRenewalCostMicros ensures that no value is present for RenewalCostMicros, not even an explicit nil
### GetTotalCostMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) GetTotalCostMicros() int64`

GetTotalCostMicros returns the TotalCostMicros field if non-nil, zero value otherwise.

### GetTotalCostMicrosOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetTotalCostMicrosOk() (*int64, bool)`

GetTotalCostMicrosOk returns a tuple with the TotalCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCostMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) SetTotalCostMicros(v int64)`

SetTotalCostMicros sets TotalCostMicros field to given value.


### GetUnitCostMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) GetUnitCostMicros() int64`

GetUnitCostMicros returns the UnitCostMicros field if non-nil, zero value otherwise.

### GetUnitCostMicrosOk

`func (o *ManagedMailboxOrderQuoteItemsInner) GetUnitCostMicrosOk() (*int64, bool)`

GetUnitCostMicrosOk returns a tuple with the UnitCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitCostMicros

`func (o *ManagedMailboxOrderQuoteItemsInner) SetUnitCostMicros(v int64)`

SetUnitCostMicros sets UnitCostMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


