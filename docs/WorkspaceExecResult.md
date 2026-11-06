# WorkspaceExecResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExitCode** | **int32** |  | 
**Stderr** | **string** |  | 
**Stdout** | **string** |  | 

## Methods

### NewWorkspaceExecResult

`func NewWorkspaceExecResult(exitCode int32, stderr string, stdout string, ) *WorkspaceExecResult`

NewWorkspaceExecResult instantiates a new WorkspaceExecResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceExecResultWithDefaults

`func NewWorkspaceExecResultWithDefaults() *WorkspaceExecResult`

NewWorkspaceExecResultWithDefaults instantiates a new WorkspaceExecResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExitCode

`func (o *WorkspaceExecResult) GetExitCode() int32`

GetExitCode returns the ExitCode field if non-nil, zero value otherwise.

### GetExitCodeOk

`func (o *WorkspaceExecResult) GetExitCodeOk() (*int32, bool)`

GetExitCodeOk returns a tuple with the ExitCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExitCode

`func (o *WorkspaceExecResult) SetExitCode(v int32)`

SetExitCode sets ExitCode field to given value.


### GetStderr

`func (o *WorkspaceExecResult) GetStderr() string`

GetStderr returns the Stderr field if non-nil, zero value otherwise.

### GetStderrOk

`func (o *WorkspaceExecResult) GetStderrOk() (*string, bool)`

GetStderrOk returns a tuple with the Stderr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStderr

`func (o *WorkspaceExecResult) SetStderr(v string)`

SetStderr sets Stderr field to given value.


### GetStdout

`func (o *WorkspaceExecResult) GetStdout() string`

GetStdout returns the Stdout field if non-nil, zero value otherwise.

### GetStdoutOk

`func (o *WorkspaceExecResult) GetStdoutOk() (*string, bool)`

GetStdoutOk returns a tuple with the Stdout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStdout

`func (o *WorkspaceExecResult) SetStdout(v string)`

SetStdout sets Stdout field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


