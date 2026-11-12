# AlertRoute

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

### NewAlertRoute

`func NewAlertRoute(enabled bool, health string, kinds []string, lastError NullableString, lastErrorAt NullableString, provider string, slackChannelId NullableString, slackChannelName NullableString, slackChannelPrivate bool, slackTeamId NullableString, updatedAt NullableString, ) *AlertRoute`

NewAlertRoute instantiates a new AlertRoute object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAlertRouteWithDefaults

`func NewAlertRouteWithDefaults() *AlertRoute`

NewAlertRouteWithDefaults instantiates a new AlertRoute object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetEnabled

`func (o *AlertRoute) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AlertRoute) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AlertRoute) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetHealth

`func (o *AlertRoute) GetHealth() string`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *AlertRoute) GetHealthOk() (*string, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *AlertRoute) SetHealth(v string)`

SetHealth sets Health field to given value.


### GetKinds

`func (o *AlertRoute) GetKinds() []string`

GetKinds returns the Kinds field if non-nil, zero value otherwise.

### GetKindsOk

`func (o *AlertRoute) GetKindsOk() (*[]string, bool)`

GetKindsOk returns a tuple with the Kinds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKinds

`func (o *AlertRoute) SetKinds(v []string)`

SetKinds sets Kinds field to given value.


### GetLastError

`func (o *AlertRoute) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *AlertRoute) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *AlertRoute) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *AlertRoute) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *AlertRoute) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetLastErrorAt

`func (o *AlertRoute) GetLastErrorAt() string`

GetLastErrorAt returns the LastErrorAt field if non-nil, zero value otherwise.

### GetLastErrorAtOk

`func (o *AlertRoute) GetLastErrorAtOk() (*string, bool)`

GetLastErrorAtOk returns a tuple with the LastErrorAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastErrorAt

`func (o *AlertRoute) SetLastErrorAt(v string)`

SetLastErrorAt sets LastErrorAt field to given value.


### SetLastErrorAtNil

`func (o *AlertRoute) SetLastErrorAtNil(b bool)`

 SetLastErrorAtNil sets the value for LastErrorAt to be an explicit nil

### UnsetLastErrorAt
`func (o *AlertRoute) UnsetLastErrorAt()`

UnsetLastErrorAt ensures that no value is present for LastErrorAt, not even an explicit nil
### GetProvider

`func (o *AlertRoute) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AlertRoute) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AlertRoute) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetSlackChannelId

`func (o *AlertRoute) GetSlackChannelId() string`

GetSlackChannelId returns the SlackChannelId field if non-nil, zero value otherwise.

### GetSlackChannelIdOk

`func (o *AlertRoute) GetSlackChannelIdOk() (*string, bool)`

GetSlackChannelIdOk returns a tuple with the SlackChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelId

`func (o *AlertRoute) SetSlackChannelId(v string)`

SetSlackChannelId sets SlackChannelId field to given value.


### SetSlackChannelIdNil

`func (o *AlertRoute) SetSlackChannelIdNil(b bool)`

 SetSlackChannelIdNil sets the value for SlackChannelId to be an explicit nil

### UnsetSlackChannelId
`func (o *AlertRoute) UnsetSlackChannelId()`

UnsetSlackChannelId ensures that no value is present for SlackChannelId, not even an explicit nil
### GetSlackChannelName

`func (o *AlertRoute) GetSlackChannelName() string`

GetSlackChannelName returns the SlackChannelName field if non-nil, zero value otherwise.

### GetSlackChannelNameOk

`func (o *AlertRoute) GetSlackChannelNameOk() (*string, bool)`

GetSlackChannelNameOk returns a tuple with the SlackChannelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelName

`func (o *AlertRoute) SetSlackChannelName(v string)`

SetSlackChannelName sets SlackChannelName field to given value.


### SetSlackChannelNameNil

`func (o *AlertRoute) SetSlackChannelNameNil(b bool)`

 SetSlackChannelNameNil sets the value for SlackChannelName to be an explicit nil

### UnsetSlackChannelName
`func (o *AlertRoute) UnsetSlackChannelName()`

UnsetSlackChannelName ensures that no value is present for SlackChannelName, not even an explicit nil
### GetSlackChannelPrivate

`func (o *AlertRoute) GetSlackChannelPrivate() bool`

GetSlackChannelPrivate returns the SlackChannelPrivate field if non-nil, zero value otherwise.

### GetSlackChannelPrivateOk

`func (o *AlertRoute) GetSlackChannelPrivateOk() (*bool, bool)`

GetSlackChannelPrivateOk returns a tuple with the SlackChannelPrivate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackChannelPrivate

`func (o *AlertRoute) SetSlackChannelPrivate(v bool)`

SetSlackChannelPrivate sets SlackChannelPrivate field to given value.


### GetSlackTeamId

`func (o *AlertRoute) GetSlackTeamId() string`

GetSlackTeamId returns the SlackTeamId field if non-nil, zero value otherwise.

### GetSlackTeamIdOk

`func (o *AlertRoute) GetSlackTeamIdOk() (*string, bool)`

GetSlackTeamIdOk returns a tuple with the SlackTeamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlackTeamId

`func (o *AlertRoute) SetSlackTeamId(v string)`

SetSlackTeamId sets SlackTeamId field to given value.


### SetSlackTeamIdNil

`func (o *AlertRoute) SetSlackTeamIdNil(b bool)`

 SetSlackTeamIdNil sets the value for SlackTeamId to be an explicit nil

### UnsetSlackTeamId
`func (o *AlertRoute) UnsetSlackTeamId()`

UnsetSlackTeamId ensures that no value is present for SlackTeamId, not even an explicit nil
### GetUpdatedAt

`func (o *AlertRoute) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AlertRoute) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AlertRoute) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *AlertRoute) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *AlertRoute) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


