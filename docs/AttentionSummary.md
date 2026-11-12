# AttentionSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CountsByKind** | [**AttentionSummaryCountsByKind**](AttentionSummaryCountsByKind.md) |  |
**Items** | [**[]AttentionSummaryItemsInner**](AttentionSummaryItemsInner.md) |  |
**Total** | **int32** |  |
**Truncated** | **bool** |  |

## Methods

### NewAttentionSummary

`func NewAttentionSummary(countsByKind AttentionSummaryCountsByKind, items []AttentionSummaryItemsInner, total int32, truncated bool, ) *AttentionSummary`

NewAttentionSummary instantiates a new AttentionSummary object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAttentionSummaryWithDefaults

`func NewAttentionSummaryWithDefaults() *AttentionSummary`

NewAttentionSummaryWithDefaults instantiates a new AttentionSummary object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCountsByKind

`func (o *AttentionSummary) GetCountsByKind() AttentionSummaryCountsByKind`

GetCountsByKind returns the CountsByKind field if non-nil, zero value otherwise.

### GetCountsByKindOk

`func (o *AttentionSummary) GetCountsByKindOk() (*AttentionSummaryCountsByKind, bool)`

GetCountsByKindOk returns a tuple with the CountsByKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountsByKind

`func (o *AttentionSummary) SetCountsByKind(v AttentionSummaryCountsByKind)`

SetCountsByKind sets CountsByKind field to given value.


### GetItems

`func (o *AttentionSummary) GetItems() []AttentionSummaryItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *AttentionSummary) GetItemsOk() (*[]AttentionSummaryItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *AttentionSummary) SetItems(v []AttentionSummaryItemsInner)`

SetItems sets Items field to given value.


### GetTotal

`func (o *AttentionSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AttentionSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AttentionSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetTruncated

`func (o *AttentionSummary) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *AttentionSummary) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *AttentionSummary) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


