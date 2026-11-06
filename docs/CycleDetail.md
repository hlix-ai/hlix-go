# CycleDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedUserId** | **NullableString** |  | 
**BaseRef** | **NullableString** |  | 
**BranchSlug** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**CreatedByRun** | [**NullableCycleDetailCreatedByRun**](CycleDetailCreatedByRun.md) |  | 
**CreatedByRunId** | **NullableString** |  | 
**DependsOn** | **[]string** |  | 
**Description** | **string** |  | 
**E2eVideoUrl** | **NullableString** |  | 
**FollowUpOfCycleId** | **NullableString** |  | 
**Id** | **string** |  | 
**Kind** | **string** |  | 
**Lane** | **NullableString** |  | 
**LinearIssueIdentifier** | **NullableString** |  | 
**LinearIssueUrl** | **NullableString** |  | 
**OrganizationId** | **string** |  | 
**OutcomeSummary** | **NullableString** |  | 
**Persona** | **NullableString** |  | 
**PrUrl** | **NullableString** |  | 
**PreviewBranch** | **NullableString** |  | 
**PreviewUrl** | **NullableString** |  | 
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
**Tasks** | [**[]CycleDetailTasksInner**](CycleDetailTasksInner.md) |  | 
**Title** | **string** |  | 
**TotalCostMicros** | **NullableInt64** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewCycleDetail

`func NewCycleDetail(assignedUserId NullableString, baseRef NullableString, branchSlug NullableString, createdAt string, createdByRun NullableCycleDetailCreatedByRun, createdByRunId NullableString, dependsOn []string, description string, e2eVideoUrl NullableString, followUpOfCycleId NullableString, id string, kind string, lane NullableString, linearIssueIdentifier NullableString, linearIssueUrl NullableString, organizationId string, outcomeSummary NullableString, persona NullableString, prUrl NullableString, previewBranch NullableString, previewUrl NullableString, priority int32, projectId string, refinedReqs NullableString, replannedThroughRun NullableInt32, repoId NullableString, requestedByUserId NullableString, revision int32, runPin NullableCycleRunPin, source NullableString, stageHistory []CycleStageHistoryInner, status string, targetBranch NullableString, taskTimeoutMinutes int32, tasks []CycleDetailTasksInner, title string, totalCostMicros NullableInt64, updatedAt string, ) *CycleDetail`

NewCycleDetail instantiates a new CycleDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleDetailWithDefaults

`func NewCycleDetailWithDefaults() *CycleDetail`

NewCycleDetailWithDefaults instantiates a new CycleDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssignedUserId

`func (o *CycleDetail) GetAssignedUserId() string`

GetAssignedUserId returns the AssignedUserId field if non-nil, zero value otherwise.

### GetAssignedUserIdOk

`func (o *CycleDetail) GetAssignedUserIdOk() (*string, bool)`

GetAssignedUserIdOk returns a tuple with the AssignedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUserId

`func (o *CycleDetail) SetAssignedUserId(v string)`

SetAssignedUserId sets AssignedUserId field to given value.


### SetAssignedUserIdNil

`func (o *CycleDetail) SetAssignedUserIdNil(b bool)`

 SetAssignedUserIdNil sets the value for AssignedUserId to be an explicit nil

### UnsetAssignedUserId
`func (o *CycleDetail) UnsetAssignedUserId()`

UnsetAssignedUserId ensures that no value is present for AssignedUserId, not even an explicit nil
### GetBaseRef

`func (o *CycleDetail) GetBaseRef() string`

GetBaseRef returns the BaseRef field if non-nil, zero value otherwise.

### GetBaseRefOk

`func (o *CycleDetail) GetBaseRefOk() (*string, bool)`

GetBaseRefOk returns a tuple with the BaseRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseRef

`func (o *CycleDetail) SetBaseRef(v string)`

SetBaseRef sets BaseRef field to given value.


### SetBaseRefNil

`func (o *CycleDetail) SetBaseRefNil(b bool)`

 SetBaseRefNil sets the value for BaseRef to be an explicit nil

### UnsetBaseRef
`func (o *CycleDetail) UnsetBaseRef()`

UnsetBaseRef ensures that no value is present for BaseRef, not even an explicit nil
### GetBranchSlug

`func (o *CycleDetail) GetBranchSlug() string`

GetBranchSlug returns the BranchSlug field if non-nil, zero value otherwise.

### GetBranchSlugOk

`func (o *CycleDetail) GetBranchSlugOk() (*string, bool)`

GetBranchSlugOk returns a tuple with the BranchSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchSlug

`func (o *CycleDetail) SetBranchSlug(v string)`

SetBranchSlug sets BranchSlug field to given value.


### SetBranchSlugNil

`func (o *CycleDetail) SetBranchSlugNil(b bool)`

 SetBranchSlugNil sets the value for BranchSlug to be an explicit nil

### UnsetBranchSlug
`func (o *CycleDetail) UnsetBranchSlug()`

UnsetBranchSlug ensures that no value is present for BranchSlug, not even an explicit nil
### GetCreatedAt

`func (o *CycleDetail) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CycleDetail) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CycleDetail) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedByRun

`func (o *CycleDetail) GetCreatedByRun() CycleDetailCreatedByRun`

GetCreatedByRun returns the CreatedByRun field if non-nil, zero value otherwise.

### GetCreatedByRunOk

`func (o *CycleDetail) GetCreatedByRunOk() (*CycleDetailCreatedByRun, bool)`

GetCreatedByRunOk returns a tuple with the CreatedByRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByRun

`func (o *CycleDetail) SetCreatedByRun(v CycleDetailCreatedByRun)`

SetCreatedByRun sets CreatedByRun field to given value.


### SetCreatedByRunNil

`func (o *CycleDetail) SetCreatedByRunNil(b bool)`

 SetCreatedByRunNil sets the value for CreatedByRun to be an explicit nil

### UnsetCreatedByRun
`func (o *CycleDetail) UnsetCreatedByRun()`

UnsetCreatedByRun ensures that no value is present for CreatedByRun, not even an explicit nil
### GetCreatedByRunId

`func (o *CycleDetail) GetCreatedByRunId() string`

GetCreatedByRunId returns the CreatedByRunId field if non-nil, zero value otherwise.

### GetCreatedByRunIdOk

`func (o *CycleDetail) GetCreatedByRunIdOk() (*string, bool)`

GetCreatedByRunIdOk returns a tuple with the CreatedByRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByRunId

`func (o *CycleDetail) SetCreatedByRunId(v string)`

SetCreatedByRunId sets CreatedByRunId field to given value.


### SetCreatedByRunIdNil

`func (o *CycleDetail) SetCreatedByRunIdNil(b bool)`

 SetCreatedByRunIdNil sets the value for CreatedByRunId to be an explicit nil

### UnsetCreatedByRunId
`func (o *CycleDetail) UnsetCreatedByRunId()`

UnsetCreatedByRunId ensures that no value is present for CreatedByRunId, not even an explicit nil
### GetDependsOn

`func (o *CycleDetail) GetDependsOn() []string`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *CycleDetail) GetDependsOnOk() (*[]string, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *CycleDetail) SetDependsOn(v []string)`

SetDependsOn sets DependsOn field to given value.


### GetDescription

`func (o *CycleDetail) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CycleDetail) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CycleDetail) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetE2eVideoUrl

`func (o *CycleDetail) GetE2eVideoUrl() string`

GetE2eVideoUrl returns the E2eVideoUrl field if non-nil, zero value otherwise.

### GetE2eVideoUrlOk

`func (o *CycleDetail) GetE2eVideoUrlOk() (*string, bool)`

GetE2eVideoUrlOk returns a tuple with the E2eVideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetE2eVideoUrl

`func (o *CycleDetail) SetE2eVideoUrl(v string)`

SetE2eVideoUrl sets E2eVideoUrl field to given value.


### SetE2eVideoUrlNil

`func (o *CycleDetail) SetE2eVideoUrlNil(b bool)`

 SetE2eVideoUrlNil sets the value for E2eVideoUrl to be an explicit nil

### UnsetE2eVideoUrl
`func (o *CycleDetail) UnsetE2eVideoUrl()`

UnsetE2eVideoUrl ensures that no value is present for E2eVideoUrl, not even an explicit nil
### GetFollowUpOfCycleId

`func (o *CycleDetail) GetFollowUpOfCycleId() string`

GetFollowUpOfCycleId returns the FollowUpOfCycleId field if non-nil, zero value otherwise.

### GetFollowUpOfCycleIdOk

`func (o *CycleDetail) GetFollowUpOfCycleIdOk() (*string, bool)`

GetFollowUpOfCycleIdOk returns a tuple with the FollowUpOfCycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowUpOfCycleId

`func (o *CycleDetail) SetFollowUpOfCycleId(v string)`

SetFollowUpOfCycleId sets FollowUpOfCycleId field to given value.


### SetFollowUpOfCycleIdNil

`func (o *CycleDetail) SetFollowUpOfCycleIdNil(b bool)`

 SetFollowUpOfCycleIdNil sets the value for FollowUpOfCycleId to be an explicit nil

### UnsetFollowUpOfCycleId
`func (o *CycleDetail) UnsetFollowUpOfCycleId()`

UnsetFollowUpOfCycleId ensures that no value is present for FollowUpOfCycleId, not even an explicit nil
### GetId

`func (o *CycleDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CycleDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CycleDetail) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *CycleDetail) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CycleDetail) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CycleDetail) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLane

`func (o *CycleDetail) GetLane() string`

GetLane returns the Lane field if non-nil, zero value otherwise.

### GetLaneOk

`func (o *CycleDetail) GetLaneOk() (*string, bool)`

GetLaneOk returns a tuple with the Lane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLane

`func (o *CycleDetail) SetLane(v string)`

SetLane sets Lane field to given value.


### SetLaneNil

`func (o *CycleDetail) SetLaneNil(b bool)`

 SetLaneNil sets the value for Lane to be an explicit nil

### UnsetLane
`func (o *CycleDetail) UnsetLane()`

UnsetLane ensures that no value is present for Lane, not even an explicit nil
### GetLinearIssueIdentifier

`func (o *CycleDetail) GetLinearIssueIdentifier() string`

GetLinearIssueIdentifier returns the LinearIssueIdentifier field if non-nil, zero value otherwise.

### GetLinearIssueIdentifierOk

`func (o *CycleDetail) GetLinearIssueIdentifierOk() (*string, bool)`

GetLinearIssueIdentifierOk returns a tuple with the LinearIssueIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueIdentifier

`func (o *CycleDetail) SetLinearIssueIdentifier(v string)`

SetLinearIssueIdentifier sets LinearIssueIdentifier field to given value.


### SetLinearIssueIdentifierNil

`func (o *CycleDetail) SetLinearIssueIdentifierNil(b bool)`

 SetLinearIssueIdentifierNil sets the value for LinearIssueIdentifier to be an explicit nil

### UnsetLinearIssueIdentifier
`func (o *CycleDetail) UnsetLinearIssueIdentifier()`

UnsetLinearIssueIdentifier ensures that no value is present for LinearIssueIdentifier, not even an explicit nil
### GetLinearIssueUrl

`func (o *CycleDetail) GetLinearIssueUrl() string`

GetLinearIssueUrl returns the LinearIssueUrl field if non-nil, zero value otherwise.

### GetLinearIssueUrlOk

`func (o *CycleDetail) GetLinearIssueUrlOk() (*string, bool)`

GetLinearIssueUrlOk returns a tuple with the LinearIssueUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueUrl

`func (o *CycleDetail) SetLinearIssueUrl(v string)`

SetLinearIssueUrl sets LinearIssueUrl field to given value.


### SetLinearIssueUrlNil

`func (o *CycleDetail) SetLinearIssueUrlNil(b bool)`

 SetLinearIssueUrlNil sets the value for LinearIssueUrl to be an explicit nil

### UnsetLinearIssueUrl
`func (o *CycleDetail) UnsetLinearIssueUrl()`

UnsetLinearIssueUrl ensures that no value is present for LinearIssueUrl, not even an explicit nil
### GetOrganizationId

`func (o *CycleDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CycleDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CycleDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOutcomeSummary

`func (o *CycleDetail) GetOutcomeSummary() string`

GetOutcomeSummary returns the OutcomeSummary field if non-nil, zero value otherwise.

### GetOutcomeSummaryOk

`func (o *CycleDetail) GetOutcomeSummaryOk() (*string, bool)`

GetOutcomeSummaryOk returns a tuple with the OutcomeSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcomeSummary

`func (o *CycleDetail) SetOutcomeSummary(v string)`

SetOutcomeSummary sets OutcomeSummary field to given value.


### SetOutcomeSummaryNil

`func (o *CycleDetail) SetOutcomeSummaryNil(b bool)`

 SetOutcomeSummaryNil sets the value for OutcomeSummary to be an explicit nil

### UnsetOutcomeSummary
`func (o *CycleDetail) UnsetOutcomeSummary()`

UnsetOutcomeSummary ensures that no value is present for OutcomeSummary, not even an explicit nil
### GetPersona

`func (o *CycleDetail) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *CycleDetail) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *CycleDetail) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *CycleDetail) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *CycleDetail) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetPrUrl

`func (o *CycleDetail) GetPrUrl() string`

GetPrUrl returns the PrUrl field if non-nil, zero value otherwise.

### GetPrUrlOk

`func (o *CycleDetail) GetPrUrlOk() (*string, bool)`

GetPrUrlOk returns a tuple with the PrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrUrl

`func (o *CycleDetail) SetPrUrl(v string)`

SetPrUrl sets PrUrl field to given value.


### SetPrUrlNil

`func (o *CycleDetail) SetPrUrlNil(b bool)`

 SetPrUrlNil sets the value for PrUrl to be an explicit nil

### UnsetPrUrl
`func (o *CycleDetail) UnsetPrUrl()`

UnsetPrUrl ensures that no value is present for PrUrl, not even an explicit nil
### GetPreviewBranch

`func (o *CycleDetail) GetPreviewBranch() string`

GetPreviewBranch returns the PreviewBranch field if non-nil, zero value otherwise.

### GetPreviewBranchOk

`func (o *CycleDetail) GetPreviewBranchOk() (*string, bool)`

GetPreviewBranchOk returns a tuple with the PreviewBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewBranch

`func (o *CycleDetail) SetPreviewBranch(v string)`

SetPreviewBranch sets PreviewBranch field to given value.


### SetPreviewBranchNil

`func (o *CycleDetail) SetPreviewBranchNil(b bool)`

 SetPreviewBranchNil sets the value for PreviewBranch to be an explicit nil

### UnsetPreviewBranch
`func (o *CycleDetail) UnsetPreviewBranch()`

UnsetPreviewBranch ensures that no value is present for PreviewBranch, not even an explicit nil
### GetPreviewUrl

`func (o *CycleDetail) GetPreviewUrl() string`

GetPreviewUrl returns the PreviewUrl field if non-nil, zero value otherwise.

### GetPreviewUrlOk

`func (o *CycleDetail) GetPreviewUrlOk() (*string, bool)`

GetPreviewUrlOk returns a tuple with the PreviewUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewUrl

`func (o *CycleDetail) SetPreviewUrl(v string)`

SetPreviewUrl sets PreviewUrl field to given value.


### SetPreviewUrlNil

`func (o *CycleDetail) SetPreviewUrlNil(b bool)`

 SetPreviewUrlNil sets the value for PreviewUrl to be an explicit nil

### UnsetPreviewUrl
`func (o *CycleDetail) UnsetPreviewUrl()`

UnsetPreviewUrl ensures that no value is present for PreviewUrl, not even an explicit nil
### GetPriority

`func (o *CycleDetail) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *CycleDetail) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *CycleDetail) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetProjectId

`func (o *CycleDetail) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CycleDetail) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CycleDetail) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRefinedReqs

`func (o *CycleDetail) GetRefinedReqs() string`

GetRefinedReqs returns the RefinedReqs field if non-nil, zero value otherwise.

### GetRefinedReqsOk

`func (o *CycleDetail) GetRefinedReqsOk() (*string, bool)`

GetRefinedReqsOk returns a tuple with the RefinedReqs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefinedReqs

`func (o *CycleDetail) SetRefinedReqs(v string)`

SetRefinedReqs sets RefinedReqs field to given value.


### SetRefinedReqsNil

`func (o *CycleDetail) SetRefinedReqsNil(b bool)`

 SetRefinedReqsNil sets the value for RefinedReqs to be an explicit nil

### UnsetRefinedReqs
`func (o *CycleDetail) UnsetRefinedReqs()`

UnsetRefinedReqs ensures that no value is present for RefinedReqs, not even an explicit nil
### GetReplannedThroughRun

`func (o *CycleDetail) GetReplannedThroughRun() int32`

GetReplannedThroughRun returns the ReplannedThroughRun field if non-nil, zero value otherwise.

### GetReplannedThroughRunOk

`func (o *CycleDetail) GetReplannedThroughRunOk() (*int32, bool)`

GetReplannedThroughRunOk returns a tuple with the ReplannedThroughRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplannedThroughRun

`func (o *CycleDetail) SetReplannedThroughRun(v int32)`

SetReplannedThroughRun sets ReplannedThroughRun field to given value.


### SetReplannedThroughRunNil

`func (o *CycleDetail) SetReplannedThroughRunNil(b bool)`

 SetReplannedThroughRunNil sets the value for ReplannedThroughRun to be an explicit nil

### UnsetReplannedThroughRun
`func (o *CycleDetail) UnsetReplannedThroughRun()`

UnsetReplannedThroughRun ensures that no value is present for ReplannedThroughRun, not even an explicit nil
### GetRepoId

`func (o *CycleDetail) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *CycleDetail) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *CycleDetail) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.


### SetRepoIdNil

`func (o *CycleDetail) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *CycleDetail) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetRequestedByUserId

`func (o *CycleDetail) GetRequestedByUserId() string`

GetRequestedByUserId returns the RequestedByUserId field if non-nil, zero value otherwise.

### GetRequestedByUserIdOk

`func (o *CycleDetail) GetRequestedByUserIdOk() (*string, bool)`

GetRequestedByUserIdOk returns a tuple with the RequestedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedByUserId

`func (o *CycleDetail) SetRequestedByUserId(v string)`

SetRequestedByUserId sets RequestedByUserId field to given value.


### SetRequestedByUserIdNil

`func (o *CycleDetail) SetRequestedByUserIdNil(b bool)`

 SetRequestedByUserIdNil sets the value for RequestedByUserId to be an explicit nil

### UnsetRequestedByUserId
`func (o *CycleDetail) UnsetRequestedByUserId()`

UnsetRequestedByUserId ensures that no value is present for RequestedByUserId, not even an explicit nil
### GetRevision

`func (o *CycleDetail) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CycleDetail) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CycleDetail) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetRunPin

`func (o *CycleDetail) GetRunPin() CycleRunPin`

GetRunPin returns the RunPin field if non-nil, zero value otherwise.

### GetRunPinOk

`func (o *CycleDetail) GetRunPinOk() (*CycleRunPin, bool)`

GetRunPinOk returns a tuple with the RunPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunPin

`func (o *CycleDetail) SetRunPin(v CycleRunPin)`

SetRunPin sets RunPin field to given value.


### SetRunPinNil

`func (o *CycleDetail) SetRunPinNil(b bool)`

 SetRunPinNil sets the value for RunPin to be an explicit nil

### UnsetRunPin
`func (o *CycleDetail) UnsetRunPin()`

UnsetRunPin ensures that no value is present for RunPin, not even an explicit nil
### GetSource

`func (o *CycleDetail) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CycleDetail) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CycleDetail) SetSource(v string)`

SetSource sets Source field to given value.


### SetSourceNil

`func (o *CycleDetail) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *CycleDetail) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetStageHistory

`func (o *CycleDetail) GetStageHistory() []CycleStageHistoryInner`

GetStageHistory returns the StageHistory field if non-nil, zero value otherwise.

### GetStageHistoryOk

`func (o *CycleDetail) GetStageHistoryOk() (*[]CycleStageHistoryInner, bool)`

GetStageHistoryOk returns a tuple with the StageHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageHistory

`func (o *CycleDetail) SetStageHistory(v []CycleStageHistoryInner)`

SetStageHistory sets StageHistory field to given value.


### GetStatus

`func (o *CycleDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleDetail) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTargetBranch

`func (o *CycleDetail) GetTargetBranch() string`

GetTargetBranch returns the TargetBranch field if non-nil, zero value otherwise.

### GetTargetBranchOk

`func (o *CycleDetail) GetTargetBranchOk() (*string, bool)`

GetTargetBranchOk returns a tuple with the TargetBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetBranch

`func (o *CycleDetail) SetTargetBranch(v string)`

SetTargetBranch sets TargetBranch field to given value.


### SetTargetBranchNil

`func (o *CycleDetail) SetTargetBranchNil(b bool)`

 SetTargetBranchNil sets the value for TargetBranch to be an explicit nil

### UnsetTargetBranch
`func (o *CycleDetail) UnsetTargetBranch()`

UnsetTargetBranch ensures that no value is present for TargetBranch, not even an explicit nil
### GetTaskTimeoutMinutes

`func (o *CycleDetail) GetTaskTimeoutMinutes() int32`

GetTaskTimeoutMinutes returns the TaskTimeoutMinutes field if non-nil, zero value otherwise.

### GetTaskTimeoutMinutesOk

`func (o *CycleDetail) GetTaskTimeoutMinutesOk() (*int32, bool)`

GetTaskTimeoutMinutesOk returns a tuple with the TaskTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskTimeoutMinutes

`func (o *CycleDetail) SetTaskTimeoutMinutes(v int32)`

SetTaskTimeoutMinutes sets TaskTimeoutMinutes field to given value.


### GetTasks

`func (o *CycleDetail) GetTasks() []CycleDetailTasksInner`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *CycleDetail) GetTasksOk() (*[]CycleDetailTasksInner, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *CycleDetail) SetTasks(v []CycleDetailTasksInner)`

SetTasks sets Tasks field to given value.


### GetTitle

`func (o *CycleDetail) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CycleDetail) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CycleDetail) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTotalCostMicros

`func (o *CycleDetail) GetTotalCostMicros() int64`

GetTotalCostMicros returns the TotalCostMicros field if non-nil, zero value otherwise.

### GetTotalCostMicrosOk

`func (o *CycleDetail) GetTotalCostMicrosOk() (*int64, bool)`

GetTotalCostMicrosOk returns a tuple with the TotalCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCostMicros

`func (o *CycleDetail) SetTotalCostMicros(v int64)`

SetTotalCostMicros sets TotalCostMicros field to given value.


### SetTotalCostMicrosNil

`func (o *CycleDetail) SetTotalCostMicrosNil(b bool)`

 SetTotalCostMicrosNil sets the value for TotalCostMicros to be an explicit nil

### UnsetTotalCostMicros
`func (o *CycleDetail) UnsetTotalCostMicros()`

UnsetTotalCostMicros ensures that no value is present for TotalCostMicros, not even an explicit nil
### GetUpdatedAt

`func (o *CycleDetail) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CycleDetail) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CycleDetail) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


