# InitialProposalRevision

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgencyReviewDecision** | Pointer to [**NullableInitialProposalDetailResponseRevisionAgencyReviewDecision**](InitialProposalDetailResponseRevisionAgencyReviewDecision.md) |  | [optional]
**BaseRevisionId** | **NullableString** |  |
**CompletedAt** | **NullableTime** |  |
**Content** | [**NullableInitialProposalDetailResponseRevisionContent**](InitialProposalDetailResponseRevisionContent.md) |  |
**ContentHash** | **NullableString** |  |
**CreatedAt** | **time.Time** |  |
**Error** | **NullableString** |  |
**Id** | **string** |  |
**InitialScopeCredits** | **NullableInt32** |  |
**InputFingerprint** | **string** |  |
**Instruction** | **NullableString** |  |
**Kind** | **string** |  |
**OrganizationId** | **string** |  |
**ProjectId** | **string** |  |
**ProposalId** | **string** |  |
**QuoteComplete** | **bool** |  |
**Revision** | **int32** |  |
**Status** | **string** |  |

## Methods

### NewInitialProposalRevision

`func NewInitialProposalRevision(baseRevisionId NullableString, completedAt NullableTime, content NullableInitialProposalDetailResponseRevisionContent, contentHash NullableString, createdAt time.Time, error_ NullableString, id string, initialScopeCredits NullableInt32, inputFingerprint string, instruction NullableString, kind string, organizationId string, projectId string, proposalId string, quoteComplete bool, revision int32, status string, ) *InitialProposalRevision`

NewInitialProposalRevision instantiates a new InitialProposalRevision object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewInitialProposalRevisionWithDefaults

`func NewInitialProposalRevisionWithDefaults() *InitialProposalRevision`

NewInitialProposalRevisionWithDefaults instantiates a new InitialProposalRevision object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgencyReviewDecision

`func (o *InitialProposalRevision) GetAgencyReviewDecision() InitialProposalDetailResponseRevisionAgencyReviewDecision`

GetAgencyReviewDecision returns the AgencyReviewDecision field if non-nil, zero value otherwise.

### GetAgencyReviewDecisionOk

`func (o *InitialProposalRevision) GetAgencyReviewDecisionOk() (*InitialProposalDetailResponseRevisionAgencyReviewDecision, bool)`

GetAgencyReviewDecisionOk returns a tuple with the AgencyReviewDecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgencyReviewDecision

`func (o *InitialProposalRevision) SetAgencyReviewDecision(v InitialProposalDetailResponseRevisionAgencyReviewDecision)`

SetAgencyReviewDecision sets AgencyReviewDecision field to given value.

### HasAgencyReviewDecision

`func (o *InitialProposalRevision) HasAgencyReviewDecision() bool`

HasAgencyReviewDecision returns a boolean if a field has been set.

### SetAgencyReviewDecisionNil

`func (o *InitialProposalRevision) SetAgencyReviewDecisionNil(b bool)`

 SetAgencyReviewDecisionNil sets the value for AgencyReviewDecision to be an explicit nil

### UnsetAgencyReviewDecision
`func (o *InitialProposalRevision) UnsetAgencyReviewDecision()`

UnsetAgencyReviewDecision ensures that no value is present for AgencyReviewDecision, not even an explicit nil
### GetBaseRevisionId

`func (o *InitialProposalRevision) GetBaseRevisionId() string`

GetBaseRevisionId returns the BaseRevisionId field if non-nil, zero value otherwise.

### GetBaseRevisionIdOk

`func (o *InitialProposalRevision) GetBaseRevisionIdOk() (*string, bool)`

GetBaseRevisionIdOk returns a tuple with the BaseRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseRevisionId

`func (o *InitialProposalRevision) SetBaseRevisionId(v string)`

SetBaseRevisionId sets BaseRevisionId field to given value.


### SetBaseRevisionIdNil

`func (o *InitialProposalRevision) SetBaseRevisionIdNil(b bool)`

 SetBaseRevisionIdNil sets the value for BaseRevisionId to be an explicit nil

### UnsetBaseRevisionId
`func (o *InitialProposalRevision) UnsetBaseRevisionId()`

UnsetBaseRevisionId ensures that no value is present for BaseRevisionId, not even an explicit nil
### GetCompletedAt

`func (o *InitialProposalRevision) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *InitialProposalRevision) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *InitialProposalRevision) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *InitialProposalRevision) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *InitialProposalRevision) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetContent

`func (o *InitialProposalRevision) GetContent() InitialProposalDetailResponseRevisionContent`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *InitialProposalRevision) GetContentOk() (*InitialProposalDetailResponseRevisionContent, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *InitialProposalRevision) SetContent(v InitialProposalDetailResponseRevisionContent)`

SetContent sets Content field to given value.


### SetContentNil

`func (o *InitialProposalRevision) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *InitialProposalRevision) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetContentHash

`func (o *InitialProposalRevision) GetContentHash() string`

GetContentHash returns the ContentHash field if non-nil, zero value otherwise.

### GetContentHashOk

`func (o *InitialProposalRevision) GetContentHashOk() (*string, bool)`

GetContentHashOk returns a tuple with the ContentHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentHash

`func (o *InitialProposalRevision) SetContentHash(v string)`

SetContentHash sets ContentHash field to given value.


### SetContentHashNil

`func (o *InitialProposalRevision) SetContentHashNil(b bool)`

 SetContentHashNil sets the value for ContentHash to be an explicit nil

### UnsetContentHash
`func (o *InitialProposalRevision) UnsetContentHash()`

UnsetContentHash ensures that no value is present for ContentHash, not even an explicit nil
### GetCreatedAt

`func (o *InitialProposalRevision) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitialProposalRevision) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitialProposalRevision) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *InitialProposalRevision) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InitialProposalRevision) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InitialProposalRevision) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *InitialProposalRevision) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *InitialProposalRevision) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *InitialProposalRevision) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitialProposalRevision) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitialProposalRevision) SetId(v string)`

SetId sets Id field to given value.


### GetInitialScopeCredits

`func (o *InitialProposalRevision) GetInitialScopeCredits() int32`

GetInitialScopeCredits returns the InitialScopeCredits field if non-nil, zero value otherwise.

### GetInitialScopeCreditsOk

`func (o *InitialProposalRevision) GetInitialScopeCreditsOk() (*int32, bool)`

GetInitialScopeCreditsOk returns a tuple with the InitialScopeCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialScopeCredits

`func (o *InitialProposalRevision) SetInitialScopeCredits(v int32)`

SetInitialScopeCredits sets InitialScopeCredits field to given value.


### SetInitialScopeCreditsNil

`func (o *InitialProposalRevision) SetInitialScopeCreditsNil(b bool)`

 SetInitialScopeCreditsNil sets the value for InitialScopeCredits to be an explicit nil

### UnsetInitialScopeCredits
`func (o *InitialProposalRevision) UnsetInitialScopeCredits()`

UnsetInitialScopeCredits ensures that no value is present for InitialScopeCredits, not even an explicit nil
### GetInputFingerprint

`func (o *InitialProposalRevision) GetInputFingerprint() string`

GetInputFingerprint returns the InputFingerprint field if non-nil, zero value otherwise.

### GetInputFingerprintOk

`func (o *InitialProposalRevision) GetInputFingerprintOk() (*string, bool)`

GetInputFingerprintOk returns a tuple with the InputFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputFingerprint

`func (o *InitialProposalRevision) SetInputFingerprint(v string)`

SetInputFingerprint sets InputFingerprint field to given value.


### GetInstruction

`func (o *InitialProposalRevision) GetInstruction() string`

GetInstruction returns the Instruction field if non-nil, zero value otherwise.

### GetInstructionOk

`func (o *InitialProposalRevision) GetInstructionOk() (*string, bool)`

GetInstructionOk returns a tuple with the Instruction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstruction

`func (o *InitialProposalRevision) SetInstruction(v string)`

SetInstruction sets Instruction field to given value.


### SetInstructionNil

`func (o *InitialProposalRevision) SetInstructionNil(b bool)`

 SetInstructionNil sets the value for Instruction to be an explicit nil

### UnsetInstruction
`func (o *InitialProposalRevision) UnsetInstruction()`

UnsetInstruction ensures that no value is present for Instruction, not even an explicit nil
### GetKind

`func (o *InitialProposalRevision) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *InitialProposalRevision) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *InitialProposalRevision) SetKind(v string)`

SetKind sets Kind field to given value.


### GetOrganizationId

`func (o *InitialProposalRevision) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *InitialProposalRevision) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *InitialProposalRevision) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *InitialProposalRevision) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *InitialProposalRevision) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *InitialProposalRevision) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProposalId

`func (o *InitialProposalRevision) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *InitialProposalRevision) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *InitialProposalRevision) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### GetQuoteComplete

`func (o *InitialProposalRevision) GetQuoteComplete() bool`

GetQuoteComplete returns the QuoteComplete field if non-nil, zero value otherwise.

### GetQuoteCompleteOk

`func (o *InitialProposalRevision) GetQuoteCompleteOk() (*bool, bool)`

GetQuoteCompleteOk returns a tuple with the QuoteComplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteComplete

`func (o *InitialProposalRevision) SetQuoteComplete(v bool)`

SetQuoteComplete sets QuoteComplete field to given value.


### GetRevision

`func (o *InitialProposalRevision) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *InitialProposalRevision) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *InitialProposalRevision) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetStatus

`func (o *InitialProposalRevision) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InitialProposalRevision) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InitialProposalRevision) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


