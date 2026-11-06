# AlertSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Slack** | [**AlertSettingsSlack**](AlertSettingsSlack.md) |  | 
**Telegram** | [**AlertSettingsTelegram**](AlertSettingsTelegram.md) |  | 

## Methods

### NewAlertSettings

`func NewAlertSettings(slack AlertSettingsSlack, telegram AlertSettingsTelegram, ) *AlertSettings`

NewAlertSettings instantiates a new AlertSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertSettingsWithDefaults

`func NewAlertSettingsWithDefaults() *AlertSettings`

NewAlertSettingsWithDefaults instantiates a new AlertSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSlack

`func (o *AlertSettings) GetSlack() AlertSettingsSlack`

GetSlack returns the Slack field if non-nil, zero value otherwise.

### GetSlackOk

`func (o *AlertSettings) GetSlackOk() (*AlertSettingsSlack, bool)`

GetSlackOk returns a tuple with the Slack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlack

`func (o *AlertSettings) SetSlack(v AlertSettingsSlack)`

SetSlack sets Slack field to given value.


### GetTelegram

`func (o *AlertSettings) GetTelegram() AlertSettingsTelegram`

GetTelegram returns the Telegram field if non-nil, zero value otherwise.

### GetTelegramOk

`func (o *AlertSettings) GetTelegramOk() (*AlertSettingsTelegram, bool)`

GetTelegramOk returns a tuple with the Telegram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelegram

`func (o *AlertSettings) SetTelegram(v AlertSettingsTelegram)`

SetTelegram sets Telegram field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


