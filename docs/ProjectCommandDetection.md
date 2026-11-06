# ProjectCommandDetection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Project** | [**ProjectCommandDetectionProject**](ProjectCommandDetectionProject.md) |  | 
**Repos** | [**[]ProjectCommandDetectionReposInner**](ProjectCommandDetectionReposInner.md) |  | 

## Methods

### NewProjectCommandDetection

`func NewProjectCommandDetection(project ProjectCommandDetectionProject, repos []ProjectCommandDetectionReposInner, ) *ProjectCommandDetection`

NewProjectCommandDetection instantiates a new ProjectCommandDetection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectCommandDetectionWithDefaults

`func NewProjectCommandDetectionWithDefaults() *ProjectCommandDetection`

NewProjectCommandDetectionWithDefaults instantiates a new ProjectCommandDetection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProject

`func (o *ProjectCommandDetection) GetProject() ProjectCommandDetectionProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *ProjectCommandDetection) GetProjectOk() (*ProjectCommandDetectionProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *ProjectCommandDetection) SetProject(v ProjectCommandDetectionProject)`

SetProject sets Project field to given value.


### GetRepos

`func (o *ProjectCommandDetection) GetRepos() []ProjectCommandDetectionReposInner`

GetRepos returns the Repos field if non-nil, zero value otherwise.

### GetReposOk

`func (o *ProjectCommandDetection) GetReposOk() (*[]ProjectCommandDetectionReposInner, bool)`

GetReposOk returns a tuple with the Repos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepos

`func (o *ProjectCommandDetection) SetRepos(v []ProjectCommandDetectionReposInner)`

SetRepos sets Repos field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


