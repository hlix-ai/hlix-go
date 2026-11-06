# GrowthSettingsState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SendingScheduleRows** | [**[]GrowthProjectSendingScheduleCampaignsInnerRowsInner**](GrowthProjectSendingScheduleCampaignsInnerRowsInner.md) |  | 
**Settings** | [**GrowthSettingsStateSettings**](GrowthSettingsStateSettings.md) |  | 
**Spend** | [**GrowthSettingsStateSpend**](GrowthSettingsStateSpend.md) |  | 

## Methods

### NewGrowthSettingsState

`func NewGrowthSettingsState(sendingScheduleRows []GrowthProjectSendingScheduleCampaignsInnerRowsInner, settings GrowthSettingsStateSettings, spend GrowthSettingsStateSpend, ) *GrowthSettingsState`

NewGrowthSettingsState instantiates a new GrowthSettingsState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthSettingsStateWithDefaults

`func NewGrowthSettingsStateWithDefaults() *GrowthSettingsState`

NewGrowthSettingsStateWithDefaults instantiates a new GrowthSettingsState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSendingScheduleRows

`func (o *GrowthSettingsState) GetSendingScheduleRows() []GrowthProjectSendingScheduleCampaignsInnerRowsInner`

GetSendingScheduleRows returns the SendingScheduleRows field if non-nil, zero value otherwise.

### GetSendingScheduleRowsOk

`func (o *GrowthSettingsState) GetSendingScheduleRowsOk() (*[]GrowthProjectSendingScheduleCampaignsInnerRowsInner, bool)`

GetSendingScheduleRowsOk returns a tuple with the SendingScheduleRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendingScheduleRows

`func (o *GrowthSettingsState) SetSendingScheduleRows(v []GrowthProjectSendingScheduleCampaignsInnerRowsInner)`

SetSendingScheduleRows sets SendingScheduleRows field to given value.


### GetSettings

`func (o *GrowthSettingsState) GetSettings() GrowthSettingsStateSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *GrowthSettingsState) GetSettingsOk() (*GrowthSettingsStateSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *GrowthSettingsState) SetSettings(v GrowthSettingsStateSettings)`

SetSettings sets Settings field to given value.


### GetSpend

`func (o *GrowthSettingsState) GetSpend() GrowthSettingsStateSpend`

GetSpend returns the Spend field if non-nil, zero value otherwise.

### GetSpendOk

`func (o *GrowthSettingsState) GetSpendOk() (*GrowthSettingsStateSpend, bool)`

GetSpendOk returns a tuple with the Spend field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpend

`func (o *GrowthSettingsState) SetSpend(v GrowthSettingsStateSpend)`

SetSpend sets Spend field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


