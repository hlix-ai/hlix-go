# WorkspaceHosting

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanCreateWorkspace** | **bool** |  |
**CurrentRegion** | **string** |  |
**HostingRegion** | **string** |  |
**IdentityRegion** | **string** |  |
**Regions** | [**[]HostingCatalogRegionsInner**](HostingCatalogRegionsInner.md) |  |
**SharedLogin** | **bool** |  |

## Methods

### NewWorkspaceHosting

`func NewWorkspaceHosting(canCreateWorkspace bool, currentRegion string, hostingRegion string, identityRegion string, regions []HostingCatalogRegionsInner, sharedLogin bool, ) *WorkspaceHosting`

NewWorkspaceHosting instantiates a new WorkspaceHosting object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewWorkspaceHostingWithDefaults

`func NewWorkspaceHostingWithDefaults() *WorkspaceHosting`

NewWorkspaceHostingWithDefaults instantiates a new WorkspaceHosting object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCanCreateWorkspace

`func (o *WorkspaceHosting) GetCanCreateWorkspace() bool`

GetCanCreateWorkspace returns the CanCreateWorkspace field if non-nil, zero value otherwise.

### GetCanCreateWorkspaceOk

`func (o *WorkspaceHosting) GetCanCreateWorkspaceOk() (*bool, bool)`

GetCanCreateWorkspaceOk returns a tuple with the CanCreateWorkspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanCreateWorkspace

`func (o *WorkspaceHosting) SetCanCreateWorkspace(v bool)`

SetCanCreateWorkspace sets CanCreateWorkspace field to given value.


### GetCurrentRegion

`func (o *WorkspaceHosting) GetCurrentRegion() string`

GetCurrentRegion returns the CurrentRegion field if non-nil, zero value otherwise.

### GetCurrentRegionOk

`func (o *WorkspaceHosting) GetCurrentRegionOk() (*string, bool)`

GetCurrentRegionOk returns a tuple with the CurrentRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentRegion

`func (o *WorkspaceHosting) SetCurrentRegion(v string)`

SetCurrentRegion sets CurrentRegion field to given value.


### GetHostingRegion

`func (o *WorkspaceHosting) GetHostingRegion() string`

GetHostingRegion returns the HostingRegion field if non-nil, zero value otherwise.

### GetHostingRegionOk

`func (o *WorkspaceHosting) GetHostingRegionOk() (*string, bool)`

GetHostingRegionOk returns a tuple with the HostingRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostingRegion

`func (o *WorkspaceHosting) SetHostingRegion(v string)`

SetHostingRegion sets HostingRegion field to given value.


### GetIdentityRegion

`func (o *WorkspaceHosting) GetIdentityRegion() string`

GetIdentityRegion returns the IdentityRegion field if non-nil, zero value otherwise.

### GetIdentityRegionOk

`func (o *WorkspaceHosting) GetIdentityRegionOk() (*string, bool)`

GetIdentityRegionOk returns a tuple with the IdentityRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityRegion

`func (o *WorkspaceHosting) SetIdentityRegion(v string)`

SetIdentityRegion sets IdentityRegion field to given value.


### GetRegions

`func (o *WorkspaceHosting) GetRegions() []HostingCatalogRegionsInner`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *WorkspaceHosting) GetRegionsOk() (*[]HostingCatalogRegionsInner, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *WorkspaceHosting) SetRegions(v []HostingCatalogRegionsInner)`

SetRegions sets Regions field to given value.


### GetSharedLogin

`func (o *WorkspaceHosting) GetSharedLogin() bool`

GetSharedLogin returns the SharedLogin field if non-nil, zero value otherwise.

### GetSharedLoginOk

`func (o *WorkspaceHosting) GetSharedLoginOk() (*bool, bool)`

GetSharedLoginOk returns a tuple with the SharedLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedLogin

`func (o *WorkspaceHosting) SetSharedLogin(v bool)`

SetSharedLogin sets SharedLogin field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


