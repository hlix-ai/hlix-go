# GrowthPlay

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Angle** | **NullableString** |  |
**AutoSendReplies** | **bool** |  |
**BudgetPinned** | **bool** |  |
**Confidence** | **NullableFloat32** |  |
**CreatedAt** | **string** |  |
**Currency** | **string** |  |
**DailyBudgetMicros** | **int64** |  |
**ExampleClients** | **[]string** |  |
**ExcludeDe** | **bool** |  |
**ExcludeEu** | **bool** |  |
**FirstEmail** | [**NullableGrowthPlayFirstEmail**](GrowthPlayFirstEmail.md) |  |
**FitLabel** | **NullableString** |  |
**GdprAckAt** | **NullableString** |  |
**GdprAckByUserId** | **NullableString** |  |
**Id** | **string** |  |
**Keywords** | **[]string** |  |
**Language** | **string** |  |
**LastLeadPassAt** | **NullableString** |  |
**Name** | **string** |  |
**NegativeCriteria** | **[]string** |  |
**OrganizationId** | **string** |  |
**PositiveCriteria** | **[]string** |  |
**ProjectId** | **string** |  |
**ReviewFirstN** | **int32** |  |
**SendingSchedule** | [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  |
**Sequence** | [**NullableCreateGrowthPlaySequence**](CreateGrowthPlaySequence.md) |  |
**Status** | **string** |  |
**UpdatedAt** | **string** |  |
**Who** | **map[string]interface{}** |  |
**WhyNow** | [**NullableGrowthPlayWhyNow**](GrowthPlayWhyNow.md) |  |

## Methods

### NewGrowthPlay

`func NewGrowthPlay(angle NullableString, autoSendReplies bool, budgetPinned bool, confidence NullableFloat32, createdAt string, currency string, dailyBudgetMicros int64, exampleClients []string, excludeDe bool, excludeEu bool, firstEmail NullableGrowthPlayFirstEmail, fitLabel NullableString, gdprAckAt NullableString, gdprAckByUserId NullableString, id string, keywords []string, language string, lastLeadPassAt NullableString, name string, negativeCriteria []string, organizationId string, positiveCriteria []string, projectId string, reviewFirstN int32, sendingSchedule NullableCreateGrowthPlaySendingSchedule, sequence NullableCreateGrowthPlaySequence, status string, updatedAt string, who map[string]interface{}, whyNow NullableGrowthPlayWhyNow, ) *GrowthPlay`

NewGrowthPlay instantiates a new GrowthPlay object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthPlayWithDefaults

`func NewGrowthPlayWithDefaults() *GrowthPlay`

NewGrowthPlayWithDefaults instantiates a new GrowthPlay object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAngle

`func (o *GrowthPlay) GetAngle() string`

GetAngle returns the Angle field if non-nil, zero value otherwise.

### GetAngleOk

`func (o *GrowthPlay) GetAngleOk() (*string, bool)`

GetAngleOk returns a tuple with the Angle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAngle

`func (o *GrowthPlay) SetAngle(v string)`

SetAngle sets Angle field to given value.


### SetAngleNil

`func (o *GrowthPlay) SetAngleNil(b bool)`

 SetAngleNil sets the value for Angle to be an explicit nil

### UnsetAngle
`func (o *GrowthPlay) UnsetAngle()`

UnsetAngle ensures that no value is present for Angle, not even an explicit nil
### GetAutoSendReplies

`func (o *GrowthPlay) GetAutoSendReplies() bool`

GetAutoSendReplies returns the AutoSendReplies field if non-nil, zero value otherwise.

### GetAutoSendRepliesOk

`func (o *GrowthPlay) GetAutoSendRepliesOk() (*bool, bool)`

GetAutoSendRepliesOk returns a tuple with the AutoSendReplies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSendReplies

`func (o *GrowthPlay) SetAutoSendReplies(v bool)`

SetAutoSendReplies sets AutoSendReplies field to given value.


### GetBudgetPinned

`func (o *GrowthPlay) GetBudgetPinned() bool`

GetBudgetPinned returns the BudgetPinned field if non-nil, zero value otherwise.

### GetBudgetPinnedOk

`func (o *GrowthPlay) GetBudgetPinnedOk() (*bool, bool)`

GetBudgetPinnedOk returns a tuple with the BudgetPinned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetPinned

`func (o *GrowthPlay) SetBudgetPinned(v bool)`

SetBudgetPinned sets BudgetPinned field to given value.


### GetConfidence

`func (o *GrowthPlay) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *GrowthPlay) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *GrowthPlay) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.


### SetConfidenceNil

`func (o *GrowthPlay) SetConfidenceNil(b bool)`

 SetConfidenceNil sets the value for Confidence to be an explicit nil

### UnsetConfidence
`func (o *GrowthPlay) UnsetConfidence()`

UnsetConfidence ensures that no value is present for Confidence, not even an explicit nil
### GetCreatedAt

`func (o *GrowthPlay) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthPlay) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthPlay) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrency

`func (o *GrowthPlay) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GrowthPlay) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GrowthPlay) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDailyBudgetMicros

`func (o *GrowthPlay) GetDailyBudgetMicros() int64`

GetDailyBudgetMicros returns the DailyBudgetMicros field if non-nil, zero value otherwise.

### GetDailyBudgetMicrosOk

`func (o *GrowthPlay) GetDailyBudgetMicrosOk() (*int64, bool)`

GetDailyBudgetMicrosOk returns a tuple with the DailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyBudgetMicros

`func (o *GrowthPlay) SetDailyBudgetMicros(v int64)`

SetDailyBudgetMicros sets DailyBudgetMicros field to given value.


### GetExampleClients

`func (o *GrowthPlay) GetExampleClients() []string`

GetExampleClients returns the ExampleClients field if non-nil, zero value otherwise.

### GetExampleClientsOk

`func (o *GrowthPlay) GetExampleClientsOk() (*[]string, bool)`

GetExampleClientsOk returns a tuple with the ExampleClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExampleClients

`func (o *GrowthPlay) SetExampleClients(v []string)`

SetExampleClients sets ExampleClients field to given value.


### GetExcludeDe

`func (o *GrowthPlay) GetExcludeDe() bool`

GetExcludeDe returns the ExcludeDe field if non-nil, zero value otherwise.

### GetExcludeDeOk

`func (o *GrowthPlay) GetExcludeDeOk() (*bool, bool)`

GetExcludeDeOk returns a tuple with the ExcludeDe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeDe

`func (o *GrowthPlay) SetExcludeDe(v bool)`

SetExcludeDe sets ExcludeDe field to given value.


### GetExcludeEu

`func (o *GrowthPlay) GetExcludeEu() bool`

GetExcludeEu returns the ExcludeEu field if non-nil, zero value otherwise.

### GetExcludeEuOk

`func (o *GrowthPlay) GetExcludeEuOk() (*bool, bool)`

GetExcludeEuOk returns a tuple with the ExcludeEu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeEu

`func (o *GrowthPlay) SetExcludeEu(v bool)`

SetExcludeEu sets ExcludeEu field to given value.


### GetFirstEmail

`func (o *GrowthPlay) GetFirstEmail() GrowthPlayFirstEmail`

GetFirstEmail returns the FirstEmail field if non-nil, zero value otherwise.

### GetFirstEmailOk

`func (o *GrowthPlay) GetFirstEmailOk() (*GrowthPlayFirstEmail, bool)`

GetFirstEmailOk returns a tuple with the FirstEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstEmail

`func (o *GrowthPlay) SetFirstEmail(v GrowthPlayFirstEmail)`

SetFirstEmail sets FirstEmail field to given value.


### SetFirstEmailNil

`func (o *GrowthPlay) SetFirstEmailNil(b bool)`

 SetFirstEmailNil sets the value for FirstEmail to be an explicit nil

### UnsetFirstEmail
`func (o *GrowthPlay) UnsetFirstEmail()`

UnsetFirstEmail ensures that no value is present for FirstEmail, not even an explicit nil
### GetFitLabel

`func (o *GrowthPlay) GetFitLabel() string`

GetFitLabel returns the FitLabel field if non-nil, zero value otherwise.

### GetFitLabelOk

`func (o *GrowthPlay) GetFitLabelOk() (*string, bool)`

GetFitLabelOk returns a tuple with the FitLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFitLabel

`func (o *GrowthPlay) SetFitLabel(v string)`

SetFitLabel sets FitLabel field to given value.


### SetFitLabelNil

`func (o *GrowthPlay) SetFitLabelNil(b bool)`

 SetFitLabelNil sets the value for FitLabel to be an explicit nil

### UnsetFitLabel
`func (o *GrowthPlay) UnsetFitLabel()`

UnsetFitLabel ensures that no value is present for FitLabel, not even an explicit nil
### GetGdprAckAt

`func (o *GrowthPlay) GetGdprAckAt() string`

GetGdprAckAt returns the GdprAckAt field if non-nil, zero value otherwise.

### GetGdprAckAtOk

`func (o *GrowthPlay) GetGdprAckAtOk() (*string, bool)`

GetGdprAckAtOk returns a tuple with the GdprAckAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdprAckAt

`func (o *GrowthPlay) SetGdprAckAt(v string)`

SetGdprAckAt sets GdprAckAt field to given value.


### SetGdprAckAtNil

`func (o *GrowthPlay) SetGdprAckAtNil(b bool)`

 SetGdprAckAtNil sets the value for GdprAckAt to be an explicit nil

### UnsetGdprAckAt
`func (o *GrowthPlay) UnsetGdprAckAt()`

UnsetGdprAckAt ensures that no value is present for GdprAckAt, not even an explicit nil
### GetGdprAckByUserId

`func (o *GrowthPlay) GetGdprAckByUserId() string`

GetGdprAckByUserId returns the GdprAckByUserId field if non-nil, zero value otherwise.

### GetGdprAckByUserIdOk

`func (o *GrowthPlay) GetGdprAckByUserIdOk() (*string, bool)`

GetGdprAckByUserIdOk returns a tuple with the GdprAckByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdprAckByUserId

`func (o *GrowthPlay) SetGdprAckByUserId(v string)`

SetGdprAckByUserId sets GdprAckByUserId field to given value.


### SetGdprAckByUserIdNil

`func (o *GrowthPlay) SetGdprAckByUserIdNil(b bool)`

 SetGdprAckByUserIdNil sets the value for GdprAckByUserId to be an explicit nil

### UnsetGdprAckByUserId
`func (o *GrowthPlay) UnsetGdprAckByUserId()`

UnsetGdprAckByUserId ensures that no value is present for GdprAckByUserId, not even an explicit nil
### GetId

`func (o *GrowthPlay) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthPlay) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthPlay) SetId(v string)`

SetId sets Id field to given value.


### GetKeywords

`func (o *GrowthPlay) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *GrowthPlay) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *GrowthPlay) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetLanguage

`func (o *GrowthPlay) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *GrowthPlay) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *GrowthPlay) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetLastLeadPassAt

`func (o *GrowthPlay) GetLastLeadPassAt() string`

GetLastLeadPassAt returns the LastLeadPassAt field if non-nil, zero value otherwise.

### GetLastLeadPassAtOk

`func (o *GrowthPlay) GetLastLeadPassAtOk() (*string, bool)`

GetLastLeadPassAtOk returns a tuple with the LastLeadPassAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLeadPassAt

`func (o *GrowthPlay) SetLastLeadPassAt(v string)`

SetLastLeadPassAt sets LastLeadPassAt field to given value.


### SetLastLeadPassAtNil

`func (o *GrowthPlay) SetLastLeadPassAtNil(b bool)`

 SetLastLeadPassAtNil sets the value for LastLeadPassAt to be an explicit nil

### UnsetLastLeadPassAt
`func (o *GrowthPlay) UnsetLastLeadPassAt()`

UnsetLastLeadPassAt ensures that no value is present for LastLeadPassAt, not even an explicit nil
### GetName

`func (o *GrowthPlay) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GrowthPlay) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GrowthPlay) SetName(v string)`

SetName sets Name field to given value.


### GetNegativeCriteria

`func (o *GrowthPlay) GetNegativeCriteria() []string`

GetNegativeCriteria returns the NegativeCriteria field if non-nil, zero value otherwise.

### GetNegativeCriteriaOk

`func (o *GrowthPlay) GetNegativeCriteriaOk() (*[]string, bool)`

GetNegativeCriteriaOk returns a tuple with the NegativeCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativeCriteria

`func (o *GrowthPlay) SetNegativeCriteria(v []string)`

SetNegativeCriteria sets NegativeCriteria field to given value.


### GetOrganizationId

`func (o *GrowthPlay) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *GrowthPlay) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *GrowthPlay) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPositiveCriteria

`func (o *GrowthPlay) GetPositiveCriteria() []string`

GetPositiveCriteria returns the PositiveCriteria field if non-nil, zero value otherwise.

### GetPositiveCriteriaOk

`func (o *GrowthPlay) GetPositiveCriteriaOk() (*[]string, bool)`

GetPositiveCriteriaOk returns a tuple with the PositiveCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveCriteria

`func (o *GrowthPlay) SetPositiveCriteria(v []string)`

SetPositiveCriteria sets PositiveCriteria field to given value.


### GetProjectId

`func (o *GrowthPlay) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GrowthPlay) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GrowthPlay) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetReviewFirstN

`func (o *GrowthPlay) GetReviewFirstN() int32`

GetReviewFirstN returns the ReviewFirstN field if non-nil, zero value otherwise.

### GetReviewFirstNOk

`func (o *GrowthPlay) GetReviewFirstNOk() (*int32, bool)`

GetReviewFirstNOk returns a tuple with the ReviewFirstN field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewFirstN

`func (o *GrowthPlay) SetReviewFirstN(v int32)`

SetReviewFirstN sets ReviewFirstN field to given value.


### GetSendingSchedule

`func (o *GrowthPlay) GetSendingSchedule() CreateGrowthPlaySendingSchedule`

GetSendingSchedule returns the SendingSchedule field if non-nil, zero value otherwise.

### GetSendingScheduleOk

`func (o *GrowthPlay) GetSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetSendingScheduleOk returns a tuple with the SendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingSchedule

`func (o *GrowthPlay) SetSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetSendingSchedule sets SendingSchedule field to given value.


### SetSendingScheduleNil

`func (o *GrowthPlay) SetSendingScheduleNil(b bool)`

 SetSendingScheduleNil sets the value for SendingSchedule to be an explicit nil

### UnsetSendingSchedule
`func (o *GrowthPlay) UnsetSendingSchedule()`

UnsetSendingSchedule ensures that no value is present for SendingSchedule, not even an explicit nil
### GetSequence

`func (o *GrowthPlay) GetSequence() CreateGrowthPlaySequence`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *GrowthPlay) GetSequenceOk() (*CreateGrowthPlaySequence, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *GrowthPlay) SetSequence(v CreateGrowthPlaySequence)`

SetSequence sets Sequence field to given value.


### SetSequenceNil

`func (o *GrowthPlay) SetSequenceNil(b bool)`

 SetSequenceNil sets the value for Sequence to be an explicit nil

### UnsetSequence
`func (o *GrowthPlay) UnsetSequence()`

UnsetSequence ensures that no value is present for Sequence, not even an explicit nil
### GetStatus

`func (o *GrowthPlay) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthPlay) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthPlay) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *GrowthPlay) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GrowthPlay) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GrowthPlay) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetWho

`func (o *GrowthPlay) GetWho() map[string]interface{}`

GetWho returns the Who field if non-nil, zero value otherwise.

### GetWhoOk

`func (o *GrowthPlay) GetWhoOk() (*map[string]interface{}, bool)`

GetWhoOk returns a tuple with the Who field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWho

`func (o *GrowthPlay) SetWho(v map[string]interface{})`

SetWho sets Who field to given value.


### GetWhyNow

`func (o *GrowthPlay) GetWhyNow() GrowthPlayWhyNow`

GetWhyNow returns the WhyNow field if non-nil, zero value otherwise.

### GetWhyNowOk

`func (o *GrowthPlay) GetWhyNowOk() (*GrowthPlayWhyNow, bool)`

GetWhyNowOk returns a tuple with the WhyNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhyNow

`func (o *GrowthPlay) SetWhyNow(v GrowthPlayWhyNow)`

SetWhyNow sets WhyNow field to given value.


### SetWhyNowNil

`func (o *GrowthPlay) SetWhyNowNil(b bool)`

 SetWhyNowNil sets the value for WhyNow to be an explicit nil

### UnsetWhyNow
`func (o *GrowthPlay) UnsetWhyNow()`

UnsetWhyNow ensures that no value is present for WhyNow, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


