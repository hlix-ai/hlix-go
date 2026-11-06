# ClientPortalOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Projects** | [**[]ClientPortalOverviewProjectsInner**](ClientPortalOverviewProjectsInner.md) |  | 
**RecentActivity** | [**[]ClientOverviewReportRecentActivityInner**](ClientOverviewReportRecentActivityInner.md) |  | 

## Methods

### NewClientPortalOverview

`func NewClientPortalOverview(projects []ClientPortalOverviewProjectsInner, recentActivity []ClientOverviewReportRecentActivityInner, ) *ClientPortalOverview`

NewClientPortalOverview instantiates a new ClientPortalOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientPortalOverviewWithDefaults

`func NewClientPortalOverviewWithDefaults() *ClientPortalOverview`

NewClientPortalOverviewWithDefaults instantiates a new ClientPortalOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProjects

`func (o *ClientPortalOverview) GetProjects() []ClientPortalOverviewProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *ClientPortalOverview) GetProjectsOk() (*[]ClientPortalOverviewProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *ClientPortalOverview) SetProjects(v []ClientPortalOverviewProjectsInner)`

SetProjects sets Projects field to given value.


### GetRecentActivity

`func (o *ClientPortalOverview) GetRecentActivity() []ClientOverviewReportRecentActivityInner`

GetRecentActivity returns the RecentActivity field if non-nil, zero value otherwise.

### GetRecentActivityOk

`func (o *ClientPortalOverview) GetRecentActivityOk() (*[]ClientOverviewReportRecentActivityInner, bool)`

GetRecentActivityOk returns a tuple with the RecentActivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentActivity

`func (o *ClientPortalOverview) SetRecentActivity(v []ClientOverviewReportRecentActivityInner)`

SetRecentActivity sets RecentActivity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


