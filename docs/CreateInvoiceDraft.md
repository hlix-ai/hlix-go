# CreateInvoiceDraft

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillableIds** | **[]string** |  | 
**BuyerAddress** | **string** |  | 
**BuyerBillingEmail** | Pointer to **NullableString** |  | [optional] 
**BuyerLegalName** | Pointer to **string** |  | [optional] 
**DueAt** | **time.Time** |  | 
**PaymentTerms** | Pointer to **string** |  | [optional] 
**ReplacesInvoiceId** | Pointer to **NullableString** |  | [optional] 
**SellerAddress** | Pointer to **string** |  | [optional] 
**SellerLegalName** | Pointer to **string** |  | [optional] 
**TaxRatesBps** | Pointer to [**CreateInvoiceDraftTaxRatesBps**](CreateInvoiceDraftTaxRatesBps.md) |  | [optional] 

## Methods

### NewCreateInvoiceDraft

`func NewCreateInvoiceDraft(billableIds []string, buyerAddress string, dueAt time.Time, ) *CreateInvoiceDraft`

NewCreateInvoiceDraft instantiates a new CreateInvoiceDraft object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateInvoiceDraftWithDefaults

`func NewCreateInvoiceDraftWithDefaults() *CreateInvoiceDraft`

NewCreateInvoiceDraftWithDefaults instantiates a new CreateInvoiceDraft object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBillableIds

`func (o *CreateInvoiceDraft) GetBillableIds() []string`

GetBillableIds returns the BillableIds field if non-nil, zero value otherwise.

### GetBillableIdsOk

`func (o *CreateInvoiceDraft) GetBillableIdsOk() (*[]string, bool)`

GetBillableIdsOk returns a tuple with the BillableIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillableIds

`func (o *CreateInvoiceDraft) SetBillableIds(v []string)`

SetBillableIds sets BillableIds field to given value.


### GetBuyerAddress

`func (o *CreateInvoiceDraft) GetBuyerAddress() string`

GetBuyerAddress returns the BuyerAddress field if non-nil, zero value otherwise.

### GetBuyerAddressOk

`func (o *CreateInvoiceDraft) GetBuyerAddressOk() (*string, bool)`

GetBuyerAddressOk returns a tuple with the BuyerAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerAddress

`func (o *CreateInvoiceDraft) SetBuyerAddress(v string)`

SetBuyerAddress sets BuyerAddress field to given value.


### GetBuyerBillingEmail

`func (o *CreateInvoiceDraft) GetBuyerBillingEmail() string`

GetBuyerBillingEmail returns the BuyerBillingEmail field if non-nil, zero value otherwise.

### GetBuyerBillingEmailOk

`func (o *CreateInvoiceDraft) GetBuyerBillingEmailOk() (*string, bool)`

GetBuyerBillingEmailOk returns a tuple with the BuyerBillingEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerBillingEmail

`func (o *CreateInvoiceDraft) SetBuyerBillingEmail(v string)`

SetBuyerBillingEmail sets BuyerBillingEmail field to given value.

### HasBuyerBillingEmail

`func (o *CreateInvoiceDraft) HasBuyerBillingEmail() bool`

HasBuyerBillingEmail returns a boolean if a field has been set.

### SetBuyerBillingEmailNil

`func (o *CreateInvoiceDraft) SetBuyerBillingEmailNil(b bool)`

 SetBuyerBillingEmailNil sets the value for BuyerBillingEmail to be an explicit nil

### UnsetBuyerBillingEmail
`func (o *CreateInvoiceDraft) UnsetBuyerBillingEmail()`

UnsetBuyerBillingEmail ensures that no value is present for BuyerBillingEmail, not even an explicit nil
### GetBuyerLegalName

`func (o *CreateInvoiceDraft) GetBuyerLegalName() string`

GetBuyerLegalName returns the BuyerLegalName field if non-nil, zero value otherwise.

### GetBuyerLegalNameOk

`func (o *CreateInvoiceDraft) GetBuyerLegalNameOk() (*string, bool)`

GetBuyerLegalNameOk returns a tuple with the BuyerLegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerLegalName

`func (o *CreateInvoiceDraft) SetBuyerLegalName(v string)`

SetBuyerLegalName sets BuyerLegalName field to given value.

### HasBuyerLegalName

`func (o *CreateInvoiceDraft) HasBuyerLegalName() bool`

HasBuyerLegalName returns a boolean if a field has been set.

### GetDueAt

`func (o *CreateInvoiceDraft) GetDueAt() time.Time`

GetDueAt returns the DueAt field if non-nil, zero value otherwise.

### GetDueAtOk

`func (o *CreateInvoiceDraft) GetDueAtOk() (*time.Time, bool)`

GetDueAtOk returns a tuple with the DueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueAt

`func (o *CreateInvoiceDraft) SetDueAt(v time.Time)`

SetDueAt sets DueAt field to given value.


### GetPaymentTerms

`func (o *CreateInvoiceDraft) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *CreateInvoiceDraft) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *CreateInvoiceDraft) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.

### HasPaymentTerms

`func (o *CreateInvoiceDraft) HasPaymentTerms() bool`

HasPaymentTerms returns a boolean if a field has been set.

### GetReplacesInvoiceId

`func (o *CreateInvoiceDraft) GetReplacesInvoiceId() string`

GetReplacesInvoiceId returns the ReplacesInvoiceId field if non-nil, zero value otherwise.

### GetReplacesInvoiceIdOk

`func (o *CreateInvoiceDraft) GetReplacesInvoiceIdOk() (*string, bool)`

GetReplacesInvoiceIdOk returns a tuple with the ReplacesInvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacesInvoiceId

`func (o *CreateInvoiceDraft) SetReplacesInvoiceId(v string)`

SetReplacesInvoiceId sets ReplacesInvoiceId field to given value.

### HasReplacesInvoiceId

`func (o *CreateInvoiceDraft) HasReplacesInvoiceId() bool`

HasReplacesInvoiceId returns a boolean if a field has been set.

### SetReplacesInvoiceIdNil

`func (o *CreateInvoiceDraft) SetReplacesInvoiceIdNil(b bool)`

 SetReplacesInvoiceIdNil sets the value for ReplacesInvoiceId to be an explicit nil

### UnsetReplacesInvoiceId
`func (o *CreateInvoiceDraft) UnsetReplacesInvoiceId()`

UnsetReplacesInvoiceId ensures that no value is present for ReplacesInvoiceId, not even an explicit nil
### GetSellerAddress

`func (o *CreateInvoiceDraft) GetSellerAddress() string`

GetSellerAddress returns the SellerAddress field if non-nil, zero value otherwise.

### GetSellerAddressOk

`func (o *CreateInvoiceDraft) GetSellerAddressOk() (*string, bool)`

GetSellerAddressOk returns a tuple with the SellerAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerAddress

`func (o *CreateInvoiceDraft) SetSellerAddress(v string)`

SetSellerAddress sets SellerAddress field to given value.

### HasSellerAddress

`func (o *CreateInvoiceDraft) HasSellerAddress() bool`

HasSellerAddress returns a boolean if a field has been set.

### GetSellerLegalName

`func (o *CreateInvoiceDraft) GetSellerLegalName() string`

GetSellerLegalName returns the SellerLegalName field if non-nil, zero value otherwise.

### GetSellerLegalNameOk

`func (o *CreateInvoiceDraft) GetSellerLegalNameOk() (*string, bool)`

GetSellerLegalNameOk returns a tuple with the SellerLegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSellerLegalName

`func (o *CreateInvoiceDraft) SetSellerLegalName(v string)`

SetSellerLegalName sets SellerLegalName field to given value.

### HasSellerLegalName

`func (o *CreateInvoiceDraft) HasSellerLegalName() bool`

HasSellerLegalName returns a boolean if a field has been set.

### GetTaxRatesBps

`func (o *CreateInvoiceDraft) GetTaxRatesBps() CreateInvoiceDraftTaxRatesBps`

GetTaxRatesBps returns the TaxRatesBps field if non-nil, zero value otherwise.

### GetTaxRatesBpsOk

`func (o *CreateInvoiceDraft) GetTaxRatesBpsOk() (*CreateInvoiceDraftTaxRatesBps, bool)`

GetTaxRatesBpsOk returns a tuple with the TaxRatesBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRatesBps

`func (o *CreateInvoiceDraft) SetTaxRatesBps(v CreateInvoiceDraftTaxRatesBps)`

SetTaxRatesBps sets TaxRatesBps field to given value.

### HasTaxRatesBps

`func (o *CreateInvoiceDraft) HasTaxRatesBps() bool`

HasTaxRatesBps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


