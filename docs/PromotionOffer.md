# PromotionOffer

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

### NewPromotionOffer

`func NewPromotionOffer(campaignId string, kind string, name string, partner NullablePromotionCurrentOfferPartner, policy PromotionCurrentGrantPolicy, quotes []PromotionCurrentOfferQuotesInner, ) *PromotionOffer`

NewPromotionOffer instantiates a new PromotionOffer object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPromotionOfferWithDefaults

`func NewPromotionOfferWithDefaults() *PromotionOffer`

NewPromotionOfferWithDefaults instantiates a new PromotionOffer object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCampaignId

`func (o *PromotionOffer) GetCampaignId() string`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *PromotionOffer) GetCampaignIdOk() (*string, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *PromotionOffer) SetCampaignId(v string)`

SetCampaignId sets CampaignId field to given value.


### GetKind

`func (o *PromotionOffer) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *PromotionOffer) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *PromotionOffer) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *PromotionOffer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PromotionOffer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PromotionOffer) SetName(v string)`

SetName sets Name field to given value.


### GetPartner

`func (o *PromotionOffer) GetPartner() PromotionCurrentOfferPartner`

GetPartner returns the Partner field if non-nil, zero value otherwise.

### GetPartnerOk

`func (o *PromotionOffer) GetPartnerOk() (*PromotionCurrentOfferPartner, bool)`

GetPartnerOk returns a tuple with the Partner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartner

`func (o *PromotionOffer) SetPartner(v PromotionCurrentOfferPartner)`

SetPartner sets Partner field to given value.


### SetPartnerNil

`func (o *PromotionOffer) SetPartnerNil(b bool)`

 SetPartnerNil sets the value for Partner to be an explicit nil

### UnsetPartner
`func (o *PromotionOffer) UnsetPartner()`

UnsetPartner ensures that no value is present for Partner, not even an explicit nil
### GetPolicy

`func (o *PromotionOffer) GetPolicy() PromotionCurrentGrantPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *PromotionOffer) GetPolicyOk() (*PromotionCurrentGrantPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *PromotionOffer) SetPolicy(v PromotionCurrentGrantPolicy)`

SetPolicy sets Policy field to given value.


### GetQuotes

`func (o *PromotionOffer) GetQuotes() []PromotionCurrentOfferQuotesInner`

GetQuotes returns the Quotes field if non-nil, zero value otherwise.

### GetQuotesOk

`func (o *PromotionOffer) GetQuotesOk() (*[]PromotionCurrentOfferQuotesInner, bool)`

GetQuotesOk returns a tuple with the Quotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotes

`func (o *PromotionOffer) SetQuotes(v []PromotionCurrentOfferQuotesInner)`

SetQuotes sets Quotes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


