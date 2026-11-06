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
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBonusActionsWithDefaults

`func NewBonusActionsWithDefaults() *BonusActions`

NewBonusActionsWithDefaults instantiates a new BonusActions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


