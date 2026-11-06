# Cycle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedUserId** | **NullableString** |  | 
**BaseRef** | **NullableString** |  | 
**BranchSlug** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**CreatedByRunId** | **NullableString** |  | 
**DependsOn** | **[]string** |  | 
**Description** | **string** |  | 
**E2eVideoUrl** | **NullableString** |  | 
**FollowUpOfCycleId** | **NullableString** |  | 
**Id** | **string** |  | 
**Kind** | **string** |  | 
**Lane** | **NullableString** |  | 
**LinearIssueIdentifier** | **NullableString** |  | 
**OrganizationId** | **string** |  | 
**OutcomeSummary** | **NullableString** |  | 
**Persona** | **NullableString** |  | 
**PrUrl** | **NullableString** |  | 
**PreviewBranch** | **NullableString** |  | 
**Priority** | **int32** |  | 
**ProjectId** | **string** |  | 
**RefinedReqs** | **NullableString** |  | 
**ReplannedThroughRun** | **NullableInt32** |  | 
**RepoId** | **NullableString** |  | 
**RequestedByUserId** | **NullableString** |  | 
**Revision** | **int32** |  | 
**RunPin** | [**NullableCycleRunPin**](CycleRunPin.md) |  | 
**Source** | **NullableString** |  | 
**StageHistory** | [**[]CycleStageHistoryInner**](CycleStageHistoryInner.md) |  | 
**Status** | **string** |  | 
**TargetBranch** | **NullableString** |  | 
**TaskTimeoutMinutes** | **int32** |  | 
**Title** | **string** |  | 
**TotalCostMicros** | **NullableInt64** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewCycle

`func NewCycle(assignedUserId NullableString, baseRef NullableString, branchSlug NullableString, createdAt string, createdByRunId NullableString, dependsOn []string, description string, e2eVideoUrl NullableString, followUpOfCycleId NullableString, id string, kind string, lane NullableString, linearIssueIdentifier NullableString, organizationId string, outcomeSummary NullableString, persona NullableString, prUrl NullableString, previewBranch NullableString, priority int32, projectId string, refinedReqs NullableString, replannedThroughRun NullableInt32, repoId NullableString, requestedByUserId NullableString, revision int32, runPin NullableCycleRunPin, source NullableString, stageHistory []CycleStageHistoryInner, status string, targetBranch NullableString, taskTimeoutMinutes int32, title string, totalCostMicros NullableInt64, updatedAt string, ) *Cycle`

NewCycle instantiates a new Cycle object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleWithDefaults

`func NewCycleWithDefaults() *Cycle`

NewCycleWithDefaults instantiates a new Cycle object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedUserId

`func (o *Cycle) GetAssignedUserId() string`

GetAssignedUserId returns the AssignedUserId field if non-nil, zero value otherwise.

### GetAssignedUserIdOk

`func (o *Cycle) GetAssignedUserIdOk() (*string, bool)`

GetAssignedUserIdOk returns a tuple with the AssignedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUserId

`func (o *Cycle) SetAssignedUserId(v string)`

SetAssignedUserId sets AssignedUserId field to given value.


### SetAssignedUserIdNil

`func (o *Cycle) SetAssignedUserIdNil(b bool)`

 SetAssignedUserIdNil sets the value for AssignedUserId to be an explicit nil

### UnsetAssignedUserId
`func (o *Cycle) UnsetAssignedUserId()`

UnsetAssignedUserId ensures that no value is present for AssignedUserId, not even an explicit nil
### GetBaseRef

`func (o *Cycle) GetBaseRef() string`

GetBaseRef returns the BaseRef field if non-nil, zero value otherwise.

### GetBaseRefOk

`func (o *Cycle) GetBaseRefOk() (*string, bool)`

GetBaseRefOk returns a tuple with the BaseRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseRef

`func (o *Cycle) SetBaseRef(v string)`

SetBaseRef sets BaseRef field to given value.


### SetBaseRefNil

`func (o *Cycle) SetBaseRefNil(b bool)`

 SetBaseRefNil sets the value for BaseRef to be an explicit nil

### UnsetBaseRef
`func (o *Cycle) UnsetBaseRef()`

UnsetBaseRef ensures that no value is present for BaseRef, not even an explicit nil
### GetBranchSlug

`func (o *Cycle) GetBranchSlug() string`

GetBranchSlug returns the BranchSlug field if non-nil, zero value otherwise.

### GetBranchSlugOk

`func (o *Cycle) GetBranchSlugOk() (*string, bool)`

GetBranchSlugOk returns a tuple with the BranchSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchSlug

`func (o *Cycle) SetBranchSlug(v string)`

SetBranchSlug sets BranchSlug field to given value.


### SetBranchSlugNil

`func (o *Cycle) SetBranchSlugNil(b bool)`

 SetBranchSlugNil sets the value for BranchSlug to be an explicit nil

### UnsetBranchSlug
`func (o *Cycle) UnsetBranchSlug()`

UnsetBranchSlug ensures that no value is present for BranchSlug, not even an explicit nil
### GetCreatedAt

`func (o *Cycle) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Cycle) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Cycle) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedByRunId

`func (o *Cycle) GetCreatedByRunId() string`

GetCreatedByRunId returns the CreatedByRunId field if non-nil, zero value otherwise.

### GetCreatedByRunIdOk

`func (o *Cycle) GetCreatedByRunIdOk() (*string, bool)`

GetCreatedByRunIdOk returns a tuple with the CreatedByRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByRunId

`func (o *Cycle) SetCreatedByRunId(v string)`

SetCreatedByRunId sets CreatedByRunId field to given value.


### SetCreatedByRunIdNil

`func (o *Cycle) SetCreatedByRunIdNil(b bool)`

 SetCreatedByRunIdNil sets the value for CreatedByRunId to be an explicit nil

### UnsetCreatedByRunId
`func (o *Cycle) UnsetCreatedByRunId()`

UnsetCreatedByRunId ensures that no value is present for CreatedByRunId, not even an explicit nil
### GetDependsOn

`func (o *Cycle) GetDependsOn() []string`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *Cycle) GetDependsOnOk() (*[]string, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *Cycle) SetDependsOn(v []string)`

SetDependsOn sets DependsOn field to given value.


### GetDescription

`func (o *Cycle) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Cycle) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Cycle) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetE2eVideoUrl

`func (o *Cycle) GetE2eVideoUrl() string`

GetE2eVideoUrl returns the E2eVideoUrl field if non-nil, zero value otherwise.

### GetE2eVideoUrlOk

`func (o *Cycle) GetE2eVideoUrlOk() (*string, bool)`

GetE2eVideoUrlOk returns a tuple with the E2eVideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetE2eVideoUrl

`func (o *Cycle) SetE2eVideoUrl(v string)`

SetE2eVideoUrl sets E2eVideoUrl field to given value.


### SetE2eVideoUrlNil

`func (o *Cycle) SetE2eVideoUrlNil(b bool)`

 SetE2eVideoUrlNil sets the value for E2eVideoUrl to be an explicit nil

### UnsetE2eVideoUrl
`func (o *Cycle) UnsetE2eVideoUrl()`

UnsetE2eVideoUrl ensures that no value is present for E2eVideoUrl, not even an explicit nil
### GetFollowUpOfCycleId

`func (o *Cycle) GetFollowUpOfCycleId() string`

GetFollowUpOfCycleId returns the FollowUpOfCycleId field if non-nil, zero value otherwise.

### GetFollowUpOfCycleIdOk

`func (o *Cycle) GetFollowUpOfCycleIdOk() (*string, bool)`

GetFollowUpOfCycleIdOk returns a tuple with the FollowUpOfCycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowUpOfCycleId

`func (o *Cycle) SetFollowUpOfCycleId(v string)`

SetFollowUpOfCycleId sets FollowUpOfCycleId field to given value.


### SetFollowUpOfCycleIdNil

`func (o *Cycle) SetFollowUpOfCycleIdNil(b bool)`

 SetFollowUpOfCycleIdNil sets the value for FollowUpOfCycleId to be an explicit nil

### UnsetFollowUpOfCycleId
`func (o *Cycle) UnsetFollowUpOfCycleId()`

UnsetFollowUpOfCycleId ensures that no value is present for FollowUpOfCycleId, not even an explicit nil
### GetId

`func (o *Cycle) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Cycle) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Cycle) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *Cycle) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *Cycle) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *Cycle) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLane

`func (o *Cycle) GetLane() string`

GetLane returns the Lane field if non-nil, zero value otherwise.

### GetLaneOk

`func (o *Cycle) GetLaneOk() (*string, bool)`

GetLaneOk returns a tuple with the Lane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLane

`func (o *Cycle) SetLane(v string)`

SetLane sets Lane field to given value.


### SetLaneNil

`func (o *Cycle) SetLaneNil(b bool)`

 SetLaneNil sets the value for Lane to be an explicit nil

### UnsetLane
`func (o *Cycle) UnsetLane()`

UnsetLane ensures that no value is present for Lane, not even an explicit nil
### GetLinearIssueIdentifier

`func (o *Cycle) GetLinearIssueIdentifier() string`

GetLinearIssueIdentifier returns the LinearIssueIdentifier field if non-nil, zero value otherwise.

### GetLinearIssueIdentifierOk

`func (o *Cycle) GetLinearIssueIdentifierOk() (*string, bool)`

GetLinearIssueIdentifierOk returns a tuple with the LinearIssueIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueIdentifier

`func (o *Cycle) SetLinearIssueIdentifier(v string)`

SetLinearIssueIdentifier sets LinearIssueIdentifier field to given value.


### SetLinearIssueIdentifierNil

`func (o *Cycle) SetLinearIssueIdentifierNil(b bool)`

 SetLinearIssueIdentifierNil sets the value for LinearIssueIdentifier to be an explicit nil

### UnsetLinearIssueIdentifier
`func (o *Cycle) UnsetLinearIssueIdentifier()`

UnsetLinearIssueIdentifier ensures that no value is present for LinearIssueIdentifier, not even an explicit nil
### GetOrganizationId

`func (o *Cycle) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Cycle) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Cycle) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOutcomeSummary

`func (o *Cycle) GetOutcomeSummary() string`

GetOutcomeSummary returns the OutcomeSummary field if non-nil, zero value otherwise.

### GetOutcomeSummaryOk

`func (o *Cycle) GetOutcomeSummaryOk() (*string, bool)`

GetOutcomeSummaryOk returns a tuple with the OutcomeSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcomeSummary

`func (o *Cycle) SetOutcomeSummary(v string)`

SetOutcomeSummary sets OutcomeSummary field to given value.


### SetOutcomeSummaryNil

`func (o *Cycle) SetOutcomeSummaryNil(b bool)`

 SetOutcomeSummaryNil sets the value for OutcomeSummary to be an explicit nil

### UnsetOutcomeSummary
`func (o *Cycle) UnsetOutcomeSummary()`

UnsetOutcomeSummary ensures that no value is present for OutcomeSummary, not even an explicit nil
### GetPersona

`func (o *Cycle) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *Cycle) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *Cycle) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *Cycle) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *Cycle) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetPrUrl

`func (o *Cycle) GetPrUrl() string`

GetPrUrl returns the PrUrl field if non-nil, zero value otherwise.

### GetPrUrlOk

`func (o *Cycle) GetPrUrlOk() (*string, bool)`

GetPrUrlOk returns a tuple with the PrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrUrl

`func (o *Cycle) SetPrUrl(v string)`

SetPrUrl sets PrUrl field to given value.


### SetPrUrlNil

`func (o *Cycle) SetPrUrlNil(b bool)`

 SetPrUrlNil sets the value for PrUrl to be an explicit nil

### UnsetPrUrl
`func (o *Cycle) UnsetPrUrl()`

UnsetPrUrl ensures that no value is present for PrUrl, not even an explicit nil
### GetPreviewBranch

`func (o *Cycle) GetPreviewBranch() string`

GetPreviewBranch returns the PreviewBranch field if non-nil, zero value otherwise.

### GetPreviewBranchOk

`func (o *Cycle) GetPreviewBranchOk() (*string, bool)`

GetPreviewBranchOk returns a tuple with the PreviewBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewBranch

`func (o *Cycle) SetPreviewBranch(v string)`

SetPreviewBranch sets PreviewBranch field to given value.


### SetPreviewBranchNil

`func (o *Cycle) SetPreviewBranchNil(b bool)`

 SetPreviewBranchNil sets the value for PreviewBranch to be an explicit nil

### UnsetPreviewBranch
`func (o *Cycle) UnsetPreviewBranch()`

UnsetPreviewBranch ensures that no value is present for PreviewBranch, not even an explicit nil
### GetPriority

`func (o *Cycle) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *Cycle) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *Cycle) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetProjectId

`func (o *Cycle) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Cycle) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Cycle) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRefinedReqs

`func (o *Cycle) GetRefinedReqs() string`

GetRefinedReqs returns the RefinedReqs field if non-nil, zero value otherwise.

### GetRefinedReqsOk

`func (o *Cycle) GetRefinedReqsOk() (*string, bool)`

GetRefinedReqsOk returns a tuple with the RefinedReqs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefinedReqs

`func (o *Cycle) SetRefinedReqs(v string)`

SetRefinedReqs sets RefinedReqs field to given value.


### SetRefinedReqsNil

`func (o *Cycle) SetRefinedReqsNil(b bool)`

 SetRefinedReqsNil sets the value for RefinedReqs to be an explicit nil

### UnsetRefinedReqs
`func (o *Cycle) UnsetRefinedReqs()`

UnsetRefinedReqs ensures that no value is present for RefinedReqs, not even an explicit nil
### GetReplannedThroughRun

`func (o *Cycle) GetReplannedThroughRun() int32`

GetReplannedThroughRun returns the ReplannedThroughRun field if non-nil, zero value otherwise.

### GetReplannedThroughRunOk

`func (o *Cycle) GetReplannedThroughRunOk() (*int32, bool)`

GetReplannedThroughRunOk returns a tuple with the ReplannedThroughRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplannedThroughRun

`func (o *Cycle) SetReplannedThroughRun(v int32)`

SetReplannedThroughRun sets ReplannedThroughRun field to given value.


### SetReplannedThroughRunNil

`func (o *Cycle) SetReplannedThroughRunNil(b bool)`

 SetReplannedThroughRunNil sets the value for ReplannedThroughRun to be an explicit nil

### UnsetReplannedThroughRun
`func (o *Cycle) UnsetReplannedThroughRun()`

UnsetReplannedThroughRun ensures that no value is present for ReplannedThroughRun, not even an explicit nil
### GetRepoId

`func (o *Cycle) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *Cycle) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *Cycle) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.


### SetRepoIdNil

`func (o *Cycle) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *Cycle) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetRequestedByUserId

`func (o *Cycle) GetRequestedByUserId() string`

GetRequestedByUserId returns the RequestedByUserId field if non-nil, zero value otherwise.

### GetRequestedByUserIdOk

`func (o *Cycle) GetRequestedByUserIdOk() (*string, bool)`

GetRequestedByUserIdOk returns a tuple with the RequestedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedByUserId

`func (o *Cycle) SetRequestedByUserId(v string)`

SetRequestedByUserId sets RequestedByUserId field to given value.


### SetRequestedByUserIdNil

`func (o *Cycle) SetRequestedByUserIdNil(b bool)`

 SetRequestedByUserIdNil sets the value for RequestedByUserId to be an explicit nil

### UnsetRequestedByUserId
`func (o *Cycle) UnsetRequestedByUserId()`

UnsetRequestedByUserId ensures that no value is present for RequestedByUserId, not even an explicit nil
### GetRevision

`func (o *Cycle) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *Cycle) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *Cycle) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetRunPin

`func (o *Cycle) GetRunPin() CycleRunPin`

GetRunPin returns the RunPin field if non-nil, zero value otherwise.

### GetRunPinOk

`func (o *Cycle) GetRunPinOk() (*CycleRunPin, bool)`

GetRunPinOk returns a tuple with the RunPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunPin

`func (o *Cycle) SetRunPin(v CycleRunPin)`

SetRunPin sets RunPin field to given value.


### SetRunPinNil

`func (o *Cycle) SetRunPinNil(b bool)`

 SetRunPinNil sets the value for RunPin to be an explicit nil

### UnsetRunPin
`func (o *Cycle) UnsetRunPin()`

UnsetRunPin ensures that no value is present for RunPin, not even an explicit nil
### GetSource

`func (o *Cycle) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Cycle) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Cycle) SetSource(v string)`

SetSource sets Source field to given value.


### SetSourceNil

`func (o *Cycle) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *Cycle) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetStageHistory

`func (o *Cycle) GetStageHistory() []CycleStageHistoryInner`

GetStageHistory returns the StageHistory field if non-nil, zero value otherwise.

### GetStageHistoryOk

`func (o *Cycle) GetStageHistoryOk() (*[]CycleStageHistoryInner, bool)`

GetStageHistoryOk returns a tuple with the StageHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageHistory

`func (o *Cycle) SetStageHistory(v []CycleStageHistoryInner)`

SetStageHistory sets StageHistory field to given value.


### GetStatus

`func (o *Cycle) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Cycle) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Cycle) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTargetBranch

`func (o *Cycle) GetTargetBranch() string`

GetTargetBranch returns the TargetBranch field if non-nil, zero value otherwise.

### GetTargetBranchOk

`func (o *Cycle) GetTargetBranchOk() (*string, bool)`

GetTargetBranchOk returns a tuple with the TargetBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetBranch

`func (o *Cycle) SetTargetBranch(v string)`

SetTargetBranch sets TargetBranch field to given value.


### SetTargetBranchNil

`func (o *Cycle) SetTargetBranchNil(b bool)`

 SetTargetBranchNil sets the value for TargetBranch to be an explicit nil

### UnsetTargetBranch
`func (o *Cycle) UnsetTargetBranch()`

UnsetTargetBranch ensures that no value is present for TargetBranch, not even an explicit nil
### GetTaskTimeoutMinutes

`func (o *Cycle) GetTaskTimeoutMinutes() int32`

GetTaskTimeoutMinutes returns the TaskTimeoutMinutes field if non-nil, zero value otherwise.

### GetTaskTimeoutMinutesOk

`func (o *Cycle) GetTaskTimeoutMinutesOk() (*int32, bool)`

GetTaskTimeoutMinutesOk returns a tuple with the TaskTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskTimeoutMinutes

`func (o *Cycle) SetTaskTimeoutMinutes(v int32)`

SetTaskTimeoutMinutes sets TaskTimeoutMinutes field to given value.


### GetTitle

`func (o *Cycle) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Cycle) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Cycle) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTotalCostMicros

`func (o *Cycle) GetTotalCostMicros() int64`

GetTotalCostMicros returns the TotalCostMicros field if non-nil, zero value otherwise.

### GetTotalCostMicrosOk

`func (o *Cycle) GetTotalCostMicrosOk() (*int64, bool)`

GetTotalCostMicrosOk returns a tuple with the TotalCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCostMicros

`func (o *Cycle) SetTotalCostMicros(v int64)`

SetTotalCostMicros sets TotalCostMicros field to given value.


### SetTotalCostMicrosNil

`func (o *Cycle) SetTotalCostMicrosNil(b bool)`

 SetTotalCostMicrosNil sets the value for TotalCostMicros to be an explicit nil

### UnsetTotalCostMicros
`func (o *Cycle) UnsetTotalCostMicros()`

UnsetTotalCostMicros ensures that no value is present for TotalCostMicros, not even an explicit nil
### GetUpdatedAt

`func (o *Cycle) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Cycle) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Cycle) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


