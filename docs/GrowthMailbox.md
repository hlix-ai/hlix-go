# GrowthMailbox

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **string** |  |
**AllowanceToday** | **int32** |  |
**CreatedAt** | **string** |  |
**DailyLimit** | **int32** |  |
**Id** | **string** |  |
**LastError** | **NullableString** |  |
**Provider** | **string** |  |
**RampStartedAt** | **NullableString** |  |
**SentToday** | **int32** |  |
**Status** | **string** |  |

## Methods

### NewGrowthMailbox

`func NewGrowthMailbox(address string, allowanceToday int32, createdAt string, dailyLimit int32, id string, lastError NullableString, provider string, rampStartedAt NullableString, sentToday int32, status string, ) *GrowthMailbox`

NewGrowthMailbox instantiates a new GrowthMailbox object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthMailboxWithDefaults

`func NewGrowthMailboxWithDefaults() *GrowthMailbox`

NewGrowthMailboxWithDefaults instantiates a new GrowthMailbox object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAddress

`func (o *GrowthMailbox) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *GrowthMailbox) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *GrowthMailbox) SetAddress(v string)`

SetAddress sets Address field to given value.


### GetAllowanceToday

`func (o *GrowthMailbox) GetAllowanceToday() int32`

GetAllowanceToday returns the AllowanceToday field if non-nil, zero value otherwise.

### GetAllowanceTodayOk

`func (o *GrowthMailbox) GetAllowanceTodayOk() (*int32, bool)`

GetAllowanceTodayOk returns a tuple with the AllowanceToday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowanceToday

`func (o *GrowthMailbox) SetAllowanceToday(v int32)`

SetAllowanceToday sets AllowanceToday field to given value.


### GetCreatedAt

`func (o *GrowthMailbox) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthMailbox) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthMailbox) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDailyLimit

`func (o *GrowthMailbox) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *GrowthMailbox) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *GrowthMailbox) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.


### GetId

`func (o *GrowthMailbox) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthMailbox) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthMailbox) SetId(v string)`

SetId sets Id field to given value.


### GetLastError

`func (o *GrowthMailbox) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *GrowthMailbox) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *GrowthMailbox) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *GrowthMailbox) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *GrowthMailbox) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetProvider

`func (o *GrowthMailbox) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *GrowthMailbox) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *GrowthMailbox) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetRampStartedAt

`func (o *GrowthMailbox) GetRampStartedAt() string`

GetRampStartedAt returns the RampStartedAt field if non-nil, zero value otherwise.

### GetRampStartedAtOk

`func (o *GrowthMailbox) GetRampStartedAtOk() (*string, bool)`

GetRampStartedAtOk returns a tuple with the RampStartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRampStartedAt

`func (o *GrowthMailbox) SetRampStartedAt(v string)`

SetRampStartedAt sets RampStartedAt field to given value.


### SetRampStartedAtNil

`func (o *GrowthMailbox) SetRampStartedAtNil(b bool)`

 SetRampStartedAtNil sets the value for RampStartedAt to be an explicit nil

### UnsetRampStartedAt
`func (o *GrowthMailbox) UnsetRampStartedAt()`

UnsetRampStartedAt ensures that no value is present for RampStartedAt, not even an explicit nil
### GetSentToday

`func (o *GrowthMailbox) GetSentToday() int32`

GetSentToday returns the SentToday field if non-nil, zero value otherwise.

### GetSentTodayOk

`func (o *GrowthMailbox) GetSentTodayOk() (*int32, bool)`

GetSentTodayOk returns a tuple with the SentToday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentToday

`func (o *GrowthMailbox) SetSentToday(v int32)`

SetSentToday sets SentToday field to given value.


### GetStatus

`func (o *GrowthMailbox) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthMailbox) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthMailbox) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


