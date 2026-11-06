# ManagedMailboxQuoteInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domains** | [**[]ManagedMailboxQuoteInputDomainsInner**](ManagedMailboxQuoteInputDomainsInner.md) |  | 
**Warmup** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewManagedMailboxQuoteInput

`func NewManagedMailboxQuoteInput(domains []ManagedMailboxQuoteInputDomainsInner, ) *ManagedMailboxQuoteInput`

NewManagedMailboxQuoteInput instantiates a new ManagedMailboxQuoteInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxQuoteInputWithDefaults

`func NewManagedMailboxQuoteInputWithDefaults() *ManagedMailboxQuoteInput`

NewManagedMailboxQuoteInputWithDefaults instantiates a new ManagedMailboxQuoteInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomains

`func (o *ManagedMailboxQuoteInput) GetDomains() []ManagedMailboxQuoteInputDomainsInner`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *ManagedMailboxQuoteInput) GetDomainsOk() (*[]ManagedMailboxQuoteInputDomainsInner, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *ManagedMailboxQuoteInput) SetDomains(v []ManagedMailboxQuoteInputDomainsInner)`

SetDomains sets Domains field to given value.


### GetWarmup

`func (o *ManagedMailboxQuoteInput) GetWarmup() bool`

GetWarmup returns the Warmup field if non-nil, zero value otherwise.

### GetWarmupOk

`func (o *ManagedMailboxQuoteInput) GetWarmupOk() (*bool, bool)`

GetWarmupOk returns a tuple with the Warmup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmup

`func (o *ManagedMailboxQuoteInput) SetWarmup(v bool)`

SetWarmup sets Warmup field to given value.

### HasWarmup

`func (o *ManagedMailboxQuoteInput) HasWarmup() bool`

HasWarmup returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


