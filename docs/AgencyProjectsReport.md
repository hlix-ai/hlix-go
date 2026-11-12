# AgencyProjectsReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  |
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  |
**Projects** | [**[]AgencyOverviewReportProjectsInner**](AgencyOverviewReportProjectsInner.md) |  |

## Methods

### NewAgencyProjectsReport

`func NewAgencyProjectsReport(generatedAt string, period AgencyBillingReportPeriod, projects []AgencyOverviewReportProjectsInner, ) *AgencyProjectsReport`

NewAgencyProjectsReport instantiates a new AgencyProjectsReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgencyProjectsReportWithDefaults

`func NewAgencyProjectsReportWithDefaults() *AgencyProjectsReport`

NewAgencyProjectsReportWithDefaults instantiates a new AgencyProjectsReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGeneratedAt

`func (o *AgencyProjectsReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *AgencyProjectsReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *AgencyProjectsReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *AgencyProjectsReport) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AgencyProjectsReport) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AgencyProjectsReport) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.


### GetProjects

`func (o *AgencyProjectsReport) GetProjects() []AgencyOverviewReportProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *AgencyProjectsReport) GetProjectsOk() (*[]AgencyOverviewReportProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *AgencyProjectsReport) SetProjects(v []AgencyOverviewReportProjectsInner)`

SetProjects sets Projects field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


