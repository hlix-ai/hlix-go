# UpdateGrowthPlay

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Angle** | Pointer to **string** |  | [optional] 
**AutoSendReplies** | Pointer to **bool** |  | [optional] 
**BudgetPinned** | Pointer to **bool** |  | [optional] 
**DailyBudgetMicros** | Pointer to **int64** |  | [optional] 
**ExampleClients** | Pointer to **[]string** |  | [optional] 
**ExcludeDe** | Pointer to **bool** |  | [optional] 
**ExcludeEu** | Pointer to **bool** |  | [optional] 
**FirstEmail** | Pointer to [**CreateGrowthPlayFirstEmail**](CreateGrowthPlayFirstEmail.md) |  | [optional] 
**GdprAcknowledged** | Pointer to **bool** |  | [optional] 
**Keywords** | Pointer to **[]string** |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NegativeCriteria** | Pointer to **[]string** |  | [optional] 
**PositiveCriteria** | Pointer to **[]string** |  | [optional] 
**ReviewFirstN** | Pointer to **int32** |  | [optional] 
**SendingSchedule** | Pointer to [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  | [optional] 
**Sequence** | Pointer to [**NullableCreateGrowthPlaySequence**](CreateGrowthPlaySequence.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Who** | Pointer to [**CreateGrowthPlayWho**](CreateGrowthPlayWho.md) |  | [optional] 
**WhyNow** | Pointer to [**CreateGrowthPlayWhyNow**](CreateGrowthPlayWhyNow.md) |  | [optional] 

## Methods

### NewUpdateGrowthPlay

`func NewUpdateGrowthPlay() *UpdateGrowthPlay`

NewUpdateGrowthPlay instantiates a new UpdateGrowthPlay object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateGrowthPlayWithDefaults

`func NewUpdateGrowthPlayWithDefaults() *UpdateGrowthPlay`

NewUpdateGrowthPlayWithDefaults instantiates a new UpdateGrowthPlay object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAngle

`func (o *UpdateGrowthPlay) GetAngle() string`

GetAngle returns the Angle field if non-nil, zero value otherwise.

### GetAngleOk

`func (o *UpdateGrowthPlay) GetAngleOk() (*string, bool)`

GetAngleOk returns a tuple with the Angle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAngle

`func (o *UpdateGrowthPlay) SetAngle(v string)`

SetAngle sets Angle field to given value.

### HasAngle

`func (o *UpdateGrowthPlay) HasAngle() bool`

HasAngle returns a boolean if a field has been set.

### GetAutoSendReplies

`func (o *UpdateGrowthPlay) GetAutoSendReplies() bool`

GetAutoSendReplies returns the AutoSendReplies field if non-nil, zero value otherwise.

### GetAutoSendRepliesOk

`func (o *UpdateGrowthPlay) GetAutoSendRepliesOk() (*bool, bool)`

GetAutoSendRepliesOk returns a tuple with the AutoSendReplies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSendReplies

`func (o *UpdateGrowthPlay) SetAutoSendReplies(v bool)`

SetAutoSendReplies sets AutoSendReplies field to given value.

### HasAutoSendReplies

`func (o *UpdateGrowthPlay) HasAutoSendReplies() bool`

HasAutoSendReplies returns a boolean if a field has been set.

### GetBudgetPinned

`func (o *UpdateGrowthPlay) GetBudgetPinned() bool`

GetBudgetPinned returns the BudgetPinned field if non-nil, zero value otherwise.

### GetBudgetPinnedOk

`func (o *UpdateGrowthPlay) GetBudgetPinnedOk() (*bool, bool)`

GetBudgetPinnedOk returns a tuple with the BudgetPinned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetPinned

`func (o *UpdateGrowthPlay) SetBudgetPinned(v bool)`

SetBudgetPinned sets BudgetPinned field to given value.

### HasBudgetPinned

`func (o *UpdateGrowthPlay) HasBudgetPinned() bool`

HasBudgetPinned returns a boolean if a field has been set.

### GetDailyBudgetMicros

`func (o *UpdateGrowthPlay) GetDailyBudgetMicros() int64`

GetDailyBudgetMicros returns the DailyBudgetMicros field if non-nil, zero value otherwise.

### GetDailyBudgetMicrosOk

`func (o *UpdateGrowthPlay) GetDailyBudgetMicrosOk() (*int64, bool)`

GetDailyBudgetMicrosOk returns a tuple with the DailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyBudgetMicros

`func (o *UpdateGrowthPlay) SetDailyBudgetMicros(v int64)`

SetDailyBudgetMicros sets DailyBudgetMicros field to given value.

### HasDailyBudgetMicros

`func (o *UpdateGrowthPlay) HasDailyBudgetMicros() bool`

HasDailyBudgetMicros returns a boolean if a field has been set.

### GetExampleClients

`func (o *UpdateGrowthPlay) GetExampleClients() []string`

GetExampleClients returns the ExampleClients field if non-nil, zero value otherwise.

### GetExampleClientsOk

`func (o *UpdateGrowthPlay) GetExampleClientsOk() (*[]string, bool)`

GetExampleClientsOk returns a tuple with the ExampleClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExampleClients

`func (o *UpdateGrowthPlay) SetExampleClients(v []string)`

SetExampleClients sets ExampleClients field to given value.

### HasExampleClients

`func (o *UpdateGrowthPlay) HasExampleClients() bool`

HasExampleClients returns a boolean if a field has been set.

### GetExcludeDe

`func (o *UpdateGrowthPlay) GetExcludeDe() bool`

GetExcludeDe returns the ExcludeDe field if non-nil, zero value otherwise.

### GetExcludeDeOk

`func (o *UpdateGrowthPlay) GetExcludeDeOk() (*bool, bool)`

GetExcludeDeOk returns a tuple with the ExcludeDe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeDe

`func (o *UpdateGrowthPlay) SetExcludeDe(v bool)`

SetExcludeDe sets ExcludeDe field to given value.

### HasExcludeDe

`func (o *UpdateGrowthPlay) HasExcludeDe() bool`

HasExcludeDe returns a boolean if a field has been set.

### GetExcludeEu

`func (o *UpdateGrowthPlay) GetExcludeEu() bool`

GetExcludeEu returns the ExcludeEu field if non-nil, zero value otherwise.

### GetExcludeEuOk

`func (o *UpdateGrowthPlay) GetExcludeEuOk() (*bool, bool)`

GetExcludeEuOk returns a tuple with the ExcludeEu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeEu

`func (o *UpdateGrowthPlay) SetExcludeEu(v bool)`

SetExcludeEu sets ExcludeEu field to given value.

### HasExcludeEu

`func (o *UpdateGrowthPlay) HasExcludeEu() bool`

HasExcludeEu returns a boolean if a field has been set.

### GetFirstEmail

`func (o *UpdateGrowthPlay) GetFirstEmail() CreateGrowthPlayFirstEmail`

GetFirstEmail returns the FirstEmail field if non-nil, zero value otherwise.

### GetFirstEmailOk

`func (o *UpdateGrowthPlay) GetFirstEmailOk() (*CreateGrowthPlayFirstEmail, bool)`

GetFirstEmailOk returns a tuple with the FirstEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstEmail

`func (o *UpdateGrowthPlay) SetFirstEmail(v CreateGrowthPlayFirstEmail)`

SetFirstEmail sets FirstEmail field to given value.

### HasFirstEmail

`func (o *UpdateGrowthPlay) HasFirstEmail() bool`

HasFirstEmail returns a boolean if a field has been set.

### GetGdprAcknowledged

`func (o *UpdateGrowthPlay) GetGdprAcknowledged() bool`

GetGdprAcknowledged returns the GdprAcknowledged field if non-nil, zero value otherwise.

### GetGdprAcknowledgedOk

`func (o *UpdateGrowthPlay) GetGdprAcknowledgedOk() (*bool, bool)`

GetGdprAcknowledgedOk returns a tuple with the GdprAcknowledged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdprAcknowledged

`func (o *UpdateGrowthPlay) SetGdprAcknowledged(v bool)`

SetGdprAcknowledged sets GdprAcknowledged field to given value.

### HasGdprAcknowledged

`func (o *UpdateGrowthPlay) HasGdprAcknowledged() bool`

HasGdprAcknowledged returns a boolean if a field has been set.

### GetKeywords

`func (o *UpdateGrowthPlay) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *UpdateGrowthPlay) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *UpdateGrowthPlay) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *UpdateGrowthPlay) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetLanguage

`func (o *UpdateGrowthPlay) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *UpdateGrowthPlay) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *UpdateGrowthPlay) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *UpdateGrowthPlay) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetName

`func (o *UpdateGrowthPlay) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateGrowthPlay) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateGrowthPlay) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateGrowthPlay) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNegativeCriteria

`func (o *UpdateGrowthPlay) GetNegativeCriteria() []string`

GetNegativeCriteria returns the NegativeCriteria field if non-nil, zero value otherwise.

### GetNegativeCriteriaOk

`func (o *UpdateGrowthPlay) GetNegativeCriteriaOk() (*[]string, bool)`

GetNegativeCriteriaOk returns a tuple with the NegativeCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativeCriteria

`func (o *UpdateGrowthPlay) SetNegativeCriteria(v []string)`

SetNegativeCriteria sets NegativeCriteria field to given value.

### HasNegativeCriteria

`func (o *UpdateGrowthPlay) HasNegativeCriteria() bool`

HasNegativeCriteria returns a boolean if a field has been set.

### GetPositiveCriteria

`func (o *UpdateGrowthPlay) GetPositiveCriteria() []string`

GetPositiveCriteria returns the PositiveCriteria field if non-nil, zero value otherwise.

### GetPositiveCriteriaOk

`func (o *UpdateGrowthPlay) GetPositiveCriteriaOk() (*[]string, bool)`

GetPositiveCriteriaOk returns a tuple with the PositiveCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveCriteria

`func (o *UpdateGrowthPlay) SetPositiveCriteria(v []string)`

SetPositiveCriteria sets PositiveCriteria field to given value.

### HasPositiveCriteria

`func (o *UpdateGrowthPlay) HasPositiveCriteria() bool`

HasPositiveCriteria returns a boolean if a field has been set.

### GetReviewFirstN

`func (o *UpdateGrowthPlay) GetReviewFirstN() int32`

GetReviewFirstN returns the ReviewFirstN field if non-nil, zero value otherwise.

### GetReviewFirstNOk

`func (o *UpdateGrowthPlay) GetReviewFirstNOk() (*int32, bool)`

GetReviewFirstNOk returns a tuple with the ReviewFirstN field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewFirstN

`func (o *UpdateGrowthPlay) SetReviewFirstN(v int32)`

SetReviewFirstN sets ReviewFirstN field to given value.

### HasReviewFirstN

`func (o *UpdateGrowthPlay) HasReviewFirstN() bool`

HasReviewFirstN returns a boolean if a field has been set.

### GetSendingSchedule

`func (o *UpdateGrowthPlay) GetSendingSchedule() CreateGrowthPlaySendingSchedule`

GetSendingSchedule returns the SendingSchedule field if non-nil, zero value otherwise.

### GetSendingScheduleOk

`func (o *UpdateGrowthPlay) GetSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetSendingScheduleOk returns a tuple with the SendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingSchedule

`func (o *UpdateGrowthPlay) SetSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetSendingSchedule sets SendingSchedule field to given value.

### HasSendingSchedule

`func (o *UpdateGrowthPlay) HasSendingSchedule() bool`

HasSendingSchedule returns a boolean if a field has been set.

### SetSendingScheduleNil

`func (o *UpdateGrowthPlay) SetSendingScheduleNil(b bool)`

 SetSendingScheduleNil sets the value for SendingSchedule to be an explicit nil

### UnsetSendingSchedule
`func (o *UpdateGrowthPlay) UnsetSendingSchedule()`

UnsetSendingSchedule ensures that no value is present for SendingSchedule, not even an explicit nil
### GetSequence

`func (o *UpdateGrowthPlay) GetSequence() CreateGrowthPlaySequence`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *UpdateGrowthPlay) GetSequenceOk() (*CreateGrowthPlaySequence, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *UpdateGrowthPlay) SetSequence(v CreateGrowthPlaySequence)`

SetSequence sets Sequence field to given value.

### HasSequence

`func (o *UpdateGrowthPlay) HasSequence() bool`

HasSequence returns a boolean if a field has been set.

### SetSequenceNil

`func (o *UpdateGrowthPlay) SetSequenceNil(b bool)`

 SetSequenceNil sets the value for Sequence to be an explicit nil

### UnsetSequence
`func (o *UpdateGrowthPlay) UnsetSequence()`

UnsetSequence ensures that no value is present for Sequence, not even an explicit nil
### GetStatus

`func (o *UpdateGrowthPlay) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateGrowthPlay) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateGrowthPlay) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateGrowthPlay) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetWho

`func (o *UpdateGrowthPlay) GetWho() CreateGrowthPlayWho`

GetWho returns the Who field if non-nil, zero value otherwise.

### GetWhoOk

`func (o *UpdateGrowthPlay) GetWhoOk() (*CreateGrowthPlayWho, bool)`

GetWhoOk returns a tuple with the Who field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWho

`func (o *UpdateGrowthPlay) SetWho(v CreateGrowthPlayWho)`

SetWho sets Who field to given value.

### HasWho

`func (o *UpdateGrowthPlay) HasWho() bool`

HasWho returns a boolean if a field has been set.

### GetWhyNow

`func (o *UpdateGrowthPlay) GetWhyNow() CreateGrowthPlayWhyNow`

GetWhyNow returns the WhyNow field if non-nil, zero value otherwise.

### GetWhyNowOk

`func (o *UpdateGrowthPlay) GetWhyNowOk() (*CreateGrowthPlayWhyNow, bool)`

GetWhyNowOk returns a tuple with the WhyNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhyNow

`func (o *UpdateGrowthPlay) SetWhyNow(v CreateGrowthPlayWhyNow)`

SetWhyNow sets WhyNow field to given value.

### HasWhyNow

`func (o *UpdateGrowthPlay) HasWhyNow() bool`

HasWhyNow returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


