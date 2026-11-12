# DeployProduction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MinInstances** | Pointer to **float32** |  | [optional]
**ProjectId** | **string** |  |
**RepoId** | Pointer to **string** |  | [optional]

## Methods

### NewDeployProduction

`func NewDeployProduction(projectId string, ) *DeployProduction`

NewDeployProduction instantiates a new DeployProduction object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeployProductionWithDefaults

`func NewDeployProductionWithDefaults() *DeployProduction`

NewDeployProductionWithDefaults instantiates a new DeployProduction object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetMinInstances

`func (o *DeployProduction) GetMinInstances() float32`

GetMinInstances returns the MinInstances field if non-nil, zero value otherwise.

### GetMinInstancesOk

`func (o *DeployProduction) GetMinInstancesOk() (*float32, bool)`

GetMinInstancesOk returns a tuple with the MinInstances field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinInstances

`func (o *DeployProduction) SetMinInstances(v float32)`

SetMinInstances sets MinInstances field to given value.

### HasMinInstances

`func (o *DeployProduction) HasMinInstances() bool`

HasMinInstances returns a boolean if a field has been set.

### GetProjectId

`func (o *DeployProduction) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *DeployProduction) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *DeployProduction) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRepoId

`func (o *DeployProduction) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *DeployProduction) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *DeployProduction) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.

### HasRepoId

`func (o *DeployProduction) HasRepoId() bool`

HasRepoId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


