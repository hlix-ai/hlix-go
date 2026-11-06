# WorkspacePortalInvitation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanCreateProjects** | **NullableBool** |  | 
**ClientAccountId** | **NullableString** |  | 
**Email** | **string** |  | 
**ExpiresAt** | **string** |  | 
**Href** | **string** |  | 
**Id** | **string** |  | 
**ProjectGrants** | [**[]CustomerAccessRemovedGrantsInner**](CustomerAccessRemovedGrantsInner.md) |  | 
**Status** | **string** |  | 

## Methods

### NewWorkspacePortalInvitation

`func NewWorkspacePortalInvitation(canCreateProjects NullableBool, clientAccountId NullableString, email string, expiresAt string, href string, id string, projectGrants []CustomerAccessRemovedGrantsInner, status string, ) *WorkspacePortalInvitation`

NewWorkspacePortalInvitation instantiates a new WorkspacePortalInvitation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspacePortalInvitationWithDefaults

`func NewWorkspacePortalInvitationWithDefaults() *WorkspacePortalInvitation`

NewWorkspacePortalInvitationWithDefaults instantiates a new WorkspacePortalInvitation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCanCreateProjects

`func (o *WorkspacePortalInvitation) GetCanCreateProjects() bool`

GetCanCreateProjects returns the CanCreateProjects field if non-nil, zero value otherwise.

### GetCanCreateProjectsOk

`func (o *WorkspacePortalInvitation) GetCanCreateProjectsOk() (*bool, bool)`

GetCanCreateProjectsOk returns a tuple with the CanCreateProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanCreateProjects

`func (o *WorkspacePortalInvitation) SetCanCreateProjects(v bool)`

SetCanCreateProjects sets CanCreateProjects field to given value.


### SetCanCreateProjectsNil

`func (o *WorkspacePortalInvitation) SetCanCreateProjectsNil(b bool)`

 SetCanCreateProjectsNil sets the value for CanCreateProjects to be an explicit nil

### UnsetCanCreateProjects
`func (o *WorkspacePortalInvitation) UnsetCanCreateProjects()`

UnsetCanCreateProjects ensures that no value is present for CanCreateProjects, not even an explicit nil
### GetClientAccountId

`func (o *WorkspacePortalInvitation) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *WorkspacePortalInvitation) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *WorkspacePortalInvitation) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *WorkspacePortalInvitation) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *WorkspacePortalInvitation) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetEmail

`func (o *WorkspacePortalInvitation) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *WorkspacePortalInvitation) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *WorkspacePortalInvitation) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetExpiresAt

`func (o *WorkspacePortalInvitation) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *WorkspacePortalInvitation) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *WorkspacePortalInvitation) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### GetHref

`func (o *WorkspacePortalInvitation) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *WorkspacePortalInvitation) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *WorkspacePortalInvitation) SetHref(v string)`

SetHref sets Href field to given value.


### GetId

`func (o *WorkspacePortalInvitation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkspacePortalInvitation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkspacePortalInvitation) SetId(v string)`

SetId sets Id field to given value.


### GetProjectGrants

`func (o *WorkspacePortalInvitation) GetProjectGrants() []CustomerAccessRemovedGrantsInner`

GetProjectGrants returns the ProjectGrants field if non-nil, zero value otherwise.

### GetProjectGrantsOk

`func (o *WorkspacePortalInvitation) GetProjectGrantsOk() (*[]CustomerAccessRemovedGrantsInner, bool)`

GetProjectGrantsOk returns a tuple with the ProjectGrants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectGrants

`func (o *WorkspacePortalInvitation) SetProjectGrants(v []CustomerAccessRemovedGrantsInner)`

SetProjectGrants sets ProjectGrants field to given value.


### GetStatus

`func (o *WorkspacePortalInvitation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WorkspacePortalInvitation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WorkspacePortalInvitation) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


