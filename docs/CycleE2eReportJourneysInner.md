# CycleE2eReportJourneysInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**By** | Pointer to **string** |  | [optional]
**FinishedAt** | **string** |  |
**JourneyId** | **string** |  |
**Outcome** | **string** |  |
**Reason** | Pointer to **string** |  | [optional]
**RecordingKeys** | **[]string** |  |
**Requirement** | Pointer to **string** |  | [optional]
**StartedAt** | **string** |  |
**TaskIds** | **[]string** |  |
**Title** | **string** |  |
**TraceKey** | Pointer to **string** |  | [optional]

## Methods

### NewCycleE2eReportJourneysInner

`func NewCycleE2eReportJourneysInner(finishedAt string, journeyId string, outcome string, recordingKeys []string, startedAt string, taskIds []string, title string, ) *CycleE2eReportJourneysInner`

NewCycleE2eReportJourneysInner instantiates a new CycleE2eReportJourneysInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleE2eReportJourneysInnerWithDefaults

`func NewCycleE2eReportJourneysInnerWithDefaults() *CycleE2eReportJourneysInner`

NewCycleE2eReportJourneysInnerWithDefaults instantiates a new CycleE2eReportJourneysInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBy

`func (o *CycleE2eReportJourneysInner) GetBy() string`

GetBy returns the By field if non-nil, zero value otherwise.

### GetByOk

`func (o *CycleE2eReportJourneysInner) GetByOk() (*string, bool)`

GetByOk returns a tuple with the By field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBy

`func (o *CycleE2eReportJourneysInner) SetBy(v string)`

SetBy sets By field to given value.

### HasBy

`func (o *CycleE2eReportJourneysInner) HasBy() bool`

HasBy returns a boolean if a field has been set.

### GetFinishedAt

`func (o *CycleE2eReportJourneysInner) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *CycleE2eReportJourneysInner) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *CycleE2eReportJourneysInner) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.


### GetJourneyId

`func (o *CycleE2eReportJourneysInner) GetJourneyId() string`

GetJourneyId returns the JourneyId field if non-nil, zero value otherwise.

### GetJourneyIdOk

`func (o *CycleE2eReportJourneysInner) GetJourneyIdOk() (*string, bool)`

GetJourneyIdOk returns a tuple with the JourneyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJourneyId

`func (o *CycleE2eReportJourneysInner) SetJourneyId(v string)`

SetJourneyId sets JourneyId field to given value.


### GetOutcome

`func (o *CycleE2eReportJourneysInner) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *CycleE2eReportJourneysInner) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *CycleE2eReportJourneysInner) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetReason

`func (o *CycleE2eReportJourneysInner) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CycleE2eReportJourneysInner) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CycleE2eReportJourneysInner) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CycleE2eReportJourneysInner) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetRecordingKeys

`func (o *CycleE2eReportJourneysInner) GetRecordingKeys() []string`

GetRecordingKeys returns the RecordingKeys field if non-nil, zero value otherwise.

### GetRecordingKeysOk

`func (o *CycleE2eReportJourneysInner) GetRecordingKeysOk() (*[]string, bool)`

GetRecordingKeysOk returns a tuple with the RecordingKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordingKeys

`func (o *CycleE2eReportJourneysInner) SetRecordingKeys(v []string)`

SetRecordingKeys sets RecordingKeys field to given value.


### GetRequirement

`func (o *CycleE2eReportJourneysInner) GetRequirement() string`

GetRequirement returns the Requirement field if non-nil, zero value otherwise.

### GetRequirementOk

`func (o *CycleE2eReportJourneysInner) GetRequirementOk() (*string, bool)`

GetRequirementOk returns a tuple with the Requirement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirement

`func (o *CycleE2eReportJourneysInner) SetRequirement(v string)`

SetRequirement sets Requirement field to given value.

### HasRequirement

`func (o *CycleE2eReportJourneysInner) HasRequirement() bool`

HasRequirement returns a boolean if a field has been set.

### GetStartedAt

`func (o *CycleE2eReportJourneysInner) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *CycleE2eReportJourneysInner) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *CycleE2eReportJourneysInner) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetTaskIds

`func (o *CycleE2eReportJourneysInner) GetTaskIds() []string`

GetTaskIds returns the TaskIds field if non-nil, zero value otherwise.

### GetTaskIdsOk

`func (o *CycleE2eReportJourneysInner) GetTaskIdsOk() (*[]string, bool)`

GetTaskIdsOk returns a tuple with the TaskIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskIds

`func (o *CycleE2eReportJourneysInner) SetTaskIds(v []string)`

SetTaskIds sets TaskIds field to given value.


### GetTitle

`func (o *CycleE2eReportJourneysInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CycleE2eReportJourneysInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CycleE2eReportJourneysInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTraceKey

`func (o *CycleE2eReportJourneysInner) GetTraceKey() string`

GetTraceKey returns the TraceKey field if non-nil, zero value otherwise.

### GetTraceKeyOk

`func (o *CycleE2eReportJourneysInner) GetTraceKeyOk() (*string, bool)`

GetTraceKeyOk returns a tuple with the TraceKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceKey

`func (o *CycleE2eReportJourneysInner) SetTraceKey(v string)`

SetTraceKey sets TraceKey field to given value.

### HasTraceKey

`func (o *CycleE2eReportJourneysInner) HasTraceKey() bool`

HasTraceKey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


