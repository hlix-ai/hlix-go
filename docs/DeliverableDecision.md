# DeliverableDecision

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comment** | **NullableString** |  | 
**ConversationMessageId** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**DecidedAt** | **NullableString** |  | 
**DecidedBy** | **NullableString** |  | 
**DeliverableId** | **string** |  | 
**Deployment** | [**DeliverableDecisionDeployment**](DeliverableDecisionDeployment.md) |  | 
**Id** | **string** |  | 
**OrganizationId** | **string** |  | 
**RequestedBy** | **string** |  | 
**RequestedReviewerId** | **string** |  | 
**Revision** | **int32** |  | 
**RevisionHash** | **string** |  | 
**Status** | **string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewDeliverableDecision

`func NewDeliverableDecision(comment NullableString, conversationMessageId NullableString, createdAt string, decidedAt NullableString, decidedBy NullableString, deliverableId string, deployment DeliverableDecisionDeployment, id string, organizationId string, requestedBy string, requestedReviewerId string, revision int32, revisionHash string, status string, updatedAt string, ) *DeliverableDecision`

NewDeliverableDecision instantiates a new DeliverableDecision object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverableDecisionWithDefaults

`func NewDeliverableDecisionWithDefaults() *DeliverableDecision`

NewDeliverableDecisionWithDefaults instantiates a new DeliverableDecision object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComment

`func (o *DeliverableDecision) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *DeliverableDecision) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *DeliverableDecision) SetComment(v string)`

SetComment sets Comment field to given value.


### SetCommentNil

`func (o *DeliverableDecision) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *DeliverableDecision) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetConversationMessageId

`func (o *DeliverableDecision) GetConversationMessageId() string`

GetConversationMessageId returns the ConversationMessageId field if non-nil, zero value otherwise.

### GetConversationMessageIdOk

`func (o *DeliverableDecision) GetConversationMessageIdOk() (*string, bool)`

GetConversationMessageIdOk returns a tuple with the ConversationMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationMessageId

`func (o *DeliverableDecision) SetConversationMessageId(v string)`

SetConversationMessageId sets ConversationMessageId field to given value.


### SetConversationMessageIdNil

`func (o *DeliverableDecision) SetConversationMessageIdNil(b bool)`

 SetConversationMessageIdNil sets the value for ConversationMessageId to be an explicit nil

### UnsetConversationMessageId
`func (o *DeliverableDecision) UnsetConversationMessageId()`

UnsetConversationMessageId ensures that no value is present for ConversationMessageId, not even an explicit nil
### GetCreatedAt

`func (o *DeliverableDecision) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DeliverableDecision) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DeliverableDecision) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDecidedAt

`func (o *DeliverableDecision) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *DeliverableDecision) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *DeliverableDecision) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *DeliverableDecision) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *DeliverableDecision) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *DeliverableDecision) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *DeliverableDecision) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *DeliverableDecision) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *DeliverableDecision) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *DeliverableDecision) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDeliverableId

`func (o *DeliverableDecision) GetDeliverableId() string`

GetDeliverableId returns the DeliverableId field if non-nil, zero value otherwise.

### GetDeliverableIdOk

`func (o *DeliverableDecision) GetDeliverableIdOk() (*string, bool)`

GetDeliverableIdOk returns a tuple with the DeliverableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverableId

`func (o *DeliverableDecision) SetDeliverableId(v string)`

SetDeliverableId sets DeliverableId field to given value.


### GetDeployment

`func (o *DeliverableDecision) GetDeployment() DeliverableDecisionDeployment`

GetDeployment returns the Deployment field if non-nil, zero value otherwise.

### GetDeploymentOk

`func (o *DeliverableDecision) GetDeploymentOk() (*DeliverableDecisionDeployment, bool)`

GetDeploymentOk returns a tuple with the Deployment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployment

`func (o *DeliverableDecision) SetDeployment(v DeliverableDecisionDeployment)`

SetDeployment sets Deployment field to given value.


### GetId

`func (o *DeliverableDecision) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeliverableDecision) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeliverableDecision) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *DeliverableDecision) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DeliverableDecision) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DeliverableDecision) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRequestedBy

`func (o *DeliverableDecision) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *DeliverableDecision) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *DeliverableDecision) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetRequestedReviewerId

`func (o *DeliverableDecision) GetRequestedReviewerId() string`

GetRequestedReviewerId returns the RequestedReviewerId field if non-nil, zero value otherwise.

### GetRequestedReviewerIdOk

`func (o *DeliverableDecision) GetRequestedReviewerIdOk() (*string, bool)`

GetRequestedReviewerIdOk returns a tuple with the RequestedReviewerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedReviewerId

`func (o *DeliverableDecision) SetRequestedReviewerId(v string)`

SetRequestedReviewerId sets RequestedReviewerId field to given value.


### GetRevision

`func (o *DeliverableDecision) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *DeliverableDecision) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *DeliverableDecision) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetRevisionHash

`func (o *DeliverableDecision) GetRevisionHash() string`

GetRevisionHash returns the RevisionHash field if non-nil, zero value otherwise.

### GetRevisionHashOk

`func (o *DeliverableDecision) GetRevisionHashOk() (*string, bool)`

GetRevisionHashOk returns a tuple with the RevisionHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionHash

`func (o *DeliverableDecision) SetRevisionHash(v string)`

SetRevisionHash sets RevisionHash field to given value.


### GetStatus

`func (o *DeliverableDecision) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliverableDecision) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliverableDecision) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *DeliverableDecision) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DeliverableDecision) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DeliverableDecision) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


