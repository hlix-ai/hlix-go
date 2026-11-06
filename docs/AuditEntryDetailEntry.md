# AuditEntryDetailEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** |  | 
**ActorId** | **NullableString** |  | 
**ActorLabel** | **NullableString** |  | 
**ActorType** | **string** |  | 
**AgentId** | **NullableString** |  | 
**AttributedUserId** | **NullableString** |  | 
**Category** | **string** |  | 
**Changes** | **interface{}** |  | 
**Id** | **string** |  | 
**IpAddress** | **NullableString** |  | 
**Metadata** | **interface{}** |  | 
**OccurredAt** | **string** |  | 
**OnBehalfOfId** | **NullableString** |  | 
**OrganizationId** | **string** |  | 
**Outcome** | **string** |  | 
**ParentResourceId** | **NullableString** |  | 
**ParentResourceType** | **NullableString** |  | 
**PrevHash** | **NullableString** |  | 
**Reason** | **NullableString** |  | 
**RecordedAt** | **string** |  | 
**RequestId** | **NullableString** |  | 
**ResourceId** | **NullableString** |  | 
**ResourceLabel** | **NullableString** |  | 
**ResourceType** | **string** |  | 
**RowHash** | **NullableString** |  | 
**Severity** | **string** |  | 
**Source** | **string** |  | 
**SpanId** | **NullableString** |  | 
**TraceId** | **NullableString** |  | 
**UserAgent** | **NullableString** |  | 

## Methods

### NewAuditEntryDetailEntry

`func NewAuditEntryDetailEntry(action string, actorId NullableString, actorLabel NullableString, actorType string, agentId NullableString, attributedUserId NullableString, category string, changes interface{}, id string, ipAddress NullableString, metadata interface{}, occurredAt string, onBehalfOfId NullableString, organizationId string, outcome string, parentResourceId NullableString, parentResourceType NullableString, prevHash NullableString, reason NullableString, recordedAt string, requestId NullableString, resourceId NullableString, resourceLabel NullableString, resourceType string, rowHash NullableString, severity string, source string, spanId NullableString, traceId NullableString, userAgent NullableString, ) *AuditEntryDetailEntry`

NewAuditEntryDetailEntry instantiates a new AuditEntryDetailEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditEntryDetailEntryWithDefaults

`func NewAuditEntryDetailEntryWithDefaults() *AuditEntryDetailEntry`

NewAuditEntryDetailEntryWithDefaults instantiates a new AuditEntryDetailEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *AuditEntryDetailEntry) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *AuditEntryDetailEntry) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *AuditEntryDetailEntry) SetAction(v string)`

SetAction sets Action field to given value.


### GetActorId

`func (o *AuditEntryDetailEntry) GetActorId() string`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *AuditEntryDetailEntry) GetActorIdOk() (*string, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *AuditEntryDetailEntry) SetActorId(v string)`

SetActorId sets ActorId field to given value.


### SetActorIdNil

`func (o *AuditEntryDetailEntry) SetActorIdNil(b bool)`

 SetActorIdNil sets the value for ActorId to be an explicit nil

### UnsetActorId
`func (o *AuditEntryDetailEntry) UnsetActorId()`

UnsetActorId ensures that no value is present for ActorId, not even an explicit nil
### GetActorLabel

`func (o *AuditEntryDetailEntry) GetActorLabel() string`

GetActorLabel returns the ActorLabel field if non-nil, zero value otherwise.

### GetActorLabelOk

`func (o *AuditEntryDetailEntry) GetActorLabelOk() (*string, bool)`

GetActorLabelOk returns a tuple with the ActorLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorLabel

`func (o *AuditEntryDetailEntry) SetActorLabel(v string)`

SetActorLabel sets ActorLabel field to given value.


### SetActorLabelNil

`func (o *AuditEntryDetailEntry) SetActorLabelNil(b bool)`

 SetActorLabelNil sets the value for ActorLabel to be an explicit nil

### UnsetActorLabel
`func (o *AuditEntryDetailEntry) UnsetActorLabel()`

UnsetActorLabel ensures that no value is present for ActorLabel, not even an explicit nil
### GetActorType

`func (o *AuditEntryDetailEntry) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *AuditEntryDetailEntry) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *AuditEntryDetailEntry) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetAgentId

`func (o *AuditEntryDetailEntry) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *AuditEntryDetailEntry) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *AuditEntryDetailEntry) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.


### SetAgentIdNil

`func (o *AuditEntryDetailEntry) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *AuditEntryDetailEntry) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetAttributedUserId

`func (o *AuditEntryDetailEntry) GetAttributedUserId() string`

GetAttributedUserId returns the AttributedUserId field if non-nil, zero value otherwise.

### GetAttributedUserIdOk

`func (o *AuditEntryDetailEntry) GetAttributedUserIdOk() (*string, bool)`

GetAttributedUserIdOk returns a tuple with the AttributedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributedUserId

`func (o *AuditEntryDetailEntry) SetAttributedUserId(v string)`

SetAttributedUserId sets AttributedUserId field to given value.


### SetAttributedUserIdNil

`func (o *AuditEntryDetailEntry) SetAttributedUserIdNil(b bool)`

 SetAttributedUserIdNil sets the value for AttributedUserId to be an explicit nil

### UnsetAttributedUserId
`func (o *AuditEntryDetailEntry) UnsetAttributedUserId()`

UnsetAttributedUserId ensures that no value is present for AttributedUserId, not even an explicit nil
### GetCategory

`func (o *AuditEntryDetailEntry) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *AuditEntryDetailEntry) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *AuditEntryDetailEntry) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetChanges

`func (o *AuditEntryDetailEntry) GetChanges() interface{}`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *AuditEntryDetailEntry) GetChangesOk() (*interface{}, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *AuditEntryDetailEntry) SetChanges(v interface{})`

SetChanges sets Changes field to given value.


### SetChangesNil

`func (o *AuditEntryDetailEntry) SetChangesNil(b bool)`

 SetChangesNil sets the value for Changes to be an explicit nil

### UnsetChanges
`func (o *AuditEntryDetailEntry) UnsetChanges()`

UnsetChanges ensures that no value is present for Changes, not even an explicit nil
### GetId

`func (o *AuditEntryDetailEntry) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuditEntryDetailEntry) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuditEntryDetailEntry) SetId(v string)`

SetId sets Id field to given value.


### GetIpAddress

`func (o *AuditEntryDetailEntry) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *AuditEntryDetailEntry) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *AuditEntryDetailEntry) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.


### SetIpAddressNil

`func (o *AuditEntryDetailEntry) SetIpAddressNil(b bool)`

 SetIpAddressNil sets the value for IpAddress to be an explicit nil

### UnsetIpAddress
`func (o *AuditEntryDetailEntry) UnsetIpAddress()`

UnsetIpAddress ensures that no value is present for IpAddress, not even an explicit nil
### GetMetadata

`func (o *AuditEntryDetailEntry) GetMetadata() interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AuditEntryDetailEntry) GetMetadataOk() (*interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AuditEntryDetailEntry) SetMetadata(v interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *AuditEntryDetailEntry) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AuditEntryDetailEntry) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetOccurredAt

`func (o *AuditEntryDetailEntry) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *AuditEntryDetailEntry) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *AuditEntryDetailEntry) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.


### GetOnBehalfOfId

`func (o *AuditEntryDetailEntry) GetOnBehalfOfId() string`

GetOnBehalfOfId returns the OnBehalfOfId field if non-nil, zero value otherwise.

### GetOnBehalfOfIdOk

`func (o *AuditEntryDetailEntry) GetOnBehalfOfIdOk() (*string, bool)`

GetOnBehalfOfIdOk returns a tuple with the OnBehalfOfId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnBehalfOfId

`func (o *AuditEntryDetailEntry) SetOnBehalfOfId(v string)`

SetOnBehalfOfId sets OnBehalfOfId field to given value.


### SetOnBehalfOfIdNil

`func (o *AuditEntryDetailEntry) SetOnBehalfOfIdNil(b bool)`

 SetOnBehalfOfIdNil sets the value for OnBehalfOfId to be an explicit nil

### UnsetOnBehalfOfId
`func (o *AuditEntryDetailEntry) UnsetOnBehalfOfId()`

UnsetOnBehalfOfId ensures that no value is present for OnBehalfOfId, not even an explicit nil
### GetOrganizationId

`func (o *AuditEntryDetailEntry) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AuditEntryDetailEntry) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AuditEntryDetailEntry) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOutcome

`func (o *AuditEntryDetailEntry) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *AuditEntryDetailEntry) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *AuditEntryDetailEntry) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetParentResourceId

`func (o *AuditEntryDetailEntry) GetParentResourceId() string`

GetParentResourceId returns the ParentResourceId field if non-nil, zero value otherwise.

### GetParentResourceIdOk

`func (o *AuditEntryDetailEntry) GetParentResourceIdOk() (*string, bool)`

GetParentResourceIdOk returns a tuple with the ParentResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentResourceId

`func (o *AuditEntryDetailEntry) SetParentResourceId(v string)`

SetParentResourceId sets ParentResourceId field to given value.


### SetParentResourceIdNil

`func (o *AuditEntryDetailEntry) SetParentResourceIdNil(b bool)`

 SetParentResourceIdNil sets the value for ParentResourceId to be an explicit nil

### UnsetParentResourceId
`func (o *AuditEntryDetailEntry) UnsetParentResourceId()`

UnsetParentResourceId ensures that no value is present for ParentResourceId, not even an explicit nil
### GetParentResourceType

`func (o *AuditEntryDetailEntry) GetParentResourceType() string`

GetParentResourceType returns the ParentResourceType field if non-nil, zero value otherwise.

### GetParentResourceTypeOk

`func (o *AuditEntryDetailEntry) GetParentResourceTypeOk() (*string, bool)`

GetParentResourceTypeOk returns a tuple with the ParentResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentResourceType

`func (o *AuditEntryDetailEntry) SetParentResourceType(v string)`

SetParentResourceType sets ParentResourceType field to given value.


### SetParentResourceTypeNil

`func (o *AuditEntryDetailEntry) SetParentResourceTypeNil(b bool)`

 SetParentResourceTypeNil sets the value for ParentResourceType to be an explicit nil

### UnsetParentResourceType
`func (o *AuditEntryDetailEntry) UnsetParentResourceType()`

UnsetParentResourceType ensures that no value is present for ParentResourceType, not even an explicit nil
### GetPrevHash

`func (o *AuditEntryDetailEntry) GetPrevHash() string`

GetPrevHash returns the PrevHash field if non-nil, zero value otherwise.

### GetPrevHashOk

`func (o *AuditEntryDetailEntry) GetPrevHashOk() (*string, bool)`

GetPrevHashOk returns a tuple with the PrevHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevHash

`func (o *AuditEntryDetailEntry) SetPrevHash(v string)`

SetPrevHash sets PrevHash field to given value.


### SetPrevHashNil

`func (o *AuditEntryDetailEntry) SetPrevHashNil(b bool)`

 SetPrevHashNil sets the value for PrevHash to be an explicit nil

### UnsetPrevHash
`func (o *AuditEntryDetailEntry) UnsetPrevHash()`

UnsetPrevHash ensures that no value is present for PrevHash, not even an explicit nil
### GetReason

`func (o *AuditEntryDetailEntry) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AuditEntryDetailEntry) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AuditEntryDetailEntry) SetReason(v string)`

SetReason sets Reason field to given value.


### SetReasonNil

`func (o *AuditEntryDetailEntry) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *AuditEntryDetailEntry) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetRecordedAt

`func (o *AuditEntryDetailEntry) GetRecordedAt() string`

GetRecordedAt returns the RecordedAt field if non-nil, zero value otherwise.

### GetRecordedAtOk

`func (o *AuditEntryDetailEntry) GetRecordedAtOk() (*string, bool)`

GetRecordedAtOk returns a tuple with the RecordedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordedAt

`func (o *AuditEntryDetailEntry) SetRecordedAt(v string)`

SetRecordedAt sets RecordedAt field to given value.


### GetRequestId

`func (o *AuditEntryDetailEntry) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AuditEntryDetailEntry) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AuditEntryDetailEntry) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### SetRequestIdNil

`func (o *AuditEntryDetailEntry) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *AuditEntryDetailEntry) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil
### GetResourceId

`func (o *AuditEntryDetailEntry) GetResourceId() string`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *AuditEntryDetailEntry) GetResourceIdOk() (*string, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *AuditEntryDetailEntry) SetResourceId(v string)`

SetResourceId sets ResourceId field to given value.


### SetResourceIdNil

`func (o *AuditEntryDetailEntry) SetResourceIdNil(b bool)`

 SetResourceIdNil sets the value for ResourceId to be an explicit nil

### UnsetResourceId
`func (o *AuditEntryDetailEntry) UnsetResourceId()`

UnsetResourceId ensures that no value is present for ResourceId, not even an explicit nil
### GetResourceLabel

`func (o *AuditEntryDetailEntry) GetResourceLabel() string`

GetResourceLabel returns the ResourceLabel field if non-nil, zero value otherwise.

### GetResourceLabelOk

`func (o *AuditEntryDetailEntry) GetResourceLabelOk() (*string, bool)`

GetResourceLabelOk returns a tuple with the ResourceLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceLabel

`func (o *AuditEntryDetailEntry) SetResourceLabel(v string)`

SetResourceLabel sets ResourceLabel field to given value.


### SetResourceLabelNil

`func (o *AuditEntryDetailEntry) SetResourceLabelNil(b bool)`

 SetResourceLabelNil sets the value for ResourceLabel to be an explicit nil

### UnsetResourceLabel
`func (o *AuditEntryDetailEntry) UnsetResourceLabel()`

UnsetResourceLabel ensures that no value is present for ResourceLabel, not even an explicit nil
### GetResourceType

`func (o *AuditEntryDetailEntry) GetResourceType() string`

GetResourceType returns the ResourceType field if non-nil, zero value otherwise.

### GetResourceTypeOk

`func (o *AuditEntryDetailEntry) GetResourceTypeOk() (*string, bool)`

GetResourceTypeOk returns a tuple with the ResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceType

`func (o *AuditEntryDetailEntry) SetResourceType(v string)`

SetResourceType sets ResourceType field to given value.


### GetRowHash

`func (o *AuditEntryDetailEntry) GetRowHash() string`

GetRowHash returns the RowHash field if non-nil, zero value otherwise.

### GetRowHashOk

`func (o *AuditEntryDetailEntry) GetRowHashOk() (*string, bool)`

GetRowHashOk returns a tuple with the RowHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRowHash

`func (o *AuditEntryDetailEntry) SetRowHash(v string)`

SetRowHash sets RowHash field to given value.


### SetRowHashNil

`func (o *AuditEntryDetailEntry) SetRowHashNil(b bool)`

 SetRowHashNil sets the value for RowHash to be an explicit nil

### UnsetRowHash
`func (o *AuditEntryDetailEntry) UnsetRowHash()`

UnsetRowHash ensures that no value is present for RowHash, not even an explicit nil
### GetSeverity

`func (o *AuditEntryDetailEntry) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *AuditEntryDetailEntry) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *AuditEntryDetailEntry) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetSource

`func (o *AuditEntryDetailEntry) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AuditEntryDetailEntry) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AuditEntryDetailEntry) SetSource(v string)`

SetSource sets Source field to given value.


### GetSpanId

`func (o *AuditEntryDetailEntry) GetSpanId() string`

GetSpanId returns the SpanId field if non-nil, zero value otherwise.

### GetSpanIdOk

`func (o *AuditEntryDetailEntry) GetSpanIdOk() (*string, bool)`

GetSpanIdOk returns a tuple with the SpanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpanId

`func (o *AuditEntryDetailEntry) SetSpanId(v string)`

SetSpanId sets SpanId field to given value.


### SetSpanIdNil

`func (o *AuditEntryDetailEntry) SetSpanIdNil(b bool)`

 SetSpanIdNil sets the value for SpanId to be an explicit nil

### UnsetSpanId
`func (o *AuditEntryDetailEntry) UnsetSpanId()`

UnsetSpanId ensures that no value is present for SpanId, not even an explicit nil
### GetTraceId

`func (o *AuditEntryDetailEntry) GetTraceId() string`

GetTraceId returns the TraceId field if non-nil, zero value otherwise.

### GetTraceIdOk

`func (o *AuditEntryDetailEntry) GetTraceIdOk() (*string, bool)`

GetTraceIdOk returns a tuple with the TraceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraceId

`func (o *AuditEntryDetailEntry) SetTraceId(v string)`

SetTraceId sets TraceId field to given value.


### SetTraceIdNil

`func (o *AuditEntryDetailEntry) SetTraceIdNil(b bool)`

 SetTraceIdNil sets the value for TraceId to be an explicit nil

### UnsetTraceId
`func (o *AuditEntryDetailEntry) UnsetTraceId()`

UnsetTraceId ensures that no value is present for TraceId, not even an explicit nil
### GetUserAgent

`func (o *AuditEntryDetailEntry) GetUserAgent() string`

GetUserAgent returns the UserAgent field if non-nil, zero value otherwise.

### GetUserAgentOk

`func (o *AuditEntryDetailEntry) GetUserAgentOk() (*string, bool)`

GetUserAgentOk returns a tuple with the UserAgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserAgent

`func (o *AuditEntryDetailEntry) SetUserAgent(v string)`

SetUserAgent sets UserAgent field to given value.


### SetUserAgentNil

`func (o *AuditEntryDetailEntry) SetUserAgentNil(b bool)`

 SetUserAgentNil sets the value for UserAgent to be an explicit nil

### UnsetUserAgent
`func (o *AuditEntryDetailEntry) UnsetUserAgent()`

UnsetUserAgent ensures that no value is present for UserAgent, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


