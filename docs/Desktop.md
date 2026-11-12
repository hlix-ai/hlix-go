# Desktop

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ControlUrl** | Pointer to **string** |  | [optional]
**ControlledBy** | [**NullableDesktopControlledBy**](DesktopControlledBy.md) |  |
**Deadline** | Pointer to **time.Time** |  | [optional]
**FrameUrl** | Pointer to **string** |  | [optional]
**HasReplay** | **bool** |  |
**HasScreenshot** | **bool** |  |
**Id** | **string** |  |
**Kind** | **string** |  |
**State** | **string** |  |
**TaskId** | Pointer to **NullableString** |  | [optional]
**Title** | Pointer to **NullableString** |  | [optional]

## Methods

### NewDesktop

`func NewDesktop(controlledBy NullableDesktopControlledBy, hasReplay bool, hasScreenshot bool, id string, kind string, state string, ) *Desktop`

NewDesktop instantiates a new Desktop object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDesktopWithDefaults

`func NewDesktopWithDefaults() *Desktop`

NewDesktopWithDefaults instantiates a new Desktop object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetControlUrl

`func (o *Desktop) GetControlUrl() string`

GetControlUrl returns the ControlUrl field if non-nil, zero value otherwise.

### GetControlUrlOk

`func (o *Desktop) GetControlUrlOk() (*string, bool)`

GetControlUrlOk returns a tuple with the ControlUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlUrl

`func (o *Desktop) SetControlUrl(v string)`

SetControlUrl sets ControlUrl field to given value.

### HasControlUrl

`func (o *Desktop) HasControlUrl() bool`

HasControlUrl returns a boolean if a field has been set.

### GetControlledBy

`func (o *Desktop) GetControlledBy() DesktopControlledBy`

GetControlledBy returns the ControlledBy field if non-nil, zero value otherwise.

### GetControlledByOk

`func (o *Desktop) GetControlledByOk() (*DesktopControlledBy, bool)`

GetControlledByOk returns a tuple with the ControlledBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlledBy

`func (o *Desktop) SetControlledBy(v DesktopControlledBy)`

SetControlledBy sets ControlledBy field to given value.


### SetControlledByNil

`func (o *Desktop) SetControlledByNil(b bool)`

 SetControlledByNil sets the value for ControlledBy to be an explicit nil

### UnsetControlledBy
`func (o *Desktop) UnsetControlledBy()`

UnsetControlledBy ensures that no value is present for ControlledBy, not even an explicit nil
### GetDeadline

`func (o *Desktop) GetDeadline() time.Time`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *Desktop) GetDeadlineOk() (*time.Time, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *Desktop) SetDeadline(v time.Time)`

SetDeadline sets Deadline field to given value.

### HasDeadline

`func (o *Desktop) HasDeadline() bool`

HasDeadline returns a boolean if a field has been set.

### GetFrameUrl

`func (o *Desktop) GetFrameUrl() string`

GetFrameUrl returns the FrameUrl field if non-nil, zero value otherwise.

### GetFrameUrlOk

`func (o *Desktop) GetFrameUrlOk() (*string, bool)`

GetFrameUrlOk returns a tuple with the FrameUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrameUrl

`func (o *Desktop) SetFrameUrl(v string)`

SetFrameUrl sets FrameUrl field to given value.

### HasFrameUrl

`func (o *Desktop) HasFrameUrl() bool`

HasFrameUrl returns a boolean if a field has been set.

### GetHasReplay

`func (o *Desktop) GetHasReplay() bool`

GetHasReplay returns the HasReplay field if non-nil, zero value otherwise.

### GetHasReplayOk

`func (o *Desktop) GetHasReplayOk() (*bool, bool)`

GetHasReplayOk returns a tuple with the HasReplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasReplay

`func (o *Desktop) SetHasReplay(v bool)`

SetHasReplay sets HasReplay field to given value.


### GetHasScreenshot

`func (o *Desktop) GetHasScreenshot() bool`

GetHasScreenshot returns the HasScreenshot field if non-nil, zero value otherwise.

### GetHasScreenshotOk

`func (o *Desktop) GetHasScreenshotOk() (*bool, bool)`

GetHasScreenshotOk returns a tuple with the HasScreenshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasScreenshot

`func (o *Desktop) SetHasScreenshot(v bool)`

SetHasScreenshot sets HasScreenshot field to given value.


### GetId

`func (o *Desktop) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Desktop) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Desktop) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *Desktop) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Desktop) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Desktop) SetKind(v string)`

SetKind sets Kind field to given value.


### GetState

`func (o *Desktop) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Desktop) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Desktop) SetState(v string)`

SetState sets State field to given value.


### GetTaskId

`func (o *Desktop) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *Desktop) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *Desktop) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.

### HasTaskId

`func (o *Desktop) HasTaskId() bool`

HasTaskId returns a boolean if a field has been set.

### SetTaskIdNil

`func (o *Desktop) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *Desktop) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTitle

`func (o *Desktop) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Desktop) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Desktop) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Desktop) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *Desktop) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *Desktop) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


