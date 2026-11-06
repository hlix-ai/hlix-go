# AlertSettingsSlackRoute

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**Health** | **string** |  | 
**Kinds** | **[]string** |  | 
**LastError** | **NullableString** |  | 
**LastErrorAt** | **NullableString** |  | 
**Provider** | **string** |  | 
**SlackChannelId** | **NullableString** |  | 
**SlackChannelName** | **NullableString** |  | 
**SlackChannelPrivate** | **bool** |  | 
**SlackTeamId** | **NullableString** |  | 
**UpdatedAt** | **NullableString** |  | 

## Methods

### NewAlertSettingsSlackRoute

`func NewAlertSettingsSlackRoute(enabled bool, health string, kinds []string, lastError NullableString, lastErrorAt NullableString, provider string, slackChannelId NullableString, slackChannelName NullableString, slackChannelPrivate bool, slackTeamId NullableString, updatedAt NullableString, ) *AlertSettingsSlackRoute`

NewAlertSettingsSlackRoute instantiates a new AlertSettingsSlackRoute object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertSettingsSlackRouteWithDefaults

`func NewAlertSettingsSlackRouteWithDefaults() *AlertSettingsSlackRoute`

NewAlertSettingsSlackRouteWithDefaults instantiates a new AlertSettingsSlackRoute object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *AlertSettingsSlackRoute) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AlertSettingsSlackRoute) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AlertSettingsSlackRoute) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetHealth

`func (o *AlertSettingsSlackRoute) GetHealth() string`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *AlertSettingsSlackRoute) GetHealthOk() (*string, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *AlertSettingsSlackRoute) SetHealth(v string)`

SetHealth sets Health field to given value.


### GetKinds

`func (o *AlertSettingsSlackRoute) GetKinds() []string`

GetKinds returns the Kinds field if non-nil, zero value otherwise.

### GetKindsOk

`func (o *AlertSettingsSlackRoute) GetKindsOk() (*[]string, bool)`

GetKindsOk returns a tuple with the Kinds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinds

`func (o *AlertSettingsSlackRoute) SetKinds(v []string)`

SetKinds sets Kinds field to given value.


### GetLastError

`func (o *AlertSettingsSlackRoute) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *AlertSettingsSlackRoute) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *AlertSettingsSlackRoute) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *AlertSettingsSlackRoute) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *AlertSettingsSlackRoute) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetLastErrorAt

`func (o *AlertSettingsSlackRoute) GetLastErrorAt() string`

GetLastErrorAt returns the LastErrorAt field if non-nil, zero value otherwise.

### GetLastErrorAtOk

`func (o *AlertSettingsSlackRoute) GetLastErrorAtOk() (*string, bool)`

GetLastErrorAtOk returns a tuple with the LastErrorAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorAt

`func (o *AlertSettingsSlackRoute) SetLastErrorAt(v string)`

SetLastErrorAt sets LastErrorAt field to given value.


### SetLastErrorAtNil

`func (o *AlertSettingsSlackRoute) SetLastErrorAtNil(b bool)`

 SetLastErrorAtNil sets the value for LastErrorAt to be an explicit nil

### UnsetLastErrorAt
`func (o *AlertSettingsSlackRoute) UnsetLastErrorAt()`

UnsetLastErrorAt ensures that no value is present for LastErrorAt, not even an explicit nil
### GetProvider

`func (o *AlertSettingsSlackRoute) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AlertSettingsSlackRoute) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AlertSettingsSlackRoute) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetSlackChannelId

`func (o *AlertSettingsSlackRoute) GetSlackChannelId() string`

GetSlackChannelId returns the SlackChannelId field if non-nil, zero value otherwise.

### GetSlackChannelIdOk

`func (o *AlertSettingsSlackRoute) GetSlackChannelIdOk() (*string, bool)`

GetSlackChannelIdOk returns a tuple with the SlackChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelId

`func (o *AlertSettingsSlackRoute) SetSlackChannelId(v string)`

SetSlackChannelId sets SlackChannelId field to given value.


### SetSlackChannelIdNil

`func (o *AlertSettingsSlackRoute) SetSlackChannelIdNil(b bool)`

 SetSlackChannelIdNil sets the value for SlackChannelId to be an explicit nil

### UnsetSlackChannelId
`func (o *AlertSettingsSlackRoute) UnsetSlackChannelId()`

UnsetSlackChannelId ensures that no value is present for SlackChannelId, not even an explicit nil
### GetSlackChannelName

`func (o *AlertSettingsSlackRoute) GetSlackChannelName() string`

GetSlackChannelName returns the SlackChannelName field if non-nil, zero value otherwise.

### GetSlackChannelNameOk

`func (o *AlertSettingsSlackRoute) GetSlackChannelNameOk() (*string, bool)`

GetSlackChannelNameOk returns a tuple with the SlackChannelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelName

`func (o *AlertSettingsSlackRoute) SetSlackChannelName(v string)`

SetSlackChannelName sets SlackChannelName field to given value.


### SetSlackChannelNameNil

`func (o *AlertSettingsSlackRoute) SetSlackChannelNameNil(b bool)`

 SetSlackChannelNameNil sets the value for SlackChannelName to be an explicit nil

### UnsetSlackChannelName
`func (o *AlertSettingsSlackRoute) UnsetSlackChannelName()`

UnsetSlackChannelName ensures that no value is present for SlackChannelName, not even an explicit nil
### GetSlackChannelPrivate

`func (o *AlertSettingsSlackRoute) GetSlackChannelPrivate() bool`

GetSlackChannelPrivate returns the SlackChannelPrivate field if non-nil, zero value otherwise.

### GetSlackChannelPrivateOk

`func (o *AlertSettingsSlackRoute) GetSlackChannelPrivateOk() (*bool, bool)`

GetSlackChannelPrivateOk returns a tuple with the SlackChannelPrivate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelPrivate

`func (o *AlertSettingsSlackRoute) SetSlackChannelPrivate(v bool)`

SetSlackChannelPrivate sets SlackChannelPrivate field to given value.


### GetSlackTeamId

`func (o *AlertSettingsSlackRoute) GetSlackTeamId() string`

GetSlackTeamId returns the SlackTeamId field if non-nil, zero value otherwise.

### GetSlackTeamIdOk

`func (o *AlertSettingsSlackRoute) GetSlackTeamIdOk() (*string, bool)`

GetSlackTeamIdOk returns a tuple with the SlackTeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackTeamId

`func (o *AlertSettingsSlackRoute) SetSlackTeamId(v string)`

SetSlackTeamId sets SlackTeamId field to given value.


### SetSlackTeamIdNil

`func (o *AlertSettingsSlackRoute) SetSlackTeamIdNil(b bool)`

 SetSlackTeamIdNil sets the value for SlackTeamId to be an explicit nil

### UnsetSlackTeamId
`func (o *AlertSettingsSlackRoute) UnsetSlackTeamId()`

UnsetSlackTeamId ensures that no value is present for SlackTeamId, not even an explicit nil
### GetUpdatedAt

`func (o *AlertSettingsSlackRoute) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AlertSettingsSlackRoute) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AlertSettingsSlackRoute) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *AlertSettingsSlackRoute) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *AlertSettingsSlackRoute) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


