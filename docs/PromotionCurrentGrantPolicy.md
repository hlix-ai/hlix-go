# PromotionCurrentGrantPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AmountCents** | **int32** |  |
**DiscountType** | **string** |  |
**Duration** | **string** |  |
**DurationMonths** | **int32** |  |
**EligiblePlans** | **[]string** |  |
**MaxCodeRedemptions** | **NullableInt32** |  |
**MaxRedemptions** | **NullableInt32** |  |
**NewCustomersOnly** | Pointer to **bool** |  | [optional] [default to true]
**PercentOffBps** | **int32** |  |
**ReferralRewardMonths** | **int32** |  |

## Methods

### NewPromotionCurrentGrantPolicy

`func NewPromotionCurrentGrantPolicy(amountCents int32, discountType string, duration string, durationMonths int32, eligiblePlans []string, maxCodeRedemptions NullableInt32, maxRedemptions NullableInt32, percentOffBps int32, referralRewardMonths int32, ) *PromotionCurrentGrantPolicy`

NewPromotionCurrentGrantPolicy instantiates a new PromotionCurrentGrantPolicy object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPromotionCurrentGrantPolicyWithDefaults

`func NewPromotionCurrentGrantPolicyWithDefaults() *PromotionCurrentGrantPolicy`

NewPromotionCurrentGrantPolicyWithDefaults instantiates a new PromotionCurrentGrantPolicy object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAmountCents

`func (o *PromotionCurrentGrantPolicy) GetAmountCents() int32`

GetAmountCents returns the AmountCents field if non-nil, zero value otherwise.

### GetAmountCentsOk

`func (o *PromotionCurrentGrantPolicy) GetAmountCentsOk() (*int32, bool)`

GetAmountCentsOk returns a tuple with the AmountCents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountCents

`func (o *PromotionCurrentGrantPolicy) SetAmountCents(v int32)`

SetAmountCents sets AmountCents field to given value.


### GetDiscountType

`func (o *PromotionCurrentGrantPolicy) GetDiscountType() string`

GetDiscountType returns the DiscountType field if non-nil, zero value otherwise.

### GetDiscountTypeOk

`func (o *PromotionCurrentGrantPolicy) GetDiscountTypeOk() (*string, bool)`

GetDiscountTypeOk returns a tuple with the DiscountType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountType

`func (o *PromotionCurrentGrantPolicy) SetDiscountType(v string)`

SetDiscountType sets DiscountType field to given value.


### GetDuration

`func (o *PromotionCurrentGrantPolicy) GetDuration() string`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *PromotionCurrentGrantPolicy) GetDurationOk() (*string, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *PromotionCurrentGrantPolicy) SetDuration(v string)`

SetDuration sets Duration field to given value.


### GetDurationMonths

`func (o *PromotionCurrentGrantPolicy) GetDurationMonths() int32`

GetDurationMonths returns the DurationMonths field if non-nil, zero value otherwise.

### GetDurationMonthsOk

`func (o *PromotionCurrentGrantPolicy) GetDurationMonthsOk() (*int32, bool)`

GetDurationMonthsOk returns a tuple with the DurationMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMonths

`func (o *PromotionCurrentGrantPolicy) SetDurationMonths(v int32)`

SetDurationMonths sets DurationMonths field to given value.


### GetEligiblePlans

`func (o *PromotionCurrentGrantPolicy) GetEligiblePlans() []string`

GetEligiblePlans returns the EligiblePlans field if non-nil, zero value otherwise.

### GetEligiblePlansOk

`func (o *PromotionCurrentGrantPolicy) GetEligiblePlansOk() (*[]string, bool)`

GetEligiblePlansOk returns a tuple with the EligiblePlans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEligiblePlans

`func (o *PromotionCurrentGrantPolicy) SetEligiblePlans(v []string)`

SetEligiblePlans sets EligiblePlans field to given value.


### GetMaxCodeRedemptions

`func (o *PromotionCurrentGrantPolicy) GetMaxCodeRedemptions() int32`

GetMaxCodeRedemptions returns the MaxCodeRedemptions field if non-nil, zero value otherwise.

### GetMaxCodeRedemptionsOk

`func (o *PromotionCurrentGrantPolicy) GetMaxCodeRedemptionsOk() (*int32, bool)`

GetMaxCodeRedemptionsOk returns a tuple with the MaxCodeRedemptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCodeRedemptions

`func (o *PromotionCurrentGrantPolicy) SetMaxCodeRedemptions(v int32)`

SetMaxCodeRedemptions sets MaxCodeRedemptions field to given value.


### SetMaxCodeRedemptionsNil

`func (o *PromotionCurrentGrantPolicy) SetMaxCodeRedemptionsNil(b bool)`

 SetMaxCodeRedemptionsNil sets the value for MaxCodeRedemptions to be an explicit nil

### UnsetMaxCodeRedemptions
`func (o *PromotionCurrentGrantPolicy) UnsetMaxCodeRedemptions()`

UnsetMaxCodeRedemptions ensures that no value is present for MaxCodeRedemptions, not even an explicit nil
### GetMaxRedemptions

`func (o *PromotionCurrentGrantPolicy) GetMaxRedemptions() int32`

GetMaxRedemptions returns the MaxRedemptions field if non-nil, zero value otherwise.

### GetMaxRedemptionsOk

`func (o *PromotionCurrentGrantPolicy) GetMaxRedemptionsOk() (*int32, bool)`

GetMaxRedemptionsOk returns a tuple with the MaxRedemptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRedemptions

`func (o *PromotionCurrentGrantPolicy) SetMaxRedemptions(v int32)`

SetMaxRedemptions sets MaxRedemptions field to given value.


### SetMaxRedemptionsNil

`func (o *PromotionCurrentGrantPolicy) SetMaxRedemptionsNil(b bool)`

 SetMaxRedemptionsNil sets the value for MaxRedemptions to be an explicit nil

### UnsetMaxRedemptions
`func (o *PromotionCurrentGrantPolicy) UnsetMaxRedemptions()`

UnsetMaxRedemptions ensures that no value is present for MaxRedemptions, not even an explicit nil
### GetNewCustomersOnly

`func (o *PromotionCurrentGrantPolicy) GetNewCustomersOnly() bool`

GetNewCustomersOnly returns the NewCustomersOnly field if non-nil, zero value otherwise.

### GetNewCustomersOnlyOk

`func (o *PromotionCurrentGrantPolicy) GetNewCustomersOnlyOk() (*bool, bool)`

GetNewCustomersOnlyOk returns a tuple with the NewCustomersOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewCustomersOnly

`func (o *PromotionCurrentGrantPolicy) SetNewCustomersOnly(v bool)`

SetNewCustomersOnly sets NewCustomersOnly field to given value.

### HasNewCustomersOnly

`func (o *PromotionCurrentGrantPolicy) HasNewCustomersOnly() bool`

HasNewCustomersOnly returns a boolean if a field has been set.

### GetPercentOffBps

`func (o *PromotionCurrentGrantPolicy) GetPercentOffBps() int32`

GetPercentOffBps returns the PercentOffBps field if non-nil, zero value otherwise.

### GetPercentOffBpsOk

`func (o *PromotionCurrentGrantPolicy) GetPercentOffBpsOk() (*int32, bool)`

GetPercentOffBpsOk returns a tuple with the PercentOffBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercentOffBps

`func (o *PromotionCurrentGrantPolicy) SetPercentOffBps(v int32)`

SetPercentOffBps sets PercentOffBps field to given value.


### GetReferralRewardMonths

`func (o *PromotionCurrentGrantPolicy) GetReferralRewardMonths() int32`

GetReferralRewardMonths returns the ReferralRewardMonths field if non-nil, zero value otherwise.

### GetReferralRewardMonthsOk

`func (o *PromotionCurrentGrantPolicy) GetReferralRewardMonthsOk() (*int32, bool)`

GetReferralRewardMonthsOk returns a tuple with the ReferralRewardMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferralRewardMonths

`func (o *PromotionCurrentGrantPolicy) SetReferralRewardMonths(v int32)`

SetReferralRewardMonths sets ReferralRewardMonths field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


