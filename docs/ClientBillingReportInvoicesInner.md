# ClientBillingReportInvoicesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | **string** |  | 
**DueAt** | **NullableString** |  | 
**Id** | **string** |  | 
**InvoiceNumber** | **NullableString** |  | 
**IssuedAt** | **NullableString** |  | 
**MinorUnitExponent** | **int32** |  | 
**PaidAt** | **NullableString** |  | 
**State** | **string** |  | 
**TotalMinorUnits** | **int32** |  | 

## Methods

### NewClientBillingReportInvoicesInner

`func NewClientBillingReportInvoicesInner(currency string, dueAt NullableString, id string, invoiceNumber NullableString, issuedAt NullableString, minorUnitExponent int32, paidAt NullableString, state string, totalMinorUnits int32, ) *ClientBillingReportInvoicesInner`

NewClientBillingReportInvoicesInner instantiates a new ClientBillingReportInvoicesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBillingReportInvoicesInnerWithDefaults

`func NewClientBillingReportInvoicesInnerWithDefaults() *ClientBillingReportInvoicesInner`

NewClientBillingReportInvoicesInnerWithDefaults instantiates a new ClientBillingReportInvoicesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *ClientBillingReportInvoicesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ClientBillingReportInvoicesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ClientBillingReportInvoicesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDueAt

`func (o *ClientBillingReportInvoicesInner) GetDueAt() string`

GetDueAt returns the DueAt field if non-nil, zero value otherwise.

### GetDueAtOk

`func (o *ClientBillingReportInvoicesInner) GetDueAtOk() (*string, bool)`

GetDueAtOk returns a tuple with the DueAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueAt

`func (o *ClientBillingReportInvoicesInner) SetDueAt(v string)`

SetDueAt sets DueAt field to given value.


### SetDueAtNil

`func (o *ClientBillingReportInvoicesInner) SetDueAtNil(b bool)`

 SetDueAtNil sets the value for DueAt to be an explicit nil

### UnsetDueAt
`func (o *ClientBillingReportInvoicesInner) UnsetDueAt()`

UnsetDueAt ensures that no value is present for DueAt, not even an explicit nil
### GetId

`func (o *ClientBillingReportInvoicesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientBillingReportInvoicesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientBillingReportInvoicesInner) SetId(v string)`

SetId sets Id field to given value.


### GetInvoiceNumber

`func (o *ClientBillingReportInvoicesInner) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *ClientBillingReportInvoicesInner) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *ClientBillingReportInvoicesInner) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### SetInvoiceNumberNil

`func (o *ClientBillingReportInvoicesInner) SetInvoiceNumberNil(b bool)`

 SetInvoiceNumberNil sets the value for InvoiceNumber to be an explicit nil

### UnsetInvoiceNumber
`func (o *ClientBillingReportInvoicesInner) UnsetInvoiceNumber()`

UnsetInvoiceNumber ensures that no value is present for InvoiceNumber, not even an explicit nil
### GetIssuedAt

`func (o *ClientBillingReportInvoicesInner) GetIssuedAt() string`

GetIssuedAt returns the IssuedAt field if non-nil, zero value otherwise.

### GetIssuedAtOk

`func (o *ClientBillingReportInvoicesInner) GetIssuedAtOk() (*string, bool)`

GetIssuedAtOk returns a tuple with the IssuedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuedAt

`func (o *ClientBillingReportInvoicesInner) SetIssuedAt(v string)`

SetIssuedAt sets IssuedAt field to given value.


### SetIssuedAtNil

`func (o *ClientBillingReportInvoicesInner) SetIssuedAtNil(b bool)`

 SetIssuedAtNil sets the value for IssuedAt to be an explicit nil

### UnsetIssuedAt
`func (o *ClientBillingReportInvoicesInner) UnsetIssuedAt()`

UnsetIssuedAt ensures that no value is present for IssuedAt, not even an explicit nil
### GetMinorUnitExponent

`func (o *ClientBillingReportInvoicesInner) GetMinorUnitExponent() int32`

GetMinorUnitExponent returns the MinorUnitExponent field if non-nil, zero value otherwise.

### GetMinorUnitExponentOk

`func (o *ClientBillingReportInvoicesInner) GetMinorUnitExponentOk() (*int32, bool)`

GetMinorUnitExponentOk returns a tuple with the MinorUnitExponent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinorUnitExponent

`func (o *ClientBillingReportInvoicesInner) SetMinorUnitExponent(v int32)`

SetMinorUnitExponent sets MinorUnitExponent field to given value.


### GetPaidAt

`func (o *ClientBillingReportInvoicesInner) GetPaidAt() string`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *ClientBillingReportInvoicesInner) GetPaidAtOk() (*string, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *ClientBillingReportInvoicesInner) SetPaidAt(v string)`

SetPaidAt sets PaidAt field to given value.


### SetPaidAtNil

`func (o *ClientBillingReportInvoicesInner) SetPaidAtNil(b bool)`

 SetPaidAtNil sets the value for PaidAt to be an explicit nil

### UnsetPaidAt
`func (o *ClientBillingReportInvoicesInner) UnsetPaidAt()`

UnsetPaidAt ensures that no value is present for PaidAt, not even an explicit nil
### GetState

`func (o *ClientBillingReportInvoicesInner) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ClientBillingReportInvoicesInner) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ClientBillingReportInvoicesInner) SetState(v string)`

SetState sets State field to given value.


### GetTotalMinorUnits

`func (o *ClientBillingReportInvoicesInner) GetTotalMinorUnits() int32`

GetTotalMinorUnits returns the TotalMinorUnits field if non-nil, zero value otherwise.

### GetTotalMinorUnitsOk

`func (o *ClientBillingReportInvoicesInner) GetTotalMinorUnitsOk() (*int32, bool)`

GetTotalMinorUnitsOk returns a tuple with the TotalMinorUnits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMinorUnits

`func (o *ClientBillingReportInvoicesInner) SetTotalMinorUnits(v int32)`

SetTotalMinorUnits sets TotalMinorUnits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


