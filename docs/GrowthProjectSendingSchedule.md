# GrowthProjectSendingSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Campaigns** | [**[]GrowthProjectSendingScheduleCampaignsInner**](GrowthProjectSendingScheduleCampaignsInner.md) |  |
**Effective** | [**GrowthProjectSendingScheduleCampaignsInnerEffective**](GrowthProjectSendingScheduleCampaignsInnerEffective.md) |  |
**InheritedCampaignCount** | **int32** |  |
**Rows** | [**[]GrowthProjectSendingScheduleCampaignsInnerRowsInner**](GrowthProjectSendingScheduleCampaignsInnerRowsInner.md) |  |
**Schedule** | [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  |
**Source** | **string** |  |

## Methods

### NewGrowthProjectSendingSchedule

`func NewGrowthProjectSendingSchedule(campaigns []GrowthProjectSendingScheduleCampaignsInner, effective GrowthProjectSendingScheduleCampaignsInnerEffective, inheritedCampaignCount int32, rows []GrowthProjectSendingScheduleCampaignsInnerRowsInner, schedule NullableCreateGrowthPlaySendingSchedule, source string, ) *GrowthProjectSendingSchedule`

NewGrowthProjectSendingSchedule instantiates a new GrowthProjectSendingSchedule object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthProjectSendingScheduleWithDefaults

`func NewGrowthProjectSendingScheduleWithDefaults() *GrowthProjectSendingSchedule`

NewGrowthProjectSendingScheduleWithDefaults instantiates a new GrowthProjectSendingSchedule object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCampaigns

`func (o *GrowthProjectSendingSchedule) GetCampaigns() []GrowthProjectSendingScheduleCampaignsInner`

GetCampaigns returns the Campaigns field if non-nil, zero value otherwise.

### GetCampaignsOk

`func (o *GrowthProjectSendingSchedule) GetCampaignsOk() (*[]GrowthProjectSendingScheduleCampaignsInner, bool)`

GetCampaignsOk returns a tuple with the Campaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaigns

`func (o *GrowthProjectSendingSchedule) SetCampaigns(v []GrowthProjectSendingScheduleCampaignsInner)`

SetCampaigns sets Campaigns field to given value.


### GetEffective

`func (o *GrowthProjectSendingSchedule) GetEffective() GrowthProjectSendingScheduleCampaignsInnerEffective`

GetEffective returns the Effective field if non-nil, zero value otherwise.

### GetEffectiveOk

`func (o *GrowthProjectSendingSchedule) GetEffectiveOk() (*GrowthProjectSendingScheduleCampaignsInnerEffective, bool)`

GetEffectiveOk returns a tuple with the Effective field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffective

`func (o *GrowthProjectSendingSchedule) SetEffective(v GrowthProjectSendingScheduleCampaignsInnerEffective)`

SetEffective sets Effective field to given value.


### GetInheritedCampaignCount

`func (o *GrowthProjectSendingSchedule) GetInheritedCampaignCount() int32`

GetInheritedCampaignCount returns the InheritedCampaignCount field if non-nil, zero value otherwise.

### GetInheritedCampaignCountOk

`func (o *GrowthProjectSendingSchedule) GetInheritedCampaignCountOk() (*int32, bool)`

GetInheritedCampaignCountOk returns a tuple with the InheritedCampaignCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInheritedCampaignCount

`func (o *GrowthProjectSendingSchedule) SetInheritedCampaignCount(v int32)`

SetInheritedCampaignCount sets InheritedCampaignCount field to given value.


### GetRows

`func (o *GrowthProjectSendingSchedule) GetRows() []GrowthProjectSendingScheduleCampaignsInnerRowsInner`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *GrowthProjectSendingSchedule) GetRowsOk() (*[]GrowthProjectSendingScheduleCampaignsInnerRowsInner, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *GrowthProjectSendingSchedule) SetRows(v []GrowthProjectSendingScheduleCampaignsInnerRowsInner)`

SetRows sets Rows field to given value.


### GetSchedule

`func (o *GrowthProjectSendingSchedule) GetSchedule() CreateGrowthPlaySendingSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *GrowthProjectSendingSchedule) GetScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *GrowthProjectSendingSchedule) SetSchedule(v CreateGrowthPlaySendingSchedule)`

SetSchedule sets Schedule field to given value.


### SetScheduleNil

`func (o *GrowthProjectSendingSchedule) SetScheduleNil(b bool)`

 SetScheduleNil sets the value for Schedule to be an explicit nil

### UnsetSchedule
`func (o *GrowthProjectSendingSchedule) UnsetSchedule()`

UnsetSchedule ensures that no value is present for Schedule, not even an explicit nil
### GetSource

`func (o *GrowthProjectSendingSchedule) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *GrowthProjectSendingSchedule) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *GrowthProjectSendingSchedule) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


