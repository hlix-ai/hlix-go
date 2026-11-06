# TaskComputersComputersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlVersion** | **int32** |  | 
**CycleTitle** | **NullableString** |  | 
**Deadline** | **time.Time** |  | 
**HasReplay** | **bool** |  | 
**HasScreenshot** | **bool** |  | 
**Id** | **string** |  | 
**LastActivityAt** | **time.Time** |  | 
**LeaseUntil** | **NullableTime** |  | 
**Presence** | **string** |  | 
**StartedAt** | **time.Time** |  | 
**State** | **string** |  | 
**TaskId** | **string** |  | 
**Title** | **NullableString** |  | 

## Methods

### NewTaskComputersComputersInner

`func NewTaskComputersComputersInner(controlVersion int32, cycleTitle NullableString, deadline time.Time, hasReplay bool, hasScreenshot bool, id string, lastActivityAt time.Time, leaseUntil NullableTime, presence string, startedAt time.Time, state string, taskId string, title NullableString, ) *TaskComputersComputersInner`

NewTaskComputersComputersInner instantiates a new TaskComputersComputersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskComputersComputersInnerWithDefaults

`func NewTaskComputersComputersInnerWithDefaults() *TaskComputersComputersInner`

NewTaskComputersComputersInnerWithDefaults instantiates a new TaskComputersComputersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetControlVersion

`func (o *TaskComputersComputersInner) GetControlVersion() int32`

GetControlVersion returns the ControlVersion field if non-nil, zero value otherwise.

### GetControlVersionOk

`func (o *TaskComputersComputersInner) GetControlVersionOk() (*int32, bool)`

GetControlVersionOk returns a tuple with the ControlVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlVersion

`func (o *TaskComputersComputersInner) SetControlVersion(v int32)`

SetControlVersion sets ControlVersion field to given value.


### GetCycleTitle

`func (o *TaskComputersComputersInner) GetCycleTitle() string`

GetCycleTitle returns the CycleTitle field if non-nil, zero value otherwise.

### GetCycleTitleOk

`func (o *TaskComputersComputersInner) GetCycleTitleOk() (*string, bool)`

GetCycleTitleOk returns a tuple with the CycleTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleTitle

`func (o *TaskComputersComputersInner) SetCycleTitle(v string)`

SetCycleTitle sets CycleTitle field to given value.


### SetCycleTitleNil

`func (o *TaskComputersComputersInner) SetCycleTitleNil(b bool)`

 SetCycleTitleNil sets the value for CycleTitle to be an explicit nil

### UnsetCycleTitle
`func (o *TaskComputersComputersInner) UnsetCycleTitle()`

UnsetCycleTitle ensures that no value is present for CycleTitle, not even an explicit nil
### GetDeadline

`func (o *TaskComputersComputersInner) GetDeadline() time.Time`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *TaskComputersComputersInner) GetDeadlineOk() (*time.Time, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *TaskComputersComputersInner) SetDeadline(v time.Time)`

SetDeadline sets Deadline field to given value.


### GetHasReplay

`func (o *TaskComputersComputersInner) GetHasReplay() bool`

GetHasReplay returns the HasReplay field if non-nil, zero value otherwise.

### GetHasReplayOk

`func (o *TaskComputersComputersInner) GetHasReplayOk() (*bool, bool)`

GetHasReplayOk returns a tuple with the HasReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasReplay

`func (o *TaskComputersComputersInner) SetHasReplay(v bool)`

SetHasReplay sets HasReplay field to given value.


### GetHasScreenshot

`func (o *TaskComputersComputersInner) GetHasScreenshot() bool`

GetHasScreenshot returns the HasScreenshot field if non-nil, zero value otherwise.

### GetHasScreenshotOk

`func (o *TaskComputersComputersInner) GetHasScreenshotOk() (*bool, bool)`

GetHasScreenshotOk returns a tuple with the HasScreenshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasScreenshot

`func (o *TaskComputersComputersInner) SetHasScreenshot(v bool)`

SetHasScreenshot sets HasScreenshot field to given value.


### GetId

`func (o *TaskComputersComputersInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TaskComputersComputersInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TaskComputersComputersInner) SetId(v string)`

SetId sets Id field to given value.


### GetLastActivityAt

`func (o *TaskComputersComputersInner) GetLastActivityAt() time.Time`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *TaskComputersComputersInner) GetLastActivityAtOk() (*time.Time, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *TaskComputersComputersInner) SetLastActivityAt(v time.Time)`

SetLastActivityAt sets LastActivityAt field to given value.


### GetLeaseUntil

`func (o *TaskComputersComputersInner) GetLeaseUntil() time.Time`

GetLeaseUntil returns the LeaseUntil field if non-nil, zero value otherwise.

### GetLeaseUntilOk

`func (o *TaskComputersComputersInner) GetLeaseUntilOk() (*time.Time, bool)`

GetLeaseUntilOk returns a tuple with the LeaseUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaseUntil

`func (o *TaskComputersComputersInner) SetLeaseUntil(v time.Time)`

SetLeaseUntil sets LeaseUntil field to given value.


### SetLeaseUntilNil

`func (o *TaskComputersComputersInner) SetLeaseUntilNil(b bool)`

 SetLeaseUntilNil sets the value for LeaseUntil to be an explicit nil

### UnsetLeaseUntil
`func (o *TaskComputersComputersInner) UnsetLeaseUntil()`

UnsetLeaseUntil ensures that no value is present for LeaseUntil, not even an explicit nil
### GetPresence

`func (o *TaskComputersComputersInner) GetPresence() string`

GetPresence returns the Presence field if non-nil, zero value otherwise.

### GetPresenceOk

`func (o *TaskComputersComputersInner) GetPresenceOk() (*string, bool)`

GetPresenceOk returns a tuple with the Presence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresence

`func (o *TaskComputersComputersInner) SetPresence(v string)`

SetPresence sets Presence field to given value.


### GetStartedAt

`func (o *TaskComputersComputersInner) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *TaskComputersComputersInner) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *TaskComputersComputersInner) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### GetState

`func (o *TaskComputersComputersInner) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *TaskComputersComputersInner) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *TaskComputersComputersInner) SetState(v string)`

SetState sets State field to given value.


### GetTaskId

`func (o *TaskComputersComputersInner) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *TaskComputersComputersInner) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *TaskComputersComputersInner) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetTitle

`func (o *TaskComputersComputersInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *TaskComputersComputersInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *TaskComputersComputersInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *TaskComputersComputersInner) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *TaskComputersComputersInner) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


