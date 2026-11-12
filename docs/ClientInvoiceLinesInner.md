# ClientInvoiceLinesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AmountMicros** | **int64** |  |
**BillableId** | **string** |  |
**CreatedAt** | **string** |  |
**Description** | **string** |  |
**Id** | **string** |  |
**InvoiceId** | **string** |  |
**OrganizationId** | **string** |  |
**Position** | **float32** |  |
**Quantity** | **string** |  |
**TaxClass** | **string** |  |
**TaxMicros** | **int64** |  |
**TaxRateBps** | **float32** |  |
**Unit** | **string** |  |
**UnitPriceMicros** | **int64** |  |

## Methods

### NewClientInvoiceLinesInner

`func NewClientInvoiceLinesInner(amountMicros int64, billableId string, createdAt string, description string, id string, invoiceId string, organizationId string, position float32, quantity string, taxClass string, taxMicros int64, taxRateBps float32, unit string, unitPriceMicros int64, ) *ClientInvoiceLinesInner`

NewClientInvoiceLinesInner instantiates a new ClientInvoiceLinesInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientInvoiceLinesInnerWithDefaults

`func NewClientInvoiceLinesInnerWithDefaults() *ClientInvoiceLinesInner`

NewClientInvoiceLinesInnerWithDefaults instantiates a new ClientInvoiceLinesInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAmountMicros

`func (o *ClientInvoiceLinesInner) GetAmountMicros() int64`

GetAmountMicros returns the AmountMicros field if non-nil, zero value otherwise.

### GetAmountMicrosOk

`func (o *ClientInvoiceLinesInner) GetAmountMicrosOk() (*int64, bool)`

GetAmountMicrosOk returns a tuple with the AmountMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountMicros

`func (o *ClientInvoiceLinesInner) SetAmountMicros(v int64)`

SetAmountMicros sets AmountMicros field to given value.


### GetBillableId

`func (o *ClientInvoiceLinesInner) GetBillableId() string`

GetBillableId returns the BillableId field if non-nil, zero value otherwise.

### GetBillableIdOk

`func (o *ClientInvoiceLinesInner) GetBillableIdOk() (*string, bool)`

GetBillableIdOk returns a tuple with the BillableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillableId

`func (o *ClientInvoiceLinesInner) SetBillableId(v string)`

SetBillableId sets BillableId field to given value.


### GetCreatedAt

`func (o *ClientInvoiceLinesInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientInvoiceLinesInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientInvoiceLinesInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *ClientInvoiceLinesInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ClientInvoiceLinesInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ClientInvoiceLinesInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *ClientInvoiceLinesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientInvoiceLinesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientInvoiceLinesInner) SetId(v string)`

SetId sets Id field to given value.


### GetInvoiceId

`func (o *ClientInvoiceLinesInner) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *ClientInvoiceLinesInner) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *ClientInvoiceLinesInner) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.


### GetOrganizationId

`func (o *ClientInvoiceLinesInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ClientInvoiceLinesInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ClientInvoiceLinesInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPosition

`func (o *ClientInvoiceLinesInner) GetPosition() float32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *ClientInvoiceLinesInner) GetPositionOk() (*float32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *ClientInvoiceLinesInner) SetPosition(v float32)`

SetPosition sets Position field to given value.


### GetQuantity

`func (o *ClientInvoiceLinesInner) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ClientInvoiceLinesInner) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ClientInvoiceLinesInner) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetTaxClass

`func (o *ClientInvoiceLinesInner) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *ClientInvoiceLinesInner) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *ClientInvoiceLinesInner) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.


### GetTaxMicros

`func (o *ClientInvoiceLinesInner) GetTaxMicros() int64`

GetTaxMicros returns the TaxMicros field if non-nil, zero value otherwise.

### GetTaxMicrosOk

`func (o *ClientInvoiceLinesInner) GetTaxMicrosOk() (*int64, bool)`

GetTaxMicrosOk returns a tuple with the TaxMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxMicros

`func (o *ClientInvoiceLinesInner) SetTaxMicros(v int64)`

SetTaxMicros sets TaxMicros field to given value.


### GetTaxRateBps

`func (o *ClientInvoiceLinesInner) GetTaxRateBps() float32`

GetTaxRateBps returns the TaxRateBps field if non-nil, zero value otherwise.

### GetTaxRateBpsOk

`func (o *ClientInvoiceLinesInner) GetTaxRateBpsOk() (*float32, bool)`

GetTaxRateBpsOk returns a tuple with the TaxRateBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxRateBps

`func (o *ClientInvoiceLinesInner) SetTaxRateBps(v float32)`

SetTaxRateBps sets TaxRateBps field to given value.


### GetUnit

`func (o *ClientInvoiceLinesInner) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ClientInvoiceLinesInner) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ClientInvoiceLinesInner) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *ClientInvoiceLinesInner) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *ClientInvoiceLinesInner) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *ClientInvoiceLinesInner) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


