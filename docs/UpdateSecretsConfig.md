# UpdateSecretsConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to **map[string]interface{}** | For an Infisical config, the fields to change (clientId, clientSecret, projectId, environment, siteUrl, secretPath, recursive); a field left out keeps its stored value. For a manual config, the whole config. | [optional] 
**EnvFilter** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 

## Methods

### NewUpdateSecretsConfig

`func NewUpdateSecretsConfig() *UpdateSecretsConfig`

NewUpdateSecretsConfig instantiates a new UpdateSecretsConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateSecretsConfigWithDefaults

`func NewUpdateSecretsConfigWithDefaults() *UpdateSecretsConfig`

NewUpdateSecretsConfigWithDefaults instantiates a new UpdateSecretsConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *UpdateSecretsConfig) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UpdateSecretsConfig) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UpdateSecretsConfig) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.

### HasConfig

`func (o *UpdateSecretsConfig) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetEnvFilter

`func (o *UpdateSecretsConfig) GetEnvFilter() string`

GetEnvFilter returns the EnvFilter field if non-nil, zero value otherwise.

### GetEnvFilterOk

`func (o *UpdateSecretsConfig) GetEnvFilterOk() (*string, bool)`

GetEnvFilterOk returns a tuple with the EnvFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvFilter

`func (o *UpdateSecretsConfig) SetEnvFilter(v string)`

SetEnvFilter sets EnvFilter field to given value.

### HasEnvFilter

`func (o *UpdateSecretsConfig) HasEnvFilter() bool`

HasEnvFilter returns a boolean if a field has been set.

### SetEnvFilterNil

`func (o *UpdateSecretsConfig) SetEnvFilterNil(b bool)`

 SetEnvFilterNil sets the value for EnvFilter to be an explicit nil

### UnsetEnvFilter
`func (o *UpdateSecretsConfig) UnsetEnvFilter()`

UnsetEnvFilter ensures that no value is present for EnvFilter, not even an explicit nil
### GetIsActive

`func (o *UpdateSecretsConfig) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateSecretsConfig) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateSecretsConfig) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateSecretsConfig) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetLabel

`func (o *UpdateSecretsConfig) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *UpdateSecretsConfig) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *UpdateSecretsConfig) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *UpdateSecretsConfig) HasLabel() bool`

HasLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


