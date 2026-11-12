# ManagedMailboxOrderQuote

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **bool** |  |
**Currency** | **string** |  |
**Domains** | [**[]ManagedMailboxOrderQuoteDomainsInner**](ManagedMailboxOrderQuoteDomainsInner.md) |  |
**ExpiresAt** | **time.Time** |  |
**Items** | [**[]ManagedMailboxOrderQuoteItemsInner**](ManagedMailboxOrderQuoteItemsInner.md) |  |
**Locked** | **bool** |  | [default to false]
**ObservedAt** | **time.Time** |  |
**QuoteId** | **string** |  |
**Recurring** | [**[]ManagedMailboxOrderQuoteItemsInner**](ManagedMailboxOrderQuoteItemsInner.md) |  |
**UpfrontBilledMicros** | **int64** |  |
**UpfrontCostMicros** | **int64** |  |

## Methods

### NewManagedMailboxOrderQuote

`func NewManagedMailboxOrderQuote(available bool, currency string, domains []ManagedMailboxOrderQuoteDomainsInner, expiresAt time.Time, items []ManagedMailboxOrderQuoteItemsInner, locked bool, observedAt time.Time, quoteId string, recurring []ManagedMailboxOrderQuoteItemsInner, upfrontBilledMicros int64, upfrontCostMicros int64, ) *ManagedMailboxOrderQuote`

NewManagedMailboxOrderQuote instantiates a new ManagedMailboxOrderQuote object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewManagedMailboxOrderQuoteWithDefaults

`func NewManagedMailboxOrderQuoteWithDefaults() *ManagedMailboxOrderQuote`

NewManagedMailboxOrderQuoteWithDefaults instantiates a new ManagedMailboxOrderQuote object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAvailable

`func (o *ManagedMailboxOrderQuote) GetAvailable() bool`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *ManagedMailboxOrderQuote) GetAvailableOk() (*bool, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *ManagedMailboxOrderQuote) SetAvailable(v bool)`

SetAvailable sets Available field to given value.


### GetCurrency

`func (o *ManagedMailboxOrderQuote) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ManagedMailboxOrderQuote) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ManagedMailboxOrderQuote) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDomains

`func (o *ManagedMailboxOrderQuote) GetDomains() []ManagedMailboxOrderQuoteDomainsInner`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *ManagedMailboxOrderQuote) GetDomainsOk() (*[]ManagedMailboxOrderQuoteDomainsInner, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *ManagedMailboxOrderQuote) SetDomains(v []ManagedMailboxOrderQuoteDomainsInner)`

SetDomains sets Domains field to given value.


### GetExpiresAt

`func (o *ManagedMailboxOrderQuote) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ManagedMailboxOrderQuote) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ManagedMailboxOrderQuote) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetItems

`func (o *ManagedMailboxOrderQuote) GetItems() []ManagedMailboxOrderQuoteItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ManagedMailboxOrderQuote) GetItemsOk() (*[]ManagedMailboxOrderQuoteItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ManagedMailboxOrderQuote) SetItems(v []ManagedMailboxOrderQuoteItemsInner)`

SetItems sets Items field to given value.


### GetLocked

`func (o *ManagedMailboxOrderQuote) GetLocked() bool`

GetLocked returns the Locked field if non-nil, zero value otherwise.

### GetLockedOk

`func (o *ManagedMailboxOrderQuote) GetLockedOk() (*bool, bool)`

GetLockedOk returns a tuple with the Locked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocked

`func (o *ManagedMailboxOrderQuote) SetLocked(v bool)`

SetLocked sets Locked field to given value.


### GetObservedAt

`func (o *ManagedMailboxOrderQuote) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *ManagedMailboxOrderQuote) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *ManagedMailboxOrderQuote) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.


### GetQuoteId

`func (o *ManagedMailboxOrderQuote) GetQuoteId() string`

GetQuoteId returns the QuoteId field if non-nil, zero value otherwise.

### GetQuoteIdOk

`func (o *ManagedMailboxOrderQuote) GetQuoteIdOk() (*string, bool)`

GetQuoteIdOk returns a tuple with the QuoteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteId

`func (o *ManagedMailboxOrderQuote) SetQuoteId(v string)`

SetQuoteId sets QuoteId field to given value.


### GetRecurring

`func (o *ManagedMailboxOrderQuote) GetRecurring() []ManagedMailboxOrderQuoteItemsInner`

GetRecurring returns the Recurring field if non-nil, zero value otherwise.

### GetRecurringOk

`func (o *ManagedMailboxOrderQuote) GetRecurringOk() (*[]ManagedMailboxOrderQuoteItemsInner, bool)`

GetRecurringOk returns a tuple with the Recurring field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurring

`func (o *ManagedMailboxOrderQuote) SetRecurring(v []ManagedMailboxOrderQuoteItemsInner)`

SetRecurring sets Recurring field to given value.


### GetUpfrontBilledMicros

`func (o *ManagedMailboxOrderQuote) GetUpfrontBilledMicros() int64`

GetUpfrontBilledMicros returns the UpfrontBilledMicros field if non-nil, zero value otherwise.

### GetUpfrontBilledMicrosOk

`func (o *ManagedMailboxOrderQuote) GetUpfrontBilledMicrosOk() (*int64, bool)`

GetUpfrontBilledMicrosOk returns a tuple with the UpfrontBilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpfrontBilledMicros

`func (o *ManagedMailboxOrderQuote) SetUpfrontBilledMicros(v int64)`

SetUpfrontBilledMicros sets UpfrontBilledMicros field to given value.


### GetUpfrontCostMicros

`func (o *ManagedMailboxOrderQuote) GetUpfrontCostMicros() int64`

GetUpfrontCostMicros returns the UpfrontCostMicros field if non-nil, zero value otherwise.

### GetUpfrontCostMicrosOk

`func (o *ManagedMailboxOrderQuote) GetUpfrontCostMicrosOk() (*int64, bool)`

GetUpfrontCostMicrosOk returns a tuple with the UpfrontCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpfrontCostMicros

`func (o *ManagedMailboxOrderQuote) SetUpfrontCostMicros(v int64)`

SetUpfrontCostMicros sets UpfrontCostMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


