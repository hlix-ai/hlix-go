# GetBillingReport200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Billing** | [**AgencyBillingReportBilling**](AgencyBillingReportBilling.md) |  | 
**GeneratedAt** | **string** |  | 
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  | 
**Invoices** | [**[]ClientBillingReportInvoicesInner**](ClientBillingReportInvoicesInner.md) |  | 

## Methods

### NewGetBillingReport200Response

`func NewGetBillingReport200Response(billing AgencyBillingReportBilling, generatedAt string, period AgencyBillingReportPeriod, invoices []ClientBillingReportInvoicesInner, ) *GetBillingReport200Response`

NewGetBillingReport200Response instantiates a new GetBillingReport200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetBillingReport200ResponseWithDefaults

`func NewGetBillingReport200ResponseWithDefaults() *GetBillingReport200Response`

NewGetBillingReport200ResponseWithDefaults instantiates a new GetBillingReport200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilling

`func (o *GetBillingReport200Response) GetBilling() AgencyBillingReportBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *GetBillingReport200Response) GetBillingOk() (*AgencyBillingReportBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *GetBillingReport200Response) SetBilling(v AgencyBillingReportBilling)`

SetBilling sets Billing field to given value.


### GetGeneratedAt

`func (o *GetBillingReport200Response) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *GetBillingReport200Response) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *GetBillingReport200Response) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *GetBillingReport200Response) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *GetBillingReport200Response) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *GetBillingReport200Response) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.


### GetInvoices

`func (o *GetBillingReport200Response) GetInvoices() []ClientBillingReportInvoicesInner`

GetInvoices returns the Invoices field if non-nil, zero value otherwise.

### GetInvoicesOk

`func (o *GetBillingReport200Response) GetInvoicesOk() (*[]ClientBillingReportInvoicesInner, bool)`

GetInvoicesOk returns a tuple with the Invoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoices

`func (o *GetBillingReport200Response) SetInvoices(v []ClientBillingReportInvoicesInner)`

SetInvoices sets Invoices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


