# GetOverviewReport200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attention** | [**[]AgencyOverviewReportAttentionInner**](AgencyOverviewReportAttentionInner.md) |  | 
**Billing** | [**AgencyBillingReportBilling**](AgencyBillingReportBilling.md) |  | 
**Customers** | [**[]AgencyOverviewReportCustomersInner**](AgencyOverviewReportCustomersInner.md) |  | 
**GeneratedAt** | **string** |  | 
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  | 
**Projects** | [**[]ClientOverviewReportProjectsInner**](ClientOverviewReportProjectsInner.md) |  | 
**Scope** | **string** |  | 
**Summary** | [**ClientOverviewReportSummary**](ClientOverviewReportSummary.md) |  | 
**Usage** | [**AgencyOverviewReportUsage**](AgencyOverviewReportUsage.md) |  | 
**Invoices** | [**[]ClientBillingReportInvoicesInner**](ClientBillingReportInvoicesInner.md) |  | 
**RecentActivity** | [**[]ClientOverviewReportRecentActivityInner**](ClientOverviewReportRecentActivityInner.md) |  | 

## Methods

### NewGetOverviewReport200Response

`func NewGetOverviewReport200Response(attention []AgencyOverviewReportAttentionInner, billing AgencyBillingReportBilling, customers []AgencyOverviewReportCustomersInner, generatedAt string, period AgencyBillingReportPeriod, projects []ClientOverviewReportProjectsInner, scope string, summary ClientOverviewReportSummary, usage AgencyOverviewReportUsage, invoices []ClientBillingReportInvoicesInner, recentActivity []ClientOverviewReportRecentActivityInner, ) *GetOverviewReport200Response`

NewGetOverviewReport200Response instantiates a new GetOverviewReport200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetOverviewReport200ResponseWithDefaults

`func NewGetOverviewReport200ResponseWithDefaults() *GetOverviewReport200Response`

NewGetOverviewReport200ResponseWithDefaults instantiates a new GetOverviewReport200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttention

`func (o *GetOverviewReport200Response) GetAttention() []AgencyOverviewReportAttentionInner`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *GetOverviewReport200Response) GetAttentionOk() (*[]AgencyOverviewReportAttentionInner, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *GetOverviewReport200Response) SetAttention(v []AgencyOverviewReportAttentionInner)`

SetAttention sets Attention field to given value.


### GetBilling

`func (o *GetOverviewReport200Response) GetBilling() AgencyBillingReportBilling`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *GetOverviewReport200Response) GetBillingOk() (*AgencyBillingReportBilling, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *GetOverviewReport200Response) SetBilling(v AgencyBillingReportBilling)`

SetBilling sets Billing field to given value.


### GetCustomers

`func (o *GetOverviewReport200Response) GetCustomers() []AgencyOverviewReportCustomersInner`

GetCustomers returns the Customers field if non-nil, zero value otherwise.

### GetCustomersOk

`func (o *GetOverviewReport200Response) GetCustomersOk() (*[]AgencyOverviewReportCustomersInner, bool)`

GetCustomersOk returns a tuple with the Customers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomers

`func (o *GetOverviewReport200Response) SetCustomers(v []AgencyOverviewReportCustomersInner)`

SetCustomers sets Customers field to given value.


### GetGeneratedAt

`func (o *GetOverviewReport200Response) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *GetOverviewReport200Response) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *GetOverviewReport200Response) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *GetOverviewReport200Response) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *GetOverviewReport200Response) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *GetOverviewReport200Response) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.


### GetProjects

`func (o *GetOverviewReport200Response) GetProjects() []ClientOverviewReportProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *GetOverviewReport200Response) GetProjectsOk() (*[]ClientOverviewReportProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *GetOverviewReport200Response) SetProjects(v []ClientOverviewReportProjectsInner)`

SetProjects sets Projects field to given value.


### GetScope

`func (o *GetOverviewReport200Response) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *GetOverviewReport200Response) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *GetOverviewReport200Response) SetScope(v string)`

SetScope sets Scope field to given value.


### GetSummary

`func (o *GetOverviewReport200Response) GetSummary() ClientOverviewReportSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *GetOverviewReport200Response) GetSummaryOk() (*ClientOverviewReportSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *GetOverviewReport200Response) SetSummary(v ClientOverviewReportSummary)`

SetSummary sets Summary field to given value.


### GetUsage

`func (o *GetOverviewReport200Response) GetUsage() AgencyOverviewReportUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *GetOverviewReport200Response) GetUsageOk() (*AgencyOverviewReportUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *GetOverviewReport200Response) SetUsage(v AgencyOverviewReportUsage)`

SetUsage sets Usage field to given value.


### GetInvoices

`func (o *GetOverviewReport200Response) GetInvoices() []ClientBillingReportInvoicesInner`

GetInvoices returns the Invoices field if non-nil, zero value otherwise.

### GetInvoicesOk

`func (o *GetOverviewReport200Response) GetInvoicesOk() (*[]ClientBillingReportInvoicesInner, bool)`

GetInvoicesOk returns a tuple with the Invoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoices

`func (o *GetOverviewReport200Response) SetInvoices(v []ClientBillingReportInvoicesInner)`

SetInvoices sets Invoices field to given value.


### GetRecentActivity

`func (o *GetOverviewReport200Response) GetRecentActivity() []ClientOverviewReportRecentActivityInner`

GetRecentActivity returns the RecentActivity field if non-nil, zero value otherwise.

### GetRecentActivityOk

`func (o *GetOverviewReport200Response) GetRecentActivityOk() (*[]ClientOverviewReportRecentActivityInner, bool)`

GetRecentActivityOk returns a tuple with the RecentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentActivity

`func (o *GetOverviewReport200Response) SetRecentActivity(v []ClientOverviewReportRecentActivityInner)`

SetRecentActivity sets RecentActivity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


