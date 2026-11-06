# AlertSettingsTelegram

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Chats** | [**[]AlertSettingsTelegramChatsInner**](AlertSettingsTelegramChatsInner.md) |  | 
**Route** | [**NullableAlertSettingsSlackRoute**](AlertSettingsSlackRoute.md) |  | 

## Methods

### NewAlertSettingsTelegram

`func NewAlertSettingsTelegram(chats []AlertSettingsTelegramChatsInner, route NullableAlertSettingsSlackRoute, ) *AlertSettingsTelegram`

NewAlertSettingsTelegram instantiates a new AlertSettingsTelegram object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertSettingsTelegramWithDefaults

`func NewAlertSettingsTelegramWithDefaults() *AlertSettingsTelegram`

NewAlertSettingsTelegramWithDefaults instantiates a new AlertSettingsTelegram object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChats

`func (o *AlertSettingsTelegram) GetChats() []AlertSettingsTelegramChatsInner`

GetChats returns the Chats field if non-nil, zero value otherwise.

### GetChatsOk

`func (o *AlertSettingsTelegram) GetChatsOk() (*[]AlertSettingsTelegramChatsInner, bool)`

GetChatsOk returns a tuple with the Chats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChats

`func (o *AlertSettingsTelegram) SetChats(v []AlertSettingsTelegramChatsInner)`

SetChats sets Chats field to given value.


### GetRoute

`func (o *AlertSettingsTelegram) GetRoute() AlertSettingsSlackRoute`

GetRoute returns the Route field if non-nil, zero value otherwise.

### GetRouteOk

`func (o *AlertSettingsTelegram) GetRouteOk() (*AlertSettingsSlackRoute, bool)`

GetRouteOk returns a tuple with the Route field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoute

`func (o *AlertSettingsTelegram) SetRoute(v AlertSettingsSlackRoute)`

SetRoute sets Route field to given value.


### SetRouteNil

`func (o *AlertSettingsTelegram) SetRouteNil(b bool)`

 SetRouteNil sets the value for Route to be an explicit nil

### UnsetRoute
`func (o *AlertSettingsTelegram) UnsetRoute()`

UnsetRoute ensures that no value is present for Route, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


