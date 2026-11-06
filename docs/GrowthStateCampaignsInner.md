# GrowthStateCampaignsInner

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

### NewGrowthStateCampaignsInner

`func NewGrowthStateCampaignsInner(angle NullableString, autoSendReplies bool, budgetPinned bool, confidence NullableFloat32, createdAt string, currency string, dailyBudgetMicros int64, exampleClients []string, excludeDe bool, excludeEu bool, firstEmail NullableGrowthPlayFirstEmail, fitLabel NullableString, gdprAckAt NullableString, gdprAckByUserId NullableString, id string, keywords []string, language string, lastLeadPassAt NullableString, name string, negativeCriteria []string, organizationId string, positiveCriteria []string, projectId string, reviewFirstN int32, sendingSchedule NullableCreateGrowthPlaySendingSchedule, sequence NullableCreateGrowthPlaySequence, status string, updatedAt string, who map[string]interface{}, whyNow NullableGrowthPlayWhyNow, ) *GrowthStateCampaignsInner`

NewGrowthStateCampaignsInner instantiates a new GrowthStateCampaignsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthStateCampaignsInnerWithDefaults

`func NewGrowthStateCampaignsInnerWithDefaults() *GrowthStateCampaignsInner`

NewGrowthStateCampaignsInnerWithDefaults instantiates a new GrowthStateCampaignsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAngle

`func (o *GrowthStateCampaignsInner) GetAngle() string`

GetAngle returns the Angle field if non-nil, zero value otherwise.

### GetAngleOk

`func (o *GrowthStateCampaignsInner) GetAngleOk() (*string, bool)`

GetAngleOk returns a tuple with the Angle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAngle

`func (o *GrowthStateCampaignsInner) SetAngle(v string)`

SetAngle sets Angle field to given value.


### SetAngleNil

`func (o *GrowthStateCampaignsInner) SetAngleNil(b bool)`

 SetAngleNil sets the value for Angle to be an explicit nil

### UnsetAngle
`func (o *GrowthStateCampaignsInner) UnsetAngle()`

UnsetAngle ensures that no value is present for Angle, not even an explicit nil
### GetAutoSendReplies

`func (o *GrowthStateCampaignsInner) GetAutoSendReplies() bool`

GetAutoSendReplies returns the AutoSendReplies field if non-nil, zero value otherwise.

### GetAutoSendRepliesOk

`func (o *GrowthStateCampaignsInner) GetAutoSendRepliesOk() (*bool, bool)`

GetAutoSendRepliesOk returns a tuple with the AutoSendReplies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoSendReplies

`func (o *GrowthStateCampaignsInner) SetAutoSendReplies(v bool)`

SetAutoSendReplies sets AutoSendReplies field to given value.


### GetBudgetPinned

`func (o *GrowthStateCampaignsInner) GetBudgetPinned() bool`

GetBudgetPinned returns the BudgetPinned field if non-nil, zero value otherwise.

### GetBudgetPinnedOk

`func (o *GrowthStateCampaignsInner) GetBudgetPinnedOk() (*bool, bool)`

GetBudgetPinnedOk returns a tuple with the BudgetPinned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudgetPinned

`func (o *GrowthStateCampaignsInner) SetBudgetPinned(v bool)`

SetBudgetPinned sets BudgetPinned field to given value.


### GetConfidence

`func (o *GrowthStateCampaignsInner) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *GrowthStateCampaignsInner) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *GrowthStateCampaignsInner) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.


### SetConfidenceNil

`func (o *GrowthStateCampaignsInner) SetConfidenceNil(b bool)`

 SetConfidenceNil sets the value for Confidence to be an explicit nil

### UnsetConfidence
`func (o *GrowthStateCampaignsInner) UnsetConfidence()`

UnsetConfidence ensures that no value is present for Confidence, not even an explicit nil
### GetCreatedAt

`func (o *GrowthStateCampaignsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthStateCampaignsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthStateCampaignsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrency

`func (o *GrowthStateCampaignsInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GrowthStateCampaignsInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GrowthStateCampaignsInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDailyBudgetMicros

`func (o *GrowthStateCampaignsInner) GetDailyBudgetMicros() int64`

GetDailyBudgetMicros returns the DailyBudgetMicros field if non-nil, zero value otherwise.

### GetDailyBudgetMicrosOk

`func (o *GrowthStateCampaignsInner) GetDailyBudgetMicrosOk() (*int64, bool)`

GetDailyBudgetMicrosOk returns a tuple with the DailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyBudgetMicros

`func (o *GrowthStateCampaignsInner) SetDailyBudgetMicros(v int64)`

SetDailyBudgetMicros sets DailyBudgetMicros field to given value.


### GetExampleClients

`func (o *GrowthStateCampaignsInner) GetExampleClients() []string`

GetExampleClients returns the ExampleClients field if non-nil, zero value otherwise.

### GetExampleClientsOk

`func (o *GrowthStateCampaignsInner) GetExampleClientsOk() (*[]string, bool)`

GetExampleClientsOk returns a tuple with the ExampleClients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExampleClients

`func (o *GrowthStateCampaignsInner) SetExampleClients(v []string)`

SetExampleClients sets ExampleClients field to given value.


### GetExcludeDe

`func (o *GrowthStateCampaignsInner) GetExcludeDe() bool`

GetExcludeDe returns the ExcludeDe field if non-nil, zero value otherwise.

### GetExcludeDeOk

`func (o *GrowthStateCampaignsInner) GetExcludeDeOk() (*bool, bool)`

GetExcludeDeOk returns a tuple with the ExcludeDe field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeDe

`func (o *GrowthStateCampaignsInner) SetExcludeDe(v bool)`

SetExcludeDe sets ExcludeDe field to given value.


### GetExcludeEu

`func (o *GrowthStateCampaignsInner) GetExcludeEu() bool`

GetExcludeEu returns the ExcludeEu field if non-nil, zero value otherwise.

### GetExcludeEuOk

`func (o *GrowthStateCampaignsInner) GetExcludeEuOk() (*bool, bool)`

GetExcludeEuOk returns a tuple with the ExcludeEu field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeEu

`func (o *GrowthStateCampaignsInner) SetExcludeEu(v bool)`

SetExcludeEu sets ExcludeEu field to given value.


### GetFirstEmail

`func (o *GrowthStateCampaignsInner) GetFirstEmail() GrowthPlayFirstEmail`

GetFirstEmail returns the FirstEmail field if non-nil, zero value otherwise.

### GetFirstEmailOk

`func (o *GrowthStateCampaignsInner) GetFirstEmailOk() (*GrowthPlayFirstEmail, bool)`

GetFirstEmailOk returns a tuple with the FirstEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstEmail

`func (o *GrowthStateCampaignsInner) SetFirstEmail(v GrowthPlayFirstEmail)`

SetFirstEmail sets FirstEmail field to given value.


### SetFirstEmailNil

`func (o *GrowthStateCampaignsInner) SetFirstEmailNil(b bool)`

 SetFirstEmailNil sets the value for FirstEmail to be an explicit nil

### UnsetFirstEmail
`func (o *GrowthStateCampaignsInner) UnsetFirstEmail()`

UnsetFirstEmail ensures that no value is present for FirstEmail, not even an explicit nil
### GetFitLabel

`func (o *GrowthStateCampaignsInner) GetFitLabel() string`

GetFitLabel returns the FitLabel field if non-nil, zero value otherwise.

### GetFitLabelOk

`func (o *GrowthStateCampaignsInner) GetFitLabelOk() (*string, bool)`

GetFitLabelOk returns a tuple with the FitLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFitLabel

`func (o *GrowthStateCampaignsInner) SetFitLabel(v string)`

SetFitLabel sets FitLabel field to given value.


### SetFitLabelNil

`func (o *GrowthStateCampaignsInner) SetFitLabelNil(b bool)`

 SetFitLabelNil sets the value for FitLabel to be an explicit nil

### UnsetFitLabel
`func (o *GrowthStateCampaignsInner) UnsetFitLabel()`

UnsetFitLabel ensures that no value is present for FitLabel, not even an explicit nil
### GetGdprAckAt

`func (o *GrowthStateCampaignsInner) GetGdprAckAt() string`

GetGdprAckAt returns the GdprAckAt field if non-nil, zero value otherwise.

### GetGdprAckAtOk

`func (o *GrowthStateCampaignsInner) GetGdprAckAtOk() (*string, bool)`

GetGdprAckAtOk returns a tuple with the GdprAckAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdprAckAt

`func (o *GrowthStateCampaignsInner) SetGdprAckAt(v string)`

SetGdprAckAt sets GdprAckAt field to given value.


### SetGdprAckAtNil

`func (o *GrowthStateCampaignsInner) SetGdprAckAtNil(b bool)`

 SetGdprAckAtNil sets the value for GdprAckAt to be an explicit nil

### UnsetGdprAckAt
`func (o *GrowthStateCampaignsInner) UnsetGdprAckAt()`

UnsetGdprAckAt ensures that no value is present for GdprAckAt, not even an explicit nil
### GetGdprAckByUserId

`func (o *GrowthStateCampaignsInner) GetGdprAckByUserId() string`

GetGdprAckByUserId returns the GdprAckByUserId field if non-nil, zero value otherwise.

### GetGdprAckByUserIdOk

`func (o *GrowthStateCampaignsInner) GetGdprAckByUserIdOk() (*string, bool)`

GetGdprAckByUserIdOk returns a tuple with the GdprAckByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGdprAckByUserId

`func (o *GrowthStateCampaignsInner) SetGdprAckByUserId(v string)`

SetGdprAckByUserId sets GdprAckByUserId field to given value.


### SetGdprAckByUserIdNil

`func (o *GrowthStateCampaignsInner) SetGdprAckByUserIdNil(b bool)`

 SetGdprAckByUserIdNil sets the value for GdprAckByUserId to be an explicit nil

### UnsetGdprAckByUserId
`func (o *GrowthStateCampaignsInner) UnsetGdprAckByUserId()`

UnsetGdprAckByUserId ensures that no value is present for GdprAckByUserId, not even an explicit nil
### GetId

`func (o *GrowthStateCampaignsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthStateCampaignsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthStateCampaignsInner) SetId(v string)`

SetId sets Id field to given value.


### GetKeywords

`func (o *GrowthStateCampaignsInner) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *GrowthStateCampaignsInner) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *GrowthStateCampaignsInner) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetLanguage

`func (o *GrowthStateCampaignsInner) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *GrowthStateCampaignsInner) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *GrowthStateCampaignsInner) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetLastLeadPassAt

`func (o *GrowthStateCampaignsInner) GetLastLeadPassAt() string`

GetLastLeadPassAt returns the LastLeadPassAt field if non-nil, zero value otherwise.

### GetLastLeadPassAtOk

`func (o *GrowthStateCampaignsInner) GetLastLeadPassAtOk() (*string, bool)`

GetLastLeadPassAtOk returns a tuple with the LastLeadPassAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLeadPassAt

`func (o *GrowthStateCampaignsInner) SetLastLeadPassAt(v string)`

SetLastLeadPassAt sets LastLeadPassAt field to given value.


### SetLastLeadPassAtNil

`func (o *GrowthStateCampaignsInner) SetLastLeadPassAtNil(b bool)`

 SetLastLeadPassAtNil sets the value for LastLeadPassAt to be an explicit nil

### UnsetLastLeadPassAt
`func (o *GrowthStateCampaignsInner) UnsetLastLeadPassAt()`

UnsetLastLeadPassAt ensures that no value is present for LastLeadPassAt, not even an explicit nil
### GetName

`func (o *GrowthStateCampaignsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GrowthStateCampaignsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GrowthStateCampaignsInner) SetName(v string)`

SetName sets Name field to given value.


### GetNegativeCriteria

`func (o *GrowthStateCampaignsInner) GetNegativeCriteria() []string`

GetNegativeCriteria returns the NegativeCriteria field if non-nil, zero value otherwise.

### GetNegativeCriteriaOk

`func (o *GrowthStateCampaignsInner) GetNegativeCriteriaOk() (*[]string, bool)`

GetNegativeCriteriaOk returns a tuple with the NegativeCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNegativeCriteria

`func (o *GrowthStateCampaignsInner) SetNegativeCriteria(v []string)`

SetNegativeCriteria sets NegativeCriteria field to given value.


### GetOrganizationId

`func (o *GrowthStateCampaignsInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *GrowthStateCampaignsInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *GrowthStateCampaignsInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPositiveCriteria

`func (o *GrowthStateCampaignsInner) GetPositiveCriteria() []string`

GetPositiveCriteria returns the PositiveCriteria field if non-nil, zero value otherwise.

### GetPositiveCriteriaOk

`func (o *GrowthStateCampaignsInner) GetPositiveCriteriaOk() (*[]string, bool)`

GetPositiveCriteriaOk returns a tuple with the PositiveCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPositiveCriteria

`func (o *GrowthStateCampaignsInner) SetPositiveCriteria(v []string)`

SetPositiveCriteria sets PositiveCriteria field to given value.


### GetProjectId

`func (o *GrowthStateCampaignsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GrowthStateCampaignsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GrowthStateCampaignsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetReviewFirstN

`func (o *GrowthStateCampaignsInner) GetReviewFirstN() int32`

GetReviewFirstN returns the ReviewFirstN field if non-nil, zero value otherwise.

### GetReviewFirstNOk

`func (o *GrowthStateCampaignsInner) GetReviewFirstNOk() (*int32, bool)`

GetReviewFirstNOk returns a tuple with the ReviewFirstN field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewFirstN

`func (o *GrowthStateCampaignsInner) SetReviewFirstN(v int32)`

SetReviewFirstN sets ReviewFirstN field to given value.


### GetSendingSchedule

`func (o *GrowthStateCampaignsInner) GetSendingSchedule() CreateGrowthPlaySendingSchedule`

GetSendingSchedule returns the SendingSchedule field if non-nil, zero value otherwise.

### GetSendingScheduleOk

`func (o *GrowthStateCampaignsInner) GetSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetSendingScheduleOk returns a tuple with the SendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingSchedule

`func (o *GrowthStateCampaignsInner) SetSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetSendingSchedule sets SendingSchedule field to given value.


### SetSendingScheduleNil

`func (o *GrowthStateCampaignsInner) SetSendingScheduleNil(b bool)`

 SetSendingScheduleNil sets the value for SendingSchedule to be an explicit nil

### UnsetSendingSchedule
`func (o *GrowthStateCampaignsInner) UnsetSendingSchedule()`

UnsetSendingSchedule ensures that no value is present for SendingSchedule, not even an explicit nil
### GetSequence

`func (o *GrowthStateCampaignsInner) GetSequence() CreateGrowthPlaySequence`

GetSequence returns the Sequence field if non-nil, zero value otherwise.

### GetSequenceOk

`func (o *GrowthStateCampaignsInner) GetSequenceOk() (*CreateGrowthPlaySequence, bool)`

GetSequenceOk returns a tuple with the Sequence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSequence

`func (o *GrowthStateCampaignsInner) SetSequence(v CreateGrowthPlaySequence)`

SetSequence sets Sequence field to given value.


### SetSequenceNil

`func (o *GrowthStateCampaignsInner) SetSequenceNil(b bool)`

 SetSequenceNil sets the value for Sequence to be an explicit nil

### UnsetSequence
`func (o *GrowthStateCampaignsInner) UnsetSequence()`

UnsetSequence ensures that no value is present for Sequence, not even an explicit nil
### GetStatus

`func (o *GrowthStateCampaignsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthStateCampaignsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthStateCampaignsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *GrowthStateCampaignsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GrowthStateCampaignsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GrowthStateCampaignsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetWho

`func (o *GrowthStateCampaignsInner) GetWho() map[string]interface{}`

GetWho returns the Who field if non-nil, zero value otherwise.

### GetWhoOk

`func (o *GrowthStateCampaignsInner) GetWhoOk() (*map[string]interface{}, bool)`

GetWhoOk returns a tuple with the Who field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWho

`func (o *GrowthStateCampaignsInner) SetWho(v map[string]interface{})`

SetWho sets Who field to given value.


### GetWhyNow

`func (o *GrowthStateCampaignsInner) GetWhyNow() GrowthPlayWhyNow`

GetWhyNow returns the WhyNow field if non-nil, zero value otherwise.

### GetWhyNowOk

`func (o *GrowthStateCampaignsInner) GetWhyNowOk() (*GrowthPlayWhyNow, bool)`

GetWhyNowOk returns a tuple with the WhyNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWhyNow

`func (o *GrowthStateCampaignsInner) SetWhyNow(v GrowthPlayWhyNow)`

SetWhyNow sets WhyNow field to given value.


### SetWhyNowNil

`func (o *GrowthStateCampaignsInner) SetWhyNowNil(b bool)`

 SetWhyNowNil sets the value for WhyNow to be an explicit nil

### UnsetWhyNow
`func (o *GrowthStateCampaignsInner) UnsetWhyNow()`

UnsetWhyNow ensures that no value is present for WhyNow, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


