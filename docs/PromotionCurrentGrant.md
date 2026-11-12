# PromotionCurrentGrant

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CampaignId** | **string** |  |
**CampaignName** | **string** |  |
**CreatedAt** | **string** |  |
**EarnedMonths** | **float32** |  |
**EndsAt** | **NullableString** |  |
**Id** | **string** |  |
**OrganizationId** | **string** |  |
**PartnerId** | **NullableString** |  |
**Policy** | [**PromotionCurrentGrantPolicy**](PromotionCurrentGrantPolicy.md) |  |
**StartsAt** | **NullableString** |  |
**State** | **string** |  |
**SubscriptionId** | **NullableString** |  |
**SyncState** | **string** |  |

## Methods

### NewPromotionCurrentGrant

`func NewPromotionCurrentGrant(campaignId string, campaignName string, createdAt string, earnedMonths float32, endsAt NullableString, id string, organizationId string, partnerId NullableString, policy PromotionCurrentGrantPolicy, startsAt NullableString, state string, subscriptionId NullableString, syncState string, ) *PromotionCurrentGrant`

NewPromotionCurrentGrant instantiates a new PromotionCurrentGrant object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPromotionCurrentGrantWithDefaults

`func NewPromotionCurrentGrantWithDefaults() *PromotionCurrentGrant`

NewPromotionCurrentGrantWithDefaults instantiates a new PromotionCurrentGrant object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCampaignId

`func (o *PromotionCurrentGrant) GetCampaignId() string`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *PromotionCurrentGrant) GetCampaignIdOk() (*string, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *PromotionCurrentGrant) SetCampaignId(v string)`

SetCampaignId sets CampaignId field to given value.


### GetCampaignName

`func (o *PromotionCurrentGrant) GetCampaignName() string`

GetCampaignName returns the CampaignName field if non-nil, zero value otherwise.

### GetCampaignNameOk

`func (o *PromotionCurrentGrant) GetCampaignNameOk() (*string, bool)`

GetCampaignNameOk returns a tuple with the CampaignName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignName

`func (o *PromotionCurrentGrant) SetCampaignName(v string)`

SetCampaignName sets CampaignName field to given value.


### GetCreatedAt

`func (o *PromotionCurrentGrant) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PromotionCurrentGrant) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PromotionCurrentGrant) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEarnedMonths

`func (o *PromotionCurrentGrant) GetEarnedMonths() float32`

GetEarnedMonths returns the EarnedMonths field if non-nil, zero value otherwise.

### GetEarnedMonthsOk

`func (o *PromotionCurrentGrant) GetEarnedMonthsOk() (*float32, bool)`

GetEarnedMonthsOk returns a tuple with the EarnedMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEarnedMonths

`func (o *PromotionCurrentGrant) SetEarnedMonths(v float32)`

SetEarnedMonths sets EarnedMonths field to given value.


### GetEndsAt

`func (o *PromotionCurrentGrant) GetEndsAt() string`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *PromotionCurrentGrant) GetEndsAtOk() (*string, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *PromotionCurrentGrant) SetEndsAt(v string)`

SetEndsAt sets EndsAt field to given value.


### SetEndsAtNil

`func (o *PromotionCurrentGrant) SetEndsAtNil(b bool)`

 SetEndsAtNil sets the value for EndsAt to be an explicit nil

### UnsetEndsAt
`func (o *PromotionCurrentGrant) UnsetEndsAt()`

UnsetEndsAt ensures that no value is present for EndsAt, not even an explicit nil
### GetId

`func (o *PromotionCurrentGrant) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PromotionCurrentGrant) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PromotionCurrentGrant) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *PromotionCurrentGrant) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *PromotionCurrentGrant) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *PromotionCurrentGrant) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPartnerId

`func (o *PromotionCurrentGrant) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PromotionCurrentGrant) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PromotionCurrentGrant) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### SetPartnerIdNil

`func (o *PromotionCurrentGrant) SetPartnerIdNil(b bool)`

 SetPartnerIdNil sets the value for PartnerId to be an explicit nil

### UnsetPartnerId
`func (o *PromotionCurrentGrant) UnsetPartnerId()`

UnsetPartnerId ensures that no value is present for PartnerId, not even an explicit nil
### GetPolicy

`func (o *PromotionCurrentGrant) GetPolicy() PromotionCurrentGrantPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *PromotionCurrentGrant) GetPolicyOk() (*PromotionCurrentGrantPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *PromotionCurrentGrant) SetPolicy(v PromotionCurrentGrantPolicy)`

SetPolicy sets Policy field to given value.


### GetStartsAt

`func (o *PromotionCurrentGrant) GetStartsAt() string`

GetStartsAt returns the StartsAt field if non-nil, zero value otherwise.

### GetStartsAtOk

`func (o *PromotionCurrentGrant) GetStartsAtOk() (*string, bool)`

GetStartsAtOk returns a tuple with the StartsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsAt

`func (o *PromotionCurrentGrant) SetStartsAt(v string)`

SetStartsAt sets StartsAt field to given value.


### SetStartsAtNil

`func (o *PromotionCurrentGrant) SetStartsAtNil(b bool)`

 SetStartsAtNil sets the value for StartsAt to be an explicit nil

### UnsetStartsAt
`func (o *PromotionCurrentGrant) UnsetStartsAt()`

UnsetStartsAt ensures that no value is present for StartsAt, not even an explicit nil
### GetState

`func (o *PromotionCurrentGrant) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *PromotionCurrentGrant) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *PromotionCurrentGrant) SetState(v string)`

SetState sets State field to given value.


### GetSubscriptionId

`func (o *PromotionCurrentGrant) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *PromotionCurrentGrant) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *PromotionCurrentGrant) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.


### SetSubscriptionIdNil

`func (o *PromotionCurrentGrant) SetSubscriptionIdNil(b bool)`

 SetSubscriptionIdNil sets the value for SubscriptionId to be an explicit nil

### UnsetSubscriptionId
`func (o *PromotionCurrentGrant) UnsetSubscriptionId()`

UnsetSubscriptionId ensures that no value is present for SubscriptionId, not even an explicit nil
### GetSyncState

`func (o *PromotionCurrentGrant) GetSyncState() string`

GetSyncState returns the SyncState field if non-nil, zero value otherwise.

### GetSyncStateOk

`func (o *PromotionCurrentGrant) GetSyncStateOk() (*string, bool)`

GetSyncStateOk returns a tuple with the SyncState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncState

`func (o *PromotionCurrentGrant) SetSyncState(v string)`

SetSyncState sets SyncState field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


