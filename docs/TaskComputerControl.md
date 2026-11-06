# TaskComputerControl

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** |  | 
**ControlVersion** | Pointer to **int32** |  | [optional] 

## Methods

### NewTaskComputerControl

`func NewTaskComputerControl(action string, ) *TaskComputerControl`

NewTaskComputerControl instantiates a new TaskComputerControl object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskComputerControlWithDefaults

`func NewTaskComputerControlWithDefaults() *TaskComputerControl`

NewTaskComputerControlWithDefaults instantiates a new TaskComputerControl object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *TaskComputerControl) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *TaskComputerControl) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *TaskComputerControl) SetAction(v string)`

SetAction sets Action field to given value.


### GetControlVersion

`func (o *TaskComputerControl) GetControlVersion() int32`

GetControlVersion returns the ControlVersion field if non-nil, zero value otherwise.

### GetControlVersionOk

`func (o *TaskComputerControl) GetControlVersionOk() (*int32, bool)`

GetControlVersionOk returns a tuple with the ControlVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlVersion

`func (o *TaskComputerControl) SetControlVersion(v int32)`

SetControlVersion sets ControlVersion field to given value.

### HasControlVersion

`func (o *TaskComputerControl) HasControlVersion() bool`

HasControlVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


