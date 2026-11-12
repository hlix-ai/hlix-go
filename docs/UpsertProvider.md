# UpsertProvider

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | Pointer to **NullableString** |  | [optional]
**BaseUrl** | Pointer to **NullableString** |  | [optional]
**Enabled** | Pointer to **bool** |  | [optional]
**Metadata** | Pointer to **map[string]interface{}** |  | [optional]
**Provider** | **string** |  |

## Methods

### NewUpsertProvider

`func NewUpsertProvider(provider string, ) *UpsertProvider`

NewUpsertProvider instantiates a new UpsertProvider object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpsertProviderWithDefaults

`func NewUpsertProviderWithDefaults() *UpsertProvider`

NewUpsertProviderWithDefaults instantiates a new UpsertProvider object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApiKey

`func (o *UpsertProvider) GetApiKey() string`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *UpsertProvider) GetApiKeyOk() (*string, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *UpsertProvider) SetApiKey(v string)`

SetApiKey sets ApiKey field to given value.

### HasApiKey

`func (o *UpsertProvider) HasApiKey() bool`

HasApiKey returns a boolean if a field has been set.

### SetApiKeyNil

`func (o *UpsertProvider) SetApiKeyNil(b bool)`

 SetApiKeyNil sets the value for ApiKey to be an explicit nil

### UnsetApiKey
`func (o *UpsertProvider) UnsetApiKey()`

UnsetApiKey ensures that no value is present for ApiKey, not even an explicit nil
### GetBaseUrl

`func (o *UpsertProvider) GetBaseUrl() string`

GetBaseUrl returns the BaseUrl field if non-nil, zero value otherwise.

### GetBaseUrlOk

`func (o *UpsertProvider) GetBaseUrlOk() (*string, bool)`

GetBaseUrlOk returns a tuple with the BaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseUrl

`func (o *UpsertProvider) SetBaseUrl(v string)`

SetBaseUrl sets BaseUrl field to given value.

### HasBaseUrl

`func (o *UpsertProvider) HasBaseUrl() bool`

HasBaseUrl returns a boolean if a field has been set.

### SetBaseUrlNil

`func (o *UpsertProvider) SetBaseUrlNil(b bool)`

 SetBaseUrlNil sets the value for BaseUrl to be an explicit nil

### UnsetBaseUrl
`func (o *UpsertProvider) UnsetBaseUrl()`

UnsetBaseUrl ensures that no value is present for BaseUrl, not even an explicit nil
### GetEnabled

`func (o *UpsertProvider) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *UpsertProvider) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *UpsertProvider) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *UpsertProvider) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetMetadata

`func (o *UpsertProvider) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *UpsertProvider) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *UpsertProvider) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *UpsertProvider) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *UpsertProvider) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *UpsertProvider) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetProvider

`func (o *UpsertProvider) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *UpsertProvider) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *UpsertProvider) SetProvider(v string)`

SetProvider sets Provider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


