# DeliverableApproval

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comment** | **NullableString** |  |
**ConversationMessageId** | **NullableString** |  |
**CreatedAt** | **string** |  |
**DecidedAt** | **NullableString** |  |
**DecidedBy** | **NullableString** |  |
**DeliverableId** | **string** |  |
**Id** | **string** |  |
**OrganizationId** | **string** |  |
**RequestedBy** | **string** |  |
**RequestedReviewerId** | **string** |  |
**Revision** | **int32** |  |
**RevisionHash** | **string** |  |
**Status** | **string** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewDeliverableApproval

`func NewDeliverableApproval(comment NullableString, conversationMessageId NullableString, createdAt string, decidedAt NullableString, decidedBy NullableString, deliverableId string, id string, organizationId string, requestedBy string, requestedReviewerId string, revision int32, revisionHash string, status string, updatedAt string, ) *DeliverableApproval`

NewDeliverableApproval instantiates a new DeliverableApproval object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeliverableApprovalWithDefaults

`func NewDeliverableApprovalWithDefaults() *DeliverableApproval`

NewDeliverableApprovalWithDefaults instantiates a new DeliverableApproval object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetComment

`func (o *DeliverableApproval) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *DeliverableApproval) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *DeliverableApproval) SetComment(v string)`

SetComment sets Comment field to given value.


### SetCommentNil

`func (o *DeliverableApproval) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *DeliverableApproval) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil
### GetConversationMessageId

`func (o *DeliverableApproval) GetConversationMessageId() string`

GetConversationMessageId returns the ConversationMessageId field if non-nil, zero value otherwise.

### GetConversationMessageIdOk

`func (o *DeliverableApproval) GetConversationMessageIdOk() (*string, bool)`

GetConversationMessageIdOk returns a tuple with the ConversationMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationMessageId

`func (o *DeliverableApproval) SetConversationMessageId(v string)`

SetConversationMessageId sets ConversationMessageId field to given value.


### SetConversationMessageIdNil

`func (o *DeliverableApproval) SetConversationMessageIdNil(b bool)`

 SetConversationMessageIdNil sets the value for ConversationMessageId to be an explicit nil

### UnsetConversationMessageId
`func (o *DeliverableApproval) UnsetConversationMessageId()`

UnsetConversationMessageId ensures that no value is present for ConversationMessageId, not even an explicit nil
### GetCreatedAt

`func (o *DeliverableApproval) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DeliverableApproval) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DeliverableApproval) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDecidedAt

`func (o *DeliverableApproval) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *DeliverableApproval) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *DeliverableApproval) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *DeliverableApproval) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *DeliverableApproval) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *DeliverableApproval) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *DeliverableApproval) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *DeliverableApproval) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *DeliverableApproval) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *DeliverableApproval) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDeliverableId

`func (o *DeliverableApproval) GetDeliverableId() string`

GetDeliverableId returns the DeliverableId field if non-nil, zero value otherwise.

### GetDeliverableIdOk

`func (o *DeliverableApproval) GetDeliverableIdOk() (*string, bool)`

GetDeliverableIdOk returns a tuple with the DeliverableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverableId

`func (o *DeliverableApproval) SetDeliverableId(v string)`

SetDeliverableId sets DeliverableId field to given value.


### GetId

`func (o *DeliverableApproval) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeliverableApproval) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeliverableApproval) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *DeliverableApproval) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *DeliverableApproval) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *DeliverableApproval) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRequestedBy

`func (o *DeliverableApproval) GetRequestedBy() string`

GetRequestedBy returns the RequestedBy field if non-nil, zero value otherwise.

### GetRequestedByOk

`func (o *DeliverableApproval) GetRequestedByOk() (*string, bool)`

GetRequestedByOk returns a tuple with the RequestedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedBy

`func (o *DeliverableApproval) SetRequestedBy(v string)`

SetRequestedBy sets RequestedBy field to given value.


### GetRequestedReviewerId

`func (o *DeliverableApproval) GetRequestedReviewerId() string`

GetRequestedReviewerId returns the RequestedReviewerId field if non-nil, zero value otherwise.

### GetRequestedReviewerIdOk

`func (o *DeliverableApproval) GetRequestedReviewerIdOk() (*string, bool)`

GetRequestedReviewerIdOk returns a tuple with the RequestedReviewerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedReviewerId

`func (o *DeliverableApproval) SetRequestedReviewerId(v string)`

SetRequestedReviewerId sets RequestedReviewerId field to given value.


### GetRevision

`func (o *DeliverableApproval) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *DeliverableApproval) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *DeliverableApproval) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetRevisionHash

`func (o *DeliverableApproval) GetRevisionHash() string`

GetRevisionHash returns the RevisionHash field if non-nil, zero value otherwise.

### GetRevisionHashOk

`func (o *DeliverableApproval) GetRevisionHashOk() (*string, bool)`

GetRevisionHashOk returns a tuple with the RevisionHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionHash

`func (o *DeliverableApproval) SetRevisionHash(v string)`

SetRevisionHash sets RevisionHash field to given value.


### GetStatus

`func (o *DeliverableApproval) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeliverableApproval) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeliverableApproval) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *DeliverableApproval) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DeliverableApproval) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DeliverableApproval) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


