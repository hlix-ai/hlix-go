# ProjectStatusSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attention** | [**[]AgencyOverviewReportAttentionInnerAttentionItem**](AgencyOverviewReportAttentionInnerAttentionItem.md) |  |
**CurrentCycle** | [**NullableProjectStatusSummaryCurrentCycle**](ProjectStatusSummaryCurrentCycle.md) |  |
**Cycles** | [**[]ProjectStatusSummaryCyclesInner**](ProjectStatusSummaryCyclesInner.md) |  |
**Declined** | [**[]ProjectStatusSummaryDeclinedInner**](ProjectStatusSummaryDeclinedInner.md) |  |
**Delivery** | [**ProjectStatusSummaryDelivery**](ProjectStatusSummaryDelivery.md) |  |
**LastActivityAt** | **NullableString** |  |
**NeedsYou** | [**[]ProjectStatusSummaryNeedsYouInner**](ProjectStatusSummaryNeedsYouInner.md) |  |
**PauseReason** | **NullableString** |  |
**PausedReason** | **NullableString** |  |
**PendingProposals** | **float32** |  |
**PreviewUrl** | **NullableString** |  |
**Progress** | [**ProjectStatusSummaryProgress**](ProjectStatusSummaryProgress.md) |  |
**Project** | [**HlixCodeModelsModelsInner**](HlixCodeModelsModelsInner.md) |  |
**Status** | **string** |  |

## Methods

### NewProjectStatusSummary

`func NewProjectStatusSummary(attention []AgencyOverviewReportAttentionInnerAttentionItem, currentCycle NullableProjectStatusSummaryCurrentCycle, cycles []ProjectStatusSummaryCyclesInner, declined []ProjectStatusSummaryDeclinedInner, delivery ProjectStatusSummaryDelivery, lastActivityAt NullableString, needsYou []ProjectStatusSummaryNeedsYouInner, pauseReason NullableString, pausedReason NullableString, pendingProposals float32, previewUrl NullableString, progress ProjectStatusSummaryProgress, project HlixCodeModelsModelsInner, status string, ) *ProjectStatusSummary`

NewProjectStatusSummary instantiates a new ProjectStatusSummary object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectStatusSummaryWithDefaults

`func NewProjectStatusSummaryWithDefaults() *ProjectStatusSummary`

NewProjectStatusSummaryWithDefaults instantiates a new ProjectStatusSummary object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAttention

`func (o *ProjectStatusSummary) GetAttention() []AgencyOverviewReportAttentionInnerAttentionItem`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *ProjectStatusSummary) GetAttentionOk() (*[]AgencyOverviewReportAttentionInnerAttentionItem, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *ProjectStatusSummary) SetAttention(v []AgencyOverviewReportAttentionInnerAttentionItem)`

SetAttention sets Attention field to given value.


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


### GetPauseReason

`func (o *ProjectStatusSummary) GetPauseReason() string`

GetPauseReason returns the PauseReason field if non-nil, zero value otherwise.

### GetPauseReasonOk

`func (o *ProjectStatusSummary) GetPauseReasonOk() (*string, bool)`

GetPauseReasonOk returns a tuple with the PauseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPauseReason

`func (o *ProjectStatusSummary) SetPauseReason(v string)`

SetPauseReason sets PauseReason field to given value.


### SetPauseReasonNil

`func (o *ProjectStatusSummary) SetPauseReasonNil(b bool)`

 SetPauseReasonNil sets the value for PauseReason to be an explicit nil

### UnsetPauseReason
`func (o *ProjectStatusSummary) UnsetPauseReason()`

UnsetPauseReason ensures that no value is present for PauseReason, not even an explicit nil
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


### GetStatus

`func (o *ProjectStatusSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectStatusSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectStatusSummary) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


