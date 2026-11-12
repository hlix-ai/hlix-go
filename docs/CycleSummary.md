# CycleSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedUser** | [**NullableCycleSummaryAssignedUser**](CycleSummaryAssignedUser.md) |  |
**AssignedUserId** | **NullableString** |  |
**BaseRef** | **NullableString** |  |
**BranchSlug** | **NullableString** |  |
**CreatedAt** | **string** |  |
**CreatedByRunId** | **NullableString** |  |
**DependsOn** | **[]string** |  |
**Description** | **string** |  |
**E2eVideoUrl** | **NullableString** |  |
**Following** | **bool** |  |
**Handling** | **NullableString** |  |
**Id** | **string** |  |
**Kind** | **string** |  |
**LinearIssueIdentifier** | **NullableString** |  |
**LinearIssueUrl** | **NullableString** |  |
**OrganizationId** | **string** |  |
**OriginCycleId** | **NullableString** |  |
**OutcomeSummary** | **NullableString** |  |
**PrUrl** | **NullableString** |  |
**PreviewBranch** | **NullableString** |  |
**Priority** | **int32** |  |
**ProjectId** | **string** |  |
**ProjectName** | **string** |  |
**ProjectStatus** | **string** |  |
**RefinedReqs** | **NullableString** |  |
**ReplannedThroughRun** | **NullableInt32** |  |
**RepoId** | **NullableString** |  |
**RequestedByUserId** | **NullableString** |  |
**Revision** | **int32** |  |
**Role** | **NullableString** |  |
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

### NewCycleSummary

`func NewCycleSummary(assignedUser NullableCycleSummaryAssignedUser, assignedUserId NullableString, baseRef NullableString, branchSlug NullableString, createdAt string, createdByRunId NullableString, dependsOn []string, description string, e2eVideoUrl NullableString, following bool, handling NullableString, id string, kind string, linearIssueIdentifier NullableString, linearIssueUrl NullableString, organizationId string, originCycleId NullableString, outcomeSummary NullableString, prUrl NullableString, previewBranch NullableString, priority int32, projectId string, projectName string, projectStatus string, refinedReqs NullableString, replannedThroughRun NullableInt32, repoId NullableString, requestedByUserId NullableString, revision int32, role NullableString, runPin NullableCycleRunPin, source NullableString, stageHistory []CycleStageHistoryInner, status string, targetBranch NullableString, taskTimeoutMinutes int32, title string, totalCostMicros NullableInt64, updatedAt string, ) *CycleSummary`

NewCycleSummary instantiates a new CycleSummary object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleSummaryWithDefaults

`func NewCycleSummaryWithDefaults() *CycleSummary`

NewCycleSummaryWithDefaults instantiates a new CycleSummary object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAssignedUser

`func (o *CycleSummary) GetAssignedUser() CycleSummaryAssignedUser`

GetAssignedUser returns the AssignedUser field if non-nil, zero value otherwise.

### GetAssignedUserOk

`func (o *CycleSummary) GetAssignedUserOk() (*CycleSummaryAssignedUser, bool)`

GetAssignedUserOk returns a tuple with the AssignedUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUser

`func (o *CycleSummary) SetAssignedUser(v CycleSummaryAssignedUser)`

SetAssignedUser sets AssignedUser field to given value.


### SetAssignedUserNil

`func (o *CycleSummary) SetAssignedUserNil(b bool)`

 SetAssignedUserNil sets the value for AssignedUser to be an explicit nil

### UnsetAssignedUser
`func (o *CycleSummary) UnsetAssignedUser()`

UnsetAssignedUser ensures that no value is present for AssignedUser, not even an explicit nil
### GetAssignedUserId

`func (o *CycleSummary) GetAssignedUserId() string`

GetAssignedUserId returns the AssignedUserId field if non-nil, zero value otherwise.

### GetAssignedUserIdOk

`func (o *CycleSummary) GetAssignedUserIdOk() (*string, bool)`

GetAssignedUserIdOk returns a tuple with the AssignedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUserId

`func (o *CycleSummary) SetAssignedUserId(v string)`

SetAssignedUserId sets AssignedUserId field to given value.


### SetAssignedUserIdNil

`func (o *CycleSummary) SetAssignedUserIdNil(b bool)`

 SetAssignedUserIdNil sets the value for AssignedUserId to be an explicit nil

### UnsetAssignedUserId
`func (o *CycleSummary) UnsetAssignedUserId()`

UnsetAssignedUserId ensures that no value is present for AssignedUserId, not even an explicit nil
### GetBaseRef

`func (o *CycleSummary) GetBaseRef() string`

GetBaseRef returns the BaseRef field if non-nil, zero value otherwise.

### GetBaseRefOk

`func (o *CycleSummary) GetBaseRefOk() (*string, bool)`

GetBaseRefOk returns a tuple with the BaseRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseRef

`func (o *CycleSummary) SetBaseRef(v string)`

SetBaseRef sets BaseRef field to given value.


### SetBaseRefNil

`func (o *CycleSummary) SetBaseRefNil(b bool)`

 SetBaseRefNil sets the value for BaseRef to be an explicit nil

### UnsetBaseRef
`func (o *CycleSummary) UnsetBaseRef()`

UnsetBaseRef ensures that no value is present for BaseRef, not even an explicit nil
### GetBranchSlug

`func (o *CycleSummary) GetBranchSlug() string`

GetBranchSlug returns the BranchSlug field if non-nil, zero value otherwise.

### GetBranchSlugOk

`func (o *CycleSummary) GetBranchSlugOk() (*string, bool)`

GetBranchSlugOk returns a tuple with the BranchSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchSlug

`func (o *CycleSummary) SetBranchSlug(v string)`

SetBranchSlug sets BranchSlug field to given value.


### SetBranchSlugNil

`func (o *CycleSummary) SetBranchSlugNil(b bool)`

 SetBranchSlugNil sets the value for BranchSlug to be an explicit nil

### UnsetBranchSlug
`func (o *CycleSummary) UnsetBranchSlug()`

UnsetBranchSlug ensures that no value is present for BranchSlug, not even an explicit nil
### GetCreatedAt

`func (o *CycleSummary) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CycleSummary) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CycleSummary) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedByRunId

`func (o *CycleSummary) GetCreatedByRunId() string`

GetCreatedByRunId returns the CreatedByRunId field if non-nil, zero value otherwise.

### GetCreatedByRunIdOk

`func (o *CycleSummary) GetCreatedByRunIdOk() (*string, bool)`

GetCreatedByRunIdOk returns a tuple with the CreatedByRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByRunId

`func (o *CycleSummary) SetCreatedByRunId(v string)`

SetCreatedByRunId sets CreatedByRunId field to given value.


### SetCreatedByRunIdNil

`func (o *CycleSummary) SetCreatedByRunIdNil(b bool)`

 SetCreatedByRunIdNil sets the value for CreatedByRunId to be an explicit nil

### UnsetCreatedByRunId
`func (o *CycleSummary) UnsetCreatedByRunId()`

UnsetCreatedByRunId ensures that no value is present for CreatedByRunId, not even an explicit nil
### GetDependsOn

`func (o *CycleSummary) GetDependsOn() []string`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *CycleSummary) GetDependsOnOk() (*[]string, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *CycleSummary) SetDependsOn(v []string)`

SetDependsOn sets DependsOn field to given value.


### GetDescription

`func (o *CycleSummary) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CycleSummary) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CycleSummary) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetE2eVideoUrl

`func (o *CycleSummary) GetE2eVideoUrl() string`

GetE2eVideoUrl returns the E2eVideoUrl field if non-nil, zero value otherwise.

### GetE2eVideoUrlOk

`func (o *CycleSummary) GetE2eVideoUrlOk() (*string, bool)`

GetE2eVideoUrlOk returns a tuple with the E2eVideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetE2eVideoUrl

`func (o *CycleSummary) SetE2eVideoUrl(v string)`

SetE2eVideoUrl sets E2eVideoUrl field to given value.


### SetE2eVideoUrlNil

`func (o *CycleSummary) SetE2eVideoUrlNil(b bool)`

 SetE2eVideoUrlNil sets the value for E2eVideoUrl to be an explicit nil

### UnsetE2eVideoUrl
`func (o *CycleSummary) UnsetE2eVideoUrl()`

UnsetE2eVideoUrl ensures that no value is present for E2eVideoUrl, not even an explicit nil
### GetFollowing

`func (o *CycleSummary) GetFollowing() bool`

GetFollowing returns the Following field if non-nil, zero value otherwise.

### GetFollowingOk

`func (o *CycleSummary) GetFollowingOk() (*bool, bool)`

GetFollowingOk returns a tuple with the Following field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowing

`func (o *CycleSummary) SetFollowing(v bool)`

SetFollowing sets Following field to given value.


### GetHandling

`func (o *CycleSummary) GetHandling() string`

GetHandling returns the Handling field if non-nil, zero value otherwise.

### GetHandlingOk

`func (o *CycleSummary) GetHandlingOk() (*string, bool)`

GetHandlingOk returns a tuple with the Handling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandling

`func (o *CycleSummary) SetHandling(v string)`

SetHandling sets Handling field to given value.


### SetHandlingNil

`func (o *CycleSummary) SetHandlingNil(b bool)`

 SetHandlingNil sets the value for Handling to be an explicit nil

### UnsetHandling
`func (o *CycleSummary) UnsetHandling()`

UnsetHandling ensures that no value is present for Handling, not even an explicit nil
### GetId

`func (o *CycleSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CycleSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CycleSummary) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *CycleSummary) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CycleSummary) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CycleSummary) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLinearIssueIdentifier

`func (o *CycleSummary) GetLinearIssueIdentifier() string`

GetLinearIssueIdentifier returns the LinearIssueIdentifier field if non-nil, zero value otherwise.

### GetLinearIssueIdentifierOk

`func (o *CycleSummary) GetLinearIssueIdentifierOk() (*string, bool)`

GetLinearIssueIdentifierOk returns a tuple with the LinearIssueIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueIdentifier

`func (o *CycleSummary) SetLinearIssueIdentifier(v string)`

SetLinearIssueIdentifier sets LinearIssueIdentifier field to given value.


### SetLinearIssueIdentifierNil

`func (o *CycleSummary) SetLinearIssueIdentifierNil(b bool)`

 SetLinearIssueIdentifierNil sets the value for LinearIssueIdentifier to be an explicit nil

### UnsetLinearIssueIdentifier
`func (o *CycleSummary) UnsetLinearIssueIdentifier()`

UnsetLinearIssueIdentifier ensures that no value is present for LinearIssueIdentifier, not even an explicit nil
### GetLinearIssueUrl

`func (o *CycleSummary) GetLinearIssueUrl() string`

GetLinearIssueUrl returns the LinearIssueUrl field if non-nil, zero value otherwise.

### GetLinearIssueUrlOk

`func (o *CycleSummary) GetLinearIssueUrlOk() (*string, bool)`

GetLinearIssueUrlOk returns a tuple with the LinearIssueUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueUrl

`func (o *CycleSummary) SetLinearIssueUrl(v string)`

SetLinearIssueUrl sets LinearIssueUrl field to given value.


### SetLinearIssueUrlNil

`func (o *CycleSummary) SetLinearIssueUrlNil(b bool)`

 SetLinearIssueUrlNil sets the value for LinearIssueUrl to be an explicit nil

### UnsetLinearIssueUrl
`func (o *CycleSummary) UnsetLinearIssueUrl()`

UnsetLinearIssueUrl ensures that no value is present for LinearIssueUrl, not even an explicit nil
### GetOrganizationId

`func (o *CycleSummary) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CycleSummary) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CycleSummary) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOriginCycleId

`func (o *CycleSummary) GetOriginCycleId() string`

GetOriginCycleId returns the OriginCycleId field if non-nil, zero value otherwise.

### GetOriginCycleIdOk

`func (o *CycleSummary) GetOriginCycleIdOk() (*string, bool)`

GetOriginCycleIdOk returns a tuple with the OriginCycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginCycleId

`func (o *CycleSummary) SetOriginCycleId(v string)`

SetOriginCycleId sets OriginCycleId field to given value.


### SetOriginCycleIdNil

`func (o *CycleSummary) SetOriginCycleIdNil(b bool)`

 SetOriginCycleIdNil sets the value for OriginCycleId to be an explicit nil

### UnsetOriginCycleId
`func (o *CycleSummary) UnsetOriginCycleId()`

UnsetOriginCycleId ensures that no value is present for OriginCycleId, not even an explicit nil
### GetOutcomeSummary

`func (o *CycleSummary) GetOutcomeSummary() string`

GetOutcomeSummary returns the OutcomeSummary field if non-nil, zero value otherwise.

### GetOutcomeSummaryOk

`func (o *CycleSummary) GetOutcomeSummaryOk() (*string, bool)`

GetOutcomeSummaryOk returns a tuple with the OutcomeSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcomeSummary

`func (o *CycleSummary) SetOutcomeSummary(v string)`

SetOutcomeSummary sets OutcomeSummary field to given value.


### SetOutcomeSummaryNil

`func (o *CycleSummary) SetOutcomeSummaryNil(b bool)`

 SetOutcomeSummaryNil sets the value for OutcomeSummary to be an explicit nil

### UnsetOutcomeSummary
`func (o *CycleSummary) UnsetOutcomeSummary()`

UnsetOutcomeSummary ensures that no value is present for OutcomeSummary, not even an explicit nil
### GetPrUrl

`func (o *CycleSummary) GetPrUrl() string`

GetPrUrl returns the PrUrl field if non-nil, zero value otherwise.

### GetPrUrlOk

`func (o *CycleSummary) GetPrUrlOk() (*string, bool)`

GetPrUrlOk returns a tuple with the PrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrUrl

`func (o *CycleSummary) SetPrUrl(v string)`

SetPrUrl sets PrUrl field to given value.


### SetPrUrlNil

`func (o *CycleSummary) SetPrUrlNil(b bool)`

 SetPrUrlNil sets the value for PrUrl to be an explicit nil

### UnsetPrUrl
`func (o *CycleSummary) UnsetPrUrl()`

UnsetPrUrl ensures that no value is present for PrUrl, not even an explicit nil
### GetPreviewBranch

`func (o *CycleSummary) GetPreviewBranch() string`

GetPreviewBranch returns the PreviewBranch field if non-nil, zero value otherwise.

### GetPreviewBranchOk

`func (o *CycleSummary) GetPreviewBranchOk() (*string, bool)`

GetPreviewBranchOk returns a tuple with the PreviewBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewBranch

`func (o *CycleSummary) SetPreviewBranch(v string)`

SetPreviewBranch sets PreviewBranch field to given value.


### SetPreviewBranchNil

`func (o *CycleSummary) SetPreviewBranchNil(b bool)`

 SetPreviewBranchNil sets the value for PreviewBranch to be an explicit nil

### UnsetPreviewBranch
`func (o *CycleSummary) UnsetPreviewBranch()`

UnsetPreviewBranch ensures that no value is present for PreviewBranch, not even an explicit nil
### GetPriority

`func (o *CycleSummary) GetPriority() int32`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *CycleSummary) GetPriorityOk() (*int32, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *CycleSummary) SetPriority(v int32)`

SetPriority sets Priority field to given value.


### GetProjectId

`func (o *CycleSummary) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CycleSummary) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CycleSummary) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProjectName

`func (o *CycleSummary) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *CycleSummary) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *CycleSummary) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### GetProjectStatus

`func (o *CycleSummary) GetProjectStatus() string`

GetProjectStatus returns the ProjectStatus field if non-nil, zero value otherwise.

### GetProjectStatusOk

`func (o *CycleSummary) GetProjectStatusOk() (*string, bool)`

GetProjectStatusOk returns a tuple with the ProjectStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectStatus

`func (o *CycleSummary) SetProjectStatus(v string)`

SetProjectStatus sets ProjectStatus field to given value.


### GetRefinedReqs

`func (o *CycleSummary) GetRefinedReqs() string`

GetRefinedReqs returns the RefinedReqs field if non-nil, zero value otherwise.

### GetRefinedReqsOk

`func (o *CycleSummary) GetRefinedReqsOk() (*string, bool)`

GetRefinedReqsOk returns a tuple with the RefinedReqs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefinedReqs

`func (o *CycleSummary) SetRefinedReqs(v string)`

SetRefinedReqs sets RefinedReqs field to given value.


### SetRefinedReqsNil

`func (o *CycleSummary) SetRefinedReqsNil(b bool)`

 SetRefinedReqsNil sets the value for RefinedReqs to be an explicit nil

### UnsetRefinedReqs
`func (o *CycleSummary) UnsetRefinedReqs()`

UnsetRefinedReqs ensures that no value is present for RefinedReqs, not even an explicit nil
### GetReplannedThroughRun

`func (o *CycleSummary) GetReplannedThroughRun() int32`

GetReplannedThroughRun returns the ReplannedThroughRun field if non-nil, zero value otherwise.

### GetReplannedThroughRunOk

`func (o *CycleSummary) GetReplannedThroughRunOk() (*int32, bool)`

GetReplannedThroughRunOk returns a tuple with the ReplannedThroughRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplannedThroughRun

`func (o *CycleSummary) SetReplannedThroughRun(v int32)`

SetReplannedThroughRun sets ReplannedThroughRun field to given value.


### SetReplannedThroughRunNil

`func (o *CycleSummary) SetReplannedThroughRunNil(b bool)`

 SetReplannedThroughRunNil sets the value for ReplannedThroughRun to be an explicit nil

### UnsetReplannedThroughRun
`func (o *CycleSummary) UnsetReplannedThroughRun()`

UnsetReplannedThroughRun ensures that no value is present for ReplannedThroughRun, not even an explicit nil
### GetRepoId

`func (o *CycleSummary) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *CycleSummary) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *CycleSummary) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.


### SetRepoIdNil

`func (o *CycleSummary) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *CycleSummary) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetRequestedByUserId

`func (o *CycleSummary) GetRequestedByUserId() string`

GetRequestedByUserId returns the RequestedByUserId field if non-nil, zero value otherwise.

### GetRequestedByUserIdOk

`func (o *CycleSummary) GetRequestedByUserIdOk() (*string, bool)`

GetRequestedByUserIdOk returns a tuple with the RequestedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedByUserId

`func (o *CycleSummary) SetRequestedByUserId(v string)`

SetRequestedByUserId sets RequestedByUserId field to given value.


### SetRequestedByUserIdNil

`func (o *CycleSummary) SetRequestedByUserIdNil(b bool)`

 SetRequestedByUserIdNil sets the value for RequestedByUserId to be an explicit nil

### UnsetRequestedByUserId
`func (o *CycleSummary) UnsetRequestedByUserId()`

UnsetRequestedByUserId ensures that no value is present for RequestedByUserId, not even an explicit nil
### GetRevision

`func (o *CycleSummary) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CycleSummary) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CycleSummary) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetRole

`func (o *CycleSummary) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CycleSummary) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CycleSummary) SetRole(v string)`

SetRole sets Role field to given value.


### SetRoleNil

`func (o *CycleSummary) SetRoleNil(b bool)`

 SetRoleNil sets the value for Role to be an explicit nil

### UnsetRole
`func (o *CycleSummary) UnsetRole()`

UnsetRole ensures that no value is present for Role, not even an explicit nil
### GetRunPin

`func (o *CycleSummary) GetRunPin() CycleRunPin`

GetRunPin returns the RunPin field if non-nil, zero value otherwise.

### GetRunPinOk

`func (o *CycleSummary) GetRunPinOk() (*CycleRunPin, bool)`

GetRunPinOk returns a tuple with the RunPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunPin

`func (o *CycleSummary) SetRunPin(v CycleRunPin)`

SetRunPin sets RunPin field to given value.


### SetRunPinNil

`func (o *CycleSummary) SetRunPinNil(b bool)`

 SetRunPinNil sets the value for RunPin to be an explicit nil

### UnsetRunPin
`func (o *CycleSummary) UnsetRunPin()`

UnsetRunPin ensures that no value is present for RunPin, not even an explicit nil
### GetSource

`func (o *CycleSummary) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CycleSummary) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CycleSummary) SetSource(v string)`

SetSource sets Source field to given value.


### SetSourceNil

`func (o *CycleSummary) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *CycleSummary) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetStageHistory

`func (o *CycleSummary) GetStageHistory() []CycleStageHistoryInner`

GetStageHistory returns the StageHistory field if non-nil, zero value otherwise.

### GetStageHistoryOk

`func (o *CycleSummary) GetStageHistoryOk() (*[]CycleStageHistoryInner, bool)`

GetStageHistoryOk returns a tuple with the StageHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageHistory

`func (o *CycleSummary) SetStageHistory(v []CycleStageHistoryInner)`

SetStageHistory sets StageHistory field to given value.


### GetStatus

`func (o *CycleSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTargetBranch

`func (o *CycleSummary) GetTargetBranch() string`

GetTargetBranch returns the TargetBranch field if non-nil, zero value otherwise.

### GetTargetBranchOk

`func (o *CycleSummary) GetTargetBranchOk() (*string, bool)`

GetTargetBranchOk returns a tuple with the TargetBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetBranch

`func (o *CycleSummary) SetTargetBranch(v string)`

SetTargetBranch sets TargetBranch field to given value.


### SetTargetBranchNil

`func (o *CycleSummary) SetTargetBranchNil(b bool)`

 SetTargetBranchNil sets the value for TargetBranch to be an explicit nil

### UnsetTargetBranch
`func (o *CycleSummary) UnsetTargetBranch()`

UnsetTargetBranch ensures that no value is present for TargetBranch, not even an explicit nil
### GetTaskTimeoutMinutes

`func (o *CycleSummary) GetTaskTimeoutMinutes() int32`

GetTaskTimeoutMinutes returns the TaskTimeoutMinutes field if non-nil, zero value otherwise.

### GetTaskTimeoutMinutesOk

`func (o *CycleSummary) GetTaskTimeoutMinutesOk() (*int32, bool)`

GetTaskTimeoutMinutesOk returns a tuple with the TaskTimeoutMinutes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskTimeoutMinutes

`func (o *CycleSummary) SetTaskTimeoutMinutes(v int32)`

SetTaskTimeoutMinutes sets TaskTimeoutMinutes field to given value.


### GetTitle

`func (o *CycleSummary) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CycleSummary) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CycleSummary) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTotalCostMicros

`func (o *CycleSummary) GetTotalCostMicros() int64`

GetTotalCostMicros returns the TotalCostMicros field if non-nil, zero value otherwise.

### GetTotalCostMicrosOk

`func (o *CycleSummary) GetTotalCostMicrosOk() (*int64, bool)`

GetTotalCostMicrosOk returns a tuple with the TotalCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCostMicros

`func (o *CycleSummary) SetTotalCostMicros(v int64)`

SetTotalCostMicros sets TotalCostMicros field to given value.


### SetTotalCostMicrosNil

`func (o *CycleSummary) SetTotalCostMicrosNil(b bool)`

 SetTotalCostMicrosNil sets the value for TotalCostMicros to be an explicit nil

### UnsetTotalCostMicros
`func (o *CycleSummary) UnsetTotalCostMicros()`

UnsetTotalCostMicros ensures that no value is present for TotalCostMicros, not even an explicit nil
### GetUpdatedAt

`func (o *CycleSummary) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CycleSummary) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CycleSummary) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


