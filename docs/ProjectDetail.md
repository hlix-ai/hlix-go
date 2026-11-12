# ProjectDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | **NullableString** |  |
**AssignedUserId** | **NullableString** |  |
**Attention** | [**[]AgencyOverviewReportAttentionInnerAttentionItem**](AgencyOverviewReportAttentionInnerAttentionItem.md) |  |
**BranchNames** | **string** |  |
**BranchPrefix** | **NullableString** |  |
**BranchPrefixLockedAt** | **NullableString** |  |
**Brief** | **NullableString** |  |
**ClaudeMd** | **NullableString** |  |
**ClientAccountId** | **NullableString** |  |
**CompletedAtLastRevision** | **int32** |  |
**CostCapMicros** | **NullableInt64** |  |
**CreatedAt** | **string** |  |
**CustomDomain** | **NullableString** |  |
**CycleCap** | **NullableInt32** |  |
**DeploymentPreviewsEnabled** | **bool** |  |
**DetectedCommands** | [**NullableProjectDetectedCommands**](ProjectDetectedCommands.md) |  |
**EnvironmentSnapshot** | [**NullableProjectEnvironmentSnapshot**](ProjectEnvironmentSnapshot.md) |  |
**ExtraUsage** | **NullableString** |  |
**GrowthAutopilot** | **bool** |  |
**GrowthDailyBudgetMicros** | **NullableInt64** |  |
**GrowthSendingSchedule** | [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  |
**Id** | **string** |  |
**InitialProposalRequired** | **bool** |  |
**Iteration** | **int32** |  |
**Kind** | **string** |  |
**MachineSize** | **NullableString** |  |
**MaxRevisions** | **NullableInt32** |  |
**MobileTargetsInitialized** | **bool** |  |
**Name** | **string** |  |
**OrganizationId** | **string** |  |
**PauseReason** | **NullableString** |  |
**PausedAt** | **NullableString** |  |
**PausedByUserId** | **NullableString** |  |
**PrUrl** | **NullableString** |  |
**PreviewCommand** | **NullableString** |  |
**PreviewMergedAt** | **NullableString** |  |
**PreviewPort** | **NullableInt32** |  |
**Repos** | [**[]ProjectReposInner**](ProjectReposInner.md) |  |
**Round** | **int32** |  |
**Runtime** | [**ProjectRuntime**](ProjectRuntime.md) |  |
**SetupReport** | [**NullableProjectSetupReport**](ProjectSetupReport.md) |  |
**Slug** | **string** |  |
**Sources** | [**ProjectSources**](ProjectSources.md) |  |
**Stack** | **string** |  |
**StalledRevisions** | **int32** |  |
**Status** | **string** |  |
**StopState** | **string** |  |
**Tier** | **NullableString** |  |
**UseWorkspaceBrand** | **bool** |  |
**VerifyCommand** | **NullableString** |  |
**ViewerCanAccessCanvas** | **bool** |  |
**ViewerCanMessage** | **bool** |  |
**ViewerCanSeeInsights** | **bool** |  |

## Methods

### NewProjectDetail

`func NewProjectDetail(archivedAt NullableString, assignedUserId NullableString, attention []AgencyOverviewReportAttentionInnerAttentionItem, branchNames string, branchPrefix NullableString, branchPrefixLockedAt NullableString, brief NullableString, claudeMd NullableString, clientAccountId NullableString, completedAtLastRevision int32, costCapMicros NullableInt64, createdAt string, customDomain NullableString, cycleCap NullableInt32, deploymentPreviewsEnabled bool, detectedCommands NullableProjectDetectedCommands, environmentSnapshot NullableProjectEnvironmentSnapshot, extraUsage NullableString, growthAutopilot bool, growthDailyBudgetMicros NullableInt64, growthSendingSchedule NullableCreateGrowthPlaySendingSchedule, id string, initialProposalRequired bool, iteration int32, kind string, machineSize NullableString, maxRevisions NullableInt32, mobileTargetsInitialized bool, name string, organizationId string, pauseReason NullableString, pausedAt NullableString, pausedByUserId NullableString, prUrl NullableString, previewCommand NullableString, previewMergedAt NullableString, previewPort NullableInt32, repos []ProjectReposInner, round int32, runtime ProjectRuntime, setupReport NullableProjectSetupReport, slug string, sources ProjectSources, stack string, stalledRevisions int32, status string, stopState string, tier NullableString, useWorkspaceBrand bool, verifyCommand NullableString, viewerCanAccessCanvas bool, viewerCanMessage bool, viewerCanSeeInsights bool, ) *ProjectDetail`

NewProjectDetail instantiates a new ProjectDetail object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectDetailWithDefaults

`func NewProjectDetailWithDefaults() *ProjectDetail`

NewProjectDetailWithDefaults instantiates a new ProjectDetail object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetArchivedAt

`func (o *ProjectDetail) GetArchivedAt() string`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ProjectDetail) GetArchivedAtOk() (*string, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ProjectDetail) SetArchivedAt(v string)`

SetArchivedAt sets ArchivedAt field to given value.


### SetArchivedAtNil

`func (o *ProjectDetail) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ProjectDetail) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAssignedUserId

`func (o *ProjectDetail) GetAssignedUserId() string`

GetAssignedUserId returns the AssignedUserId field if non-nil, zero value otherwise.

### GetAssignedUserIdOk

`func (o *ProjectDetail) GetAssignedUserIdOk() (*string, bool)`

GetAssignedUserIdOk returns a tuple with the AssignedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUserId

`func (o *ProjectDetail) SetAssignedUserId(v string)`

SetAssignedUserId sets AssignedUserId field to given value.


### SetAssignedUserIdNil

`func (o *ProjectDetail) SetAssignedUserIdNil(b bool)`

 SetAssignedUserIdNil sets the value for AssignedUserId to be an explicit nil

### UnsetAssignedUserId
`func (o *ProjectDetail) UnsetAssignedUserId()`

UnsetAssignedUserId ensures that no value is present for AssignedUserId, not even an explicit nil
### GetAttention

`func (o *ProjectDetail) GetAttention() []AgencyOverviewReportAttentionInnerAttentionItem`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *ProjectDetail) GetAttentionOk() (*[]AgencyOverviewReportAttentionInnerAttentionItem, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *ProjectDetail) SetAttention(v []AgencyOverviewReportAttentionInnerAttentionItem)`

SetAttention sets Attention field to given value.


### GetBranchNames

`func (o *ProjectDetail) GetBranchNames() string`

GetBranchNames returns the BranchNames field if non-nil, zero value otherwise.

### GetBranchNamesOk

`func (o *ProjectDetail) GetBranchNamesOk() (*string, bool)`

GetBranchNamesOk returns a tuple with the BranchNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchNames

`func (o *ProjectDetail) SetBranchNames(v string)`

SetBranchNames sets BranchNames field to given value.


### GetBranchPrefix

`func (o *ProjectDetail) GetBranchPrefix() string`

GetBranchPrefix returns the BranchPrefix field if non-nil, zero value otherwise.

### GetBranchPrefixOk

`func (o *ProjectDetail) GetBranchPrefixOk() (*string, bool)`

GetBranchPrefixOk returns a tuple with the BranchPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefix

`func (o *ProjectDetail) SetBranchPrefix(v string)`

SetBranchPrefix sets BranchPrefix field to given value.


### SetBranchPrefixNil

`func (o *ProjectDetail) SetBranchPrefixNil(b bool)`

 SetBranchPrefixNil sets the value for BranchPrefix to be an explicit nil

### UnsetBranchPrefix
`func (o *ProjectDetail) UnsetBranchPrefix()`

UnsetBranchPrefix ensures that no value is present for BranchPrefix, not even an explicit nil
### GetBranchPrefixLockedAt

`func (o *ProjectDetail) GetBranchPrefixLockedAt() string`

GetBranchPrefixLockedAt returns the BranchPrefixLockedAt field if non-nil, zero value otherwise.

### GetBranchPrefixLockedAtOk

`func (o *ProjectDetail) GetBranchPrefixLockedAtOk() (*string, bool)`

GetBranchPrefixLockedAtOk returns a tuple with the BranchPrefixLockedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefixLockedAt

`func (o *ProjectDetail) SetBranchPrefixLockedAt(v string)`

SetBranchPrefixLockedAt sets BranchPrefixLockedAt field to given value.


### SetBranchPrefixLockedAtNil

`func (o *ProjectDetail) SetBranchPrefixLockedAtNil(b bool)`

 SetBranchPrefixLockedAtNil sets the value for BranchPrefixLockedAt to be an explicit nil

### UnsetBranchPrefixLockedAt
`func (o *ProjectDetail) UnsetBranchPrefixLockedAt()`

UnsetBranchPrefixLockedAt ensures that no value is present for BranchPrefixLockedAt, not even an explicit nil
### GetBrief

`func (o *ProjectDetail) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *ProjectDetail) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *ProjectDetail) SetBrief(v string)`

SetBrief sets Brief field to given value.


### SetBriefNil

`func (o *ProjectDetail) SetBriefNil(b bool)`

 SetBriefNil sets the value for Brief to be an explicit nil

### UnsetBrief
`func (o *ProjectDetail) UnsetBrief()`

UnsetBrief ensures that no value is present for Brief, not even an explicit nil
### GetClaudeMd

`func (o *ProjectDetail) GetClaudeMd() string`

GetClaudeMd returns the ClaudeMd field if non-nil, zero value otherwise.

### GetClaudeMdOk

`func (o *ProjectDetail) GetClaudeMdOk() (*string, bool)`

GetClaudeMdOk returns a tuple with the ClaudeMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaudeMd

`func (o *ProjectDetail) SetClaudeMd(v string)`

SetClaudeMd sets ClaudeMd field to given value.


### SetClaudeMdNil

`func (o *ProjectDetail) SetClaudeMdNil(b bool)`

 SetClaudeMdNil sets the value for ClaudeMd to be an explicit nil

### UnsetClaudeMd
`func (o *ProjectDetail) UnsetClaudeMd()`

UnsetClaudeMd ensures that no value is present for ClaudeMd, not even an explicit nil
### GetClientAccountId

`func (o *ProjectDetail) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *ProjectDetail) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *ProjectDetail) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *ProjectDetail) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *ProjectDetail) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetCompletedAtLastRevision

`func (o *ProjectDetail) GetCompletedAtLastRevision() int32`

GetCompletedAtLastRevision returns the CompletedAtLastRevision field if non-nil, zero value otherwise.

### GetCompletedAtLastRevisionOk

`func (o *ProjectDetail) GetCompletedAtLastRevisionOk() (*int32, bool)`

GetCompletedAtLastRevisionOk returns a tuple with the CompletedAtLastRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAtLastRevision

`func (o *ProjectDetail) SetCompletedAtLastRevision(v int32)`

SetCompletedAtLastRevision sets CompletedAtLastRevision field to given value.


### GetCostCapMicros

`func (o *ProjectDetail) GetCostCapMicros() int64`

GetCostCapMicros returns the CostCapMicros field if non-nil, zero value otherwise.

### GetCostCapMicrosOk

`func (o *ProjectDetail) GetCostCapMicrosOk() (*int64, bool)`

GetCostCapMicrosOk returns a tuple with the CostCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCapMicros

`func (o *ProjectDetail) SetCostCapMicros(v int64)`

SetCostCapMicros sets CostCapMicros field to given value.


### SetCostCapMicrosNil

`func (o *ProjectDetail) SetCostCapMicrosNil(b bool)`

 SetCostCapMicrosNil sets the value for CostCapMicros to be an explicit nil

### UnsetCostCapMicros
`func (o *ProjectDetail) UnsetCostCapMicros()`

UnsetCostCapMicros ensures that no value is present for CostCapMicros, not even an explicit nil
### GetCreatedAt

`func (o *ProjectDetail) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectDetail) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectDetail) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomDomain

`func (o *ProjectDetail) GetCustomDomain() string`

GetCustomDomain returns the CustomDomain field if non-nil, zero value otherwise.

### GetCustomDomainOk

`func (o *ProjectDetail) GetCustomDomainOk() (*string, bool)`

GetCustomDomainOk returns a tuple with the CustomDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomDomain

`func (o *ProjectDetail) SetCustomDomain(v string)`

SetCustomDomain sets CustomDomain field to given value.


### SetCustomDomainNil

`func (o *ProjectDetail) SetCustomDomainNil(b bool)`

 SetCustomDomainNil sets the value for CustomDomain to be an explicit nil

### UnsetCustomDomain
`func (o *ProjectDetail) UnsetCustomDomain()`

UnsetCustomDomain ensures that no value is present for CustomDomain, not even an explicit nil
### GetCycleCap

`func (o *ProjectDetail) GetCycleCap() int32`

GetCycleCap returns the CycleCap field if non-nil, zero value otherwise.

### GetCycleCapOk

`func (o *ProjectDetail) GetCycleCapOk() (*int32, bool)`

GetCycleCapOk returns a tuple with the CycleCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleCap

`func (o *ProjectDetail) SetCycleCap(v int32)`

SetCycleCap sets CycleCap field to given value.


### SetCycleCapNil

`func (o *ProjectDetail) SetCycleCapNil(b bool)`

 SetCycleCapNil sets the value for CycleCap to be an explicit nil

### UnsetCycleCap
`func (o *ProjectDetail) UnsetCycleCap()`

UnsetCycleCap ensures that no value is present for CycleCap, not even an explicit nil
### GetDeploymentPreviewsEnabled

`func (o *ProjectDetail) GetDeploymentPreviewsEnabled() bool`

GetDeploymentPreviewsEnabled returns the DeploymentPreviewsEnabled field if non-nil, zero value otherwise.

### GetDeploymentPreviewsEnabledOk

`func (o *ProjectDetail) GetDeploymentPreviewsEnabledOk() (*bool, bool)`

GetDeploymentPreviewsEnabledOk returns a tuple with the DeploymentPreviewsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeploymentPreviewsEnabled

`func (o *ProjectDetail) SetDeploymentPreviewsEnabled(v bool)`

SetDeploymentPreviewsEnabled sets DeploymentPreviewsEnabled field to given value.


### GetDetectedCommands

`func (o *ProjectDetail) GetDetectedCommands() ProjectDetectedCommands`

GetDetectedCommands returns the DetectedCommands field if non-nil, zero value otherwise.

### GetDetectedCommandsOk

`func (o *ProjectDetail) GetDetectedCommandsOk() (*ProjectDetectedCommands, bool)`

GetDetectedCommandsOk returns a tuple with the DetectedCommands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedCommands

`func (o *ProjectDetail) SetDetectedCommands(v ProjectDetectedCommands)`

SetDetectedCommands sets DetectedCommands field to given value.


### SetDetectedCommandsNil

`func (o *ProjectDetail) SetDetectedCommandsNil(b bool)`

 SetDetectedCommandsNil sets the value for DetectedCommands to be an explicit nil

### UnsetDetectedCommands
`func (o *ProjectDetail) UnsetDetectedCommands()`

UnsetDetectedCommands ensures that no value is present for DetectedCommands, not even an explicit nil
### GetEnvironmentSnapshot

`func (o *ProjectDetail) GetEnvironmentSnapshot() ProjectEnvironmentSnapshot`

GetEnvironmentSnapshot returns the EnvironmentSnapshot field if non-nil, zero value otherwise.

### GetEnvironmentSnapshotOk

`func (o *ProjectDetail) GetEnvironmentSnapshotOk() (*ProjectEnvironmentSnapshot, bool)`

GetEnvironmentSnapshotOk returns a tuple with the EnvironmentSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironmentSnapshot

`func (o *ProjectDetail) SetEnvironmentSnapshot(v ProjectEnvironmentSnapshot)`

SetEnvironmentSnapshot sets EnvironmentSnapshot field to given value.


### SetEnvironmentSnapshotNil

`func (o *ProjectDetail) SetEnvironmentSnapshotNil(b bool)`

 SetEnvironmentSnapshotNil sets the value for EnvironmentSnapshot to be an explicit nil

### UnsetEnvironmentSnapshot
`func (o *ProjectDetail) UnsetEnvironmentSnapshot()`

UnsetEnvironmentSnapshot ensures that no value is present for EnvironmentSnapshot, not even an explicit nil
### GetExtraUsage

`func (o *ProjectDetail) GetExtraUsage() string`

GetExtraUsage returns the ExtraUsage field if non-nil, zero value otherwise.

### GetExtraUsageOk

`func (o *ProjectDetail) GetExtraUsageOk() (*string, bool)`

GetExtraUsageOk returns a tuple with the ExtraUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraUsage

`func (o *ProjectDetail) SetExtraUsage(v string)`

SetExtraUsage sets ExtraUsage field to given value.


### SetExtraUsageNil

`func (o *ProjectDetail) SetExtraUsageNil(b bool)`

 SetExtraUsageNil sets the value for ExtraUsage to be an explicit nil

### UnsetExtraUsage
`func (o *ProjectDetail) UnsetExtraUsage()`

UnsetExtraUsage ensures that no value is present for ExtraUsage, not even an explicit nil
### GetGrowthAutopilot

`func (o *ProjectDetail) GetGrowthAutopilot() bool`

GetGrowthAutopilot returns the GrowthAutopilot field if non-nil, zero value otherwise.

### GetGrowthAutopilotOk

`func (o *ProjectDetail) GetGrowthAutopilotOk() (*bool, bool)`

GetGrowthAutopilotOk returns a tuple with the GrowthAutopilot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthAutopilot

`func (o *ProjectDetail) SetGrowthAutopilot(v bool)`

SetGrowthAutopilot sets GrowthAutopilot field to given value.


### GetGrowthDailyBudgetMicros

`func (o *ProjectDetail) GetGrowthDailyBudgetMicros() int64`

GetGrowthDailyBudgetMicros returns the GrowthDailyBudgetMicros field if non-nil, zero value otherwise.

### GetGrowthDailyBudgetMicrosOk

`func (o *ProjectDetail) GetGrowthDailyBudgetMicrosOk() (*int64, bool)`

GetGrowthDailyBudgetMicrosOk returns a tuple with the GrowthDailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthDailyBudgetMicros

`func (o *ProjectDetail) SetGrowthDailyBudgetMicros(v int64)`

SetGrowthDailyBudgetMicros sets GrowthDailyBudgetMicros field to given value.


### SetGrowthDailyBudgetMicrosNil

`func (o *ProjectDetail) SetGrowthDailyBudgetMicrosNil(b bool)`

 SetGrowthDailyBudgetMicrosNil sets the value for GrowthDailyBudgetMicros to be an explicit nil

### UnsetGrowthDailyBudgetMicros
`func (o *ProjectDetail) UnsetGrowthDailyBudgetMicros()`

UnsetGrowthDailyBudgetMicros ensures that no value is present for GrowthDailyBudgetMicros, not even an explicit nil
### GetGrowthSendingSchedule

`func (o *ProjectDetail) GetGrowthSendingSchedule() CreateGrowthPlaySendingSchedule`

GetGrowthSendingSchedule returns the GrowthSendingSchedule field if non-nil, zero value otherwise.

### GetGrowthSendingScheduleOk

`func (o *ProjectDetail) GetGrowthSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetGrowthSendingScheduleOk returns a tuple with the GrowthSendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthSendingSchedule

`func (o *ProjectDetail) SetGrowthSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetGrowthSendingSchedule sets GrowthSendingSchedule field to given value.


### SetGrowthSendingScheduleNil

`func (o *ProjectDetail) SetGrowthSendingScheduleNil(b bool)`

 SetGrowthSendingScheduleNil sets the value for GrowthSendingSchedule to be an explicit nil

### UnsetGrowthSendingSchedule
`func (o *ProjectDetail) UnsetGrowthSendingSchedule()`

UnsetGrowthSendingSchedule ensures that no value is present for GrowthSendingSchedule, not even an explicit nil
### GetId

`func (o *ProjectDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectDetail) SetId(v string)`

SetId sets Id field to given value.


### GetInitialProposalRequired

`func (o *ProjectDetail) GetInitialProposalRequired() bool`

GetInitialProposalRequired returns the InitialProposalRequired field if non-nil, zero value otherwise.

### GetInitialProposalRequiredOk

`func (o *ProjectDetail) GetInitialProposalRequiredOk() (*bool, bool)`

GetInitialProposalRequiredOk returns a tuple with the InitialProposalRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialProposalRequired

`func (o *ProjectDetail) SetInitialProposalRequired(v bool)`

SetInitialProposalRequired sets InitialProposalRequired field to given value.


### GetIteration

`func (o *ProjectDetail) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *ProjectDetail) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *ProjectDetail) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### GetKind

`func (o *ProjectDetail) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProjectDetail) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProjectDetail) SetKind(v string)`

SetKind sets Kind field to given value.


### GetMachineSize

`func (o *ProjectDetail) GetMachineSize() string`

GetMachineSize returns the MachineSize field if non-nil, zero value otherwise.

### GetMachineSizeOk

`func (o *ProjectDetail) GetMachineSizeOk() (*string, bool)`

GetMachineSizeOk returns a tuple with the MachineSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineSize

`func (o *ProjectDetail) SetMachineSize(v string)`

SetMachineSize sets MachineSize field to given value.


### SetMachineSizeNil

`func (o *ProjectDetail) SetMachineSizeNil(b bool)`

 SetMachineSizeNil sets the value for MachineSize to be an explicit nil

### UnsetMachineSize
`func (o *ProjectDetail) UnsetMachineSize()`

UnsetMachineSize ensures that no value is present for MachineSize, not even an explicit nil
### GetMaxRevisions

`func (o *ProjectDetail) GetMaxRevisions() int32`

GetMaxRevisions returns the MaxRevisions field if non-nil, zero value otherwise.

### GetMaxRevisionsOk

`func (o *ProjectDetail) GetMaxRevisionsOk() (*int32, bool)`

GetMaxRevisionsOk returns a tuple with the MaxRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRevisions

`func (o *ProjectDetail) SetMaxRevisions(v int32)`

SetMaxRevisions sets MaxRevisions field to given value.


### SetMaxRevisionsNil

`func (o *ProjectDetail) SetMaxRevisionsNil(b bool)`

 SetMaxRevisionsNil sets the value for MaxRevisions to be an explicit nil

### UnsetMaxRevisions
`func (o *ProjectDetail) UnsetMaxRevisions()`

UnsetMaxRevisions ensures that no value is present for MaxRevisions, not even an explicit nil
### GetMobileTargetsInitialized

`func (o *ProjectDetail) GetMobileTargetsInitialized() bool`

GetMobileTargetsInitialized returns the MobileTargetsInitialized field if non-nil, zero value otherwise.

### GetMobileTargetsInitializedOk

`func (o *ProjectDetail) GetMobileTargetsInitializedOk() (*bool, bool)`

GetMobileTargetsInitializedOk returns a tuple with the MobileTargetsInitialized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobileTargetsInitialized

`func (o *ProjectDetail) SetMobileTargetsInitialized(v bool)`

SetMobileTargetsInitialized sets MobileTargetsInitialized field to given value.


### GetName

`func (o *ProjectDetail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectDetail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectDetail) SetName(v string)`

SetName sets Name field to given value.


### GetOrganizationId

`func (o *ProjectDetail) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ProjectDetail) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ProjectDetail) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPauseReason

`func (o *ProjectDetail) GetPauseReason() string`

GetPauseReason returns the PauseReason field if non-nil, zero value otherwise.

### GetPauseReasonOk

`func (o *ProjectDetail) GetPauseReasonOk() (*string, bool)`

GetPauseReasonOk returns a tuple with the PauseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPauseReason

`func (o *ProjectDetail) SetPauseReason(v string)`

SetPauseReason sets PauseReason field to given value.


### SetPauseReasonNil

`func (o *ProjectDetail) SetPauseReasonNil(b bool)`

 SetPauseReasonNil sets the value for PauseReason to be an explicit nil

### UnsetPauseReason
`func (o *ProjectDetail) UnsetPauseReason()`

UnsetPauseReason ensures that no value is present for PauseReason, not even an explicit nil
### GetPausedAt

`func (o *ProjectDetail) GetPausedAt() string`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *ProjectDetail) GetPausedAtOk() (*string, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *ProjectDetail) SetPausedAt(v string)`

SetPausedAt sets PausedAt field to given value.


### SetPausedAtNil

`func (o *ProjectDetail) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *ProjectDetail) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetPausedByUserId

`func (o *ProjectDetail) GetPausedByUserId() string`

GetPausedByUserId returns the PausedByUserId field if non-nil, zero value otherwise.

### GetPausedByUserIdOk

`func (o *ProjectDetail) GetPausedByUserIdOk() (*string, bool)`

GetPausedByUserIdOk returns a tuple with the PausedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedByUserId

`func (o *ProjectDetail) SetPausedByUserId(v string)`

SetPausedByUserId sets PausedByUserId field to given value.


### SetPausedByUserIdNil

`func (o *ProjectDetail) SetPausedByUserIdNil(b bool)`

 SetPausedByUserIdNil sets the value for PausedByUserId to be an explicit nil

### UnsetPausedByUserId
`func (o *ProjectDetail) UnsetPausedByUserId()`

UnsetPausedByUserId ensures that no value is present for PausedByUserId, not even an explicit nil
### GetPrUrl

`func (o *ProjectDetail) GetPrUrl() string`

GetPrUrl returns the PrUrl field if non-nil, zero value otherwise.

### GetPrUrlOk

`func (o *ProjectDetail) GetPrUrlOk() (*string, bool)`

GetPrUrlOk returns a tuple with the PrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrUrl

`func (o *ProjectDetail) SetPrUrl(v string)`

SetPrUrl sets PrUrl field to given value.


### SetPrUrlNil

`func (o *ProjectDetail) SetPrUrlNil(b bool)`

 SetPrUrlNil sets the value for PrUrl to be an explicit nil

### UnsetPrUrl
`func (o *ProjectDetail) UnsetPrUrl()`

UnsetPrUrl ensures that no value is present for PrUrl, not even an explicit nil
### GetPreviewCommand

`func (o *ProjectDetail) GetPreviewCommand() string`

GetPreviewCommand returns the PreviewCommand field if non-nil, zero value otherwise.

### GetPreviewCommandOk

`func (o *ProjectDetail) GetPreviewCommandOk() (*string, bool)`

GetPreviewCommandOk returns a tuple with the PreviewCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewCommand

`func (o *ProjectDetail) SetPreviewCommand(v string)`

SetPreviewCommand sets PreviewCommand field to given value.


### SetPreviewCommandNil

`func (o *ProjectDetail) SetPreviewCommandNil(b bool)`

 SetPreviewCommandNil sets the value for PreviewCommand to be an explicit nil

### UnsetPreviewCommand
`func (o *ProjectDetail) UnsetPreviewCommand()`

UnsetPreviewCommand ensures that no value is present for PreviewCommand, not even an explicit nil
### GetPreviewMergedAt

`func (o *ProjectDetail) GetPreviewMergedAt() string`

GetPreviewMergedAt returns the PreviewMergedAt field if non-nil, zero value otherwise.

### GetPreviewMergedAtOk

`func (o *ProjectDetail) GetPreviewMergedAtOk() (*string, bool)`

GetPreviewMergedAtOk returns a tuple with the PreviewMergedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewMergedAt

`func (o *ProjectDetail) SetPreviewMergedAt(v string)`

SetPreviewMergedAt sets PreviewMergedAt field to given value.


### SetPreviewMergedAtNil

`func (o *ProjectDetail) SetPreviewMergedAtNil(b bool)`

 SetPreviewMergedAtNil sets the value for PreviewMergedAt to be an explicit nil

### UnsetPreviewMergedAt
`func (o *ProjectDetail) UnsetPreviewMergedAt()`

UnsetPreviewMergedAt ensures that no value is present for PreviewMergedAt, not even an explicit nil
### GetPreviewPort

`func (o *ProjectDetail) GetPreviewPort() int32`

GetPreviewPort returns the PreviewPort field if non-nil, zero value otherwise.

### GetPreviewPortOk

`func (o *ProjectDetail) GetPreviewPortOk() (*int32, bool)`

GetPreviewPortOk returns a tuple with the PreviewPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPort

`func (o *ProjectDetail) SetPreviewPort(v int32)`

SetPreviewPort sets PreviewPort field to given value.


### SetPreviewPortNil

`func (o *ProjectDetail) SetPreviewPortNil(b bool)`

 SetPreviewPortNil sets the value for PreviewPort to be an explicit nil

### UnsetPreviewPort
`func (o *ProjectDetail) UnsetPreviewPort()`

UnsetPreviewPort ensures that no value is present for PreviewPort, not even an explicit nil
### GetRepos

`func (o *ProjectDetail) GetRepos() []ProjectReposInner`

GetRepos returns the Repos field if non-nil, zero value otherwise.

### GetReposOk

`func (o *ProjectDetail) GetReposOk() (*[]ProjectReposInner, bool)`

GetReposOk returns a tuple with the Repos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepos

`func (o *ProjectDetail) SetRepos(v []ProjectReposInner)`

SetRepos sets Repos field to given value.


### GetRound

`func (o *ProjectDetail) GetRound() int32`

GetRound returns the Round field if non-nil, zero value otherwise.

### GetRoundOk

`func (o *ProjectDetail) GetRoundOk() (*int32, bool)`

GetRoundOk returns a tuple with the Round field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRound

`func (o *ProjectDetail) SetRound(v int32)`

SetRound sets Round field to given value.


### GetRuntime

`func (o *ProjectDetail) GetRuntime() ProjectRuntime`

GetRuntime returns the Runtime field if non-nil, zero value otherwise.

### GetRuntimeOk

`func (o *ProjectDetail) GetRuntimeOk() (*ProjectRuntime, bool)`

GetRuntimeOk returns a tuple with the Runtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntime

`func (o *ProjectDetail) SetRuntime(v ProjectRuntime)`

SetRuntime sets Runtime field to given value.


### GetSetupReport

`func (o *ProjectDetail) GetSetupReport() ProjectSetupReport`

GetSetupReport returns the SetupReport field if non-nil, zero value otherwise.

### GetSetupReportOk

`func (o *ProjectDetail) GetSetupReportOk() (*ProjectSetupReport, bool)`

GetSetupReportOk returns a tuple with the SetupReport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupReport

`func (o *ProjectDetail) SetSetupReport(v ProjectSetupReport)`

SetSetupReport sets SetupReport field to given value.


### SetSetupReportNil

`func (o *ProjectDetail) SetSetupReportNil(b bool)`

 SetSetupReportNil sets the value for SetupReport to be an explicit nil

### UnsetSetupReport
`func (o *ProjectDetail) UnsetSetupReport()`

UnsetSetupReport ensures that no value is present for SetupReport, not even an explicit nil
### GetSlug

`func (o *ProjectDetail) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ProjectDetail) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ProjectDetail) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetSources

`func (o *ProjectDetail) GetSources() ProjectSources`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ProjectDetail) GetSourcesOk() (*ProjectSources, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ProjectDetail) SetSources(v ProjectSources)`

SetSources sets Sources field to given value.


### GetStack

`func (o *ProjectDetail) GetStack() string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *ProjectDetail) GetStackOk() (*string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *ProjectDetail) SetStack(v string)`

SetStack sets Stack field to given value.


### GetStalledRevisions

`func (o *ProjectDetail) GetStalledRevisions() int32`

GetStalledRevisions returns the StalledRevisions field if non-nil, zero value otherwise.

### GetStalledRevisionsOk

`func (o *ProjectDetail) GetStalledRevisionsOk() (*int32, bool)`

GetStalledRevisionsOk returns a tuple with the StalledRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStalledRevisions

`func (o *ProjectDetail) SetStalledRevisions(v int32)`

SetStalledRevisions sets StalledRevisions field to given value.


### GetStatus

`func (o *ProjectDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDetail) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStopState

`func (o *ProjectDetail) GetStopState() string`

GetStopState returns the StopState field if non-nil, zero value otherwise.

### GetStopStateOk

`func (o *ProjectDetail) GetStopStateOk() (*string, bool)`

GetStopStateOk returns a tuple with the StopState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopState

`func (o *ProjectDetail) SetStopState(v string)`

SetStopState sets StopState field to given value.


### GetTier

`func (o *ProjectDetail) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *ProjectDetail) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *ProjectDetail) SetTier(v string)`

SetTier sets Tier field to given value.


### SetTierNil

`func (o *ProjectDetail) SetTierNil(b bool)`

 SetTierNil sets the value for Tier to be an explicit nil

### UnsetTier
`func (o *ProjectDetail) UnsetTier()`

UnsetTier ensures that no value is present for Tier, not even an explicit nil
### GetUseWorkspaceBrand

`func (o *ProjectDetail) GetUseWorkspaceBrand() bool`

GetUseWorkspaceBrand returns the UseWorkspaceBrand field if non-nil, zero value otherwise.

### GetUseWorkspaceBrandOk

`func (o *ProjectDetail) GetUseWorkspaceBrandOk() (*bool, bool)`

GetUseWorkspaceBrandOk returns a tuple with the UseWorkspaceBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWorkspaceBrand

`func (o *ProjectDetail) SetUseWorkspaceBrand(v bool)`

SetUseWorkspaceBrand sets UseWorkspaceBrand field to given value.


### GetVerifyCommand

`func (o *ProjectDetail) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *ProjectDetail) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *ProjectDetail) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.


### SetVerifyCommandNil

`func (o *ProjectDetail) SetVerifyCommandNil(b bool)`

 SetVerifyCommandNil sets the value for VerifyCommand to be an explicit nil

### UnsetVerifyCommand
`func (o *ProjectDetail) UnsetVerifyCommand()`

UnsetVerifyCommand ensures that no value is present for VerifyCommand, not even an explicit nil
### GetViewerCanAccessCanvas

`func (o *ProjectDetail) GetViewerCanAccessCanvas() bool`

GetViewerCanAccessCanvas returns the ViewerCanAccessCanvas field if non-nil, zero value otherwise.

### GetViewerCanAccessCanvasOk

`func (o *ProjectDetail) GetViewerCanAccessCanvasOk() (*bool, bool)`

GetViewerCanAccessCanvasOk returns a tuple with the ViewerCanAccessCanvas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViewerCanAccessCanvas

`func (o *ProjectDetail) SetViewerCanAccessCanvas(v bool)`

SetViewerCanAccessCanvas sets ViewerCanAccessCanvas field to given value.


### GetViewerCanMessage

`func (o *ProjectDetail) GetViewerCanMessage() bool`

GetViewerCanMessage returns the ViewerCanMessage field if non-nil, zero value otherwise.

### GetViewerCanMessageOk

`func (o *ProjectDetail) GetViewerCanMessageOk() (*bool, bool)`

GetViewerCanMessageOk returns a tuple with the ViewerCanMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViewerCanMessage

`func (o *ProjectDetail) SetViewerCanMessage(v bool)`

SetViewerCanMessage sets ViewerCanMessage field to given value.


### GetViewerCanSeeInsights

`func (o *ProjectDetail) GetViewerCanSeeInsights() bool`

GetViewerCanSeeInsights returns the ViewerCanSeeInsights field if non-nil, zero value otherwise.

### GetViewerCanSeeInsightsOk

`func (o *ProjectDetail) GetViewerCanSeeInsightsOk() (*bool, bool)`

GetViewerCanSeeInsightsOk returns a tuple with the ViewerCanSeeInsights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViewerCanSeeInsights

`func (o *ProjectDetail) SetViewerCanSeeInsights(v bool)`

SetViewerCanSeeInsights sets ViewerCanSeeInsights field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


