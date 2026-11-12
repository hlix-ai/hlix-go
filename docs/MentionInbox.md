# MentionInbox

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]MentionInboxItemsInner**](MentionInboxItemsInner.md) |  |
**Total** | **int32** |  |
**Truncated** | **bool** |  |

## Methods

### NewMentionInbox

`func NewMentionInbox(items []MentionInboxItemsInner, total int32, truncated bool, ) *MentionInbox`

NewMentionInbox instantiates a new MentionInbox object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMentionInboxWithDefaults

`func NewMentionInboxWithDefaults() *MentionInbox`

NewMentionInboxWithDefaults instantiates a new MentionInbox object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetItems

`func (o *MentionInbox) GetItems() []MentionInboxItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *MentionInbox) GetItemsOk() (*[]MentionInboxItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *MentionInbox) SetItems(v []MentionInboxItemsInner)`

SetItems sets Items field to given value.


### GetTotal

`func (o *MentionInbox) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *MentionInbox) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *MentionInbox) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetTruncated

`func (o *MentionInbox) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *MentionInbox) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *MentionInbox) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


