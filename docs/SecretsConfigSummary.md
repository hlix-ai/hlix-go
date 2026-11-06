# SecretsConfigSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConfigSummary** | **map[string]interface{}** |  | 
**CreatedAt** | **string** |  | 
**EnvFilter** | **NullableString** |  | 
**Id** | **string** |  | 
**IsActive** | **bool** |  | 
**Label** | **string** |  | 
**OrganizationId** | **string** |  | 
**ProjectId** | **string** |  | 
**Provider** | **string** |  | 
**Remote** | [**NullableSecretsConfigSummaryRemote**](SecretsConfigSummaryRemote.md) |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewSecretsConfigSummary

`func NewSecretsConfigSummary(configSummary map[string]interface{}, createdAt string, envFilter NullableString, id string, isActive bool, label string, organizationId string, projectId string, provider string, remote NullableSecretsConfigSummaryRemote, updatedAt string, ) *SecretsConfigSummary`

NewSecretsConfigSummary instantiates a new SecretsConfigSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecretsConfigSummaryWithDefaults

`func NewSecretsConfigSummaryWithDefaults() *SecretsConfigSummary`

NewSecretsConfigSummaryWithDefaults instantiates a new SecretsConfigSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigSummary

`func (o *SecretsConfigSummary) GetConfigSummary() map[string]interface{}`

GetConfigSummary returns the ConfigSummary field if non-nil, zero value otherwise.

### GetConfigSummaryOk

`func (o *SecretsConfigSummary) GetConfigSummaryOk() (*map[string]interface{}, bool)`

GetConfigSummaryOk returns a tuple with the ConfigSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigSummary

`func (o *SecretsConfigSummary) SetConfigSummary(v map[string]interface{})`

SetConfigSummary sets ConfigSummary field to given value.


### GetCreatedAt

`func (o *SecretsConfigSummary) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SecretsConfigSummary) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SecretsConfigSummary) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEnvFilter

`func (o *SecretsConfigSummary) GetEnvFilter() string`

GetEnvFilter returns the EnvFilter field if non-nil, zero value otherwise.

### GetEnvFilterOk

`func (o *SecretsConfigSummary) GetEnvFilterOk() (*string, bool)`

GetEnvFilterOk returns a tuple with the EnvFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvFilter

`func (o *SecretsConfigSummary) SetEnvFilter(v string)`

SetEnvFilter sets EnvFilter field to given value.


### SetEnvFilterNil

`func (o *SecretsConfigSummary) SetEnvFilterNil(b bool)`

 SetEnvFilterNil sets the value for EnvFilter to be an explicit nil

### UnsetEnvFilter
`func (o *SecretsConfigSummary) UnsetEnvFilter()`

UnsetEnvFilter ensures that no value is present for EnvFilter, not even an explicit nil
### GetId

`func (o *SecretsConfigSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SecretsConfigSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SecretsConfigSummary) SetId(v string)`

SetId sets Id field to given value.


### GetIsActive

`func (o *SecretsConfigSummary) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *SecretsConfigSummary) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *SecretsConfigSummary) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetLabel

`func (o *SecretsConfigSummary) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *SecretsConfigSummary) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *SecretsConfigSummary) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetOrganizationId

`func (o *SecretsConfigSummary) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *SecretsConfigSummary) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *SecretsConfigSummary) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *SecretsConfigSummary) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SecretsConfigSummary) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SecretsConfigSummary) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProvider

`func (o *SecretsConfigSummary) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *SecretsConfigSummary) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *SecretsConfigSummary) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetRemote

`func (o *SecretsConfigSummary) GetRemote() SecretsConfigSummaryRemote`

GetRemote returns the Remote field if non-nil, zero value otherwise.

### GetRemoteOk

`func (o *SecretsConfigSummary) GetRemoteOk() (*SecretsConfigSummaryRemote, bool)`

GetRemoteOk returns a tuple with the Remote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemote

`func (o *SecretsConfigSummary) SetRemote(v SecretsConfigSummaryRemote)`

SetRemote sets Remote field to given value.


### SetRemoteNil

`func (o *SecretsConfigSummary) SetRemoteNil(b bool)`

 SetRemoteNil sets the value for Remote to be an explicit nil

### UnsetRemote
`func (o *SecretsConfigSummary) UnsetRemote()`

UnsetRemote ensures that no value is present for Remote, not even an explicit nil
### GetUpdatedAt

`func (o *SecretsConfigSummary) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SecretsConfigSummary) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SecretsConfigSummary) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


