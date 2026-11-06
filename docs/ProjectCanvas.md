# ProjectCanvas

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Activity** | [**[]ProjectCanvasActivityInner**](ProjectCanvasActivityInner.md) |  | 
**Intake** | [**ProjectCanvasIntake**](ProjectCanvasIntake.md) |  | 
**Preview** | [**NullableProjectCanvasPreview**](ProjectCanvasPreview.md) |  | 
**Repositories** | [**[]ProjectCanvasRepositoriesInner**](ProjectCanvasRepositoriesInner.md) |  | 
**Workspace** | [**NullableProjectCanvasWorkspace**](ProjectCanvasWorkspace.md) |  | 

## Methods

### NewProjectCanvas

`func NewProjectCanvas(activity []ProjectCanvasActivityInner, intake ProjectCanvasIntake, preview NullableProjectCanvasPreview, repositories []ProjectCanvasRepositoriesInner, workspace NullableProjectCanvasWorkspace, ) *ProjectCanvas`

NewProjectCanvas instantiates a new ProjectCanvas object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectCanvasWithDefaults

`func NewProjectCanvasWithDefaults() *ProjectCanvas`

NewProjectCanvasWithDefaults instantiates a new ProjectCanvas object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivity

`func (o *ProjectCanvas) GetActivity() []ProjectCanvasActivityInner`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *ProjectCanvas) GetActivityOk() (*[]ProjectCanvasActivityInner, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *ProjectCanvas) SetActivity(v []ProjectCanvasActivityInner)`

SetActivity sets Activity field to given value.


### GetIntake

`func (o *ProjectCanvas) GetIntake() ProjectCanvasIntake`

GetIntake returns the Intake field if non-nil, zero value otherwise.

### GetIntakeOk

`func (o *ProjectCanvas) GetIntakeOk() (*ProjectCanvasIntake, bool)`

GetIntakeOk returns a tuple with the Intake field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntake

`func (o *ProjectCanvas) SetIntake(v ProjectCanvasIntake)`

SetIntake sets Intake field to given value.


### GetPreview

`func (o *ProjectCanvas) GetPreview() ProjectCanvasPreview`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *ProjectCanvas) GetPreviewOk() (*ProjectCanvasPreview, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *ProjectCanvas) SetPreview(v ProjectCanvasPreview)`

SetPreview sets Preview field to given value.


### SetPreviewNil

`func (o *ProjectCanvas) SetPreviewNil(b bool)`

 SetPreviewNil sets the value for Preview to be an explicit nil

### UnsetPreview
`func (o *ProjectCanvas) UnsetPreview()`

UnsetPreview ensures that no value is present for Preview, not even an explicit nil
### GetRepositories

`func (o *ProjectCanvas) GetRepositories() []ProjectCanvasRepositoriesInner`

GetRepositories returns the Repositories field if non-nil, zero value otherwise.

### GetRepositoriesOk

`func (o *ProjectCanvas) GetRepositoriesOk() (*[]ProjectCanvasRepositoriesInner, bool)`

GetRepositoriesOk returns a tuple with the Repositories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepositories

`func (o *ProjectCanvas) SetRepositories(v []ProjectCanvasRepositoriesInner)`

SetRepositories sets Repositories field to given value.


### GetWorkspace

`func (o *ProjectCanvas) GetWorkspace() ProjectCanvasWorkspace`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *ProjectCanvas) GetWorkspaceOk() (*ProjectCanvasWorkspace, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *ProjectCanvas) SetWorkspace(v ProjectCanvasWorkspace)`

SetWorkspace sets Workspace field to given value.


### SetWorkspaceNil

`func (o *ProjectCanvas) SetWorkspaceNil(b bool)`

 SetWorkspaceNil sets the value for Workspace to be an explicit nil

### UnsetWorkspace
`func (o *ProjectCanvas) UnsetWorkspace()`

UnsetWorkspace ensures that no value is present for Workspace, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


