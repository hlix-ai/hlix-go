# ProjectThreadDirectory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Agents** | [**[]ProjectThreadDirectoryAgentsInner**](ProjectThreadDirectoryAgentsInner.md) |  | 
**Authoritative** | **bool** |  | 
**Conductor** | [**NullableProjectThreadDirectoryConductor**](ProjectThreadDirectoryConductor.md) |  | 
**ProjectId** | **string** |  | 
**Source** | **string** |  | 
**WorkGroups** | [**[]ProjectThreadDirectoryWorkGroupsInner**](ProjectThreadDirectoryWorkGroupsInner.md) |  | 

## Methods

### NewProjectThreadDirectory

`func NewProjectThreadDirectory(agents []ProjectThreadDirectoryAgentsInner, authoritative bool, conductor NullableProjectThreadDirectoryConductor, projectId string, source string, workGroups []ProjectThreadDirectoryWorkGroupsInner, ) *ProjectThreadDirectory`

NewProjectThreadDirectory instantiates a new ProjectThreadDirectory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectThreadDirectoryWithDefaults

`func NewProjectThreadDirectoryWithDefaults() *ProjectThreadDirectory`

NewProjectThreadDirectoryWithDefaults instantiates a new ProjectThreadDirectory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgents

`func (o *ProjectThreadDirectory) GetAgents() []ProjectThreadDirectoryAgentsInner`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *ProjectThreadDirectory) GetAgentsOk() (*[]ProjectThreadDirectoryAgentsInner, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *ProjectThreadDirectory) SetAgents(v []ProjectThreadDirectoryAgentsInner)`

SetAgents sets Agents field to given value.


### GetAuthoritative

`func (o *ProjectThreadDirectory) GetAuthoritative() bool`

GetAuthoritative returns the Authoritative field if non-nil, zero value otherwise.

### GetAuthoritativeOk

`func (o *ProjectThreadDirectory) GetAuthoritativeOk() (*bool, bool)`

GetAuthoritativeOk returns a tuple with the Authoritative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthoritative

`func (o *ProjectThreadDirectory) SetAuthoritative(v bool)`

SetAuthoritative sets Authoritative field to given value.


### GetConductor

`func (o *ProjectThreadDirectory) GetConductor() ProjectThreadDirectoryConductor`

GetConductor returns the Conductor field if non-nil, zero value otherwise.

### GetConductorOk

`func (o *ProjectThreadDirectory) GetConductorOk() (*ProjectThreadDirectoryConductor, bool)`

GetConductorOk returns a tuple with the Conductor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConductor

`func (o *ProjectThreadDirectory) SetConductor(v ProjectThreadDirectoryConductor)`

SetConductor sets Conductor field to given value.


### SetConductorNil

`func (o *ProjectThreadDirectory) SetConductorNil(b bool)`

 SetConductorNil sets the value for Conductor to be an explicit nil

### UnsetConductor
`func (o *ProjectThreadDirectory) UnsetConductor()`

UnsetConductor ensures that no value is present for Conductor, not even an explicit nil
### GetProjectId

`func (o *ProjectThreadDirectory) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectThreadDirectory) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectThreadDirectory) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetSource

`func (o *ProjectThreadDirectory) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ProjectThreadDirectory) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ProjectThreadDirectory) SetSource(v string)`

SetSource sets Source field to given value.


### GetWorkGroups

`func (o *ProjectThreadDirectory) GetWorkGroups() []ProjectThreadDirectoryWorkGroupsInner`

GetWorkGroups returns the WorkGroups field if non-nil, zero value otherwise.

### GetWorkGroupsOk

`func (o *ProjectThreadDirectory) GetWorkGroupsOk() (*[]ProjectThreadDirectoryWorkGroupsInner, bool)`

GetWorkGroupsOk returns a tuple with the WorkGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkGroups

`func (o *ProjectThreadDirectory) SetWorkGroups(v []ProjectThreadDirectoryWorkGroupsInner)`

SetWorkGroups sets WorkGroups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


