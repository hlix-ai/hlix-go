# WorkspaceUsageRunsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingSource** | **NullableString** |  | 
**BilledTo** | **NullableString** |  | 
**CoderAccountId** | **NullableString** |  | 
**CostMicros** | **NullableInt64** |  | 
**CredentialKind** | **NullableString** |  | 
**FundingMode** | **NullableString** |  | 
**Id** | **string** |  | 
**Model** | **string** |  | 
**Persona** | **NullableString** |  | 
**ProjectName** | **NullableString** |  | 
**Role** | **string** |  | 
**StartedAt** | **string** |  | 
**TokensIn** | **NullableInt32** |  | 
**TokensOut** | **NullableInt32** |  | 
**UsageCompleteness** | **NullableString** |  | 

## Methods

### NewWorkspaceUsageRunsInner

`func NewWorkspaceUsageRunsInner(accountingSource NullableString, billedTo NullableString, coderAccountId NullableString, costMicros NullableInt64, credentialKind NullableString, fundingMode NullableString, id string, model string, persona NullableString, projectName NullableString, role string, startedAt string, tokensIn NullableInt32, tokensOut NullableInt32, usageCompleteness NullableString, ) *WorkspaceUsageRunsInner`

NewWorkspaceUsageRunsInner instantiates a new WorkspaceUsageRunsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceUsageRunsInnerWithDefaults

`func NewWorkspaceUsageRunsInnerWithDefaults() *WorkspaceUsageRunsInner`

NewWorkspaceUsageRunsInnerWithDefaults instantiates a new WorkspaceUsageRunsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingSource

`func (o *WorkspaceUsageRunsInner) GetAccountingSource() string`

GetAccountingSource returns the AccountingSource field if non-nil, zero value otherwise.

### GetAccountingSourceOk

`func (o *WorkspaceUsageRunsInner) GetAccountingSourceOk() (*string, bool)`

GetAccountingSourceOk returns a tuple with the AccountingSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingSource

`func (o *WorkspaceUsageRunsInner) SetAccountingSource(v string)`

SetAccountingSource sets AccountingSource field to given value.


### SetAccountingSourceNil

`func (o *WorkspaceUsageRunsInner) SetAccountingSourceNil(b bool)`

 SetAccountingSourceNil sets the value for AccountingSource to be an explicit nil

### UnsetAccountingSource
`func (o *WorkspaceUsageRunsInner) UnsetAccountingSource()`

UnsetAccountingSource ensures that no value is present for AccountingSource, not even an explicit nil
### GetBilledTo

`func (o *WorkspaceUsageRunsInner) GetBilledTo() string`

GetBilledTo returns the BilledTo field if non-nil, zero value otherwise.

### GetBilledToOk

`func (o *WorkspaceUsageRunsInner) GetBilledToOk() (*string, bool)`

GetBilledToOk returns a tuple with the BilledTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledTo

`func (o *WorkspaceUsageRunsInner) SetBilledTo(v string)`

SetBilledTo sets BilledTo field to given value.


### SetBilledToNil

`func (o *WorkspaceUsageRunsInner) SetBilledToNil(b bool)`

 SetBilledToNil sets the value for BilledTo to be an explicit nil

### UnsetBilledTo
`func (o *WorkspaceUsageRunsInner) UnsetBilledTo()`

UnsetBilledTo ensures that no value is present for BilledTo, not even an explicit nil
### GetCoderAccountId

`func (o *WorkspaceUsageRunsInner) GetCoderAccountId() string`

GetCoderAccountId returns the CoderAccountId field if non-nil, zero value otherwise.

### GetCoderAccountIdOk

`func (o *WorkspaceUsageRunsInner) GetCoderAccountIdOk() (*string, bool)`

GetCoderAccountIdOk returns a tuple with the CoderAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoderAccountId

`func (o *WorkspaceUsageRunsInner) SetCoderAccountId(v string)`

SetCoderAccountId sets CoderAccountId field to given value.


### SetCoderAccountIdNil

`func (o *WorkspaceUsageRunsInner) SetCoderAccountIdNil(b bool)`

 SetCoderAccountIdNil sets the value for CoderAccountId to be an explicit nil

### UnsetCoderAccountId
`func (o *WorkspaceUsageRunsInner) UnsetCoderAccountId()`

UnsetCoderAccountId ensures that no value is present for CoderAccountId, not even an explicit nil
### GetCostMicros

`func (o *WorkspaceUsageRunsInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *WorkspaceUsageRunsInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *WorkspaceUsageRunsInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *WorkspaceUsageRunsInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *WorkspaceUsageRunsInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCredentialKind

`func (o *WorkspaceUsageRunsInner) GetCredentialKind() string`

GetCredentialKind returns the CredentialKind field if non-nil, zero value otherwise.

### GetCredentialKindOk

`func (o *WorkspaceUsageRunsInner) GetCredentialKindOk() (*string, bool)`

GetCredentialKindOk returns a tuple with the CredentialKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentialKind

`func (o *WorkspaceUsageRunsInner) SetCredentialKind(v string)`

SetCredentialKind sets CredentialKind field to given value.


### SetCredentialKindNil

`func (o *WorkspaceUsageRunsInner) SetCredentialKindNil(b bool)`

 SetCredentialKindNil sets the value for CredentialKind to be an explicit nil

### UnsetCredentialKind
`func (o *WorkspaceUsageRunsInner) UnsetCredentialKind()`

UnsetCredentialKind ensures that no value is present for CredentialKind, not even an explicit nil
### GetFundingMode

`func (o *WorkspaceUsageRunsInner) GetFundingMode() string`

GetFundingMode returns the FundingMode field if non-nil, zero value otherwise.

### GetFundingModeOk

`func (o *WorkspaceUsageRunsInner) GetFundingModeOk() (*string, bool)`

GetFundingModeOk returns a tuple with the FundingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundingMode

`func (o *WorkspaceUsageRunsInner) SetFundingMode(v string)`

SetFundingMode sets FundingMode field to given value.


### SetFundingModeNil

`func (o *WorkspaceUsageRunsInner) SetFundingModeNil(b bool)`

 SetFundingModeNil sets the value for FundingMode to be an explicit nil

### UnsetFundingMode
`func (o *WorkspaceUsageRunsInner) UnsetFundingMode()`

UnsetFundingMode ensures that no value is present for FundingMode, not even an explicit nil
### GetId

`func (o *WorkspaceUsageRunsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkspaceUsageRunsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkspaceUsageRunsInner) SetId(v string)`

SetId sets Id field to given value.


### GetModel

`func (o *WorkspaceUsageRunsInner) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *WorkspaceUsageRunsInner) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *WorkspaceUsageRunsInner) SetModel(v string)`

SetModel sets Model field to given value.


### GetPersona

`func (o *WorkspaceUsageRunsInner) GetPersona() string`

GetPersona returns the Persona field if non-nil, zero value otherwise.

### GetPersonaOk

`func (o *WorkspaceUsageRunsInner) GetPersonaOk() (*string, bool)`

GetPersonaOk returns a tuple with the Persona field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersona

`func (o *WorkspaceUsageRunsInner) SetPersona(v string)`

SetPersona sets Persona field to given value.


### SetPersonaNil

`func (o *WorkspaceUsageRunsInner) SetPersonaNil(b bool)`

 SetPersonaNil sets the value for Persona to be an explicit nil

### UnsetPersona
`func (o *WorkspaceUsageRunsInner) UnsetPersona()`

UnsetPersona ensures that no value is present for Persona, not even an explicit nil
### GetProjectName

`func (o *WorkspaceUsageRunsInner) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *WorkspaceUsageRunsInner) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *WorkspaceUsageRunsInner) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### SetProjectNameNil

`func (o *WorkspaceUsageRunsInner) SetProjectNameNil(b bool)`

 SetProjectNameNil sets the value for ProjectName to be an explicit nil

### UnsetProjectName
`func (o *WorkspaceUsageRunsInner) UnsetProjectName()`

UnsetProjectName ensures that no value is present for ProjectName, not even an explicit nil
### GetRole

`func (o *WorkspaceUsageRunsInner) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *WorkspaceUsageRunsInner) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *WorkspaceUsageRunsInner) SetRole(v string)`

SetRole sets Role field to given value.


### GetStartedAt

`func (o *WorkspaceUsageRunsInner) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *WorkspaceUsageRunsInner) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *WorkspaceUsageRunsInner) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetTokensIn

`func (o *WorkspaceUsageRunsInner) GetTokensIn() int32`

GetTokensIn returns the TokensIn field if non-nil, zero value otherwise.

### GetTokensInOk

`func (o *WorkspaceUsageRunsInner) GetTokensInOk() (*int32, bool)`

GetTokensInOk returns a tuple with the TokensIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensIn

`func (o *WorkspaceUsageRunsInner) SetTokensIn(v int32)`

SetTokensIn sets TokensIn field to given value.


### SetTokensInNil

`func (o *WorkspaceUsageRunsInner) SetTokensInNil(b bool)`

 SetTokensInNil sets the value for TokensIn to be an explicit nil

### UnsetTokensIn
`func (o *WorkspaceUsageRunsInner) UnsetTokensIn()`

UnsetTokensIn ensures that no value is present for TokensIn, not even an explicit nil
### GetTokensOut

`func (o *WorkspaceUsageRunsInner) GetTokensOut() int32`

GetTokensOut returns the TokensOut field if non-nil, zero value otherwise.

### GetTokensOutOk

`func (o *WorkspaceUsageRunsInner) GetTokensOutOk() (*int32, bool)`

GetTokensOutOk returns a tuple with the TokensOut field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensOut

`func (o *WorkspaceUsageRunsInner) SetTokensOut(v int32)`

SetTokensOut sets TokensOut field to given value.


### SetTokensOutNil

`func (o *WorkspaceUsageRunsInner) SetTokensOutNil(b bool)`

 SetTokensOutNil sets the value for TokensOut to be an explicit nil

### UnsetTokensOut
`func (o *WorkspaceUsageRunsInner) UnsetTokensOut()`

UnsetTokensOut ensures that no value is present for TokensOut, not even an explicit nil
### GetUsageCompleteness

`func (o *WorkspaceUsageRunsInner) GetUsageCompleteness() string`

GetUsageCompleteness returns the UsageCompleteness field if non-nil, zero value otherwise.

### GetUsageCompletenessOk

`func (o *WorkspaceUsageRunsInner) GetUsageCompletenessOk() (*string, bool)`

GetUsageCompletenessOk returns a tuple with the UsageCompleteness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageCompleteness

`func (o *WorkspaceUsageRunsInner) SetUsageCompleteness(v string)`

SetUsageCompleteness sets UsageCompleteness field to given value.


### SetUsageCompletenessNil

`func (o *WorkspaceUsageRunsInner) SetUsageCompletenessNil(b bool)`

 SetUsageCompletenessNil sets the value for UsageCompleteness to be an explicit nil

### UnsetUsageCompleteness
`func (o *WorkspaceUsageRunsInner) UnsetUsageCompleteness()`

UnsetUsageCompleteness ensures that no value is present for UsageCompleteness, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


