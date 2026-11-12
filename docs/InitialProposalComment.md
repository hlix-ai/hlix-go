# InitialProposalComment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthorId** | **string** |  |
**AuthorType** | **string** |  |
**BlockId** | **string** |  |
**Body** | **string** |  |
**CreatedAt** | **time.Time** |  |
**Id** | **string** |  |
**OrganizationId** | **string** |  |
**ParentId** | **NullableString** |  |
**ProjectId** | **string** |  |
**ProposalId** | **string** |  |
**ResolvedAt** | **NullableTime** |  |
**ResolvedBy** | **NullableString** |  |
**RevisionHash** | **string** |  |
**RevisionId** | **string** |  |
**SelectedText** | **NullableString** |  |
**UpdatedAt** | **time.Time** |  |

## Methods

### NewInitialProposalComment

`func NewInitialProposalComment(authorId string, authorType string, blockId string, body string, createdAt time.Time, id string, organizationId string, parentId NullableString, projectId string, proposalId string, resolvedAt NullableTime, resolvedBy NullableString, revisionHash string, revisionId string, selectedText NullableString, updatedAt time.Time, ) *InitialProposalComment`

NewInitialProposalComment instantiates a new InitialProposalComment object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewInitialProposalCommentWithDefaults

`func NewInitialProposalCommentWithDefaults() *InitialProposalComment`

NewInitialProposalCommentWithDefaults instantiates a new InitialProposalComment object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAuthorId

`func (o *InitialProposalComment) GetAuthorId() string`

GetAuthorId returns the AuthorId field if non-nil, zero value otherwise.

### GetAuthorIdOk

`func (o *InitialProposalComment) GetAuthorIdOk() (*string, bool)`

GetAuthorIdOk returns a tuple with the AuthorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorId

`func (o *InitialProposalComment) SetAuthorId(v string)`

SetAuthorId sets AuthorId field to given value.


### GetAuthorType

`func (o *InitialProposalComment) GetAuthorType() string`

GetAuthorType returns the AuthorType field if non-nil, zero value otherwise.

### GetAuthorTypeOk

`func (o *InitialProposalComment) GetAuthorTypeOk() (*string, bool)`

GetAuthorTypeOk returns a tuple with the AuthorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorType

`func (o *InitialProposalComment) SetAuthorType(v string)`

SetAuthorType sets AuthorType field to given value.


### GetBlockId

`func (o *InitialProposalComment) GetBlockId() string`

GetBlockId returns the BlockId field if non-nil, zero value otherwise.

### GetBlockIdOk

`func (o *InitialProposalComment) GetBlockIdOk() (*string, bool)`

GetBlockIdOk returns a tuple with the BlockId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockId

`func (o *InitialProposalComment) SetBlockId(v string)`

SetBlockId sets BlockId field to given value.


### GetBody

`func (o *InitialProposalComment) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *InitialProposalComment) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *InitialProposalComment) SetBody(v string)`

SetBody sets Body field to given value.


### GetCreatedAt

`func (o *InitialProposalComment) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitialProposalComment) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitialProposalComment) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *InitialProposalComment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitialProposalComment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitialProposalComment) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *InitialProposalComment) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *InitialProposalComment) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *InitialProposalComment) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetParentId

`func (o *InitialProposalComment) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *InitialProposalComment) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *InitialProposalComment) SetParentId(v string)`

SetParentId sets ParentId field to given value.


### SetParentIdNil

`func (o *InitialProposalComment) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *InitialProposalComment) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil
### GetProjectId

`func (o *InitialProposalComment) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *InitialProposalComment) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *InitialProposalComment) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProposalId

`func (o *InitialProposalComment) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *InitialProposalComment) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *InitialProposalComment) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### GetResolvedAt

`func (o *InitialProposalComment) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *InitialProposalComment) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *InitialProposalComment) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.


### SetResolvedAtNil

`func (o *InitialProposalComment) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *InitialProposalComment) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *InitialProposalComment) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *InitialProposalComment) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *InitialProposalComment) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.


### SetResolvedByNil

`func (o *InitialProposalComment) SetResolvedByNil(b bool)`

 SetResolvedByNil sets the value for ResolvedBy to be an explicit nil

### UnsetResolvedBy
`func (o *InitialProposalComment) UnsetResolvedBy()`

UnsetResolvedBy ensures that no value is present for ResolvedBy, not even an explicit nil
### GetRevisionHash

`func (o *InitialProposalComment) GetRevisionHash() string`

GetRevisionHash returns the RevisionHash field if non-nil, zero value otherwise.

### GetRevisionHashOk

`func (o *InitialProposalComment) GetRevisionHashOk() (*string, bool)`

GetRevisionHashOk returns a tuple with the RevisionHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionHash

`func (o *InitialProposalComment) SetRevisionHash(v string)`

SetRevisionHash sets RevisionHash field to given value.


### GetRevisionId

`func (o *InitialProposalComment) GetRevisionId() string`

GetRevisionId returns the RevisionId field if non-nil, zero value otherwise.

### GetRevisionIdOk

`func (o *InitialProposalComment) GetRevisionIdOk() (*string, bool)`

GetRevisionIdOk returns a tuple with the RevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionId

`func (o *InitialProposalComment) SetRevisionId(v string)`

SetRevisionId sets RevisionId field to given value.


### GetSelectedText

`func (o *InitialProposalComment) GetSelectedText() string`

GetSelectedText returns the SelectedText field if non-nil, zero value otherwise.

### GetSelectedTextOk

`func (o *InitialProposalComment) GetSelectedTextOk() (*string, bool)`

GetSelectedTextOk returns a tuple with the SelectedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedText

`func (o *InitialProposalComment) SetSelectedText(v string)`

SetSelectedText sets SelectedText field to given value.


### SetSelectedTextNil

`func (o *InitialProposalComment) SetSelectedTextNil(b bool)`

 SetSelectedTextNil sets the value for SelectedText to be an explicit nil

### UnsetSelectedText
`func (o *InitialProposalComment) UnsetSelectedText()`

UnsetSelectedText ensures that no value is present for SelectedText, not even an explicit nil
### GetUpdatedAt

`func (o *InitialProposalComment) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *InitialProposalComment) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *InitialProposalComment) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


