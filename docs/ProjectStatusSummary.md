# ProjectStatusSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentCycle** | [**NullableProjectStatusSummaryCurrentCycle**](ProjectStatusSummaryCurrentCycle.md) |  | 
**Cycles** | [**[]ProjectStatusSummaryCyclesInner**](ProjectStatusSummaryCyclesInner.md) |  | 
**Declined** | [**[]ProjectStatusSummaryDeclinedInner**](ProjectStatusSummaryDeclinedInner.md) |  | 
**Delivery** | [**ProjectStatusSummaryDelivery**](ProjectStatusSummaryDelivery.md) |  | 
**LastActivityAt** | **NullableString** |  | 
**NeedsYou** | [**[]ProjectStatusSummaryNeedsYouInner**](ProjectStatusSummaryNeedsYouInner.md) |  | 
**PausedReason** | **NullableString** |  | 
**PendingProposals** | **float32** |  | 
**Phase** | **string** |  | 
**PreviewUrl** | **NullableString** |  | 
**Progress** | [**ProjectStatusSummaryProgress**](ProjectStatusSummaryProgress.md) |  | 
**Project** | [**HlixCodeModelsModelsInner**](HlixCodeModelsModelsInner.md) |  | 

## Methods

### NewProjectStatusSummary

`func NewProjectStatusSummary(currentCycle NullableProjectStatusSummaryCurrentCycle, cycles []ProjectStatusSummaryCyclesInner, declined []ProjectStatusSummaryDeclinedInner, delivery ProjectStatusSummaryDelivery, lastActivityAt NullableString, needsYou []ProjectStatusSummaryNeedsYouInner, pausedReason NullableString, pendingProposals float32, phase string, previewUrl NullableString, progress ProjectStatusSummaryProgress, project HlixCodeModelsModelsInner, ) *ProjectStatusSummary`

NewProjectStatusSummary instantiates a new ProjectStatusSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectStatusSummaryWithDefaults

`func NewProjectStatusSummaryWithDefaults() *ProjectStatusSummary`

NewProjectStatusSummaryWithDefaults instantiates a new ProjectStatusSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentCycle

`func (o *ProjectStatusSummary) GetCurrentCycle() ProjectStatusSummaryCurrentCycle`

GetCurrentCycle returns the CurrentCycle field if non-nil, zero value otherwise.

### GetCurrentCycleOk

`func (o *ProjectStatusSummary) GetCurrentCycleOk() (*ProjectStatusSummaryCurrentCycle, bool)`

GetCurrentCycleOk returns a tuple with the CurrentCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCycle

`func (o *ProjectStatusSummary) SetCurrentCycle(v ProjectStatusSummaryCurrentCycle)`

SetCurrentCycle sets CurrentCycle field to given value.


### SetCurrentCycleNil

`func (o *ProjectStatusSummary) SetCurrentCycleNil(b bool)`

 SetCurrentCycleNil sets the value for CurrentCycle to be an explicit nil

### UnsetCurrentCycle
`func (o *ProjectStatusSummary) UnsetCurrentCycle()`

UnsetCurrentCycle ensures that no value is present for CurrentCycle, not even an explicit nil
### GetCycles

`func (o *ProjectStatusSummary) GetCycles() []ProjectStatusSummaryCyclesInner`

GetCycles returns the Cycles field if non-nil, zero value otherwise.

### GetCyclesOk

`func (o *ProjectStatusSummary) GetCyclesOk() (*[]ProjectStatusSummaryCyclesInner, bool)`

GetCyclesOk returns a tuple with the Cycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycles

`func (o *ProjectStatusSummary) SetCycles(v []ProjectStatusSummaryCyclesInner)`

SetCycles sets Cycles field to given value.


### GetDeclined

`func (o *ProjectStatusSummary) GetDeclined() []ProjectStatusSummaryDeclinedInner`

GetDeclined returns the Declined field if non-nil, zero value otherwise.

### GetDeclinedOk

`func (o *ProjectStatusSummary) GetDeclinedOk() (*[]ProjectStatusSummaryDeclinedInner, bool)`

GetDeclinedOk returns a tuple with the Declined field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeclined

`func (o *ProjectStatusSummary) SetDeclined(v []ProjectStatusSummaryDeclinedInner)`

SetDeclined sets Declined field to given value.


### GetDelivery

`func (o *ProjectStatusSummary) GetDelivery() ProjectStatusSummaryDelivery`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *ProjectStatusSummary) GetDeliveryOk() (*ProjectStatusSummaryDelivery, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *ProjectStatusSummary) SetDelivery(v ProjectStatusSummaryDelivery)`

SetDelivery sets Delivery field to given value.


### GetLastActivityAt

`func (o *ProjectStatusSummary) GetLastActivityAt() string`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *ProjectStatusSummary) GetLastActivityAtOk() (*string, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *ProjectStatusSummary) SetLastActivityAt(v string)`

SetLastActivityAt sets LastActivityAt field to given value.


### SetLastActivityAtNil

`func (o *ProjectStatusSummary) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *ProjectStatusSummary) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetNeedsYou

`func (o *ProjectStatusSummary) GetNeedsYou() []ProjectStatusSummaryNeedsYouInner`

GetNeedsYou returns the NeedsYou field if non-nil, zero value otherwise.

### GetNeedsYouOk

`func (o *ProjectStatusSummary) GetNeedsYouOk() (*[]ProjectStatusSummaryNeedsYouInner, bool)`

GetNeedsYouOk returns a tuple with the NeedsYou field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeedsYou

`func (o *ProjectStatusSummary) SetNeedsYou(v []ProjectStatusSummaryNeedsYouInner)`

SetNeedsYou sets NeedsYou field to given value.


### GetPausedReason

`func (o *ProjectStatusSummary) GetPausedReason() string`

GetPausedReason returns the PausedReason field if non-nil, zero value otherwise.

### GetPausedReasonOk

`func (o *ProjectStatusSummary) GetPausedReasonOk() (*string, bool)`

GetPausedReasonOk returns a tuple with the PausedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedReason

`func (o *ProjectStatusSummary) SetPausedReason(v string)`

SetPausedReason sets PausedReason field to given value.


### SetPausedReasonNil

`func (o *ProjectStatusSummary) SetPausedReasonNil(b bool)`

 SetPausedReasonNil sets the value for PausedReason to be an explicit nil

### UnsetPausedReason
`func (o *ProjectStatusSummary) UnsetPausedReason()`

UnsetPausedReason ensures that no value is present for PausedReason, not even an explicit nil
### GetPendingProposals

`func (o *ProjectStatusSummary) GetPendingProposals() float32`

GetPendingProposals returns the PendingProposals field if non-nil, zero value otherwise.

### GetPendingProposalsOk

`func (o *ProjectStatusSummary) GetPendingProposalsOk() (*float32, bool)`

GetPendingProposalsOk returns a tuple with the PendingProposals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingProposals

`func (o *ProjectStatusSummary) SetPendingProposals(v float32)`

SetPendingProposals sets PendingProposals field to given value.


### GetPhase

`func (o *ProjectStatusSummary) GetPhase() string`

GetPhase returns the Phase field if non-nil, zero value otherwise.

### GetPhaseOk

`func (o *ProjectStatusSummary) GetPhaseOk() (*string, bool)`

GetPhaseOk returns a tuple with the Phase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhase

`func (o *ProjectStatusSummary) SetPhase(v string)`

SetPhase sets Phase field to given value.


### GetPreviewUrl

`func (o *ProjectStatusSummary) GetPreviewUrl() string`

GetPreviewUrl returns the PreviewUrl field if non-nil, zero value otherwise.

### GetPreviewUrlOk

`func (o *ProjectStatusSummary) GetPreviewUrlOk() (*string, bool)`

GetPreviewUrlOk returns a tuple with the PreviewUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewUrl

`func (o *ProjectStatusSummary) SetPreviewUrl(v string)`

SetPreviewUrl sets PreviewUrl field to given value.


### SetPreviewUrlNil

`func (o *ProjectStatusSummary) SetPreviewUrlNil(b bool)`

 SetPreviewUrlNil sets the value for PreviewUrl to be an explicit nil

### UnsetPreviewUrl
`func (o *ProjectStatusSummary) UnsetPreviewUrl()`

UnsetPreviewUrl ensures that no value is present for PreviewUrl, not even an explicit nil
### GetProgress

`func (o *ProjectStatusSummary) GetProgress() ProjectStatusSummaryProgress`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *ProjectStatusSummary) GetProgressOk() (*ProjectStatusSummaryProgress, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *ProjectStatusSummary) SetProgress(v ProjectStatusSummaryProgress)`

SetProgress sets Progress field to given value.


### GetProject

`func (o *ProjectStatusSummary) GetProject() HlixCodeModelsModelsInner`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectStatusSummary) GetProjectOk() (*HlixCodeModelsModelsInner, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectStatusSummary) SetProject(v HlixCodeModelsModelsInner)`

SetProject sets Project field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


