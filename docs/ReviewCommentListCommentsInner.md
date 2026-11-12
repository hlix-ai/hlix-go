# ReviewCommentListCommentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthorId** | **string** |  |
**Body** | **string** |  |
**CreatedAt** | **string** |  |
**CycleId** | **string** |  |
**HeadSha** | **string** |  |
**Id** | **string** |  |
**LineEnd** | **NullableFloat32** |  |
**LineStart** | **NullableFloat32** |  |
**Path** | **NullableString** |  |
**ProjectId** | **string** |  |
**Resolution** | **string** |  |
**ResolvedAt** | **NullableString** |  |
**ResolvedBy** | **NullableString** |  |
**RevisionIteration** | **NullableFloat32** |  |
**SelectedText** | **NullableString** |  |
**Side** | **NullableString** |  |
**Stale** | **bool** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewReviewCommentListCommentsInner

`func NewReviewCommentListCommentsInner(authorId string, body string, createdAt string, cycleId string, headSha string, id string, lineEnd NullableFloat32, lineStart NullableFloat32, path NullableString, projectId string, resolution string, resolvedAt NullableString, resolvedBy NullableString, revisionIteration NullableFloat32, selectedText NullableString, side NullableString, stale bool, updatedAt string, ) *ReviewCommentListCommentsInner`

NewReviewCommentListCommentsInner instantiates a new ReviewCommentListCommentsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewReviewCommentListCommentsInnerWithDefaults

`func NewReviewCommentListCommentsInnerWithDefaults() *ReviewCommentListCommentsInner`

NewReviewCommentListCommentsInnerWithDefaults instantiates a new ReviewCommentListCommentsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAuthorId

`func (o *ReviewCommentListCommentsInner) GetAuthorId() string`

GetAuthorId returns the AuthorId field if non-nil, zero value otherwise.

### GetAuthorIdOk

`func (o *ReviewCommentListCommentsInner) GetAuthorIdOk() (*string, bool)`

GetAuthorIdOk returns a tuple with the AuthorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorId

`func (o *ReviewCommentListCommentsInner) SetAuthorId(v string)`

SetAuthorId sets AuthorId field to given value.


### GetBody

`func (o *ReviewCommentListCommentsInner) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *ReviewCommentListCommentsInner) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *ReviewCommentListCommentsInner) SetBody(v string)`

SetBody sets Body field to given value.


### GetCreatedAt

`func (o *ReviewCommentListCommentsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReviewCommentListCommentsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReviewCommentListCommentsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *ReviewCommentListCommentsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ReviewCommentListCommentsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ReviewCommentListCommentsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetHeadSha

`func (o *ReviewCommentListCommentsInner) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *ReviewCommentListCommentsInner) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *ReviewCommentListCommentsInner) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### GetId

`func (o *ReviewCommentListCommentsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReviewCommentListCommentsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReviewCommentListCommentsInner) SetId(v string)`

SetId sets Id field to given value.


### GetLineEnd

`func (o *ReviewCommentListCommentsInner) GetLineEnd() float32`

GetLineEnd returns the LineEnd field if non-nil, zero value otherwise.

### GetLineEndOk

`func (o *ReviewCommentListCommentsInner) GetLineEndOk() (*float32, bool)`

GetLineEndOk returns a tuple with the LineEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineEnd

`func (o *ReviewCommentListCommentsInner) SetLineEnd(v float32)`

SetLineEnd sets LineEnd field to given value.


### SetLineEndNil

`func (o *ReviewCommentListCommentsInner) SetLineEndNil(b bool)`

 SetLineEndNil sets the value for LineEnd to be an explicit nil

### UnsetLineEnd
`func (o *ReviewCommentListCommentsInner) UnsetLineEnd()`

UnsetLineEnd ensures that no value is present for LineEnd, not even an explicit nil
### GetLineStart

`func (o *ReviewCommentListCommentsInner) GetLineStart() float32`

GetLineStart returns the LineStart field if non-nil, zero value otherwise.

### GetLineStartOk

`func (o *ReviewCommentListCommentsInner) GetLineStartOk() (*float32, bool)`

GetLineStartOk returns a tuple with the LineStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineStart

`func (o *ReviewCommentListCommentsInner) SetLineStart(v float32)`

SetLineStart sets LineStart field to given value.


### SetLineStartNil

`func (o *ReviewCommentListCommentsInner) SetLineStartNil(b bool)`

 SetLineStartNil sets the value for LineStart to be an explicit nil

### UnsetLineStart
`func (o *ReviewCommentListCommentsInner) UnsetLineStart()`

UnsetLineStart ensures that no value is present for LineStart, not even an explicit nil
### GetPath

`func (o *ReviewCommentListCommentsInner) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ReviewCommentListCommentsInner) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ReviewCommentListCommentsInner) SetPath(v string)`

SetPath sets Path field to given value.


### SetPathNil

`func (o *ReviewCommentListCommentsInner) SetPathNil(b bool)`

 SetPathNil sets the value for Path to be an explicit nil

### UnsetPath
`func (o *ReviewCommentListCommentsInner) UnsetPath()`

UnsetPath ensures that no value is present for Path, not even an explicit nil
### GetProjectId

`func (o *ReviewCommentListCommentsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ReviewCommentListCommentsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ReviewCommentListCommentsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetResolution

`func (o *ReviewCommentListCommentsInner) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *ReviewCommentListCommentsInner) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *ReviewCommentListCommentsInner) SetResolution(v string)`

SetResolution sets Resolution field to given value.


### GetResolvedAt

`func (o *ReviewCommentListCommentsInner) GetResolvedAt() string`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *ReviewCommentListCommentsInner) GetResolvedAtOk() (*string, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *ReviewCommentListCommentsInner) SetResolvedAt(v string)`

SetResolvedAt sets ResolvedAt field to given value.


### SetResolvedAtNil

`func (o *ReviewCommentListCommentsInner) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *ReviewCommentListCommentsInner) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *ReviewCommentListCommentsInner) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *ReviewCommentListCommentsInner) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *ReviewCommentListCommentsInner) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.


### SetResolvedByNil

`func (o *ReviewCommentListCommentsInner) SetResolvedByNil(b bool)`

 SetResolvedByNil sets the value for ResolvedBy to be an explicit nil

### UnsetResolvedBy
`func (o *ReviewCommentListCommentsInner) UnsetResolvedBy()`

UnsetResolvedBy ensures that no value is present for ResolvedBy, not even an explicit nil
### GetRevisionIteration

`func (o *ReviewCommentListCommentsInner) GetRevisionIteration() float32`

GetRevisionIteration returns the RevisionIteration field if non-nil, zero value otherwise.

### GetRevisionIterationOk

`func (o *ReviewCommentListCommentsInner) GetRevisionIterationOk() (*float32, bool)`

GetRevisionIterationOk returns a tuple with the RevisionIteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionIteration

`func (o *ReviewCommentListCommentsInner) SetRevisionIteration(v float32)`

SetRevisionIteration sets RevisionIteration field to given value.


### SetRevisionIterationNil

`func (o *ReviewCommentListCommentsInner) SetRevisionIterationNil(b bool)`

 SetRevisionIterationNil sets the value for RevisionIteration to be an explicit nil

### UnsetRevisionIteration
`func (o *ReviewCommentListCommentsInner) UnsetRevisionIteration()`

UnsetRevisionIteration ensures that no value is present for RevisionIteration, not even an explicit nil
### GetSelectedText

`func (o *ReviewCommentListCommentsInner) GetSelectedText() string`

GetSelectedText returns the SelectedText field if non-nil, zero value otherwise.

### GetSelectedTextOk

`func (o *ReviewCommentListCommentsInner) GetSelectedTextOk() (*string, bool)`

GetSelectedTextOk returns a tuple with the SelectedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedText

`func (o *ReviewCommentListCommentsInner) SetSelectedText(v string)`

SetSelectedText sets SelectedText field to given value.


### SetSelectedTextNil

`func (o *ReviewCommentListCommentsInner) SetSelectedTextNil(b bool)`

 SetSelectedTextNil sets the value for SelectedText to be an explicit nil

### UnsetSelectedText
`func (o *ReviewCommentListCommentsInner) UnsetSelectedText()`

UnsetSelectedText ensures that no value is present for SelectedText, not even an explicit nil
### GetSide

`func (o *ReviewCommentListCommentsInner) GetSide() string`

GetSide returns the Side field if non-nil, zero value otherwise.

### GetSideOk

`func (o *ReviewCommentListCommentsInner) GetSideOk() (*string, bool)`

GetSideOk returns a tuple with the Side field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSide

`func (o *ReviewCommentListCommentsInner) SetSide(v string)`

SetSide sets Side field to given value.


### SetSideNil

`func (o *ReviewCommentListCommentsInner) SetSideNil(b bool)`

 SetSideNil sets the value for Side to be an explicit nil

### UnsetSide
`func (o *ReviewCommentListCommentsInner) UnsetSide()`

UnsetSide ensures that no value is present for Side, not even an explicit nil
### GetStale

`func (o *ReviewCommentListCommentsInner) GetStale() bool`

GetStale returns the Stale field if non-nil, zero value otherwise.

### GetStaleOk

`func (o *ReviewCommentListCommentsInner) GetStaleOk() (*bool, bool)`

GetStaleOk returns a tuple with the Stale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStale

`func (o *ReviewCommentListCommentsInner) SetStale(v bool)`

SetStale sets Stale field to given value.


### GetUpdatedAt

`func (o *ReviewCommentListCommentsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ReviewCommentListCommentsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ReviewCommentListCommentsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


