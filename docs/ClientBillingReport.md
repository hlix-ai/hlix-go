# ClientBillingReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  |
**Invoices** | [**[]ClientBillingReportInvoicesInner**](ClientBillingReportInvoicesInner.md) |  |

## Methods

### NewClientBillingReport

`func NewClientBillingReport(generatedAt string, invoices []ClientBillingReportInvoicesInner, ) *ClientBillingReport`

NewClientBillingReport instantiates a new ClientBillingReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientBillingReportWithDefaults

`func NewClientBillingReportWithDefaults() *ClientBillingReport`

NewClientBillingReportWithDefaults instantiates a new ClientBillingReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGeneratedAt

`func (o *ClientBillingReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *ClientBillingReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *ClientBillingReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetInvoices

`func (o *ClientBillingReport) GetInvoices() []ClientBillingReportInvoicesInner`

GetInvoices returns the Invoices field if non-nil, zero value otherwise.

### GetInvoicesOk

`func (o *ClientBillingReport) GetInvoicesOk() (*[]ClientBillingReportInvoicesInner, bool)`

GetInvoicesOk returns a tuple with the Invoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoices

`func (o *ClientBillingReport) SetInvoices(v []ClientBillingReportInvoicesInner)`

SetInvoices sets Invoices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


