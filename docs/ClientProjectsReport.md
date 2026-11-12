# ClientProjectsReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  |
**Projects** | [**[]ClientOverviewReportProjectsInner**](ClientOverviewReportProjectsInner.md) |  |

## Methods

### NewClientProjectsReport

`func NewClientProjectsReport(generatedAt string, projects []ClientOverviewReportProjectsInner, ) *ClientProjectsReport`

NewClientProjectsReport instantiates a new ClientProjectsReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientProjectsReportWithDefaults

`func NewClientProjectsReportWithDefaults() *ClientProjectsReport`

NewClientProjectsReportWithDefaults instantiates a new ClientProjectsReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGeneratedAt

`func (o *ClientProjectsReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *ClientProjectsReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *ClientProjectsReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetProjects

`func (o *ClientProjectsReport) GetProjects() []ClientOverviewReportProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *ClientProjectsReport) GetProjectsOk() (*[]ClientOverviewReportProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *ClientProjectsReport) SetProjects(v []ClientOverviewReportProjectsInner)`

SetProjects sets Projects field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


