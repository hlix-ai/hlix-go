# ReviewRevisionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CommentIds** | **[]string** |  |
**CycleId** | **string** |  |
**Feedback** | **string** |  |
**HeadSha** | **string** |  |
**Iteration** | **float32** |  |
**Reason** | **NullableString** |  |
**StaleSkipped** | **float32** |  |
**Started** | **bool** |  |
**TaskId** | **string** |  |

## Methods

### NewReviewRevisionRequest

`func NewReviewRevisionRequest(commentIds []string, cycleId string, feedback string, headSha string, iteration float32, reason NullableString, staleSkipped float32, started bool, taskId string, ) *ReviewRevisionRequest`

NewReviewRevisionRequest instantiates a new ReviewRevisionRequest object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewReviewRevisionRequestWithDefaults

`func NewReviewRevisionRequestWithDefaults() *ReviewRevisionRequest`

NewReviewRevisionRequestWithDefaults instantiates a new ReviewRevisionRequest object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCommentIds

`func (o *ReviewRevisionRequest) GetCommentIds() []string`

GetCommentIds returns the CommentIds field if non-nil, zero value otherwise.

### GetCommentIdsOk

`func (o *ReviewRevisionRequest) GetCommentIdsOk() (*[]string, bool)`

GetCommentIdsOk returns a tuple with the CommentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommentIds

`func (o *ReviewRevisionRequest) SetCommentIds(v []string)`

SetCommentIds sets CommentIds field to given value.


### GetCycleId

`func (o *ReviewRevisionRequest) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ReviewRevisionRequest) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ReviewRevisionRequest) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetFeedback

`func (o *ReviewRevisionRequest) GetFeedback() string`

GetFeedback returns the Feedback field if non-nil, zero value otherwise.

### GetFeedbackOk

`func (o *ReviewRevisionRequest) GetFeedbackOk() (*string, bool)`

GetFeedbackOk returns a tuple with the Feedback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeedback

`func (o *ReviewRevisionRequest) SetFeedback(v string)`

SetFeedback sets Feedback field to given value.


### GetHeadSha

`func (o *ReviewRevisionRequest) GetHeadSha() string`

GetHeadSha returns the HeadSha field if non-nil, zero value otherwise.

### GetHeadShaOk

`func (o *ReviewRevisionRequest) GetHeadShaOk() (*string, bool)`

GetHeadShaOk returns a tuple with the HeadSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadSha

`func (o *ReviewRevisionRequest) SetHeadSha(v string)`

SetHeadSha sets HeadSha field to given value.


### GetIteration

`func (o *ReviewRevisionRequest) GetIteration() float32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *ReviewRevisionRequest) GetIterationOk() (*float32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *ReviewRevisionRequest) SetIteration(v float32)`

SetIteration sets Iteration field to given value.


### GetReason

`func (o *ReviewRevisionRequest) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ReviewRevisionRequest) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ReviewRevisionRequest) SetReason(v string)`

SetReason sets Reason field to given value.


### SetReasonNil

`func (o *ReviewRevisionRequest) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *ReviewRevisionRequest) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetStaleSkipped

`func (o *ReviewRevisionRequest) GetStaleSkipped() float32`

GetStaleSkipped returns the StaleSkipped field if non-nil, zero value otherwise.

### GetStaleSkippedOk

`func (o *ReviewRevisionRequest) GetStaleSkippedOk() (*float32, bool)`

GetStaleSkippedOk returns a tuple with the StaleSkipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStaleSkipped

`func (o *ReviewRevisionRequest) SetStaleSkipped(v float32)`

SetStaleSkipped sets StaleSkipped field to given value.


### GetStarted

`func (o *ReviewRevisionRequest) GetStarted() bool`

GetStarted returns the Started field if non-nil, zero value otherwise.

### GetStartedOk

`func (o *ReviewRevisionRequest) GetStartedOk() (*bool, bool)`

GetStartedOk returns a tuple with the Started field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStarted

`func (o *ReviewRevisionRequest) SetStarted(v bool)`

SetStarted sets Started field to given value.


### GetTaskId

`func (o *ReviewRevisionRequest) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *ReviewRevisionRequest) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *ReviewRevisionRequest) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


