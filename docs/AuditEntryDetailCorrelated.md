# AuditEntryDetailCorrelated

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentRuns** | [**[]AuditEntryDetailCorrelatedAgentRunsInner**](AuditEntryDetailCorrelatedAgentRunsInner.md) |  | 
**Events** | [**[]AuditEntryDetailCorrelatedEventsInner**](AuditEntryDetailCorrelatedEventsInner.md) |  | 
**Logs** | [**[]AuditEntryDetailCorrelatedLogsInner**](AuditEntryDetailCorrelatedLogsInner.md) |  | 

## Methods

### NewAuditEntryDetailCorrelated

`func NewAuditEntryDetailCorrelated(agentRuns []AuditEntryDetailCorrelatedAgentRunsInner, events []AuditEntryDetailCorrelatedEventsInner, logs []AuditEntryDetailCorrelatedLogsInner, ) *AuditEntryDetailCorrelated`

NewAuditEntryDetailCorrelated instantiates a new AuditEntryDetailCorrelated object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditEntryDetailCorrelatedWithDefaults

`func NewAuditEntryDetailCorrelatedWithDefaults() *AuditEntryDetailCorrelated`

NewAuditEntryDetailCorrelatedWithDefaults instantiates a new AuditEntryDetailCorrelated object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentRuns

`func (o *AuditEntryDetailCorrelated) GetAgentRuns() []AuditEntryDetailCorrelatedAgentRunsInner`

GetAgentRuns returns the AgentRuns field if non-nil, zero value otherwise.

### GetAgentRunsOk

`func (o *AuditEntryDetailCorrelated) GetAgentRunsOk() (*[]AuditEntryDetailCorrelatedAgentRunsInner, bool)`

GetAgentRunsOk returns a tuple with the AgentRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentRuns

`func (o *AuditEntryDetailCorrelated) SetAgentRuns(v []AuditEntryDetailCorrelatedAgentRunsInner)`

SetAgentRuns sets AgentRuns field to given value.


### GetEvents

`func (o *AuditEntryDetailCorrelated) GetEvents() []AuditEntryDetailCorrelatedEventsInner`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *AuditEntryDetailCorrelated) GetEventsOk() (*[]AuditEntryDetailCorrelatedEventsInner, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *AuditEntryDetailCorrelated) SetEvents(v []AuditEntryDetailCorrelatedEventsInner)`

SetEvents sets Events field to given value.


### GetLogs

`func (o *AuditEntryDetailCorrelated) GetLogs() []AuditEntryDetailCorrelatedLogsInner`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *AuditEntryDetailCorrelated) GetLogsOk() (*[]AuditEntryDetailCorrelatedLogsInner, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *AuditEntryDetailCorrelated) SetLogs(v []AuditEntryDetailCorrelatedLogsInner)`

SetLogs sets Logs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


