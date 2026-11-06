# WireMessage

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

### NewWireMessage

`func NewWireMessage(agentId NullableString, author NullableClientRequestDetailMessagesInnerAuthor, content string, createdAt string, cycleId NullableString, id string, metadata ClientRequestDetailMessagesInnerMetadata, role string, ) *WireMessage`

NewWireMessage instantiates a new WireMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWireMessageWithDefaults

`func NewWireMessageWithDefaults() *WireMessage`

NewWireMessageWithDefaults instantiates a new WireMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentId

`func (o *WireMessage) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *WireMessage) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *WireMessage) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.


### SetAgentIdNil

`func (o *WireMessage) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *WireMessage) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetAuthor

`func (o *WireMessage) GetAuthor() ClientRequestDetailMessagesInnerAuthor`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *WireMessage) GetAuthorOk() (*ClientRequestDetailMessagesInnerAuthor, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *WireMessage) SetAuthor(v ClientRequestDetailMessagesInnerAuthor)`

SetAuthor sets Author field to given value.


### SetAuthorNil

`func (o *WireMessage) SetAuthorNil(b bool)`

 SetAuthorNil sets the value for Author to be an explicit nil

### UnsetAuthor
`func (o *WireMessage) UnsetAuthor()`

UnsetAuthor ensures that no value is present for Author, not even an explicit nil
### GetContent

`func (o *WireMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *WireMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *WireMessage) SetContent(v string)`

SetContent sets Content field to given value.


### GetCreatedAt

`func (o *WireMessage) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WireMessage) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WireMessage) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *WireMessage) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *WireMessage) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *WireMessage) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *WireMessage) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *WireMessage) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDelivery

`func (o *WireMessage) GetDelivery() string`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *WireMessage) GetDeliveryOk() (*string, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *WireMessage) SetDelivery(v string)`

SetDelivery sets Delivery field to given value.

### HasDelivery

`func (o *WireMessage) HasDelivery() bool`

HasDelivery returns a boolean if a field has been set.

### GetId

`func (o *WireMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WireMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WireMessage) SetId(v string)`

SetId sets Id field to given value.


### GetMetadata

`func (o *WireMessage) GetMetadata() ClientRequestDetailMessagesInnerMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *WireMessage) GetMetadataOk() (*ClientRequestDetailMessagesInnerMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *WireMessage) SetMetadata(v ClientRequestDetailMessagesInnerMetadata)`

SetMetadata sets Metadata field to given value.


### GetParts

`func (o *WireMessage) GetParts() []ClientRequestDetailMessagesInnerPartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *WireMessage) GetPartsOk() (*[]ClientRequestDetailMessagesInnerPartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *WireMessage) SetParts(v []ClientRequestDetailMessagesInnerPartsInner)`

SetParts sets Parts field to given value.

### HasParts

`func (o *WireMessage) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetReplyTo

`func (o *WireMessage) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *WireMessage) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *WireMessage) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *WireMessage) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetRole

`func (o *WireMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *WireMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *WireMessage) SetRole(v string)`

SetRole sets Role field to given value.


### GetStatus

`func (o *WireMessage) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WireMessage) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WireMessage) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *WireMessage) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


