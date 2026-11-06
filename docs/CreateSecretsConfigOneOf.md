# CreateSecretsConfigOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | [**CreateSecretsConfigOneOfConfig**](CreateSecretsConfigOneOfConfig.md) |  | 
**EnvFilter** | Pointer to **string** |  | [optional] 
**Label** | **string** |  | 
**Provider** | **string** |  | 

## Methods

### NewCreateSecretsConfigOneOf

`func NewCreateSecretsConfigOneOf(config CreateSecretsConfigOneOfConfig, label string, provider string, ) *CreateSecretsConfigOneOf`

NewCreateSecretsConfigOneOf instantiates a new CreateSecretsConfigOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateSecretsConfigOneOfWithDefaults

`func NewCreateSecretsConfigOneOfWithDefaults() *CreateSecretsConfigOneOf`

NewCreateSecretsConfigOneOfWithDefaults instantiates a new CreateSecretsConfigOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *CreateSecretsConfigOneOf) GetConfig() CreateSecretsConfigOneOfConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateSecretsConfigOneOf) GetConfigOk() (*CreateSecretsConfigOneOfConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateSecretsConfigOneOf) SetConfig(v CreateSecretsConfigOneOfConfig)`

SetConfig sets Config field to given value.


### GetEnvFilter

`func (o *CreateSecretsConfigOneOf) GetEnvFilter() string`

GetEnvFilter returns the EnvFilter field if non-nil, zero value otherwise.

### GetEnvFilterOk

`func (o *CreateSecretsConfigOneOf) GetEnvFilterOk() (*string, bool)`

GetEnvFilterOk returns a tuple with the EnvFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvFilter

`func (o *CreateSecretsConfigOneOf) SetEnvFilter(v string)`

SetEnvFilter sets EnvFilter field to given value.

### HasEnvFilter

`func (o *CreateSecretsConfigOneOf) HasEnvFilter() bool`

HasEnvFilter returns a boolean if a field has been set.

### GetLabel

`func (o *CreateSecretsConfigOneOf) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateSecretsConfigOneOf) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateSecretsConfigOneOf) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetProvider

`func (o *CreateSecretsConfigOneOf) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateSecretsConfigOneOf) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateSecretsConfigOneOf) SetProvider(v string)`

SetProvider sets Provider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


