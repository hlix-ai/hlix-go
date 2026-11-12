# GrowthProjectSendingScheduleCampaignsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Effective** | [**GrowthProjectSendingScheduleCampaignsInnerEffective**](GrowthProjectSendingScheduleCampaignsInnerEffective.md) |  |
**Name** | **string** |  |
**PlayId** | **string** |  |
**Rows** | [**[]GrowthProjectSendingScheduleCampaignsInnerRowsInner**](GrowthProjectSendingScheduleCampaignsInnerRowsInner.md) |  |
**Schedule** | [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  |
**Source** | **string** |  |

## Methods

### NewGrowthProjectSendingScheduleCampaignsInner

`func NewGrowthProjectSendingScheduleCampaignsInner(effective GrowthProjectSendingScheduleCampaignsInnerEffective, name string, playId string, rows []GrowthProjectSendingScheduleCampaignsInnerRowsInner, schedule NullableCreateGrowthPlaySendingSchedule, source string, ) *GrowthProjectSendingScheduleCampaignsInner`

NewGrowthProjectSendingScheduleCampaignsInner instantiates a new GrowthProjectSendingScheduleCampaignsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthProjectSendingScheduleCampaignsInnerWithDefaults

`func NewGrowthProjectSendingScheduleCampaignsInnerWithDefaults() *GrowthProjectSendingScheduleCampaignsInner`

NewGrowthProjectSendingScheduleCampaignsInnerWithDefaults instantiates a new GrowthProjectSendingScheduleCampaignsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetEffective

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetEffective() GrowthProjectSendingScheduleCampaignsInnerEffective`

GetEffective returns the Effective field if non-nil, zero value otherwise.

### GetEffectiveOk

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetEffectiveOk() (*GrowthProjectSendingScheduleCampaignsInnerEffective, bool)`

GetEffectiveOk returns a tuple with the Effective field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffective

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetEffective(v GrowthProjectSendingScheduleCampaignsInnerEffective)`

SetEffective sets Effective field to given value.


### GetName

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetName(v string)`

SetName sets Name field to given value.


### GetPlayId

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetPlayId() string`

GetPlayId returns the PlayId field if non-nil, zero value otherwise.

### GetPlayIdOk

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetPlayIdOk() (*string, bool)`

GetPlayIdOk returns a tuple with the PlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayId

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetPlayId(v string)`

SetPlayId sets PlayId field to given value.


### GetRows

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetRows() []GrowthProjectSendingScheduleCampaignsInnerRowsInner`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetRowsOk() (*[]GrowthProjectSendingScheduleCampaignsInnerRowsInner, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetRows(v []GrowthProjectSendingScheduleCampaignsInnerRowsInner)`

SetRows sets Rows field to given value.


### GetSchedule

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetSchedule() CreateGrowthPlaySendingSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetSchedule(v CreateGrowthPlaySendingSchedule)`

SetSchedule sets Schedule field to given value.


### SetScheduleNil

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetScheduleNil(b bool)`

 SetScheduleNil sets the value for Schedule to be an explicit nil

### UnsetSchedule
`func (o *GrowthProjectSendingScheduleCampaignsInner) UnsetSchedule()`

UnsetSchedule ensures that no value is present for Schedule, not even an explicit nil
### GetSource

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *GrowthProjectSendingScheduleCampaignsInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *GrowthProjectSendingScheduleCampaignsInner) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


