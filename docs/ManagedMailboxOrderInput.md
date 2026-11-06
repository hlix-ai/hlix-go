# ManagedMailboxOrderInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Contact** | [**ManagedMailboxOrderInputContact**](ManagedMailboxOrderInputContact.md) |  | 
**IdempotencyKey** | **string** |  | 
**QuoteId** | **string** |  | 

## Methods

### NewManagedMailboxOrderInput

`func NewManagedMailboxOrderInput(contact ManagedMailboxOrderInputContact, idempotencyKey string, quoteId string, ) *ManagedMailboxOrderInput`

NewManagedMailboxOrderInput instantiates a new ManagedMailboxOrderInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxOrderInputWithDefaults

`func NewManagedMailboxOrderInputWithDefaults() *ManagedMailboxOrderInput`

NewManagedMailboxOrderInputWithDefaults instantiates a new ManagedMailboxOrderInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContact

`func (o *ManagedMailboxOrderInput) GetContact() ManagedMailboxOrderInputContact`

GetContact returns the Contact field if non-nil, zero value otherwise.

### GetContactOk

`func (o *ManagedMailboxOrderInput) GetContactOk() (*ManagedMailboxOrderInputContact, bool)`

GetContactOk returns a tuple with the Contact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContact

`func (o *ManagedMailboxOrderInput) SetContact(v ManagedMailboxOrderInputContact)`

SetContact sets Contact field to given value.


### GetIdempotencyKey

`func (o *ManagedMailboxOrderInput) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *ManagedMailboxOrderInput) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *ManagedMailboxOrderInput) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetQuoteId

`func (o *ManagedMailboxOrderInput) GetQuoteId() string`

GetQuoteId returns the QuoteId field if non-nil, zero value otherwise.

### GetQuoteIdOk

`func (o *ManagedMailboxOrderInput) GetQuoteIdOk() (*string, bool)`

GetQuoteIdOk returns a tuple with the QuoteId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteId

`func (o *ManagedMailboxOrderInput) SetQuoteId(v string)`

SetQuoteId sets QuoteId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


