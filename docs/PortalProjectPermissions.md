# PortalProjectPermissions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanAccessCanvas** | Pointer to **bool** |  | [optional]
**CanMessage** | **bool** |  |
**ShowProjectInsights** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewPortalProjectPermissions

`func NewPortalProjectPermissions(canMessage bool, ) *PortalProjectPermissions`

NewPortalProjectPermissions instantiates a new PortalProjectPermissions object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPortalProjectPermissionsWithDefaults

`func NewPortalProjectPermissionsWithDefaults() *PortalProjectPermissions`

NewPortalProjectPermissionsWithDefaults instantiates a new PortalProjectPermissions object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCanAccessCanvas

`func (o *PortalProjectPermissions) GetCanAccessCanvas() bool`

GetCanAccessCanvas returns the CanAccessCanvas field if non-nil, zero value otherwise.

### GetCanAccessCanvasOk

`func (o *PortalProjectPermissions) GetCanAccessCanvasOk() (*bool, bool)`

GetCanAccessCanvasOk returns a tuple with the CanAccessCanvas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanAccessCanvas

`func (o *PortalProjectPermissions) SetCanAccessCanvas(v bool)`

SetCanAccessCanvas sets CanAccessCanvas field to given value.

### HasCanAccessCanvas

`func (o *PortalProjectPermissions) HasCanAccessCanvas() bool`

HasCanAccessCanvas returns a boolean if a field has been set.

### GetCanMessage

`func (o *PortalProjectPermissions) GetCanMessage() bool`

GetCanMessage returns the CanMessage field if non-nil, zero value otherwise.

### GetCanMessageOk

`func (o *PortalProjectPermissions) GetCanMessageOk() (*bool, bool)`

GetCanMessageOk returns a tuple with the CanMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanMessage

`func (o *PortalProjectPermissions) SetCanMessage(v bool)`

SetCanMessage sets CanMessage field to given value.


### GetShowProjectInsights

`func (o *PortalProjectPermissions) GetShowProjectInsights() bool`

GetShowProjectInsights returns the ShowProjectInsights field if non-nil, zero value otherwise.

### GetShowProjectInsightsOk

`func (o *PortalProjectPermissions) GetShowProjectInsightsOk() (*bool, bool)`

GetShowProjectInsightsOk returns a tuple with the ShowProjectInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowProjectInsights

`func (o *PortalProjectPermissions) SetShowProjectInsights(v bool)`

SetShowProjectInsights sets ShowProjectInsights field to given value.

### HasShowProjectInsights

`func (o *PortalProjectPermissions) HasShowProjectInsights() bool`

HasShowProjectInsights returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


