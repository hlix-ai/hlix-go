# WorkspacePortalClient

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanCreateProjects** | **bool** |  |
**CanCreateProjectsOverride** | **NullableBool** |  |
**ClientAccountIds** | **[]string** |  |
**Email** | **string** |  |
**Image** | **NullableString** |  |
**Name** | **string** |  |
**ProjectGrants** | [**[]CustomerAccessRemovedGrantsInner**](CustomerAccessRemovedGrantsInner.md) |  |
**Role** | **string** |  |
**UserId** | **string** |  |

## Methods

### NewWorkspacePortalClient

`func NewWorkspacePortalClient(canCreateProjects bool, canCreateProjectsOverride NullableBool, clientAccountIds []string, email string, image NullableString, name string, projectGrants []CustomerAccessRemovedGrantsInner, role string, userId string, ) *WorkspacePortalClient`

NewWorkspacePortalClient instantiates a new WorkspacePortalClient object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewWorkspacePortalClientWithDefaults

`func NewWorkspacePortalClientWithDefaults() *WorkspacePortalClient`

NewWorkspacePortalClientWithDefaults instantiates a new WorkspacePortalClient object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCanCreateProjects

`func (o *WorkspacePortalClient) GetCanCreateProjects() bool`

GetCanCreateProjects returns the CanCreateProjects field if non-nil, zero value otherwise.

### GetCanCreateProjectsOk

`func (o *WorkspacePortalClient) GetCanCreateProjectsOk() (*bool, bool)`

GetCanCreateProjectsOk returns a tuple with the CanCreateProjects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanCreateProjects

`func (o *WorkspacePortalClient) SetCanCreateProjects(v bool)`

SetCanCreateProjects sets CanCreateProjects field to given value.


### GetCanCreateProjectsOverride

`func (o *WorkspacePortalClient) GetCanCreateProjectsOverride() bool`

GetCanCreateProjectsOverride returns the CanCreateProjectsOverride field if non-nil, zero value otherwise.

### GetCanCreateProjectsOverrideOk

`func (o *WorkspacePortalClient) GetCanCreateProjectsOverrideOk() (*bool, bool)`

GetCanCreateProjectsOverrideOk returns a tuple with the CanCreateProjectsOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanCreateProjectsOverride

`func (o *WorkspacePortalClient) SetCanCreateProjectsOverride(v bool)`

SetCanCreateProjectsOverride sets CanCreateProjectsOverride field to given value.


### SetCanCreateProjectsOverrideNil

`func (o *WorkspacePortalClient) SetCanCreateProjectsOverrideNil(b bool)`

 SetCanCreateProjectsOverrideNil sets the value for CanCreateProjectsOverride to be an explicit nil

### UnsetCanCreateProjectsOverride
`func (o *WorkspacePortalClient) UnsetCanCreateProjectsOverride()`

UnsetCanCreateProjectsOverride ensures that no value is present for CanCreateProjectsOverride, not even an explicit nil
### GetClientAccountIds

`func (o *WorkspacePortalClient) GetClientAccountIds() []string`

GetClientAccountIds returns the ClientAccountIds field if non-nil, zero value otherwise.

### GetClientAccountIdsOk

`func (o *WorkspacePortalClient) GetClientAccountIdsOk() (*[]string, bool)`

GetClientAccountIdsOk returns a tuple with the ClientAccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountIds

`func (o *WorkspacePortalClient) SetClientAccountIds(v []string)`

SetClientAccountIds sets ClientAccountIds field to given value.


### GetEmail

`func (o *WorkspacePortalClient) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *WorkspacePortalClient) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *WorkspacePortalClient) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetImage

`func (o *WorkspacePortalClient) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *WorkspacePortalClient) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *WorkspacePortalClient) SetImage(v string)`

SetImage sets Image field to given value.


### SetImageNil

`func (o *WorkspacePortalClient) SetImageNil(b bool)`

 SetImageNil sets the value for Image to be an explicit nil

### UnsetImage
`func (o *WorkspacePortalClient) UnsetImage()`

UnsetImage ensures that no value is present for Image, not even an explicit nil
### GetName

`func (o *WorkspacePortalClient) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkspacePortalClient) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkspacePortalClient) SetName(v string)`

SetName sets Name field to given value.


### GetProjectGrants

`func (o *WorkspacePortalClient) GetProjectGrants() []CustomerAccessRemovedGrantsInner`

GetProjectGrants returns the ProjectGrants field if non-nil, zero value otherwise.

### GetProjectGrantsOk

`func (o *WorkspacePortalClient) GetProjectGrantsOk() (*[]CustomerAccessRemovedGrantsInner, bool)`

GetProjectGrantsOk returns a tuple with the ProjectGrants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectGrants

`func (o *WorkspacePortalClient) SetProjectGrants(v []CustomerAccessRemovedGrantsInner)`

SetProjectGrants sets ProjectGrants field to given value.


### GetRole

`func (o *WorkspacePortalClient) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *WorkspacePortalClient) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *WorkspacePortalClient) SetRole(v string)`

SetRole sets Role field to given value.


### GetUserId

`func (o *WorkspacePortalClient) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *WorkspacePortalClient) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *WorkspacePortalClient) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


