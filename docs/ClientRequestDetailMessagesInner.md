# ClientRequestDetailMessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentId** | **NullableString** |  |
**Author** | [**NullableClientRequestDetailMessagesInnerAuthor**](ClientRequestDetailMessagesInnerAuthor.md) |  |
**Content** | **string** |  |
**CreatedAt** | **string** |  |
**CycleId** | **NullableString** |  |
**Delivery** | Pointer to **string** |  | [optional]
**Id** | **string** |  |
**Metadata** | [**ClientRequestDetailMessagesInnerMetadata**](ClientRequestDetailMessagesInnerMetadata.md) |  |
**Parts** | Pointer to [**[]ClientRequestDetailMessagesInnerPartsInner**](ClientRequestDetailMessagesInnerPartsInner.md) |  | [optional]
**ReplyTo** | Pointer to **string** |  | [optional]
**Role** | **string** |  |
**Status** | Pointer to **string** |  | [optional]

## Methods

### NewClientRequestDetailMessagesInner

`func NewClientRequestDetailMessagesInner(agentId NullableString, author NullableClientRequestDetailMessagesInnerAuthor, content string, createdAt string, cycleId NullableString, id string, metadata ClientRequestDetailMessagesInnerMetadata, role string, ) *ClientRequestDetailMessagesInner`

NewClientRequestDetailMessagesInner instantiates a new ClientRequestDetailMessagesInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientRequestDetailMessagesInnerWithDefaults

`func NewClientRequestDetailMessagesInnerWithDefaults() *ClientRequestDetailMessagesInner`

NewClientRequestDetailMessagesInnerWithDefaults instantiates a new ClientRequestDetailMessagesInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentId

`func (o *ClientRequestDetailMessagesInner) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *ClientRequestDetailMessagesInner) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *ClientRequestDetailMessagesInner) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.


### SetAgentIdNil

`func (o *ClientRequestDetailMessagesInner) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *ClientRequestDetailMessagesInner) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetAuthor

`func (o *ClientRequestDetailMessagesInner) GetAuthor() ClientRequestDetailMessagesInnerAuthor`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *ClientRequestDetailMessagesInner) GetAuthorOk() (*ClientRequestDetailMessagesInnerAuthor, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *ClientRequestDetailMessagesInner) SetAuthor(v ClientRequestDetailMessagesInnerAuthor)`

SetAuthor sets Author field to given value.


### SetAuthorNil

`func (o *ClientRequestDetailMessagesInner) SetAuthorNil(b bool)`

 SetAuthorNil sets the value for Author to be an explicit nil

### UnsetAuthor
`func (o *ClientRequestDetailMessagesInner) UnsetAuthor()`

UnsetAuthor ensures that no value is present for Author, not even an explicit nil
### GetContent

`func (o *ClientRequestDetailMessagesInner) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ClientRequestDetailMessagesInner) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ClientRequestDetailMessagesInner) SetContent(v string)`

SetContent sets Content field to given value.


### GetCreatedAt

`func (o *ClientRequestDetailMessagesInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientRequestDetailMessagesInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientRequestDetailMessagesInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *ClientRequestDetailMessagesInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ClientRequestDetailMessagesInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ClientRequestDetailMessagesInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ClientRequestDetailMessagesInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ClientRequestDetailMessagesInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDelivery

`func (o *ClientRequestDetailMessagesInner) GetDelivery() string`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *ClientRequestDetailMessagesInner) GetDeliveryOk() (*string, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *ClientRequestDetailMessagesInner) SetDelivery(v string)`

SetDelivery sets Delivery field to given value.

### HasDelivery

`func (o *ClientRequestDetailMessagesInner) HasDelivery() bool`

HasDelivery returns a boolean if a field has been set.

### GetId

`func (o *ClientRequestDetailMessagesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientRequestDetailMessagesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientRequestDetailMessagesInner) SetId(v string)`

SetId sets Id field to given value.


### GetMetadata

`func (o *ClientRequestDetailMessagesInner) GetMetadata() ClientRequestDetailMessagesInnerMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ClientRequestDetailMessagesInner) GetMetadataOk() (*ClientRequestDetailMessagesInnerMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ClientRequestDetailMessagesInner) SetMetadata(v ClientRequestDetailMessagesInnerMetadata)`

SetMetadata sets Metadata field to given value.


### GetParts

`func (o *ClientRequestDetailMessagesInner) GetParts() []ClientRequestDetailMessagesInnerPartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *ClientRequestDetailMessagesInner) GetPartsOk() (*[]ClientRequestDetailMessagesInnerPartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *ClientRequestDetailMessagesInner) SetParts(v []ClientRequestDetailMessagesInnerPartsInner)`

SetParts sets Parts field to given value.

### HasParts

`func (o *ClientRequestDetailMessagesInner) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetReplyTo

`func (o *ClientRequestDetailMessagesInner) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *ClientRequestDetailMessagesInner) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *ClientRequestDetailMessagesInner) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *ClientRequestDetailMessagesInner) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetRole

`func (o *ClientRequestDetailMessagesInner) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ClientRequestDetailMessagesInner) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ClientRequestDetailMessagesInner) SetRole(v string)`

SetRole sets Role field to given value.


### GetStatus

`func (o *ClientRequestDetailMessagesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientRequestDetailMessagesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientRequestDetailMessagesInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ClientRequestDetailMessagesInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


