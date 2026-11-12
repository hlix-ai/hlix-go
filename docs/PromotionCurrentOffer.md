# PromotionCurrentOffer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignId** | **string** |  |
**Kind** | **string** |  |
**Name** | **string** |  |
**Partner** | [**NullablePromotionCurrentOfferPartner**](PromotionCurrentOfferPartner.md) |  |
**Policy** | [**PromotionCurrentGrantPolicy**](PromotionCurrentGrantPolicy.md) |  |
**Quotes** | [**[]PromotionCurrentOfferQuotesInner**](PromotionCurrentOfferQuotesInner.md) |  |

## Methods

### NewPromotionCurrentOffer

`func NewPromotionCurrentOffer(campaignId string, kind string, name string, partner NullablePromotionCurrentOfferPartner, policy PromotionCurrentGrantPolicy, quotes []PromotionCurrentOfferQuotesInner, ) *PromotionCurrentOffer`

NewPromotionCurrentOffer instantiates a new PromotionCurrentOffer object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPromotionCurrentOfferWithDefaults

`func NewPromotionCurrentOfferWithDefaults() *PromotionCurrentOffer`

NewPromotionCurrentOfferWithDefaults instantiates a new PromotionCurrentOffer object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCampaignId

`func (o *PromotionCurrentOffer) GetCampaignId() string`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *PromotionCurrentOffer) GetCampaignIdOk() (*string, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *PromotionCurrentOffer) SetCampaignId(v string)`

SetCampaignId sets CampaignId field to given value.


### GetKind

`func (o *PromotionCurrentOffer) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PromotionCurrentOffer) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PromotionCurrentOffer) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *PromotionCurrentOffer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PromotionCurrentOffer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PromotionCurrentOffer) SetName(v string)`

SetName sets Name field to given value.


### GetPartner

`func (o *PromotionCurrentOffer) GetPartner() PromotionCurrentOfferPartner`

GetPartner returns the Partner field if non-nil, zero value otherwise.

### GetPartnerOk

`func (o *PromotionCurrentOffer) GetPartnerOk() (*PromotionCurrentOfferPartner, bool)`

GetPartnerOk returns a tuple with the Partner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartner

`func (o *PromotionCurrentOffer) SetPartner(v PromotionCurrentOfferPartner)`

SetPartner sets Partner field to given value.


### SetPartnerNil

`func (o *PromotionCurrentOffer) SetPartnerNil(b bool)`

 SetPartnerNil sets the value for Partner to be an explicit nil

### UnsetPartner
`func (o *PromotionCurrentOffer) UnsetPartner()`

UnsetPartner ensures that no value is present for Partner, not even an explicit nil
### GetPolicy

`func (o *PromotionCurrentOffer) GetPolicy() PromotionCurrentGrantPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *PromotionCurrentOffer) GetPolicyOk() (*PromotionCurrentGrantPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *PromotionCurrentOffer) SetPolicy(v PromotionCurrentGrantPolicy)`

SetPolicy sets Policy field to given value.


### GetQuotes

`func (o *PromotionCurrentOffer) GetQuotes() []PromotionCurrentOfferQuotesInner`

GetQuotes returns the Quotes field if non-nil, zero value otherwise.

### GetQuotesOk

`func (o *PromotionCurrentOffer) GetQuotesOk() (*[]PromotionCurrentOfferQuotesInner, bool)`

GetQuotesOk returns a tuple with the Quotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotes

`func (o *PromotionCurrentOffer) SetQuotes(v []PromotionCurrentOfferQuotesInner)`

SetQuotes sets Quotes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


