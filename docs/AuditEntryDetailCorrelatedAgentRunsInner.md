# AuditEntryDetailCorrelatedAgentRunsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingSource** | **NullableString** |  | 
**BilledTo** | **NullableString** |  | 
**BillingMarkupBps** | **NullableInt32** |  | 
**BillingProjectKind** | **NullableString** |  | 
**CoderAccountId** | **NullableString** |  | 
**CompletedAt** | **NullableString** |  | 
**CostMicros** | **NullableInt64** |  | 
**CredentialKind** | **NullableString** |  | 
**CycleId** | **NullableString** |  | 
**CycleRunId** | **NullableString** |  | 
**DurableRunId** | **NullableString** |  | 
**FundingMode** | **NullableString** |  | 
**Id** | **string** |  | 
**InputSnapshot** | **NullableString** |  | 
**Iteration** | **NullableInt32** |  | 
**Model** | **string** |  | 
**OrganizationId** | **string** |  | 
**OutputSnapshot** | **NullableString** |  | 
**ParentRunId** | **NullableString** |  | 
**Persona** | **NullableString** |  | 
**ProjectId** | **NullableString** |  | 
**Role** | **string** |  | 
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

### NewAuditEntryDetailCorrelatedAgentRunsInner

`func NewAuditEntryDetailCorrelatedAgentRunsInner(accountingSource NullableString, billedTo NullableString, billingMarkupBps NullableInt32, billingProjectKind NullableString, coderAccountId NullableString, completedAt NullableString, costMicros NullableInt64, credentialKind NullableString, cycleId NullableString, cycleRunId NullableString, durableRunId NullableString, fundingMode NullableString, id string, inputSnapshot NullableString, iteration NullableInt32, model string, organizationId string, outputSnapshot NullableString, parentRunId NullableString, persona NullableString, projectId NullableString, role string, spanId NullableString, startedAt string, status string, taskId NullableString, tokensIn NullableInt32, tokensOut NullableInt32, traceId NullableString, usageCompleteness NullableString, usageSequence NullableInt32, ) *AuditEntryDetailCorrelatedAgentRunsInner`

NewAuditEntryDetailCorrelatedAgentRunsInner instantiates a new AuditEntryDetailCorrelatedAgentRunsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditEntryDetailCorrelatedAgentRunsInnerWithDefaults

`func NewAuditEntryDetailCorrelatedAgentRunsInnerWithDefaults() *AuditEntryDetailCorrelatedAgentRunsInner`

NewAuditEntryDetailCorrelatedAgentRunsInnerWithDefaults instantiates a new AuditEntryDetailCorrelatedAgentRunsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingSource

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetAccountingSource() string`

GetAccountingSource returns the AccountingSource field if non-nil, zero value otherwise.

### GetAccountingSourceOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetAccountingSourceOk() (*string, bool)`

GetAccountingSourceOk returns a tuple with the AccountingSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingSource

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetAccountingSource(v string)`

SetAccountingSource sets AccountingSource field to given value.


### SetAccountingSourceNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetAccountingSourceNil(b bool)`

 SetAccountingSourceNil sets the value for AccountingSource to be an explicit nil

### UnsetAccountingSource
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetAccountingSource()`

UnsetAccountingSource ensures that no value is present for AccountingSource, not even an explicit nil
### GetBilledTo

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetBilledTo() string`

GetBilledTo returns the BilledTo field if non-nil, zero value otherwise.

### GetBilledToOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetBilledToOk() (*string, bool)`

GetBilledToOk returns a tuple with the BilledTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledTo

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetBilledTo(v string)`

SetBilledTo sets BilledTo field to given value.


### SetBilledToNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetBilledToNil(b bool)`

 SetBilledToNil sets the value for BilledTo to be an explicit nil

### UnsetBilledTo
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetBilledTo()`

UnsetBilledTo ensures that no value is present for BilledTo, not even an explicit nil
### GetBillingMarkupBps

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetBillingMarkupBps() int32`

GetBillingMarkupBps returns the BillingMarkupBps field if non-nil, zero value otherwise.

### GetBillingMarkupBpsOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetBillingMarkupBpsOk() (*int32, bool)`

GetBillingMarkupBpsOk returns a tuple with the BillingMarkupBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMarkupBps

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetBillingMarkupBps(v int32)`

SetBillingMarkupBps sets BillingMarkupBps field to given value.


### SetBillingMarkupBpsNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetBillingMarkupBpsNil(b bool)`

 SetBillingMarkupBpsNil sets the value for BillingMarkupBps to be an explicit nil

### UnsetBillingMarkupBps
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetBillingMarkupBps()`

UnsetBillingMarkupBps ensures that no value is present for BillingMarkupBps, not even an explicit nil
### GetBillingProjectKind

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetBillingProjectKind() string`

GetBillingProjectKind returns the BillingProjectKind field if non-nil, zero value otherwise.

### GetBillingProjectKindOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetBillingProjectKindOk() (*string, bool)`

GetBillingProjectKindOk returns a tuple with the BillingProjectKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingProjectKind

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetBillingProjectKind(v string)`

SetBillingProjectKind sets BillingProjectKind field to given value.


### SetBillingProjectKindNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetBillingProjectKindNil(b bool)`

 SetBillingProjectKindNil sets the value for BillingProjectKind to be an explicit nil

### UnsetBillingProjectKind
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetBillingProjectKind()`

UnsetBillingProjectKind ensures that no value is present for BillingProjectKind, not even an explicit nil
### GetCoderAccountId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCoderAccountId() string`

GetCoderAccountId returns the CoderAccountId field if non-nil, zero value otherwise.

### GetCoderAccountIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCoderAccountIdOk() (*string, bool)`

GetCoderAccountIdOk returns a tuple with the CoderAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoderAccountId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCoderAccountId(v string)`

SetCoderAccountId sets CoderAccountId field to given value.


### SetCoderAccountIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCoderAccountIdNil(b bool)`

 SetCoderAccountIdNil sets the value for CoderAccountId to be an explicit nil

### UnsetCoderAccountId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetCoderAccountId()`

UnsetCoderAccountId ensures that no value is present for CoderAccountId, not even an explicit nil
### GetCompletedAt

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCompletedAt() string`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCompletedAtOk() (*string, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCompletedAt(v string)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCostMicros

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCredentialKind

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCredentialKind() string`

GetCredentialKind returns the CredentialKind field if non-nil, zero value otherwise.

### GetCredentialKindOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCredentialKindOk() (*string, bool)`

GetCredentialKindOk returns a tuple with the CredentialKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentialKind

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCredentialKind(v string)`

SetCredentialKind sets CredentialKind field to given value.


### SetCredentialKindNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCredentialKindNil(b bool)`

 SetCredentialKindNil sets the value for CredentialKind to be an explicit nil

### UnsetCredentialKind
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetCredentialKind()`

UnsetCredentialKind ensures that no value is present for CredentialKind, not even an explicit nil
### GetCycleId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetCycleRunId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCycleRunId() string`

GetCycleRunId returns the CycleRunId field if non-nil, zero value otherwise.

### GetCycleRunIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetCycleRunIdOk() (*string, bool)`

GetCycleRunIdOk returns a tuple with the CycleRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleRunId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCycleRunId(v string)`

SetCycleRunId sets CycleRunId field to given value.


### SetCycleRunIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetCycleRunIdNil(b bool)`

 SetCycleRunIdNil sets the value for CycleRunId to be an explicit nil

### UnsetCycleRunId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetCycleRunId()`

UnsetCycleRunId ensures that no value is present for CycleRunId, not even an explicit nil
### GetDurableRunId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetDurableRunId() string`

GetDurableRunId returns the DurableRunId field if non-nil, zero value otherwise.

### GetDurableRunIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetDurableRunIdOk() (*string, bool)`

GetDurableRunIdOk returns a tuple with the DurableRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurableRunId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetDurableRunId(v string)`

SetDurableRunId sets DurableRunId field to given value.


### SetDurableRunIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetDurableRunIdNil(b bool)`

 SetDurableRunIdNil sets the value for DurableRunId to be an explicit nil

### UnsetDurableRunId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetDurableRunId()`

UnsetDurableRunId ensures that no value is present for DurableRunId, not even an explicit nil
### GetFundingMode

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetFundingMode() string`

GetFundingMode returns the FundingMode field if non-nil, zero value otherwise.

### GetFundingModeOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetFundingModeOk() (*string, bool)`

GetFundingModeOk returns a tuple with the FundingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundingMode

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetFundingMode(v string)`

SetFundingMode sets FundingMode field to given value.


### SetFundingModeNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetFundingModeNil(b bool)`

 SetFundingModeNil sets the value for FundingMode to be an explicit nil

### UnsetFundingMode
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetFundingMode()`

UnsetFundingMode ensures that no value is present for FundingMode, not even an explicit nil
### GetId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetId(v string)`

SetId sets Id field to given value.


### GetInputSnapshot

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetInputSnapshot() string`

GetInputSnapshot returns the InputSnapshot field if non-nil, zero value otherwise.

### GetInputSnapshotOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetInputSnapshotOk() (*string, bool)`

GetInputSnapshotOk returns a tuple with the InputSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputSnapshot

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetInputSnapshot(v string)`

SetInputSnapshot sets InputSnapshot field to given value.


### SetInputSnapshotNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetInputSnapshotNil(b bool)`

 SetInputSnapshotNil sets the value for InputSnapshot to be an explicit nil

### UnsetInputSnapshot
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetInputSnapshot()`

UnsetInputSnapshot ensures that no value is present for InputSnapshot, not even an explicit nil
### GetIteration

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetIteration() int32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetIterationOk() (*int32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetIteration(v int32)`

SetIteration sets Iteration field to given value.


### SetIterationNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetIterationNil(b bool)`

 SetIterationNil sets the value for Iteration to be an explicit nil

### UnsetIteration
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetIteration()`

UnsetIteration ensures that no value is present for Iteration, not even an explicit nil
### GetModel

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetModel(v string)`

SetModel sets Model field to given value.


### GetOrganizationId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOutputSnapshot

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetOutputSnapshot() string`

GetOutputSnapshot returns the OutputSnapshot field if non-nil, zero value otherwise.

### GetOutputSnapshotOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetOutputSnapshotOk() (*string, bool)`

GetOutputSnapshotOk returns a tuple with the OutputSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputSnapshot

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetOutputSnapshot(v string)`

SetOutputSnapshot sets OutputSnapshot field to given value.


### SetOutputSnapshotNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetOutputSnapshotNil(b bool)`

 SetOutputSnapshotNil sets the value for OutputSnapshot to be an explicit nil

### UnsetOutputSnapshot
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetOutputSnapshot()`

UnsetOutputSnapshot ensures that no value is present for OutputSnapshot, not even an explicit nil
### GetParentRunId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.


### SetParentRunIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetParentRunIdNil(b bool)`

 SetParentRunIdNil sets the value for ParentRunId to be an explicit nil

### UnsetParentRunId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetParentRunId()`

UnsetParentRunId ensures that no value is present for ParentRunId, not even an explicit nil
### GetPersona

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetProjectId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetRole

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetRole(v string)`

SetRole sets Role field to given value.


### GetSpanId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetSpanId() string`

GetSpanId returns the SpanId field if non-nil, zero value otherwise.

### GetSpanIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetSpanIdOk() (*string, bool)`

GetSpanIdOk returns a tuple with the SpanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpanId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetSpanId(v string)`

SetSpanId sets SpanId field to given value.


### SetSpanIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetSpanIdNil(b bool)`

 SetSpanIdNil sets the value for SpanId to be an explicit nil

### UnsetSpanId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetSpanId()`

UnsetSpanId ensures that no value is present for SpanId, not even an explicit nil
### GetStartedAt

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTokensIn

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### SetTokensInNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTokensInNil(b bool)`

 SetTokensInNil sets the value for TokensIn to be an explicit nil

### UnsetTokensIn
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetTokensIn()`

UnsetTokensIn ensures that no value is present for TokensIn, not even an explicit nil
### GetTokensOut

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.


### SetTokensOutNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTokensOutNil(b bool)`

 SetTokensOutNil sets the value for TokensOut to be an explicit nil

### UnsetTokensOut
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetTokensOut()`

UnsetTokensOut ensures that no value is present for TokensOut, not even an explicit nil
### GetTraceId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTraceId() string`

GetTraceId returns the TraceId field if non-nil, zero value otherwise.

### GetTraceIdOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetTraceIdOk() (*string, bool)`

GetTraceIdOk returns a tuple with the TraceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceId

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTraceId(v string)`

SetTraceId sets TraceId field to given value.


### SetTraceIdNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetTraceIdNil(b bool)`

 SetTraceIdNil sets the value for TraceId to be an explicit nil

### UnsetTraceId
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetTraceId()`

UnsetTraceId ensures that no value is present for TraceId, not even an explicit nil
### GetUsageCompleteness

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetUsageCompleteness() string`

GetUsageCompleteness returns the UsageCompleteness field if non-nil, zero value otherwise.

### GetUsageCompletenessOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetUsageCompletenessOk() (*string, bool)`

GetUsageCompletenessOk returns a tuple with the UsageCompleteness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageCompleteness

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetUsageCompleteness(v string)`

SetUsageCompleteness sets UsageCompleteness field to given value.


### SetUsageCompletenessNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetUsageCompletenessNil(b bool)`

 SetUsageCompletenessNil sets the value for UsageCompleteness to be an explicit nil

### UnsetUsageCompleteness
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetUsageCompleteness()`

UnsetUsageCompleteness ensures that no value is present for UsageCompleteness, not even an explicit nil
### GetUsageSequence

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetUsageSequence() int32`

GetUsageSequence returns the UsageSequence field if non-nil, zero value otherwise.

### GetUsageSequenceOk

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) GetUsageSequenceOk() (*int32, bool)`

GetUsageSequenceOk returns a tuple with the UsageSequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageSequence

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetUsageSequence(v int32)`

SetUsageSequence sets UsageSequence field to given value.


### SetUsageSequenceNil

`func (o *AuditEntryDetailCorrelatedAgentRunsInner) SetUsageSequenceNil(b bool)`

 SetUsageSequenceNil sets the value for UsageSequence to be an explicit nil

### UnsetUsageSequence
`func (o *AuditEntryDetailCorrelatedAgentRunsInner) UnsetUsageSequence()`

UnsetUsageSequence ensures that no value is present for UsageSequence, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


