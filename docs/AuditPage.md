# AuditPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]AuditEntryDetailEntry**](AuditEntryDetailEntry.md) |  |
**NextCursor** | **NullableString** |  |

## Methods

### NewAuditPage

`func NewAuditPage(items []AuditEntryDetailEntry, nextCursor NullableString, ) *AuditPage`

NewAuditPage instantiates a new AuditPage object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAuditPageWithDefaults

`func NewAuditPageWithDefaults() *AuditPage`

NewAuditPageWithDefaults instantiates a new AuditPage object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetItems

`func (o *AuditPage) GetItems() []AuditEntryDetailEntry`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *AuditPage) GetItemsOk() (*[]AuditEntryDetailEntry, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *AuditPage) SetItems(v []AuditEntryDetailEntry)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *AuditPage) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *AuditPage) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *AuditPage) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *AuditPage) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *AuditPage) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


