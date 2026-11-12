# RestoreCustomerAccess

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Grants** | Pointer to [**[]InviteWorkspacePortalProjectGrantsInner**](InviteWorkspacePortalProjectGrantsInner.md) |  | [optional]
**Seat** | **bool** |  |

## Methods

### NewRestoreCustomerAccess

`func NewRestoreCustomerAccess(seat bool, ) *RestoreCustomerAccess`

NewRestoreCustomerAccess instantiates a new RestoreCustomerAccess object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewRestoreCustomerAccessWithDefaults

`func NewRestoreCustomerAccessWithDefaults() *RestoreCustomerAccess`

NewRestoreCustomerAccessWithDefaults instantiates a new RestoreCustomerAccess object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGrants

`func (o *RestoreCustomerAccess) GetGrants() []InviteWorkspacePortalProjectGrantsInner`

GetGrants returns the Grants field if non-nil, zero value otherwise.

### GetGrantsOk

`func (o *RestoreCustomerAccess) GetGrantsOk() (*[]InviteWorkspacePortalProjectGrantsInner, bool)`

GetGrantsOk returns a tuple with the Grants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrants

`func (o *RestoreCustomerAccess) SetGrants(v []InviteWorkspacePortalProjectGrantsInner)`

SetGrants sets Grants field to given value.

### HasGrants

`func (o *RestoreCustomerAccess) HasGrants() bool`

HasGrants returns a boolean if a field has been set.

### GetSeat

`func (o *RestoreCustomerAccess) GetSeat() bool`

GetSeat returns the Seat field if non-nil, zero value otherwise.

### GetSeatOk

`func (o *RestoreCustomerAccess) GetSeatOk() (*bool, bool)`

GetSeatOk returns a tuple with the Seat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeat

`func (o *RestoreCustomerAccess) SetSeat(v bool)`

SetSeat sets Seat field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


