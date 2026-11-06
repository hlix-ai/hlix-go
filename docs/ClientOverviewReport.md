# ClientOverviewReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  | 
**Invoices** | [**[]ClientBillingReportInvoicesInner**](ClientBillingReportInvoicesInner.md) |  | 
**Projects** | [**[]ClientOverviewReportProjectsInner**](ClientOverviewReportProjectsInner.md) |  | 
**RecentActivity** | [**[]ClientOverviewReportRecentActivityInner**](ClientOverviewReportRecentActivityInner.md) |  | 
**Scope** | **string** |  | 
**Summary** | [**ClientOverviewReportSummary**](ClientOverviewReportSummary.md) |  | 

## Methods

### NewClientOverviewReport

`func NewClientOverviewReport(generatedAt string, invoices []ClientBillingReportInvoicesInner, projects []ClientOverviewReportProjectsInner, recentActivity []ClientOverviewReportRecentActivityInner, scope string, summary ClientOverviewReportSummary, ) *ClientOverviewReport`

NewClientOverviewReport instantiates a new ClientOverviewReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientOverviewReportWithDefaults

`func NewClientOverviewReportWithDefaults() *ClientOverviewReport`

NewClientOverviewReportWithDefaults instantiates a new ClientOverviewReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *ClientOverviewReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *ClientOverviewReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *ClientOverviewReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetInvoices

`func (o *ClientOverviewReport) GetInvoices() []ClientBillingReportInvoicesInner`

GetInvoices returns the Invoices field if non-nil, zero value otherwise.

### GetInvoicesOk

`func (o *ClientOverviewReport) GetInvoicesOk() (*[]ClientBillingReportInvoicesInner, bool)`

GetInvoicesOk returns a tuple with the Invoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoices

`func (o *ClientOverviewReport) SetInvoices(v []ClientBillingReportInvoicesInner)`

SetInvoices sets Invoices field to given value.


### GetProjects

`func (o *ClientOverviewReport) GetProjects() []ClientOverviewReportProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *ClientOverviewReport) GetProjectsOk() (*[]ClientOverviewReportProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *ClientOverviewReport) SetProjects(v []ClientOverviewReportProjectsInner)`

SetProjects sets Projects field to given value.


### GetRecentActivity

`func (o *ClientOverviewReport) GetRecentActivity() []ClientOverviewReportRecentActivityInner`

GetRecentActivity returns the RecentActivity field if non-nil, zero value otherwise.

### GetRecentActivityOk

`func (o *ClientOverviewReport) GetRecentActivityOk() (*[]ClientOverviewReportRecentActivityInner, bool)`

GetRecentActivityOk returns a tuple with the RecentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentActivity

`func (o *ClientOverviewReport) SetRecentActivity(v []ClientOverviewReportRecentActivityInner)`

SetRecentActivity sets RecentActivity field to given value.


### GetScope

`func (o *ClientOverviewReport) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *ClientOverviewReport) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *ClientOverviewReport) SetScope(v string)`

SetScope sets Scope field to given value.


### GetSummary

`func (o *ClientOverviewReport) GetSummary() ClientOverviewReportSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ClientOverviewReport) GetSummaryOk() (*ClientOverviewReportSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ClientOverviewReport) SetSummary(v ClientOverviewReportSummary)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


