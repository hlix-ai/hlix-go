# CreateEnvironment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | [**CreateEnvironmentConfig**](CreateEnvironmentConfig.md) |  | 
**IsActive** | Pointer to **bool** |  | [optional] 
**Label** | **string** |  | 

## Methods

### NewCreateEnvironment

`func NewCreateEnvironment(config CreateEnvironmentConfig, label string, ) *CreateEnvironment`

NewCreateEnvironment instantiates a new CreateEnvironment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateEnvironmentWithDefaults

`func NewCreateEnvironmentWithDefaults() *CreateEnvironment`

NewCreateEnvironmentWithDefaults instantiates a new CreateEnvironment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *CreateEnvironment) GetConfig() CreateEnvironmentConfig`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *CreateEnvironment) GetConfigOk() (*CreateEnvironmentConfig, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *CreateEnvironment) SetConfig(v CreateEnvironmentConfig)`

SetConfig sets Config field to given value.


### GetIsActive

`func (o *CreateEnvironment) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *CreateEnvironment) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *CreateEnvironment) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *CreateEnvironment) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetLabel

`func (o *CreateEnvironment) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateEnvironment) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateEnvironment) SetLabel(v string)`

SetLabel sets Label field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


