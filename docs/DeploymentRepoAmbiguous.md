# DeploymentRepoAmbiguous

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** |  |
**Repos** | Pointer to [**[]DeploymentRepoAmbiguousReposInner**](DeploymentRepoAmbiguousReposInner.md) |  | [optional]

## Methods

### NewDeploymentRepoAmbiguous

`func NewDeploymentRepoAmbiguous(error_ string, ) *DeploymentRepoAmbiguous`

NewDeploymentRepoAmbiguous instantiates a new DeploymentRepoAmbiguous object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeploymentRepoAmbiguousWithDefaults

`func NewDeploymentRepoAmbiguousWithDefaults() *DeploymentRepoAmbiguous`

NewDeploymentRepoAmbiguousWithDefaults instantiates a new DeploymentRepoAmbiguous object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetError

`func (o *DeploymentRepoAmbiguous) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DeploymentRepoAmbiguous) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DeploymentRepoAmbiguous) SetError(v string)`

SetError sets Error field to given value.


### GetRepos

`func (o *DeploymentRepoAmbiguous) GetRepos() []DeploymentRepoAmbiguousReposInner`

GetRepos returns the Repos field if non-nil, zero value otherwise.

### GetReposOk

`func (o *DeploymentRepoAmbiguous) GetReposOk() (*[]DeploymentRepoAmbiguousReposInner, bool)`

GetReposOk returns a tuple with the Repos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepos

`func (o *DeploymentRepoAmbiguous) SetRepos(v []DeploymentRepoAmbiguousReposInner)`

SetRepos sets Repos field to given value.

### HasRepos

`func (o *DeploymentRepoAmbiguous) HasRepos() bool`

HasRepos returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


