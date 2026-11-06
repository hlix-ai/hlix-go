# GrowthBrainRowContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Competitors** | [**[]GrowthBrainCompetitorsInner**](GrowthBrainCompetitorsInner.md) |  | 
**Languages** | [**[]GrowthBrainLanguagesInner**](GrowthBrainLanguagesInner.md) |  | 
**NeverSay** | **[]string** |  | 
**Offer** | [**NullableGrowthBrainOffer**](GrowthBrainOffer.md) |  | 
**Pricing** | [**NullableGrowthBrainOffer**](GrowthBrainOffer.md) |  | 
**Proof** | [**[]GrowthBrainLanguagesInner**](GrowthBrainLanguagesInner.md) |  | 

## Methods

### NewGrowthBrainRowContent

`func NewGrowthBrainRowContent(competitors []GrowthBrainCompetitorsInner, languages []GrowthBrainLanguagesInner, neverSay []string, offer NullableGrowthBrainOffer, pricing NullableGrowthBrainOffer, proof []GrowthBrainLanguagesInner, ) *GrowthBrainRowContent`

NewGrowthBrainRowContent instantiates a new GrowthBrainRowContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthBrainRowContentWithDefaults

`func NewGrowthBrainRowContentWithDefaults() *GrowthBrainRowContent`

NewGrowthBrainRowContentWithDefaults instantiates a new GrowthBrainRowContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompetitors

`func (o *GrowthBrainRowContent) GetCompetitors() []GrowthBrainCompetitorsInner`

GetCompetitors returns the Competitors field if non-nil, zero value otherwise.

### GetCompetitorsOk

`func (o *GrowthBrainRowContent) GetCompetitorsOk() (*[]GrowthBrainCompetitorsInner, bool)`

GetCompetitorsOk returns a tuple with the Competitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompetitors

`func (o *GrowthBrainRowContent) SetCompetitors(v []GrowthBrainCompetitorsInner)`

SetCompetitors sets Competitors field to given value.


### GetLanguages

`func (o *GrowthBrainRowContent) GetLanguages() []GrowthBrainLanguagesInner`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *GrowthBrainRowContent) GetLanguagesOk() (*[]GrowthBrainLanguagesInner, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *GrowthBrainRowContent) SetLanguages(v []GrowthBrainLanguagesInner)`

SetLanguages sets Languages field to given value.


### GetNeverSay

`func (o *GrowthBrainRowContent) GetNeverSay() []string`

GetNeverSay returns the NeverSay field if non-nil, zero value otherwise.

### GetNeverSayOk

`func (o *GrowthBrainRowContent) GetNeverSayOk() (*[]string, bool)`

GetNeverSayOk returns a tuple with the NeverSay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeverSay

`func (o *GrowthBrainRowContent) SetNeverSay(v []string)`

SetNeverSay sets NeverSay field to given value.


### GetOffer

`func (o *GrowthBrainRowContent) GetOffer() GrowthBrainOffer`

GetOffer returns the Offer field if non-nil, zero value otherwise.

### GetOfferOk

`func (o *GrowthBrainRowContent) GetOfferOk() (*GrowthBrainOffer, bool)`

GetOfferOk returns a tuple with the Offer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffer

`func (o *GrowthBrainRowContent) SetOffer(v GrowthBrainOffer)`

SetOffer sets Offer field to given value.


### SetOfferNil

`func (o *GrowthBrainRowContent) SetOfferNil(b bool)`

 SetOfferNil sets the value for Offer to be an explicit nil

### UnsetOffer
`func (o *GrowthBrainRowContent) UnsetOffer()`

UnsetOffer ensures that no value is present for Offer, not even an explicit nil
### GetPricing

`func (o *GrowthBrainRowContent) GetPricing() GrowthBrainOffer`

GetPricing returns the Pricing field if non-nil, zero value otherwise.

### GetPricingOk

`func (o *GrowthBrainRowContent) GetPricingOk() (*GrowthBrainOffer, bool)`

GetPricingOk returns a tuple with the Pricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricing

`func (o *GrowthBrainRowContent) SetPricing(v GrowthBrainOffer)`

SetPricing sets Pricing field to given value.


### SetPricingNil

`func (o *GrowthBrainRowContent) SetPricingNil(b bool)`

 SetPricingNil sets the value for Pricing to be an explicit nil

### UnsetPricing
`func (o *GrowthBrainRowContent) UnsetPricing()`

UnsetPricing ensures that no value is present for Pricing, not even an explicit nil
### GetProof

`func (o *GrowthBrainRowContent) GetProof() []GrowthBrainLanguagesInner`

GetProof returns the Proof field if non-nil, zero value otherwise.

### GetProofOk

`func (o *GrowthBrainRowContent) GetProofOk() (*[]GrowthBrainLanguagesInner, bool)`

GetProofOk returns a tuple with the Proof field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProof

`func (o *GrowthBrainRowContent) SetProof(v []GrowthBrainLanguagesInner)`

SetProof sets Proof field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


