# ProjectChanges

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EnvironmentState** | **NullableString** |  |
**InFlight** | [**[]ProjectChangesInFlightInner**](ProjectChangesInFlightInner.md) |  |
**ObservedAt** | **string** |  |
**ProjectId** | **string** |  |
**Repos** | [**[]ProjectChangesReposInner**](ProjectChangesReposInner.md) |  |
**Source** | **string** |  |

## Methods

### NewProjectChanges

`func NewProjectChanges(environmentState NullableString, inFlight []ProjectChangesInFlightInner, observedAt string, projectId string, repos []ProjectChangesReposInner, source string, ) *ProjectChanges`

NewProjectChanges instantiates a new ProjectChanges object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectChangesWithDefaults

`func NewProjectChangesWithDefaults() *ProjectChanges`

NewProjectChangesWithDefaults instantiates a new ProjectChanges object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetEnvironmentState

`func (o *ProjectChanges) GetEnvironmentState() string`

GetEnvironmentState returns the EnvironmentState field if non-nil, zero value otherwise.

### GetEnvironmentStateOk

`func (o *ProjectChanges) GetEnvironmentStateOk() (*string, bool)`

GetEnvironmentStateOk returns a tuple with the EnvironmentState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironmentState

`func (o *ProjectChanges) SetEnvironmentState(v string)`

SetEnvironmentState sets EnvironmentState field to given value.


### SetEnvironmentStateNil

`func (o *ProjectChanges) SetEnvironmentStateNil(b bool)`

 SetEnvironmentStateNil sets the value for EnvironmentState to be an explicit nil

### UnsetEnvironmentState
`func (o *ProjectChanges) UnsetEnvironmentState()`

UnsetEnvironmentState ensures that no value is present for EnvironmentState, not even an explicit nil
### GetInFlight

`func (o *ProjectChanges) GetInFlight() []ProjectChangesInFlightInner`

GetInFlight returns the InFlight field if non-nil, zero value otherwise.

### GetInFlightOk

`func (o *ProjectChanges) GetInFlightOk() (*[]ProjectChangesInFlightInner, bool)`

GetInFlightOk returns a tuple with the InFlight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInFlight

`func (o *ProjectChanges) SetInFlight(v []ProjectChangesInFlightInner)`

SetInFlight sets InFlight field to given value.


### GetObservedAt

`func (o *ProjectChanges) GetObservedAt() string`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *ProjectChanges) GetObservedAtOk() (*string, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *ProjectChanges) SetObservedAt(v string)`

SetObservedAt sets ObservedAt field to given value.


### GetProjectId

`func (o *ProjectChanges) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ProjectChanges) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ProjectChanges) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRepos

`func (o *ProjectChanges) GetRepos() []ProjectChangesReposInner`

GetRepos returns the Repos field if non-nil, zero value otherwise.

### GetReposOk

`func (o *ProjectChanges) GetReposOk() (*[]ProjectChangesReposInner, bool)`

GetReposOk returns a tuple with the Repos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepos

`func (o *ProjectChanges) SetRepos(v []ProjectChangesReposInner)`

SetRepos sets Repos field to given value.


### GetSource

`func (o *ProjectChanges) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ProjectChanges) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ProjectChanges) SetSource(v string)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


