# GrowthSettingsStateSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BookingUrl** | **NullableString** |  | 
**CountrySendingOverrides** | [**map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue**](CreateGrowthPlaySendingScheduleCountryOverridesValue.md) |  | 
**FollowUpDays** | **[]int32** |  | 
**MailboxDailyMax** | **NullableInt32** |  | 
**MonthlyCapMicros** | **NullableInt64** |  | 
**SendDays** | **[]int32** |  | 
**SendEndHour** | **int32** |  | 
**SendStartHour** | **int32** |  | 
**StopOnReply** | **bool** |  | 
**TimeZone** | **NullableString** |  | 

## Methods

### NewGrowthSettingsStateSettings

`func NewGrowthSettingsStateSettings(bookingUrl NullableString, countrySendingOverrides map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue, followUpDays []int32, mailboxDailyMax NullableInt32, monthlyCapMicros NullableInt64, sendDays []int32, sendEndHour int32, sendStartHour int32, stopOnReply bool, timeZone NullableString, ) *GrowthSettingsStateSettings`

NewGrowthSettingsStateSettings instantiates a new GrowthSettingsStateSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthSettingsStateSettingsWithDefaults

`func NewGrowthSettingsStateSettingsWithDefaults() *GrowthSettingsStateSettings`

NewGrowthSettingsStateSettingsWithDefaults instantiates a new GrowthSettingsStateSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBookingUrl

`func (o *GrowthSettingsStateSettings) GetBookingUrl() string`

GetBookingUrl returns the BookingUrl field if non-nil, zero value otherwise.

### GetBookingUrlOk

`func (o *GrowthSettingsStateSettings) GetBookingUrlOk() (*string, bool)`

GetBookingUrlOk returns a tuple with the BookingUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBookingUrl

`func (o *GrowthSettingsStateSettings) SetBookingUrl(v string)`

SetBookingUrl sets BookingUrl field to given value.


### SetBookingUrlNil

`func (o *GrowthSettingsStateSettings) SetBookingUrlNil(b bool)`

 SetBookingUrlNil sets the value for BookingUrl to be an explicit nil

### UnsetBookingUrl
`func (o *GrowthSettingsStateSettings) UnsetBookingUrl()`

UnsetBookingUrl ensures that no value is present for BookingUrl, not even an explicit nil
### GetCountrySendingOverrides

`func (o *GrowthSettingsStateSettings) GetCountrySendingOverrides() map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue`

GetCountrySendingOverrides returns the CountrySendingOverrides field if non-nil, zero value otherwise.

### GetCountrySendingOverridesOk

`func (o *GrowthSettingsStateSettings) GetCountrySendingOverridesOk() (*map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue, bool)`

GetCountrySendingOverridesOk returns a tuple with the CountrySendingOverrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountrySendingOverrides

`func (o *GrowthSettingsStateSettings) SetCountrySendingOverrides(v map[string]CreateGrowthPlaySendingScheduleCountryOverridesValue)`

SetCountrySendingOverrides sets CountrySendingOverrides field to given value.


### GetFollowUpDays

`func (o *GrowthSettingsStateSettings) GetFollowUpDays() []int32`

GetFollowUpDays returns the FollowUpDays field if non-nil, zero value otherwise.

### GetFollowUpDaysOk

`func (o *GrowthSettingsStateSettings) GetFollowUpDaysOk() (*[]int32, bool)`

GetFollowUpDaysOk returns a tuple with the FollowUpDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowUpDays

`func (o *GrowthSettingsStateSettings) SetFollowUpDays(v []int32)`

SetFollowUpDays sets FollowUpDays field to given value.


### GetMailboxDailyMax

`func (o *GrowthSettingsStateSettings) GetMailboxDailyMax() int32`

GetMailboxDailyMax returns the MailboxDailyMax field if non-nil, zero value otherwise.

### GetMailboxDailyMaxOk

`func (o *GrowthSettingsStateSettings) GetMailboxDailyMaxOk() (*int32, bool)`

GetMailboxDailyMaxOk returns a tuple with the MailboxDailyMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxDailyMax

`func (o *GrowthSettingsStateSettings) SetMailboxDailyMax(v int32)`

SetMailboxDailyMax sets MailboxDailyMax field to given value.


### SetMailboxDailyMaxNil

`func (o *GrowthSettingsStateSettings) SetMailboxDailyMaxNil(b bool)`

 SetMailboxDailyMaxNil sets the value for MailboxDailyMax to be an explicit nil

### UnsetMailboxDailyMax
`func (o *GrowthSettingsStateSettings) UnsetMailboxDailyMax()`

UnsetMailboxDailyMax ensures that no value is present for MailboxDailyMax, not even an explicit nil
### GetMonthlyCapMicros

`func (o *GrowthSettingsStateSettings) GetMonthlyCapMicros() int64`

GetMonthlyCapMicros returns the MonthlyCapMicros field if non-nil, zero value otherwise.

### GetMonthlyCapMicrosOk

`func (o *GrowthSettingsStateSettings) GetMonthlyCapMicrosOk() (*int64, bool)`

GetMonthlyCapMicrosOk returns a tuple with the MonthlyCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyCapMicros

`func (o *GrowthSettingsStateSettings) SetMonthlyCapMicros(v int64)`

SetMonthlyCapMicros sets MonthlyCapMicros field to given value.


### SetMonthlyCapMicrosNil

`func (o *GrowthSettingsStateSettings) SetMonthlyCapMicrosNil(b bool)`

 SetMonthlyCapMicrosNil sets the value for MonthlyCapMicros to be an explicit nil

### UnsetMonthlyCapMicros
`func (o *GrowthSettingsStateSettings) UnsetMonthlyCapMicros()`

UnsetMonthlyCapMicros ensures that no value is present for MonthlyCapMicros, not even an explicit nil
### GetSendDays

`func (o *GrowthSettingsStateSettings) GetSendDays() []int32`

GetSendDays returns the SendDays field if non-nil, zero value otherwise.

### GetSendDaysOk

`func (o *GrowthSettingsStateSettings) GetSendDaysOk() (*[]int32, bool)`

GetSendDaysOk returns a tuple with the SendDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendDays

`func (o *GrowthSettingsStateSettings) SetSendDays(v []int32)`

SetSendDays sets SendDays field to given value.


### SetSendDaysNil

`func (o *GrowthSettingsStateSettings) SetSendDaysNil(b bool)`

 SetSendDaysNil sets the value for SendDays to be an explicit nil

### UnsetSendDays
`func (o *GrowthSettingsStateSettings) UnsetSendDays()`

UnsetSendDays ensures that no value is present for SendDays, not even an explicit nil
### GetSendEndHour

`func (o *GrowthSettingsStateSettings) GetSendEndHour() int32`

GetSendEndHour returns the SendEndHour field if non-nil, zero value otherwise.

### GetSendEndHourOk

`func (o *GrowthSettingsStateSettings) GetSendEndHourOk() (*int32, bool)`

GetSendEndHourOk returns a tuple with the SendEndHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendEndHour

`func (o *GrowthSettingsStateSettings) SetSendEndHour(v int32)`

SetSendEndHour sets SendEndHour field to given value.


### GetSendStartHour

`func (o *GrowthSettingsStateSettings) GetSendStartHour() int32`

GetSendStartHour returns the SendStartHour field if non-nil, zero value otherwise.

### GetSendStartHourOk

`func (o *GrowthSettingsStateSettings) GetSendStartHourOk() (*int32, bool)`

GetSendStartHourOk returns a tuple with the SendStartHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSendStartHour

`func (o *GrowthSettingsStateSettings) SetSendStartHour(v int32)`

SetSendStartHour sets SendStartHour field to given value.


### GetStopOnReply

`func (o *GrowthSettingsStateSettings) GetStopOnReply() bool`

GetStopOnReply returns the StopOnReply field if non-nil, zero value otherwise.

### GetStopOnReplyOk

`func (o *GrowthSettingsStateSettings) GetStopOnReplyOk() (*bool, bool)`

GetStopOnReplyOk returns a tuple with the StopOnReply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopOnReply

`func (o *GrowthSettingsStateSettings) SetStopOnReply(v bool)`

SetStopOnReply sets StopOnReply field to given value.


### GetTimeZone

`func (o *GrowthSettingsStateSettings) GetTimeZone() string`

GetTimeZone returns the TimeZone field if non-nil, zero value otherwise.

### GetTimeZoneOk

`func (o *GrowthSettingsStateSettings) GetTimeZoneOk() (*string, bool)`

GetTimeZoneOk returns a tuple with the TimeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeZone

`func (o *GrowthSettingsStateSettings) SetTimeZone(v string)`

SetTimeZone sets TimeZone field to given value.


### SetTimeZoneNil

`func (o *GrowthSettingsStateSettings) SetTimeZoneNil(b bool)`

 SetTimeZoneNil sets the value for TimeZone to be an explicit nil

### UnsetTimeZone
`func (o *GrowthSettingsStateSettings) UnsetTimeZone()`

UnsetTimeZone ensures that no value is present for TimeZone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


