# ProjectBoardProject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attention** | [**[]AgencyOverviewReportAttentionInnerAttentionItem**](AgencyOverviewReportAttentionInnerAttentionItem.md) |  |
**Id** | **string** |  |
**Name** | **string** |  |
**PauseReason** | **NullableString** |  |
**Status** | **string** |  |
**StopState** | **string** |  |

## Methods

### NewProjectBoardProject

`func NewProjectBoardProject(attention []AgencyOverviewReportAttentionInnerAttentionItem, id string, name string, pauseReason NullableString, status string, stopState string, ) *ProjectBoardProject`

NewProjectBoardProject instantiates a new ProjectBoardProject object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectBoardProjectWithDefaults

`func NewProjectBoardProjectWithDefaults() *ProjectBoardProject`

NewProjectBoardProjectWithDefaults instantiates a new ProjectBoardProject object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAttention

`func (o *ProjectBoardProject) GetAttention() []AgencyOverviewReportAttentionInnerAttentionItem`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *ProjectBoardProject) GetAttentionOk() (*[]AgencyOverviewReportAttentionInnerAttentionItem, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *ProjectBoardProject) SetAttention(v []AgencyOverviewReportAttentionInnerAttentionItem)`

SetAttention sets Attention field to given value.


### GetId

`func (o *ProjectBoardProject) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectBoardProject) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectBoardProject) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ProjectBoardProject) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectBoardProject) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectBoardProject) SetName(v string)`

SetName sets Name field to given value.


### GetPauseReason

`func (o *ProjectBoardProject) GetPauseReason() string`

GetPauseReason returns the PauseReason field if non-nil, zero value otherwise.

### GetPauseReasonOk

`func (o *ProjectBoardProject) GetPauseReasonOk() (*string, bool)`

GetPauseReasonOk returns a tuple with the PauseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPauseReason

`func (o *ProjectBoardProject) SetPauseReason(v string)`

SetPauseReason sets PauseReason field to given value.


### SetPauseReasonNil

`func (o *ProjectBoardProject) SetPauseReasonNil(b bool)`

 SetPauseReasonNil sets the value for PauseReason to be an explicit nil

### UnsetPauseReason
`func (o *ProjectBoardProject) UnsetPauseReason()`

UnsetPauseReason ensures that no value is present for PauseReason, not even an explicit nil
### GetStatus

`func (o *ProjectBoardProject) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectBoardProject) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectBoardProject) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopState

`func (o *ProjectBoardProject) GetStopState() string`

GetStopState returns the StopState field if non-nil, zero value otherwise.

### GetStopStateOk

`func (o *ProjectBoardProject) GetStopStateOk() (*string, bool)`

GetStopStateOk returns a tuple with the StopState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopState

`func (o *ProjectBoardProject) SetStopState(v string)`

SetStopState sets StopState field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


