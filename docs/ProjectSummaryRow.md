# ProjectSummaryRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveCycles** | **int32** |  |
**AgentCount** | **int32** |  |
**Approvals** | **int32** |  |
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
**CycleCount** | **int32** |  |
**CyclesDone** | **int32** |  |
**DeliveryStatus** | **NullableString** |  |
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
**LastActivityAt** | **NullableString** |  |
**LatestCycleStatus** | **NullableString** |  |
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
**Round** | **int32** |  |
**RunningAgents** | **int32** |  |
**Runtime** | [**ProjectRuntime**](ProjectRuntime.md) |  |
**SetupReport** | [**NullableProjectSetupReport**](ProjectSetupReport.md) |  |
**Slug** | **string** |  |
**Sources** | [**ProjectSources**](ProjectSources.md) |  |
**Stack** | **string** |  |
**StalledRevisions** | **int32** |  |
**Status** | **string** |  |
**Tier** | **NullableString** |  |
**TotalCostMicros** | **NullableInt64** |  |
**UseWorkspaceBrand** | **bool** |  |
**VerifyCommand** | **NullableString** |  |

## Methods

### NewProjectSummaryRow

`func NewProjectSummaryRow(activeCycles int32, agentCount int32, approvals int32, archivedAt NullableString, assignedUserId NullableString, attention []AgencyOverviewReportAttentionInnerAttentionItem, branchNames string, branchPrefix NullableString, branchPrefixLockedAt NullableString, brief NullableString, claudeMd NullableString, clientAccountId NullableString, completedAtLastRevision int32, costCapMicros NullableInt64, createdAt string, customDomain NullableString, cycleCap NullableInt32, cycleCount int32, cyclesDone int32, deliveryStatus NullableString, detectedCommands NullableProjectDetectedCommands, environmentSnapshot NullableProjectEnvironmentSnapshot, extraUsage NullableString, growthAutopilot bool, growthDailyBudgetMicros NullableInt64, growthSendingSchedule NullableCreateGrowthPlaySendingSchedule, id string, initialProposalRequired bool, iteration int32, kind string, lastActivityAt NullableString, latestCycleStatus NullableString, machineSize NullableString, maxRevisions NullableInt32, mobileTargetsInitialized bool, name string, organizationId string, pauseReason NullableString, pausedAt NullableString, pausedByUserId NullableString, prUrl NullableString, previewCommand NullableString, previewMergedAt NullableString, previewPort NullableInt32, round int32, runningAgents int32, runtime ProjectRuntime, setupReport NullableProjectSetupReport, slug string, sources ProjectSources, stack string, stalledRevisions int32, status string, tier NullableString, totalCostMicros NullableInt64, useWorkspaceBrand bool, verifyCommand NullableString, ) *ProjectSummaryRow`

NewProjectSummaryRow instantiates a new ProjectSummaryRow object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectSummaryRowWithDefaults

`func NewProjectSummaryRowWithDefaults() *ProjectSummaryRow`

NewProjectSummaryRowWithDefaults instantiates a new ProjectSummaryRow object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetActiveCycles

`func (o *ProjectSummaryRow) GetActiveCycles() int32`

GetActiveCycles returns the ActiveCycles field if non-nil, zero value otherwise.

### GetActiveCyclesOk

`func (o *ProjectSummaryRow) GetActiveCyclesOk() (*int32, bool)`

GetActiveCyclesOk returns a tuple with the ActiveCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveCycles

`func (o *ProjectSummaryRow) SetActiveCycles(v int32)`

SetActiveCycles sets ActiveCycles field to given value.


### GetAgentCount

`func (o *ProjectSummaryRow) GetAgentCount() int32`

GetAgentCount returns the AgentCount field if non-nil, zero value otherwise.

### GetAgentCountOk

`func (o *ProjectSummaryRow) GetAgentCountOk() (*int32, bool)`

GetAgentCountOk returns a tuple with the AgentCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentCount

`func (o *ProjectSummaryRow) SetAgentCount(v int32)`

SetAgentCount sets AgentCount field to given value.


### GetApprovals

`func (o *ProjectSummaryRow) GetApprovals() int32`

GetApprovals returns the Approvals field if non-nil, zero value otherwise.

### GetApprovalsOk

`func (o *ProjectSummaryRow) GetApprovalsOk() (*int32, bool)`

GetApprovalsOk returns a tuple with the Approvals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovals

`func (o *ProjectSummaryRow) SetApprovals(v int32)`

SetApprovals sets Approvals field to given value.


### GetArchivedAt

`func (o *ProjectSummaryRow) GetArchivedAt() string`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ProjectSummaryRow) GetArchivedAtOk() (*string, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ProjectSummaryRow) SetArchivedAt(v string)`

SetArchivedAt sets ArchivedAt field to given value.


### SetArchivedAtNil

`func (o *ProjectSummaryRow) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ProjectSummaryRow) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAssignedUserId

`func (o *ProjectSummaryRow) GetAssignedUserId() string`

GetAssignedUserId returns the AssignedUserId field if non-nil, zero value otherwise.

### GetAssignedUserIdOk

`func (o *ProjectSummaryRow) GetAssignedUserIdOk() (*string, bool)`

GetAssignedUserIdOk returns a tuple with the AssignedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUserId

`func (o *ProjectSummaryRow) SetAssignedUserId(v string)`

SetAssignedUserId sets AssignedUserId field to given value.


### SetAssignedUserIdNil

`func (o *ProjectSummaryRow) SetAssignedUserIdNil(b bool)`

 SetAssignedUserIdNil sets the value for AssignedUserId to be an explicit nil

### UnsetAssignedUserId
`func (o *ProjectSummaryRow) UnsetAssignedUserId()`

UnsetAssignedUserId ensures that no value is present for AssignedUserId, not even an explicit nil
### GetAttention

`func (o *ProjectSummaryRow) GetAttention() []AgencyOverviewReportAttentionInnerAttentionItem`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *ProjectSummaryRow) GetAttentionOk() (*[]AgencyOverviewReportAttentionInnerAttentionItem, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *ProjectSummaryRow) SetAttention(v []AgencyOverviewReportAttentionInnerAttentionItem)`

SetAttention sets Attention field to given value.


### GetBranchNames

`func (o *ProjectSummaryRow) GetBranchNames() string`

GetBranchNames returns the BranchNames field if non-nil, zero value otherwise.

### GetBranchNamesOk

`func (o *ProjectSummaryRow) GetBranchNamesOk() (*string, bool)`

GetBranchNamesOk returns a tuple with the BranchNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchNames

`func (o *ProjectSummaryRow) SetBranchNames(v string)`

SetBranchNames sets BranchNames field to given value.


### GetBranchPrefix

`func (o *ProjectSummaryRow) GetBranchPrefix() string`

GetBranchPrefix returns the BranchPrefix field if non-nil, zero value otherwise.

### GetBranchPrefixOk

`func (o *ProjectSummaryRow) GetBranchPrefixOk() (*string, bool)`

GetBranchPrefixOk returns a tuple with the BranchPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefix

`func (o *ProjectSummaryRow) SetBranchPrefix(v string)`

SetBranchPrefix sets BranchPrefix field to given value.


### SetBranchPrefixNil

`func (o *ProjectSummaryRow) SetBranchPrefixNil(b bool)`

 SetBranchPrefixNil sets the value for BranchPrefix to be an explicit nil

### UnsetBranchPrefix
`func (o *ProjectSummaryRow) UnsetBranchPrefix()`

UnsetBranchPrefix ensures that no value is present for BranchPrefix, not even an explicit nil
### GetBranchPrefixLockedAt

`func (o *ProjectSummaryRow) GetBranchPrefixLockedAt() string`

GetBranchPrefixLockedAt returns the BranchPrefixLockedAt field if non-nil, zero value otherwise.

### GetBranchPrefixLockedAtOk

`func (o *ProjectSummaryRow) GetBranchPrefixLockedAtOk() (*string, bool)`

GetBranchPrefixLockedAtOk returns a tuple with the BranchPrefixLockedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefixLockedAt

`func (o *ProjectSummaryRow) SetBranchPrefixLockedAt(v string)`

SetBranchPrefixLockedAt sets BranchPrefixLockedAt field to given value.


### SetBranchPrefixLockedAtNil

`func (o *ProjectSummaryRow) SetBranchPrefixLockedAtNil(b bool)`

 SetBranchPrefixLockedAtNil sets the value for BranchPrefixLockedAt to be an explicit nil

### UnsetBranchPrefixLockedAt
`func (o *ProjectSummaryRow) UnsetBranchPrefixLockedAt()`

UnsetBranchPrefixLockedAt ensures that no value is present for BranchPrefixLockedAt, not even an explicit nil
### GetBrief

`func (o *ProjectSummaryRow) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *ProjectSummaryRow) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *ProjectSummaryRow) SetBrief(v string)`

SetBrief sets Brief field to given value.


### SetBriefNil

`func (o *ProjectSummaryRow) SetBriefNil(b bool)`

 SetBriefNil sets the value for Brief to be an explicit nil

### UnsetBrief
`func (o *ProjectSummaryRow) UnsetBrief()`

UnsetBrief ensures that no value is present for Brief, not even an explicit nil
### GetClaudeMd

`func (o *ProjectSummaryRow) GetClaudeMd() string`

GetClaudeMd returns the ClaudeMd field if non-nil, zero value otherwise.

### GetClaudeMdOk

`func (o *ProjectSummaryRow) GetClaudeMdOk() (*string, bool)`

GetClaudeMdOk returns a tuple with the ClaudeMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaudeMd

`func (o *ProjectSummaryRow) SetClaudeMd(v string)`

SetClaudeMd sets ClaudeMd field to given value.


### SetClaudeMdNil

`func (o *ProjectSummaryRow) SetClaudeMdNil(b bool)`

 SetClaudeMdNil sets the value for ClaudeMd to be an explicit nil

### UnsetClaudeMd
`func (o *ProjectSummaryRow) UnsetClaudeMd()`

UnsetClaudeMd ensures that no value is present for ClaudeMd, not even an explicit nil
### GetClientAccountId

`func (o *ProjectSummaryRow) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *ProjectSummaryRow) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *ProjectSummaryRow) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *ProjectSummaryRow) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *ProjectSummaryRow) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetCompletedAtLastRevision

`func (o *ProjectSummaryRow) GetCompletedAtLastRevision() int32`

GetCompletedAtLastRevision returns the CompletedAtLastRevision field if non-nil, zero value otherwise.

### GetCompletedAtLastRevisionOk

`func (o *ProjectSummaryRow) GetCompletedAtLastRevisionOk() (*int32, bool)`

GetCompletedAtLastRevisionOk returns a tuple with the CompletedAtLastRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAtLastRevision

`func (o *ProjectSummaryRow) SetCompletedAtLastRevision(v int32)`

SetCompletedAtLastRevision sets CompletedAtLastRevision field to given value.


### GetCostCapMicros

`func (o *ProjectSummaryRow) GetCostCapMicros() int64`

GetCostCapMicros returns the CostCapMicros field if non-nil, zero value otherwise.

### GetCostCapMicrosOk

`func (o *ProjectSummaryRow) GetCostCapMicrosOk() (*int64, bool)`

GetCostCapMicrosOk returns a tuple with the CostCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCapMicros

`func (o *ProjectSummaryRow) SetCostCapMicros(v int64)`

SetCostCapMicros sets CostCapMicros field to given value.


### SetCostCapMicrosNil

`func (o *ProjectSummaryRow) SetCostCapMicrosNil(b bool)`

 SetCostCapMicrosNil sets the value for CostCapMicros to be an explicit nil

### UnsetCostCapMicros
`func (o *ProjectSummaryRow) UnsetCostCapMicros()`

UnsetCostCapMicros ensures that no value is present for CostCapMicros, not even an explicit nil
### GetCreatedAt

`func (o *ProjectSummaryRow) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectSummaryRow) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectSummaryRow) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomDomain

`func (o *ProjectSummaryRow) GetCustomDomain() string`

GetCustomDomain returns the CustomDomain field if non-nil, zero value otherwise.

### GetCustomDomainOk

`func (o *ProjectSummaryRow) GetCustomDomainOk() (*string, bool)`

GetCustomDomainOk returns a tuple with the CustomDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomDomain

`func (o *ProjectSummaryRow) SetCustomDomain(v string)`

SetCustomDomain sets CustomDomain field to given value.


### SetCustomDomainNil

`func (o *ProjectSummaryRow) SetCustomDomainNil(b bool)`

 SetCustomDomainNil sets the value for CustomDomain to be an explicit nil

### UnsetCustomDomain
`func (o *ProjectSummaryRow) UnsetCustomDomain()`

UnsetCustomDomain ensures that no value is present for CustomDomain, not even an explicit nil
### GetCycleCap

`func (o *ProjectSummaryRow) GetCycleCap() int32`

GetCycleCap returns the CycleCap field if non-nil, zero value otherwise.

### GetCycleCapOk

`func (o *ProjectSummaryRow) GetCycleCapOk() (*int32, bool)`

GetCycleCapOk returns a tuple with the CycleCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleCap

`func (o *ProjectSummaryRow) SetCycleCap(v int32)`

SetCycleCap sets CycleCap field to given value.


### SetCycleCapNil

`func (o *ProjectSummaryRow) SetCycleCapNil(b bool)`

 SetCycleCapNil sets the value for CycleCap to be an explicit nil

### UnsetCycleCap
`func (o *ProjectSummaryRow) UnsetCycleCap()`

UnsetCycleCap ensures that no value is present for CycleCap, not even an explicit nil
### GetCycleCount

`func (o *ProjectSummaryRow) GetCycleCount() int32`

GetCycleCount returns the CycleCount field if non-nil, zero value otherwise.

### GetCycleCountOk

`func (o *ProjectSummaryRow) GetCycleCountOk() (*int32, bool)`

GetCycleCountOk returns a tuple with the CycleCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleCount

`func (o *ProjectSummaryRow) SetCycleCount(v int32)`

SetCycleCount sets CycleCount field to given value.


### GetCyclesDone

`func (o *ProjectSummaryRow) GetCyclesDone() int32`

GetCyclesDone returns the CyclesDone field if non-nil, zero value otherwise.

### GetCyclesDoneOk

`func (o *ProjectSummaryRow) GetCyclesDoneOk() (*int32, bool)`

GetCyclesDoneOk returns a tuple with the CyclesDone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCyclesDone

`func (o *ProjectSummaryRow) SetCyclesDone(v int32)`

SetCyclesDone sets CyclesDone field to given value.


### GetDeliveryStatus

`func (o *ProjectSummaryRow) GetDeliveryStatus() string`

GetDeliveryStatus returns the DeliveryStatus field if non-nil, zero value otherwise.

### GetDeliveryStatusOk

`func (o *ProjectSummaryRow) GetDeliveryStatusOk() (*string, bool)`

GetDeliveryStatusOk returns a tuple with the DeliveryStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryStatus

`func (o *ProjectSummaryRow) SetDeliveryStatus(v string)`

SetDeliveryStatus sets DeliveryStatus field to given value.


### SetDeliveryStatusNil

`func (o *ProjectSummaryRow) SetDeliveryStatusNil(b bool)`

 SetDeliveryStatusNil sets the value for DeliveryStatus to be an explicit nil

### UnsetDeliveryStatus
`func (o *ProjectSummaryRow) UnsetDeliveryStatus()`

UnsetDeliveryStatus ensures that no value is present for DeliveryStatus, not even an explicit nil
### GetDetectedCommands

`func (o *ProjectSummaryRow) GetDetectedCommands() ProjectDetectedCommands`

GetDetectedCommands returns the DetectedCommands field if non-nil, zero value otherwise.

### GetDetectedCommandsOk

`func (o *ProjectSummaryRow) GetDetectedCommandsOk() (*ProjectDetectedCommands, bool)`

GetDetectedCommandsOk returns a tuple with the DetectedCommands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedCommands

`func (o *ProjectSummaryRow) SetDetectedCommands(v ProjectDetectedCommands)`

SetDetectedCommands sets DetectedCommands field to given value.


### SetDetectedCommandsNil

`func (o *ProjectSummaryRow) SetDetectedCommandsNil(b bool)`

 SetDetectedCommandsNil sets the value for DetectedCommands to be an explicit nil

### UnsetDetectedCommands
`func (o *ProjectSummaryRow) UnsetDetectedCommands()`

UnsetDetectedCommands ensures that no value is present for DetectedCommands, not even an explicit nil
### GetEnvironmentSnapshot

`func (o *ProjectSummaryRow) GetEnvironmentSnapshot() ProjectEnvironmentSnapshot`

GetEnvironmentSnapshot returns the EnvironmentSnapshot field if non-nil, zero value otherwise.

### GetEnvironmentSnapshotOk

`func (o *ProjectSummaryRow) GetEnvironmentSnapshotOk() (*ProjectEnvironmentSnapshot, bool)`

GetEnvironmentSnapshotOk returns a tuple with the EnvironmentSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironmentSnapshot

`func (o *ProjectSummaryRow) SetEnvironmentSnapshot(v ProjectEnvironmentSnapshot)`

SetEnvironmentSnapshot sets EnvironmentSnapshot field to given value.


### SetEnvironmentSnapshotNil

`func (o *ProjectSummaryRow) SetEnvironmentSnapshotNil(b bool)`

 SetEnvironmentSnapshotNil sets the value for EnvironmentSnapshot to be an explicit nil

### UnsetEnvironmentSnapshot
`func (o *ProjectSummaryRow) UnsetEnvironmentSnapshot()`

UnsetEnvironmentSnapshot ensures that no value is present for EnvironmentSnapshot, not even an explicit nil
### GetExtraUsage

`func (o *ProjectSummaryRow) GetExtraUsage() string`

GetExtraUsage returns the ExtraUsage field if non-nil, zero value otherwise.

### GetExtraUsageOk

`func (o *ProjectSummaryRow) GetExtraUsageOk() (*string, bool)`

GetExtraUsageOk returns a tuple with the ExtraUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraUsage

`func (o *ProjectSummaryRow) SetExtraUsage(v string)`

SetExtraUsage sets ExtraUsage field to given value.


### SetExtraUsageNil

`func (o *ProjectSummaryRow) SetExtraUsageNil(b bool)`

 SetExtraUsageNil sets the value for ExtraUsage to be an explicit nil

### UnsetExtraUsage
`func (o *ProjectSummaryRow) UnsetExtraUsage()`

UnsetExtraUsage ensures that no value is present for ExtraUsage, not even an explicit nil
### GetGrowthAutopilot

`func (o *ProjectSummaryRow) GetGrowthAutopilot() bool`

GetGrowthAutopilot returns the GrowthAutopilot field if non-nil, zero value otherwise.

### GetGrowthAutopilotOk

`func (o *ProjectSummaryRow) GetGrowthAutopilotOk() (*bool, bool)`

GetGrowthAutopilotOk returns a tuple with the GrowthAutopilot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthAutopilot

`func (o *ProjectSummaryRow) SetGrowthAutopilot(v bool)`

SetGrowthAutopilot sets GrowthAutopilot field to given value.


### GetGrowthDailyBudgetMicros

`func (o *ProjectSummaryRow) GetGrowthDailyBudgetMicros() int64`

GetGrowthDailyBudgetMicros returns the GrowthDailyBudgetMicros field if non-nil, zero value otherwise.

### GetGrowthDailyBudgetMicrosOk

`func (o *ProjectSummaryRow) GetGrowthDailyBudgetMicrosOk() (*int64, bool)`

GetGrowthDailyBudgetMicrosOk returns a tuple with the GrowthDailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthDailyBudgetMicros

`func (o *ProjectSummaryRow) SetGrowthDailyBudgetMicros(v int64)`

SetGrowthDailyBudgetMicros sets GrowthDailyBudgetMicros field to given value.


### SetGrowthDailyBudgetMicrosNil

`func (o *ProjectSummaryRow) SetGrowthDailyBudgetMicrosNil(b bool)`

 SetGrowthDailyBudgetMicrosNil sets the value for GrowthDailyBudgetMicros to be an explicit nil

### UnsetGrowthDailyBudgetMicros
`func (o *ProjectSummaryRow) UnsetGrowthDailyBudgetMicros()`

UnsetGrowthDailyBudgetMicros ensures that no value is present for GrowthDailyBudgetMicros, not even an explicit nil
### GetGrowthSendingSchedule

`func (o *ProjectSummaryRow) GetGrowthSendingSchedule() CreateGrowthPlaySendingSchedule`

GetGrowthSendingSchedule returns the GrowthSendingSchedule field if non-nil, zero value otherwise.

### GetGrowthSendingScheduleOk

`func (o *ProjectSummaryRow) GetGrowthSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetGrowthSendingScheduleOk returns a tuple with the GrowthSendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthSendingSchedule

`func (o *ProjectSummaryRow) SetGrowthSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetGrowthSendingSchedule sets GrowthSendingSchedule field to given value.


### SetGrowthSendingScheduleNil

`func (o *ProjectSummaryRow) SetGrowthSendingScheduleNil(b bool)`

 SetGrowthSendingScheduleNil sets the value for GrowthSendingSchedule to be an explicit nil

### UnsetGrowthSendingSchedule
`func (o *ProjectSummaryRow) UnsetGrowthSendingSchedule()`

UnsetGrowthSendingSchedule ensures that no value is present for GrowthSendingSchedule, not even an explicit nil
### GetId

`func (o *ProjectSummaryRow) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectSummaryRow) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectSummaryRow) SetId(v string)`

SetId sets Id field to given value.


### GetInitialProposalRequired

`func (o *ProjectSummaryRow) GetInitialProposalRequired() bool`

GetInitialProposalRequired returns the InitialProposalRequired field if non-nil, zero value otherwise.

### GetInitialProposalRequiredOk

`func (o *ProjectSummaryRow) GetInitialProposalRequiredOk() (*bool, bool)`

GetInitialProposalRequiredOk returns a tuple with the InitialProposalRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialProposalRequired

`func (o *ProjectSummaryRow) SetInitialProposalRequired(v bool)`

SetInitialProposalRequired sets InitialProposalRequired field to given value.


### GetIteration

`func (o *ProjectSummaryRow) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *ProjectSummaryRow) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *ProjectSummaryRow) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### GetKind

`func (o *ProjectSummaryRow) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProjectSummaryRow) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProjectSummaryRow) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLastActivityAt

`func (o *ProjectSummaryRow) GetLastActivityAt() string`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *ProjectSummaryRow) GetLastActivityAtOk() (*string, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *ProjectSummaryRow) SetLastActivityAt(v string)`

SetLastActivityAt sets LastActivityAt field to given value.


### SetLastActivityAtNil

`func (o *ProjectSummaryRow) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *ProjectSummaryRow) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetLatestCycleStatus

`func (o *ProjectSummaryRow) GetLatestCycleStatus() string`

GetLatestCycleStatus returns the LatestCycleStatus field if non-nil, zero value otherwise.

### GetLatestCycleStatusOk

`func (o *ProjectSummaryRow) GetLatestCycleStatusOk() (*string, bool)`

GetLatestCycleStatusOk returns a tuple with the LatestCycleStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestCycleStatus

`func (o *ProjectSummaryRow) SetLatestCycleStatus(v string)`

SetLatestCycleStatus sets LatestCycleStatus field to given value.


### SetLatestCycleStatusNil

`func (o *ProjectSummaryRow) SetLatestCycleStatusNil(b bool)`

 SetLatestCycleStatusNil sets the value for LatestCycleStatus to be an explicit nil

### UnsetLatestCycleStatus
`func (o *ProjectSummaryRow) UnsetLatestCycleStatus()`

UnsetLatestCycleStatus ensures that no value is present for LatestCycleStatus, not even an explicit nil
### GetMachineSize

`func (o *ProjectSummaryRow) GetMachineSize() string`

GetMachineSize returns the MachineSize field if non-nil, zero value otherwise.

### GetMachineSizeOk

`func (o *ProjectSummaryRow) GetMachineSizeOk() (*string, bool)`

GetMachineSizeOk returns a tuple with the MachineSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineSize

`func (o *ProjectSummaryRow) SetMachineSize(v string)`

SetMachineSize sets MachineSize field to given value.


### SetMachineSizeNil

`func (o *ProjectSummaryRow) SetMachineSizeNil(b bool)`

 SetMachineSizeNil sets the value for MachineSize to be an explicit nil

### UnsetMachineSize
`func (o *ProjectSummaryRow) UnsetMachineSize()`

UnsetMachineSize ensures that no value is present for MachineSize, not even an explicit nil
### GetMaxRevisions

`func (o *ProjectSummaryRow) GetMaxRevisions() int32`

GetMaxRevisions returns the MaxRevisions field if non-nil, zero value otherwise.

### GetMaxRevisionsOk

`func (o *ProjectSummaryRow) GetMaxRevisionsOk() (*int32, bool)`

GetMaxRevisionsOk returns a tuple with the MaxRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRevisions

`func (o *ProjectSummaryRow) SetMaxRevisions(v int32)`

SetMaxRevisions sets MaxRevisions field to given value.


### SetMaxRevisionsNil

`func (o *ProjectSummaryRow) SetMaxRevisionsNil(b bool)`

 SetMaxRevisionsNil sets the value for MaxRevisions to be an explicit nil

### UnsetMaxRevisions
`func (o *ProjectSummaryRow) UnsetMaxRevisions()`

UnsetMaxRevisions ensures that no value is present for MaxRevisions, not even an explicit nil
### GetMobileTargetsInitialized

`func (o *ProjectSummaryRow) GetMobileTargetsInitialized() bool`

GetMobileTargetsInitialized returns the MobileTargetsInitialized field if non-nil, zero value otherwise.

### GetMobileTargetsInitializedOk

`func (o *ProjectSummaryRow) GetMobileTargetsInitializedOk() (*bool, bool)`

GetMobileTargetsInitializedOk returns a tuple with the MobileTargetsInitialized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobileTargetsInitialized

`func (o *ProjectSummaryRow) SetMobileTargetsInitialized(v bool)`

SetMobileTargetsInitialized sets MobileTargetsInitialized field to given value.


### GetName

`func (o *ProjectSummaryRow) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectSummaryRow) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectSummaryRow) SetName(v string)`

SetName sets Name field to given value.


### GetOrganizationId

`func (o *ProjectSummaryRow) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ProjectSummaryRow) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ProjectSummaryRow) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPauseReason

`func (o *ProjectSummaryRow) GetPauseReason() string`

GetPauseReason returns the PauseReason field if non-nil, zero value otherwise.

### GetPauseReasonOk

`func (o *ProjectSummaryRow) GetPauseReasonOk() (*string, bool)`

GetPauseReasonOk returns a tuple with the PauseReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPauseReason

`func (o *ProjectSummaryRow) SetPauseReason(v string)`

SetPauseReason sets PauseReason field to given value.


### SetPauseReasonNil

`func (o *ProjectSummaryRow) SetPauseReasonNil(b bool)`

 SetPauseReasonNil sets the value for PauseReason to be an explicit nil

### UnsetPauseReason
`func (o *ProjectSummaryRow) UnsetPauseReason()`

UnsetPauseReason ensures that no value is present for PauseReason, not even an explicit nil
### GetPausedAt

`func (o *ProjectSummaryRow) GetPausedAt() string`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *ProjectSummaryRow) GetPausedAtOk() (*string, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *ProjectSummaryRow) SetPausedAt(v string)`

SetPausedAt sets PausedAt field to given value.


### SetPausedAtNil

`func (o *ProjectSummaryRow) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *ProjectSummaryRow) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetPausedByUserId

`func (o *ProjectSummaryRow) GetPausedByUserId() string`

GetPausedByUserId returns the PausedByUserId field if non-nil, zero value otherwise.

### GetPausedByUserIdOk

`func (o *ProjectSummaryRow) GetPausedByUserIdOk() (*string, bool)`

GetPausedByUserIdOk returns a tuple with the PausedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedByUserId

`func (o *ProjectSummaryRow) SetPausedByUserId(v string)`

SetPausedByUserId sets PausedByUserId field to given value.


### SetPausedByUserIdNil

`func (o *ProjectSummaryRow) SetPausedByUserIdNil(b bool)`

 SetPausedByUserIdNil sets the value for PausedByUserId to be an explicit nil

### UnsetPausedByUserId
`func (o *ProjectSummaryRow) UnsetPausedByUserId()`

UnsetPausedByUserId ensures that no value is present for PausedByUserId, not even an explicit nil
### GetPrUrl

`func (o *ProjectSummaryRow) GetPrUrl() string`

GetPrUrl returns the PrUrl field if non-nil, zero value otherwise.

### GetPrUrlOk

`func (o *ProjectSummaryRow) GetPrUrlOk() (*string, bool)`

GetPrUrlOk returns a tuple with the PrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrUrl

`func (o *ProjectSummaryRow) SetPrUrl(v string)`

SetPrUrl sets PrUrl field to given value.


### SetPrUrlNil

`func (o *ProjectSummaryRow) SetPrUrlNil(b bool)`

 SetPrUrlNil sets the value for PrUrl to be an explicit nil

### UnsetPrUrl
`func (o *ProjectSummaryRow) UnsetPrUrl()`

UnsetPrUrl ensures that no value is present for PrUrl, not even an explicit nil
### GetPreviewCommand

`func (o *ProjectSummaryRow) GetPreviewCommand() string`

GetPreviewCommand returns the PreviewCommand field if non-nil, zero value otherwise.

### GetPreviewCommandOk

`func (o *ProjectSummaryRow) GetPreviewCommandOk() (*string, bool)`

GetPreviewCommandOk returns a tuple with the PreviewCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewCommand

`func (o *ProjectSummaryRow) SetPreviewCommand(v string)`

SetPreviewCommand sets PreviewCommand field to given value.


### SetPreviewCommandNil

`func (o *ProjectSummaryRow) SetPreviewCommandNil(b bool)`

 SetPreviewCommandNil sets the value for PreviewCommand to be an explicit nil

### UnsetPreviewCommand
`func (o *ProjectSummaryRow) UnsetPreviewCommand()`

UnsetPreviewCommand ensures that no value is present for PreviewCommand, not even an explicit nil
### GetPreviewMergedAt

`func (o *ProjectSummaryRow) GetPreviewMergedAt() string`

GetPreviewMergedAt returns the PreviewMergedAt field if non-nil, zero value otherwise.

### GetPreviewMergedAtOk

`func (o *ProjectSummaryRow) GetPreviewMergedAtOk() (*string, bool)`

GetPreviewMergedAtOk returns a tuple with the PreviewMergedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewMergedAt

`func (o *ProjectSummaryRow) SetPreviewMergedAt(v string)`

SetPreviewMergedAt sets PreviewMergedAt field to given value.


### SetPreviewMergedAtNil

`func (o *ProjectSummaryRow) SetPreviewMergedAtNil(b bool)`

 SetPreviewMergedAtNil sets the value for PreviewMergedAt to be an explicit nil

### UnsetPreviewMergedAt
`func (o *ProjectSummaryRow) UnsetPreviewMergedAt()`

UnsetPreviewMergedAt ensures that no value is present for PreviewMergedAt, not even an explicit nil
### GetPreviewPort

`func (o *ProjectSummaryRow) GetPreviewPort() int32`

GetPreviewPort returns the PreviewPort field if non-nil, zero value otherwise.

### GetPreviewPortOk

`func (o *ProjectSummaryRow) GetPreviewPortOk() (*int32, bool)`

GetPreviewPortOk returns a tuple with the PreviewPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPort

`func (o *ProjectSummaryRow) SetPreviewPort(v int32)`

SetPreviewPort sets PreviewPort field to given value.


### SetPreviewPortNil

`func (o *ProjectSummaryRow) SetPreviewPortNil(b bool)`

 SetPreviewPortNil sets the value for PreviewPort to be an explicit nil

### UnsetPreviewPort
`func (o *ProjectSummaryRow) UnsetPreviewPort()`

UnsetPreviewPort ensures that no value is present for PreviewPort, not even an explicit nil
### GetRound

`func (o *ProjectSummaryRow) GetRound() int32`

GetRound returns the Round field if non-nil, zero value otherwise.

### GetRoundOk

`func (o *ProjectSummaryRow) GetRoundOk() (*int32, bool)`

GetRoundOk returns a tuple with the Round field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRound

`func (o *ProjectSummaryRow) SetRound(v int32)`

SetRound sets Round field to given value.


### GetRunningAgents

`func (o *ProjectSummaryRow) GetRunningAgents() int32`

GetRunningAgents returns the RunningAgents field if non-nil, zero value otherwise.

### GetRunningAgentsOk

`func (o *ProjectSummaryRow) GetRunningAgentsOk() (*int32, bool)`

GetRunningAgentsOk returns a tuple with the RunningAgents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningAgents

`func (o *ProjectSummaryRow) SetRunningAgents(v int32)`

SetRunningAgents sets RunningAgents field to given value.


### GetRuntime

`func (o *ProjectSummaryRow) GetRuntime() ProjectRuntime`

GetRuntime returns the Runtime field if non-nil, zero value otherwise.

### GetRuntimeOk

`func (o *ProjectSummaryRow) GetRuntimeOk() (*ProjectRuntime, bool)`

GetRuntimeOk returns a tuple with the Runtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntime

`func (o *ProjectSummaryRow) SetRuntime(v ProjectRuntime)`

SetRuntime sets Runtime field to given value.


### GetSetupReport

`func (o *ProjectSummaryRow) GetSetupReport() ProjectSetupReport`

GetSetupReport returns the SetupReport field if non-nil, zero value otherwise.

### GetSetupReportOk

`func (o *ProjectSummaryRow) GetSetupReportOk() (*ProjectSetupReport, bool)`

GetSetupReportOk returns a tuple with the SetupReport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupReport

`func (o *ProjectSummaryRow) SetSetupReport(v ProjectSetupReport)`

SetSetupReport sets SetupReport field to given value.


### SetSetupReportNil

`func (o *ProjectSummaryRow) SetSetupReportNil(b bool)`

 SetSetupReportNil sets the value for SetupReport to be an explicit nil

### UnsetSetupReport
`func (o *ProjectSummaryRow) UnsetSetupReport()`

UnsetSetupReport ensures that no value is present for SetupReport, not even an explicit nil
### GetSlug

`func (o *ProjectSummaryRow) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ProjectSummaryRow) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ProjectSummaryRow) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetSources

`func (o *ProjectSummaryRow) GetSources() ProjectSources`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ProjectSummaryRow) GetSourcesOk() (*ProjectSources, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ProjectSummaryRow) SetSources(v ProjectSources)`

SetSources sets Sources field to given value.


### GetStack

`func (o *ProjectSummaryRow) GetStack() string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *ProjectSummaryRow) GetStackOk() (*string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *ProjectSummaryRow) SetStack(v string)`

SetStack sets Stack field to given value.


### GetStalledRevisions

`func (o *ProjectSummaryRow) GetStalledRevisions() int32`

GetStalledRevisions returns the StalledRevisions field if non-nil, zero value otherwise.

### GetStalledRevisionsOk

`func (o *ProjectSummaryRow) GetStalledRevisionsOk() (*int32, bool)`

GetStalledRevisionsOk returns a tuple with the StalledRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStalledRevisions

`func (o *ProjectSummaryRow) SetStalledRevisions(v int32)`

SetStalledRevisions sets StalledRevisions field to given value.


### GetStatus

`func (o *ProjectSummaryRow) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectSummaryRow) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectSummaryRow) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTier

`func (o *ProjectSummaryRow) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *ProjectSummaryRow) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *ProjectSummaryRow) SetTier(v string)`

SetTier sets Tier field to given value.


### SetTierNil

`func (o *ProjectSummaryRow) SetTierNil(b bool)`

 SetTierNil sets the value for Tier to be an explicit nil

### UnsetTier
`func (o *ProjectSummaryRow) UnsetTier()`

UnsetTier ensures that no value is present for Tier, not even an explicit nil
### GetTotalCostMicros

`func (o *ProjectSummaryRow) GetTotalCostMicros() int64`

GetTotalCostMicros returns the TotalCostMicros field if non-nil, zero value otherwise.

### GetTotalCostMicrosOk

`func (o *ProjectSummaryRow) GetTotalCostMicrosOk() (*int64, bool)`

GetTotalCostMicrosOk returns a tuple with the TotalCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCostMicros

`func (o *ProjectSummaryRow) SetTotalCostMicros(v int64)`

SetTotalCostMicros sets TotalCostMicros field to given value.


### SetTotalCostMicrosNil

`func (o *ProjectSummaryRow) SetTotalCostMicrosNil(b bool)`

 SetTotalCostMicrosNil sets the value for TotalCostMicros to be an explicit nil

### UnsetTotalCostMicros
`func (o *ProjectSummaryRow) UnsetTotalCostMicros()`

UnsetTotalCostMicros ensures that no value is present for TotalCostMicros, not even an explicit nil
### GetUseWorkspaceBrand

`func (o *ProjectSummaryRow) GetUseWorkspaceBrand() bool`

GetUseWorkspaceBrand returns the UseWorkspaceBrand field if non-nil, zero value otherwise.

### GetUseWorkspaceBrandOk

`func (o *ProjectSummaryRow) GetUseWorkspaceBrandOk() (*bool, bool)`

GetUseWorkspaceBrandOk returns a tuple with the UseWorkspaceBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWorkspaceBrand

`func (o *ProjectSummaryRow) SetUseWorkspaceBrand(v bool)`

SetUseWorkspaceBrand sets UseWorkspaceBrand field to given value.


### GetVerifyCommand

`func (o *ProjectSummaryRow) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *ProjectSummaryRow) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *ProjectSummaryRow) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.


### SetVerifyCommandNil

`func (o *ProjectSummaryRow) SetVerifyCommandNil(b bool)`

 SetVerifyCommandNil sets the value for VerifyCommand to be an explicit nil

### UnsetVerifyCommand
`func (o *ProjectSummaryRow) UnsetVerifyCommand()`

UnsetVerifyCommand ensures that no value is present for VerifyCommand, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


