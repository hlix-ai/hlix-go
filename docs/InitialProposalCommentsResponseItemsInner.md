# InitialProposalCommentsResponseItemsInner

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

### NewInitialProposalCommentsResponseItemsInner

`func NewInitialProposalCommentsResponseItemsInner(authorId string, authorType string, blockId string, body string, createdAt time.Time, id string, organizationId string, parentId NullableString, projectId string, proposalId string, resolvedAt NullableTime, resolvedBy NullableString, revisionHash string, revisionId string, selectedText NullableString, updatedAt time.Time, ) *InitialProposalCommentsResponseItemsInner`

NewInitialProposalCommentsResponseItemsInner instantiates a new InitialProposalCommentsResponseItemsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitialProposalCommentsResponseItemsInnerWithDefaults

`func NewInitialProposalCommentsResponseItemsInnerWithDefaults() *InitialProposalCommentsResponseItemsInner`

NewInitialProposalCommentsResponseItemsInnerWithDefaults instantiates a new InitialProposalCommentsResponseItemsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthorId

`func (o *InitialProposalCommentsResponseItemsInner) GetAuthorId() string`

GetAuthorId returns the AuthorId field if non-nil, zero value otherwise.

### GetAuthorIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetAuthorIdOk() (*string, bool)`

GetAuthorIdOk returns a tuple with the AuthorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorId

`func (o *InitialProposalCommentsResponseItemsInner) SetAuthorId(v string)`

SetAuthorId sets AuthorId field to given value.


### GetAuthorType

`func (o *InitialProposalCommentsResponseItemsInner) GetAuthorType() string`

GetAuthorType returns the AuthorType field if non-nil, zero value otherwise.

### GetAuthorTypeOk

`func (o *InitialProposalCommentsResponseItemsInner) GetAuthorTypeOk() (*string, bool)`

GetAuthorTypeOk returns a tuple with the AuthorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorType

`func (o *InitialProposalCommentsResponseItemsInner) SetAuthorType(v string)`

SetAuthorType sets AuthorType field to given value.


### GetBlockId

`func (o *InitialProposalCommentsResponseItemsInner) GetBlockId() string`

GetBlockId returns the BlockId field if non-nil, zero value otherwise.

### GetBlockIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetBlockIdOk() (*string, bool)`

GetBlockIdOk returns a tuple with the BlockId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockId

`func (o *InitialProposalCommentsResponseItemsInner) SetBlockId(v string)`

SetBlockId sets BlockId field to given value.


### GetBody

`func (o *InitialProposalCommentsResponseItemsInner) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *InitialProposalCommentsResponseItemsInner) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *InitialProposalCommentsResponseItemsInner) SetBody(v string)`

SetBody sets Body field to given value.


### GetCreatedAt

`func (o *InitialProposalCommentsResponseItemsInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitialProposalCommentsResponseItemsInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitialProposalCommentsResponseItemsInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *InitialProposalCommentsResponseItemsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitialProposalCommentsResponseItemsInner) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *InitialProposalCommentsResponseItemsInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *InitialProposalCommentsResponseItemsInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetParentId

`func (o *InitialProposalCommentsResponseItemsInner) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *InitialProposalCommentsResponseItemsInner) SetParentId(v string)`

SetParentId sets ParentId field to given value.


### SetParentIdNil

`func (o *InitialProposalCommentsResponseItemsInner) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *InitialProposalCommentsResponseItemsInner) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil
### GetProjectId

`func (o *InitialProposalCommentsResponseItemsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *InitialProposalCommentsResponseItemsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProposalId

`func (o *InitialProposalCommentsResponseItemsInner) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *InitialProposalCommentsResponseItemsInner) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### GetResolvedAt

`func (o *InitialProposalCommentsResponseItemsInner) GetResolvedAt() time.Time`

GetResolvedAt returns the ResolvedAt field if non-nil, zero value otherwise.

### GetResolvedAtOk

`func (o *InitialProposalCommentsResponseItemsInner) GetResolvedAtOk() (*time.Time, bool)`

GetResolvedAtOk returns a tuple with the ResolvedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAt

`func (o *InitialProposalCommentsResponseItemsInner) SetResolvedAt(v time.Time)`

SetResolvedAt sets ResolvedAt field to given value.


### SetResolvedAtNil

`func (o *InitialProposalCommentsResponseItemsInner) SetResolvedAtNil(b bool)`

 SetResolvedAtNil sets the value for ResolvedAt to be an explicit nil

### UnsetResolvedAt
`func (o *InitialProposalCommentsResponseItemsInner) UnsetResolvedAt()`

UnsetResolvedAt ensures that no value is present for ResolvedAt, not even an explicit nil
### GetResolvedBy

`func (o *InitialProposalCommentsResponseItemsInner) GetResolvedBy() string`

GetResolvedBy returns the ResolvedBy field if non-nil, zero value otherwise.

### GetResolvedByOk

`func (o *InitialProposalCommentsResponseItemsInner) GetResolvedByOk() (*string, bool)`

GetResolvedByOk returns a tuple with the ResolvedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedBy

`func (o *InitialProposalCommentsResponseItemsInner) SetResolvedBy(v string)`

SetResolvedBy sets ResolvedBy field to given value.


### SetResolvedByNil

`func (o *InitialProposalCommentsResponseItemsInner) SetResolvedByNil(b bool)`

 SetResolvedByNil sets the value for ResolvedBy to be an explicit nil

### UnsetResolvedBy
`func (o *InitialProposalCommentsResponseItemsInner) UnsetResolvedBy()`

UnsetResolvedBy ensures that no value is present for ResolvedBy, not even an explicit nil
### GetRevisionHash

`func (o *InitialProposalCommentsResponseItemsInner) GetRevisionHash() string`

GetRevisionHash returns the RevisionHash field if non-nil, zero value otherwise.

### GetRevisionHashOk

`func (o *InitialProposalCommentsResponseItemsInner) GetRevisionHashOk() (*string, bool)`

GetRevisionHashOk returns a tuple with the RevisionHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionHash

`func (o *InitialProposalCommentsResponseItemsInner) SetRevisionHash(v string)`

SetRevisionHash sets RevisionHash field to given value.


### GetRevisionId

`func (o *InitialProposalCommentsResponseItemsInner) GetRevisionId() string`

GetRevisionId returns the RevisionId field if non-nil, zero value otherwise.

### GetRevisionIdOk

`func (o *InitialProposalCommentsResponseItemsInner) GetRevisionIdOk() (*string, bool)`

GetRevisionIdOk returns a tuple with the RevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionId

`func (o *InitialProposalCommentsResponseItemsInner) SetRevisionId(v string)`

SetRevisionId sets RevisionId field to given value.


### GetSelectedText

`func (o *InitialProposalCommentsResponseItemsInner) GetSelectedText() string`

GetSelectedText returns the SelectedText field if non-nil, zero value otherwise.

### GetSelectedTextOk

`func (o *InitialProposalCommentsResponseItemsInner) GetSelectedTextOk() (*string, bool)`

GetSelectedTextOk returns a tuple with the SelectedText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedText

`func (o *InitialProposalCommentsResponseItemsInner) SetSelectedText(v string)`

SetSelectedText sets SelectedText field to given value.


### SetSelectedTextNil

`func (o *InitialProposalCommentsResponseItemsInner) SetSelectedTextNil(b bool)`

 SetSelectedTextNil sets the value for SelectedText to be an explicit nil

### UnsetSelectedText
`func (o *InitialProposalCommentsResponseItemsInner) UnsetSelectedText()`

UnsetSelectedText ensures that no value is present for SelectedText, not even an explicit nil
### GetUpdatedAt

`func (o *InitialProposalCommentsResponseItemsInner) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *InitialProposalCommentsResponseItemsInner) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *InitialProposalCommentsResponseItemsInner) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


