# ManagedMailboxQuote

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **bool** |  | 
**Currency** | **string** |  | 
**Domains** | [**[]ManagedMailboxOrderQuoteDomainsInner**](ManagedMailboxOrderQuoteDomainsInner.md) |  | 
**ExpiresAt** | **time.Time** |  | 
**Items** | [**[]ManagedMailboxOrderQuoteItemsInner**](ManagedMailboxOrderQuoteItemsInner.md) |  | 
**Locked** | **bool** |  | 
**ObservedAt** | **time.Time** |  | 
**QuoteId** | **string** |  | 
**Recurring** | [**[]ManagedMailboxOrderQuoteItemsInner**](ManagedMailboxOrderQuoteItemsInner.md) |  | 
**UpfrontBilledMicros** | **int64** |  | 
**UpfrontCostMicros** | **int64** |  | 

## Methods

### NewManagedMailboxQuote

`func NewManagedMailboxQuote(available bool, currency string, domains []ManagedMailboxOrderQuoteDomainsInner, expiresAt time.Time, items []ManagedMailboxOrderQuoteItemsInner, locked bool, observedAt time.Time, quoteId string, recurring []ManagedMailboxOrderQuoteItemsInner, upfrontBilledMicros int64, upfrontCostMicros int64, ) *ManagedMailboxQuote`

NewManagedMailboxQuote instantiates a new ManagedMailboxQuote object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxQuoteWithDefaults

`func NewManagedMailboxQuoteWithDefaults() *ManagedMailboxQuote`

NewManagedMailboxQuoteWithDefaults instantiates a new ManagedMailboxQuote object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *ManagedMailboxQuote) GetAvailable() bool`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *ManagedMailboxQuote) GetAvailableOk() (*bool, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *ManagedMailboxQuote) SetAvailable(v bool)`

SetAvailable sets Available field to given value.


### GetCurrency

`func (o *ManagedMailboxQuote) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ManagedMailboxQuote) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ManagedMailboxQuote) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDomains

`func (o *ManagedMailboxQuote) GetDomains() []ManagedMailboxOrderQuoteDomainsInner`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *ManagedMailboxQuote) GetDomainsOk() (*[]ManagedMailboxOrderQuoteDomainsInner, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *ManagedMailboxQuote) SetDomains(v []ManagedMailboxOrderQuoteDomainsInner)`

SetDomains sets Domains field to given value.


### GetExpiresAt

`func (o *ManagedMailboxQuote) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ManagedMailboxQuote) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ManagedMailboxQuote) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetItems

`func (o *ManagedMailboxQuote) GetItems() []ManagedMailboxOrderQuoteItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ManagedMailboxQuote) GetItemsOk() (*[]ManagedMailboxOrderQuoteItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ManagedMailboxQuote) SetItems(v []ManagedMailboxOrderQuoteItemsInner)`

SetItems sets Items field to given value.


### GetLocked

`func (o *ManagedMailboxQuote) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *ManagedMailboxQuote) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *ManagedMailboxQuote) SetLocked(v bool)`

SetLocked sets Locked field to given value.


### GetObservedAt

`func (o *ManagedMailboxQuote) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *ManagedMailboxQuote) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *ManagedMailboxQuote) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetQuoteId

`func (o *ManagedMailboxQuote) GetQuoteId() string`

GetQuoteId returns the QuoteId field if non-nil, zero value otherwise.

### GetQuoteIdOk

`func (o *ManagedMailboxQuote) GetQuoteIdOk() (*string, bool)`

GetQuoteIdOk returns a tuple with the QuoteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteId

`func (o *ManagedMailboxQuote) SetQuoteId(v string)`

SetQuoteId sets QuoteId field to given value.


### GetRecurring

`func (o *ManagedMailboxQuote) GetRecurring() []ManagedMailboxOrderQuoteItemsInner`

GetRecurring returns the Recurring field if non-nil, zero value otherwise.

### GetRecurringOk

`func (o *ManagedMailboxQuote) GetRecurringOk() (*[]ManagedMailboxOrderQuoteItemsInner, bool)`

GetRecurringOk returns a tuple with the Recurring field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurring

`func (o *ManagedMailboxQuote) SetRecurring(v []ManagedMailboxOrderQuoteItemsInner)`

SetRecurring sets Recurring field to given value.


### GetUpfrontBilledMicros

`func (o *ManagedMailboxQuote) GetUpfrontBilledMicros() int64`

GetUpfrontBilledMicros returns the UpfrontBilledMicros field if non-nil, zero value otherwise.

### GetUpfrontBilledMicrosOk

`func (o *ManagedMailboxQuote) GetUpfrontBilledMicrosOk() (*int64, bool)`

GetUpfrontBilledMicrosOk returns a tuple with the UpfrontBilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpfrontBilledMicros

`func (o *ManagedMailboxQuote) SetUpfrontBilledMicros(v int64)`

SetUpfrontBilledMicros sets UpfrontBilledMicros field to given value.


### GetUpfrontCostMicros

`func (o *ManagedMailboxQuote) GetUpfrontCostMicros() int64`

GetUpfrontCostMicros returns the UpfrontCostMicros field if non-nil, zero value otherwise.

### GetUpfrontCostMicrosOk

`func (o *ManagedMailboxQuote) GetUpfrontCostMicrosOk() (*int64, bool)`

GetUpfrontCostMicrosOk returns a tuple with the UpfrontCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpfrontCostMicros

`func (o *ManagedMailboxQuote) SetUpfrontCostMicros(v int64)`

SetUpfrontCostMicros sets UpfrontCostMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


