# OrgBillingStateActiveSubscriptionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **NullableFloat32** |  | 
**CancelAtPeriodEnd** | **bool** |  | 
**Currency** | **string** |  | 
**CurrentPeriodEnd** | **NullableString** |  | 
**Id** | **string** |  | 
**PlanSlug** | **NullableString** |  | 
**Product** | [**OrgBillingStateActiveSubscriptionsInnerProduct**](OrgBillingStateActiveSubscriptionsInnerProduct.md) |  | 
**RecurringInterval** | **NullableString** |  | 
**Status** | **string** |  | 

## Methods

### NewOrgBillingStateActiveSubscriptionsInner

`func NewOrgBillingStateActiveSubscriptionsInner(amount NullableFloat32, cancelAtPeriodEnd bool, currency string, currentPeriodEnd NullableString, id string, planSlug NullableString, product OrgBillingStateActiveSubscriptionsInnerProduct, recurringInterval NullableString, status string, ) *OrgBillingStateActiveSubscriptionsInner`

NewOrgBillingStateActiveSubscriptionsInner instantiates a new OrgBillingStateActiveSubscriptionsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrgBillingStateActiveSubscriptionsInnerWithDefaults

`func NewOrgBillingStateActiveSubscriptionsInnerWithDefaults() *OrgBillingStateActiveSubscriptionsInner`

NewOrgBillingStateActiveSubscriptionsInnerWithDefaults instantiates a new OrgBillingStateActiveSubscriptionsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *OrgBillingStateActiveSubscriptionsInner) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *OrgBillingStateActiveSubscriptionsInner) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### SetAmountNil

`func (o *OrgBillingStateActiveSubscriptionsInner) SetAmountNil(b bool)`

 SetAmountNil sets the value for Amount to be an explicit nil

### UnsetAmount
`func (o *OrgBillingStateActiveSubscriptionsInner) UnsetAmount()`

UnsetAmount ensures that no value is present for Amount, not even an explicit nil
### GetCancelAtPeriodEnd

`func (o *OrgBillingStateActiveSubscriptionsInner) GetCancelAtPeriodEnd() bool`

GetCancelAtPeriodEnd returns the CancelAtPeriodEnd field if non-nil, zero value otherwise.

### GetCancelAtPeriodEndOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetCancelAtPeriodEndOk() (*bool, bool)`

GetCancelAtPeriodEndOk returns a tuple with the CancelAtPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelAtPeriodEnd

`func (o *OrgBillingStateActiveSubscriptionsInner) SetCancelAtPeriodEnd(v bool)`

SetCancelAtPeriodEnd sets CancelAtPeriodEnd field to given value.


### GetCurrency

`func (o *OrgBillingStateActiveSubscriptionsInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *OrgBillingStateActiveSubscriptionsInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCurrentPeriodEnd

`func (o *OrgBillingStateActiveSubscriptionsInner) GetCurrentPeriodEnd() string`

GetCurrentPeriodEnd returns the CurrentPeriodEnd field if non-nil, zero value otherwise.

### GetCurrentPeriodEndOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetCurrentPeriodEndOk() (*string, bool)`

GetCurrentPeriodEndOk returns a tuple with the CurrentPeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriodEnd

`func (o *OrgBillingStateActiveSubscriptionsInner) SetCurrentPeriodEnd(v string)`

SetCurrentPeriodEnd sets CurrentPeriodEnd field to given value.


### SetCurrentPeriodEndNil

`func (o *OrgBillingStateActiveSubscriptionsInner) SetCurrentPeriodEndNil(b bool)`

 SetCurrentPeriodEndNil sets the value for CurrentPeriodEnd to be an explicit nil

### UnsetCurrentPeriodEnd
`func (o *OrgBillingStateActiveSubscriptionsInner) UnsetCurrentPeriodEnd()`

UnsetCurrentPeriodEnd ensures that no value is present for CurrentPeriodEnd, not even an explicit nil
### GetId

`func (o *OrgBillingStateActiveSubscriptionsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OrgBillingStateActiveSubscriptionsInner) SetId(v string)`

SetId sets Id field to given value.


### GetPlanSlug

`func (o *OrgBillingStateActiveSubscriptionsInner) GetPlanSlug() string`

GetPlanSlug returns the PlanSlug field if non-nil, zero value otherwise.

### GetPlanSlugOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetPlanSlugOk() (*string, bool)`

GetPlanSlugOk returns a tuple with the PlanSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanSlug

`func (o *OrgBillingStateActiveSubscriptionsInner) SetPlanSlug(v string)`

SetPlanSlug sets PlanSlug field to given value.


### SetPlanSlugNil

`func (o *OrgBillingStateActiveSubscriptionsInner) SetPlanSlugNil(b bool)`

 SetPlanSlugNil sets the value for PlanSlug to be an explicit nil

### UnsetPlanSlug
`func (o *OrgBillingStateActiveSubscriptionsInner) UnsetPlanSlug()`

UnsetPlanSlug ensures that no value is present for PlanSlug, not even an explicit nil
### GetProduct

`func (o *OrgBillingStateActiveSubscriptionsInner) GetProduct() OrgBillingStateActiveSubscriptionsInnerProduct`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetProductOk() (*OrgBillingStateActiveSubscriptionsInnerProduct, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *OrgBillingStateActiveSubscriptionsInner) SetProduct(v OrgBillingStateActiveSubscriptionsInnerProduct)`

SetProduct sets Product field to given value.


### GetRecurringInterval

`func (o *OrgBillingStateActiveSubscriptionsInner) GetRecurringInterval() string`

GetRecurringInterval returns the RecurringInterval field if non-nil, zero value otherwise.

### GetRecurringIntervalOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetRecurringIntervalOk() (*string, bool)`

GetRecurringIntervalOk returns a tuple with the RecurringInterval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurringInterval

`func (o *OrgBillingStateActiveSubscriptionsInner) SetRecurringInterval(v string)`

SetRecurringInterval sets RecurringInterval field to given value.


### SetRecurringIntervalNil

`func (o *OrgBillingStateActiveSubscriptionsInner) SetRecurringIntervalNil(b bool)`

 SetRecurringIntervalNil sets the value for RecurringInterval to be an explicit nil

### UnsetRecurringInterval
`func (o *OrgBillingStateActiveSubscriptionsInner) UnsetRecurringInterval()`

UnsetRecurringInterval ensures that no value is present for RecurringInterval, not even an explicit nil
### GetStatus

`func (o *OrgBillingStateActiveSubscriptionsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrgBillingStateActiveSubscriptionsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrgBillingStateActiveSubscriptionsInner) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


