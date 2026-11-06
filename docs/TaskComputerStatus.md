# TaskComputerStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **bool** |  | 
**ControlVersion** | **int32** |  | 
**Deadline** | **time.Time** |  | 
**DesktopUrl** | Pointer to **string** |  | [optional] 
**HasReplay** | **bool** |  | 
**HasScreenshot** | **bool** |  | 
**HumanControl** | Pointer to **bool** |  | [optional] 
**Id** | **string** |  | 
**LeaseUntil** | **NullableTime** |  | 
**State** | **string** |  | 
**TaskId** | **string** |  | 
**Title** | **NullableString** |  | 

## Methods

### NewTaskComputerStatus

`func NewTaskComputerStatus(available bool, controlVersion int32, deadline time.Time, hasReplay bool, hasScreenshot bool, id string, leaseUntil NullableTime, state string, taskId string, title NullableString, ) *TaskComputerStatus`

NewTaskComputerStatus instantiates a new TaskComputerStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskComputerStatusWithDefaults

`func NewTaskComputerStatusWithDefaults() *TaskComputerStatus`

NewTaskComputerStatusWithDefaults instantiates a new TaskComputerStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *TaskComputerStatus) GetAvailable() bool`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *TaskComputerStatus) GetAvailableOk() (*bool, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *TaskComputerStatus) SetAvailable(v bool)`

SetAvailable sets Available field to given value.


### GetControlVersion

`func (o *TaskComputerStatus) GetControlVersion() int32`

GetControlVersion returns the ControlVersion field if non-nil, zero value otherwise.

### GetControlVersionOk

`func (o *TaskComputerStatus) GetControlVersionOk() (*int32, bool)`

GetControlVersionOk returns a tuple with the ControlVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlVersion

`func (o *TaskComputerStatus) SetControlVersion(v int32)`

SetControlVersion sets ControlVersion field to given value.


### GetDeadline

`func (o *TaskComputerStatus) GetDeadline() time.Time`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *TaskComputerStatus) GetDeadlineOk() (*time.Time, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *TaskComputerStatus) SetDeadline(v time.Time)`

SetDeadline sets Deadline field to given value.


### GetDesktopUrl

`func (o *TaskComputerStatus) GetDesktopUrl() string`

GetDesktopUrl returns the DesktopUrl field if non-nil, zero value otherwise.

### GetDesktopUrlOk

`func (o *TaskComputerStatus) GetDesktopUrlOk() (*string, bool)`

GetDesktopUrlOk returns a tuple with the DesktopUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesktopUrl

`func (o *TaskComputerStatus) SetDesktopUrl(v string)`

SetDesktopUrl sets DesktopUrl field to given value.

### HasDesktopUrl

`func (o *TaskComputerStatus) HasDesktopUrl() bool`

HasDesktopUrl returns a boolean if a field has been set.

### GetHasReplay

`func (o *TaskComputerStatus) GetHasReplay() bool`

GetHasReplay returns the HasReplay field if non-nil, zero value otherwise.

### GetHasReplayOk

`func (o *TaskComputerStatus) GetHasReplayOk() (*bool, bool)`

GetHasReplayOk returns a tuple with the HasReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasReplay

`func (o *TaskComputerStatus) SetHasReplay(v bool)`

SetHasReplay sets HasReplay field to given value.


### GetHasScreenshot

`func (o *TaskComputerStatus) GetHasScreenshot() bool`

GetHasScreenshot returns the HasScreenshot field if non-nil, zero value otherwise.

### GetHasScreenshotOk

`func (o *TaskComputerStatus) GetHasScreenshotOk() (*bool, bool)`

GetHasScreenshotOk returns a tuple with the HasScreenshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasScreenshot

`func (o *TaskComputerStatus) SetHasScreenshot(v bool)`

SetHasScreenshot sets HasScreenshot field to given value.


### GetHumanControl

`func (o *TaskComputerStatus) GetHumanControl() bool`

GetHumanControl returns the HumanControl field if non-nil, zero value otherwise.

### GetHumanControlOk

`func (o *TaskComputerStatus) GetHumanControlOk() (*bool, bool)`

GetHumanControlOk returns a tuple with the HumanControl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHumanControl

`func (o *TaskComputerStatus) SetHumanControl(v bool)`

SetHumanControl sets HumanControl field to given value.

### HasHumanControl

`func (o *TaskComputerStatus) HasHumanControl() bool`

HasHumanControl returns a boolean if a field has been set.

### GetId

`func (o *TaskComputerStatus) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TaskComputerStatus) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TaskComputerStatus) SetId(v string)`

SetId sets Id field to given value.


### GetLeaseUntil

`func (o *TaskComputerStatus) GetLeaseUntil() time.Time`

GetLeaseUntil returns the LeaseUntil field if non-nil, zero value otherwise.

### GetLeaseUntilOk

`func (o *TaskComputerStatus) GetLeaseUntilOk() (*time.Time, bool)`

GetLeaseUntilOk returns a tuple with the LeaseUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseUntil

`func (o *TaskComputerStatus) SetLeaseUntil(v time.Time)`

SetLeaseUntil sets LeaseUntil field to given value.


### SetLeaseUntilNil

`func (o *TaskComputerStatus) SetLeaseUntilNil(b bool)`

 SetLeaseUntilNil sets the value for LeaseUntil to be an explicit nil

### UnsetLeaseUntil
`func (o *TaskComputerStatus) UnsetLeaseUntil()`

UnsetLeaseUntil ensures that no value is present for LeaseUntil, not even an explicit nil
### GetState

`func (o *TaskComputerStatus) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *TaskComputerStatus) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *TaskComputerStatus) SetState(v string)`

SetState sets State field to given value.


### GetTaskId

`func (o *TaskComputerStatus) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *TaskComputerStatus) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *TaskComputerStatus) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetTitle

`func (o *TaskComputerStatus) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *TaskComputerStatus) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *TaskComputerStatus) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *TaskComputerStatus) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *TaskComputerStatus) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


