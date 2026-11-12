# UpdateGrowthSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BookingUrl** | Pointer to **NullableString** |  | [optional]
**CountrySendingOverrides** | Pointer to [**map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue**](CreateGrowthPlaySendingScheduleCountryOverridesValue.md) |  | [optional]
**FollowUpDays** | Pointer to **[]interface{}** |  | [optional]
**MailboxDailyMax** | Pointer to **NullableInt32** |  | [optional]
**MonthlyCapMicros** | Pointer to **NullableInt64** |  | [optional]
**SendDays** | Pointer to **[]int32** |  | [optional]
**SendEndHour** | Pointer to **int32** |  | [optional]
**SendStartHour** | Pointer to **int32** |  | [optional]
**StopOnReply** | Pointer to **bool** |  | [optional]
**TimeZone** | Pointer to **NullableString** |  | [optional]

## Methods

### NewUpdateGrowthSettings

`func NewUpdateGrowthSettings() *UpdateGrowthSettings`

NewUpdateGrowthSettings instantiates a new UpdateGrowthSettings object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpdateGrowthSettingsWithDefaults

`func NewUpdateGrowthSettingsWithDefaults() *UpdateGrowthSettings`

NewUpdateGrowthSettingsWithDefaults instantiates a new UpdateGrowthSettings object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBookingUrl

`func (o *UpdateGrowthSettings) GetBookingUrl() string`

GetBookingUrl returns the BookingUrl field if non-nil, zero value otherwise.

### GetBookingUrlOk

`func (o *UpdateGrowthSettings) GetBookingUrlOk() (*string, bool)`

GetBookingUrlOk returns a tuple with the BookingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBookingUrl

`func (o *UpdateGrowthSettings) SetBookingUrl(v string)`

SetBookingUrl sets BookingUrl field to given value.

### HasBookingUrl

`func (o *UpdateGrowthSettings) HasBookingUrl() bool`

HasBookingUrl returns a boolean if a field has been set.

### SetBookingUrlNil

`func (o *UpdateGrowthSettings) SetBookingUrlNil(b bool)`

 SetBookingUrlNil sets the value for BookingUrl to be an explicit nil

### UnsetBookingUrl
`func (o *UpdateGrowthSettings) UnsetBookingUrl()`

UnsetBookingUrl ensures that no value is present for BookingUrl, not even an explicit nil
### GetCountrySendingOverrides

`func (o *UpdateGrowthSettings) GetCountrySendingOverrides() map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue`

GetCountrySendingOverrides returns the CountrySendingOverrides field if non-nil, zero value otherwise.

### GetCountrySendingOverridesOk

`func (o *UpdateGrowthSettings) GetCountrySendingOverridesOk() (*map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue, bool)`

GetCountrySendingOverridesOk returns a tuple with the CountrySendingOverrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountrySendingOverrides

`func (o *UpdateGrowthSettings) SetCountrySendingOverrides(v map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue)`

SetCountrySendingOverrides sets CountrySendingOverrides field to given value.

### HasCountrySendingOverrides

`func (o *UpdateGrowthSettings) HasCountrySendingOverrides() bool`

HasCountrySendingOverrides returns a boolean if a field has been set.

### GetFollowUpDays

`func (o *UpdateGrowthSettings) GetFollowUpDays() []interface{}`

GetFollowUpDays returns the FollowUpDays field if non-nil, zero value otherwise.

### GetFollowUpDaysOk

`func (o *UpdateGrowthSettings) GetFollowUpDaysOk() (*[]interface{}, bool)`

GetFollowUpDaysOk returns a tuple with the FollowUpDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowUpDays

`func (o *UpdateGrowthSettings) SetFollowUpDays(v []interface{})`

SetFollowUpDays sets FollowUpDays field to given value.

### HasFollowUpDays

`func (o *UpdateGrowthSettings) HasFollowUpDays() bool`

HasFollowUpDays returns a boolean if a field has been set.

### GetMailboxDailyMax

`func (o *UpdateGrowthSettings) GetMailboxDailyMax() int32`

GetMailboxDailyMax returns the MailboxDailyMax field if non-nil, zero value otherwise.

### GetMailboxDailyMaxOk

`func (o *UpdateGrowthSettings) GetMailboxDailyMaxOk() (*int32, bool)`

GetMailboxDailyMaxOk returns a tuple with the MailboxDailyMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxDailyMax

`func (o *UpdateGrowthSettings) SetMailboxDailyMax(v int32)`

SetMailboxDailyMax sets MailboxDailyMax field to given value.

### HasMailboxDailyMax

`func (o *UpdateGrowthSettings) HasMailboxDailyMax() bool`

HasMailboxDailyMax returns a boolean if a field has been set.

### SetMailboxDailyMaxNil

`func (o *UpdateGrowthSettings) SetMailboxDailyMaxNil(b bool)`

 SetMailboxDailyMaxNil sets the value for MailboxDailyMax to be an explicit nil

### UnsetMailboxDailyMax
`func (o *UpdateGrowthSettings) UnsetMailboxDailyMax()`

UnsetMailboxDailyMax ensures that no value is present for MailboxDailyMax, not even an explicit nil
### GetMonthlyCapMicros

`func (o *UpdateGrowthSettings) GetMonthlyCapMicros() int64`

GetMonthlyCapMicros returns the MonthlyCapMicros field if non-nil, zero value otherwise.

### GetMonthlyCapMicrosOk

`func (o *UpdateGrowthSettings) GetMonthlyCapMicrosOk() (*int64, bool)`

GetMonthlyCapMicrosOk returns a tuple with the MonthlyCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyCapMicros

`func (o *UpdateGrowthSettings) SetMonthlyCapMicros(v int64)`

SetMonthlyCapMicros sets MonthlyCapMicros field to given value.

### HasMonthlyCapMicros

`func (o *UpdateGrowthSettings) HasMonthlyCapMicros() bool`

HasMonthlyCapMicros returns a boolean if a field has been set.

### SetMonthlyCapMicrosNil

`func (o *UpdateGrowthSettings) SetMonthlyCapMicrosNil(b bool)`

 SetMonthlyCapMicrosNil sets the value for MonthlyCapMicros to be an explicit nil

### UnsetMonthlyCapMicros
`func (o *UpdateGrowthSettings) UnsetMonthlyCapMicros()`

UnsetMonthlyCapMicros ensures that no value is present for MonthlyCapMicros, not even an explicit nil
### GetSendDays

`func (o *UpdateGrowthSettings) GetSendDays() []int32`

GetSendDays returns the SendDays field if non-nil, zero value otherwise.

### GetSendDaysOk

`func (o *UpdateGrowthSettings) GetSendDaysOk() (*[]int32, bool)`

GetSendDaysOk returns a tuple with the SendDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendDays

`func (o *UpdateGrowthSettings) SetSendDays(v []int32)`

SetSendDays sets SendDays field to given value.

### HasSendDays

`func (o *UpdateGrowthSettings) HasSendDays() bool`

HasSendDays returns a boolean if a field has been set.

### SetSendDaysNil

`func (o *UpdateGrowthSettings) SetSendDaysNil(b bool)`

 SetSendDaysNil sets the value for SendDays to be an explicit nil

### UnsetSendDays
`func (o *UpdateGrowthSettings) UnsetSendDays()`

UnsetSendDays ensures that no value is present for SendDays, not even an explicit nil
### GetSendEndHour

`func (o *UpdateGrowthSettings) GetSendEndHour() int32`

GetSendEndHour returns the SendEndHour field if non-nil, zero value otherwise.

### GetSendEndHourOk

`func (o *UpdateGrowthSettings) GetSendEndHourOk() (*int32, bool)`

GetSendEndHourOk returns a tuple with the SendEndHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendEndHour

`func (o *UpdateGrowthSettings) SetSendEndHour(v int32)`

SetSendEndHour sets SendEndHour field to given value.

### HasSendEndHour

`func (o *UpdateGrowthSettings) HasSendEndHour() bool`

HasSendEndHour returns a boolean if a field has been set.

### GetSendStartHour

`func (o *UpdateGrowthSettings) GetSendStartHour() int32`

GetSendStartHour returns the SendStartHour field if non-nil, zero value otherwise.

### GetSendStartHourOk

`func (o *UpdateGrowthSettings) GetSendStartHourOk() (*int32, bool)`

GetSendStartHourOk returns a tuple with the SendStartHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendStartHour

`func (o *UpdateGrowthSettings) SetSendStartHour(v int32)`

SetSendStartHour sets SendStartHour field to given value.

### HasSendStartHour

`func (o *UpdateGrowthSettings) HasSendStartHour() bool`

HasSendStartHour returns a boolean if a field has been set.

### GetStopOnReply

`func (o *UpdateGrowthSettings) GetStopOnReply() bool`

GetStopOnReply returns the StopOnReply field if non-nil, zero value otherwise.

### GetStopOnReplyOk

`func (o *UpdateGrowthSettings) GetStopOnReplyOk() (*bool, bool)`

GetStopOnReplyOk returns a tuple with the StopOnReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnReply

`func (o *UpdateGrowthSettings) SetStopOnReply(v bool)`

SetStopOnReply sets StopOnReply field to given value.

### HasStopOnReply

`func (o *UpdateGrowthSettings) HasStopOnReply() bool`

HasStopOnReply returns a boolean if a field has been set.

### GetTimeZone

`func (o *UpdateGrowthSettings) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *UpdateGrowthSettings) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *UpdateGrowthSettings) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.

### HasTimeZone

`func (o *UpdateGrowthSettings) HasTimeZone() bool`

HasTimeZone returns a boolean if a field has been set.

### SetTimeZoneNil

`func (o *UpdateGrowthSettings) SetTimeZoneNil(b bool)`

 SetTimeZoneNil sets the value for TimeZone to be an explicit nil

### UnsetTimeZone
`func (o *UpdateGrowthSettings) UnsetTimeZone()`

UnsetTimeZone ensures that no value is present for TimeZone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


