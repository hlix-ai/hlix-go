# UpdateDeal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **NullableString** |  | [optional] 
**ExpectedCloseOn** | Pointer to **NullableString** |  | [optional] 
**LostReason** | Pointer to **string** |  | [optional] 
**NextStep** | Pointer to **NullableString** |  | [optional] 
**NextStepAt** | Pointer to **NullableTime** |  | [optional] 
**OwnerUserId** | Pointer to **NullableString** |  | [optional] 
**Stage** | Pointer to **string** |  | [optional] 
**ValueMicros** | Pointer to **NullableInt64** |  | [optional] 

## Methods

### NewUpdateDeal

`func NewUpdateDeal() *UpdateDeal`

NewUpdateDeal instantiates a new UpdateDeal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDealWithDefaults

`func NewUpdateDealWithDefaults() *UpdateDeal`

NewUpdateDealWithDefaults instantiates a new UpdateDeal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *UpdateDeal) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *UpdateDeal) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *UpdateDeal) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *UpdateDeal) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *UpdateDeal) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *UpdateDeal) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetExpectedCloseOn

`func (o *UpdateDeal) GetExpectedCloseOn() string`

GetExpectedCloseOn returns the ExpectedCloseOn field if non-nil, zero value otherwise.

### GetExpectedCloseOnOk

`func (o *UpdateDeal) GetExpectedCloseOnOk() (*string, bool)`

GetExpectedCloseOnOk returns a tuple with the ExpectedCloseOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedCloseOn

`func (o *UpdateDeal) SetExpectedCloseOn(v string)`

SetExpectedCloseOn sets ExpectedCloseOn field to given value.

### HasExpectedCloseOn

`func (o *UpdateDeal) HasExpectedCloseOn() bool`

HasExpectedCloseOn returns a boolean if a field has been set.

### SetExpectedCloseOnNil

`func (o *UpdateDeal) SetExpectedCloseOnNil(b bool)`

 SetExpectedCloseOnNil sets the value for ExpectedCloseOn to be an explicit nil

### UnsetExpectedCloseOn
`func (o *UpdateDeal) UnsetExpectedCloseOn()`

UnsetExpectedCloseOn ensures that no value is present for ExpectedCloseOn, not even an explicit nil
### GetLostReason

`func (o *UpdateDeal) GetLostReason() string`

GetLostReason returns the LostReason field if non-nil, zero value otherwise.

### GetLostReasonOk

`func (o *UpdateDeal) GetLostReasonOk() (*string, bool)`

GetLostReasonOk returns a tuple with the LostReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLostReason

`func (o *UpdateDeal) SetLostReason(v string)`

SetLostReason sets LostReason field to given value.

### HasLostReason

`func (o *UpdateDeal) HasLostReason() bool`

HasLostReason returns a boolean if a field has been set.

### GetNextStep

`func (o *UpdateDeal) GetNextStep() string`

GetNextStep returns the NextStep field if non-nil, zero value otherwise.

### GetNextStepOk

`func (o *UpdateDeal) GetNextStepOk() (*string, bool)`

GetNextStepOk returns a tuple with the NextStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextStep

`func (o *UpdateDeal) SetNextStep(v string)`

SetNextStep sets NextStep field to given value.

### HasNextStep

`func (o *UpdateDeal) HasNextStep() bool`

HasNextStep returns a boolean if a field has been set.

### SetNextStepNil

`func (o *UpdateDeal) SetNextStepNil(b bool)`

 SetNextStepNil sets the value for NextStep to be an explicit nil

### UnsetNextStep
`func (o *UpdateDeal) UnsetNextStep()`

UnsetNextStep ensures that no value is present for NextStep, not even an explicit nil
### GetNextStepAt

`func (o *UpdateDeal) GetNextStepAt() time.Time`

GetNextStepAt returns the NextStepAt field if non-nil, zero value otherwise.

### GetNextStepAtOk

`func (o *UpdateDeal) GetNextStepAtOk() (*time.Time, bool)`

GetNextStepAtOk returns a tuple with the NextStepAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextStepAt

`func (o *UpdateDeal) SetNextStepAt(v time.Time)`

SetNextStepAt sets NextStepAt field to given value.

### HasNextStepAt

`func (o *UpdateDeal) HasNextStepAt() bool`

HasNextStepAt returns a boolean if a field has been set.

### SetNextStepAtNil

`func (o *UpdateDeal) SetNextStepAtNil(b bool)`

 SetNextStepAtNil sets the value for NextStepAt to be an explicit nil

### UnsetNextStepAt
`func (o *UpdateDeal) UnsetNextStepAt()`

UnsetNextStepAt ensures that no value is present for NextStepAt, not even an explicit nil
### GetOwnerUserId

`func (o *UpdateDeal) GetOwnerUserId() string`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *UpdateDeal) GetOwnerUserIdOk() (*string, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *UpdateDeal) SetOwnerUserId(v string)`

SetOwnerUserId sets OwnerUserId field to given value.

### HasOwnerUserId

`func (o *UpdateDeal) HasOwnerUserId() bool`

HasOwnerUserId returns a boolean if a field has been set.

### SetOwnerUserIdNil

`func (o *UpdateDeal) SetOwnerUserIdNil(b bool)`

 SetOwnerUserIdNil sets the value for OwnerUserId to be an explicit nil

### UnsetOwnerUserId
`func (o *UpdateDeal) UnsetOwnerUserId()`

UnsetOwnerUserId ensures that no value is present for OwnerUserId, not even an explicit nil
### GetStage

`func (o *UpdateDeal) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *UpdateDeal) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *UpdateDeal) SetStage(v string)`

SetStage sets Stage field to given value.

### HasStage

`func (o *UpdateDeal) HasStage() bool`

HasStage returns a boolean if a field has been set.

### GetValueMicros

`func (o *UpdateDeal) GetValueMicros() int64`

GetValueMicros returns the ValueMicros field if non-nil, zero value otherwise.

### GetValueMicrosOk

`func (o *UpdateDeal) GetValueMicrosOk() (*int64, bool)`

GetValueMicrosOk returns a tuple with the ValueMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueMicros

`func (o *UpdateDeal) SetValueMicros(v int64)`

SetValueMicros sets ValueMicros field to given value.

### HasValueMicros

`func (o *UpdateDeal) HasValueMicros() bool`

HasValueMicros returns a boolean if a field has been set.

### SetValueMicrosNil

`func (o *UpdateDeal) SetValueMicrosNil(b bool)`

 SetValueMicrosNil sets the value for ValueMicros to be an explicit nil

### UnsetValueMicros
`func (o *UpdateDeal) UnsetValueMicros()`

UnsetValueMicros ensures that no value is present for ValueMicros, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


