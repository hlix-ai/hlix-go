# ActivityEvent

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

### NewActivityEvent

`func NewActivityEvent(actorId NullableString, actorType string, entityId string, entityType string, eventType string, id string, organizationId string, payload interface{}, spanId NullableString, timestamp string, traceId NullableString, ) *ActivityEvent`

NewActivityEvent instantiates a new ActivityEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityEventWithDefaults

`func NewActivityEventWithDefaults() *ActivityEvent`

NewActivityEventWithDefaults instantiates a new ActivityEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActorId

`func (o *ActivityEvent) GetActorId() string`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *ActivityEvent) GetActorIdOk() (*string, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *ActivityEvent) SetActorId(v string)`

SetActorId sets ActorId field to given value.


### SetActorIdNil

`func (o *ActivityEvent) SetActorIdNil(b bool)`

 SetActorIdNil sets the value for ActorId to be an explicit nil

### UnsetActorId
`func (o *ActivityEvent) UnsetActorId()`

UnsetActorId ensures that no value is present for ActorId, not even an explicit nil
### GetActorType

`func (o *ActivityEvent) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *ActivityEvent) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *ActivityEvent) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetEntityId

`func (o *ActivityEvent) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *ActivityEvent) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *ActivityEvent) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.


### GetEntityType

`func (o *ActivityEvent) GetEntityType() string`

GetEntityType returns the EntityType field if non-nil, zero value otherwise.

### GetEntityTypeOk

`func (o *ActivityEvent) GetEntityTypeOk() (*string, bool)`

GetEntityTypeOk returns a tuple with the EntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityType

`func (o *ActivityEvent) SetEntityType(v string)`

SetEntityType sets EntityType field to given value.


### GetEventType

`func (o *ActivityEvent) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *ActivityEvent) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *ActivityEvent) SetEventType(v string)`

SetEventType sets EventType field to given value.


### GetId

`func (o *ActivityEvent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ActivityEvent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ActivityEvent) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *ActivityEvent) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ActivityEvent) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ActivityEvent) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPayload

`func (o *ActivityEvent) GetPayload() interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *ActivityEvent) GetPayloadOk() (*interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *ActivityEvent) SetPayload(v interface{})`

SetPayload sets Payload field to given value.


### SetPayloadNil

`func (o *ActivityEvent) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *ActivityEvent) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil
### GetSpanId

`func (o *ActivityEvent) GetSpanId() string`

GetSpanId returns the SpanId field if non-nil, zero value otherwise.

### GetSpanIdOk

`func (o *ActivityEvent) GetSpanIdOk() (*string, bool)`

GetSpanIdOk returns a tuple with the SpanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpanId

`func (o *ActivityEvent) SetSpanId(v string)`

SetSpanId sets SpanId field to given value.


### SetSpanIdNil

`func (o *ActivityEvent) SetSpanIdNil(b bool)`

 SetSpanIdNil sets the value for SpanId to be an explicit nil

### UnsetSpanId
`func (o *ActivityEvent) UnsetSpanId()`

UnsetSpanId ensures that no value is present for SpanId, not even an explicit nil
### GetTimestamp

`func (o *ActivityEvent) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ActivityEvent) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ActivityEvent) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetTraceId

`func (o *ActivityEvent) GetTraceId() string`

GetTraceId returns the TraceId field if non-nil, zero value otherwise.

### GetTraceIdOk

`func (o *ActivityEvent) GetTraceIdOk() (*string, bool)`

GetTraceIdOk returns a tuple with the TraceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceId

`func (o *ActivityEvent) SetTraceId(v string)`

SetTraceId sets TraceId field to given value.


### SetTraceIdNil

`func (o *ActivityEvent) SetTraceIdNil(b bool)`

 SetTraceIdNil sets the value for TraceId to be an explicit nil

### UnsetTraceId
`func (o *ActivityEvent) UnsetTraceId()`

UnsetTraceId ensures that no value is present for TraceId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


