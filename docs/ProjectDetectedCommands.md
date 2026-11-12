# ProjectDetectedCommands

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Apps** | Pointer to [**[]ProjectDetectedCommandsAppsInner**](ProjectDetectedCommandsAppsInner.md) |  | [optional]
**Mobile** | Pointer to **bool** |  | [optional]
**PreviewCommand** | **NullableString** |  |
**PreviewPort** | **NullableInt32** |  |
**VerifyCommand** | **NullableString** |  |

## Methods

### NewProjectDetectedCommands

`func NewProjectDetectedCommands(previewCommand NullableString, previewPort NullableInt32, verifyCommand NullableString, ) *ProjectDetectedCommands`

NewProjectDetectedCommands instantiates a new ProjectDetectedCommands object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectDetectedCommandsWithDefaults

`func NewProjectDetectedCommandsWithDefaults() *ProjectDetectedCommands`

NewProjectDetectedCommandsWithDefaults instantiates a new ProjectDetectedCommands object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApps

`func (o *ProjectDetectedCommands) GetApps() []ProjectDetectedCommandsAppsInner`

GetApps returns the Apps field if non-nil, zero value otherwise.

### GetAppsOk

`func (o *ProjectDetectedCommands) GetAppsOk() (*[]ProjectDetectedCommandsAppsInner, bool)`

GetAppsOk returns a tuple with the Apps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApps

`func (o *ProjectDetectedCommands) SetApps(v []ProjectDetectedCommandsAppsInner)`

SetApps sets Apps field to given value.

### HasApps

`func (o *ProjectDetectedCommands) HasApps() bool`

HasApps returns a boolean if a field has been set.

### GetMobile

`func (o *ProjectDetectedCommands) GetMobile() bool`

GetMobile returns the Mobile field if non-nil, zero value otherwise.

### GetMobileOk

`func (o *ProjectDetectedCommands) GetMobileOk() (*bool, bool)`

GetMobileOk returns a tuple with the Mobile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobile

`func (o *ProjectDetectedCommands) SetMobile(v bool)`

SetMobile sets Mobile field to given value.

### HasMobile

`func (o *ProjectDetectedCommands) HasMobile() bool`

HasMobile returns a boolean if a field has been set.

### GetPreviewCommand

`func (o *ProjectDetectedCommands) GetPreviewCommand() string`

GetPreviewCommand returns the PreviewCommand field if non-nil, zero value otherwise.

### GetPreviewCommandOk

`func (o *ProjectDetectedCommands) GetPreviewCommandOk() (*string, bool)`

GetPreviewCommandOk returns a tuple with the PreviewCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewCommand

`func (o *ProjectDetectedCommands) SetPreviewCommand(v string)`

SetPreviewCommand sets PreviewCommand field to given value.


### SetPreviewCommandNil

`func (o *ProjectDetectedCommands) SetPreviewCommandNil(b bool)`

 SetPreviewCommandNil sets the value for PreviewCommand to be an explicit nil

### UnsetPreviewCommand
`func (o *ProjectDetectedCommands) UnsetPreviewCommand()`

UnsetPreviewCommand ensures that no value is present for PreviewCommand, not even an explicit nil
### GetPreviewPort

`func (o *ProjectDetectedCommands) GetPreviewPort() int32`

GetPreviewPort returns the PreviewPort field if non-nil, zero value otherwise.

### GetPreviewPortOk

`func (o *ProjectDetectedCommands) GetPreviewPortOk() (*int32, bool)`

GetPreviewPortOk returns a tuple with the PreviewPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPort

`func (o *ProjectDetectedCommands) SetPreviewPort(v int32)`

SetPreviewPort sets PreviewPort field to given value.


### SetPreviewPortNil

`func (o *ProjectDetectedCommands) SetPreviewPortNil(b bool)`

 SetPreviewPortNil sets the value for PreviewPort to be an explicit nil

### UnsetPreviewPort
`func (o *ProjectDetectedCommands) UnsetPreviewPort()`

UnsetPreviewPort ensures that no value is present for PreviewPort, not even an explicit nil
### GetVerifyCommand

`func (o *ProjectDetectedCommands) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *ProjectDetectedCommands) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *ProjectDetectedCommands) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.


### SetVerifyCommandNil

`func (o *ProjectDetectedCommands) SetVerifyCommandNil(b bool)`

 SetVerifyCommandNil sets the value for VerifyCommand to be an explicit nil

### UnsetVerifyCommand
`func (o *ProjectDetectedCommands) UnsetVerifyCommand()`

UnsetVerifyCommand ensures that no value is present for VerifyCommand, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


