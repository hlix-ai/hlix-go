# InviteWorkspacePortal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanCreateProjects** | Pointer to **NullableBool** |  | [optional] 
**ClientAccountId** | Pointer to **NullableString** |  | [optional] 
**Email** | **string** |  | 
**ProjectGrants** | Pointer to [**[]InviteWorkspacePortalProjectGrantsInner**](InviteWorkspacePortalProjectGrantsInner.md) |  | [optional] 

## Methods

### NewInviteWorkspacePortal

`func NewInviteWorkspacePortal(email string, ) *InviteWorkspacePortal`

NewInviteWorkspacePortal instantiates a new InviteWorkspacePortal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInviteWorkspacePortalWithDefaults

`func NewInviteWorkspacePortalWithDefaults() *InviteWorkspacePortal`

NewInviteWorkspacePortalWithDefaults instantiates a new InviteWorkspacePortal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCanCreateProjects

`func (o *InviteWorkspacePortal) GetCanCreateProjects() bool`

GetCanCreateProjects returns the CanCreateProjects field if non-nil, zero value otherwise.

### GetCanCreateProjectsOk

`func (o *InviteWorkspacePortal) GetCanCreateProjectsOk() (*bool, bool)`

GetCanCreateProjectsOk returns a tuple with the CanCreateProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanCreateProjects

`func (o *InviteWorkspacePortal) SetCanCreateProjects(v bool)`

SetCanCreateProjects sets CanCreateProjects field to given value.

### HasCanCreateProjects

`func (o *InviteWorkspacePortal) HasCanCreateProjects() bool`

HasCanCreateProjects returns a boolean if a field has been set.

### SetCanCreateProjectsNil

`func (o *InviteWorkspacePortal) SetCanCreateProjectsNil(b bool)`

 SetCanCreateProjectsNil sets the value for CanCreateProjects to be an explicit nil

### UnsetCanCreateProjects
`func (o *InviteWorkspacePortal) UnsetCanCreateProjects()`

UnsetCanCreateProjects ensures that no value is present for CanCreateProjects, not even an explicit nil
### GetClientAccountId

`func (o *InviteWorkspacePortal) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *InviteWorkspacePortal) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *InviteWorkspacePortal) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.

### HasClientAccountId

`func (o *InviteWorkspacePortal) HasClientAccountId() bool`

HasClientAccountId returns a boolean if a field has been set.

### SetClientAccountIdNil

`func (o *InviteWorkspacePortal) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *InviteWorkspacePortal) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetEmail

`func (o *InviteWorkspacePortal) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *InviteWorkspacePortal) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *InviteWorkspacePortal) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetProjectGrants

`func (o *InviteWorkspacePortal) GetProjectGrants() []InviteWorkspacePortalProjectGrantsInner`

GetProjectGrants returns the ProjectGrants field if non-nil, zero value otherwise.

### GetProjectGrantsOk

`func (o *InviteWorkspacePortal) GetProjectGrantsOk() (*[]InviteWorkspacePortalProjectGrantsInner, bool)`

GetProjectGrantsOk returns a tuple with the ProjectGrants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectGrants

`func (o *InviteWorkspacePortal) SetProjectGrants(v []InviteWorkspacePortalProjectGrantsInner)`

SetProjectGrants sets ProjectGrants field to given value.

### HasProjectGrants

`func (o *InviteWorkspacePortal) HasProjectGrants() bool`

HasProjectGrants returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


