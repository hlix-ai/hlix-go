# AlertSettingsSlack

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Route** | [**NullableAlertSettingsSlackRoute**](AlertSettingsSlackRoute.md) |  |
**Workspaces** | [**[]AlertSettingsSlackWorkspacesInner**](AlertSettingsSlackWorkspacesInner.md) |  |

## Methods

### NewAlertSettingsSlack

`func NewAlertSettingsSlack(route NullableAlertSettingsSlackRoute, workspaces []AlertSettingsSlackWorkspacesInner, ) *AlertSettingsSlack`

NewAlertSettingsSlack instantiates a new AlertSettingsSlack object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAlertSettingsSlackWithDefaults

`func NewAlertSettingsSlackWithDefaults() *AlertSettingsSlack`

NewAlertSettingsSlackWithDefaults instantiates a new AlertSettingsSlack object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetRoute

`func (o *AlertSettingsSlack) GetRoute() AlertSettingsSlackRoute`

GetRoute returns the Route field if non-nil, zero value otherwise.

### GetRouteOk

`func (o *AlertSettingsSlack) GetRouteOk() (*AlertSettingsSlackRoute, bool)`

GetRouteOk returns a tuple with the Route field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoute

`func (o *AlertSettingsSlack) SetRoute(v AlertSettingsSlackRoute)`

SetRoute sets Route field to given value.


### SetRouteNil

`func (o *AlertSettingsSlack) SetRouteNil(b bool)`

 SetRouteNil sets the value for Route to be an explicit nil

### UnsetRoute
`func (o *AlertSettingsSlack) UnsetRoute()`

UnsetRoute ensures that no value is present for Route, not even an explicit nil
### GetWorkspaces

`func (o *AlertSettingsSlack) GetWorkspaces() []AlertSettingsSlackWorkspacesInner`

GetWorkspaces returns the Workspaces field if non-nil, zero value otherwise.

### GetWorkspacesOk

`func (o *AlertSettingsSlack) GetWorkspacesOk() (*[]AlertSettingsSlackWorkspacesInner, bool)`

GetWorkspacesOk returns a tuple with the Workspaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaces

`func (o *AlertSettingsSlack) SetWorkspaces(v []AlertSettingsSlackWorkspacesInner)`

SetWorkspaces sets Workspaces field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


