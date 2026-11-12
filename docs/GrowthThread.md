# GrowthThread

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deal** | [**NullableGrowthThreadDeal**](GrowthThreadDeal.md) |  |
**Lead** | [**GrowthThreadLead**](GrowthThreadLead.md) |  |
**Messages** | [**[]GrowthThreadMessagesInner**](GrowthThreadMessagesInner.md) |  |

## Methods

### NewGrowthThread

`func NewGrowthThread(deal NullableGrowthThreadDeal, lead GrowthThreadLead, messages []GrowthThreadMessagesInner, ) *GrowthThread`

NewGrowthThread instantiates a new GrowthThread object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthThreadWithDefaults

`func NewGrowthThreadWithDefaults() *GrowthThread`

NewGrowthThreadWithDefaults instantiates a new GrowthThread object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDeal

`func (o *GrowthThread) GetDeal() GrowthThreadDeal`

GetDeal returns the Deal field if non-nil, zero value otherwise.

### GetDealOk

`func (o *GrowthThread) GetDealOk() (*GrowthThreadDeal, bool)`

GetDealOk returns a tuple with the Deal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeal

`func (o *GrowthThread) SetDeal(v GrowthThreadDeal)`

SetDeal sets Deal field to given value.


### SetDealNil

`func (o *GrowthThread) SetDealNil(b bool)`

 SetDealNil sets the value for Deal to be an explicit nil

### UnsetDeal
`func (o *GrowthThread) UnsetDeal()`

UnsetDeal ensures that no value is present for Deal, not even an explicit nil
### GetLead

`func (o *GrowthThread) GetLead() GrowthThreadLead`

GetLead returns the Lead field if non-nil, zero value otherwise.

### GetLeadOk

`func (o *GrowthThread) GetLeadOk() (*GrowthThreadLead, bool)`

GetLeadOk returns a tuple with the Lead field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLead

`func (o *GrowthThread) SetLead(v GrowthThreadLead)`

SetLead sets Lead field to given value.


### GetMessages

`func (o *GrowthThread) GetMessages() []GrowthThreadMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *GrowthThread) GetMessagesOk() (*[]GrowthThreadMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *GrowthThread) SetMessages(v []GrowthThreadMessagesInner)`

SetMessages sets Messages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


