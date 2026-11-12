# UpsertBillingProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **string** |  |
**BrandColor** | Pointer to **NullableString** |  | [optional]
**ContactEmail** | Pointer to **NullableString** |  | [optional]
**DefaultPaymentTerms** | Pointer to **NullableString** |  | [optional]
**InvoiceFooter** | Pointer to **NullableString** |  | [optional]
**LegalName** | **string** |  |
**Logo** | Pointer to [**NullableUpsertBillingProfileLogo**](UpsertBillingProfileLogo.md) |  | [optional]
**TaxId** | Pointer to **NullableString** |  | [optional]

## Methods

### NewUpsertBillingProfile

`func NewUpsertBillingProfile(address string, legalName string, ) *UpsertBillingProfile`

NewUpsertBillingProfile instantiates a new UpsertBillingProfile object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpsertBillingProfileWithDefaults

`func NewUpsertBillingProfileWithDefaults() *UpsertBillingProfile`

NewUpsertBillingProfileWithDefaults instantiates a new UpsertBillingProfile object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAddress

`func (o *UpsertBillingProfile) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *UpsertBillingProfile) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *UpsertBillingProfile) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetBrandColor

`func (o *UpsertBillingProfile) GetBrandColor() string`

GetBrandColor returns the BrandColor field if non-nil, zero value otherwise.

### GetBrandColorOk

`func (o *UpsertBillingProfile) GetBrandColorOk() (*string, bool)`

GetBrandColorOk returns a tuple with the BrandColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandColor

`func (o *UpsertBillingProfile) SetBrandColor(v string)`

SetBrandColor sets BrandColor field to given value.

### HasBrandColor

`func (o *UpsertBillingProfile) HasBrandColor() bool`

HasBrandColor returns a boolean if a field has been set.

### SetBrandColorNil

`func (o *UpsertBillingProfile) SetBrandColorNil(b bool)`

 SetBrandColorNil sets the value for BrandColor to be an explicit nil

### UnsetBrandColor
`func (o *UpsertBillingProfile) UnsetBrandColor()`

UnsetBrandColor ensures that no value is present for BrandColor, not even an explicit nil
### GetContactEmail

`func (o *UpsertBillingProfile) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *UpsertBillingProfile) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *UpsertBillingProfile) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.

### HasContactEmail

`func (o *UpsertBillingProfile) HasContactEmail() bool`

HasContactEmail returns a boolean if a field has been set.

### SetContactEmailNil

`func (o *UpsertBillingProfile) SetContactEmailNil(b bool)`

 SetContactEmailNil sets the value for ContactEmail to be an explicit nil

### UnsetContactEmail
`func (o *UpsertBillingProfile) UnsetContactEmail()`

UnsetContactEmail ensures that no value is present for ContactEmail, not even an explicit nil
### GetDefaultPaymentTerms

`func (o *UpsertBillingProfile) GetDefaultPaymentTerms() string`

GetDefaultPaymentTerms returns the DefaultPaymentTerms field if non-nil, zero value otherwise.

### GetDefaultPaymentTermsOk

`func (o *UpsertBillingProfile) GetDefaultPaymentTermsOk() (*string, bool)`

GetDefaultPaymentTermsOk returns a tuple with the DefaultPaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultPaymentTerms

`func (o *UpsertBillingProfile) SetDefaultPaymentTerms(v string)`

SetDefaultPaymentTerms sets DefaultPaymentTerms field to given value.

### HasDefaultPaymentTerms

`func (o *UpsertBillingProfile) HasDefaultPaymentTerms() bool`

HasDefaultPaymentTerms returns a boolean if a field has been set.

### SetDefaultPaymentTermsNil

`func (o *UpsertBillingProfile) SetDefaultPaymentTermsNil(b bool)`

 SetDefaultPaymentTermsNil sets the value for DefaultPaymentTerms to be an explicit nil

### UnsetDefaultPaymentTerms
`func (o *UpsertBillingProfile) UnsetDefaultPaymentTerms()`

UnsetDefaultPaymentTerms ensures that no value is present for DefaultPaymentTerms, not even an explicit nil
### GetInvoiceFooter

`func (o *UpsertBillingProfile) GetInvoiceFooter() string`

GetInvoiceFooter returns the InvoiceFooter field if non-nil, zero value otherwise.

### GetInvoiceFooterOk

`func (o *UpsertBillingProfile) GetInvoiceFooterOk() (*string, bool)`

GetInvoiceFooterOk returns a tuple with the InvoiceFooter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceFooter

`func (o *UpsertBillingProfile) SetInvoiceFooter(v string)`

SetInvoiceFooter sets InvoiceFooter field to given value.

### HasInvoiceFooter

`func (o *UpsertBillingProfile) HasInvoiceFooter() bool`

HasInvoiceFooter returns a boolean if a field has been set.

### SetInvoiceFooterNil

`func (o *UpsertBillingProfile) SetInvoiceFooterNil(b bool)`

 SetInvoiceFooterNil sets the value for InvoiceFooter to be an explicit nil

### UnsetInvoiceFooter
`func (o *UpsertBillingProfile) UnsetInvoiceFooter()`

UnsetInvoiceFooter ensures that no value is present for InvoiceFooter, not even an explicit nil
### GetLegalName

`func (o *UpsertBillingProfile) GetLegalName() string`

GetLegalName returns the LegalName field if non-nil, zero value otherwise.

### GetLegalNameOk

`func (o *UpsertBillingProfile) GetLegalNameOk() (*string, bool)`

GetLegalNameOk returns a tuple with the LegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalName

`func (o *UpsertBillingProfile) SetLegalName(v string)`

SetLegalName sets LegalName field to given value.


### GetLogo

`func (o *UpsertBillingProfile) GetLogo() UpsertBillingProfileLogo`

GetLogo returns the Logo field if non-nil, zero value otherwise.

### GetLogoOk

`func (o *UpsertBillingProfile) GetLogoOk() (*UpsertBillingProfileLogo, bool)`

GetLogoOk returns a tuple with the Logo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogo

`func (o *UpsertBillingProfile) SetLogo(v UpsertBillingProfileLogo)`

SetLogo sets Logo field to given value.

### HasLogo

`func (o *UpsertBillingProfile) HasLogo() bool`

HasLogo returns a boolean if a field has been set.

### SetLogoNil

`func (o *UpsertBillingProfile) SetLogoNil(b bool)`

 SetLogoNil sets the value for Logo to be an explicit nil

### UnsetLogo
`func (o *UpsertBillingProfile) UnsetLogo()`

UnsetLogo ensures that no value is present for Logo, not even an explicit nil
### GetTaxId

`func (o *UpsertBillingProfile) GetTaxId() string`

GetTaxId returns the TaxId field if non-nil, zero value otherwise.

### GetTaxIdOk

`func (o *UpsertBillingProfile) GetTaxIdOk() (*string, bool)`

GetTaxIdOk returns a tuple with the TaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxId

`func (o *UpsertBillingProfile) SetTaxId(v string)`

SetTaxId sets TaxId field to given value.

### HasTaxId

`func (o *UpsertBillingProfile) HasTaxId() bool`

HasTaxId returns a boolean if a field has been set.

### SetTaxIdNil

`func (o *UpsertBillingProfile) SetTaxIdNil(b bool)`

 SetTaxIdNil sets the value for TaxId to be an explicit nil

### UnsetTaxId
`func (o *UpsertBillingProfile) UnsetTaxId()`

UnsetTaxId ensures that no value is present for TaxId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


