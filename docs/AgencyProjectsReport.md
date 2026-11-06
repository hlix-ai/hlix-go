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
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgencyProjectsReportWithDefaults

`func NewAgencyProjectsReportWithDefaults() *AgencyProjectsReport`

NewAgencyProjectsReportWithDefaults instantiates a new AgencyProjectsReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


