# ManagedMailboxResourceList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ManagedMailboxOrderResourcesInner**](ManagedMailboxOrderResourcesInner.md) |  | 
**NextCursor** | **NullableString** |  | 

## Methods

### NewManagedMailboxResourceList

`func NewManagedMailboxResourceList(items []ManagedMailboxOrderResourcesInner, nextCursor NullableString, ) *ManagedMailboxResourceList`

NewManagedMailboxResourceList instantiates a new ManagedMailboxResourceList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxResourceListWithDefaults

`func NewManagedMailboxResourceListWithDefaults() *ManagedMailboxResourceList`

NewManagedMailboxResourceListWithDefaults instantiates a new ManagedMailboxResourceList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *ManagedMailboxResourceList) GetItems() []ManagedMailboxOrderResourcesInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ManagedMailboxResourceList) GetItemsOk() (*[]ManagedMailboxOrderResourcesInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ManagedMailboxResourceList) SetItems(v []ManagedMailboxOrderResourcesInner)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *ManagedMailboxResourceList) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ManagedMailboxResourceList) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ManagedMailboxResourceList) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *ManagedMailboxResourceList) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ManagedMailboxResourceList) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


