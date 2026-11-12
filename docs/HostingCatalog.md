# HostingCatalog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentRegion** | **string** |  |
**IdentityRegion** | **string** |  |
**Regions** | [**[]HostingCatalogRegionsInner**](HostingCatalogRegionsInner.md) |  |
**SharedLogin** | **bool** |  |

## Methods

### NewHostingCatalog

`func NewHostingCatalog(currentRegion string, identityRegion string, regions []HostingCatalogRegionsInner, sharedLogin bool, ) *HostingCatalog`

NewHostingCatalog instantiates a new HostingCatalog object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewHostingCatalogWithDefaults

`func NewHostingCatalogWithDefaults() *HostingCatalog`

NewHostingCatalogWithDefaults instantiates a new HostingCatalog object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCurrentRegion

`func (o *HostingCatalog) GetCurrentRegion() string`

GetCurrentRegion returns the CurrentRegion field if non-nil, zero value otherwise.

### GetCurrentRegionOk

`func (o *HostingCatalog) GetCurrentRegionOk() (*string, bool)`

GetCurrentRegionOk returns a tuple with the CurrentRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentRegion

`func (o *HostingCatalog) SetCurrentRegion(v string)`

SetCurrentRegion sets CurrentRegion field to given value.


### GetIdentityRegion

`func (o *HostingCatalog) GetIdentityRegion() string`

GetIdentityRegion returns the IdentityRegion field if non-nil, zero value otherwise.

### GetIdentityRegionOk

`func (o *HostingCatalog) GetIdentityRegionOk() (*string, bool)`

GetIdentityRegionOk returns a tuple with the IdentityRegion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityRegion

`func (o *HostingCatalog) SetIdentityRegion(v string)`

SetIdentityRegion sets IdentityRegion field to given value.


### GetRegions

`func (o *HostingCatalog) GetRegions() []HostingCatalogRegionsInner`

GetRegions returns the Regions field if non-nil, zero value otherwise.

### GetRegionsOk

`func (o *HostingCatalog) GetRegionsOk() (*[]HostingCatalogRegionsInner, bool)`

GetRegionsOk returns a tuple with the Regions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegions

`func (o *HostingCatalog) SetRegions(v []HostingCatalogRegionsInner)`

SetRegions sets Regions field to given value.


### GetSharedLogin

`func (o *HostingCatalog) GetSharedLogin() bool`

GetSharedLogin returns the SharedLogin field if non-nil, zero value otherwise.

### GetSharedLoginOk

`func (o *HostingCatalog) GetSharedLoginOk() (*bool, bool)`

GetSharedLoginOk returns a tuple with the SharedLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedLogin

`func (o *HostingCatalog) SetSharedLogin(v bool)`

SetSharedLogin sets SharedLogin field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


