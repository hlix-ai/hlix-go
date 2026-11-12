# ProjectWorkspaceExec

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | **string** |  |
**Cwd** | Pointer to **string** |  | [optional]
**TimeoutMs** | Pointer to **int32** |  | [optional] [default to 600000]

## Methods

### NewProjectWorkspaceExec

`func NewProjectWorkspaceExec(command string, ) *ProjectWorkspaceExec`

NewProjectWorkspaceExec instantiates a new ProjectWorkspaceExec object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectWorkspaceExecWithDefaults

`func NewProjectWorkspaceExecWithDefaults() *ProjectWorkspaceExec`

NewProjectWorkspaceExecWithDefaults instantiates a new ProjectWorkspaceExec object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCommand

`func (o *ProjectWorkspaceExec) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *ProjectWorkspaceExec) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *ProjectWorkspaceExec) SetCommand(v string)`

SetCommand sets Command field to given value.


### GetCwd

`func (o *ProjectWorkspaceExec) GetCwd() string`

GetCwd returns the Cwd field if non-nil, zero value otherwise.

### GetCwdOk

`func (o *ProjectWorkspaceExec) GetCwdOk() (*string, bool)`

GetCwdOk returns a tuple with the Cwd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCwd

`func (o *ProjectWorkspaceExec) SetCwd(v string)`

SetCwd sets Cwd field to given value.

### HasCwd

`func (o *ProjectWorkspaceExec) HasCwd() bool`

HasCwd returns a boolean if a field has been set.

### GetTimeoutMs

`func (o *ProjectWorkspaceExec) GetTimeoutMs() int32`

GetTimeoutMs returns the TimeoutMs field if non-nil, zero value otherwise.

### GetTimeoutMsOk

`func (o *ProjectWorkspaceExec) GetTimeoutMsOk() (*int32, bool)`

GetTimeoutMsOk returns a tuple with the TimeoutMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeoutMs

`func (o *ProjectWorkspaceExec) SetTimeoutMs(v int32)`

SetTimeoutMs sets TimeoutMs field to given value.

### HasTimeoutMs

`func (o *ProjectWorkspaceExec) HasTimeoutMs() bool`

HasTimeoutMs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


