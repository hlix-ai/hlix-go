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
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAiBatchPollWithDefaults

`func NewAiBatchPollWithDefaults() *AiBatchPoll`

NewAiBatchPollWithDefaults instantiates a new AiBatchPoll object
This constructor applies declared defaults. It does not ensure required properties are set.

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


