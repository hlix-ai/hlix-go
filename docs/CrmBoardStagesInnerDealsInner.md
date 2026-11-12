# CrmBoardStagesInnerDealsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientAccount** | [**NullableCrmBoardStagesInnerDealsInnerClientAccount**](CrmBoardStagesInnerDealsInnerClientAccount.md) |  |
**ClientAccountId** | **string** |  |
**ClosedAt** | **NullableString** |  |
**CreatedAt** | **string** |  |
**Currency** | **NullableString** |  |
**ExpectedCloseOn** | **NullableString** |  |
**Id** | **string** |  |
**LastActivityAt** | **string** |  |
**LostReason** | **NullableString** |  |
**NextStep** | **NullableString** |  |
**NextStepAt** | **NullableString** |  |
**OrganizationId** | **string** |  |
**Owner** | [**NullableCrmBoardStagesInnerDealsInnerOwner**](CrmBoardStagesInnerDealsInnerOwner.md) |  |
**OwnerUserId** | **NullableString** |  |
**PipelineId** | **string** |  |
**PrimaryContact** | [**NullableCrmBoardStagesInnerDealsInnerPrimaryContact**](CrmBoardStagesInnerDealsInnerPrimaryContact.md) |  |
**SourceKind** | **string** |  |
**SourcePlay** | [**NullableCrmBoardStagesInnerDealsInnerSourcePlay**](CrmBoardStagesInnerDealsInnerSourcePlay.md) |  |
**SourcePlayId** | **NullableString** |  |
**Stage** | **string** |  |
**Suggestion** | [**NullableCrmBoardStagesInnerDealsInnerSuggestion**](CrmBoardStagesInnerDealsInnerSuggestion.md) |  |
**UpdatedAt** | **string** |  |
**ValueMicros** | **NullableInt64** |  |
**WonAt** | **NullableString** |  |

## Methods

### NewCrmBoardStagesInnerDealsInner

`func NewCrmBoardStagesInnerDealsInner(clientAccount NullableCrmBoardStagesInnerDealsInnerClientAccount, clientAccountId string, closedAt NullableString, createdAt string, currency NullableString, expectedCloseOn NullableString, id string, lastActivityAt string, lostReason NullableString, nextStep NullableString, nextStepAt NullableString, organizationId string, owner NullableCrmBoardStagesInnerDealsInnerOwner, ownerUserId NullableString, pipelineId string, primaryContact NullableCrmBoardStagesInnerDealsInnerPrimaryContact, sourceKind string, sourcePlay NullableCrmBoardStagesInnerDealsInnerSourcePlay, sourcePlayId NullableString, stage string, suggestion NullableCrmBoardStagesInnerDealsInnerSuggestion, updatedAt string, valueMicros NullableInt64, wonAt NullableString, ) *CrmBoardStagesInnerDealsInner`

NewCrmBoardStagesInnerDealsInner instantiates a new CrmBoardStagesInnerDealsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCrmBoardStagesInnerDealsInnerWithDefaults

`func NewCrmBoardStagesInnerDealsInnerWithDefaults() *CrmBoardStagesInnerDealsInner`

NewCrmBoardStagesInnerDealsInnerWithDefaults instantiates a new CrmBoardStagesInnerDealsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetClientAccount

`func (o *CrmBoardStagesInnerDealsInner) GetClientAccount() CrmBoardStagesInnerDealsInnerClientAccount`

GetClientAccount returns the ClientAccount field if non-nil, zero value otherwise.

### GetClientAccountOk

`func (o *CrmBoardStagesInnerDealsInner) GetClientAccountOk() (*CrmBoardStagesInnerDealsInnerClientAccount, bool)`

GetClientAccountOk returns a tuple with the ClientAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccount

`func (o *CrmBoardStagesInnerDealsInner) SetClientAccount(v CrmBoardStagesInnerDealsInnerClientAccount)`

SetClientAccount sets ClientAccount field to given value.


### SetClientAccountNil

`func (o *CrmBoardStagesInnerDealsInner) SetClientAccountNil(b bool)`

 SetClientAccountNil sets the value for ClientAccount to be an explicit nil

### UnsetClientAccount
`func (o *CrmBoardStagesInnerDealsInner) UnsetClientAccount()`

UnsetClientAccount ensures that no value is present for ClientAccount, not even an explicit nil
### GetClientAccountId

`func (o *CrmBoardStagesInnerDealsInner) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CrmBoardStagesInnerDealsInner) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CrmBoardStagesInnerDealsInner) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetClosedAt

`func (o *CrmBoardStagesInnerDealsInner) GetClosedAt() string`

GetClosedAt returns the ClosedAt field if non-nil, zero value otherwise.

### GetClosedAtOk

`func (o *CrmBoardStagesInnerDealsInner) GetClosedAtOk() (*string, bool)`

GetClosedAtOk returns a tuple with the ClosedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClosedAt

`func (o *CrmBoardStagesInnerDealsInner) SetClosedAt(v string)`

SetClosedAt sets ClosedAt field to given value.


### SetClosedAtNil

`func (o *CrmBoardStagesInnerDealsInner) SetClosedAtNil(b bool)`

 SetClosedAtNil sets the value for ClosedAt to be an explicit nil

### UnsetClosedAt
`func (o *CrmBoardStagesInnerDealsInner) UnsetClosedAt()`

UnsetClosedAt ensures that no value is present for ClosedAt, not even an explicit nil
### GetCreatedAt

`func (o *CrmBoardStagesInnerDealsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CrmBoardStagesInnerDealsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CrmBoardStagesInnerDealsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrency

`func (o *CrmBoardStagesInnerDealsInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CrmBoardStagesInnerDealsInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CrmBoardStagesInnerDealsInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### SetCurrencyNil

`func (o *CrmBoardStagesInnerDealsInner) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CrmBoardStagesInnerDealsInner) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetExpectedCloseOn

`func (o *CrmBoardStagesInnerDealsInner) GetExpectedCloseOn() string`

GetExpectedCloseOn returns the ExpectedCloseOn field if non-nil, zero value otherwise.

### GetExpectedCloseOnOk

`func (o *CrmBoardStagesInnerDealsInner) GetExpectedCloseOnOk() (*string, bool)`

GetExpectedCloseOnOk returns a tuple with the ExpectedCloseOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedCloseOn

`func (o *CrmBoardStagesInnerDealsInner) SetExpectedCloseOn(v string)`

SetExpectedCloseOn sets ExpectedCloseOn field to given value.


### SetExpectedCloseOnNil

`func (o *CrmBoardStagesInnerDealsInner) SetExpectedCloseOnNil(b bool)`

 SetExpectedCloseOnNil sets the value for ExpectedCloseOn to be an explicit nil

### UnsetExpectedCloseOn
`func (o *CrmBoardStagesInnerDealsInner) UnsetExpectedCloseOn()`

UnsetExpectedCloseOn ensures that no value is present for ExpectedCloseOn, not even an explicit nil
### GetId

`func (o *CrmBoardStagesInnerDealsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CrmBoardStagesInnerDealsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CrmBoardStagesInnerDealsInner) SetId(v string)`

SetId sets Id field to given value.


### GetLastActivityAt

`func (o *CrmBoardStagesInnerDealsInner) GetLastActivityAt() string`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *CrmBoardStagesInnerDealsInner) GetLastActivityAtOk() (*string, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *CrmBoardStagesInnerDealsInner) SetLastActivityAt(v string)`

SetLastActivityAt sets LastActivityAt field to given value.


### GetLostReason

`func (o *CrmBoardStagesInnerDealsInner) GetLostReason() string`

GetLostReason returns the LostReason field if non-nil, zero value otherwise.

### GetLostReasonOk

`func (o *CrmBoardStagesInnerDealsInner) GetLostReasonOk() (*string, bool)`

GetLostReasonOk returns a tuple with the LostReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLostReason

`func (o *CrmBoardStagesInnerDealsInner) SetLostReason(v string)`

SetLostReason sets LostReason field to given value.


### SetLostReasonNil

`func (o *CrmBoardStagesInnerDealsInner) SetLostReasonNil(b bool)`

 SetLostReasonNil sets the value for LostReason to be an explicit nil

### UnsetLostReason
`func (o *CrmBoardStagesInnerDealsInner) UnsetLostReason()`

UnsetLostReason ensures that no value is present for LostReason, not even an explicit nil
### GetNextStep

`func (o *CrmBoardStagesInnerDealsInner) GetNextStep() string`

GetNextStep returns the NextStep field if non-nil, zero value otherwise.

### GetNextStepOk

`func (o *CrmBoardStagesInnerDealsInner) GetNextStepOk() (*string, bool)`

GetNextStepOk returns a tuple with the NextStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextStep

`func (o *CrmBoardStagesInnerDealsInner) SetNextStep(v string)`

SetNextStep sets NextStep field to given value.


### SetNextStepNil

`func (o *CrmBoardStagesInnerDealsInner) SetNextStepNil(b bool)`

 SetNextStepNil sets the value for NextStep to be an explicit nil

### UnsetNextStep
`func (o *CrmBoardStagesInnerDealsInner) UnsetNextStep()`

UnsetNextStep ensures that no value is present for NextStep, not even an explicit nil
### GetNextStepAt

`func (o *CrmBoardStagesInnerDealsInner) GetNextStepAt() string`

GetNextStepAt returns the NextStepAt field if non-nil, zero value otherwise.

### GetNextStepAtOk

`func (o *CrmBoardStagesInnerDealsInner) GetNextStepAtOk() (*string, bool)`

GetNextStepAtOk returns a tuple with the NextStepAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextStepAt

`func (o *CrmBoardStagesInnerDealsInner) SetNextStepAt(v string)`

SetNextStepAt sets NextStepAt field to given value.


### SetNextStepAtNil

`func (o *CrmBoardStagesInnerDealsInner) SetNextStepAtNil(b bool)`

 SetNextStepAtNil sets the value for NextStepAt to be an explicit nil

### UnsetNextStepAt
`func (o *CrmBoardStagesInnerDealsInner) UnsetNextStepAt()`

UnsetNextStepAt ensures that no value is present for NextStepAt, not even an explicit nil
### GetOrganizationId

`func (o *CrmBoardStagesInnerDealsInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CrmBoardStagesInnerDealsInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CrmBoardStagesInnerDealsInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOwner

`func (o *CrmBoardStagesInnerDealsInner) GetOwner() CrmBoardStagesInnerDealsInnerOwner`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *CrmBoardStagesInnerDealsInner) GetOwnerOk() (*CrmBoardStagesInnerDealsInnerOwner, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *CrmBoardStagesInnerDealsInner) SetOwner(v CrmBoardStagesInnerDealsInnerOwner)`

SetOwner sets Owner field to given value.


### SetOwnerNil

`func (o *CrmBoardStagesInnerDealsInner) SetOwnerNil(b bool)`

 SetOwnerNil sets the value for Owner to be an explicit nil

### UnsetOwner
`func (o *CrmBoardStagesInnerDealsInner) UnsetOwner()`

UnsetOwner ensures that no value is present for Owner, not even an explicit nil
### GetOwnerUserId

`func (o *CrmBoardStagesInnerDealsInner) GetOwnerUserId() string`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *CrmBoardStagesInnerDealsInner) GetOwnerUserIdOk() (*string, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *CrmBoardStagesInnerDealsInner) SetOwnerUserId(v string)`

SetOwnerUserId sets OwnerUserId field to given value.


### SetOwnerUserIdNil

`func (o *CrmBoardStagesInnerDealsInner) SetOwnerUserIdNil(b bool)`

 SetOwnerUserIdNil sets the value for OwnerUserId to be an explicit nil

### UnsetOwnerUserId
`func (o *CrmBoardStagesInnerDealsInner) UnsetOwnerUserId()`

UnsetOwnerUserId ensures that no value is present for OwnerUserId, not even an explicit nil
### GetPipelineId

`func (o *CrmBoardStagesInnerDealsInner) GetPipelineId() string`

GetPipelineId returns the PipelineId field if non-nil, zero value otherwise.

### GetPipelineIdOk

`func (o *CrmBoardStagesInnerDealsInner) GetPipelineIdOk() (*string, bool)`

GetPipelineIdOk returns a tuple with the PipelineId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipelineId

`func (o *CrmBoardStagesInnerDealsInner) SetPipelineId(v string)`

SetPipelineId sets PipelineId field to given value.


### GetPrimaryContact

`func (o *CrmBoardStagesInnerDealsInner) GetPrimaryContact() CrmBoardStagesInnerDealsInnerPrimaryContact`

GetPrimaryContact returns the PrimaryContact field if non-nil, zero value otherwise.

### GetPrimaryContactOk

`func (o *CrmBoardStagesInnerDealsInner) GetPrimaryContactOk() (*CrmBoardStagesInnerDealsInnerPrimaryContact, bool)`

GetPrimaryContactOk returns a tuple with the PrimaryContact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryContact

`func (o *CrmBoardStagesInnerDealsInner) SetPrimaryContact(v CrmBoardStagesInnerDealsInnerPrimaryContact)`

SetPrimaryContact sets PrimaryContact field to given value.


### SetPrimaryContactNil

`func (o *CrmBoardStagesInnerDealsInner) SetPrimaryContactNil(b bool)`

 SetPrimaryContactNil sets the value for PrimaryContact to be an explicit nil

### UnsetPrimaryContact
`func (o *CrmBoardStagesInnerDealsInner) UnsetPrimaryContact()`

UnsetPrimaryContact ensures that no value is present for PrimaryContact, not even an explicit nil
### GetSourceKind

`func (o *CrmBoardStagesInnerDealsInner) GetSourceKind() string`

GetSourceKind returns the SourceKind field if non-nil, zero value otherwise.

### GetSourceKindOk

`func (o *CrmBoardStagesInnerDealsInner) GetSourceKindOk() (*string, bool)`

GetSourceKindOk returns a tuple with the SourceKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceKind

`func (o *CrmBoardStagesInnerDealsInner) SetSourceKind(v string)`

SetSourceKind sets SourceKind field to given value.


### GetSourcePlay

`func (o *CrmBoardStagesInnerDealsInner) GetSourcePlay() CrmBoardStagesInnerDealsInnerSourcePlay`

GetSourcePlay returns the SourcePlay field if non-nil, zero value otherwise.

### GetSourcePlayOk

`func (o *CrmBoardStagesInnerDealsInner) GetSourcePlayOk() (*CrmBoardStagesInnerDealsInnerSourcePlay, bool)`

GetSourcePlayOk returns a tuple with the SourcePlay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePlay

`func (o *CrmBoardStagesInnerDealsInner) SetSourcePlay(v CrmBoardStagesInnerDealsInnerSourcePlay)`

SetSourcePlay sets SourcePlay field to given value.


### SetSourcePlayNil

`func (o *CrmBoardStagesInnerDealsInner) SetSourcePlayNil(b bool)`

 SetSourcePlayNil sets the value for SourcePlay to be an explicit nil

### UnsetSourcePlay
`func (o *CrmBoardStagesInnerDealsInner) UnsetSourcePlay()`

UnsetSourcePlay ensures that no value is present for SourcePlay, not even an explicit nil
### GetSourcePlayId

`func (o *CrmBoardStagesInnerDealsInner) GetSourcePlayId() string`

GetSourcePlayId returns the SourcePlayId field if non-nil, zero value otherwise.

### GetSourcePlayIdOk

`func (o *CrmBoardStagesInnerDealsInner) GetSourcePlayIdOk() (*string, bool)`

GetSourcePlayIdOk returns a tuple with the SourcePlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePlayId

`func (o *CrmBoardStagesInnerDealsInner) SetSourcePlayId(v string)`

SetSourcePlayId sets SourcePlayId field to given value.


### SetSourcePlayIdNil

`func (o *CrmBoardStagesInnerDealsInner) SetSourcePlayIdNil(b bool)`

 SetSourcePlayIdNil sets the value for SourcePlayId to be an explicit nil

### UnsetSourcePlayId
`func (o *CrmBoardStagesInnerDealsInner) UnsetSourcePlayId()`

UnsetSourcePlayId ensures that no value is present for SourcePlayId, not even an explicit nil
### GetStage

`func (o *CrmBoardStagesInnerDealsInner) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *CrmBoardStagesInnerDealsInner) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *CrmBoardStagesInnerDealsInner) SetStage(v string)`

SetStage sets Stage field to given value.


### GetSuggestion

`func (o *CrmBoardStagesInnerDealsInner) GetSuggestion() CrmBoardStagesInnerDealsInnerSuggestion`

GetSuggestion returns the Suggestion field if non-nil, zero value otherwise.

### GetSuggestionOk

`func (o *CrmBoardStagesInnerDealsInner) GetSuggestionOk() (*CrmBoardStagesInnerDealsInnerSuggestion, bool)`

GetSuggestionOk returns a tuple with the Suggestion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestion

`func (o *CrmBoardStagesInnerDealsInner) SetSuggestion(v CrmBoardStagesInnerDealsInnerSuggestion)`

SetSuggestion sets Suggestion field to given value.


### SetSuggestionNil

`func (o *CrmBoardStagesInnerDealsInner) SetSuggestionNil(b bool)`

 SetSuggestionNil sets the value for Suggestion to be an explicit nil

### UnsetSuggestion
`func (o *CrmBoardStagesInnerDealsInner) UnsetSuggestion()`

UnsetSuggestion ensures that no value is present for Suggestion, not even an explicit nil
### GetUpdatedAt

`func (o *CrmBoardStagesInnerDealsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CrmBoardStagesInnerDealsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CrmBoardStagesInnerDealsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetValueMicros

`func (o *CrmBoardStagesInnerDealsInner) GetValueMicros() int64`

GetValueMicros returns the ValueMicros field if non-nil, zero value otherwise.

### GetValueMicrosOk

`func (o *CrmBoardStagesInnerDealsInner) GetValueMicrosOk() (*int64, bool)`

GetValueMicrosOk returns a tuple with the ValueMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueMicros

`func (o *CrmBoardStagesInnerDealsInner) SetValueMicros(v int64)`

SetValueMicros sets ValueMicros field to given value.


### SetValueMicrosNil

`func (o *CrmBoardStagesInnerDealsInner) SetValueMicrosNil(b bool)`

 SetValueMicrosNil sets the value for ValueMicros to be an explicit nil

### UnsetValueMicros
`func (o *CrmBoardStagesInnerDealsInner) UnsetValueMicros()`

UnsetValueMicros ensures that no value is present for ValueMicros, not even an explicit nil
### GetWonAt

`func (o *CrmBoardStagesInnerDealsInner) GetWonAt() string`

GetWonAt returns the WonAt field if non-nil, zero value otherwise.

### GetWonAtOk

`func (o *CrmBoardStagesInnerDealsInner) GetWonAtOk() (*string, bool)`

GetWonAtOk returns a tuple with the WonAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWonAt

`func (o *CrmBoardStagesInnerDealsInner) SetWonAt(v string)`

SetWonAt sets WonAt field to given value.


### SetWonAtNil

`func (o *CrmBoardStagesInnerDealsInner) SetWonAtNil(b bool)`

 SetWonAtNil sets the value for WonAt to be an explicit nil

### UnsetWonAt
`func (o *CrmBoardStagesInnerDealsInner) UnsetWonAt()`

UnsetWonAt ensures that no value is present for WonAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


