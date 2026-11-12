# Sequence

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cycle** | [**SequenceCycle**](SequenceCycle.md) |  |
**Events** | [**[]SequenceEventsInner**](SequenceEventsInner.md) |  |
**Explainer** | [**SequenceExplainer**](SequenceExplainer.md) |  |
**Narration** | [**[]SequenceNarrationInner**](SequenceNarrationInner.md) |  |
**Progress** | [**[]SequenceProgressInner**](SequenceProgressInner.md) |  |
**Status** | [**SequenceStatus**](SequenceStatus.md) |  |
**Team** | [**SequenceTeam**](SequenceTeam.md) |  |
**TimeOnTask** | [**[]SequenceTimeOnTaskInner**](SequenceTimeOnTaskInner.md) |  |

## Methods

### NewSequence

`func NewSequence(cycle SequenceCycle, events []SequenceEventsInner, explainer SequenceExplainer, narration []SequenceNarrationInner, progress []SequenceProgressInner, status SequenceStatus, team SequenceTeam, timeOnTask []SequenceTimeOnTaskInner, ) *Sequence`

NewSequence instantiates a new Sequence object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewSequenceWithDefaults

`func NewSequenceWithDefaults() *Sequence`

NewSequenceWithDefaults instantiates a new Sequence object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCycle

`func (o *Sequence) GetCycle() SequenceCycle`

GetCycle returns the Cycle field if non-nil, zero value otherwise.

### GetCycleOk

`func (o *Sequence) GetCycleOk() (*SequenceCycle, bool)`

GetCycleOk returns a tuple with the Cycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycle

`func (o *Sequence) SetCycle(v SequenceCycle)`

SetCycle sets Cycle field to given value.


### GetEvents

`func (o *Sequence) GetEvents() []SequenceEventsInner`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *Sequence) GetEventsOk() (*[]SequenceEventsInner, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *Sequence) SetEvents(v []SequenceEventsInner)`

SetEvents sets Events field to given value.


### GetExplainer

`func (o *Sequence) GetExplainer() SequenceExplainer`

GetExplainer returns the Explainer field if non-nil, zero value otherwise.

### GetExplainerOk

`func (o *Sequence) GetExplainerOk() (*SequenceExplainer, bool)`

GetExplainerOk returns a tuple with the Explainer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExplainer

`func (o *Sequence) SetExplainer(v SequenceExplainer)`

SetExplainer sets Explainer field to given value.


### GetNarration

`func (o *Sequence) GetNarration() []SequenceNarrationInner`

GetNarration returns the Narration field if non-nil, zero value otherwise.

### GetNarrationOk

`func (o *Sequence) GetNarrationOk() (*[]SequenceNarrationInner, bool)`

GetNarrationOk returns a tuple with the Narration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNarration

`func (o *Sequence) SetNarration(v []SequenceNarrationInner)`

SetNarration sets Narration field to given value.


### GetProgress

`func (o *Sequence) GetProgress() []SequenceProgressInner`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *Sequence) GetProgressOk() (*[]SequenceProgressInner, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *Sequence) SetProgress(v []SequenceProgressInner)`

SetProgress sets Progress field to given value.


### GetStatus

`func (o *Sequence) GetStatus() SequenceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Sequence) GetStatusOk() (*SequenceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Sequence) SetStatus(v SequenceStatus)`

SetStatus sets Status field to given value.


### GetTeam

`func (o *Sequence) GetTeam() SequenceTeam`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *Sequence) GetTeamOk() (*SequenceTeam, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *Sequence) SetTeam(v SequenceTeam)`

SetTeam sets Team field to given value.


### GetTimeOnTask

`func (o *Sequence) GetTimeOnTask() []SequenceTimeOnTaskInner`

GetTimeOnTask returns the TimeOnTask field if non-nil, zero value otherwise.

### GetTimeOnTaskOk

`func (o *Sequence) GetTimeOnTaskOk() (*[]SequenceTimeOnTaskInner, bool)`

GetTimeOnTaskOk returns a tuple with the TimeOnTask field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeOnTask

`func (o *Sequence) SetTimeOnTask(v []SequenceTimeOnTaskInner)`

SetTimeOnTask sets TimeOnTask field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


