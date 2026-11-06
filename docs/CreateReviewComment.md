# CreateReviewComment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | **string** |  | 
**HeadSha** | **string** |  | 
**LineEnd** | Pointer to **NullableInt32** |  | [optional] 
**LineStart** | Pointer to **NullableInt32** |  | [optional] 
**Path** | Pointer to **NullableString** |  | [optional] 
**SelectedText** | Pointer to **NullableString** |  | [optional] 
**Side** | Pointer to **NullableString** |  | [optional] 
**VisualContext** | Pointer to [**CreateReviewCommentVisualContext**](CreateReviewCommentVisualContext.md) |  | [optional] 

## Methods

### NewCreateReviewComment

`func NewCreateReviewComment(body string, headSha string, ) *CreateReviewComment`

NewCreateReviewComment instantiates a new CreateReviewComment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateReviewCommentWithDefaults

`func NewCreateReviewCommentWithDefaults() *CreateReviewComment`

NewCreateReviewCommentWithDefaults instantiates a new CreateReviewComment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *CreateReviewComment) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *CreateReviewComment) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *CreateReviewComment) SetBody(v string)`

SetBody sets Body field to given value.


### GetHeadSha

`func (o *CreateReviewComment) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *CreateReviewComment) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *CreateReviewComment) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### GetLineEnd

`func (o *CreateReviewComment) GetLineEnd() int32`

GetLineEnd returns the LineEnd field if non-nil, zero value otherwise.

### GetLineEndOk

`func (o *CreateReviewComment) GetLineEndOk() (*int32, bool)`

GetLineEndOk returns a tuple with the LineEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineEnd

`func (o *CreateReviewComment) SetLineEnd(v int32)`

SetLineEnd sets LineEnd field to given value.

### HasLineEnd

`func (o *CreateReviewComment) HasLineEnd() bool`

HasLineEnd returns a boolean if a field has been set.

### SetLineEndNil

`func (o *CreateReviewComment) SetLineEndNil(b bool)`

 SetLineEndNil sets the value for LineEnd to be an explicit nil

### UnsetLineEnd
`func (o *CreateReviewComment) UnsetLineEnd()`

UnsetLineEnd ensures that no value is present for LineEnd, not even an explicit nil
### GetLineStart

`func (o *CreateReviewComment) GetLineStart() int32`

GetLineStart returns the LineStart field if non-nil, zero value otherwise.

### GetLineStartOk

`func (o *CreateReviewComment) GetLineStartOk() (*int32, bool)`

GetLineStartOk returns a tuple with the LineStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineStart

`func (o *CreateReviewComment) SetLineStart(v int32)`

SetLineStart sets LineStart field to given value.

### HasLineStart

`func (o *CreateReviewComment) HasLineStart() bool`

HasLineStart returns a boolean if a field has been set.

### SetLineStartNil

`func (o *CreateReviewComment) SetLineStartNil(b bool)`

 SetLineStartNil sets the value for LineStart to be an explicit nil

### UnsetLineStart
`func (o *CreateReviewComment) UnsetLineStart()`

UnsetLineStart ensures that no value is present for LineStart, not even an explicit nil
### GetPath

`func (o *CreateReviewComment) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *CreateReviewComment) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *CreateReviewComment) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *CreateReviewComment) HasPath() bool`

HasPath returns a boolean if a field has been set.

### SetPathNil

`func (o *CreateReviewComment) SetPathNil(b bool)`

 SetPathNil sets the value for Path to be an explicit nil

### UnsetPath
`func (o *CreateReviewComment) UnsetPath()`

UnsetPath ensures that no value is present for Path, not even an explicit nil
### GetSelectedText

`func (o *CreateReviewComment) GetSelectedText() string`

GetSelectedText returns the SelectedText field if non-nil, zero value otherwise.

### GetSelectedTextOk

`func (o *CreateReviewComment) GetSelectedTextOk() (*string, bool)`

GetSelectedTextOk returns a tuple with the SelectedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedText

`func (o *CreateReviewComment) SetSelectedText(v string)`

SetSelectedText sets SelectedText field to given value.

### HasSelectedText

`func (o *CreateReviewComment) HasSelectedText() bool`

HasSelectedText returns a boolean if a field has been set.

### SetSelectedTextNil

`func (o *CreateReviewComment) SetSelectedTextNil(b bool)`

 SetSelectedTextNil sets the value for SelectedText to be an explicit nil

### UnsetSelectedText
`func (o *CreateReviewComment) UnsetSelectedText()`

UnsetSelectedText ensures that no value is present for SelectedText, not even an explicit nil
### GetSide

`func (o *CreateReviewComment) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *CreateReviewComment) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *CreateReviewComment) SetSide(v string)`

SetSide sets Side field to given value.

### HasSide

`func (o *CreateReviewComment) HasSide() bool`

HasSide returns a boolean if a field has been set.

### SetSideNil

`func (o *CreateReviewComment) SetSideNil(b bool)`

 SetSideNil sets the value for Side to be an explicit nil

### UnsetSide
`func (o *CreateReviewComment) UnsetSide()`

UnsetSide ensures that no value is present for Side, not even an explicit nil
### GetVisualContext

`func (o *CreateReviewComment) GetVisualContext() CreateReviewCommentVisualContext`

GetVisualContext returns the VisualContext field if non-nil, zero value otherwise.

### GetVisualContextOk

`func (o *CreateReviewComment) GetVisualContextOk() (*CreateReviewCommentVisualContext, bool)`

GetVisualContextOk returns a tuple with the VisualContext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisualContext

`func (o *CreateReviewComment) SetVisualContext(v CreateReviewCommentVisualContext)`

SetVisualContext sets VisualContext field to given value.

### HasVisualContext

`func (o *CreateReviewComment) HasVisualContext() bool`

HasVisualContext returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


