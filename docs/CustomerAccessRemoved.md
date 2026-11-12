# CustomerAccessRemoved

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Grants** | [**[]CustomerAccessRemovedGrantsInner**](CustomerAccessRemovedGrantsInner.md) |  |
**Seat** | **bool** |  |

## Methods

### NewCustomerAccessRemoved

`func NewCustomerAccessRemoved(grants []CustomerAccessRemovedGrantsInner, seat bool, ) *CustomerAccessRemoved`

NewCustomerAccessRemoved instantiates a new CustomerAccessRemoved object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCustomerAccessRemovedWithDefaults

`func NewCustomerAccessRemovedWithDefaults() *CustomerAccessRemoved`

NewCustomerAccessRemovedWithDefaults instantiates a new CustomerAccessRemoved object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGrants

`func (o *CustomerAccessRemoved) GetGrants() []CustomerAccessRemovedGrantsInner`

GetGrants returns the Grants field if non-nil, zero value otherwise.

### GetGrantsOk

`func (o *CustomerAccessRemoved) GetGrantsOk() (*[]CustomerAccessRemovedGrantsInner, bool)`

GetGrantsOk returns a tuple with the Grants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrants

`func (o *CustomerAccessRemoved) SetGrants(v []CustomerAccessRemovedGrantsInner)`

SetGrants sets Grants field to given value.


### GetSeat

`func (o *CustomerAccessRemoved) GetSeat() bool`

GetSeat returns the Seat field if non-nil, zero value otherwise.

### GetSeatOk

`func (o *CustomerAccessRemoved) GetSeatOk() (*bool, bool)`

GetSeatOk returns a tuple with the Seat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeat

`func (o *CustomerAccessRemoved) SetSeat(v bool)`

SetSeat sets Seat field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


