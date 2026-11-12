# CustomersReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Customers** | [**[]AgencyOverviewReportCustomersInner**](AgencyOverviewReportCustomersInner.md) |  |
**GeneratedAt** | **string** |  |
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  |

## Methods

### NewCustomersReport

`func NewCustomersReport(customers []AgencyOverviewReportCustomersInner, generatedAt string, period AgencyBillingReportPeriod, ) *CustomersReport`

NewCustomersReport instantiates a new CustomersReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCustomersReportWithDefaults

`func NewCustomersReportWithDefaults() *CustomersReport`

NewCustomersReportWithDefaults instantiates a new CustomersReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCustomers

`func (o *CustomersReport) GetCustomers() []AgencyOverviewReportCustomersInner`

GetCustomers returns the Customers field if non-nil, zero value otherwise.

### GetCustomersOk

`func (o *CustomersReport) GetCustomersOk() (*[]AgencyOverviewReportCustomersInner, bool)`

GetCustomersOk returns a tuple with the Customers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomers

`func (o *CustomersReport) SetCustomers(v []AgencyOverviewReportCustomersInner)`

SetCustomers sets Customers field to given value.


### GetGeneratedAt

`func (o *CustomersReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *CustomersReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *CustomersReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *CustomersReport) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *CustomersReport) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *CustomersReport) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


