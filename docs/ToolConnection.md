# ToolConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  |
**HasApiKey** | **bool** |  |
**OrganizationId** | **NullableString** |  |
**PlatformAvailable** | **bool** |  |
**Provider** | **string** |  |

## Methods

### NewToolConnection

`func NewToolConnection(enabled bool, hasApiKey bool, organizationId NullableString, platformAvailable bool, provider string, ) *ToolConnection`

NewToolConnection instantiates a new ToolConnection object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewToolConnectionWithDefaults

`func NewToolConnectionWithDefaults() *ToolConnection`

NewToolConnectionWithDefaults instantiates a new ToolConnection object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetEnabled

`func (o *ToolConnection) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ToolConnection) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ToolConnection) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetHasApiKey

`func (o *ToolConnection) GetHasApiKey() bool`

GetHasApiKey returns the HasApiKey field if non-nil, zero value otherwise.

### GetHasApiKeyOk

`func (o *ToolConnection) GetHasApiKeyOk() (*bool, bool)`

GetHasApiKeyOk returns a tuple with the HasApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasApiKey

`func (o *ToolConnection) SetHasApiKey(v bool)`

SetHasApiKey sets HasApiKey field to given value.


### GetOrganizationId

`func (o *ToolConnection) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ToolConnection) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ToolConnection) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### SetOrganizationIdNil

`func (o *ToolConnection) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *ToolConnection) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetPlatformAvailable

`func (o *ToolConnection) GetPlatformAvailable() bool`

GetPlatformAvailable returns the PlatformAvailable field if non-nil, zero value otherwise.

### GetPlatformAvailableOk

`func (o *ToolConnection) GetPlatformAvailableOk() (*bool, bool)`

GetPlatformAvailableOk returns a tuple with the PlatformAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformAvailable

`func (o *ToolConnection) SetPlatformAvailable(v bool)`

SetPlatformAvailable sets PlatformAvailable field to given value.


### GetProvider

`func (o *ToolConnection) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ToolConnection) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ToolConnection) SetProvider(v string)`

SetProvider sets Provider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


