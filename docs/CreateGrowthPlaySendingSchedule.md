# CreateGrowthPlaySendingSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountryOverrides** | [**map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue**](CreateGrowthPlaySendingScheduleCountryOverridesValue.md) |  |
**SendDays** | **[]int32** |  |
**SendEndHour** | **int32** |  |
**SendStartHour** | **int32** |  |
**TimeZone** | **NullableString** |  |

## Methods

### NewCreateGrowthPlaySendingSchedule

`func NewCreateGrowthPlaySendingSchedule(countryOverrides map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue, sendDays []int32, sendEndHour int32, sendStartHour int32, timeZone NullableString, ) *CreateGrowthPlaySendingSchedule`

NewCreateGrowthPlaySendingSchedule instantiates a new CreateGrowthPlaySendingSchedule object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateGrowthPlaySendingScheduleWithDefaults

`func NewCreateGrowthPlaySendingScheduleWithDefaults() *CreateGrowthPlaySendingSchedule`

NewCreateGrowthPlaySendingScheduleWithDefaults instantiates a new CreateGrowthPlaySendingSchedule object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCountryOverrides

`func (o *CreateGrowthPlaySendingSchedule) GetCountryOverrides() map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue`

GetCountryOverrides returns the CountryOverrides field if non-nil, zero value otherwise.

### GetCountryOverridesOk

`func (o *CreateGrowthPlaySendingSchedule) GetCountryOverridesOk() (*map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue, bool)`

GetCountryOverridesOk returns a tuple with the CountryOverrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryOverrides

`func (o *CreateGrowthPlaySendingSchedule) SetCountryOverrides(v map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue)`

SetCountryOverrides sets CountryOverrides field to given value.


### GetSendDays

`func (o *CreateGrowthPlaySendingSchedule) GetSendDays() []int32`

GetSendDays returns the SendDays field if non-nil, zero value otherwise.

### GetSendDaysOk

`func (o *CreateGrowthPlaySendingSchedule) GetSendDaysOk() (*[]int32, bool)`

GetSendDaysOk returns a tuple with the SendDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendDays

`func (o *CreateGrowthPlaySendingSchedule) SetSendDays(v []int32)`

SetSendDays sets SendDays field to given value.


### SetSendDaysNil

`func (o *CreateGrowthPlaySendingSchedule) SetSendDaysNil(b bool)`

 SetSendDaysNil sets the value for SendDays to be an explicit nil

### UnsetSendDays
`func (o *CreateGrowthPlaySendingSchedule) UnsetSendDays()`

UnsetSendDays ensures that no value is present for SendDays, not even an explicit nil
### GetSendEndHour

`func (o *CreateGrowthPlaySendingSchedule) GetSendEndHour() int32`

GetSendEndHour returns the SendEndHour field if non-nil, zero value otherwise.

### GetSendEndHourOk

`func (o *CreateGrowthPlaySendingSchedule) GetSendEndHourOk() (*int32, bool)`

GetSendEndHourOk returns a tuple with the SendEndHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendEndHour

`func (o *CreateGrowthPlaySendingSchedule) SetSendEndHour(v int32)`

SetSendEndHour sets SendEndHour field to given value.


### GetSendStartHour

`func (o *CreateGrowthPlaySendingSchedule) GetSendStartHour() int32`

GetSendStartHour returns the SendStartHour field if non-nil, zero value otherwise.

### GetSendStartHourOk

`func (o *CreateGrowthPlaySendingSchedule) GetSendStartHourOk() (*int32, bool)`

GetSendStartHourOk returns a tuple with the SendStartHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendStartHour

`func (o *CreateGrowthPlaySendingSchedule) SetSendStartHour(v int32)`

SetSendStartHour sets SendStartHour field to given value.


### GetTimeZone

`func (o *CreateGrowthPlaySendingSchedule) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *CreateGrowthPlaySendingSchedule) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *CreateGrowthPlaySendingSchedule) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.


### SetTimeZoneNil

`func (o *CreateGrowthPlaySendingSchedule) SetTimeZoneNil(b bool)`

 SetTimeZoneNil sets the value for TimeZone to be an explicit nil

### UnsetTimeZone
`func (o *CreateGrowthPlaySendingSchedule) UnsetTimeZone()`

UnsetTimeZone ensures that no value is present for TimeZone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


