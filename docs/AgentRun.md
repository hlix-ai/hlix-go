# AgentRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingSource** | **NullableString** |  |
**AgentKind** | **string** |  |
**BilledTo** | **NullableString** |  |
**BillingMarkupBps** | **NullableInt32** |  |
**BillingProjectKind** | **NullableString** |  |
**CoderAccountId** | **NullableString** |  |
**CompletedAt** | **NullableString** |  |
**CostMicros** | **NullableInt64** |  |
**CredentialKind** | **NullableString** |  |
**CycleId** | **NullableString** |  |
**CycleRunId** | **NullableString** |  |
**FundingMode** | **NullableString** |  |
**Id** | **string** |  |
**InputSnapshot** | **NullableString** |  |
**Iteration** | **NullableInt32** |  |
**Model** | **string** |  |
**OrganizationId** | **string** |  |
**OutputSnapshot** | **NullableString** |  |
**ParentRunId** | **NullableString** |  |
**ProjectId** | **NullableString** |  |
**PromptKey** | **NullableString** |  |
**SpanId** | **NullableString** |  |
**StartedAt** | **string** |  |
**Status** | **string** |  |
**TaskId** | **NullableString** |  |
**TokensIn** | **NullableInt32** |  |
**TokensOut** | **NullableInt32** |  |
**TraceId** | **NullableString** |  |
**UsageCompleteness** | **NullableString** |  |
**UsageSequence** | **NullableInt32** |  |

## Methods

### NewAgentRun

`func NewAgentRun(accountingSource NullableString, agentKind string, billedTo NullableString, billingMarkupBps NullableInt32, billingProjectKind NullableString, coderAccountId NullableString, completedAt NullableString, costMicros NullableInt64, credentialKind NullableString, cycleId NullableString, cycleRunId NullableString, fundingMode NullableString, id string, inputSnapshot NullableString, iteration NullableInt32, model string, organizationId string, outputSnapshot NullableString, parentRunId NullableString, projectId NullableString, promptKey NullableString, spanId NullableString, startedAt string, status string, taskId NullableString, tokensIn NullableInt32, tokensOut NullableInt32, traceId NullableString, usageCompleteness NullableString, usageSequence NullableInt32, ) *AgentRun`

NewAgentRun instantiates a new AgentRun object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgentRunWithDefaults

`func NewAgentRunWithDefaults() *AgentRun`

NewAgentRunWithDefaults instantiates a new AgentRun object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAccountingSource

`func (o *AgentRun) GetAccountingSource() string`

GetAccountingSource returns the AccountingSource field if non-nil, zero value otherwise.

### GetAccountingSourceOk

`func (o *AgentRun) GetAccountingSourceOk() (*string, bool)`

GetAccountingSourceOk returns a tuple with the AccountingSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingSource

`func (o *AgentRun) SetAccountingSource(v string)`

SetAccountingSource sets AccountingSource field to given value.


### SetAccountingSourceNil

`func (o *AgentRun) SetAccountingSourceNil(b bool)`

 SetAccountingSourceNil sets the value for AccountingSource to be an explicit nil

### UnsetAccountingSource
`func (o *AgentRun) UnsetAccountingSource()`

UnsetAccountingSource ensures that no value is present for AccountingSource, not even an explicit nil
### GetAgentKind

`func (o *AgentRun) GetAgentKind() string`

GetAgentKind returns the AgentKind field if non-nil, zero value otherwise.

### GetAgentKindOk

`func (o *AgentRun) GetAgentKindOk() (*string, bool)`

GetAgentKindOk returns a tuple with the AgentKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentKind

`func (o *AgentRun) SetAgentKind(v string)`

SetAgentKind sets AgentKind field to given value.


### GetBilledTo

`func (o *AgentRun) GetBilledTo() string`

GetBilledTo returns the BilledTo field if non-nil, zero value otherwise.

### GetBilledToOk

`func (o *AgentRun) GetBilledToOk() (*string, bool)`

GetBilledToOk returns a tuple with the BilledTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledTo

`func (o *AgentRun) SetBilledTo(v string)`

SetBilledTo sets BilledTo field to given value.


### SetBilledToNil

`func (o *AgentRun) SetBilledToNil(b bool)`

 SetBilledToNil sets the value for BilledTo to be an explicit nil

### UnsetBilledTo
`func (o *AgentRun) UnsetBilledTo()`

UnsetBilledTo ensures that no value is present for BilledTo, not even an explicit nil
### GetBillingMarkupBps

`func (o *AgentRun) GetBillingMarkupBps() int32`

GetBillingMarkupBps returns the BillingMarkupBps field if non-nil, zero value otherwise.

### GetBillingMarkupBpsOk

`func (o *AgentRun) GetBillingMarkupBpsOk() (*int32, bool)`

GetBillingMarkupBpsOk returns a tuple with the BillingMarkupBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMarkupBps

`func (o *AgentRun) SetBillingMarkupBps(v int32)`

SetBillingMarkupBps sets BillingMarkupBps field to given value.


### SetBillingMarkupBpsNil

`func (o *AgentRun) SetBillingMarkupBpsNil(b bool)`

 SetBillingMarkupBpsNil sets the value for BillingMarkupBps to be an explicit nil

### UnsetBillingMarkupBps
`func (o *AgentRun) UnsetBillingMarkupBps()`

UnsetBillingMarkupBps ensures that no value is present for BillingMarkupBps, not even an explicit nil
### GetBillingProjectKind

`func (o *AgentRun) GetBillingProjectKind() string`

GetBillingProjectKind returns the BillingProjectKind field if non-nil, zero value otherwise.

### GetBillingProjectKindOk

`func (o *AgentRun) GetBillingProjectKindOk() (*string, bool)`

GetBillingProjectKindOk returns a tuple with the BillingProjectKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingProjectKind

`func (o *AgentRun) SetBillingProjectKind(v string)`

SetBillingProjectKind sets BillingProjectKind field to given value.


### SetBillingProjectKindNil

`func (o *AgentRun) SetBillingProjectKindNil(b bool)`

 SetBillingProjectKindNil sets the value for BillingProjectKind to be an explicit nil

### UnsetBillingProjectKind
`func (o *AgentRun) UnsetBillingProjectKind()`

UnsetBillingProjectKind ensures that no value is present for BillingProjectKind, not even an explicit nil
### GetCoderAccountId

`func (o *AgentRun) GetCoderAccountId() string`

GetCoderAccountId returns the CoderAccountId field if non-nil, zero value otherwise.

### GetCoderAccountIdOk

`func (o *AgentRun) GetCoderAccountIdOk() (*string, bool)`

GetCoderAccountIdOk returns a tuple with the CoderAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoderAccountId

`func (o *AgentRun) SetCoderAccountId(v string)`

SetCoderAccountId sets CoderAccountId field to given value.


### SetCoderAccountIdNil

`func (o *AgentRun) SetCoderAccountIdNil(b bool)`

 SetCoderAccountIdNil sets the value for CoderAccountId to be an explicit nil

### UnsetCoderAccountId
`func (o *AgentRun) UnsetCoderAccountId()`

UnsetCoderAccountId ensures that no value is present for CoderAccountId, not even an explicit nil
### GetCompletedAt

`func (o *AgentRun) GetCompletedAt() string`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AgentRun) GetCompletedAtOk() (*string, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AgentRun) SetCompletedAt(v string)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *AgentRun) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AgentRun) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCostMicros

`func (o *AgentRun) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AgentRun) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AgentRun) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AgentRun) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AgentRun) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCredentialKind

`func (o *AgentRun) GetCredentialKind() string`

GetCredentialKind returns the CredentialKind field if non-nil, zero value otherwise.

### GetCredentialKindOk

`func (o *AgentRun) GetCredentialKindOk() (*string, bool)`

GetCredentialKindOk returns a tuple with the CredentialKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentialKind

`func (o *AgentRun) SetCredentialKind(v string)`

SetCredentialKind sets CredentialKind field to given value.


### SetCredentialKindNil

`func (o *AgentRun) SetCredentialKindNil(b bool)`

 SetCredentialKindNil sets the value for CredentialKind to be an explicit nil

### UnsetCredentialKind
`func (o *AgentRun) UnsetCredentialKind()`

UnsetCredentialKind ensures that no value is present for CredentialKind, not even an explicit nil
### GetCycleId

`func (o *AgentRun) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *AgentRun) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *AgentRun) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *AgentRun) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *AgentRun) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetCycleRunId

`func (o *AgentRun) GetCycleRunId() string`

GetCycleRunId returns the CycleRunId field if non-nil, zero value otherwise.

### GetCycleRunIdOk

`func (o *AgentRun) GetCycleRunIdOk() (*string, bool)`

GetCycleRunIdOk returns a tuple with the CycleRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleRunId

`func (o *AgentRun) SetCycleRunId(v string)`

SetCycleRunId sets CycleRunId field to given value.


### SetCycleRunIdNil

`func (o *AgentRun) SetCycleRunIdNil(b bool)`

 SetCycleRunIdNil sets the value for CycleRunId to be an explicit nil

### UnsetCycleRunId
`func (o *AgentRun) UnsetCycleRunId()`

UnsetCycleRunId ensures that no value is present for CycleRunId, not even an explicit nil
### GetFundingMode

`func (o *AgentRun) GetFundingMode() string`

GetFundingMode returns the FundingMode field if non-nil, zero value otherwise.

### GetFundingModeOk

`func (o *AgentRun) GetFundingModeOk() (*string, bool)`

GetFundingModeOk returns a tuple with the FundingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundingMode

`func (o *AgentRun) SetFundingMode(v string)`

SetFundingMode sets FundingMode field to given value.


### SetFundingModeNil

`func (o *AgentRun) SetFundingModeNil(b bool)`

 SetFundingModeNil sets the value for FundingMode to be an explicit nil

### UnsetFundingMode
`func (o *AgentRun) UnsetFundingMode()`

UnsetFundingMode ensures that no value is present for FundingMode, not even an explicit nil
### GetId

`func (o *AgentRun) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentRun) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentRun) SetId(v string)`

SetId sets Id field to given value.


### GetInputSnapshot

`func (o *AgentRun) GetInputSnapshot() string`

GetInputSnapshot returns the InputSnapshot field if non-nil, zero value otherwise.

### GetInputSnapshotOk

`func (o *AgentRun) GetInputSnapshotOk() (*string, bool)`

GetInputSnapshotOk returns a tuple with the InputSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputSnapshot

`func (o *AgentRun) SetInputSnapshot(v string)`

SetInputSnapshot sets InputSnapshot field to given value.


### SetInputSnapshotNil

`func (o *AgentRun) SetInputSnapshotNil(b bool)`

 SetInputSnapshotNil sets the value for InputSnapshot to be an explicit nil

### UnsetInputSnapshot
`func (o *AgentRun) UnsetInputSnapshot()`

UnsetInputSnapshot ensures that no value is present for InputSnapshot, not even an explicit nil
### GetIteration

`func (o *AgentRun) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *AgentRun) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *AgentRun) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### SetIterationNil

`func (o *AgentRun) SetIterationNil(b bool)`

 SetIterationNil sets the value for Iteration to be an explicit nil

### UnsetIteration
`func (o *AgentRun) UnsetIteration()`

UnsetIteration ensures that no value is present for Iteration, not even an explicit nil
### GetModel

`func (o *AgentRun) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AgentRun) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AgentRun) SetModel(v string)`

SetModel sets Model field to given value.


### GetOrganizationId

`func (o *AgentRun) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AgentRun) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AgentRun) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOutputSnapshot

`func (o *AgentRun) GetOutputSnapshot() string`

GetOutputSnapshot returns the OutputSnapshot field if non-nil, zero value otherwise.

### GetOutputSnapshotOk

`func (o *AgentRun) GetOutputSnapshotOk() (*string, bool)`

GetOutputSnapshotOk returns a tuple with the OutputSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputSnapshot

`func (o *AgentRun) SetOutputSnapshot(v string)`

SetOutputSnapshot sets OutputSnapshot field to given value.


### SetOutputSnapshotNil

`func (o *AgentRun) SetOutputSnapshotNil(b bool)`

 SetOutputSnapshotNil sets the value for OutputSnapshot to be an explicit nil

### UnsetOutputSnapshot
`func (o *AgentRun) UnsetOutputSnapshot()`

UnsetOutputSnapshot ensures that no value is present for OutputSnapshot, not even an explicit nil
### GetParentRunId

`func (o *AgentRun) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *AgentRun) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *AgentRun) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.


### SetParentRunIdNil

`func (o *AgentRun) SetParentRunIdNil(b bool)`

 SetParentRunIdNil sets the value for ParentRunId to be an explicit nil

### UnsetParentRunId
`func (o *AgentRun) UnsetParentRunId()`

UnsetParentRunId ensures that no value is present for ParentRunId, not even an explicit nil
### GetProjectId

`func (o *AgentRun) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AgentRun) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AgentRun) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *AgentRun) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *AgentRun) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetPromptKey

`func (o *AgentRun) GetPromptKey() string`

GetPromptKey returns the PromptKey field if non-nil, zero value otherwise.

### GetPromptKeyOk

`func (o *AgentRun) GetPromptKeyOk() (*string, bool)`

GetPromptKeyOk returns a tuple with the PromptKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptKey

`func (o *AgentRun) SetPromptKey(v string)`

SetPromptKey sets PromptKey field to given value.


### SetPromptKeyNil

`func (o *AgentRun) SetPromptKeyNil(b bool)`

 SetPromptKeyNil sets the value for PromptKey to be an explicit nil

### UnsetPromptKey
`func (o *AgentRun) UnsetPromptKey()`

UnsetPromptKey ensures that no value is present for PromptKey, not even an explicit nil
### GetSpanId

`func (o *AgentRun) GetSpanId() string`

GetSpanId returns the SpanId field if non-nil, zero value otherwise.

### GetSpanIdOk

`func (o *AgentRun) GetSpanIdOk() (*string, bool)`

GetSpanIdOk returns a tuple with the SpanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpanId

`func (o *AgentRun) SetSpanId(v string)`

SetSpanId sets SpanId field to given value.


### SetSpanIdNil

`func (o *AgentRun) SetSpanIdNil(b bool)`

 SetSpanIdNil sets the value for SpanId to be an explicit nil

### UnsetSpanId
`func (o *AgentRun) UnsetSpanId()`

UnsetSpanId ensures that no value is present for SpanId, not even an explicit nil
### GetStartedAt

`func (o *AgentRun) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *AgentRun) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *AgentRun) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *AgentRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AgentRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AgentRun) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *AgentRun) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *AgentRun) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *AgentRun) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *AgentRun) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *AgentRun) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTokensIn

`func (o *AgentRun) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AgentRun) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AgentRun) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### SetTokensInNil

`func (o *AgentRun) SetTokensInNil(b bool)`

 SetTokensInNil sets the value for TokensIn to be an explicit nil

### UnsetTokensIn
`func (o *AgentRun) UnsetTokensIn()`

UnsetTokensIn ensures that no value is present for TokensIn, not even an explicit nil
### GetTokensOut

`func (o *AgentRun) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AgentRun) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AgentRun) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.


### SetTokensOutNil

`func (o *AgentRun) SetTokensOutNil(b bool)`

 SetTokensOutNil sets the value for TokensOut to be an explicit nil

### UnsetTokensOut
`func (o *AgentRun) UnsetTokensOut()`

UnsetTokensOut ensures that no value is present for TokensOut, not even an explicit nil
### GetTraceId

`func (o *AgentRun) GetTraceId() string`

GetTraceId returns the TraceId field if non-nil, zero value otherwise.

### GetTraceIdOk

`func (o *AgentRun) GetTraceIdOk() (*string, bool)`

GetTraceIdOk returns a tuple with the TraceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceId

`func (o *AgentRun) SetTraceId(v string)`

SetTraceId sets TraceId field to given value.


### SetTraceIdNil

`func (o *AgentRun) SetTraceIdNil(b bool)`

 SetTraceIdNil sets the value for TraceId to be an explicit nil

### UnsetTraceId
`func (o *AgentRun) UnsetTraceId()`

UnsetTraceId ensures that no value is present for TraceId, not even an explicit nil
### GetUsageCompleteness

`func (o *AgentRun) GetUsageCompleteness() string`

GetUsageCompleteness returns the UsageCompleteness field if non-nil, zero value otherwise.

### GetUsageCompletenessOk

`func (o *AgentRun) GetUsageCompletenessOk() (*string, bool)`

GetUsageCompletenessOk returns a tuple with the UsageCompleteness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageCompleteness

`func (o *AgentRun) SetUsageCompleteness(v string)`

SetUsageCompleteness sets UsageCompleteness field to given value.


### SetUsageCompletenessNil

`func (o *AgentRun) SetUsageCompletenessNil(b bool)`

 SetUsageCompletenessNil sets the value for UsageCompleteness to be an explicit nil

### UnsetUsageCompleteness
`func (o *AgentRun) UnsetUsageCompleteness()`

UnsetUsageCompleteness ensures that no value is present for UsageCompleteness, not even an explicit nil
### GetUsageSequence

`func (o *AgentRun) GetUsageSequence() int32`

GetUsageSequence returns the UsageSequence field if non-nil, zero value otherwise.

### GetUsageSequenceOk

`func (o *AgentRun) GetUsageSequenceOk() (*int32, bool)`

GetUsageSequenceOk returns a tuple with the UsageSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageSequence

`func (o *AgentRun) SetUsageSequence(v int32)`

SetUsageSequence sets UsageSequence field to given value.


### SetUsageSequenceNil

`func (o *AgentRun) SetUsageSequenceNil(b bool)`

 SetUsageSequenceNil sets the value for UsageSequence to be an explicit nil

### UnsetUsageSequence
`func (o *AgentRun) UnsetUsageSequence()`

UnsetUsageSequence ensures that no value is present for UsageSequence, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


