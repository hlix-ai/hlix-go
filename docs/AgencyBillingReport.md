# AgencyBillingReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Billing** | [**AgencyBillingReportBilling**](AgencyBillingReportBilling.md) |  |
**GeneratedAt** | **string** |  |
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  |

## Methods

### NewAgencyBillingReport

`func NewAgencyBillingReport(billing AgencyBillingReportBilling, generatedAt string, period AgencyBillingReportPeriod, ) *AgencyBillingReport`

NewAgencyBillingReport instantiates a new AgencyBillingReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgencyBillingReportWithDefaults

`func NewAgencyBillingReportWithDefaults() *AgencyBillingReport`

NewAgencyBillingReportWithDefaults instantiates a new AgencyBillingReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBilling

`func (o *AgencyBillingReport) GetBilling() AgencyBillingReportBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *AgencyBillingReport) GetBillingOk() (*AgencyBillingReportBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *AgencyBillingReport) SetBilling(v AgencyBillingReportBilling)`

SetBilling sets Billing field to given value.


### GetGeneratedAt

`func (o *AgencyBillingReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *AgencyBillingReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *AgencyBillingReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *AgencyBillingReport) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AgencyBillingReport) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AgencyBillingReport) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


