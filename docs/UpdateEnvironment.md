# UpdateEnvironment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | Pointer to [**CreateEnvironmentConfig**](CreateEnvironmentConfig.md) |  | [optional]
**IsActive** | Pointer to **bool** |  | [optional]
**Label** | Pointer to **string** |  | [optional]

## Methods

### NewUpdateEnvironment

`func NewUpdateEnvironment() *UpdateEnvironment`

NewUpdateEnvironment instantiates a new UpdateEnvironment object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpdateEnvironmentWithDefaults

`func NewUpdateEnvironmentWithDefaults() *UpdateEnvironment`

NewUpdateEnvironmentWithDefaults instantiates a new UpdateEnvironment object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetConfig

`func (o *UpdateEnvironment) GetConfig() CreateEnvironmentConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *UpdateEnvironment) GetConfigOk() (*CreateEnvironmentConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *UpdateEnvironment) SetConfig(v CreateEnvironmentConfig)`

SetConfig sets Config field to given value.

### HasConfig

`func (o *UpdateEnvironment) HasConfig() bool`

HasConfig returns a boolean if a field has been set.

### GetIsActive

`func (o *UpdateEnvironment) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateEnvironment) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateEnvironment) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateEnvironment) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetLabel

`func (o *UpdateEnvironment) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *UpdateEnvironment) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *UpdateEnvironment) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *UpdateEnvironment) HasLabel() bool`

HasLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


