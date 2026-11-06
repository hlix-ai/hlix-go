# DeploymentAccepted

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accepted** | **bool** |  | 
**Kind** | **string** |  | 
**Repo** | [**DeploymentAcceptedRepo**](DeploymentAcceptedRepo.md) |  | 
**SelectedBy** | **string** |  | 

## Methods

### NewDeploymentAccepted

`func NewDeploymentAccepted(accepted bool, kind string, repo DeploymentAcceptedRepo, selectedBy string, ) *DeploymentAccepted`

NewDeploymentAccepted instantiates a new DeploymentAccepted object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeploymentAcceptedWithDefaults

`func NewDeploymentAcceptedWithDefaults() *DeploymentAccepted`

NewDeploymentAcceptedWithDefaults instantiates a new DeploymentAccepted object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccepted

`func (o *DeploymentAccepted) GetAccepted() bool`

GetAccepted returns the Accepted field if non-nil, zero value otherwise.

### GetAcceptedOk

`func (o *DeploymentAccepted) GetAcceptedOk() (*bool, bool)`

GetAcceptedOk returns a tuple with the Accepted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccepted

`func (o *DeploymentAccepted) SetAccepted(v bool)`

SetAccepted sets Accepted field to given value.


### GetKind

`func (o *DeploymentAccepted) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *DeploymentAccepted) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *DeploymentAccepted) SetKind(v string)`

SetKind sets Kind field to given value.


### GetRepo

`func (o *DeploymentAccepted) GetRepo() DeploymentAcceptedRepo`

GetRepo returns the Repo field if non-nil, zero value otherwise.

### GetRepoOk

`func (o *DeploymentAccepted) GetRepoOk() (*DeploymentAcceptedRepo, bool)`

GetRepoOk returns a tuple with the Repo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepo

`func (o *DeploymentAccepted) SetRepo(v DeploymentAcceptedRepo)`

SetRepo sets Repo field to given value.


### GetSelectedBy

`func (o *DeploymentAccepted) GetSelectedBy() string`

GetSelectedBy returns the SelectedBy field if non-nil, zero value otherwise.

### GetSelectedByOk

`func (o *DeploymentAccepted) GetSelectedByOk() (*string, bool)`

GetSelectedByOk returns a tuple with the SelectedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedBy

`func (o *DeploymentAccepted) SetSelectedBy(v string)`

SetSelectedBy sets SelectedBy field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


