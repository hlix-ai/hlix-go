# AuditEntryDetailCorrelated

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentRuns** | [**[]AuditEntryDetailCorrelatedAgentRunsInner**](AuditEntryDetailCorrelatedAgentRunsInner.md) |  |
**Events** | [**[]AuditEntryDetailCorrelatedEventsInner**](AuditEntryDetailCorrelatedEventsInner.md) |  |

## Methods

### NewAuditEntryDetailCorrelated

`func NewAuditEntryDetailCorrelated(agentRuns []AuditEntryDetailCorrelatedAgentRunsInner, events []AuditEntryDetailCorrelatedEventsInner, ) *AuditEntryDetailCorrelated`

NewAuditEntryDetailCorrelated instantiates a new AuditEntryDetailCorrelated object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAuditEntryDetailCorrelatedWithDefaults

`func NewAuditEntryDetailCorrelatedWithDefaults() *AuditEntryDetailCorrelated`

NewAuditEntryDetailCorrelatedWithDefaults instantiates a new AuditEntryDetailCorrelated object
This constructor applies declared defaults. It does not ensure required properties are set.

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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


