# ProjectStopped

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InterruptedCycles** | **[]string** |  | 
**Status** | **string** |  | 

## Methods

### NewProjectStopped

`func NewProjectStopped(interruptedCycles []string, status string, ) *ProjectStopped`

NewProjectStopped instantiates a new ProjectStopped object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectStoppedWithDefaults

`func NewProjectStoppedWithDefaults() *ProjectStopped`

NewProjectStoppedWithDefaults instantiates a new ProjectStopped object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInterruptedCycles

`func (o *ProjectStopped) GetInterruptedCycles() []string`

GetInterruptedCycles returns the InterruptedCycles field if non-nil, zero value otherwise.

### GetInterruptedCyclesOk

`func (o *ProjectStopped) GetInterruptedCyclesOk() (*[]string, bool)`

GetInterruptedCyclesOk returns a tuple with the InterruptedCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterruptedCycles

`func (o *ProjectStopped) SetInterruptedCycles(v []string)`

SetInterruptedCycles sets InterruptedCycles field to given value.


### GetStatus

`func (o *ProjectStopped) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectStopped) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectStopped) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


