# ReviewCommentList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comments** | [**[]ReviewCommentListCommentsInner**](ReviewCommentListCommentsInner.md) |  | 
**CycleId** | **string** |  | 
**HeadSha** | **NullableString** |  | 
**VisualContext** | Pointer to [**ReviewCommentListVisualContext**](ReviewCommentListVisualContext.md) |  | [optional] 

## Methods

### NewReviewCommentList

`func NewReviewCommentList(comments []ReviewCommentListCommentsInner, cycleId string, headSha NullableString, ) *ReviewCommentList`

NewReviewCommentList instantiates a new ReviewCommentList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReviewCommentListWithDefaults

`func NewReviewCommentListWithDefaults() *ReviewCommentList`

NewReviewCommentListWithDefaults instantiates a new ReviewCommentList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComments

`func (o *ReviewCommentList) GetComments() []ReviewCommentListCommentsInner`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *ReviewCommentList) GetCommentsOk() (*[]ReviewCommentListCommentsInner, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *ReviewCommentList) SetComments(v []ReviewCommentListCommentsInner)`

SetComments sets Comments field to given value.


### GetCycleId

`func (o *ReviewCommentList) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ReviewCommentList) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ReviewCommentList) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetHeadSha

`func (o *ReviewCommentList) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *ReviewCommentList) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *ReviewCommentList) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### SetHeadShaNil

`func (o *ReviewCommentList) SetHeadShaNil(b bool)`

 SetHeadShaNil sets the value for HeadSha to be an explicit nil

### UnsetHeadSha
`func (o *ReviewCommentList) UnsetHeadSha()`

UnsetHeadSha ensures that no value is present for HeadSha, not even an explicit nil
### GetVisualContext

`func (o *ReviewCommentList) GetVisualContext() ReviewCommentListVisualContext`

GetVisualContext returns the VisualContext field if non-nil, zero value otherwise.

### GetVisualContextOk

`func (o *ReviewCommentList) GetVisualContextOk() (*ReviewCommentListVisualContext, bool)`

GetVisualContextOk returns a tuple with the VisualContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisualContext

`func (o *ReviewCommentList) SetVisualContext(v ReviewCommentListVisualContext)`

SetVisualContext sets VisualContext field to given value.

### HasVisualContext

`func (o *ReviewCommentList) HasVisualContext() bool`

HasVisualContext returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


