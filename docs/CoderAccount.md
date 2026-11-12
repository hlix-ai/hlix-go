# CoderAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseUrl** | **NullableString** |  |
**Coder** | **string** |  |
**CreatedAt** | **string** |  |
**Enabled** | **bool** |  |
**ExpiresAt** | **NullableString** |  |
**Hint** | **NullableString** |  |
**Id** | **string** |  |
**InUse** | **bool** |  |
**Kind** | **string** |  |
**Label** | **string** |  |
**LastUsedAt** | **NullableString** |  |
**LimitedUntil** | **NullableString** |  |
**OwnerUserId** | **NullableString** |  |
**Shared** | **bool** |  |
**Status** | **string** |  |
**UpdatedAt** | **string** |  |
**Usage** | [**NullableCoderAccountUsage**](CoderAccountUsage.md) |  |

## Methods

### NewCoderAccount

`func NewCoderAccount(baseUrl NullableString, coder string, createdAt string, enabled bool, expiresAt NullableString, hint NullableString, id string, inUse bool, kind string, label string, lastUsedAt NullableString, limitedUntil NullableString, ownerUserId NullableString, shared bool, status string, updatedAt string, usage NullableCoderAccountUsage, ) *CoderAccount`

NewCoderAccount instantiates a new CoderAccount object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCoderAccountWithDefaults

`func NewCoderAccountWithDefaults() *CoderAccount`

NewCoderAccountWithDefaults instantiates a new CoderAccount object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBaseUrl

`func (o *CoderAccount) GetBaseUrl() string`

GetBaseUrl returns the BaseUrl field if non-nil, zero value otherwise.

### GetBaseUrlOk

`func (o *CoderAccount) GetBaseUrlOk() (*string, bool)`

GetBaseUrlOk returns a tuple with the BaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseUrl

`func (o *CoderAccount) SetBaseUrl(v string)`

SetBaseUrl sets BaseUrl field to given value.


### SetBaseUrlNil

`func (o *CoderAccount) SetBaseUrlNil(b bool)`

 SetBaseUrlNil sets the value for BaseUrl to be an explicit nil

### UnsetBaseUrl
`func (o *CoderAccount) UnsetBaseUrl()`

UnsetBaseUrl ensures that no value is present for BaseUrl, not even an explicit nil
### GetCoder

`func (o *CoderAccount) GetCoder() string`

GetCoder returns the Coder field if non-nil, zero value otherwise.

### GetCoderOk

`func (o *CoderAccount) GetCoderOk() (*string, bool)`

GetCoderOk returns a tuple with the Coder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoder

`func (o *CoderAccount) SetCoder(v string)`

SetCoder sets Coder field to given value.


### GetCreatedAt

`func (o *CoderAccount) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CoderAccount) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CoderAccount) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEnabled

`func (o *CoderAccount) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CoderAccount) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CoderAccount) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetExpiresAt

`func (o *CoderAccount) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CoderAccount) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CoderAccount) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *CoderAccount) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CoderAccount) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetHint

`func (o *CoderAccount) GetHint() string`

GetHint returns the Hint field if non-nil, zero value otherwise.

### GetHintOk

`func (o *CoderAccount) GetHintOk() (*string, bool)`

GetHintOk returns a tuple with the Hint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHint

`func (o *CoderAccount) SetHint(v string)`

SetHint sets Hint field to given value.


### SetHintNil

`func (o *CoderAccount) SetHintNil(b bool)`

 SetHintNil sets the value for Hint to be an explicit nil

### UnsetHint
`func (o *CoderAccount) UnsetHint()`

UnsetHint ensures that no value is present for Hint, not even an explicit nil
### GetId

`func (o *CoderAccount) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CoderAccount) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CoderAccount) SetId(v string)`

SetId sets Id field to given value.


### GetInUse

`func (o *CoderAccount) GetInUse() bool`

GetInUse returns the InUse field if non-nil, zero value otherwise.

### GetInUseOk

`func (o *CoderAccount) GetInUseOk() (*bool, bool)`

GetInUseOk returns a tuple with the InUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInUse

`func (o *CoderAccount) SetInUse(v bool)`

SetInUse sets InUse field to given value.


### GetKind

`func (o *CoderAccount) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CoderAccount) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CoderAccount) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLabel

`func (o *CoderAccount) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CoderAccount) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CoderAccount) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetLastUsedAt

`func (o *CoderAccount) GetLastUsedAt() string`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *CoderAccount) GetLastUsedAtOk() (*string, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *CoderAccount) SetLastUsedAt(v string)`

SetLastUsedAt sets LastUsedAt field to given value.


### SetLastUsedAtNil

`func (o *CoderAccount) SetLastUsedAtNil(b bool)`

 SetLastUsedAtNil sets the value for LastUsedAt to be an explicit nil

### UnsetLastUsedAt
`func (o *CoderAccount) UnsetLastUsedAt()`

UnsetLastUsedAt ensures that no value is present for LastUsedAt, not even an explicit nil
### GetLimitedUntil

`func (o *CoderAccount) GetLimitedUntil() string`

GetLimitedUntil returns the LimitedUntil field if non-nil, zero value otherwise.

### GetLimitedUntilOk

`func (o *CoderAccount) GetLimitedUntilOk() (*string, bool)`

GetLimitedUntilOk returns a tuple with the LimitedUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitedUntil

`func (o *CoderAccount) SetLimitedUntil(v string)`

SetLimitedUntil sets LimitedUntil field to given value.


### SetLimitedUntilNil

`func (o *CoderAccount) SetLimitedUntilNil(b bool)`

 SetLimitedUntilNil sets the value for LimitedUntil to be an explicit nil

### UnsetLimitedUntil
`func (o *CoderAccount) UnsetLimitedUntil()`

UnsetLimitedUntil ensures that no value is present for LimitedUntil, not even an explicit nil
### GetOwnerUserId

`func (o *CoderAccount) GetOwnerUserId() string`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *CoderAccount) GetOwnerUserIdOk() (*string, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *CoderAccount) SetOwnerUserId(v string)`

SetOwnerUserId sets OwnerUserId field to given value.


### SetOwnerUserIdNil

`func (o *CoderAccount) SetOwnerUserIdNil(b bool)`

 SetOwnerUserIdNil sets the value for OwnerUserId to be an explicit nil

### UnsetOwnerUserId
`func (o *CoderAccount) UnsetOwnerUserId()`

UnsetOwnerUserId ensures that no value is present for OwnerUserId, not even an explicit nil
### GetShared

`func (o *CoderAccount) GetShared() bool`

GetShared returns the Shared field if non-nil, zero value otherwise.

### GetSharedOk

`func (o *CoderAccount) GetSharedOk() (*bool, bool)`

GetSharedOk returns a tuple with the Shared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShared

`func (o *CoderAccount) SetShared(v bool)`

SetShared sets Shared field to given value.


### GetStatus

`func (o *CoderAccount) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CoderAccount) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CoderAccount) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *CoderAccount) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CoderAccount) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CoderAccount) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUsage

`func (o *CoderAccount) GetUsage() CoderAccountUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CoderAccount) GetUsageOk() (*CoderAccountUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CoderAccount) SetUsage(v CoderAccountUsage)`

SetUsage sets Usage field to given value.


### SetUsageNil

`func (o *CoderAccount) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *CoderAccount) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


