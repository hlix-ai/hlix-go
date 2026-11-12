# ProjectEnvironment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Capabilities** | [**ProjectEnvironmentCapabilities**](ProjectEnvironmentCapabilities.md) |  |
**CreatedAt** | **NullableString** |  |
**State** | **string** |  |
**WorkspaceRoot** | **string** |  |

## Methods

### NewProjectEnvironment

`func NewProjectEnvironment(capabilities ProjectEnvironmentCapabilities, createdAt NullableString, state string, workspaceRoot string, ) *ProjectEnvironment`

NewProjectEnvironment instantiates a new ProjectEnvironment object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectEnvironmentWithDefaults

`func NewProjectEnvironmentWithDefaults() *ProjectEnvironment`

NewProjectEnvironmentWithDefaults instantiates a new ProjectEnvironment object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCapabilities

`func (o *ProjectEnvironment) GetCapabilities() ProjectEnvironmentCapabilities`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *ProjectEnvironment) GetCapabilitiesOk() (*ProjectEnvironmentCapabilities, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *ProjectEnvironment) SetCapabilities(v ProjectEnvironmentCapabilities)`

SetCapabilities sets Capabilities field to given value.


### GetCreatedAt

`func (o *ProjectEnvironment) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectEnvironment) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectEnvironment) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *ProjectEnvironment) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ProjectEnvironment) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetState

`func (o *ProjectEnvironment) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ProjectEnvironment) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ProjectEnvironment) SetState(v string)`

SetState sets State field to given value.


### GetWorkspaceRoot

`func (o *ProjectEnvironment) GetWorkspaceRoot() string`

GetWorkspaceRoot returns the WorkspaceRoot field if non-nil, zero value otherwise.

### GetWorkspaceRootOk

`func (o *ProjectEnvironment) GetWorkspaceRootOk() (*string, bool)`

GetWorkspaceRootOk returns a tuple with the WorkspaceRoot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceRoot

`func (o *ProjectEnvironment) SetWorkspaceRoot(v string)`

SetWorkspaceRoot sets WorkspaceRoot field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


