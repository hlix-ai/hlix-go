# DesktopsDesktopsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlledBy** | [**NullableDesktopControlledBy**](DesktopControlledBy.md) |  |
**CycleTitle** | **NullableString** |  |
**HasReplay** | **bool** |  |
**HasScreenshot** | **bool** |  |
**Id** | **string** |  |
**Kind** | **string** |  |
**LastActivityAt** | **NullableTime** |  |
**Presence** | **string** |  |
**Role** | **NullableString** |  |
**StartedAt** | **NullableTime** |  |
**TaskId** | **NullableString** |  |
**Title** | **NullableString** |  |

## Methods

### NewDesktopsDesktopsInner

`func NewDesktopsDesktopsInner(controlledBy NullableDesktopControlledBy, cycleTitle NullableString, hasReplay bool, hasScreenshot bool, id string, kind string, lastActivityAt NullableTime, presence string, role NullableString, startedAt NullableTime, taskId NullableString, title NullableString, ) *DesktopsDesktopsInner`

NewDesktopsDesktopsInner instantiates a new DesktopsDesktopsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDesktopsDesktopsInnerWithDefaults

`func NewDesktopsDesktopsInnerWithDefaults() *DesktopsDesktopsInner`

NewDesktopsDesktopsInnerWithDefaults instantiates a new DesktopsDesktopsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetControlledBy

`func (o *DesktopsDesktopsInner) GetControlledBy() DesktopControlledBy`

GetControlledBy returns the ControlledBy field if non-nil, zero value otherwise.

### GetControlledByOk

`func (o *DesktopsDesktopsInner) GetControlledByOk() (*DesktopControlledBy, bool)`

GetControlledByOk returns a tuple with the ControlledBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlledBy

`func (o *DesktopsDesktopsInner) SetControlledBy(v DesktopControlledBy)`

SetControlledBy sets ControlledBy field to given value.


### SetControlledByNil

`func (o *DesktopsDesktopsInner) SetControlledByNil(b bool)`

 SetControlledByNil sets the value for ControlledBy to be an explicit nil

### UnsetControlledBy
`func (o *DesktopsDesktopsInner) UnsetControlledBy()`

UnsetControlledBy ensures that no value is present for ControlledBy, not even an explicit nil
### GetCycleTitle

`func (o *DesktopsDesktopsInner) GetCycleTitle() string`

GetCycleTitle returns the CycleTitle field if non-nil, zero value otherwise.

### GetCycleTitleOk

`func (o *DesktopsDesktopsInner) GetCycleTitleOk() (*string, bool)`

GetCycleTitleOk returns a tuple with the CycleTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleTitle

`func (o *DesktopsDesktopsInner) SetCycleTitle(v string)`

SetCycleTitle sets CycleTitle field to given value.


### SetCycleTitleNil

`func (o *DesktopsDesktopsInner) SetCycleTitleNil(b bool)`

 SetCycleTitleNil sets the value for CycleTitle to be an explicit nil

### UnsetCycleTitle
`func (o *DesktopsDesktopsInner) UnsetCycleTitle()`

UnsetCycleTitle ensures that no value is present for CycleTitle, not even an explicit nil
### GetHasReplay

`func (o *DesktopsDesktopsInner) GetHasReplay() bool`

GetHasReplay returns the HasReplay field if non-nil, zero value otherwise.

### GetHasReplayOk

`func (o *DesktopsDesktopsInner) GetHasReplayOk() (*bool, bool)`

GetHasReplayOk returns a tuple with the HasReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasReplay

`func (o *DesktopsDesktopsInner) SetHasReplay(v bool)`

SetHasReplay sets HasReplay field to given value.


### GetHasScreenshot

`func (o *DesktopsDesktopsInner) GetHasScreenshot() bool`

GetHasScreenshot returns the HasScreenshot field if non-nil, zero value otherwise.

### GetHasScreenshotOk

`func (o *DesktopsDesktopsInner) GetHasScreenshotOk() (*bool, bool)`

GetHasScreenshotOk returns a tuple with the HasScreenshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasScreenshot

`func (o *DesktopsDesktopsInner) SetHasScreenshot(v bool)`

SetHasScreenshot sets HasScreenshot field to given value.


### GetId

`func (o *DesktopsDesktopsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DesktopsDesktopsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DesktopsDesktopsInner) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *DesktopsDesktopsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *DesktopsDesktopsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *DesktopsDesktopsInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLastActivityAt

`func (o *DesktopsDesktopsInner) GetLastActivityAt() time.Time`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *DesktopsDesktopsInner) GetLastActivityAtOk() (*time.Time, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *DesktopsDesktopsInner) SetLastActivityAt(v time.Time)`

SetLastActivityAt sets LastActivityAt field to given value.


### SetLastActivityAtNil

`func (o *DesktopsDesktopsInner) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *DesktopsDesktopsInner) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetPresence

`func (o *DesktopsDesktopsInner) GetPresence() string`

GetPresence returns the Presence field if non-nil, zero value otherwise.

### GetPresenceOk

`func (o *DesktopsDesktopsInner) GetPresenceOk() (*string, bool)`

GetPresenceOk returns a tuple with the Presence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresence

`func (o *DesktopsDesktopsInner) SetPresence(v string)`

SetPresence sets Presence field to given value.


### GetRole

`func (o *DesktopsDesktopsInner) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *DesktopsDesktopsInner) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *DesktopsDesktopsInner) SetRole(v string)`

SetRole sets Role field to given value.


### SetRoleNil

`func (o *DesktopsDesktopsInner) SetRoleNil(b bool)`

 SetRoleNil sets the value for Role to be an explicit nil

### UnsetRole
`func (o *DesktopsDesktopsInner) UnsetRole()`

UnsetRole ensures that no value is present for Role, not even an explicit nil
### GetStartedAt

`func (o *DesktopsDesktopsInner) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *DesktopsDesktopsInner) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *DesktopsDesktopsInner) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.


### SetStartedAtNil

`func (o *DesktopsDesktopsInner) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *DesktopsDesktopsInner) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetTaskId

`func (o *DesktopsDesktopsInner) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *DesktopsDesktopsInner) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *DesktopsDesktopsInner) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *DesktopsDesktopsInner) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *DesktopsDesktopsInner) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTitle

`func (o *DesktopsDesktopsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *DesktopsDesktopsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *DesktopsDesktopsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *DesktopsDesktopsInner) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *DesktopsDesktopsInner) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


