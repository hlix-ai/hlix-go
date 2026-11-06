# ClientPaymentLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckoutUrl** | **string** |  | 
**Provider** | **string** |  | 
**ProviderReference** | **string** |  | 

## Methods

### NewClientPaymentLink

`func NewClientPaymentLink(checkoutUrl string, provider string, providerReference string, ) *ClientPaymentLink`

NewClientPaymentLink instantiates a new ClientPaymentLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientPaymentLinkWithDefaults

`func NewClientPaymentLinkWithDefaults() *ClientPaymentLink`

NewClientPaymentLinkWithDefaults instantiates a new ClientPaymentLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckoutUrl

`func (o *ClientPaymentLink) GetCheckoutUrl() string`

GetCheckoutUrl returns the CheckoutUrl field if non-nil, zero value otherwise.

### GetCheckoutUrlOk

`func (o *ClientPaymentLink) GetCheckoutUrlOk() (*string, bool)`

GetCheckoutUrlOk returns a tuple with the CheckoutUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutUrl

`func (o *ClientPaymentLink) SetCheckoutUrl(v string)`

SetCheckoutUrl sets CheckoutUrl field to given value.


### GetProvider

`func (o *ClientPaymentLink) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ClientPaymentLink) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ClientPaymentLink) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetProviderReference

`func (o *ClientPaymentLink) GetProviderReference() string`

GetProviderReference returns the ProviderReference field if non-nil, zero value otherwise.

### GetProviderReferenceOk

`func (o *ClientPaymentLink) GetProviderReferenceOk() (*string, bool)`

GetProviderReferenceOk returns a tuple with the ProviderReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderReference

`func (o *ClientPaymentLink) SetProviderReference(v string)`

SetProviderReference sets ProviderReference field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


