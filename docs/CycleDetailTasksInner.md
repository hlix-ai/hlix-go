# CycleDetailTasksInner

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
**DependsOn** | **[]string** |  | 
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

### NewCycleDetailTasksInner

`func NewCycleDetailTasksInner(agentId NullableString, billableCostMicros NullableInt64, costMicros NullableInt64, createdAt string, currentStage NullableString, cycleId NullableString, dependsOn []string, description string, doingSince NullableString, doneWhen NullableString, headSha NullableString, id string, implementationPlan NullableString, iteration int32, metadata interface{}, note NullableString, organizationId string, pipeline interface{}, projectId string, repoId NullableString, requirementsSummary NullableString, reviewFeedback NullableString, reviewRounds int32, sortOrder int32, source string, status string, title NullableString, updatedAt string, ) *CycleDetailTasksInner`

NewCycleDetailTasksInner instantiates a new CycleDetailTasksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleDetailTasksInnerWithDefaults

`func NewCycleDetailTasksInnerWithDefaults() *CycleDetailTasksInner`

NewCycleDetailTasksInnerWithDefaults instantiates a new CycleDetailTasksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentId

`func (o *CycleDetailTasksInner) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *CycleDetailTasksInner) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *CycleDetailTasksInner) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.


### SetAgentIdNil

`func (o *CycleDetailTasksInner) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *CycleDetailTasksInner) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetBillableCostMicros

`func (o *CycleDetailTasksInner) GetBillableCostMicros() int64`

GetBillableCostMicros returns the BillableCostMicros field if non-nil, zero value otherwise.

### GetBillableCostMicrosOk

`func (o *CycleDetailTasksInner) GetBillableCostMicrosOk() (*int64, bool)`

GetBillableCostMicrosOk returns a tuple with the BillableCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillableCostMicros

`func (o *CycleDetailTasksInner) SetBillableCostMicros(v int64)`

SetBillableCostMicros sets BillableCostMicros field to given value.


### SetBillableCostMicrosNil

`func (o *CycleDetailTasksInner) SetBillableCostMicrosNil(b bool)`

 SetBillableCostMicrosNil sets the value for BillableCostMicros to be an explicit nil

### UnsetBillableCostMicros
`func (o *CycleDetailTasksInner) UnsetBillableCostMicros()`

UnsetBillableCostMicros ensures that no value is present for BillableCostMicros, not even an explicit nil
### GetCostMicros

`func (o *CycleDetailTasksInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *CycleDetailTasksInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *CycleDetailTasksInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *CycleDetailTasksInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *CycleDetailTasksInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCreatedAt

`func (o *CycleDetailTasksInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CycleDetailTasksInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CycleDetailTasksInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrentStage

`func (o *CycleDetailTasksInner) GetCurrentStage() string`

GetCurrentStage returns the CurrentStage field if non-nil, zero value otherwise.

### GetCurrentStageOk

`func (o *CycleDetailTasksInner) GetCurrentStageOk() (*string, bool)`

GetCurrentStageOk returns a tuple with the CurrentStage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentStage

`func (o *CycleDetailTasksInner) SetCurrentStage(v string)`

SetCurrentStage sets CurrentStage field to given value.


### SetCurrentStageNil

`func (o *CycleDetailTasksInner) SetCurrentStageNil(b bool)`

 SetCurrentStageNil sets the value for CurrentStage to be an explicit nil

### UnsetCurrentStage
`func (o *CycleDetailTasksInner) UnsetCurrentStage()`

UnsetCurrentStage ensures that no value is present for CurrentStage, not even an explicit nil
### GetCycleId

`func (o *CycleDetailTasksInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *CycleDetailTasksInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *CycleDetailTasksInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *CycleDetailTasksInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *CycleDetailTasksInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDeliveryEvidence

`func (o *CycleDetailTasksInner) GetDeliveryEvidence() CycleDetailTasksInnerDeliveryEvidence`

GetDeliveryEvidence returns the DeliveryEvidence field if non-nil, zero value otherwise.

### GetDeliveryEvidenceOk

`func (o *CycleDetailTasksInner) GetDeliveryEvidenceOk() (*CycleDetailTasksInnerDeliveryEvidence, bool)`

GetDeliveryEvidenceOk returns a tuple with the DeliveryEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryEvidence

`func (o *CycleDetailTasksInner) SetDeliveryEvidence(v CycleDetailTasksInnerDeliveryEvidence)`

SetDeliveryEvidence sets DeliveryEvidence field to given value.

### HasDeliveryEvidence

`func (o *CycleDetailTasksInner) HasDeliveryEvidence() bool`

HasDeliveryEvidence returns a boolean if a field has been set.

### GetDependsOn

`func (o *CycleDetailTasksInner) GetDependsOn() []string`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *CycleDetailTasksInner) GetDependsOnOk() (*[]string, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *CycleDetailTasksInner) SetDependsOn(v []string)`

SetDependsOn sets DependsOn field to given value.


### GetDescription

`func (o *CycleDetailTasksInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CycleDetailTasksInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CycleDetailTasksInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetDoingSince

`func (o *CycleDetailTasksInner) GetDoingSince() string`

GetDoingSince returns the DoingSince field if non-nil, zero value otherwise.

### GetDoingSinceOk

`func (o *CycleDetailTasksInner) GetDoingSinceOk() (*string, bool)`

GetDoingSinceOk returns a tuple with the DoingSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoingSince

`func (o *CycleDetailTasksInner) SetDoingSince(v string)`

SetDoingSince sets DoingSince field to given value.


### SetDoingSinceNil

`func (o *CycleDetailTasksInner) SetDoingSinceNil(b bool)`

 SetDoingSinceNil sets the value for DoingSince to be an explicit nil

### UnsetDoingSince
`func (o *CycleDetailTasksInner) UnsetDoingSince()`

UnsetDoingSince ensures that no value is present for DoingSince, not even an explicit nil
### GetDoneWhen

`func (o *CycleDetailTasksInner) GetDoneWhen() string`

GetDoneWhen returns the DoneWhen field if non-nil, zero value otherwise.

### GetDoneWhenOk

`func (o *CycleDetailTasksInner) GetDoneWhenOk() (*string, bool)`

GetDoneWhenOk returns a tuple with the DoneWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoneWhen

`func (o *CycleDetailTasksInner) SetDoneWhen(v string)`

SetDoneWhen sets DoneWhen field to given value.


### SetDoneWhenNil

`func (o *CycleDetailTasksInner) SetDoneWhenNil(b bool)`

 SetDoneWhenNil sets the value for DoneWhen to be an explicit nil

### UnsetDoneWhen
`func (o *CycleDetailTasksInner) UnsetDoneWhen()`

UnsetDoneWhen ensures that no value is present for DoneWhen, not even an explicit nil
### GetHeadSha

`func (o *CycleDetailTasksInner) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *CycleDetailTasksInner) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *CycleDetailTasksInner) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### SetHeadShaNil

`func (o *CycleDetailTasksInner) SetHeadShaNil(b bool)`

 SetHeadShaNil sets the value for HeadSha to be an explicit nil

### UnsetHeadSha
`func (o *CycleDetailTasksInner) UnsetHeadSha()`

UnsetHeadSha ensures that no value is present for HeadSha, not even an explicit nil
### GetId

`func (o *CycleDetailTasksInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CycleDetailTasksInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CycleDetailTasksInner) SetId(v string)`

SetId sets Id field to given value.


### GetImplementationPlan

`func (o *CycleDetailTasksInner) GetImplementationPlan() string`

GetImplementationPlan returns the ImplementationPlan field if non-nil, zero value otherwise.

### GetImplementationPlanOk

`func (o *CycleDetailTasksInner) GetImplementationPlanOk() (*string, bool)`

GetImplementationPlanOk returns a tuple with the ImplementationPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImplementationPlan

`func (o *CycleDetailTasksInner) SetImplementationPlan(v string)`

SetImplementationPlan sets ImplementationPlan field to given value.


### SetImplementationPlanNil

`func (o *CycleDetailTasksInner) SetImplementationPlanNil(b bool)`

 SetImplementationPlanNil sets the value for ImplementationPlan to be an explicit nil

### UnsetImplementationPlan
`func (o *CycleDetailTasksInner) UnsetImplementationPlan()`

UnsetImplementationPlan ensures that no value is present for ImplementationPlan, not even an explicit nil
### GetIteration

`func (o *CycleDetailTasksInner) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *CycleDetailTasksInner) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *CycleDetailTasksInner) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### GetMetadata

`func (o *CycleDetailTasksInner) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CycleDetailTasksInner) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CycleDetailTasksInner) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *CycleDetailTasksInner) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *CycleDetailTasksInner) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetNote

`func (o *CycleDetailTasksInner) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CycleDetailTasksInner) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CycleDetailTasksInner) SetNote(v string)`

SetNote sets Note field to given value.


### SetNoteNil

`func (o *CycleDetailTasksInner) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *CycleDetailTasksInner) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetOrganizationId

`func (o *CycleDetailTasksInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CycleDetailTasksInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CycleDetailTasksInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPipeline

`func (o *CycleDetailTasksInner) GetPipeline() interface{}`

GetPipeline returns the Pipeline field if non-nil, zero value otherwise.

### GetPipelineOk

`func (o *CycleDetailTasksInner) GetPipelineOk() (*interface{}, bool)`

GetPipelineOk returns a tuple with the Pipeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipeline

`func (o *CycleDetailTasksInner) SetPipeline(v interface{})`

SetPipeline sets Pipeline field to given value.


### SetPipelineNil

`func (o *CycleDetailTasksInner) SetPipelineNil(b bool)`

 SetPipelineNil sets the value for Pipeline to be an explicit nil

### UnsetPipeline
`func (o *CycleDetailTasksInner) UnsetPipeline()`

UnsetPipeline ensures that no value is present for Pipeline, not even an explicit nil
### GetProjectId

`func (o *CycleDetailTasksInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CycleDetailTasksInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CycleDetailTasksInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRepoId

`func (o *CycleDetailTasksInner) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *CycleDetailTasksInner) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *CycleDetailTasksInner) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.


### SetRepoIdNil

`func (o *CycleDetailTasksInner) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *CycleDetailTasksInner) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetRequirementsSummary

`func (o *CycleDetailTasksInner) GetRequirementsSummary() string`

GetRequirementsSummary returns the RequirementsSummary field if non-nil, zero value otherwise.

### GetRequirementsSummaryOk

`func (o *CycleDetailTasksInner) GetRequirementsSummaryOk() (*string, bool)`

GetRequirementsSummaryOk returns a tuple with the RequirementsSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirementsSummary

`func (o *CycleDetailTasksInner) SetRequirementsSummary(v string)`

SetRequirementsSummary sets RequirementsSummary field to given value.


### SetRequirementsSummaryNil

`func (o *CycleDetailTasksInner) SetRequirementsSummaryNil(b bool)`

 SetRequirementsSummaryNil sets the value for RequirementsSummary to be an explicit nil

### UnsetRequirementsSummary
`func (o *CycleDetailTasksInner) UnsetRequirementsSummary()`

UnsetRequirementsSummary ensures that no value is present for RequirementsSummary, not even an explicit nil
### GetReviewFeedback

`func (o *CycleDetailTasksInner) GetReviewFeedback() string`

GetReviewFeedback returns the ReviewFeedback field if non-nil, zero value otherwise.

### GetReviewFeedbackOk

`func (o *CycleDetailTasksInner) GetReviewFeedbackOk() (*string, bool)`

GetReviewFeedbackOk returns a tuple with the ReviewFeedback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewFeedback

`func (o *CycleDetailTasksInner) SetReviewFeedback(v string)`

SetReviewFeedback sets ReviewFeedback field to given value.


### SetReviewFeedbackNil

`func (o *CycleDetailTasksInner) SetReviewFeedbackNil(b bool)`

 SetReviewFeedbackNil sets the value for ReviewFeedback to be an explicit nil

### UnsetReviewFeedback
`func (o *CycleDetailTasksInner) UnsetReviewFeedback()`

UnsetReviewFeedback ensures that no value is present for ReviewFeedback, not even an explicit nil
### GetReviewRounds

`func (o *CycleDetailTasksInner) GetReviewRounds() int32`

GetReviewRounds returns the ReviewRounds field if non-nil, zero value otherwise.

### GetReviewRoundsOk

`func (o *CycleDetailTasksInner) GetReviewRoundsOk() (*int32, bool)`

GetReviewRoundsOk returns a tuple with the ReviewRounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewRounds

`func (o *CycleDetailTasksInner) SetReviewRounds(v int32)`

SetReviewRounds sets ReviewRounds field to given value.


### GetSortOrder

`func (o *CycleDetailTasksInner) GetSortOrder() int32`

GetSortOrder returns the SortOrder field if non-nil, zero value otherwise.

### GetSortOrderOk

`func (o *CycleDetailTasksInner) GetSortOrderOk() (*int32, bool)`

GetSortOrderOk returns a tuple with the SortOrder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortOrder

`func (o *CycleDetailTasksInner) SetSortOrder(v int32)`

SetSortOrder sets SortOrder field to given value.


### GetSource

`func (o *CycleDetailTasksInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CycleDetailTasksInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CycleDetailTasksInner) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *CycleDetailTasksInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleDetailTasksInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleDetailTasksInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *CycleDetailTasksInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CycleDetailTasksInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CycleDetailTasksInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *CycleDetailTasksInner) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *CycleDetailTasksInner) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetUpdatedAt

`func (o *CycleDetailTasksInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CycleDetailTasksInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CycleDetailTasksInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


