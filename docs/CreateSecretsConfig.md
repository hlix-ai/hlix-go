# CreateSecretsConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | **map[string]interface{}** |  | 
**EnvFilter** | Pointer to **string** |  | [optional] 
**Label** | **string** |  | 
**Provider** | **string** |  | 

## Methods

### NewCreateSecretsConfig

`func NewCreateSecretsConfig(config map[string]interface{}, label string, provider string, ) *CreateSecretsConfig`

NewCreateSecretsConfig instantiates a new CreateSecretsConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSecretsConfigWithDefaults

`func NewCreateSecretsConfigWithDefaults() *CreateSecretsConfig`

NewCreateSecretsConfigWithDefaults instantiates a new CreateSecretsConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *CreateSecretsConfig) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateSecretsConfig) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateSecretsConfig) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.


### GetEnvFilter

`func (o *CreateSecretsConfig) GetEnvFilter() string`

GetEnvFilter returns the EnvFilter field if non-nil, zero value otherwise.

### GetEnvFilterOk

`func (o *CreateSecretsConfig) GetEnvFilterOk() (*string, bool)`

GetEnvFilterOk returns a tuple with the EnvFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvFilter

`func (o *CreateSecretsConfig) SetEnvFilter(v string)`

SetEnvFilter sets EnvFilter field to given value.

### HasEnvFilter

`func (o *CreateSecretsConfig) HasEnvFilter() bool`

HasEnvFilter returns a boolean if a field has been set.

### GetLabel

`func (o *CreateSecretsConfig) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateSecretsConfig) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateSecretsConfig) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetProvider

`func (o *CreateSecretsConfig) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateSecretsConfig) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateSecretsConfig) SetProvider(v string)`

SetProvider sets Provider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


