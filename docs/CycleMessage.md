# CycleMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentId** | Pointer to **NullableString** |  | [optional] 
**Attachments** | Pointer to [**[]AnalyzeMediaSourceAnyOf1**](AnalyzeMediaSourceAnyOf1.md) |  | [optional] 
**Content** | **string** |  | 
**Deliver** | Pointer to **bool** |  | [optional] 
**MessageId** | Pointer to **string** |  | [optional] 
**Urgent** | Pointer to **bool** |  | [optional] 

## Methods

### NewCycleMessage

`func NewCycleMessage(content string, ) *CycleMessage`

NewCycleMessage instantiates a new CycleMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleMessageWithDefaults

`func NewCycleMessageWithDefaults() *CycleMessage`

NewCycleMessageWithDefaults instantiates a new CycleMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentId

`func (o *CycleMessage) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *CycleMessage) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *CycleMessage) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.

### HasAgentId

`func (o *CycleMessage) HasAgentId() bool`

HasAgentId returns a boolean if a field has been set.

### SetAgentIdNil

`func (o *CycleMessage) SetAgentIdNil(b bool)`

 SetAgentIdNil sets the value for AgentId to be an explicit nil

### UnsetAgentId
`func (o *CycleMessage) UnsetAgentId()`

UnsetAgentId ensures that no value is present for AgentId, not even an explicit nil
### GetAttachments

`func (o *CycleMessage) GetAttachments() []AnalyzeMediaSourceAnyOf1`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *CycleMessage) GetAttachmentsOk() (*[]AnalyzeMediaSourceAnyOf1, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *CycleMessage) SetAttachments(v []AnalyzeMediaSourceAnyOf1)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *CycleMessage) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetContent

`func (o *CycleMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CycleMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CycleMessage) SetContent(v string)`

SetContent sets Content field to given value.


### GetDeliver

`func (o *CycleMessage) GetDeliver() bool`

GetDeliver returns the Deliver field if non-nil, zero value otherwise.

### GetDeliverOk

`func (o *CycleMessage) GetDeliverOk() (*bool, bool)`

GetDeliverOk returns a tuple with the Deliver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliver

`func (o *CycleMessage) SetDeliver(v bool)`

SetDeliver sets Deliver field to given value.

### HasDeliver

`func (o *CycleMessage) HasDeliver() bool`

HasDeliver returns a boolean if a field has been set.

### GetMessageId

`func (o *CycleMessage) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *CycleMessage) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *CycleMessage) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *CycleMessage) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### GetUrgent

`func (o *CycleMessage) GetUrgent() bool`

GetUrgent returns the Urgent field if non-nil, zero value otherwise.

### GetUrgentOk

`func (o *CycleMessage) GetUrgentOk() (*bool, bool)`

GetUrgentOk returns a tuple with the Urgent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrgent

`func (o *CycleMessage) SetUrgent(v bool)`

SetUrgent sets Urgent field to given value.

### HasUrgent

`func (o *CycleMessage) HasUrgent() bool`

HasUrgent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


