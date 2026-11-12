# CreditsState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balance** | [**NullableCreditsStateBalance**](CreditsStateBalance.md) |  |
**BillingMode** | **string** |  |
**FreeReworkRounds** | **int32** |  |
**FrontierMaxEffort** | **string** |  |
**TaskCredits** | [**CreditsStateTaskCredits**](CreditsStateTaskCredits.md) |  |

## Methods

### NewCreditsState

`func NewCreditsState(balance NullableCreditsStateBalance, billingMode string, freeReworkRounds int32, frontierMaxEffort string, taskCredits CreditsStateTaskCredits, ) *CreditsState`

NewCreditsState instantiates a new CreditsState object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreditsStateWithDefaults

`func NewCreditsStateWithDefaults() *CreditsState`

NewCreditsStateWithDefaults instantiates a new CreditsState object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBalance

`func (o *CreditsState) GetBalance() CreditsStateBalance`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *CreditsState) GetBalanceOk() (*CreditsStateBalance, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *CreditsState) SetBalance(v CreditsStateBalance)`

SetBalance sets Balance field to given value.


### SetBalanceNil

`func (o *CreditsState) SetBalanceNil(b bool)`

 SetBalanceNil sets the value for Balance to be an explicit nil

### UnsetBalance
`func (o *CreditsState) UnsetBalance()`

UnsetBalance ensures that no value is present for Balance, not even an explicit nil
### GetBillingMode

`func (o *CreditsState) GetBillingMode() string`

GetBillingMode returns the BillingMode field if non-nil, zero value otherwise.

### GetBillingModeOk

`func (o *CreditsState) GetBillingModeOk() (*string, bool)`

GetBillingModeOk returns a tuple with the BillingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMode

`func (o *CreditsState) SetBillingMode(v string)`

SetBillingMode sets BillingMode field to given value.


### GetFreeReworkRounds

`func (o *CreditsState) GetFreeReworkRounds() int32`

GetFreeReworkRounds returns the FreeReworkRounds field if non-nil, zero value otherwise.

### GetFreeReworkRoundsOk

`func (o *CreditsState) GetFreeReworkRoundsOk() (*int32, bool)`

GetFreeReworkRoundsOk returns a tuple with the FreeReworkRounds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeReworkRounds

`func (o *CreditsState) SetFreeReworkRounds(v int32)`

SetFreeReworkRounds sets FreeReworkRounds field to given value.


### GetFrontierMaxEffort

`func (o *CreditsState) GetFrontierMaxEffort() string`

GetFrontierMaxEffort returns the FrontierMaxEffort field if non-nil, zero value otherwise.

### GetFrontierMaxEffortOk

`func (o *CreditsState) GetFrontierMaxEffortOk() (*string, bool)`

GetFrontierMaxEffortOk returns a tuple with the FrontierMaxEffort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrontierMaxEffort

`func (o *CreditsState) SetFrontierMaxEffort(v string)`

SetFrontierMaxEffort sets FrontierMaxEffort field to given value.


### GetTaskCredits

`func (o *CreditsState) GetTaskCredits() CreditsStateTaskCredits`

GetTaskCredits returns the TaskCredits field if non-nil, zero value otherwise.

### GetTaskCreditsOk

`func (o *CreditsState) GetTaskCreditsOk() (*CreditsStateTaskCredits, bool)`

GetTaskCreditsOk returns a tuple with the TaskCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskCredits

`func (o *CreditsState) SetTaskCredits(v CreditsStateTaskCredits)`

SetTaskCredits sets TaskCredits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


