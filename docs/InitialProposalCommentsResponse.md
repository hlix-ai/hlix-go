# InitialProposalCommentsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]InitialProposalCommentsResponseItemsInner**](InitialProposalCommentsResponseItemsInner.md) |  |
**NextCursor** | [**NullableInitialProposalCommentsResponseNextCursor**](InitialProposalCommentsResponseNextCursor.md) |  |

## Methods

### NewInitialProposalCommentsResponse

`func NewInitialProposalCommentsResponse(items []InitialProposalCommentsResponseItemsInner, nextCursor NullableInitialProposalCommentsResponseNextCursor, ) *InitialProposalCommentsResponse`

NewInitialProposalCommentsResponse instantiates a new InitialProposalCommentsResponse object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewInitialProposalCommentsResponseWithDefaults

`func NewInitialProposalCommentsResponseWithDefaults() *InitialProposalCommentsResponse`

NewInitialProposalCommentsResponseWithDefaults instantiates a new InitialProposalCommentsResponse object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetItems

`func (o *InitialProposalCommentsResponse) GetItems() []InitialProposalCommentsResponseItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *InitialProposalCommentsResponse) GetItemsOk() (*[]InitialProposalCommentsResponseItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *InitialProposalCommentsResponse) SetItems(v []InitialProposalCommentsResponseItemsInner)`

SetItems sets Items field to given value.


### GetNextCursor

`func (o *InitialProposalCommentsResponse) GetNextCursor() InitialProposalCommentsResponseNextCursor`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *InitialProposalCommentsResponse) GetNextCursorOk() (*InitialProposalCommentsResponseNextCursor, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *InitialProposalCommentsResponse) SetNextCursor(v InitialProposalCommentsResponseNextCursor)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *InitialProposalCommentsResponse) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *InitialProposalCommentsResponse) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


