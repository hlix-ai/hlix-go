# Task

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentId** | **NullableString** |  |
**BillableCostMicros** | **NullableInt64** |  |
**CostMicros** | **NullableInt64** |  |
**CreatedAt** | **string** |  |
**CurrentStage** | **NullableString** |  |
**CycleId** | **NullableString** |  |
**DeliveryEvidence** | Pointer to [**CycleDetailTasksInnerDeliveryEvidence**](CycleDetailTasksInnerDeliveryEvidence.md) |  | [optional]
**Description** | **string** |  |
**DoingSince** | **NullableString** |  |
**DoneWhen** | **NullableString** |  |
**HeadSha** | **NullableString** |  |
**Id** | **string** |  |
**ImplementationPlan** | **NullableString** |  |
**Iteration** | **int32** |  |
**Metadata** | **interface{}** |  |
**Note** | **NullableString** |  |
**OrganizationId** | **string** |  |
**Pipeline** | **interface{}** |  |
**ProjectId** | **string** |  |
**RepoId** | **NullableString** |  |
**RequirementsSummary** | **NullableString** |  |
**ReviewFeedback** | **NullableString** |  |
**ReviewRounds** | **int32** |  |
**SortOrder** | **int32** |  |
**Source** | **string** |  |
**Status** | **string** |  |
**Title** | **NullableString** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewTask

`func NewTask(agentId NullableString, billableCostMicros NullableInt64, costMicros NullableInt64, createdAt string, currentStage NullableString, cycleId NullableString, description string, doingSince NullableString, doneWhen NullableString, headSha NullableString, id string, implementationPlan NullableString, iteration int32, metadata interface{}, note NullableString, organizationId string, pipeline interface{}, projectId string, repoId NullableString, requirementsSummary NullableString, reviewFeedback NullableString, reviewRounds int32, sortOrder int32, source string, status string, title NullableString, updatedAt string, ) *Task`

NewTask instantiates a new Task object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewTaskWithDefaults

`func NewTaskWithDefaults() *Task`

NewTaskWithDefaults instantiates a new Task object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentId

`func (o *Task) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *Task) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *Task) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.


### SetAgentIdNil

`func (o *Task) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *Task) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetBillableCostMicros

`func (o *Task) GetBillableCostMicros() int64`

GetBillableCostMicros returns the BillableCostMicros field if non-nil, zero value otherwise.

### GetBillableCostMicrosOk

`func (o *Task) GetBillableCostMicrosOk() (*int64, bool)`

GetBillableCostMicrosOk returns a tuple with the BillableCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillableCostMicros

`func (o *Task) SetBillableCostMicros(v int64)`

SetBillableCostMicros sets BillableCostMicros field to given value.


### SetBillableCostMicrosNil

`func (o *Task) SetBillableCostMicrosNil(b bool)`

 SetBillableCostMicrosNil sets the value for BillableCostMicros to be an explicit nil

### UnsetBillableCostMicros
`func (o *Task) UnsetBillableCostMicros()`

UnsetBillableCostMicros ensures that no value is present for BillableCostMicros, not even an explicit nil
### GetCostMicros

`func (o *Task) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *Task) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *Task) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *Task) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *Task) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCreatedAt

`func (o *Task) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Task) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Task) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrentStage

`func (o *Task) GetCurrentStage() string`

GetCurrentStage returns the CurrentStage field if non-nil, zero value otherwise.

### GetCurrentStageOk

`func (o *Task) GetCurrentStageOk() (*string, bool)`

GetCurrentStageOk returns a tuple with the CurrentStage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStage

`func (o *Task) SetCurrentStage(v string)`

SetCurrentStage sets CurrentStage field to given value.


### SetCurrentStageNil

`func (o *Task) SetCurrentStageNil(b bool)`

 SetCurrentStageNil sets the value for CurrentStage to be an explicit nil

### UnsetCurrentStage
`func (o *Task) UnsetCurrentStage()`

UnsetCurrentStage ensures that no value is present for CurrentStage, not even an explicit nil
### GetCycleId

`func (o *Task) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *Task) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *Task) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *Task) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *Task) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDeliveryEvidence

`func (o *Task) GetDeliveryEvidence() CycleDetailTasksInnerDeliveryEvidence`

GetDeliveryEvidence returns the DeliveryEvidence field if non-nil, zero value otherwise.

### GetDeliveryEvidenceOk

`func (o *Task) GetDeliveryEvidenceOk() (*CycleDetailTasksInnerDeliveryEvidence, bool)`

GetDeliveryEvidenceOk returns a tuple with the DeliveryEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryEvidence

`func (o *Task) SetDeliveryEvidence(v CycleDetailTasksInnerDeliveryEvidence)`

SetDeliveryEvidence sets DeliveryEvidence field to given value.

### HasDeliveryEvidence

`func (o *Task) HasDeliveryEvidence() bool`

HasDeliveryEvidence returns a boolean if a field has been set.

### GetDescription

`func (o *Task) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Task) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Task) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetDoingSince

`func (o *Task) GetDoingSince() string`

GetDoingSince returns the DoingSince field if non-nil, zero value otherwise.

### GetDoingSinceOk

`func (o *Task) GetDoingSinceOk() (*string, bool)`

GetDoingSinceOk returns a tuple with the DoingSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoingSince

`func (o *Task) SetDoingSince(v string)`

SetDoingSince sets DoingSince field to given value.


### SetDoingSinceNil

`func (o *Task) SetDoingSinceNil(b bool)`

 SetDoingSinceNil sets the value for DoingSince to be an explicit nil

### UnsetDoingSince
`func (o *Task) UnsetDoingSince()`

UnsetDoingSince ensures that no value is present for DoingSince, not even an explicit nil
### GetDoneWhen

`func (o *Task) GetDoneWhen() string`

GetDoneWhen returns the DoneWhen field if non-nil, zero value otherwise.

### GetDoneWhenOk

`func (o *Task) GetDoneWhenOk() (*string, bool)`

GetDoneWhenOk returns a tuple with the DoneWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoneWhen

`func (o *Task) SetDoneWhen(v string)`

SetDoneWhen sets DoneWhen field to given value.


### SetDoneWhenNil

`func (o *Task) SetDoneWhenNil(b bool)`

 SetDoneWhenNil sets the value for DoneWhen to be an explicit nil

### UnsetDoneWhen
`func (o *Task) UnsetDoneWhen()`

UnsetDoneWhen ensures that no value is present for DoneWhen, not even an explicit nil
### GetHeadSha

`func (o *Task) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *Task) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *Task) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### SetHeadShaNil

`func (o *Task) SetHeadShaNil(b bool)`

 SetHeadShaNil sets the value for HeadSha to be an explicit nil

### UnsetHeadSha
`func (o *Task) UnsetHeadSha()`

UnsetHeadSha ensures that no value is present for HeadSha, not even an explicit nil
### GetId

`func (o *Task) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Task) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Task) SetId(v string)`

SetId sets Id field to given value.


### GetImplementationPlan

`func (o *Task) GetImplementationPlan() string`

GetImplementationPlan returns the ImplementationPlan field if non-nil, zero value otherwise.

### GetImplementationPlanOk

`func (o *Task) GetImplementationPlanOk() (*string, bool)`

GetImplementationPlanOk returns a tuple with the ImplementationPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImplementationPlan

`func (o *Task) SetImplementationPlan(v string)`

SetImplementationPlan sets ImplementationPlan field to given value.


### SetImplementationPlanNil

`func (o *Task) SetImplementationPlanNil(b bool)`

 SetImplementationPlanNil sets the value for ImplementationPlan to be an explicit nil

### UnsetImplementationPlan
`func (o *Task) UnsetImplementationPlan()`

UnsetImplementationPlan ensures that no value is present for ImplementationPlan, not even an explicit nil
### GetIteration

`func (o *Task) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *Task) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *Task) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### GetMetadata

`func (o *Task) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Task) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Task) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *Task) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *Task) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetNote

`func (o *Task) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *Task) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *Task) SetNote(v string)`

SetNote sets Note field to given value.


### SetNoteNil

`func (o *Task) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *Task) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetOrganizationId

`func (o *Task) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Task) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Task) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPipeline

`func (o *Task) GetPipeline() interface{}`

GetPipeline returns the Pipeline field if non-nil, zero value otherwise.

### GetPipelineOk

`func (o *Task) GetPipelineOk() (*interface{}, bool)`

GetPipelineOk returns a tuple with the Pipeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipeline

`func (o *Task) SetPipeline(v interface{})`

SetPipeline sets Pipeline field to given value.


### SetPipelineNil

`func (o *Task) SetPipelineNil(b bool)`

 SetPipelineNil sets the value for Pipeline to be an explicit nil

### UnsetPipeline
`func (o *Task) UnsetPipeline()`

UnsetPipeline ensures that no value is present for Pipeline, not even an explicit nil
### GetProjectId

`func (o *Task) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Task) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Task) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRepoId

`func (o *Task) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *Task) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *Task) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.


### SetRepoIdNil

`func (o *Task) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *Task) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetRequirementsSummary

`func (o *Task) GetRequirementsSummary() string`

GetRequirementsSummary returns the RequirementsSummary field if non-nil, zero value otherwise.

### GetRequirementsSummaryOk

`func (o *Task) GetRequirementsSummaryOk() (*string, bool)`

GetRequirementsSummaryOk returns a tuple with the RequirementsSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirementsSummary

`func (o *Task) SetRequirementsSummary(v string)`

SetRequirementsSummary sets RequirementsSummary field to given value.


### SetRequirementsSummaryNil

`func (o *Task) SetRequirementsSummaryNil(b bool)`

 SetRequirementsSummaryNil sets the value for RequirementsSummary to be an explicit nil

### UnsetRequirementsSummary
`func (o *Task) UnsetRequirementsSummary()`

UnsetRequirementsSummary ensures that no value is present for RequirementsSummary, not even an explicit nil
### GetReviewFeedback

`func (o *Task) GetReviewFeedback() string`

GetReviewFeedback returns the ReviewFeedback field if non-nil, zero value otherwise.

### GetReviewFeedbackOk

`func (o *Task) GetReviewFeedbackOk() (*string, bool)`

GetReviewFeedbackOk returns a tuple with the ReviewFeedback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewFeedback

`func (o *Task) SetReviewFeedback(v string)`

SetReviewFeedback sets ReviewFeedback field to given value.


### SetReviewFeedbackNil

`func (o *Task) SetReviewFeedbackNil(b bool)`

 SetReviewFeedbackNil sets the value for ReviewFeedback to be an explicit nil

### UnsetReviewFeedback
`func (o *Task) UnsetReviewFeedback()`

UnsetReviewFeedback ensures that no value is present for ReviewFeedback, not even an explicit nil
### GetReviewRounds

`func (o *Task) GetReviewRounds() int32`

GetReviewRounds returns the ReviewRounds field if non-nil, zero value otherwise.

### GetReviewRoundsOk

`func (o *Task) GetReviewRoundsOk() (*int32, bool)`

GetReviewRoundsOk returns a tuple with the ReviewRounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewRounds

`func (o *Task) SetReviewRounds(v int32)`

SetReviewRounds sets ReviewRounds field to given value.


### GetSortOrder

`func (o *Task) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *Task) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *Task) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.


### GetSource

`func (o *Task) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Task) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Task) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *Task) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Task) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Task) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *Task) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Task) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Task) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *Task) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *Task) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetUpdatedAt

`func (o *Task) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Task) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Task) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


