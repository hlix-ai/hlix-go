# SequenceStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Risk** | **NullableString** |  |
**SpendMicros** | **NullableInt64** |  |
**TasksDone** | **NullableInt32** |  |
**TasksTotal** | **NullableInt32** |  |
**TestsPassed** | **NullableInt32** |  |
**TestsTotal** | **NullableInt32** |  |

## Methods

### NewSequenceStatus

`func NewSequenceStatus(risk NullableString, spendMicros NullableInt64, tasksDone NullableInt32, tasksTotal NullableInt32, testsPassed NullableInt32, testsTotal NullableInt32, ) *SequenceStatus`

NewSequenceStatus instantiates a new SequenceStatus object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewSequenceStatusWithDefaults

`func NewSequenceStatusWithDefaults() *SequenceStatus`

NewSequenceStatusWithDefaults instantiates a new SequenceStatus object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetRisk

`func (o *SequenceStatus) GetRisk() string`

GetRisk returns the Risk field if non-nil, zero value otherwise.

### GetRiskOk

`func (o *SequenceStatus) GetRiskOk() (*string, bool)`

GetRiskOk returns a tuple with the Risk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRisk

`func (o *SequenceStatus) SetRisk(v string)`

SetRisk sets Risk field to given value.


### SetRiskNil

`func (o *SequenceStatus) SetRiskNil(b bool)`

 SetRiskNil sets the value for Risk to be an explicit nil

### UnsetRisk
`func (o *SequenceStatus) UnsetRisk()`

UnsetRisk ensures that no value is present for Risk, not even an explicit nil
### GetSpendMicros

`func (o *SequenceStatus) GetSpendMicros() int64`

GetSpendMicros returns the SpendMicros field if non-nil, zero value otherwise.

### GetSpendMicrosOk

`func (o *SequenceStatus) GetSpendMicrosOk() (*int64, bool)`

GetSpendMicrosOk returns a tuple with the SpendMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpendMicros

`func (o *SequenceStatus) SetSpendMicros(v int64)`

SetSpendMicros sets SpendMicros field to given value.


### SetSpendMicrosNil

`func (o *SequenceStatus) SetSpendMicrosNil(b bool)`

 SetSpendMicrosNil sets the value for SpendMicros to be an explicit nil

### UnsetSpendMicros
`func (o *SequenceStatus) UnsetSpendMicros()`

UnsetSpendMicros ensures that no value is present for SpendMicros, not even an explicit nil
### GetTasksDone

`func (o *SequenceStatus) GetTasksDone() int32`

GetTasksDone returns the TasksDone field if non-nil, zero value otherwise.

### GetTasksDoneOk

`func (o *SequenceStatus) GetTasksDoneOk() (*int32, bool)`

GetTasksDoneOk returns a tuple with the TasksDone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasksDone

`func (o *SequenceStatus) SetTasksDone(v int32)`

SetTasksDone sets TasksDone field to given value.


### SetTasksDoneNil

`func (o *SequenceStatus) SetTasksDoneNil(b bool)`

 SetTasksDoneNil sets the value for TasksDone to be an explicit nil

### UnsetTasksDone
`func (o *SequenceStatus) UnsetTasksDone()`

UnsetTasksDone ensures that no value is present for TasksDone, not even an explicit nil
### GetTasksTotal

`func (o *SequenceStatus) GetTasksTotal() int32`

GetTasksTotal returns the TasksTotal field if non-nil, zero value otherwise.

### GetTasksTotalOk

`func (o *SequenceStatus) GetTasksTotalOk() (*int32, bool)`

GetTasksTotalOk returns a tuple with the TasksTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasksTotal

`func (o *SequenceStatus) SetTasksTotal(v int32)`

SetTasksTotal sets TasksTotal field to given value.


### SetTasksTotalNil

`func (o *SequenceStatus) SetTasksTotalNil(b bool)`

 SetTasksTotalNil sets the value for TasksTotal to be an explicit nil

### UnsetTasksTotal
`func (o *SequenceStatus) UnsetTasksTotal()`

UnsetTasksTotal ensures that no value is present for TasksTotal, not even an explicit nil
### GetTestsPassed

`func (o *SequenceStatus) GetTestsPassed() int32`

GetTestsPassed returns the TestsPassed field if non-nil, zero value otherwise.

### GetTestsPassedOk

`func (o *SequenceStatus) GetTestsPassedOk() (*int32, bool)`

GetTestsPassedOk returns a tuple with the TestsPassed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTestsPassed

`func (o *SequenceStatus) SetTestsPassed(v int32)`

SetTestsPassed sets TestsPassed field to given value.


### SetTestsPassedNil

`func (o *SequenceStatus) SetTestsPassedNil(b bool)`

 SetTestsPassedNil sets the value for TestsPassed to be an explicit nil

### UnsetTestsPassed
`func (o *SequenceStatus) UnsetTestsPassed()`

UnsetTestsPassed ensures that no value is present for TestsPassed, not even an explicit nil
### GetTestsTotal

`func (o *SequenceStatus) GetTestsTotal() int32`

GetTestsTotal returns the TestsTotal field if non-nil, zero value otherwise.

### GetTestsTotalOk

`func (o *SequenceStatus) GetTestsTotalOk() (*int32, bool)`

GetTestsTotalOk returns a tuple with the TestsTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTestsTotal

`func (o *SequenceStatus) SetTestsTotal(v int32)`

SetTestsTotal sets TestsTotal field to given value.


### SetTestsTotalNil

`func (o *SequenceStatus) SetTestsTotalNil(b bool)`

 SetTestsTotalNil sets the value for TestsTotal to be an explicit nil

### UnsetTestsTotal
`func (o *SequenceStatus) UnsetTestsTotal()`

UnsetTestsTotal ensures that no value is present for TestsTotal, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


