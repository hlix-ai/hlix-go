# PromotionPartnerSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EarnedMonths** | **float32** |  |
**Grant** | [**NullablePromotionCurrentGrant**](PromotionCurrentGrant.md) |  |
**PaidReferralCount** | **float32** |  |
**Partner** | [**NullablePromotionPartnerSummaryPartner**](PromotionPartnerSummaryPartner.md) |  |
**ReferredCount** | **float32** |  |
**Rewards** | [**[]PromotionPartnerSummaryRewardsInner**](PromotionPartnerSummaryRewardsInner.md) |  |

## Methods

### NewPromotionPartnerSummary

`func NewPromotionPartnerSummary(earnedMonths float32, grant NullablePromotionCurrentGrant, paidReferralCount float32, partner NullablePromotionPartnerSummaryPartner, referredCount float32, rewards []PromotionPartnerSummaryRewardsInner, ) *PromotionPartnerSummary`

NewPromotionPartnerSummary instantiates a new PromotionPartnerSummary object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPromotionPartnerSummaryWithDefaults

`func NewPromotionPartnerSummaryWithDefaults() *PromotionPartnerSummary`

NewPromotionPartnerSummaryWithDefaults instantiates a new PromotionPartnerSummary object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetEarnedMonths

`func (o *PromotionPartnerSummary) GetEarnedMonths() float32`

GetEarnedMonths returns the EarnedMonths field if non-nil, zero value otherwise.

### GetEarnedMonthsOk

`func (o *PromotionPartnerSummary) GetEarnedMonthsOk() (*float32, bool)`

GetEarnedMonthsOk returns a tuple with the EarnedMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarnedMonths

`func (o *PromotionPartnerSummary) SetEarnedMonths(v float32)`

SetEarnedMonths sets EarnedMonths field to given value.


### GetGrant

`func (o *PromotionPartnerSummary) GetGrant() PromotionCurrentGrant`

GetGrant returns the Grant field if non-nil, zero value otherwise.

### GetGrantOk

`func (o *PromotionPartnerSummary) GetGrantOk() (*PromotionCurrentGrant, bool)`

GetGrantOk returns a tuple with the Grant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrant

`func (o *PromotionPartnerSummary) SetGrant(v PromotionCurrentGrant)`

SetGrant sets Grant field to given value.


### SetGrantNil

`func (o *PromotionPartnerSummary) SetGrantNil(b bool)`

 SetGrantNil sets the value for Grant to be an explicit nil

### UnsetGrant
`func (o *PromotionPartnerSummary) UnsetGrant()`

UnsetGrant ensures that no value is present for Grant, not even an explicit nil
### GetPaidReferralCount

`func (o *PromotionPartnerSummary) GetPaidReferralCount() float32`

GetPaidReferralCount returns the PaidReferralCount field if non-nil, zero value otherwise.

### GetPaidReferralCountOk

`func (o *PromotionPartnerSummary) GetPaidReferralCountOk() (*float32, bool)`

GetPaidReferralCountOk returns a tuple with the PaidReferralCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidReferralCount

`func (o *PromotionPartnerSummary) SetPaidReferralCount(v float32)`

SetPaidReferralCount sets PaidReferralCount field to given value.


### GetPartner

`func (o *PromotionPartnerSummary) GetPartner() PromotionPartnerSummaryPartner`

GetPartner returns the Partner field if non-nil, zero value otherwise.

### GetPartnerOk

`func (o *PromotionPartnerSummary) GetPartnerOk() (*PromotionPartnerSummaryPartner, bool)`

GetPartnerOk returns a tuple with the Partner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartner

`func (o *PromotionPartnerSummary) SetPartner(v PromotionPartnerSummaryPartner)`

SetPartner sets Partner field to given value.


### SetPartnerNil

`func (o *PromotionPartnerSummary) SetPartnerNil(b bool)`

 SetPartnerNil sets the value for Partner to be an explicit nil

### UnsetPartner
`func (o *PromotionPartnerSummary) UnsetPartner()`

UnsetPartner ensures that no value is present for Partner, not even an explicit nil
### GetReferredCount

`func (o *PromotionPartnerSummary) GetReferredCount() float32`

GetReferredCount returns the ReferredCount field if non-nil, zero value otherwise.

### GetReferredCountOk

`func (o *PromotionPartnerSummary) GetReferredCountOk() (*float32, bool)`

GetReferredCountOk returns a tuple with the ReferredCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferredCount

`func (o *PromotionPartnerSummary) SetReferredCount(v float32)`

SetReferredCount sets ReferredCount field to given value.


### GetRewards

`func (o *PromotionPartnerSummary) GetRewards() []PromotionPartnerSummaryRewardsInner`

GetRewards returns the Rewards field if non-nil, zero value otherwise.

### GetRewardsOk

`func (o *PromotionPartnerSummary) GetRewardsOk() (*[]PromotionPartnerSummaryRewardsInner, bool)`

GetRewardsOk returns a tuple with the Rewards field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRewards

`func (o *PromotionPartnerSummary) SetRewards(v []PromotionPartnerSummaryRewardsInner)`

SetRewards sets Rewards field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


