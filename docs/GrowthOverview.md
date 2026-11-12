# GrowthOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Autopilot** | [**GrowthOverviewAutopilot**](GrowthOverviewAutopilot.md) |  |
**Budget** | [**GrowthOverviewBudget**](GrowthOverviewBudget.md) |  |
**CampaignId** | **NullableString** |  |
**Campaigns** | [**[]GrowthOverviewCampaignsInner**](GrowthOverviewCampaignsInner.md) |  |
**Days** | [**[]GrowthOverviewDaysInner**](GrowthOverviewDaysInner.md) |  |
**Previous** | [**GrowthOverviewPrevious**](GrowthOverviewPrevious.md) |  |
**Range** | [**GrowthOverviewRange**](GrowthOverviewRange.md) |  |
**Threads** | [**GrowthOverviewThreads**](GrowthOverviewThreads.md) |  |
**Totals** | [**GrowthOverviewPrevious**](GrowthOverviewPrevious.md) |  |
**UnansweredHotLeads** | **int32** |  |
**Week** | [**GrowthOverviewWeek**](GrowthOverviewWeek.md) |  |

## Methods

### NewGrowthOverview

`func NewGrowthOverview(autopilot GrowthOverviewAutopilot, budget GrowthOverviewBudget, campaignId NullableString, campaigns []GrowthOverviewCampaignsInner, days []GrowthOverviewDaysInner, previous GrowthOverviewPrevious, range_ GrowthOverviewRange, threads GrowthOverviewThreads, totals GrowthOverviewPrevious, unansweredHotLeads int32, week GrowthOverviewWeek, ) *GrowthOverview`

NewGrowthOverview instantiates a new GrowthOverview object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthOverviewWithDefaults

`func NewGrowthOverviewWithDefaults() *GrowthOverview`

NewGrowthOverviewWithDefaults instantiates a new GrowthOverview object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAutopilot

`func (o *GrowthOverview) GetAutopilot() GrowthOverviewAutopilot`

GetAutopilot returns the Autopilot field if non-nil, zero value otherwise.

### GetAutopilotOk

`func (o *GrowthOverview) GetAutopilotOk() (*GrowthOverviewAutopilot, bool)`

GetAutopilotOk returns a tuple with the Autopilot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutopilot

`func (o *GrowthOverview) SetAutopilot(v GrowthOverviewAutopilot)`

SetAutopilot sets Autopilot field to given value.


### GetBudget

`func (o *GrowthOverview) GetBudget() GrowthOverviewBudget`

GetBudget returns the Budget field if non-nil, zero value otherwise.

### GetBudgetOk

`func (o *GrowthOverview) GetBudgetOk() (*GrowthOverviewBudget, bool)`

GetBudgetOk returns a tuple with the Budget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBudget

`func (o *GrowthOverview) SetBudget(v GrowthOverviewBudget)`

SetBudget sets Budget field to given value.


### GetCampaignId

`func (o *GrowthOverview) GetCampaignId() string`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *GrowthOverview) GetCampaignIdOk() (*string, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *GrowthOverview) SetCampaignId(v string)`

SetCampaignId sets CampaignId field to given value.


### SetCampaignIdNil

`func (o *GrowthOverview) SetCampaignIdNil(b bool)`

 SetCampaignIdNil sets the value for CampaignId to be an explicit nil

### UnsetCampaignId
`func (o *GrowthOverview) UnsetCampaignId()`

UnsetCampaignId ensures that no value is present for CampaignId, not even an explicit nil
### GetCampaigns

`func (o *GrowthOverview) GetCampaigns() []GrowthOverviewCampaignsInner`

GetCampaigns returns the Campaigns field if non-nil, zero value otherwise.

### GetCampaignsOk

`func (o *GrowthOverview) GetCampaignsOk() (*[]GrowthOverviewCampaignsInner, bool)`

GetCampaignsOk returns a tuple with the Campaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaigns

`func (o *GrowthOverview) SetCampaigns(v []GrowthOverviewCampaignsInner)`

SetCampaigns sets Campaigns field to given value.


### GetDays

`func (o *GrowthOverview) GetDays() []GrowthOverviewDaysInner`

GetDays returns the Days field if non-nil, zero value otherwise.

### GetDaysOk

`func (o *GrowthOverview) GetDaysOk() (*[]GrowthOverviewDaysInner, bool)`

GetDaysOk returns a tuple with the Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDays

`func (o *GrowthOverview) SetDays(v []GrowthOverviewDaysInner)`

SetDays sets Days field to given value.


### GetPrevious

`func (o *GrowthOverview) GetPrevious() GrowthOverviewPrevious`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *GrowthOverview) GetPreviousOk() (*GrowthOverviewPrevious, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *GrowthOverview) SetPrevious(v GrowthOverviewPrevious)`

SetPrevious sets Previous field to given value.


### GetRange

`func (o *GrowthOverview) GetRange() GrowthOverviewRange`

GetRange returns the Range field if non-nil, zero value otherwise.

### GetRangeOk

`func (o *GrowthOverview) GetRangeOk() (*GrowthOverviewRange, bool)`

GetRangeOk returns a tuple with the Range field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRange

`func (o *GrowthOverview) SetRange(v GrowthOverviewRange)`

SetRange sets Range field to given value.


### GetThreads

`func (o *GrowthOverview) GetThreads() GrowthOverviewThreads`

GetThreads returns the Threads field if non-nil, zero value otherwise.

### GetThreadsOk

`func (o *GrowthOverview) GetThreadsOk() (*GrowthOverviewThreads, bool)`

GetThreadsOk returns a tuple with the Threads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreads

`func (o *GrowthOverview) SetThreads(v GrowthOverviewThreads)`

SetThreads sets Threads field to given value.


### GetTotals

`func (o *GrowthOverview) GetTotals() GrowthOverviewPrevious`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *GrowthOverview) GetTotalsOk() (*GrowthOverviewPrevious, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *GrowthOverview) SetTotals(v GrowthOverviewPrevious)`

SetTotals sets Totals field to given value.


### GetUnansweredHotLeads

`func (o *GrowthOverview) GetUnansweredHotLeads() int32`

GetUnansweredHotLeads returns the UnansweredHotLeads field if non-nil, zero value otherwise.

### GetUnansweredHotLeadsOk

`func (o *GrowthOverview) GetUnansweredHotLeadsOk() (*int32, bool)`

GetUnansweredHotLeadsOk returns a tuple with the UnansweredHotLeads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnansweredHotLeads

`func (o *GrowthOverview) SetUnansweredHotLeads(v int32)`

SetUnansweredHotLeads sets UnansweredHotLeads field to given value.


### GetWeek

`func (o *GrowthOverview) GetWeek() GrowthOverviewWeek`

GetWeek returns the Week field if non-nil, zero value otherwise.

### GetWeekOk

`func (o *GrowthOverview) GetWeekOk() (*GrowthOverviewWeek, bool)`

GetWeekOk returns a tuple with the Week field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeek

`func (o *GrowthOverview) SetWeek(v GrowthOverviewWeek)`

SetWeek sets Week field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


