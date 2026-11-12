# AgencyOverviewReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attention** | [**[]AgencyOverviewReportAttentionInner**](AgencyOverviewReportAttentionInner.md) |  |
**Billing** | [**AgencyBillingReportBilling**](AgencyBillingReportBilling.md) |  |
**Customers** | [**[]AgencyOverviewReportCustomersInner**](AgencyOverviewReportCustomersInner.md) |  |
**GeneratedAt** | **string** |  |
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  |
**Projects** | [**[]AgencyOverviewReportProjectsInner**](AgencyOverviewReportProjectsInner.md) |  |
**Scope** | **string** |  |
**Summary** | [**AgencyOverviewReportSummary**](AgencyOverviewReportSummary.md) |  |
**Usage** | [**AgencyOverviewReportUsage**](AgencyOverviewReportUsage.md) |  |

## Methods

### NewAgencyOverviewReport

`func NewAgencyOverviewReport(attention []AgencyOverviewReportAttentionInner, billing AgencyBillingReportBilling, customers []AgencyOverviewReportCustomersInner, generatedAt string, period AgencyBillingReportPeriod, projects []AgencyOverviewReportProjectsInner, scope string, summary AgencyOverviewReportSummary, usage AgencyOverviewReportUsage, ) *AgencyOverviewReport`

NewAgencyOverviewReport instantiates a new AgencyOverviewReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgencyOverviewReportWithDefaults

`func NewAgencyOverviewReportWithDefaults() *AgencyOverviewReport`

NewAgencyOverviewReportWithDefaults instantiates a new AgencyOverviewReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAttention

`func (o *AgencyOverviewReport) GetAttention() []AgencyOverviewReportAttentionInner`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *AgencyOverviewReport) GetAttentionOk() (*[]AgencyOverviewReportAttentionInner, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *AgencyOverviewReport) SetAttention(v []AgencyOverviewReportAttentionInner)`

SetAttention sets Attention field to given value.


### GetBilling

`func (o *AgencyOverviewReport) GetBilling() AgencyBillingReportBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *AgencyOverviewReport) GetBillingOk() (*AgencyBillingReportBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *AgencyOverviewReport) SetBilling(v AgencyBillingReportBilling)`

SetBilling sets Billing field to given value.


### GetCustomers

`func (o *AgencyOverviewReport) GetCustomers() []AgencyOverviewReportCustomersInner`

GetCustomers returns the Customers field if non-nil, zero value otherwise.

### GetCustomersOk

`func (o *AgencyOverviewReport) GetCustomersOk() (*[]AgencyOverviewReportCustomersInner, bool)`

GetCustomersOk returns a tuple with the Customers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomers

`func (o *AgencyOverviewReport) SetCustomers(v []AgencyOverviewReportCustomersInner)`

SetCustomers sets Customers field to given value.


### GetGeneratedAt

`func (o *AgencyOverviewReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *AgencyOverviewReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *AgencyOverviewReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *AgencyOverviewReport) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AgencyOverviewReport) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AgencyOverviewReport) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.


### GetProjects

`func (o *AgencyOverviewReport) GetProjects() []AgencyOverviewReportProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *AgencyOverviewReport) GetProjectsOk() (*[]AgencyOverviewReportProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *AgencyOverviewReport) SetProjects(v []AgencyOverviewReportProjectsInner)`

SetProjects sets Projects field to given value.


### GetScope

`func (o *AgencyOverviewReport) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *AgencyOverviewReport) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *AgencyOverviewReport) SetScope(v string)`

SetScope sets Scope field to given value.


### GetSummary

`func (o *AgencyOverviewReport) GetSummary() AgencyOverviewReportSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *AgencyOverviewReport) GetSummaryOk() (*AgencyOverviewReportSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *AgencyOverviewReport) SetSummary(v AgencyOverviewReportSummary)`

SetSummary sets Summary field to given value.


### GetUsage

`func (o *AgencyOverviewReport) GetUsage() AgencyOverviewReportUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AgencyOverviewReport) GetUsageOk() (*AgencyOverviewReportUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AgencyOverviewReport) SetUsage(v AgencyOverviewReportUsage)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


