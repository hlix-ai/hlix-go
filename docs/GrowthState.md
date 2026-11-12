# GrowthState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Brain** | [**NullableGrowthStateBrain**](GrowthStateBrain.md) |  |
**Campaigns** | [**[]GrowthStateCampaignsInner**](GrowthStateCampaignsInner.md) |  |
**DroppedFacts** | **NullableInt32** |  |
**LastRun** | [**NullableGrowthStateLastRun**](GrowthStateLastRun.md) |  |
**LeadList** | [**GrowthStateLeadList**](GrowthStateLeadList.md) |  |
**Project** | [**GrowthProjectCreatedProject**](GrowthProjectCreatedProject.md) |  |
**Reach** | [**map[string]GrowthStateReachValue**](GrowthStateReachValue.md) |  |
**WebsiteUrl** | **NullableString** |  |

## Methods

### NewGrowthState

`func NewGrowthState(brain NullableGrowthStateBrain, campaigns []GrowthStateCampaignsInner, droppedFacts NullableInt32, lastRun NullableGrowthStateLastRun, leadList GrowthStateLeadList, project GrowthProjectCreatedProject, reach map[string]GrowthStateReachValue, websiteUrl NullableString, ) *GrowthState`

NewGrowthState instantiates a new GrowthState object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthStateWithDefaults

`func NewGrowthStateWithDefaults() *GrowthState`

NewGrowthStateWithDefaults instantiates a new GrowthState object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBrain

`func (o *GrowthState) GetBrain() GrowthStateBrain`

GetBrain returns the Brain field if non-nil, zero value otherwise.

### GetBrainOk

`func (o *GrowthState) GetBrainOk() (*GrowthStateBrain, bool)`

GetBrainOk returns a tuple with the Brain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrain

`func (o *GrowthState) SetBrain(v GrowthStateBrain)`

SetBrain sets Brain field to given value.


### SetBrainNil

`func (o *GrowthState) SetBrainNil(b bool)`

 SetBrainNil sets the value for Brain to be an explicit nil

### UnsetBrain
`func (o *GrowthState) UnsetBrain()`

UnsetBrain ensures that no value is present for Brain, not even an explicit nil
### GetCampaigns

`func (o *GrowthState) GetCampaigns() []GrowthStateCampaignsInner`

GetCampaigns returns the Campaigns field if non-nil, zero value otherwise.

### GetCampaignsOk

`func (o *GrowthState) GetCampaignsOk() (*[]GrowthStateCampaignsInner, bool)`

GetCampaignsOk returns a tuple with the Campaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaigns

`func (o *GrowthState) SetCampaigns(v []GrowthStateCampaignsInner)`

SetCampaigns sets Campaigns field to given value.


### GetDroppedFacts

`func (o *GrowthState) GetDroppedFacts() int32`

GetDroppedFacts returns the DroppedFacts field if non-nil, zero value otherwise.

### GetDroppedFactsOk

`func (o *GrowthState) GetDroppedFactsOk() (*int32, bool)`

GetDroppedFactsOk returns a tuple with the DroppedFacts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDroppedFacts

`func (o *GrowthState) SetDroppedFacts(v int32)`

SetDroppedFacts sets DroppedFacts field to given value.


### SetDroppedFactsNil

`func (o *GrowthState) SetDroppedFactsNil(b bool)`

 SetDroppedFactsNil sets the value for DroppedFacts to be an explicit nil

### UnsetDroppedFacts
`func (o *GrowthState) UnsetDroppedFacts()`

UnsetDroppedFacts ensures that no value is present for DroppedFacts, not even an explicit nil
### GetLastRun

`func (o *GrowthState) GetLastRun() GrowthStateLastRun`

GetLastRun returns the LastRun field if non-nil, zero value otherwise.

### GetLastRunOk

`func (o *GrowthState) GetLastRunOk() (*GrowthStateLastRun, bool)`

GetLastRunOk returns a tuple with the LastRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRun

`func (o *GrowthState) SetLastRun(v GrowthStateLastRun)`

SetLastRun sets LastRun field to given value.


### SetLastRunNil

`func (o *GrowthState) SetLastRunNil(b bool)`

 SetLastRunNil sets the value for LastRun to be an explicit nil

### UnsetLastRun
`func (o *GrowthState) UnsetLastRun()`

UnsetLastRun ensures that no value is present for LastRun, not even an explicit nil
### GetLeadList

`func (o *GrowthState) GetLeadList() GrowthStateLeadList`

GetLeadList returns the LeadList field if non-nil, zero value otherwise.

### GetLeadListOk

`func (o *GrowthState) GetLeadListOk() (*GrowthStateLeadList, bool)`

GetLeadListOk returns a tuple with the LeadList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadList

`func (o *GrowthState) SetLeadList(v GrowthStateLeadList)`

SetLeadList sets LeadList field to given value.


### GetProject

`func (o *GrowthState) GetProject() GrowthProjectCreatedProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *GrowthState) GetProjectOk() (*GrowthProjectCreatedProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *GrowthState) SetProject(v GrowthProjectCreatedProject)`

SetProject sets Project field to given value.


### GetReach

`func (o *GrowthState) GetReach() map[string]GrowthStateReachValue`

GetReach returns the Reach field if non-nil, zero value otherwise.

### GetReachOk

`func (o *GrowthState) GetReachOk() (*map[string]GrowthStateReachValue, bool)`

GetReachOk returns a tuple with the Reach field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReach

`func (o *GrowthState) SetReach(v map[string]GrowthStateReachValue)`

SetReach sets Reach field to given value.


### GetWebsiteUrl

`func (o *GrowthState) GetWebsiteUrl() string`

GetWebsiteUrl returns the WebsiteUrl field if non-nil, zero value otherwise.

### GetWebsiteUrlOk

`func (o *GrowthState) GetWebsiteUrlOk() (*string, bool)`

GetWebsiteUrlOk returns a tuple with the WebsiteUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsiteUrl

`func (o *GrowthState) SetWebsiteUrl(v string)`

SetWebsiteUrl sets WebsiteUrl field to given value.


### SetWebsiteUrlNil

`func (o *GrowthState) SetWebsiteUrlNil(b bool)`

 SetWebsiteUrlNil sets the value for WebsiteUrl to be an explicit nil

### UnsetWebsiteUrl
`func (o *GrowthState) UnsetWebsiteUrl()`

UnsetWebsiteUrl ensures that no value is present for WebsiteUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


