# ClientInvoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BuyerAddress** | **NullableString** |  | 
**BuyerBillingEmail** | **NullableString** |  | 
**BuyerLegalName** | **NullableString** |  | 
**ClientAccountId** | **string** |  | 
**CollectorLegalName** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**CreatedBy** | **string** |  | 
**Currency** | **string** |  | 
**DueAt** | **NullableString** |  | 
**Id** | **string** |  | 
**InvoiceFooter** | **NullableString** |  | 
**InvoiceNumber** | **NullableString** |  | 
**InvoiceSequence** | **NullableFloat32** |  | 
**IssuedAt** | **NullableString** |  | 
**Lines** | [**[]ClientInvoiceLinesInner**](ClientInvoiceLinesInner.md) |  | 
**MinorUnitExponent** | **float32** |  | 
**OrganizationId** | **string** |  | 
**PaidAt** | **NullableString** |  | 
**PaymentDescriptor** | **NullableString** |  | 
**PaymentProvider** | **NullableString** |  | 
**PaymentProviderReference** | **NullableString** |  | 
**PaymentTerms** | **NullableString** |  | 
**ReplacesInvoiceId** | **NullableString** |  | 
**SellerAddress** | **NullableString** |  | 
**SellerBrandColor** | **NullableString** |  | 
**SellerContactEmail** | **NullableString** |  | 
**SellerLegalName** | **NullableString** |  | 
**SellerLogoMediaType** | **NullableString** |  | 
**SellerTaxId** | **NullableString** |  | 
**Status** | **string** |  | 
**SubtotalMicros** | **int64** |  | 
**TaxMicros** | **int64** |  | 
**TotalMicros** | **int64** |  | 
**TotalMinorUnits** | **float32** |  | 
**VoidReason** | **NullableString** |  | 
**VoidedAt** | **NullableString** |  | 

## Methods

### NewClientInvoice

`func NewClientInvoice(buyerAddress NullableString, buyerBillingEmail NullableString, buyerLegalName NullableString, clientAccountId string, collectorLegalName NullableString, createdAt string, createdBy string, currency string, dueAt NullableString, id string, invoiceFooter NullableString, invoiceNumber NullableString, invoiceSequence NullableFloat32, issuedAt NullableString, lines []ClientInvoiceLinesInner, minorUnitExponent float32, organizationId string, paidAt NullableString, paymentDescriptor NullableString, paymentProvider NullableString, paymentProviderReference NullableString, paymentTerms NullableString, replacesInvoiceId NullableString, sellerAddress NullableString, sellerBrandColor NullableString, sellerContactEmail NullableString, sellerLegalName NullableString, sellerLogoMediaType NullableString, sellerTaxId NullableString, status string, subtotalMicros int64, taxMicros int64, totalMicros int64, totalMinorUnits float32, voidReason NullableString, voidedAt NullableString, ) *ClientInvoice`

NewClientInvoice instantiates a new ClientInvoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientInvoiceWithDefaults

`func NewClientInvoiceWithDefaults() *ClientInvoice`

NewClientInvoiceWithDefaults instantiates a new ClientInvoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBuyerAddress

`func (o *ClientInvoice) GetBuyerAddress() string`

GetBuyerAddress returns the BuyerAddress field if non-nil, zero value otherwise.

### GetBuyerAddressOk

`func (o *ClientInvoice) GetBuyerAddressOk() (*string, bool)`

GetBuyerAddressOk returns a tuple with the BuyerAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerAddress

`func (o *ClientInvoice) SetBuyerAddress(v string)`

SetBuyerAddress sets BuyerAddress field to given value.


### SetBuyerAddressNil

`func (o *ClientInvoice) SetBuyerAddressNil(b bool)`

 SetBuyerAddressNil sets the value for BuyerAddress to be an explicit nil

### UnsetBuyerAddress
`func (o *ClientInvoice) UnsetBuyerAddress()`

UnsetBuyerAddress ensures that no value is present for BuyerAddress, not even an explicit nil
### GetBuyerBillingEmail

`func (o *ClientInvoice) GetBuyerBillingEmail() string`

GetBuyerBillingEmail returns the BuyerBillingEmail field if non-nil, zero value otherwise.

### GetBuyerBillingEmailOk

`func (o *ClientInvoice) GetBuyerBillingEmailOk() (*string, bool)`

GetBuyerBillingEmailOk returns a tuple with the BuyerBillingEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerBillingEmail

`func (o *ClientInvoice) SetBuyerBillingEmail(v string)`

SetBuyerBillingEmail sets BuyerBillingEmail field to given value.


### SetBuyerBillingEmailNil

`func (o *ClientInvoice) SetBuyerBillingEmailNil(b bool)`

 SetBuyerBillingEmailNil sets the value for BuyerBillingEmail to be an explicit nil

### UnsetBuyerBillingEmail
`func (o *ClientInvoice) UnsetBuyerBillingEmail()`

UnsetBuyerBillingEmail ensures that no value is present for BuyerBillingEmail, not even an explicit nil
### GetBuyerLegalName

`func (o *ClientInvoice) GetBuyerLegalName() string`

GetBuyerLegalName returns the BuyerLegalName field if non-nil, zero value otherwise.

### GetBuyerLegalNameOk

`func (o *ClientInvoice) GetBuyerLegalNameOk() (*string, bool)`

GetBuyerLegalNameOk returns a tuple with the BuyerLegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerLegalName

`func (o *ClientInvoice) SetBuyerLegalName(v string)`

SetBuyerLegalName sets BuyerLegalName field to given value.


### SetBuyerLegalNameNil

`func (o *ClientInvoice) SetBuyerLegalNameNil(b bool)`

 SetBuyerLegalNameNil sets the value for BuyerLegalName to be an explicit nil

### UnsetBuyerLegalName
`func (o *ClientInvoice) UnsetBuyerLegalName()`

UnsetBuyerLegalName ensures that no value is present for BuyerLegalName, not even an explicit nil
### GetClientAccountId

`func (o *ClientInvoice) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *ClientInvoice) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *ClientInvoice) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetCollectorLegalName

`func (o *ClientInvoice) GetCollectorLegalName() string`

GetCollectorLegalName returns the CollectorLegalName field if non-nil, zero value otherwise.

### GetCollectorLegalNameOk

`func (o *ClientInvoice) GetCollectorLegalNameOk() (*string, bool)`

GetCollectorLegalNameOk returns a tuple with the CollectorLegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollectorLegalName

`func (o *ClientInvoice) SetCollectorLegalName(v string)`

SetCollectorLegalName sets CollectorLegalName field to given value.


### SetCollectorLegalNameNil

`func (o *ClientInvoice) SetCollectorLegalNameNil(b bool)`

 SetCollectorLegalNameNil sets the value for CollectorLegalName to be an explicit nil

### UnsetCollectorLegalName
`func (o *ClientInvoice) UnsetCollectorLegalName()`

UnsetCollectorLegalName ensures that no value is present for CollectorLegalName, not even an explicit nil
### GetCreatedAt

`func (o *ClientInvoice) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientInvoice) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientInvoice) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedBy

`func (o *ClientInvoice) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ClientInvoice) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ClientInvoice) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetCurrency

`func (o *ClientInvoice) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ClientInvoice) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ClientInvoice) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDueAt

`func (o *ClientInvoice) GetDueAt() string`

GetDueAt returns the DueAt field if non-nil, zero value otherwise.

### GetDueAtOk

`func (o *ClientInvoice) GetDueAtOk() (*string, bool)`

GetDueAtOk returns a tuple with the DueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueAt

`func (o *ClientInvoice) SetDueAt(v string)`

SetDueAt sets DueAt field to given value.


### SetDueAtNil

`func (o *ClientInvoice) SetDueAtNil(b bool)`

 SetDueAtNil sets the value for DueAt to be an explicit nil

### UnsetDueAt
`func (o *ClientInvoice) UnsetDueAt()`

UnsetDueAt ensures that no value is present for DueAt, not even an explicit nil
### GetId

`func (o *ClientInvoice) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientInvoice) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientInvoice) SetId(v string)`

SetId sets Id field to given value.


### GetInvoiceFooter

`func (o *ClientInvoice) GetInvoiceFooter() string`

GetInvoiceFooter returns the InvoiceFooter field if non-nil, zero value otherwise.

### GetInvoiceFooterOk

`func (o *ClientInvoice) GetInvoiceFooterOk() (*string, bool)`

GetInvoiceFooterOk returns a tuple with the InvoiceFooter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceFooter

`func (o *ClientInvoice) SetInvoiceFooter(v string)`

SetInvoiceFooter sets InvoiceFooter field to given value.


### SetInvoiceFooterNil

`func (o *ClientInvoice) SetInvoiceFooterNil(b bool)`

 SetInvoiceFooterNil sets the value for InvoiceFooter to be an explicit nil

### UnsetInvoiceFooter
`func (o *ClientInvoice) UnsetInvoiceFooter()`

UnsetInvoiceFooter ensures that no value is present for InvoiceFooter, not even an explicit nil
### GetInvoiceNumber

`func (o *ClientInvoice) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *ClientInvoice) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *ClientInvoice) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### SetInvoiceNumberNil

`func (o *ClientInvoice) SetInvoiceNumberNil(b bool)`

 SetInvoiceNumberNil sets the value for InvoiceNumber to be an explicit nil

### UnsetInvoiceNumber
`func (o *ClientInvoice) UnsetInvoiceNumber()`

UnsetInvoiceNumber ensures that no value is present for InvoiceNumber, not even an explicit nil
### GetInvoiceSequence

`func (o *ClientInvoice) GetInvoiceSequence() float32`

GetInvoiceSequence returns the InvoiceSequence field if non-nil, zero value otherwise.

### GetInvoiceSequenceOk

`func (o *ClientInvoice) GetInvoiceSequenceOk() (*float32, bool)`

GetInvoiceSequenceOk returns a tuple with the InvoiceSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceSequence

`func (o *ClientInvoice) SetInvoiceSequence(v float32)`

SetInvoiceSequence sets InvoiceSequence field to given value.


### SetInvoiceSequenceNil

`func (o *ClientInvoice) SetInvoiceSequenceNil(b bool)`

 SetInvoiceSequenceNil sets the value for InvoiceSequence to be an explicit nil

### UnsetInvoiceSequence
`func (o *ClientInvoice) UnsetInvoiceSequence()`

UnsetInvoiceSequence ensures that no value is present for InvoiceSequence, not even an explicit nil
### GetIssuedAt

`func (o *ClientInvoice) GetIssuedAt() string`

GetIssuedAt returns the IssuedAt field if non-nil, zero value otherwise.

### GetIssuedAtOk

`func (o *ClientInvoice) GetIssuedAtOk() (*string, bool)`

GetIssuedAtOk returns a tuple with the IssuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuedAt

`func (o *ClientInvoice) SetIssuedAt(v string)`

SetIssuedAt sets IssuedAt field to given value.


### SetIssuedAtNil

`func (o *ClientInvoice) SetIssuedAtNil(b bool)`

 SetIssuedAtNil sets the value for IssuedAt to be an explicit nil

### UnsetIssuedAt
`func (o *ClientInvoice) UnsetIssuedAt()`

UnsetIssuedAt ensures that no value is present for IssuedAt, not even an explicit nil
### GetLines

`func (o *ClientInvoice) GetLines() []ClientInvoiceLinesInner`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *ClientInvoice) GetLinesOk() (*[]ClientInvoiceLinesInner, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *ClientInvoice) SetLines(v []ClientInvoiceLinesInner)`

SetLines sets Lines field to given value.


### GetMinorUnitExponent

`func (o *ClientInvoice) GetMinorUnitExponent() float32`

GetMinorUnitExponent returns the MinorUnitExponent field if non-nil, zero value otherwise.

### GetMinorUnitExponentOk

`func (o *ClientInvoice) GetMinorUnitExponentOk() (*float32, bool)`

GetMinorUnitExponentOk returns a tuple with the MinorUnitExponent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinorUnitExponent

`func (o *ClientInvoice) SetMinorUnitExponent(v float32)`

SetMinorUnitExponent sets MinorUnitExponent field to given value.


### GetOrganizationId

`func (o *ClientInvoice) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ClientInvoice) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ClientInvoice) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPaidAt

`func (o *ClientInvoice) GetPaidAt() string`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *ClientInvoice) GetPaidAtOk() (*string, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *ClientInvoice) SetPaidAt(v string)`

SetPaidAt sets PaidAt field to given value.


### SetPaidAtNil

`func (o *ClientInvoice) SetPaidAtNil(b bool)`

 SetPaidAtNil sets the value for PaidAt to be an explicit nil

### UnsetPaidAt
`func (o *ClientInvoice) UnsetPaidAt()`

UnsetPaidAt ensures that no value is present for PaidAt, not even an explicit nil
### GetPaymentDescriptor

`func (o *ClientInvoice) GetPaymentDescriptor() string`

GetPaymentDescriptor returns the PaymentDescriptor field if non-nil, zero value otherwise.

### GetPaymentDescriptorOk

`func (o *ClientInvoice) GetPaymentDescriptorOk() (*string, bool)`

GetPaymentDescriptorOk returns a tuple with the PaymentDescriptor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentDescriptor

`func (o *ClientInvoice) SetPaymentDescriptor(v string)`

SetPaymentDescriptor sets PaymentDescriptor field to given value.


### SetPaymentDescriptorNil

`func (o *ClientInvoice) SetPaymentDescriptorNil(b bool)`

 SetPaymentDescriptorNil sets the value for PaymentDescriptor to be an explicit nil

### UnsetPaymentDescriptor
`func (o *ClientInvoice) UnsetPaymentDescriptor()`

UnsetPaymentDescriptor ensures that no value is present for PaymentDescriptor, not even an explicit nil
### GetPaymentProvider

`func (o *ClientInvoice) GetPaymentProvider() string`

GetPaymentProvider returns the PaymentProvider field if non-nil, zero value otherwise.

### GetPaymentProviderOk

`func (o *ClientInvoice) GetPaymentProviderOk() (*string, bool)`

GetPaymentProviderOk returns a tuple with the PaymentProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentProvider

`func (o *ClientInvoice) SetPaymentProvider(v string)`

SetPaymentProvider sets PaymentProvider field to given value.


### SetPaymentProviderNil

`func (o *ClientInvoice) SetPaymentProviderNil(b bool)`

 SetPaymentProviderNil sets the value for PaymentProvider to be an explicit nil

### UnsetPaymentProvider
`func (o *ClientInvoice) UnsetPaymentProvider()`

UnsetPaymentProvider ensures that no value is present for PaymentProvider, not even an explicit nil
### GetPaymentProviderReference

`func (o *ClientInvoice) GetPaymentProviderReference() string`

GetPaymentProviderReference returns the PaymentProviderReference field if non-nil, zero value otherwise.

### GetPaymentProviderReferenceOk

`func (o *ClientInvoice) GetPaymentProviderReferenceOk() (*string, bool)`

GetPaymentProviderReferenceOk returns a tuple with the PaymentProviderReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentProviderReference

`func (o *ClientInvoice) SetPaymentProviderReference(v string)`

SetPaymentProviderReference sets PaymentProviderReference field to given value.


### SetPaymentProviderReferenceNil

`func (o *ClientInvoice) SetPaymentProviderReferenceNil(b bool)`

 SetPaymentProviderReferenceNil sets the value for PaymentProviderReference to be an explicit nil

### UnsetPaymentProviderReference
`func (o *ClientInvoice) UnsetPaymentProviderReference()`

UnsetPaymentProviderReference ensures that no value is present for PaymentProviderReference, not even an explicit nil
### GetPaymentTerms

`func (o *ClientInvoice) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *ClientInvoice) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *ClientInvoice) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.


### SetPaymentTermsNil

`func (o *ClientInvoice) SetPaymentTermsNil(b bool)`

 SetPaymentTermsNil sets the value for PaymentTerms to be an explicit nil

### UnsetPaymentTerms
`func (o *ClientInvoice) UnsetPaymentTerms()`

UnsetPaymentTerms ensures that no value is present for PaymentTerms, not even an explicit nil
### GetReplacesInvoiceId

`func (o *ClientInvoice) GetReplacesInvoiceId() string`

GetReplacesInvoiceId returns the ReplacesInvoiceId field if non-nil, zero value otherwise.

### GetReplacesInvoiceIdOk

`func (o *ClientInvoice) GetReplacesInvoiceIdOk() (*string, bool)`

GetReplacesInvoiceIdOk returns a tuple with the ReplacesInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacesInvoiceId

`func (o *ClientInvoice) SetReplacesInvoiceId(v string)`

SetReplacesInvoiceId sets ReplacesInvoiceId field to given value.


### SetReplacesInvoiceIdNil

`func (o *ClientInvoice) SetReplacesInvoiceIdNil(b bool)`

 SetReplacesInvoiceIdNil sets the value for ReplacesInvoiceId to be an explicit nil

### UnsetReplacesInvoiceId
`func (o *ClientInvoice) UnsetReplacesInvoiceId()`

UnsetReplacesInvoiceId ensures that no value is present for ReplacesInvoiceId, not even an explicit nil
### GetSellerAddress

`func (o *ClientInvoice) GetSellerAddress() string`

GetSellerAddress returns the SellerAddress field if non-nil, zero value otherwise.

### GetSellerAddressOk

`func (o *ClientInvoice) GetSellerAddressOk() (*string, bool)`

GetSellerAddressOk returns a tuple with the SellerAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerAddress

`func (o *ClientInvoice) SetSellerAddress(v string)`

SetSellerAddress sets SellerAddress field to given value.


### SetSellerAddressNil

`func (o *ClientInvoice) SetSellerAddressNil(b bool)`

 SetSellerAddressNil sets the value for SellerAddress to be an explicit nil

### UnsetSellerAddress
`func (o *ClientInvoice) UnsetSellerAddress()`

UnsetSellerAddress ensures that no value is present for SellerAddress, not even an explicit nil
### GetSellerBrandColor

`func (o *ClientInvoice) GetSellerBrandColor() string`

GetSellerBrandColor returns the SellerBrandColor field if non-nil, zero value otherwise.

### GetSellerBrandColorOk

`func (o *ClientInvoice) GetSellerBrandColorOk() (*string, bool)`

GetSellerBrandColorOk returns a tuple with the SellerBrandColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerBrandColor

`func (o *ClientInvoice) SetSellerBrandColor(v string)`

SetSellerBrandColor sets SellerBrandColor field to given value.


### SetSellerBrandColorNil

`func (o *ClientInvoice) SetSellerBrandColorNil(b bool)`

 SetSellerBrandColorNil sets the value for SellerBrandColor to be an explicit nil

### UnsetSellerBrandColor
`func (o *ClientInvoice) UnsetSellerBrandColor()`

UnsetSellerBrandColor ensures that no value is present for SellerBrandColor, not even an explicit nil
### GetSellerContactEmail

`func (o *ClientInvoice) GetSellerContactEmail() string`

GetSellerContactEmail returns the SellerContactEmail field if non-nil, zero value otherwise.

### GetSellerContactEmailOk

`func (o *ClientInvoice) GetSellerContactEmailOk() (*string, bool)`

GetSellerContactEmailOk returns a tuple with the SellerContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerContactEmail

`func (o *ClientInvoice) SetSellerContactEmail(v string)`

SetSellerContactEmail sets SellerContactEmail field to given value.


### SetSellerContactEmailNil

`func (o *ClientInvoice) SetSellerContactEmailNil(b bool)`

 SetSellerContactEmailNil sets the value for SellerContactEmail to be an explicit nil

### UnsetSellerContactEmail
`func (o *ClientInvoice) UnsetSellerContactEmail()`

UnsetSellerContactEmail ensures that no value is present for SellerContactEmail, not even an explicit nil
### GetSellerLegalName

`func (o *ClientInvoice) GetSellerLegalName() string`

GetSellerLegalName returns the SellerLegalName field if non-nil, zero value otherwise.

### GetSellerLegalNameOk

`func (o *ClientInvoice) GetSellerLegalNameOk() (*string, bool)`

GetSellerLegalNameOk returns a tuple with the SellerLegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerLegalName

`func (o *ClientInvoice) SetSellerLegalName(v string)`

SetSellerLegalName sets SellerLegalName field to given value.


### SetSellerLegalNameNil

`func (o *ClientInvoice) SetSellerLegalNameNil(b bool)`

 SetSellerLegalNameNil sets the value for SellerLegalName to be an explicit nil

### UnsetSellerLegalName
`func (o *ClientInvoice) UnsetSellerLegalName()`

UnsetSellerLegalName ensures that no value is present for SellerLegalName, not even an explicit nil
### GetSellerLogoMediaType

`func (o *ClientInvoice) GetSellerLogoMediaType() string`

GetSellerLogoMediaType returns the SellerLogoMediaType field if non-nil, zero value otherwise.

### GetSellerLogoMediaTypeOk

`func (o *ClientInvoice) GetSellerLogoMediaTypeOk() (*string, bool)`

GetSellerLogoMediaTypeOk returns a tuple with the SellerLogoMediaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerLogoMediaType

`func (o *ClientInvoice) SetSellerLogoMediaType(v string)`

SetSellerLogoMediaType sets SellerLogoMediaType field to given value.


### SetSellerLogoMediaTypeNil

`func (o *ClientInvoice) SetSellerLogoMediaTypeNil(b bool)`

 SetSellerLogoMediaTypeNil sets the value for SellerLogoMediaType to be an explicit nil

### UnsetSellerLogoMediaType
`func (o *ClientInvoice) UnsetSellerLogoMediaType()`

UnsetSellerLogoMediaType ensures that no value is present for SellerLogoMediaType, not even an explicit nil
### GetSellerTaxId

`func (o *ClientInvoice) GetSellerTaxId() string`

GetSellerTaxId returns the SellerTaxId field if non-nil, zero value otherwise.

### GetSellerTaxIdOk

`func (o *ClientInvoice) GetSellerTaxIdOk() (*string, bool)`

GetSellerTaxIdOk returns a tuple with the SellerTaxId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerTaxId

`func (o *ClientInvoice) SetSellerTaxId(v string)`

SetSellerTaxId sets SellerTaxId field to given value.


### SetSellerTaxIdNil

`func (o *ClientInvoice) SetSellerTaxIdNil(b bool)`

 SetSellerTaxIdNil sets the value for SellerTaxId to be an explicit nil

### UnsetSellerTaxId
`func (o *ClientInvoice) UnsetSellerTaxId()`

UnsetSellerTaxId ensures that no value is present for SellerTaxId, not even an explicit nil
### GetStatus

`func (o *ClientInvoice) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientInvoice) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientInvoice) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSubtotalMicros

`func (o *ClientInvoice) GetSubtotalMicros() int64`

GetSubtotalMicros returns the SubtotalMicros field if non-nil, zero value otherwise.

### GetSubtotalMicrosOk

`func (o *ClientInvoice) GetSubtotalMicrosOk() (*int64, bool)`

GetSubtotalMicrosOk returns a tuple with the SubtotalMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotalMicros

`func (o *ClientInvoice) SetSubtotalMicros(v int64)`

SetSubtotalMicros sets SubtotalMicros field to given value.


### GetTaxMicros

`func (o *ClientInvoice) GetTaxMicros() int64`

GetTaxMicros returns the TaxMicros field if non-nil, zero value otherwise.

### GetTaxMicrosOk

`func (o *ClientInvoice) GetTaxMicrosOk() (*int64, bool)`

GetTaxMicrosOk returns a tuple with the TaxMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxMicros

`func (o *ClientInvoice) SetTaxMicros(v int64)`

SetTaxMicros sets TaxMicros field to given value.


### GetTotalMicros

`func (o *ClientInvoice) GetTotalMicros() int64`

GetTotalMicros returns the TotalMicros field if non-nil, zero value otherwise.

### GetTotalMicrosOk

`func (o *ClientInvoice) GetTotalMicrosOk() (*int64, bool)`

GetTotalMicrosOk returns a tuple with the TotalMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMicros

`func (o *ClientInvoice) SetTotalMicros(v int64)`

SetTotalMicros sets TotalMicros field to given value.


### GetTotalMinorUnits

`func (o *ClientInvoice) GetTotalMinorUnits() float32`

GetTotalMinorUnits returns the TotalMinorUnits field if non-nil, zero value otherwise.

### GetTotalMinorUnitsOk

`func (o *ClientInvoice) GetTotalMinorUnitsOk() (*float32, bool)`

GetTotalMinorUnitsOk returns a tuple with the TotalMinorUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMinorUnits

`func (o *ClientInvoice) SetTotalMinorUnits(v float32)`

SetTotalMinorUnits sets TotalMinorUnits field to given value.


### GetVoidReason

`func (o *ClientInvoice) GetVoidReason() string`

GetVoidReason returns the VoidReason field if non-nil, zero value otherwise.

### GetVoidReasonOk

`func (o *ClientInvoice) GetVoidReasonOk() (*string, bool)`

GetVoidReasonOk returns a tuple with the VoidReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoidReason

`func (o *ClientInvoice) SetVoidReason(v string)`

SetVoidReason sets VoidReason field to given value.


### SetVoidReasonNil

`func (o *ClientInvoice) SetVoidReasonNil(b bool)`

 SetVoidReasonNil sets the value for VoidReason to be an explicit nil

### UnsetVoidReason
`func (o *ClientInvoice) UnsetVoidReason()`

UnsetVoidReason ensures that no value is present for VoidReason, not even an explicit nil
### GetVoidedAt

`func (o *ClientInvoice) GetVoidedAt() string`

GetVoidedAt returns the VoidedAt field if non-nil, zero value otherwise.

### GetVoidedAtOk

`func (o *ClientInvoice) GetVoidedAtOk() (*string, bool)`

GetVoidedAtOk returns a tuple with the VoidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoidedAt

`func (o *ClientInvoice) SetVoidedAt(v string)`

SetVoidedAt sets VoidedAt field to given value.


### SetVoidedAtNil

`func (o *ClientInvoice) SetVoidedAtNil(b bool)`

 SetVoidedAtNil sets the value for VoidedAt to be an explicit nil

### UnsetVoidedAt
`func (o *ClientInvoice) UnsetVoidedAt()`

UnsetVoidedAt ensures that no value is present for VoidedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


