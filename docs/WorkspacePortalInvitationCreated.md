# WorkspacePortalInvitationCreated

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptUrl** | **string** |  | 
**CanCreateProjects** | **NullableBool** |  | 
**ClientAccountId** | **NullableString** |  | 
**Email** | **string** |  | 
**EmailSent** | **bool** |  | 
**ExpiresAt** | **string** |  | 
**Href** | **string** |  | 
**Id** | **string** |  | 
**ProjectGrants** | [**[]CustomerAccessRemovedGrantsInner**](CustomerAccessRemovedGrantsInner.md) |  | 
**Status** | **string** |  | 

## Methods

### NewWorkspacePortalInvitationCreated

`func NewWorkspacePortalInvitationCreated(acceptUrl string, canCreateProjects NullableBool, clientAccountId NullableString, email string, emailSent bool, expiresAt string, href string, id string, projectGrants []CustomerAccessRemovedGrantsInner, status string, ) *WorkspacePortalInvitationCreated`

NewWorkspacePortalInvitationCreated instantiates a new WorkspacePortalInvitationCreated object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspacePortalInvitationCreatedWithDefaults

`func NewWorkspacePortalInvitationCreatedWithDefaults() *WorkspacePortalInvitationCreated`

NewWorkspacePortalInvitationCreatedWithDefaults instantiates a new WorkspacePortalInvitationCreated object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptUrl

`func (o *WorkspacePortalInvitationCreated) GetAcceptUrl() string`

GetAcceptUrl returns the AcceptUrl field if non-nil, zero value otherwise.

### GetAcceptUrlOk

`func (o *WorkspacePortalInvitationCreated) GetAcceptUrlOk() (*string, bool)`

GetAcceptUrlOk returns a tuple with the AcceptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptUrl

`func (o *WorkspacePortalInvitationCreated) SetAcceptUrl(v string)`

SetAcceptUrl sets AcceptUrl field to given value.


### GetCanCreateProjects

`func (o *WorkspacePortalInvitationCreated) GetCanCreateProjects() bool`

GetCanCreateProjects returns the CanCreateProjects field if non-nil, zero value otherwise.

### GetCanCreateProjectsOk

`func (o *WorkspacePortalInvitationCreated) GetCanCreateProjectsOk() (*bool, bool)`

GetCanCreateProjectsOk returns a tuple with the CanCreateProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanCreateProjects

`func (o *WorkspacePortalInvitationCreated) SetCanCreateProjects(v bool)`

SetCanCreateProjects sets CanCreateProjects field to given value.


### SetCanCreateProjectsNil

`func (o *WorkspacePortalInvitationCreated) SetCanCreateProjectsNil(b bool)`

 SetCanCreateProjectsNil sets the value for CanCreateProjects to be an explicit nil

### UnsetCanCreateProjects
`func (o *WorkspacePortalInvitationCreated) UnsetCanCreateProjects()`

UnsetCanCreateProjects ensures that no value is present for CanCreateProjects, not even an explicit nil
### GetClientAccountId

`func (o *WorkspacePortalInvitationCreated) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *WorkspacePortalInvitationCreated) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *WorkspacePortalInvitationCreated) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *WorkspacePortalInvitationCreated) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *WorkspacePortalInvitationCreated) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetEmail

`func (o *WorkspacePortalInvitationCreated) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *WorkspacePortalInvitationCreated) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *WorkspacePortalInvitationCreated) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetEmailSent

`func (o *WorkspacePortalInvitationCreated) GetEmailSent() bool`

GetEmailSent returns the EmailSent field if non-nil, zero value otherwise.

### GetEmailSentOk

`func (o *WorkspacePortalInvitationCreated) GetEmailSentOk() (*bool, bool)`

GetEmailSentOk returns a tuple with the EmailSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailSent

`func (o *WorkspacePortalInvitationCreated) SetEmailSent(v bool)`

SetEmailSent sets EmailSent field to given value.


### GetExpiresAt

`func (o *WorkspacePortalInvitationCreated) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *WorkspacePortalInvitationCreated) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *WorkspacePortalInvitationCreated) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### GetHref

`func (o *WorkspacePortalInvitationCreated) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *WorkspacePortalInvitationCreated) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *WorkspacePortalInvitationCreated) SetHref(v string)`

SetHref sets Href field to given value.


### GetId

`func (o *WorkspacePortalInvitationCreated) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkspacePortalInvitationCreated) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkspacePortalInvitationCreated) SetId(v string)`

SetId sets Id field to given value.


### GetProjectGrants

`func (o *WorkspacePortalInvitationCreated) GetProjectGrants() []CustomerAccessRemovedGrantsInner`

GetProjectGrants returns the ProjectGrants field if non-nil, zero value otherwise.

### GetProjectGrantsOk

`func (o *WorkspacePortalInvitationCreated) GetProjectGrantsOk() (*[]CustomerAccessRemovedGrantsInner, bool)`

GetProjectGrantsOk returns a tuple with the ProjectGrants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectGrants

`func (o *WorkspacePortalInvitationCreated) SetProjectGrants(v []CustomerAccessRemovedGrantsInner)`

SetProjectGrants sets ProjectGrants field to given value.


### GetStatus

`func (o *WorkspacePortalInvitationCreated) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WorkspacePortalInvitationCreated) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WorkspacePortalInvitationCreated) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


