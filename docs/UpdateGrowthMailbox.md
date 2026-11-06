# UpdateGrowthMailbox

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DailyLimit** | Pointer to **int32** |  | [optional] 
**RampStartedAt** | Pointer to **time.Time** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewUpdateGrowthMailbox

`func NewUpdateGrowthMailbox() *UpdateGrowthMailbox`

NewUpdateGrowthMailbox instantiates a new UpdateGrowthMailbox object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateGrowthMailboxWithDefaults

`func NewUpdateGrowthMailboxWithDefaults() *UpdateGrowthMailbox`

NewUpdateGrowthMailboxWithDefaults instantiates a new UpdateGrowthMailbox object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDailyLimit

`func (o *UpdateGrowthMailbox) GetDailyLimit() int32`

GetDailyLimit returns the DailyLimit field if non-nil, zero value otherwise.

### GetDailyLimitOk

`func (o *UpdateGrowthMailbox) GetDailyLimitOk() (*int32, bool)`

GetDailyLimitOk returns a tuple with the DailyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyLimit

`func (o *UpdateGrowthMailbox) SetDailyLimit(v int32)`

SetDailyLimit sets DailyLimit field to given value.

### HasDailyLimit

`func (o *UpdateGrowthMailbox) HasDailyLimit() bool`

HasDailyLimit returns a boolean if a field has been set.

### GetRampStartedAt

`func (o *UpdateGrowthMailbox) GetRampStartedAt() time.Time`

GetRampStartedAt returns the RampStartedAt field if non-nil, zero value otherwise.

### GetRampStartedAtOk

`func (o *UpdateGrowthMailbox) GetRampStartedAtOk() (*time.Time, bool)`

GetRampStartedAtOk returns a tuple with the RampStartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRampStartedAt

`func (o *UpdateGrowthMailbox) SetRampStartedAt(v time.Time)`

SetRampStartedAt sets RampStartedAt field to given value.

### HasRampStartedAt

`func (o *UpdateGrowthMailbox) HasRampStartedAt() bool`

HasRampStartedAt returns a boolean if a field has been set.

### GetStatus

`func (o *UpdateGrowthMailbox) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateGrowthMailbox) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateGrowthMailbox) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateGrowthMailbox) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


