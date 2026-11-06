# AgentRunSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingSource** | **NullableString** |  | 
**BilledTo** | **NullableString** |  | 
**CoderAccountId** | **NullableString** |  | 
**CompletedAt** | **NullableString** |  | 
**CostMicros** | **NullableInt64** |  | 
**CredentialKind** | **NullableString** |  | 
**FundingMode** | **NullableString** |  | 
**Id** | **string** |  | 
**Model** | **string** |  | 
**Persona** | **NullableString** |  | 
**Role** | **string** |  | 
**StartedAt** | **string** |  | 
**Status** | **string** |  | 
**TaskId** | **NullableString** |  | 
**TokensIn** | **NullableInt32** |  | 
**TokensOut** | **NullableInt32** |  | 
**UsageCompleteness** | **NullableString** |  | 

## Methods

### NewAgentRunSummary

`func NewAgentRunSummary(accountingSource NullableString, billedTo NullableString, coderAccountId NullableString, completedAt NullableString, costMicros NullableInt64, credentialKind NullableString, fundingMode NullableString, id string, model string, persona NullableString, role string, startedAt string, status string, taskId NullableString, tokensIn NullableInt32, tokensOut NullableInt32, usageCompleteness NullableString, ) *AgentRunSummary`

NewAgentRunSummary instantiates a new AgentRunSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentRunSummaryWithDefaults

`func NewAgentRunSummaryWithDefaults() *AgentRunSummary`

NewAgentRunSummaryWithDefaults instantiates a new AgentRunSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingSource

`func (o *AgentRunSummary) GetAccountingSource() string`

GetAccountingSource returns the AccountingSource field if non-nil, zero value otherwise.

### GetAccountingSourceOk

`func (o *AgentRunSummary) GetAccountingSourceOk() (*string, bool)`

GetAccountingSourceOk returns a tuple with the AccountingSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingSource

`func (o *AgentRunSummary) SetAccountingSource(v string)`

SetAccountingSource sets AccountingSource field to given value.


### SetAccountingSourceNil

`func (o *AgentRunSummary) SetAccountingSourceNil(b bool)`

 SetAccountingSourceNil sets the value for AccountingSource to be an explicit nil

### UnsetAccountingSource
`func (o *AgentRunSummary) UnsetAccountingSource()`

UnsetAccountingSource ensures that no value is present for AccountingSource, not even an explicit nil
### GetBilledTo

`func (o *AgentRunSummary) GetBilledTo() string`

GetBilledTo returns the BilledTo field if non-nil, zero value otherwise.

### GetBilledToOk

`func (o *AgentRunSummary) GetBilledToOk() (*string, bool)`

GetBilledToOk returns a tuple with the BilledTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledTo

`func (o *AgentRunSummary) SetBilledTo(v string)`

SetBilledTo sets BilledTo field to given value.


### SetBilledToNil

`func (o *AgentRunSummary) SetBilledToNil(b bool)`

 SetBilledToNil sets the value for BilledTo to be an explicit nil

### UnsetBilledTo
`func (o *AgentRunSummary) UnsetBilledTo()`

UnsetBilledTo ensures that no value is present for BilledTo, not even an explicit nil
### GetCoderAccountId

`func (o *AgentRunSummary) GetCoderAccountId() string`

GetCoderAccountId returns the CoderAccountId field if non-nil, zero value otherwise.

### GetCoderAccountIdOk

`func (o *AgentRunSummary) GetCoderAccountIdOk() (*string, bool)`

GetCoderAccountIdOk returns a tuple with the CoderAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoderAccountId

`func (o *AgentRunSummary) SetCoderAccountId(v string)`

SetCoderAccountId sets CoderAccountId field to given value.


### SetCoderAccountIdNil

`func (o *AgentRunSummary) SetCoderAccountIdNil(b bool)`

 SetCoderAccountIdNil sets the value for CoderAccountId to be an explicit nil

### UnsetCoderAccountId
`func (o *AgentRunSummary) UnsetCoderAccountId()`

UnsetCoderAccountId ensures that no value is present for CoderAccountId, not even an explicit nil
### GetCompletedAt

`func (o *AgentRunSummary) GetCompletedAt() string`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AgentRunSummary) GetCompletedAtOk() (*string, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AgentRunSummary) SetCompletedAt(v string)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *AgentRunSummary) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AgentRunSummary) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCostMicros

`func (o *AgentRunSummary) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AgentRunSummary) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AgentRunSummary) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AgentRunSummary) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AgentRunSummary) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCredentialKind

`func (o *AgentRunSummary) GetCredentialKind() string`

GetCredentialKind returns the CredentialKind field if non-nil, zero value otherwise.

### GetCredentialKindOk

`func (o *AgentRunSummary) GetCredentialKindOk() (*string, bool)`

GetCredentialKindOk returns a tuple with the CredentialKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentialKind

`func (o *AgentRunSummary) SetCredentialKind(v string)`

SetCredentialKind sets CredentialKind field to given value.


### SetCredentialKindNil

`func (o *AgentRunSummary) SetCredentialKindNil(b bool)`

 SetCredentialKindNil sets the value for CredentialKind to be an explicit nil

### UnsetCredentialKind
`func (o *AgentRunSummary) UnsetCredentialKind()`

UnsetCredentialKind ensures that no value is present for CredentialKind, not even an explicit nil
### GetFundingMode

`func (o *AgentRunSummary) GetFundingMode() string`

GetFundingMode returns the FundingMode field if non-nil, zero value otherwise.

### GetFundingModeOk

`func (o *AgentRunSummary) GetFundingModeOk() (*string, bool)`

GetFundingModeOk returns a tuple with the FundingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundingMode

`func (o *AgentRunSummary) SetFundingMode(v string)`

SetFundingMode sets FundingMode field to given value.


### SetFundingModeNil

`func (o *AgentRunSummary) SetFundingModeNil(b bool)`

 SetFundingModeNil sets the value for FundingMode to be an explicit nil

### UnsetFundingMode
`func (o *AgentRunSummary) UnsetFundingMode()`

UnsetFundingMode ensures that no value is present for FundingMode, not even an explicit nil
### GetId

`func (o *AgentRunSummary) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgentRunSummary) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgentRunSummary) SetId(v string)`

SetId sets Id field to given value.


### GetModel

`func (o *AgentRunSummary) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AgentRunSummary) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AgentRunSummary) SetModel(v string)`

SetModel sets Model field to given value.


### GetPersona

`func (o *AgentRunSummary) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *AgentRunSummary) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *AgentRunSummary) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *AgentRunSummary) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *AgentRunSummary) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetRole

`func (o *AgentRunSummary) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *AgentRunSummary) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *AgentRunSummary) SetRole(v string)`

SetRole sets Role field to given value.


### GetStartedAt

`func (o *AgentRunSummary) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *AgentRunSummary) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *AgentRunSummary) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *AgentRunSummary) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AgentRunSummary) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AgentRunSummary) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *AgentRunSummary) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *AgentRunSummary) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *AgentRunSummary) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *AgentRunSummary) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *AgentRunSummary) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTokensIn

`func (o *AgentRunSummary) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *AgentRunSummary) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *AgentRunSummary) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### SetTokensInNil

`func (o *AgentRunSummary) SetTokensInNil(b bool)`

 SetTokensInNil sets the value for TokensIn to be an explicit nil

### UnsetTokensIn
`func (o *AgentRunSummary) UnsetTokensIn()`

UnsetTokensIn ensures that no value is present for TokensIn, not even an explicit nil
### GetTokensOut

`func (o *AgentRunSummary) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *AgentRunSummary) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *AgentRunSummary) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.


### SetTokensOutNil

`func (o *AgentRunSummary) SetTokensOutNil(b bool)`

 SetTokensOutNil sets the value for TokensOut to be an explicit nil

### UnsetTokensOut
`func (o *AgentRunSummary) UnsetTokensOut()`

UnsetTokensOut ensures that no value is present for TokensOut, not even an explicit nil
### GetUsageCompleteness

`func (o *AgentRunSummary) GetUsageCompleteness() string`

GetUsageCompleteness returns the UsageCompleteness field if non-nil, zero value otherwise.

### GetUsageCompletenessOk

`func (o *AgentRunSummary) GetUsageCompletenessOk() (*string, bool)`

GetUsageCompletenessOk returns a tuple with the UsageCompleteness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageCompleteness

`func (o *AgentRunSummary) SetUsageCompleteness(v string)`

SetUsageCompleteness sets UsageCompleteness field to given value.


### SetUsageCompletenessNil

`func (o *AgentRunSummary) SetUsageCompletenessNil(b bool)`

 SetUsageCompletenessNil sets the value for UsageCompleteness to be an explicit nil

### UnsetUsageCompleteness
`func (o *AgentRunSummary) UnsetUsageCompleteness()`

UnsetUsageCompleteness ensures that no value is present for UsageCompleteness, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


