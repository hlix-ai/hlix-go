# ToolSearchResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tools** | [**[]ToolSearchResultToolsInner**](ToolSearchResultToolsInner.md) |  |
**Total** | **NullableInt32** |  |
**Truncated** | **bool** |  |

## Methods

### NewToolSearchResult

`func NewToolSearchResult(tools []ToolSearchResultToolsInner, total NullableInt32, truncated bool, ) *ToolSearchResult`

NewToolSearchResult instantiates a new ToolSearchResult object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewToolSearchResultWithDefaults

`func NewToolSearchResultWithDefaults() *ToolSearchResult`

NewToolSearchResultWithDefaults instantiates a new ToolSearchResult object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetTools

`func (o *ToolSearchResult) GetTools() []ToolSearchResultToolsInner`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *ToolSearchResult) GetToolsOk() (*[]ToolSearchResultToolsInner, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *ToolSearchResult) SetTools(v []ToolSearchResultToolsInner)`

SetTools sets Tools field to given value.


### GetTotal

`func (o *ToolSearchResult) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ToolSearchResult) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ToolSearchResult) SetTotal(v int32)`

SetTotal sets Total field to given value.


### SetTotalNil

`func (o *ToolSearchResult) SetTotalNil(b bool)`

 SetTotalNil sets the value for Total to be an explicit nil

### UnsetTotal
`func (o *ToolSearchResult) UnsetTotal()`

UnsetTotal ensures that no value is present for Total, not even an explicit nil
### GetTruncated

`func (o *ToolSearchResult) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *ToolSearchResult) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *ToolSearchResult) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


