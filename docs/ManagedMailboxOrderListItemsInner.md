# ManagedMailboxOrderListItemsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BilledMicros** | **NullableInt64** |  | 
**CostStatus** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**Id** | **string** |  | 
**IssueCode** | **NullableString** |  | 
**ProviderCostMicros** | **NullableInt64** |  | 
**Quote** | [**ManagedMailboxOrderQuote**](ManagedMailboxOrderQuote.md) |  | 
**ReservedMicros** | **int64** |  | 
**Resources** | [**[]ManagedMailboxOrderResourcesInner**](ManagedMailboxOrderResourcesInner.md) |  | 
**Source** | Pointer to **string** |  | [optional] 
**Status** | **string** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewManagedMailboxOrderListItemsInner

`func NewManagedMailboxOrderListItemsInner(billedMicros NullableInt64, costStatus string, createdAt time.Time, id string, issueCode NullableString, providerCostMicros NullableInt64, quote ManagedMailboxOrderQuote, reservedMicros int64, resources []ManagedMailboxOrderResourcesInner, status string, updatedAt time.Time, ) *ManagedMailboxOrderListItemsInner`

NewManagedMailboxOrderListItemsInner instantiates a new ManagedMailboxOrderListItemsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxOrderListItemsInnerWithDefaults

`func NewManagedMailboxOrderListItemsInnerWithDefaults() *ManagedMailboxOrderListItemsInner`

NewManagedMailboxOrderListItemsInnerWithDefaults instantiates a new ManagedMailboxOrderListItemsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilledMicros

`func (o *ManagedMailboxOrderListItemsInner) GetBilledMicros() int64`

GetBilledMicros returns the BilledMicros field if non-nil, zero value otherwise.

### GetBilledMicrosOk

`func (o *ManagedMailboxOrderListItemsInner) GetBilledMicrosOk() (*int64, bool)`

GetBilledMicrosOk returns a tuple with the BilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledMicros

`func (o *ManagedMailboxOrderListItemsInner) SetBilledMicros(v int64)`

SetBilledMicros sets BilledMicros field to given value.


### SetBilledMicrosNil

`func (o *ManagedMailboxOrderListItemsInner) SetBilledMicrosNil(b bool)`

 SetBilledMicrosNil sets the value for BilledMicros to be an explicit nil

### UnsetBilledMicros
`func (o *ManagedMailboxOrderListItemsInner) UnsetBilledMicros()`

UnsetBilledMicros ensures that no value is present for BilledMicros, not even an explicit nil
### GetCostStatus

`func (o *ManagedMailboxOrderListItemsInner) GetCostStatus() string`

GetCostStatus returns the CostStatus field if non-nil, zero value otherwise.

### GetCostStatusOk

`func (o *ManagedMailboxOrderListItemsInner) GetCostStatusOk() (*string, bool)`

GetCostStatusOk returns a tuple with the CostStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostStatus

`func (o *ManagedMailboxOrderListItemsInner) SetCostStatus(v string)`

SetCostStatus sets CostStatus field to given value.


### GetCreatedAt

`func (o *ManagedMailboxOrderListItemsInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManagedMailboxOrderListItemsInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManagedMailboxOrderListItemsInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *ManagedMailboxOrderListItemsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManagedMailboxOrderListItemsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManagedMailboxOrderListItemsInner) SetId(v string)`

SetId sets Id field to given value.


### GetIssueCode

`func (o *ManagedMailboxOrderListItemsInner) GetIssueCode() string`

GetIssueCode returns the IssueCode field if non-nil, zero value otherwise.

### GetIssueCodeOk

`func (o *ManagedMailboxOrderListItemsInner) GetIssueCodeOk() (*string, bool)`

GetIssueCodeOk returns a tuple with the IssueCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssueCode

`func (o *ManagedMailboxOrderListItemsInner) SetIssueCode(v string)`

SetIssueCode sets IssueCode field to given value.


### SetIssueCodeNil

`func (o *ManagedMailboxOrderListItemsInner) SetIssueCodeNil(b bool)`

 SetIssueCodeNil sets the value for IssueCode to be an explicit nil

### UnsetIssueCode
`func (o *ManagedMailboxOrderListItemsInner) UnsetIssueCode()`

UnsetIssueCode ensures that no value is present for IssueCode, not even an explicit nil
### GetProviderCostMicros

`func (o *ManagedMailboxOrderListItemsInner) GetProviderCostMicros() int64`

GetProviderCostMicros returns the ProviderCostMicros field if non-nil, zero value otherwise.

### GetProviderCostMicrosOk

`func (o *ManagedMailboxOrderListItemsInner) GetProviderCostMicrosOk() (*int64, bool)`

GetProviderCostMicrosOk returns a tuple with the ProviderCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderCostMicros

`func (o *ManagedMailboxOrderListItemsInner) SetProviderCostMicros(v int64)`

SetProviderCostMicros sets ProviderCostMicros field to given value.


### SetProviderCostMicrosNil

`func (o *ManagedMailboxOrderListItemsInner) SetProviderCostMicrosNil(b bool)`

 SetProviderCostMicrosNil sets the value for ProviderCostMicros to be an explicit nil

### UnsetProviderCostMicros
`func (o *ManagedMailboxOrderListItemsInner) UnsetProviderCostMicros()`

UnsetProviderCostMicros ensures that no value is present for ProviderCostMicros, not even an explicit nil
### GetQuote

`func (o *ManagedMailboxOrderListItemsInner) GetQuote() ManagedMailboxOrderQuote`

GetQuote returns the Quote field if non-nil, zero value otherwise.

### GetQuoteOk

`func (o *ManagedMailboxOrderListItemsInner) GetQuoteOk() (*ManagedMailboxOrderQuote, bool)`

GetQuoteOk returns a tuple with the Quote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuote

`func (o *ManagedMailboxOrderListItemsInner) SetQuote(v ManagedMailboxOrderQuote)`

SetQuote sets Quote field to given value.


### GetReservedMicros

`func (o *ManagedMailboxOrderListItemsInner) GetReservedMicros() int64`

GetReservedMicros returns the ReservedMicros field if non-nil, zero value otherwise.

### GetReservedMicrosOk

`func (o *ManagedMailboxOrderListItemsInner) GetReservedMicrosOk() (*int64, bool)`

GetReservedMicrosOk returns a tuple with the ReservedMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedMicros

`func (o *ManagedMailboxOrderListItemsInner) SetReservedMicros(v int64)`

SetReservedMicros sets ReservedMicros field to given value.


### GetResources

`func (o *ManagedMailboxOrderListItemsInner) GetResources() []ManagedMailboxOrderResourcesInner`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *ManagedMailboxOrderListItemsInner) GetResourcesOk() (*[]ManagedMailboxOrderResourcesInner, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *ManagedMailboxOrderListItemsInner) SetResources(v []ManagedMailboxOrderResourcesInner)`

SetResources sets Resources field to given value.


### GetSource

`func (o *ManagedMailboxOrderListItemsInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ManagedMailboxOrderListItemsInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ManagedMailboxOrderListItemsInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *ManagedMailboxOrderListItemsInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetStatus

`func (o *ManagedMailboxOrderListItemsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ManagedMailboxOrderListItemsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ManagedMailboxOrderListItemsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *ManagedMailboxOrderListItemsInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ManagedMailboxOrderListItemsInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ManagedMailboxOrderListItemsInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


