# ProjectRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | **NullableString** |  | 
**AssignedUserId** | **NullableString** |  | 
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
**DetectedCommands** | [**NullableProjectDetectedCommands**](ProjectDetectedCommands.md) |  | 
**EnvironmentSnapshot** | [**NullableProjectEnvironmentSnapshot**](ProjectEnvironmentSnapshot.md) |  | 
**ExtraUsage** | **NullableString** |  | 
**GrowthAutopilot** | **bool** |  | 
**GrowthDailyBudgetMicros** | **NullableInt64** |  | 
**GrowthSendingSchedule** | [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  | 
**Id** | **string** |  | 
**InitialProposalRequired** | **bool** |  | 
**Intake** | [**ProjectIntake**](ProjectIntake.md) |  | 
**Iteration** | **int32** |  | 
**Kind** | **string** |  | 
**MaxRevisions** | **NullableInt32** |  | 
**MobileTargetsInitialized** | **bool** |  | 
**Name** | **string** |  | 
**OrganizationId** | **string** |  | 
**PausedAt** | **NullableString** |  | 
**PausedByUserId** | **NullableString** |  | 
**PrUrl** | **NullableString** |  | 
**PreviewCommand** | **NullableString** |  | 
**PreviewPort** | **NullableInt32** |  | 
**Round** | **int32** |  | 
**Runtime** | [**ProjectRuntime**](ProjectRuntime.md) |  | 
**SandboxSize** | **NullableString** |  | 
**SetupReport** | [**NullableProjectSetupReport**](ProjectSetupReport.md) |  | 
**Slug** | **string** |  | 
**Stack** | **string** |  | 
**StalledRevisions** | **int32** |  | 
**Tier** | **NullableString** |  | 
**UseWorkspaceBrand** | **bool** |  | 
**VerifyCommand** | **NullableString** |  | 

## Methods

### NewProjectRow

`func NewProjectRow(archivedAt NullableString, assignedUserId NullableString, branchNames string, branchPrefix NullableString, branchPrefixLockedAt NullableString, brief NullableString, claudeMd NullableString, clientAccountId NullableString, completedAtLastRevision int32, costCapMicros NullableInt64, createdAt string, customDomain NullableString, cycleCap NullableInt32, detectedCommands NullableProjectDetectedCommands, environmentSnapshot NullableProjectEnvironmentSnapshot, extraUsage NullableString, growthAutopilot bool, growthDailyBudgetMicros NullableInt64, growthSendingSchedule NullableCreateGrowthPlaySendingSchedule, id string, initialProposalRequired bool, intake ProjectIntake, iteration int32, kind string, maxRevisions NullableInt32, mobileTargetsInitialized bool, name string, organizationId string, pausedAt NullableString, pausedByUserId NullableString, prUrl NullableString, previewCommand NullableString, previewPort NullableInt32, round int32, runtime ProjectRuntime, sandboxSize NullableString, setupReport NullableProjectSetupReport, slug string, stack string, stalledRevisions int32, tier NullableString, useWorkspaceBrand bool, verifyCommand NullableString, ) *ProjectRow`

NewProjectRow instantiates a new ProjectRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectRowWithDefaults

`func NewProjectRowWithDefaults() *ProjectRow`

NewProjectRowWithDefaults instantiates a new ProjectRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchivedAt

`func (o *ProjectRow) GetArchivedAt() string`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ProjectRow) GetArchivedAtOk() (*string, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ProjectRow) SetArchivedAt(v string)`

SetArchivedAt sets ArchivedAt field to given value.


### SetArchivedAtNil

`func (o *ProjectRow) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ProjectRow) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetAssignedUserId

`func (o *ProjectRow) GetAssignedUserId() string`

GetAssignedUserId returns the AssignedUserId field if non-nil, zero value otherwise.

### GetAssignedUserIdOk

`func (o *ProjectRow) GetAssignedUserIdOk() (*string, bool)`

GetAssignedUserIdOk returns a tuple with the AssignedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignedUserId

`func (o *ProjectRow) SetAssignedUserId(v string)`

SetAssignedUserId sets AssignedUserId field to given value.


### SetAssignedUserIdNil

`func (o *ProjectRow) SetAssignedUserIdNil(b bool)`

 SetAssignedUserIdNil sets the value for AssignedUserId to be an explicit nil

### UnsetAssignedUserId
`func (o *ProjectRow) UnsetAssignedUserId()`

UnsetAssignedUserId ensures that no value is present for AssignedUserId, not even an explicit nil
### GetBranchNames

`func (o *ProjectRow) GetBranchNames() string`

GetBranchNames returns the BranchNames field if non-nil, zero value otherwise.

### GetBranchNamesOk

`func (o *ProjectRow) GetBranchNamesOk() (*string, bool)`

GetBranchNamesOk returns a tuple with the BranchNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchNames

`func (o *ProjectRow) SetBranchNames(v string)`

SetBranchNames sets BranchNames field to given value.


### GetBranchPrefix

`func (o *ProjectRow) GetBranchPrefix() string`

GetBranchPrefix returns the BranchPrefix field if non-nil, zero value otherwise.

### GetBranchPrefixOk

`func (o *ProjectRow) GetBranchPrefixOk() (*string, bool)`

GetBranchPrefixOk returns a tuple with the BranchPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefix

`func (o *ProjectRow) SetBranchPrefix(v string)`

SetBranchPrefix sets BranchPrefix field to given value.


### SetBranchPrefixNil

`func (o *ProjectRow) SetBranchPrefixNil(b bool)`

 SetBranchPrefixNil sets the value for BranchPrefix to be an explicit nil

### UnsetBranchPrefix
`func (o *ProjectRow) UnsetBranchPrefix()`

UnsetBranchPrefix ensures that no value is present for BranchPrefix, not even an explicit nil
### GetBranchPrefixLockedAt

`func (o *ProjectRow) GetBranchPrefixLockedAt() string`

GetBranchPrefixLockedAt returns the BranchPrefixLockedAt field if non-nil, zero value otherwise.

### GetBranchPrefixLockedAtOk

`func (o *ProjectRow) GetBranchPrefixLockedAtOk() (*string, bool)`

GetBranchPrefixLockedAtOk returns a tuple with the BranchPrefixLockedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefixLockedAt

`func (o *ProjectRow) SetBranchPrefixLockedAt(v string)`

SetBranchPrefixLockedAt sets BranchPrefixLockedAt field to given value.


### SetBranchPrefixLockedAtNil

`func (o *ProjectRow) SetBranchPrefixLockedAtNil(b bool)`

 SetBranchPrefixLockedAtNil sets the value for BranchPrefixLockedAt to be an explicit nil

### UnsetBranchPrefixLockedAt
`func (o *ProjectRow) UnsetBranchPrefixLockedAt()`

UnsetBranchPrefixLockedAt ensures that no value is present for BranchPrefixLockedAt, not even an explicit nil
### GetBrief

`func (o *ProjectRow) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *ProjectRow) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *ProjectRow) SetBrief(v string)`

SetBrief sets Brief field to given value.


### SetBriefNil

`func (o *ProjectRow) SetBriefNil(b bool)`

 SetBriefNil sets the value for Brief to be an explicit nil

### UnsetBrief
`func (o *ProjectRow) UnsetBrief()`

UnsetBrief ensures that no value is present for Brief, not even an explicit nil
### GetClaudeMd

`func (o *ProjectRow) GetClaudeMd() string`

GetClaudeMd returns the ClaudeMd field if non-nil, zero value otherwise.

### GetClaudeMdOk

`func (o *ProjectRow) GetClaudeMdOk() (*string, bool)`

GetClaudeMdOk returns a tuple with the ClaudeMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaudeMd

`func (o *ProjectRow) SetClaudeMd(v string)`

SetClaudeMd sets ClaudeMd field to given value.


### SetClaudeMdNil

`func (o *ProjectRow) SetClaudeMdNil(b bool)`

 SetClaudeMdNil sets the value for ClaudeMd to be an explicit nil

### UnsetClaudeMd
`func (o *ProjectRow) UnsetClaudeMd()`

UnsetClaudeMd ensures that no value is present for ClaudeMd, not even an explicit nil
### GetClientAccountId

`func (o *ProjectRow) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *ProjectRow) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *ProjectRow) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *ProjectRow) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *ProjectRow) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetCompletedAtLastRevision

`func (o *ProjectRow) GetCompletedAtLastRevision() int32`

GetCompletedAtLastRevision returns the CompletedAtLastRevision field if non-nil, zero value otherwise.

### GetCompletedAtLastRevisionOk

`func (o *ProjectRow) GetCompletedAtLastRevisionOk() (*int32, bool)`

GetCompletedAtLastRevisionOk returns a tuple with the CompletedAtLastRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAtLastRevision

`func (o *ProjectRow) SetCompletedAtLastRevision(v int32)`

SetCompletedAtLastRevision sets CompletedAtLastRevision field to given value.


### GetCostCapMicros

`func (o *ProjectRow) GetCostCapMicros() int64`

GetCostCapMicros returns the CostCapMicros field if non-nil, zero value otherwise.

### GetCostCapMicrosOk

`func (o *ProjectRow) GetCostCapMicrosOk() (*int64, bool)`

GetCostCapMicrosOk returns a tuple with the CostCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCapMicros

`func (o *ProjectRow) SetCostCapMicros(v int64)`

SetCostCapMicros sets CostCapMicros field to given value.


### SetCostCapMicrosNil

`func (o *ProjectRow) SetCostCapMicrosNil(b bool)`

 SetCostCapMicrosNil sets the value for CostCapMicros to be an explicit nil

### UnsetCostCapMicros
`func (o *ProjectRow) UnsetCostCapMicros()`

UnsetCostCapMicros ensures that no value is present for CostCapMicros, not even an explicit nil
### GetCreatedAt

`func (o *ProjectRow) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ProjectRow) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ProjectRow) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomDomain

`func (o *ProjectRow) GetCustomDomain() string`

GetCustomDomain returns the CustomDomain field if non-nil, zero value otherwise.

### GetCustomDomainOk

`func (o *ProjectRow) GetCustomDomainOk() (*string, bool)`

GetCustomDomainOk returns a tuple with the CustomDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomDomain

`func (o *ProjectRow) SetCustomDomain(v string)`

SetCustomDomain sets CustomDomain field to given value.


### SetCustomDomainNil

`func (o *ProjectRow) SetCustomDomainNil(b bool)`

 SetCustomDomainNil sets the value for CustomDomain to be an explicit nil

### UnsetCustomDomain
`func (o *ProjectRow) UnsetCustomDomain()`

UnsetCustomDomain ensures that no value is present for CustomDomain, not even an explicit nil
### GetCycleCap

`func (o *ProjectRow) GetCycleCap() int32`

GetCycleCap returns the CycleCap field if non-nil, zero value otherwise.

### GetCycleCapOk

`func (o *ProjectRow) GetCycleCapOk() (*int32, bool)`

GetCycleCapOk returns a tuple with the CycleCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleCap

`func (o *ProjectRow) SetCycleCap(v int32)`

SetCycleCap sets CycleCap field to given value.


### SetCycleCapNil

`func (o *ProjectRow) SetCycleCapNil(b bool)`

 SetCycleCapNil sets the value for CycleCap to be an explicit nil

### UnsetCycleCap
`func (o *ProjectRow) UnsetCycleCap()`

UnsetCycleCap ensures that no value is present for CycleCap, not even an explicit nil
### GetDetectedCommands

`func (o *ProjectRow) GetDetectedCommands() ProjectDetectedCommands`

GetDetectedCommands returns the DetectedCommands field if non-nil, zero value otherwise.

### GetDetectedCommandsOk

`func (o *ProjectRow) GetDetectedCommandsOk() (*ProjectDetectedCommands, bool)`

GetDetectedCommandsOk returns a tuple with the DetectedCommands field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetectedCommands

`func (o *ProjectRow) SetDetectedCommands(v ProjectDetectedCommands)`

SetDetectedCommands sets DetectedCommands field to given value.


### SetDetectedCommandsNil

`func (o *ProjectRow) SetDetectedCommandsNil(b bool)`

 SetDetectedCommandsNil sets the value for DetectedCommands to be an explicit nil

### UnsetDetectedCommands
`func (o *ProjectRow) UnsetDetectedCommands()`

UnsetDetectedCommands ensures that no value is present for DetectedCommands, not even an explicit nil
### GetEnvironmentSnapshot

`func (o *ProjectRow) GetEnvironmentSnapshot() ProjectEnvironmentSnapshot`

GetEnvironmentSnapshot returns the EnvironmentSnapshot field if non-nil, zero value otherwise.

### GetEnvironmentSnapshotOk

`func (o *ProjectRow) GetEnvironmentSnapshotOk() (*ProjectEnvironmentSnapshot, bool)`

GetEnvironmentSnapshotOk returns a tuple with the EnvironmentSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironmentSnapshot

`func (o *ProjectRow) SetEnvironmentSnapshot(v ProjectEnvironmentSnapshot)`

SetEnvironmentSnapshot sets EnvironmentSnapshot field to given value.


### SetEnvironmentSnapshotNil

`func (o *ProjectRow) SetEnvironmentSnapshotNil(b bool)`

 SetEnvironmentSnapshotNil sets the value for EnvironmentSnapshot to be an explicit nil

### UnsetEnvironmentSnapshot
`func (o *ProjectRow) UnsetEnvironmentSnapshot()`

UnsetEnvironmentSnapshot ensures that no value is present for EnvironmentSnapshot, not even an explicit nil
### GetExtraUsage

`func (o *ProjectRow) GetExtraUsage() string`

GetExtraUsage returns the ExtraUsage field if non-nil, zero value otherwise.

### GetExtraUsageOk

`func (o *ProjectRow) GetExtraUsageOk() (*string, bool)`

GetExtraUsageOk returns a tuple with the ExtraUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraUsage

`func (o *ProjectRow) SetExtraUsage(v string)`

SetExtraUsage sets ExtraUsage field to given value.


### SetExtraUsageNil

`func (o *ProjectRow) SetExtraUsageNil(b bool)`

 SetExtraUsageNil sets the value for ExtraUsage to be an explicit nil

### UnsetExtraUsage
`func (o *ProjectRow) UnsetExtraUsage()`

UnsetExtraUsage ensures that no value is present for ExtraUsage, not even an explicit nil
### GetGrowthAutopilot

`func (o *ProjectRow) GetGrowthAutopilot() bool`

GetGrowthAutopilot returns the GrowthAutopilot field if non-nil, zero value otherwise.

### GetGrowthAutopilotOk

`func (o *ProjectRow) GetGrowthAutopilotOk() (*bool, bool)`

GetGrowthAutopilotOk returns a tuple with the GrowthAutopilot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthAutopilot

`func (o *ProjectRow) SetGrowthAutopilot(v bool)`

SetGrowthAutopilot sets GrowthAutopilot field to given value.


### GetGrowthDailyBudgetMicros

`func (o *ProjectRow) GetGrowthDailyBudgetMicros() int64`

GetGrowthDailyBudgetMicros returns the GrowthDailyBudgetMicros field if non-nil, zero value otherwise.

### GetGrowthDailyBudgetMicrosOk

`func (o *ProjectRow) GetGrowthDailyBudgetMicrosOk() (*int64, bool)`

GetGrowthDailyBudgetMicrosOk returns a tuple with the GrowthDailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthDailyBudgetMicros

`func (o *ProjectRow) SetGrowthDailyBudgetMicros(v int64)`

SetGrowthDailyBudgetMicros sets GrowthDailyBudgetMicros field to given value.


### SetGrowthDailyBudgetMicrosNil

`func (o *ProjectRow) SetGrowthDailyBudgetMicrosNil(b bool)`

 SetGrowthDailyBudgetMicrosNil sets the value for GrowthDailyBudgetMicros to be an explicit nil

### UnsetGrowthDailyBudgetMicros
`func (o *ProjectRow) UnsetGrowthDailyBudgetMicros()`

UnsetGrowthDailyBudgetMicros ensures that no value is present for GrowthDailyBudgetMicros, not even an explicit nil
### GetGrowthSendingSchedule

`func (o *ProjectRow) GetGrowthSendingSchedule() CreateGrowthPlaySendingSchedule`

GetGrowthSendingSchedule returns the GrowthSendingSchedule field if non-nil, zero value otherwise.

### GetGrowthSendingScheduleOk

`func (o *ProjectRow) GetGrowthSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetGrowthSendingScheduleOk returns a tuple with the GrowthSendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthSendingSchedule

`func (o *ProjectRow) SetGrowthSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetGrowthSendingSchedule sets GrowthSendingSchedule field to given value.


### SetGrowthSendingScheduleNil

`func (o *ProjectRow) SetGrowthSendingScheduleNil(b bool)`

 SetGrowthSendingScheduleNil sets the value for GrowthSendingSchedule to be an explicit nil

### UnsetGrowthSendingSchedule
`func (o *ProjectRow) UnsetGrowthSendingSchedule()`

UnsetGrowthSendingSchedule ensures that no value is present for GrowthSendingSchedule, not even an explicit nil
### GetId

`func (o *ProjectRow) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ProjectRow) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ProjectRow) SetId(v string)`

SetId sets Id field to given value.


### GetInitialProposalRequired

`func (o *ProjectRow) GetInitialProposalRequired() bool`

GetInitialProposalRequired returns the InitialProposalRequired field if non-nil, zero value otherwise.

### GetInitialProposalRequiredOk

`func (o *ProjectRow) GetInitialProposalRequiredOk() (*bool, bool)`

GetInitialProposalRequiredOk returns a tuple with the InitialProposalRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialProposalRequired

`func (o *ProjectRow) SetInitialProposalRequired(v bool)`

SetInitialProposalRequired sets InitialProposalRequired field to given value.


### GetIntake

`func (o *ProjectRow) GetIntake() ProjectIntake`

GetIntake returns the Intake field if non-nil, zero value otherwise.

### GetIntakeOk

`func (o *ProjectRow) GetIntakeOk() (*ProjectIntake, bool)`

GetIntakeOk returns a tuple with the Intake field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntake

`func (o *ProjectRow) SetIntake(v ProjectIntake)`

SetIntake sets Intake field to given value.


### GetIteration

`func (o *ProjectRow) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *ProjectRow) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *ProjectRow) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### GetKind

`func (o *ProjectRow) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProjectRow) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProjectRow) SetKind(v string)`

SetKind sets Kind field to given value.


### GetMaxRevisions

`func (o *ProjectRow) GetMaxRevisions() int32`

GetMaxRevisions returns the MaxRevisions field if non-nil, zero value otherwise.

### GetMaxRevisionsOk

`func (o *ProjectRow) GetMaxRevisionsOk() (*int32, bool)`

GetMaxRevisionsOk returns a tuple with the MaxRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRevisions

`func (o *ProjectRow) SetMaxRevisions(v int32)`

SetMaxRevisions sets MaxRevisions field to given value.


### SetMaxRevisionsNil

`func (o *ProjectRow) SetMaxRevisionsNil(b bool)`

 SetMaxRevisionsNil sets the value for MaxRevisions to be an explicit nil

### UnsetMaxRevisions
`func (o *ProjectRow) UnsetMaxRevisions()`

UnsetMaxRevisions ensures that no value is present for MaxRevisions, not even an explicit nil
### GetMobileTargetsInitialized

`func (o *ProjectRow) GetMobileTargetsInitialized() bool`

GetMobileTargetsInitialized returns the MobileTargetsInitialized field if non-nil, zero value otherwise.

### GetMobileTargetsInitializedOk

`func (o *ProjectRow) GetMobileTargetsInitializedOk() (*bool, bool)`

GetMobileTargetsInitializedOk returns a tuple with the MobileTargetsInitialized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobileTargetsInitialized

`func (o *ProjectRow) SetMobileTargetsInitialized(v bool)`

SetMobileTargetsInitialized sets MobileTargetsInitialized field to given value.


### GetName

`func (o *ProjectRow) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ProjectRow) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ProjectRow) SetName(v string)`

SetName sets Name field to given value.


### GetOrganizationId

`func (o *ProjectRow) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ProjectRow) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ProjectRow) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPausedAt

`func (o *ProjectRow) GetPausedAt() string`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *ProjectRow) GetPausedAtOk() (*string, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *ProjectRow) SetPausedAt(v string)`

SetPausedAt sets PausedAt field to given value.


### SetPausedAtNil

`func (o *ProjectRow) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *ProjectRow) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetPausedByUserId

`func (o *ProjectRow) GetPausedByUserId() string`

GetPausedByUserId returns the PausedByUserId field if non-nil, zero value otherwise.

### GetPausedByUserIdOk

`func (o *ProjectRow) GetPausedByUserIdOk() (*string, bool)`

GetPausedByUserIdOk returns a tuple with the PausedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedByUserId

`func (o *ProjectRow) SetPausedByUserId(v string)`

SetPausedByUserId sets PausedByUserId field to given value.


### SetPausedByUserIdNil

`func (o *ProjectRow) SetPausedByUserIdNil(b bool)`

 SetPausedByUserIdNil sets the value for PausedByUserId to be an explicit nil

### UnsetPausedByUserId
`func (o *ProjectRow) UnsetPausedByUserId()`

UnsetPausedByUserId ensures that no value is present for PausedByUserId, not even an explicit nil
### GetPrUrl

`func (o *ProjectRow) GetPrUrl() string`

GetPrUrl returns the PrUrl field if non-nil, zero value otherwise.

### GetPrUrlOk

`func (o *ProjectRow) GetPrUrlOk() (*string, bool)`

GetPrUrlOk returns a tuple with the PrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrUrl

`func (o *ProjectRow) SetPrUrl(v string)`

SetPrUrl sets PrUrl field to given value.


### SetPrUrlNil

`func (o *ProjectRow) SetPrUrlNil(b bool)`

 SetPrUrlNil sets the value for PrUrl to be an explicit nil

### UnsetPrUrl
`func (o *ProjectRow) UnsetPrUrl()`

UnsetPrUrl ensures that no value is present for PrUrl, not even an explicit nil
### GetPreviewCommand

`func (o *ProjectRow) GetPreviewCommand() string`

GetPreviewCommand returns the PreviewCommand field if non-nil, zero value otherwise.

### GetPreviewCommandOk

`func (o *ProjectRow) GetPreviewCommandOk() (*string, bool)`

GetPreviewCommandOk returns a tuple with the PreviewCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewCommand

`func (o *ProjectRow) SetPreviewCommand(v string)`

SetPreviewCommand sets PreviewCommand field to given value.


### SetPreviewCommandNil

`func (o *ProjectRow) SetPreviewCommandNil(b bool)`

 SetPreviewCommandNil sets the value for PreviewCommand to be an explicit nil

### UnsetPreviewCommand
`func (o *ProjectRow) UnsetPreviewCommand()`

UnsetPreviewCommand ensures that no value is present for PreviewCommand, not even an explicit nil
### GetPreviewPort

`func (o *ProjectRow) GetPreviewPort() int32`

GetPreviewPort returns the PreviewPort field if non-nil, zero value otherwise.

### GetPreviewPortOk

`func (o *ProjectRow) GetPreviewPortOk() (*int32, bool)`

GetPreviewPortOk returns a tuple with the PreviewPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPort

`func (o *ProjectRow) SetPreviewPort(v int32)`

SetPreviewPort sets PreviewPort field to given value.


### SetPreviewPortNil

`func (o *ProjectRow) SetPreviewPortNil(b bool)`

 SetPreviewPortNil sets the value for PreviewPort to be an explicit nil

### UnsetPreviewPort
`func (o *ProjectRow) UnsetPreviewPort()`

UnsetPreviewPort ensures that no value is present for PreviewPort, not even an explicit nil
### GetRound

`func (o *ProjectRow) GetRound() int32`

GetRound returns the Round field if non-nil, zero value otherwise.

### GetRoundOk

`func (o *ProjectRow) GetRoundOk() (*int32, bool)`

GetRoundOk returns a tuple with the Round field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRound

`func (o *ProjectRow) SetRound(v int32)`

SetRound sets Round field to given value.


### GetRuntime

`func (o *ProjectRow) GetRuntime() ProjectRuntime`

GetRuntime returns the Runtime field if non-nil, zero value otherwise.

### GetRuntimeOk

`func (o *ProjectRow) GetRuntimeOk() (*ProjectRuntime, bool)`

GetRuntimeOk returns a tuple with the Runtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntime

`func (o *ProjectRow) SetRuntime(v ProjectRuntime)`

SetRuntime sets Runtime field to given value.


### GetSandboxSize

`func (o *ProjectRow) GetSandboxSize() string`

GetSandboxSize returns the SandboxSize field if non-nil, zero value otherwise.

### GetSandboxSizeOk

`func (o *ProjectRow) GetSandboxSizeOk() (*string, bool)`

GetSandboxSizeOk returns a tuple with the SandboxSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSandboxSize

`func (o *ProjectRow) SetSandboxSize(v string)`

SetSandboxSize sets SandboxSize field to given value.


### SetSandboxSizeNil

`func (o *ProjectRow) SetSandboxSizeNil(b bool)`

 SetSandboxSizeNil sets the value for SandboxSize to be an explicit nil

### UnsetSandboxSize
`func (o *ProjectRow) UnsetSandboxSize()`

UnsetSandboxSize ensures that no value is present for SandboxSize, not even an explicit nil
### GetSetupReport

`func (o *ProjectRow) GetSetupReport() ProjectSetupReport`

GetSetupReport returns the SetupReport field if non-nil, zero value otherwise.

### GetSetupReportOk

`func (o *ProjectRow) GetSetupReportOk() (*ProjectSetupReport, bool)`

GetSetupReportOk returns a tuple with the SetupReport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupReport

`func (o *ProjectRow) SetSetupReport(v ProjectSetupReport)`

SetSetupReport sets SetupReport field to given value.


### SetSetupReportNil

`func (o *ProjectRow) SetSetupReportNil(b bool)`

 SetSetupReportNil sets the value for SetupReport to be an explicit nil

### UnsetSetupReport
`func (o *ProjectRow) UnsetSetupReport()`

UnsetSetupReport ensures that no value is present for SetupReport, not even an explicit nil
### GetSlug

`func (o *ProjectRow) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ProjectRow) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ProjectRow) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetStack

`func (o *ProjectRow) GetStack() string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *ProjectRow) GetStackOk() (*string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *ProjectRow) SetStack(v string)`

SetStack sets Stack field to given value.


### GetStalledRevisions

`func (o *ProjectRow) GetStalledRevisions() int32`

GetStalledRevisions returns the StalledRevisions field if non-nil, zero value otherwise.

### GetStalledRevisionsOk

`func (o *ProjectRow) GetStalledRevisionsOk() (*int32, bool)`

GetStalledRevisionsOk returns a tuple with the StalledRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStalledRevisions

`func (o *ProjectRow) SetStalledRevisions(v int32)`

SetStalledRevisions sets StalledRevisions field to given value.


### GetTier

`func (o *ProjectRow) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *ProjectRow) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *ProjectRow) SetTier(v string)`

SetTier sets Tier field to given value.


### SetTierNil

`func (o *ProjectRow) SetTierNil(b bool)`

 SetTierNil sets the value for Tier to be an explicit nil

### UnsetTier
`func (o *ProjectRow) UnsetTier()`

UnsetTier ensures that no value is present for Tier, not even an explicit nil
### GetUseWorkspaceBrand

`func (o *ProjectRow) GetUseWorkspaceBrand() bool`

GetUseWorkspaceBrand returns the UseWorkspaceBrand field if non-nil, zero value otherwise.

### GetUseWorkspaceBrandOk

`func (o *ProjectRow) GetUseWorkspaceBrandOk() (*bool, bool)`

GetUseWorkspaceBrandOk returns a tuple with the UseWorkspaceBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWorkspaceBrand

`func (o *ProjectRow) SetUseWorkspaceBrand(v bool)`

SetUseWorkspaceBrand sets UseWorkspaceBrand field to given value.


### GetVerifyCommand

`func (o *ProjectRow) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *ProjectRow) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *ProjectRow) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.


### SetVerifyCommandNil

`func (o *ProjectRow) SetVerifyCommandNil(b bool)`

 SetVerifyCommandNil sets the value for VerifyCommand to be an explicit nil

### UnsetVerifyCommand
`func (o *ProjectRow) UnsetVerifyCommand()`

UnsetVerifyCommand ensures that no value is present for VerifyCommand, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


