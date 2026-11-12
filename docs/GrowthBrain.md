# GrowthBrain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Competitors** | [**[]GrowthBrainCompetitorsInner**](GrowthBrainCompetitorsInner.md) |  |
**Languages** | [**[]GrowthBrainLanguagesInner**](GrowthBrainLanguagesInner.md) |  |
**NeverSay** | **[]string** |  |
**Offer** | [**NullableGrowthBrainOffer**](GrowthBrainOffer.md) |  |
**Pricing** | [**NullableGrowthBrainOffer**](GrowthBrainOffer.md) |  |
**Proof** | [**[]GrowthBrainOffer**](GrowthBrainOffer.md) |  |

## Methods

### NewGrowthBrain

`func NewGrowthBrain(competitors []GrowthBrainCompetitorsInner, languages []GrowthBrainLanguagesInner, neverSay []string, offer NullableGrowthBrainOffer, pricing NullableGrowthBrainOffer, proof []GrowthBrainOffer, ) *GrowthBrain`

NewGrowthBrain instantiates a new GrowthBrain object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthBrainWithDefaults

`func NewGrowthBrainWithDefaults() *GrowthBrain`

NewGrowthBrainWithDefaults instantiates a new GrowthBrain object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCompetitors

`func (o *GrowthBrain) GetCompetitors() []GrowthBrainCompetitorsInner`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *GrowthBrain) GetCompetitorsOk() (*[]GrowthBrainCompetitorsInner, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *GrowthBrain) SetCompetitors(v []GrowthBrainCompetitorsInner)`

SetCompetitors sets Competitors field to given value.


### GetLanguages

`func (o *GrowthBrain) GetLanguages() []GrowthBrainLanguagesInner`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *GrowthBrain) GetLanguagesOk() (*[]GrowthBrainLanguagesInner, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *GrowthBrain) SetLanguages(v []GrowthBrainLanguagesInner)`

SetLanguages sets Languages field to given value.


### GetNeverSay

`func (o *GrowthBrain) GetNeverSay() []string`

GetNeverSay returns the NeverSay field if non-nil, zero value otherwise.

### GetNeverSayOk

`func (o *GrowthBrain) GetNeverSayOk() (*[]string, bool)`

GetNeverSayOk returns a tuple with the NeverSay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeverSay

`func (o *GrowthBrain) SetNeverSay(v []string)`

SetNeverSay sets NeverSay field to given value.


### GetOffer

`func (o *GrowthBrain) GetOffer() GrowthBrainOffer`

GetOffer returns the Offer field if non-nil, zero value otherwise.

### GetOfferOk

`func (o *GrowthBrain) GetOfferOk() (*GrowthBrainOffer, bool)`

GetOfferOk returns a tuple with the Offer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffer

`func (o *GrowthBrain) SetOffer(v GrowthBrainOffer)`

SetOffer sets Offer field to given value.


### SetOfferNil

`func (o *GrowthBrain) SetOfferNil(b bool)`

 SetOfferNil sets the value for Offer to be an explicit nil

### UnsetOffer
`func (o *GrowthBrain) UnsetOffer()`

UnsetOffer ensures that no value is present for Offer, not even an explicit nil
### GetPricing

`func (o *GrowthBrain) GetPricing() GrowthBrainOffer`

GetPricing returns the Pricing field if non-nil, zero value otherwise.

### GetPricingOk

`func (o *GrowthBrain) GetPricingOk() (*GrowthBrainOffer, bool)`

GetPricingOk returns a tuple with the Pricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricing

`func (o *GrowthBrain) SetPricing(v GrowthBrainOffer)`

SetPricing sets Pricing field to given value.


### SetPricingNil

`func (o *GrowthBrain) SetPricingNil(b bool)`

 SetPricingNil sets the value for Pricing to be an explicit nil

### UnsetPricing
`func (o *GrowthBrain) UnsetPricing()`

UnsetPricing ensures that no value is present for Pricing, not even an explicit nil
### GetProof

`func (o *GrowthBrain) GetProof() []GrowthBrainOffer`

GetProof returns the Proof field if non-nil, zero value otherwise.

### GetProofOk

`func (o *GrowthBrain) GetProofOk() (*[]GrowthBrainOffer, bool)`

GetProofOk returns a tuple with the Proof field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProof

`func (o *GrowthBrain) SetProof(v []GrowthBrainOffer)`

SetProof sets Proof field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


