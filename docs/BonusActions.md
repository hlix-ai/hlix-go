# BonusActions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | [**[]BonusActionsActionsInner**](BonusActionsActionsInner.md) |  |
**PerActionMicros** | **int64** |  |

## Methods

### NewBonusActions

`func NewBonusActions(actions []BonusActionsActionsInner, perActionMicros int64, ) *BonusActions`

NewBonusActions instantiates a new BonusActions object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewBonusActionsWithDefaults

`func NewBonusActionsWithDefaults() *BonusActions`

NewBonusActionsWithDefaults instantiates a new BonusActions object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetActions

`func (o *BonusActions) GetActions() []BonusActionsActionsInner`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *BonusActions) GetActionsOk() (*[]BonusActionsActionsInner, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *BonusActions) SetActions(v []BonusActionsActionsInner)`

SetActions sets Actions field to given value.


### GetPerActionMicros

`func (o *BonusActions) GetPerActionMicros() int64`

GetPerActionMicros returns the PerActionMicros field if non-nil, zero value otherwise.

### GetPerActionMicrosOk

`func (o *BonusActions) GetPerActionMicrosOk() (*int64, bool)`

GetPerActionMicrosOk returns a tuple with the PerActionMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerActionMicros

`func (o *BonusActions) SetPerActionMicros(v int64)`

SetPerActionMicros sets PerActionMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


