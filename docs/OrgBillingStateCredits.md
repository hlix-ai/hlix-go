# OrgBillingStateCredits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **NullableFloat32** |  | 
**Balance** | **NullableFloat32** |  | 
**FreeTasks** | [**NullableOrgBillingStateCreditsFreeTasks**](OrgBillingStateCreditsFreeTasks.md) |  | 
**Held** | **float32** |  | 
**Unsent** | **float32** |  | 

## Methods

### NewOrgBillingStateCredits

`func NewOrgBillingStateCredits(available NullableFloat32, balance NullableFloat32, freeTasks NullableOrgBillingStateCreditsFreeTasks, held float32, unsent float32, ) *OrgBillingStateCredits`

NewOrgBillingStateCredits instantiates a new OrgBillingStateCredits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrgBillingStateCreditsWithDefaults

`func NewOrgBillingStateCreditsWithDefaults() *OrgBillingStateCredits`

NewOrgBillingStateCreditsWithDefaults instantiates a new OrgBillingStateCredits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *OrgBillingStateCredits) GetAvailable() float32`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *OrgBillingStateCredits) GetAvailableOk() (*float32, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *OrgBillingStateCredits) SetAvailable(v float32)`

SetAvailable sets Available field to given value.


### SetAvailableNil

`func (o *OrgBillingStateCredits) SetAvailableNil(b bool)`

 SetAvailableNil sets the value for Available to be an explicit nil

### UnsetAvailable
`func (o *OrgBillingStateCredits) UnsetAvailable()`

UnsetAvailable ensures that no value is present for Available, not even an explicit nil
### GetBalance

`func (o *OrgBillingStateCredits) GetBalance() float32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *OrgBillingStateCredits) GetBalanceOk() (*float32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *OrgBillingStateCredits) SetBalance(v float32)`

SetBalance sets Balance field to given value.


### SetBalanceNil

`func (o *OrgBillingStateCredits) SetBalanceNil(b bool)`

 SetBalanceNil sets the value for Balance to be an explicit nil

### UnsetBalance
`func (o *OrgBillingStateCredits) UnsetBalance()`

UnsetBalance ensures that no value is present for Balance, not even an explicit nil
### GetFreeTasks

`func (o *OrgBillingStateCredits) GetFreeTasks() OrgBillingStateCreditsFreeTasks`

GetFreeTasks returns the FreeTasks field if non-nil, zero value otherwise.

### GetFreeTasksOk

`func (o *OrgBillingStateCredits) GetFreeTasksOk() (*OrgBillingStateCreditsFreeTasks, bool)`

GetFreeTasksOk returns a tuple with the FreeTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeTasks

`func (o *OrgBillingStateCredits) SetFreeTasks(v OrgBillingStateCreditsFreeTasks)`

SetFreeTasks sets FreeTasks field to given value.


### SetFreeTasksNil

`func (o *OrgBillingStateCredits) SetFreeTasksNil(b bool)`

 SetFreeTasksNil sets the value for FreeTasks to be an explicit nil

### UnsetFreeTasks
`func (o *OrgBillingStateCredits) UnsetFreeTasks()`

UnsetFreeTasks ensures that no value is present for FreeTasks, not even an explicit nil
### GetHeld

`func (o *OrgBillingStateCredits) GetHeld() float32`

GetHeld returns the Held field if non-nil, zero value otherwise.

### GetHeldOk

`func (o *OrgBillingStateCredits) GetHeldOk() (*float32, bool)`

GetHeldOk returns a tuple with the Held field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeld

`func (o *OrgBillingStateCredits) SetHeld(v float32)`

SetHeld sets Held field to given value.


### GetUnsent

`func (o *OrgBillingStateCredits) GetUnsent() float32`

GetUnsent returns the Unsent field if non-nil, zero value otherwise.

### GetUnsentOk

`func (o *OrgBillingStateCredits) GetUnsentOk() (*float32, bool)`

GetUnsentOk returns a tuple with the Unsent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsent

`func (o *OrgBillingStateCredits) SetUnsent(v float32)`

SetUnsent sets Unsent field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


