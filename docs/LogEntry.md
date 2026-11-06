# LogEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentRunId** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**CycleId** | **NullableString** |  | 
**Id** | **string** |  | 
**Level** | **string** |  | 
**Message** | **string** |  | 
**OrganizationId** | **string** |  | 
**SpanId** | **NullableString** |  | 
**TaskId** | **NullableString** |  | 
**TraceId** | **NullableString** |  | 

## Methods

### NewLogEntry

`func NewLogEntry(agentRunId NullableString, createdAt string, cycleId NullableString, id string, level string, message string, organizationId string, spanId NullableString, taskId NullableString, traceId NullableString, ) *LogEntry`

NewLogEntry instantiates a new LogEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLogEntryWithDefaults

`func NewLogEntryWithDefaults() *LogEntry`

NewLogEntryWithDefaults instantiates a new LogEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentRunId

`func (o *LogEntry) GetAgentRunId() string`

GetAgentRunId returns the AgentRunId field if non-nil, zero value otherwise.

### GetAgentRunIdOk

`func (o *LogEntry) GetAgentRunIdOk() (*string, bool)`

GetAgentRunIdOk returns a tuple with the AgentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentRunId

`func (o *LogEntry) SetAgentRunId(v string)`

SetAgentRunId sets AgentRunId field to given value.


### SetAgentRunIdNil

`func (o *LogEntry) SetAgentRunIdNil(b bool)`

 SetAgentRunIdNil sets the value for AgentRunId to be an explicit nil

### UnsetAgentRunId
`func (o *LogEntry) UnsetAgentRunId()`

UnsetAgentRunId ensures that no value is present for AgentRunId, not even an explicit nil
### GetCreatedAt

`func (o *LogEntry) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LogEntry) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LogEntry) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *LogEntry) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *LogEntry) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *LogEntry) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *LogEntry) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *LogEntry) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetId

`func (o *LogEntry) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LogEntry) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LogEntry) SetId(v string)`

SetId sets Id field to given value.


### GetLevel

`func (o *LogEntry) GetLevel() string`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *LogEntry) GetLevelOk() (*string, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *LogEntry) SetLevel(v string)`

SetLevel sets Level field to given value.


### GetMessage

`func (o *LogEntry) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *LogEntry) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *LogEntry) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetOrganizationId

`func (o *LogEntry) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *LogEntry) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *LogEntry) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetSpanId

`func (o *LogEntry) GetSpanId() string`

GetSpanId returns the SpanId field if non-nil, zero value otherwise.

### GetSpanIdOk

`func (o *LogEntry) GetSpanIdOk() (*string, bool)`

GetSpanIdOk returns a tuple with the SpanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpanId

`func (o *LogEntry) SetSpanId(v string)`

SetSpanId sets SpanId field to given value.


### SetSpanIdNil

`func (o *LogEntry) SetSpanIdNil(b bool)`

 SetSpanIdNil sets the value for SpanId to be an explicit nil

### UnsetSpanId
`func (o *LogEntry) UnsetSpanId()`

UnsetSpanId ensures that no value is present for SpanId, not even an explicit nil
### GetTaskId

`func (o *LogEntry) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *LogEntry) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *LogEntry) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *LogEntry) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *LogEntry) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTraceId

`func (o *LogEntry) GetTraceId() string`

GetTraceId returns the TraceId field if non-nil, zero value otherwise.

### GetTraceIdOk

`func (o *LogEntry) GetTraceIdOk() (*string, bool)`

GetTraceIdOk returns a tuple with the TraceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceId

`func (o *LogEntry) SetTraceId(v string)`

SetTraceId sets TraceId field to given value.


### SetTraceIdNil

`func (o *LogEntry) SetTraceIdNil(b bool)`

 SetTraceIdNil sets the value for TraceId to be an explicit nil

### UnsetTraceId
`func (o *LogEntry) UnsetTraceId()`

UnsetTraceId ensures that no value is present for TraceId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


