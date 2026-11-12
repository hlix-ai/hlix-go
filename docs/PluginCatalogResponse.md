# PluginCatalogResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NextCursor** | Pointer to **string** |  | [optional]
**Servers** | [**[]PluginCatalogDetailResponseServer**](PluginCatalogDetailResponseServer.md) |  |
**Warnings** | Pointer to **[]string** |  | [optional]

## Methods

### NewPluginCatalogResponse

`func NewPluginCatalogResponse(servers []PluginCatalogDetailResponseServer, ) *PluginCatalogResponse`

NewPluginCatalogResponse instantiates a new PluginCatalogResponse object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPluginCatalogResponseWithDefaults

`func NewPluginCatalogResponseWithDefaults() *PluginCatalogResponse`

NewPluginCatalogResponseWithDefaults instantiates a new PluginCatalogResponse object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetNextCursor

`func (o *PluginCatalogResponse) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *PluginCatalogResponse) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *PluginCatalogResponse) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *PluginCatalogResponse) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.

### GetServers

`func (o *PluginCatalogResponse) GetServers() []PluginCatalogDetailResponseServer`

GetServers returns the Servers field if non-nil, zero value otherwise.

### GetServersOk

`func (o *PluginCatalogResponse) GetServersOk() (*[]PluginCatalogDetailResponseServer, bool)`

GetServersOk returns a tuple with the Servers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServers

`func (o *PluginCatalogResponse) SetServers(v []PluginCatalogDetailResponseServer)`

SetServers sets Servers field to given value.


### GetWarnings

`func (o *PluginCatalogResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PluginCatalogResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PluginCatalogResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *PluginCatalogResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


