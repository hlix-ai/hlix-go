# AuditEntryDetailCorrelatedEventsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActorId** | **NullableString** |  |
**ActorType** | **string** |  |
**EntityId** | **string** |  |
**EntityType** | **string** |  |
**EventType** | **string** |  |
**Id** | **string** |  |
**OrganizationId** | **string** |  |
**Payload** | **interface{}** |  |
**SpanId** | **NullableString** |  |
**Timestamp** | **string** |  |
**TraceId** | **NullableString** |  |

## Methods

### NewAuditEntryDetailCorrelatedEventsInner

`func NewAuditEntryDetailCorrelatedEventsInner(actorId NullableString, actorType string, entityId string, entityType string, eventType string, id string, organizationId string, payload interface{}, spanId NullableString, timestamp string, traceId NullableString, ) *AuditEntryDetailCorrelatedEventsInner`

NewAuditEntryDetailCorrelatedEventsInner instantiates a new AuditEntryDetailCorrelatedEventsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAuditEntryDetailCorrelatedEventsInnerWithDefaults

`func NewAuditEntryDetailCorrelatedEventsInnerWithDefaults() *AuditEntryDetailCorrelatedEventsInner`

NewAuditEntryDetailCorrelatedEventsInnerWithDefaults instantiates a new AuditEntryDetailCorrelatedEventsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetActorId

`func (o *AuditEntryDetailCorrelatedEventsInner) GetActorId() string`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetActorIdOk() (*string, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *AuditEntryDetailCorrelatedEventsInner) SetActorId(v string)`

SetActorId sets ActorId field to given value.


### SetActorIdNil

`func (o *AuditEntryDetailCorrelatedEventsInner) SetActorIdNil(b bool)`

 SetActorIdNil sets the value for ActorId to be an explicit nil

### UnsetActorId
`func (o *AuditEntryDetailCorrelatedEventsInner) UnsetActorId()`

UnsetActorId ensures that no value is present for ActorId, not even an explicit nil
### GetActorType

`func (o *AuditEntryDetailCorrelatedEventsInner) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *AuditEntryDetailCorrelatedEventsInner) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetEntityId

`func (o *AuditEntryDetailCorrelatedEventsInner) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *AuditEntryDetailCorrelatedEventsInner) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.


### GetEntityType

`func (o *AuditEntryDetailCorrelatedEventsInner) GetEntityType() string`

GetEntityType returns the EntityType field if non-nil, zero value otherwise.

### GetEntityTypeOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetEntityTypeOk() (*string, bool)`

GetEntityTypeOk returns a tuple with the EntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityType

`func (o *AuditEntryDetailCorrelatedEventsInner) SetEntityType(v string)`

SetEntityType sets EntityType field to given value.


### GetEventType

`func (o *AuditEntryDetailCorrelatedEventsInner) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *AuditEntryDetailCorrelatedEventsInner) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetId

`func (o *AuditEntryDetailCorrelatedEventsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuditEntryDetailCorrelatedEventsInner) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *AuditEntryDetailCorrelatedEventsInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AuditEntryDetailCorrelatedEventsInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPayload

`func (o *AuditEntryDetailCorrelatedEventsInner) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *AuditEntryDetailCorrelatedEventsInner) SetPayload(v interface{})`

SetPayload sets Payload field to given value.


### SetPayloadNil

`func (o *AuditEntryDetailCorrelatedEventsInner) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *AuditEntryDetailCorrelatedEventsInner) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetSpanId

`func (o *AuditEntryDetailCorrelatedEventsInner) GetSpanId() string`

GetSpanId returns the SpanId field if non-nil, zero value otherwise.

### GetSpanIdOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetSpanIdOk() (*string, bool)`

GetSpanIdOk returns a tuple with the SpanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpanId

`func (o *AuditEntryDetailCorrelatedEventsInner) SetSpanId(v string)`

SetSpanId sets SpanId field to given value.


### SetSpanIdNil

`func (o *AuditEntryDetailCorrelatedEventsInner) SetSpanIdNil(b bool)`

 SetSpanIdNil sets the value for SpanId to be an explicit nil

### UnsetSpanId
`func (o *AuditEntryDetailCorrelatedEventsInner) UnsetSpanId()`

UnsetSpanId ensures that no value is present for SpanId, not even an explicit nil
### GetTimestamp

`func (o *AuditEntryDetailCorrelatedEventsInner) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *AuditEntryDetailCorrelatedEventsInner) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetTraceId

`func (o *AuditEntryDetailCorrelatedEventsInner) GetTraceId() string`

GetTraceId returns the TraceId field if non-nil, zero value otherwise.

### GetTraceIdOk

`func (o *AuditEntryDetailCorrelatedEventsInner) GetTraceIdOk() (*string, bool)`

GetTraceIdOk returns a tuple with the TraceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceId

`func (o *AuditEntryDetailCorrelatedEventsInner) SetTraceId(v string)`

SetTraceId sets TraceId field to given value.


### SetTraceIdNil

`func (o *AuditEntryDetailCorrelatedEventsInner) SetTraceIdNil(b bool)`

 SetTraceIdNil sets the value for TraceId to be an explicit nil

### UnsetTraceId
`func (o *AuditEntryDetailCorrelatedEventsInner) UnsetTraceId()`

UnsetTraceId ensures that no value is present for TraceId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


