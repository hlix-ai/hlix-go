# ManagedMailboxOrderList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ManagedMailboxOrderListItemsInner**](ManagedMailboxOrderListItemsInner.md) |  |
**NextCursor** | **NullableString** |  |

## Methods

### NewManagedMailboxOrderList

`func NewManagedMailboxOrderList(items []ManagedMailboxOrderListItemsInner, nextCursor NullableString, ) *ManagedMailboxOrderList`

NewManagedMailboxOrderList instantiates a new ManagedMailboxOrderList object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewManagedMailboxOrderListWithDefaults

`func NewManagedMailboxOrderListWithDefaults() *ManagedMailboxOrderList`

NewManagedMailboxOrderListWithDefaults instantiates a new ManagedMailboxOrderList object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetItems

`func (o *ManagedMailboxOrderList) GetItems() []ManagedMailboxOrderListItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ManagedMailboxOrderList) GetItemsOk() (*[]ManagedMailboxOrderListItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ManagedMailboxOrderList) SetItems(v []ManagedMailboxOrderListItemsInner)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *ManagedMailboxOrderList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ManagedMailboxOrderList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ManagedMailboxOrderList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *ManagedMailboxOrderList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ManagedMailboxOrderList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


