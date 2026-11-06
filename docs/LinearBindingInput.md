# LinearBindingInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**InstallationId** | **string** |  | 
**LabelId** | **NullableString** |  | 
**LinearProjectId** | **NullableString** |  | 
**Mode** | Pointer to **string** |  | [optional] [default to "automatic"]
**TeamId** | **string** |  | 

## Methods

### NewLinearBindingInput

`func NewLinearBindingInput(enabled bool, installationId string, labelId NullableString, linearProjectId NullableString, teamId string, ) *LinearBindingInput`

NewLinearBindingInput instantiates a new LinearBindingInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinearBindingInputWithDefaults

`func NewLinearBindingInputWithDefaults() *LinearBindingInput`

NewLinearBindingInputWithDefaults instantiates a new LinearBindingInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *LinearBindingInput) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *LinearBindingInput) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *LinearBindingInput) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetInstallationId

`func (o *LinearBindingInput) GetInstallationId() string`

GetInstallationId returns the InstallationId field if non-nil, zero value otherwise.

### GetInstallationIdOk

`func (o *LinearBindingInput) GetInstallationIdOk() (*string, bool)`

GetInstallationIdOk returns a tuple with the InstallationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallationId

`func (o *LinearBindingInput) SetInstallationId(v string)`

SetInstallationId sets InstallationId field to given value.


### GetLabelId

`func (o *LinearBindingInput) GetLabelId() string`

GetLabelId returns the LabelId field if non-nil, zero value otherwise.

### GetLabelIdOk

`func (o *LinearBindingInput) GetLabelIdOk() (*string, bool)`

GetLabelIdOk returns a tuple with the LabelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabelId

`func (o *LinearBindingInput) SetLabelId(v string)`

SetLabelId sets LabelId field to given value.


### SetLabelIdNil

`func (o *LinearBindingInput) SetLabelIdNil(b bool)`

 SetLabelIdNil sets the value for LabelId to be an explicit nil

### UnsetLabelId
`func (o *LinearBindingInput) UnsetLabelId()`

UnsetLabelId ensures that no value is present for LabelId, not even an explicit nil
### GetLinearProjectId

`func (o *LinearBindingInput) GetLinearProjectId() string`

GetLinearProjectId returns the LinearProjectId field if non-nil, zero value otherwise.

### GetLinearProjectIdOk

`func (o *LinearBindingInput) GetLinearProjectIdOk() (*string, bool)`

GetLinearProjectIdOk returns a tuple with the LinearProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearProjectId

`func (o *LinearBindingInput) SetLinearProjectId(v string)`

SetLinearProjectId sets LinearProjectId field to given value.


### SetLinearProjectIdNil

`func (o *LinearBindingInput) SetLinearProjectIdNil(b bool)`

 SetLinearProjectIdNil sets the value for LinearProjectId to be an explicit nil

### UnsetLinearProjectId
`func (o *LinearBindingInput) UnsetLinearProjectId()`

UnsetLinearProjectId ensures that no value is present for LinearProjectId, not even an explicit nil
### GetMode

`func (o *LinearBindingInput) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *LinearBindingInput) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *LinearBindingInput) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *LinearBindingInput) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetTeamId

`func (o *LinearBindingInput) GetTeamId() string`

GetTeamId returns the TeamId field if non-nil, zero value otherwise.

### GetTeamIdOk

`func (o *LinearBindingInput) GetTeamIdOk() (*string, bool)`

GetTeamIdOk returns a tuple with the TeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeamId

`func (o *LinearBindingInput) SetTeamId(v string)`

SetTeamId sets TeamId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


