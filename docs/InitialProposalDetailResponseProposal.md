# InitialProposalDetailResponseProposal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApprovedAt** | **NullableTime** |  |
**ApprovedBy** | **NullableString** |  |
**ApprovedRevisionId** | **NullableString** |  |
**CanvasBatchId** | **NullableString** |  |
**CanvasPublicationError** | **NullableString** |  |
**CanvasPublishedAt** | **NullableTime** |  |
**ClientDecidedAt** | **NullableTime** |  |
**ClientDecidedBy** | **NullableString** |  |
**ClientDecision** | **NullableString** |  |
**ClientDecisionComment** | **NullableString** |  |
**ClientDecisionRevisionHash** | **NullableString** |  |
**ClientDecisionRevisionId** | **NullableString** |  |
**ClientReviewerId** | **NullableString** |  |
**CreatedAt** | **time.Time** |  |
**CurrentRevisionId** | **NullableString** |  |
**Id** | **string** |  |
**OperationId** | **NullableString** |  |
**OperationLeaseExpiresAt** | **NullableTime** |  |
**OperationLeaseToken** | **NullableString** |  |
**OrganizationId** | **string** |  |
**ProjectId** | **string** |  |
**PublishedRevisionId** | **NullableString** |  |
**UpdatedAt** | **time.Time** |  |
**Visibility** | **string** |  |

## Methods

### NewInitialProposalDetailResponseProposal

`func NewInitialProposalDetailResponseProposal(approvedAt NullableTime, approvedBy NullableString, approvedRevisionId NullableString, canvasBatchId NullableString, canvasPublicationError NullableString, canvasPublishedAt NullableTime, clientDecidedAt NullableTime, clientDecidedBy NullableString, clientDecision NullableString, clientDecisionComment NullableString, clientDecisionRevisionHash NullableString, clientDecisionRevisionId NullableString, clientReviewerId NullableString, createdAt time.Time, currentRevisionId NullableString, id string, operationId NullableString, operationLeaseExpiresAt NullableTime, operationLeaseToken NullableString, organizationId string, projectId string, publishedRevisionId NullableString, updatedAt time.Time, visibility string, ) *InitialProposalDetailResponseProposal`

NewInitialProposalDetailResponseProposal instantiates a new InitialProposalDetailResponseProposal object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewInitialProposalDetailResponseProposalWithDefaults

`func NewInitialProposalDetailResponseProposalWithDefaults() *InitialProposalDetailResponseProposal`

NewInitialProposalDetailResponseProposalWithDefaults instantiates a new InitialProposalDetailResponseProposal object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovedAt

`func (o *InitialProposalDetailResponseProposal) GetApprovedAt() time.Time`

GetApprovedAt returns the ApprovedAt field if non-nil, zero value otherwise.

### GetApprovedAtOk

`func (o *InitialProposalDetailResponseProposal) GetApprovedAtOk() (*time.Time, bool)`

GetApprovedAtOk returns a tuple with the ApprovedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedAt

`func (o *InitialProposalDetailResponseProposal) SetApprovedAt(v time.Time)`

SetApprovedAt sets ApprovedAt field to given value.


### SetApprovedAtNil

`func (o *InitialProposalDetailResponseProposal) SetApprovedAtNil(b bool)`

 SetApprovedAtNil sets the value for ApprovedAt to be an explicit nil

### UnsetApprovedAt
`func (o *InitialProposalDetailResponseProposal) UnsetApprovedAt()`

UnsetApprovedAt ensures that no value is present for ApprovedAt, not even an explicit nil
### GetApprovedBy

`func (o *InitialProposalDetailResponseProposal) GetApprovedBy() string`

GetApprovedBy returns the ApprovedBy field if non-nil, zero value otherwise.

### GetApprovedByOk

`func (o *InitialProposalDetailResponseProposal) GetApprovedByOk() (*string, bool)`

GetApprovedByOk returns a tuple with the ApprovedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedBy

`func (o *InitialProposalDetailResponseProposal) SetApprovedBy(v string)`

SetApprovedBy sets ApprovedBy field to given value.


### SetApprovedByNil

`func (o *InitialProposalDetailResponseProposal) SetApprovedByNil(b bool)`

 SetApprovedByNil sets the value for ApprovedBy to be an explicit nil

### UnsetApprovedBy
`func (o *InitialProposalDetailResponseProposal) UnsetApprovedBy()`

UnsetApprovedBy ensures that no value is present for ApprovedBy, not even an explicit nil
### GetApprovedRevisionId

`func (o *InitialProposalDetailResponseProposal) GetApprovedRevisionId() string`

GetApprovedRevisionId returns the ApprovedRevisionId field if non-nil, zero value otherwise.

### GetApprovedRevisionIdOk

`func (o *InitialProposalDetailResponseProposal) GetApprovedRevisionIdOk() (*string, bool)`

GetApprovedRevisionIdOk returns a tuple with the ApprovedRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedRevisionId

`func (o *InitialProposalDetailResponseProposal) SetApprovedRevisionId(v string)`

SetApprovedRevisionId sets ApprovedRevisionId field to given value.


### SetApprovedRevisionIdNil

`func (o *InitialProposalDetailResponseProposal) SetApprovedRevisionIdNil(b bool)`

 SetApprovedRevisionIdNil sets the value for ApprovedRevisionId to be an explicit nil

### UnsetApprovedRevisionId
`func (o *InitialProposalDetailResponseProposal) UnsetApprovedRevisionId()`

UnsetApprovedRevisionId ensures that no value is present for ApprovedRevisionId, not even an explicit nil
### GetCanvasBatchId

`func (o *InitialProposalDetailResponseProposal) GetCanvasBatchId() string`

GetCanvasBatchId returns the CanvasBatchId field if non-nil, zero value otherwise.

### GetCanvasBatchIdOk

`func (o *InitialProposalDetailResponseProposal) GetCanvasBatchIdOk() (*string, bool)`

GetCanvasBatchIdOk returns a tuple with the CanvasBatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasBatchId

`func (o *InitialProposalDetailResponseProposal) SetCanvasBatchId(v string)`

SetCanvasBatchId sets CanvasBatchId field to given value.


### SetCanvasBatchIdNil

`func (o *InitialProposalDetailResponseProposal) SetCanvasBatchIdNil(b bool)`

 SetCanvasBatchIdNil sets the value for CanvasBatchId to be an explicit nil

### UnsetCanvasBatchId
`func (o *InitialProposalDetailResponseProposal) UnsetCanvasBatchId()`

UnsetCanvasBatchId ensures that no value is present for CanvasBatchId, not even an explicit nil
### GetCanvasPublicationError

`func (o *InitialProposalDetailResponseProposal) GetCanvasPublicationError() string`

GetCanvasPublicationError returns the CanvasPublicationError field if non-nil, zero value otherwise.

### GetCanvasPublicationErrorOk

`func (o *InitialProposalDetailResponseProposal) GetCanvasPublicationErrorOk() (*string, bool)`

GetCanvasPublicationErrorOk returns a tuple with the CanvasPublicationError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasPublicationError

`func (o *InitialProposalDetailResponseProposal) SetCanvasPublicationError(v string)`

SetCanvasPublicationError sets CanvasPublicationError field to given value.


### SetCanvasPublicationErrorNil

`func (o *InitialProposalDetailResponseProposal) SetCanvasPublicationErrorNil(b bool)`

 SetCanvasPublicationErrorNil sets the value for CanvasPublicationError to be an explicit nil

### UnsetCanvasPublicationError
`func (o *InitialProposalDetailResponseProposal) UnsetCanvasPublicationError()`

UnsetCanvasPublicationError ensures that no value is present for CanvasPublicationError, not even an explicit nil
### GetCanvasPublishedAt

`func (o *InitialProposalDetailResponseProposal) GetCanvasPublishedAt() time.Time`

GetCanvasPublishedAt returns the CanvasPublishedAt field if non-nil, zero value otherwise.

### GetCanvasPublishedAtOk

`func (o *InitialProposalDetailResponseProposal) GetCanvasPublishedAtOk() (*time.Time, bool)`

GetCanvasPublishedAtOk returns a tuple with the CanvasPublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasPublishedAt

`func (o *InitialProposalDetailResponseProposal) SetCanvasPublishedAt(v time.Time)`

SetCanvasPublishedAt sets CanvasPublishedAt field to given value.


### SetCanvasPublishedAtNil

`func (o *InitialProposalDetailResponseProposal) SetCanvasPublishedAtNil(b bool)`

 SetCanvasPublishedAtNil sets the value for CanvasPublishedAt to be an explicit nil

### UnsetCanvasPublishedAt
`func (o *InitialProposalDetailResponseProposal) UnsetCanvasPublishedAt()`

UnsetCanvasPublishedAt ensures that no value is present for CanvasPublishedAt, not even an explicit nil
### GetClientDecidedAt

`func (o *InitialProposalDetailResponseProposal) GetClientDecidedAt() time.Time`

GetClientDecidedAt returns the ClientDecidedAt field if non-nil, zero value otherwise.

### GetClientDecidedAtOk

`func (o *InitialProposalDetailResponseProposal) GetClientDecidedAtOk() (*time.Time, bool)`

GetClientDecidedAtOk returns a tuple with the ClientDecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientDecidedAt

`func (o *InitialProposalDetailResponseProposal) SetClientDecidedAt(v time.Time)`

SetClientDecidedAt sets ClientDecidedAt field to given value.


### SetClientDecidedAtNil

`func (o *InitialProposalDetailResponseProposal) SetClientDecidedAtNil(b bool)`

 SetClientDecidedAtNil sets the value for ClientDecidedAt to be an explicit nil

### UnsetClientDecidedAt
`func (o *InitialProposalDetailResponseProposal) UnsetClientDecidedAt()`

UnsetClientDecidedAt ensures that no value is present for ClientDecidedAt, not even an explicit nil
### GetClientDecidedBy

`func (o *InitialProposalDetailResponseProposal) GetClientDecidedBy() string`

GetClientDecidedBy returns the ClientDecidedBy field if non-nil, zero value otherwise.

### GetClientDecidedByOk

`func (o *InitialProposalDetailResponseProposal) GetClientDecidedByOk() (*string, bool)`

GetClientDecidedByOk returns a tuple with the ClientDecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientDecidedBy

`func (o *InitialProposalDetailResponseProposal) SetClientDecidedBy(v string)`

SetClientDecidedBy sets ClientDecidedBy field to given value.


### SetClientDecidedByNil

`func (o *InitialProposalDetailResponseProposal) SetClientDecidedByNil(b bool)`

 SetClientDecidedByNil sets the value for ClientDecidedBy to be an explicit nil

### UnsetClientDecidedBy
`func (o *InitialProposalDetailResponseProposal) UnsetClientDecidedBy()`

UnsetClientDecidedBy ensures that no value is present for ClientDecidedBy, not even an explicit nil
### GetClientDecision

`func (o *InitialProposalDetailResponseProposal) GetClientDecision() string`

GetClientDecision returns the ClientDecision field if non-nil, zero value otherwise.

### GetClientDecisionOk

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionOk() (*string, bool)`

GetClientDecisionOk returns a tuple with the ClientDecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientDecision

`func (o *InitialProposalDetailResponseProposal) SetClientDecision(v string)`

SetClientDecision sets ClientDecision field to given value.


### SetClientDecisionNil

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionNil(b bool)`

 SetClientDecisionNil sets the value for ClientDecision to be an explicit nil

### UnsetClientDecision
`func (o *InitialProposalDetailResponseProposal) UnsetClientDecision()`

UnsetClientDecision ensures that no value is present for ClientDecision, not even an explicit nil
### GetClientDecisionComment

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionComment() string`

GetClientDecisionComment returns the ClientDecisionComment field if non-nil, zero value otherwise.

### GetClientDecisionCommentOk

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionCommentOk() (*string, bool)`

GetClientDecisionCommentOk returns a tuple with the ClientDecisionComment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientDecisionComment

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionComment(v string)`

SetClientDecisionComment sets ClientDecisionComment field to given value.


### SetClientDecisionCommentNil

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionCommentNil(b bool)`

 SetClientDecisionCommentNil sets the value for ClientDecisionComment to be an explicit nil

### UnsetClientDecisionComment
`func (o *InitialProposalDetailResponseProposal) UnsetClientDecisionComment()`

UnsetClientDecisionComment ensures that no value is present for ClientDecisionComment, not even an explicit nil
### GetClientDecisionRevisionHash

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionRevisionHash() string`

GetClientDecisionRevisionHash returns the ClientDecisionRevisionHash field if non-nil, zero value otherwise.

### GetClientDecisionRevisionHashOk

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionRevisionHashOk() (*string, bool)`

GetClientDecisionRevisionHashOk returns a tuple with the ClientDecisionRevisionHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientDecisionRevisionHash

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionRevisionHash(v string)`

SetClientDecisionRevisionHash sets ClientDecisionRevisionHash field to given value.


### SetClientDecisionRevisionHashNil

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionRevisionHashNil(b bool)`

 SetClientDecisionRevisionHashNil sets the value for ClientDecisionRevisionHash to be an explicit nil

### UnsetClientDecisionRevisionHash
`func (o *InitialProposalDetailResponseProposal) UnsetClientDecisionRevisionHash()`

UnsetClientDecisionRevisionHash ensures that no value is present for ClientDecisionRevisionHash, not even an explicit nil
### GetClientDecisionRevisionId

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionRevisionId() string`

GetClientDecisionRevisionId returns the ClientDecisionRevisionId field if non-nil, zero value otherwise.

### GetClientDecisionRevisionIdOk

`func (o *InitialProposalDetailResponseProposal) GetClientDecisionRevisionIdOk() (*string, bool)`

GetClientDecisionRevisionIdOk returns a tuple with the ClientDecisionRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientDecisionRevisionId

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionRevisionId(v string)`

SetClientDecisionRevisionId sets ClientDecisionRevisionId field to given value.


### SetClientDecisionRevisionIdNil

`func (o *InitialProposalDetailResponseProposal) SetClientDecisionRevisionIdNil(b bool)`

 SetClientDecisionRevisionIdNil sets the value for ClientDecisionRevisionId to be an explicit nil

### UnsetClientDecisionRevisionId
`func (o *InitialProposalDetailResponseProposal) UnsetClientDecisionRevisionId()`

UnsetClientDecisionRevisionId ensures that no value is present for ClientDecisionRevisionId, not even an explicit nil
### GetClientReviewerId

`func (o *InitialProposalDetailResponseProposal) GetClientReviewerId() string`

GetClientReviewerId returns the ClientReviewerId field if non-nil, zero value otherwise.

### GetClientReviewerIdOk

`func (o *InitialProposalDetailResponseProposal) GetClientReviewerIdOk() (*string, bool)`

GetClientReviewerIdOk returns a tuple with the ClientReviewerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientReviewerId

`func (o *InitialProposalDetailResponseProposal) SetClientReviewerId(v string)`

SetClientReviewerId sets ClientReviewerId field to given value.


### SetClientReviewerIdNil

`func (o *InitialProposalDetailResponseProposal) SetClientReviewerIdNil(b bool)`

 SetClientReviewerIdNil sets the value for ClientReviewerId to be an explicit nil

### UnsetClientReviewerId
`func (o *InitialProposalDetailResponseProposal) UnsetClientReviewerId()`

UnsetClientReviewerId ensures that no value is present for ClientReviewerId, not even an explicit nil
### GetCreatedAt

`func (o *InitialProposalDetailResponseProposal) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitialProposalDetailResponseProposal) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitialProposalDetailResponseProposal) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrentRevisionId

`func (o *InitialProposalDetailResponseProposal) GetCurrentRevisionId() string`

GetCurrentRevisionId returns the CurrentRevisionId field if non-nil, zero value otherwise.

### GetCurrentRevisionIdOk

`func (o *InitialProposalDetailResponseProposal) GetCurrentRevisionIdOk() (*string, bool)`

GetCurrentRevisionIdOk returns a tuple with the CurrentRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentRevisionId

`func (o *InitialProposalDetailResponseProposal) SetCurrentRevisionId(v string)`

SetCurrentRevisionId sets CurrentRevisionId field to given value.


### SetCurrentRevisionIdNil

`func (o *InitialProposalDetailResponseProposal) SetCurrentRevisionIdNil(b bool)`

 SetCurrentRevisionIdNil sets the value for CurrentRevisionId to be an explicit nil

### UnsetCurrentRevisionId
`func (o *InitialProposalDetailResponseProposal) UnsetCurrentRevisionId()`

UnsetCurrentRevisionId ensures that no value is present for CurrentRevisionId, not even an explicit nil
### GetId

`func (o *InitialProposalDetailResponseProposal) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitialProposalDetailResponseProposal) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitialProposalDetailResponseProposal) SetId(v string)`

SetId sets Id field to given value.


### GetOperationId

`func (o *InitialProposalDetailResponseProposal) GetOperationId() string`

GetOperationId returns the OperationId field if non-nil, zero value otherwise.

### GetOperationIdOk

`func (o *InitialProposalDetailResponseProposal) GetOperationIdOk() (*string, bool)`

GetOperationIdOk returns a tuple with the OperationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationId

`func (o *InitialProposalDetailResponseProposal) SetOperationId(v string)`

SetOperationId sets OperationId field to given value.


### SetOperationIdNil

`func (o *InitialProposalDetailResponseProposal) SetOperationIdNil(b bool)`

 SetOperationIdNil sets the value for OperationId to be an explicit nil

### UnsetOperationId
`func (o *InitialProposalDetailResponseProposal) UnsetOperationId()`

UnsetOperationId ensures that no value is present for OperationId, not even an explicit nil
### GetOperationLeaseExpiresAt

`func (o *InitialProposalDetailResponseProposal) GetOperationLeaseExpiresAt() time.Time`

GetOperationLeaseExpiresAt returns the OperationLeaseExpiresAt field if non-nil, zero value otherwise.

### GetOperationLeaseExpiresAtOk

`func (o *InitialProposalDetailResponseProposal) GetOperationLeaseExpiresAtOk() (*time.Time, bool)`

GetOperationLeaseExpiresAtOk returns a tuple with the OperationLeaseExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationLeaseExpiresAt

`func (o *InitialProposalDetailResponseProposal) SetOperationLeaseExpiresAt(v time.Time)`

SetOperationLeaseExpiresAt sets OperationLeaseExpiresAt field to given value.


### SetOperationLeaseExpiresAtNil

`func (o *InitialProposalDetailResponseProposal) SetOperationLeaseExpiresAtNil(b bool)`

 SetOperationLeaseExpiresAtNil sets the value for OperationLeaseExpiresAt to be an explicit nil

### UnsetOperationLeaseExpiresAt
`func (o *InitialProposalDetailResponseProposal) UnsetOperationLeaseExpiresAt()`

UnsetOperationLeaseExpiresAt ensures that no value is present for OperationLeaseExpiresAt, not even an explicit nil
### GetOperationLeaseToken

`func (o *InitialProposalDetailResponseProposal) GetOperationLeaseToken() string`

GetOperationLeaseToken returns the OperationLeaseToken field if non-nil, zero value otherwise.

### GetOperationLeaseTokenOk

`func (o *InitialProposalDetailResponseProposal) GetOperationLeaseTokenOk() (*string, bool)`

GetOperationLeaseTokenOk returns a tuple with the OperationLeaseToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationLeaseToken

`func (o *InitialProposalDetailResponseProposal) SetOperationLeaseToken(v string)`

SetOperationLeaseToken sets OperationLeaseToken field to given value.


### SetOperationLeaseTokenNil

`func (o *InitialProposalDetailResponseProposal) SetOperationLeaseTokenNil(b bool)`

 SetOperationLeaseTokenNil sets the value for OperationLeaseToken to be an explicit nil

### UnsetOperationLeaseToken
`func (o *InitialProposalDetailResponseProposal) UnsetOperationLeaseToken()`

UnsetOperationLeaseToken ensures that no value is present for OperationLeaseToken, not even an explicit nil
### GetOrganizationId

`func (o *InitialProposalDetailResponseProposal) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *InitialProposalDetailResponseProposal) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *InitialProposalDetailResponseProposal) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *InitialProposalDetailResponseProposal) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *InitialProposalDetailResponseProposal) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *InitialProposalDetailResponseProposal) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetPublishedRevisionId

`func (o *InitialProposalDetailResponseProposal) GetPublishedRevisionId() string`

GetPublishedRevisionId returns the PublishedRevisionId field if non-nil, zero value otherwise.

### GetPublishedRevisionIdOk

`func (o *InitialProposalDetailResponseProposal) GetPublishedRevisionIdOk() (*string, bool)`

GetPublishedRevisionIdOk returns a tuple with the PublishedRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedRevisionId

`func (o *InitialProposalDetailResponseProposal) SetPublishedRevisionId(v string)`

SetPublishedRevisionId sets PublishedRevisionId field to given value.


### SetPublishedRevisionIdNil

`func (o *InitialProposalDetailResponseProposal) SetPublishedRevisionIdNil(b bool)`

 SetPublishedRevisionIdNil sets the value for PublishedRevisionId to be an explicit nil

### UnsetPublishedRevisionId
`func (o *InitialProposalDetailResponseProposal) UnsetPublishedRevisionId()`

UnsetPublishedRevisionId ensures that no value is present for PublishedRevisionId, not even an explicit nil
### GetUpdatedAt

`func (o *InitialProposalDetailResponseProposal) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *InitialProposalDetailResponseProposal) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *InitialProposalDetailResponseProposal) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVisibility

`func (o *InitialProposalDetailResponseProposal) GetVisibility() string`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *InitialProposalDetailResponseProposal) GetVisibilityOk() (*string, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *InitialProposalDetailResponseProposal) SetVisibility(v string)`

SetVisibility sets Visibility field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


