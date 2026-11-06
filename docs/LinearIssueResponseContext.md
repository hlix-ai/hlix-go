# LinearIssueResponseContext

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | **bool** |  | 
**Assignee** | **NullableString** |  | 
**Attachments** | [**[]LinearIssueResponseContextAttachmentsInner**](LinearIssueResponseContextAttachmentsInner.md) |  | 
**Children** | [**[]LinearIssueResponseContextChildrenInner**](LinearIssueResponseContextChildrenInner.md) |  | 
**Comments** | [**[]LinearIssueResponseContextCommentsInner**](LinearIssueResponseContextCommentsInner.md) |  | 
**Description** | **string** |  | 
**Id** | **string** |  | 
**Identifier** | **string** |  | 
**Labels** | [**[]HlixCodeModelsModelsInner**](HlixCodeModelsModelsInner.md) |  | 
**Parent** | [**NullableLinearIssueResponseContextParent**](LinearIssueResponseContextParent.md) |  | 
**Priority** | **string** |  | 
**Project** | [**NullableLinearIssueResponseContextProject**](LinearIssueResponseContextProject.md) |  | 
**State** | [**LinearIssueResponseContextState**](LinearIssueResponseContextState.md) |  | 
**Team** | [**LinearCatalogResponseTeamsInner**](LinearCatalogResponseTeamsInner.md) |  | 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 
**Url** | **string** |  | 

## Methods

### NewLinearIssueResponseContext

`func NewLinearIssueResponseContext(archived bool, assignee NullableString, attachments []LinearIssueResponseContextAttachmentsInner, children []LinearIssueResponseContextChildrenInner, comments []LinearIssueResponseContextCommentsInner, description string, id string, identifier string, labels []HlixCodeModelsModelsInner, parent NullableLinearIssueResponseContextParent, priority string, project NullableLinearIssueResponseContextProject, state LinearIssueResponseContextState, team LinearCatalogResponseTeamsInner, title string, updatedAt string, url string, ) *LinearIssueResponseContext`

NewLinearIssueResponseContext instantiates a new LinearIssueResponseContext object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinearIssueResponseContextWithDefaults

`func NewLinearIssueResponseContextWithDefaults() *LinearIssueResponseContext`

NewLinearIssueResponseContextWithDefaults instantiates a new LinearIssueResponseContext object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *LinearIssueResponseContext) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *LinearIssueResponseContext) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *LinearIssueResponseContext) SetArchived(v bool)`

SetArchived sets Archived field to given value.


### GetAssignee

`func (o *LinearIssueResponseContext) GetAssignee() string`

GetAssignee returns the Assignee field if non-nil, zero value otherwise.

### GetAssigneeOk

`func (o *LinearIssueResponseContext) GetAssigneeOk() (*string, bool)`

GetAssigneeOk returns a tuple with the Assignee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssignee

`func (o *LinearIssueResponseContext) SetAssignee(v string)`

SetAssignee sets Assignee field to given value.


### SetAssigneeNil

`func (o *LinearIssueResponseContext) SetAssigneeNil(b bool)`

 SetAssigneeNil sets the value for Assignee to be an explicit nil

### UnsetAssignee
`func (o *LinearIssueResponseContext) UnsetAssignee()`

UnsetAssignee ensures that no value is present for Assignee, not even an explicit nil
### GetAttachments

`func (o *LinearIssueResponseContext) GetAttachments() []LinearIssueResponseContextAttachmentsInner`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *LinearIssueResponseContext) GetAttachmentsOk() (*[]LinearIssueResponseContextAttachmentsInner, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *LinearIssueResponseContext) SetAttachments(v []LinearIssueResponseContextAttachmentsInner)`

SetAttachments sets Attachments field to given value.


### GetChildren

`func (o *LinearIssueResponseContext) GetChildren() []LinearIssueResponseContextChildrenInner`

GetChildren returns the Children field if non-nil, zero value otherwise.

### GetChildrenOk

`func (o *LinearIssueResponseContext) GetChildrenOk() (*[]LinearIssueResponseContextChildrenInner, bool)`

GetChildrenOk returns a tuple with the Children field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildren

`func (o *LinearIssueResponseContext) SetChildren(v []LinearIssueResponseContextChildrenInner)`

SetChildren sets Children field to given value.


### GetComments

`func (o *LinearIssueResponseContext) GetComments() []LinearIssueResponseContextCommentsInner`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *LinearIssueResponseContext) GetCommentsOk() (*[]LinearIssueResponseContextCommentsInner, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *LinearIssueResponseContext) SetComments(v []LinearIssueResponseContextCommentsInner)`

SetComments sets Comments field to given value.


### GetDescription

`func (o *LinearIssueResponseContext) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *LinearIssueResponseContext) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *LinearIssueResponseContext) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *LinearIssueResponseContext) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LinearIssueResponseContext) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LinearIssueResponseContext) SetId(v string)`

SetId sets Id field to given value.


### GetIdentifier

`func (o *LinearIssueResponseContext) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *LinearIssueResponseContext) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *LinearIssueResponseContext) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetLabels

`func (o *LinearIssueResponseContext) GetLabels() []HlixCodeModelsModelsInner`

GetLabels returns the Labels field if non-nil, zero value otherwise.

### GetLabelsOk

`func (o *LinearIssueResponseContext) GetLabelsOk() (*[]HlixCodeModelsModelsInner, bool)`

GetLabelsOk returns a tuple with the Labels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabels

`func (o *LinearIssueResponseContext) SetLabels(v []HlixCodeModelsModelsInner)`

SetLabels sets Labels field to given value.


### GetParent

`func (o *LinearIssueResponseContext) GetParent() LinearIssueResponseContextParent`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *LinearIssueResponseContext) GetParentOk() (*LinearIssueResponseContextParent, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *LinearIssueResponseContext) SetParent(v LinearIssueResponseContextParent)`

SetParent sets Parent field to given value.


### SetParentNil

`func (o *LinearIssueResponseContext) SetParentNil(b bool)`

 SetParentNil sets the value for Parent to be an explicit nil

### UnsetParent
`func (o *LinearIssueResponseContext) UnsetParent()`

UnsetParent ensures that no value is present for Parent, not even an explicit nil
### GetPriority

`func (o *LinearIssueResponseContext) GetPriority() string`

GetPriority returns the Priority field if non-nil, zero value otherwise.

### GetPriorityOk

`func (o *LinearIssueResponseContext) GetPriorityOk() (*string, bool)`

GetPriorityOk returns a tuple with the Priority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriority

`func (o *LinearIssueResponseContext) SetPriority(v string)`

SetPriority sets Priority field to given value.


### GetProject

`func (o *LinearIssueResponseContext) GetProject() LinearIssueResponseContextProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *LinearIssueResponseContext) GetProjectOk() (*LinearIssueResponseContextProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *LinearIssueResponseContext) SetProject(v LinearIssueResponseContextProject)`

SetProject sets Project field to given value.


### SetProjectNil

`func (o *LinearIssueResponseContext) SetProjectNil(b bool)`

 SetProjectNil sets the value for Project to be an explicit nil

### UnsetProject
`func (o *LinearIssueResponseContext) UnsetProject()`

UnsetProject ensures that no value is present for Project, not even an explicit nil
### GetState

`func (o *LinearIssueResponseContext) GetState() LinearIssueResponseContextState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *LinearIssueResponseContext) GetStateOk() (*LinearIssueResponseContextState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *LinearIssueResponseContext) SetState(v LinearIssueResponseContextState)`

SetState sets State field to given value.


### GetTeam

`func (o *LinearIssueResponseContext) GetTeam() LinearCatalogResponseTeamsInner`

GetTeam returns the Team field if non-nil, zero value otherwise.

### GetTeamOk

`func (o *LinearIssueResponseContext) GetTeamOk() (*LinearCatalogResponseTeamsInner, bool)`

GetTeamOk returns a tuple with the Team field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTeam

`func (o *LinearIssueResponseContext) SetTeam(v LinearCatalogResponseTeamsInner)`

SetTeam sets Team field to given value.


### GetTitle

`func (o *LinearIssueResponseContext) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *LinearIssueResponseContext) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *LinearIssueResponseContext) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *LinearIssueResponseContext) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LinearIssueResponseContext) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LinearIssueResponseContext) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUrl

`func (o *LinearIssueResponseContext) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *LinearIssueResponseContext) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *LinearIssueResponseContext) SetUrl(v string)`

SetUrl sets Url field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


