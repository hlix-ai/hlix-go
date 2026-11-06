# AiBatchPoll

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Job** | [**AiBatchAcceptedJob**](AiBatchAcceptedJob.md) |  | 
**Polled** | **bool** |  | 

## Methods

### NewAiBatchPoll

`func NewAiBatchPoll(job AiBatchAcceptedJob, polled bool, ) *AiBatchPoll`

NewAiBatchPoll instantiates a new AiBatchPoll object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiBatchPollWithDefaults

`func NewAiBatchPollWithDefaults() *AiBatchPoll`

NewAiBatchPollWithDefaults instantiates a new AiBatchPoll object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJob

`func (o *AiBatchPoll) GetJob() AiBatchAcceptedJob`

GetJob returns the Job field if non-nil, zero value otherwise.

### GetJobOk

`func (o *AiBatchPoll) GetJobOk() (*AiBatchAcceptedJob, bool)`

GetJobOk returns a tuple with the Job field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJob

`func (o *AiBatchPoll) SetJob(v AiBatchAcceptedJob)`

SetJob sets Job field to given value.


### GetPolled

`func (o *AiBatchPoll) GetPolled() bool`

GetPolled returns the Polled field if non-nil, zero value otherwise.

### GetPolledOk

`func (o *AiBatchPoll) GetPolledOk() (*bool, bool)`

GetPolledOk returns a tuple with the Polled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolled

`func (o *AiBatchPoll) SetPolled(v bool)`

SetPolled sets Polled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


