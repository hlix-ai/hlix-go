# ListProjectReports200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  | 
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  | 
**Projects** | [**[]ClientOverviewReportProjectsInner**](ClientOverviewReportProjectsInner.md) |  | 

## Methods

### NewListProjectReports200Response

`func NewListProjectReports200Response(generatedAt string, period AgencyBillingReportPeriod, projects []ClientOverviewReportProjectsInner, ) *ListProjectReports200Response`

NewListProjectReports200Response instantiates a new ListProjectReports200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListProjectReports200ResponseWithDefaults

`func NewListProjectReports200ResponseWithDefaults() *ListProjectReports200Response`

NewListProjectReports200ResponseWithDefaults instantiates a new ListProjectReports200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGeneratedAt

`func (o *ListProjectReports200Response) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *ListProjectReports200Response) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *ListProjectReports200Response) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *ListProjectReports200Response) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *ListProjectReports200Response) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *ListProjectReports200Response) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.


### GetProjects

`func (o *ListProjectReports200Response) GetProjects() []ClientOverviewReportProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *ListProjectReports200Response) GetProjectsOk() (*[]ClientOverviewReportProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *ListProjectReports200Response) SetProjects(v []ClientOverviewReportProjectsInner)`

SetProjects sets Projects field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


