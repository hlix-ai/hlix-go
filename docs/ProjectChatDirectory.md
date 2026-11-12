# ProjectChatDirectory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Agents** | [**[]ProjectChatDirectoryAgentsInner**](ProjectChatDirectoryAgentsInner.md) |  |
**Authoritative** | **bool** |  |
**ProjectId** | **string** |  |
**ProjectManager** | [**NullableProjectChatDirectoryProjectManager**](ProjectChatDirectoryProjectManager.md) |  |
**Source** | **string** |  |
**WorkGroups** | [**[]ProjectChatDirectoryWorkGroupsInner**](ProjectChatDirectoryWorkGroupsInner.md) |  |

## Methods

### NewProjectChatDirectory

`func NewProjectChatDirectory(agents []ProjectChatDirectoryAgentsInner, authoritative bool, projectId string, projectManager NullableProjectChatDirectoryProjectManager, source string, workGroups []ProjectChatDirectoryWorkGroupsInner, ) *ProjectChatDirectory`

NewProjectChatDirectory instantiates a new ProjectChatDirectory object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectChatDirectoryWithDefaults

`func NewProjectChatDirectoryWithDefaults() *ProjectChatDirectory`

NewProjectChatDirectoryWithDefaults instantiates a new ProjectChatDirectory object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgents

`func (o *ProjectChatDirectory) GetAgents() []ProjectChatDirectoryAgentsInner`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *ProjectChatDirectory) GetAgentsOk() (*[]ProjectChatDirectoryAgentsInner, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *ProjectChatDirectory) SetAgents(v []ProjectChatDirectoryAgentsInner)`

SetAgents sets Agents field to given value.


### GetAuthoritative

`func (o *ProjectChatDirectory) GetAuthoritative() bool`

GetAuthoritative returns the Authoritative field if non-nil, zero value otherwise.

### GetAuthoritativeOk

`func (o *ProjectChatDirectory) GetAuthoritativeOk() (*bool, bool)`

GetAuthoritativeOk returns a tuple with the Authoritative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthoritative

`func (o *ProjectChatDirectory) SetAuthoritative(v bool)`

SetAuthoritative sets Authoritative field to given value.


### GetProjectId

`func (o *ProjectChatDirectory) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectChatDirectory) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectChatDirectory) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProjectManager

`func (o *ProjectChatDirectory) GetProjectManager() ProjectChatDirectoryProjectManager`

GetProjectManager returns the ProjectManager field if non-nil, zero value otherwise.

### GetProjectManagerOk

`func (o *ProjectChatDirectory) GetProjectManagerOk() (*ProjectChatDirectoryProjectManager, bool)`

GetProjectManagerOk returns a tuple with the ProjectManager field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectManager

`func (o *ProjectChatDirectory) SetProjectManager(v ProjectChatDirectoryProjectManager)`

SetProjectManager sets ProjectManager field to given value.


### SetProjectManagerNil

`func (o *ProjectChatDirectory) SetProjectManagerNil(b bool)`

 SetProjectManagerNil sets the value for ProjectManager to be an explicit nil

### UnsetProjectManager
`func (o *ProjectChatDirectory) UnsetProjectManager()`

UnsetProjectManager ensures that no value is present for ProjectManager, not even an explicit nil
### GetSource

`func (o *ProjectChatDirectory) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ProjectChatDirectory) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ProjectChatDirectory) SetSource(v string)`

SetSource sets Source field to given value.


### GetWorkGroups

`func (o *ProjectChatDirectory) GetWorkGroups() []ProjectChatDirectoryWorkGroupsInner`

GetWorkGroups returns the WorkGroups field if non-nil, zero value otherwise.

### GetWorkGroupsOk

`func (o *ProjectChatDirectory) GetWorkGroupsOk() (*[]ProjectChatDirectoryWorkGroupsInner, bool)`

GetWorkGroupsOk returns a tuple with the WorkGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkGroups

`func (o *ProjectChatDirectory) SetWorkGroups(v []ProjectChatDirectoryWorkGroupsInner)`

SetWorkGroups sets WorkGroups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


