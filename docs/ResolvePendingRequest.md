# ResolvePendingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DecidedBy** | Pointer to **string** |  | [optional] 
**Decision** | Pointer to **string** |  | [optional] 
**Feedback** | Pointer to **string** |  | [optional] 
**Status** | **string** |  | 

## Methods

### NewResolvePendingRequest

`func NewResolvePendingRequest(status string, ) *ResolvePendingRequest`

NewResolvePendingRequest instantiates a new ResolvePendingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResolvePendingRequestWithDefaults

`func NewResolvePendingRequestWithDefaults() *ResolvePendingRequest`

NewResolvePendingRequestWithDefaults instantiates a new ResolvePendingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDecidedBy

`func (o *ResolvePendingRequest) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *ResolvePendingRequest) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *ResolvePendingRequest) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.

### HasDecidedBy

`func (o *ResolvePendingRequest) HasDecidedBy() bool`

HasDecidedBy returns a boolean if a field has been set.

### GetDecision

`func (o *ResolvePendingRequest) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *ResolvePendingRequest) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *ResolvePendingRequest) SetDecision(v string)`

SetDecision sets Decision field to given value.

### HasDecision

`func (o *ResolvePendingRequest) HasDecision() bool`

HasDecision returns a boolean if a field has been set.

### GetFeedback

`func (o *ResolvePendingRequest) GetFeedback() string`

GetFeedback returns the Feedback field if non-nil, zero value otherwise.

### GetFeedbackOk

`func (o *ResolvePendingRequest) GetFeedbackOk() (*string, bool)`

GetFeedbackOk returns a tuple with the Feedback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeedback

`func (o *ResolvePendingRequest) SetFeedback(v string)`

SetFeedback sets Feedback field to given value.

### HasFeedback

`func (o *ResolvePendingRequest) HasFeedback() bool`

HasFeedback returns a boolean if a field has been set.

### GetStatus

`func (o *ResolvePendingRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ResolvePendingRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ResolvePendingRequest) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


