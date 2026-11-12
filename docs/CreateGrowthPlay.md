# CreateGrowthPlay

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Angle** | Pointer to **string** |  | [optional]
**AutoSendReplies** | Pointer to **bool** |  | [optional]
**DailyBudgetMicros** | Pointer to **int64** |  | [optional]
**ExampleClients** | Pointer to **[]string** |  | [optional]
**ExcludeDe** | Pointer to **bool** |  | [optional]
**ExcludeEu** | Pointer to **bool** |  | [optional]
**FirstEmail** | Pointer to [**CreateGrowthPlayFirstEmail**](CreateGrowthPlayFirstEmail.md) |  | [optional]
**GdprAcknowledged** | Pointer to **bool** |  | [optional]
**Keywords** | Pointer to **[]string** |  | [optional]
**Language** | Pointer to **string** |  | [optional]
**Name** | **string** |  |
**NegativeCriteria** | Pointer to **[]string** |  | [optional]
**PositiveCriteria** | Pointer to **[]string** |  | [optional]
**ReviewFirstN** | Pointer to **int32** |  | [optional]
**SendingSchedule** | Pointer to [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  | [optional]
**Sequence** | Pointer to [**NullableCreateGrowthPlaySequence**](CreateGrowthPlaySequence.md) |  | [optional]
**Status** | Pointer to **string** |  | [optional]
**Who** | [**CreateGrowthPlayWho**](CreateGrowthPlayWho.md) |  |
**WhyNow** | Pointer to [**CreateGrowthPlayWhyNow**](CreateGrowthPlayWhyNow.md) |  | [optional]

## Methods

### NewCreateGrowthPlay

`func NewCreateGrowthPlay(name string, who CreateGrowthPlayWho, ) *CreateGrowthPlay`

NewCreateGrowthPlay instantiates a new CreateGrowthPlay object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateGrowthPlayWithDefaults

`func NewCreateGrowthPlayWithDefaults() *CreateGrowthPlay`

NewCreateGrowthPlayWithDefaults instantiates a new CreateGrowthPlay object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAngle

`func (o *CreateGrowthPlay) GetAngle() string`

GetAngle returns the Angle field if non-nil, zero value otherwise.

### GetAngleOk

`func (o *CreateGrowthPlay) GetAngleOk() (*string, bool)`

GetAngleOk returns a tuple with the Angle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAngle

`func (o *CreateGrowthPlay) SetAngle(v string)`

SetAngle sets Angle field to given value.

### HasAngle

`func (o *CreateGrowthPlay) HasAngle() bool`

HasAngle returns a boolean if a field has been set.

### GetAutoSendReplies

`func (o *CreateGrowthPlay) GetAutoSendReplies() bool`

GetAutoSendReplies returns the AutoSendReplies field if non-nil, zero value otherwise.

### GetAutoSendRepliesOk

`func (o *CreateGrowthPlay) GetAutoSendRepliesOk() (*bool, bool)`

GetAutoSendRepliesOk returns a tuple with the AutoSendReplies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSendReplies

`func (o *CreateGrowthPlay) SetAutoSendReplies(v bool)`

SetAutoSendReplies sets AutoSendReplies field to given value.

### HasAutoSendReplies

`func (o *CreateGrowthPlay) HasAutoSendReplies() bool`

HasAutoSendReplies returns a boolean if a field has been set.

### GetDailyBudgetMicros

`func (o *CreateGrowthPlay) GetDailyBudgetMicros() int64`

GetDailyBudgetMicros returns the DailyBudgetMicros field if non-nil, zero value otherwise.

### GetDailyBudgetMicrosOk

`func (o *CreateGrowthPlay) GetDailyBudgetMicrosOk() (*int64, bool)`

GetDailyBudgetMicrosOk returns a tuple with the DailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyBudgetMicros

`func (o *CreateGrowthPlay) SetDailyBudgetMicros(v int64)`

SetDailyBudgetMicros sets DailyBudgetMicros field to given value.

### HasDailyBudgetMicros

`func (o *CreateGrowthPlay) HasDailyBudgetMicros() bool`

HasDailyBudgetMicros returns a boolean if a field has been set.

### GetExampleClients

`func (o *CreateGrowthPlay) GetExampleClients() []string`

GetExampleClients returns the ExampleClients field if non-nil, zero value otherwise.

### GetExampleClientsOk

`func (o *CreateGrowthPlay) GetExampleClientsOk() (*[]string, bool)`

GetExampleClientsOk returns a tuple with the ExampleClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExampleClients

`func (o *CreateGrowthPlay) SetExampleClients(v []string)`

SetExampleClients sets ExampleClients field to given value.

### HasExampleClients

`func (o *CreateGrowthPlay) HasExampleClients() bool`

HasExampleClients returns a boolean if a field has been set.

### GetExcludeDe

`func (o *CreateGrowthPlay) GetExcludeDe() bool`

GetExcludeDe returns the ExcludeDe field if non-nil, zero value otherwise.

### GetExcludeDeOk

`func (o *CreateGrowthPlay) GetExcludeDeOk() (*bool, bool)`

GetExcludeDeOk returns a tuple with the ExcludeDe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeDe

`func (o *CreateGrowthPlay) SetExcludeDe(v bool)`

SetExcludeDe sets ExcludeDe field to given value.

### HasExcludeDe

`func (o *CreateGrowthPlay) HasExcludeDe() bool`

HasExcludeDe returns a boolean if a field has been set.

### GetExcludeEu

`func (o *CreateGrowthPlay) GetExcludeEu() bool`

GetExcludeEu returns the ExcludeEu field if non-nil, zero value otherwise.

### GetExcludeEuOk

`func (o *CreateGrowthPlay) GetExcludeEuOk() (*bool, bool)`

GetExcludeEuOk returns a tuple with the ExcludeEu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeEu

`func (o *CreateGrowthPlay) SetExcludeEu(v bool)`

SetExcludeEu sets ExcludeEu field to given value.

### HasExcludeEu

`func (o *CreateGrowthPlay) HasExcludeEu() bool`

HasExcludeEu returns a boolean if a field has been set.

### GetFirstEmail

`func (o *CreateGrowthPlay) GetFirstEmail() CreateGrowthPlayFirstEmail`

GetFirstEmail returns the FirstEmail field if non-nil, zero value otherwise.

### GetFirstEmailOk

`func (o *CreateGrowthPlay) GetFirstEmailOk() (*CreateGrowthPlayFirstEmail, bool)`

GetFirstEmailOk returns a tuple with the FirstEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstEmail

`func (o *CreateGrowthPlay) SetFirstEmail(v CreateGrowthPlayFirstEmail)`

SetFirstEmail sets FirstEmail field to given value.

### HasFirstEmail

`func (o *CreateGrowthPlay) HasFirstEmail() bool`

HasFirstEmail returns a boolean if a field has been set.

### GetGdprAcknowledged

`func (o *CreateGrowthPlay) GetGdprAcknowledged() bool`

GetGdprAcknowledged returns the GdprAcknowledged field if non-nil, zero value otherwise.

### GetGdprAcknowledgedOk

`func (o *CreateGrowthPlay) GetGdprAcknowledgedOk() (*bool, bool)`

GetGdprAcknowledgedOk returns a tuple with the GdprAcknowledged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdprAcknowledged

`func (o *CreateGrowthPlay) SetGdprAcknowledged(v bool)`

SetGdprAcknowledged sets GdprAcknowledged field to given value.

### HasGdprAcknowledged

`func (o *CreateGrowthPlay) HasGdprAcknowledged() bool`

HasGdprAcknowledged returns a boolean if a field has been set.

### GetKeywords

`func (o *CreateGrowthPlay) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateGrowthPlay) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateGrowthPlay) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateGrowthPlay) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetLanguage

`func (o *CreateGrowthPlay) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *CreateGrowthPlay) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *CreateGrowthPlay) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *CreateGrowthPlay) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetName

`func (o *CreateGrowthPlay) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateGrowthPlay) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateGrowthPlay) SetName(v string)`

SetName sets Name field to given value.


### GetNegativeCriteria

`func (o *CreateGrowthPlay) GetNegativeCriteria() []string`

GetNegativeCriteria returns the NegativeCriteria field if non-nil, zero value otherwise.

### GetNegativeCriteriaOk

`func (o *CreateGrowthPlay) GetNegativeCriteriaOk() (*[]string, bool)`

GetNegativeCriteriaOk returns a tuple with the NegativeCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativeCriteria

`func (o *CreateGrowthPlay) SetNegativeCriteria(v []string)`

SetNegativeCriteria sets NegativeCriteria field to given value.

### HasNegativeCriteria

`func (o *CreateGrowthPlay) HasNegativeCriteria() bool`

HasNegativeCriteria returns a boolean if a field has been set.

### GetPositiveCriteria

`func (o *CreateGrowthPlay) GetPositiveCriteria() []string`

GetPositiveCriteria returns the PositiveCriteria field if non-nil, zero value otherwise.

### GetPositiveCriteriaOk

`func (o *CreateGrowthPlay) GetPositiveCriteriaOk() (*[]string, bool)`

GetPositiveCriteriaOk returns a tuple with the PositiveCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveCriteria

`func (o *CreateGrowthPlay) SetPositiveCriteria(v []string)`

SetPositiveCriteria sets PositiveCriteria field to given value.

### HasPositiveCriteria

`func (o *CreateGrowthPlay) HasPositiveCriteria() bool`

HasPositiveCriteria returns a boolean if a field has been set.

### GetReviewFirstN

`func (o *CreateGrowthPlay) GetReviewFirstN() int32`

GetReviewFirstN returns the ReviewFirstN field if non-nil, zero value otherwise.

### GetReviewFirstNOk

`func (o *CreateGrowthPlay) GetReviewFirstNOk() (*int32, bool)`

GetReviewFirstNOk returns a tuple with the ReviewFirstN field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewFirstN

`func (o *CreateGrowthPlay) SetReviewFirstN(v int32)`

SetReviewFirstN sets ReviewFirstN field to given value.

### HasReviewFirstN

`func (o *CreateGrowthPlay) HasReviewFirstN() bool`

HasReviewFirstN returns a boolean if a field has been set.

### GetSendingSchedule

`func (o *CreateGrowthPlay) GetSendingSchedule() CreateGrowthPlaySendingSchedule`

GetSendingSchedule returns the SendingSchedule field if non-nil, zero value otherwise.

### GetSendingScheduleOk

`func (o *CreateGrowthPlay) GetSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetSendingScheduleOk returns a tuple with the SendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingSchedule

`func (o *CreateGrowthPlay) SetSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetSendingSchedule sets SendingSchedule field to given value.

### HasSendingSchedule

`func (o *CreateGrowthPlay) HasSendingSchedule() bool`

HasSendingSchedule returns a boolean if a field has been set.

### SetSendingScheduleNil

`func (o *CreateGrowthPlay) SetSendingScheduleNil(b bool)`

 SetSendingScheduleNil sets the value for SendingSchedule to be an explicit nil

### UnsetSendingSchedule
`func (o *CreateGrowthPlay) UnsetSendingSchedule()`

UnsetSendingSchedule ensures that no value is present for SendingSchedule, not even an explicit nil
### GetSequence

`func (o *CreateGrowthPlay) GetSequence() CreateGrowthPlaySequence`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *CreateGrowthPlay) GetSequenceOk() (*CreateGrowthPlaySequence, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *CreateGrowthPlay) SetSequence(v CreateGrowthPlaySequence)`

SetSequence sets Sequence field to given value.

### HasSequence

`func (o *CreateGrowthPlay) HasSequence() bool`

HasSequence returns a boolean if a field has been set.

### SetSequenceNil

`func (o *CreateGrowthPlay) SetSequenceNil(b bool)`

 SetSequenceNil sets the value for Sequence to be an explicit nil

### UnsetSequence
`func (o *CreateGrowthPlay) UnsetSequence()`

UnsetSequence ensures that no value is present for Sequence, not even an explicit nil
### GetStatus

`func (o *CreateGrowthPlay) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateGrowthPlay) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateGrowthPlay) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateGrowthPlay) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetWho

`func (o *CreateGrowthPlay) GetWho() CreateGrowthPlayWho`

GetWho returns the Who field if non-nil, zero value otherwise.

### GetWhoOk

`func (o *CreateGrowthPlay) GetWhoOk() (*CreateGrowthPlayWho, bool)`

GetWhoOk returns a tuple with the Who field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWho

`func (o *CreateGrowthPlay) SetWho(v CreateGrowthPlayWho)`

SetWho sets Who field to given value.


### GetWhyNow

`func (o *CreateGrowthPlay) GetWhyNow() CreateGrowthPlayWhyNow`

GetWhyNow returns the WhyNow field if non-nil, zero value otherwise.

### GetWhyNowOk

`func (o *CreateGrowthPlay) GetWhyNowOk() (*CreateGrowthPlayWhyNow, bool)`

GetWhyNowOk returns a tuple with the WhyNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhyNow

`func (o *CreateGrowthPlay) SetWhyNow(v CreateGrowthPlayWhyNow)`

SetWhyNow sets WhyNow field to given value.

### HasWhyNow

`func (o *CreateGrowthPlay) HasWhyNow() bool`

HasWhyNow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


