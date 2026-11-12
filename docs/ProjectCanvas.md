# ProjectCanvas

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Activity** | [**[]ProjectCanvasActivityInner**](ProjectCanvasActivityInner.md) |  |
**Preview** | [**NullableProjectCanvasPreview**](ProjectCanvasPreview.md) |  |
**Repositories** | [**[]ProjectCanvasRepositoriesInner**](ProjectCanvasRepositoriesInner.md) |  |
**Sources** | [**ProjectCanvasSources**](ProjectCanvasSources.md) |  |
**Workspace** | [**NullableProjectCanvasWorkspace**](ProjectCanvasWorkspace.md) |  |

## Methods

### NewProjectCanvas

`func NewProjectCanvas(activity []ProjectCanvasActivityInner, preview NullableProjectCanvasPreview, repositories []ProjectCanvasRepositoriesInner, sources ProjectCanvasSources, workspace NullableProjectCanvasWorkspace, ) *ProjectCanvas`

NewProjectCanvas instantiates a new ProjectCanvas object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectCanvasWithDefaults

`func NewProjectCanvasWithDefaults() *ProjectCanvas`

NewProjectCanvasWithDefaults instantiates a new ProjectCanvas object
This constructor applies declared defaults. It does not ensure required properties are set.

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


### GetSources

`func (o *ProjectCanvas) GetSources() ProjectCanvasSources`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ProjectCanvas) GetSourcesOk() (*ProjectCanvasSources, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ProjectCanvas) SetSources(v ProjectCanvasSources)`

SetSources sets Sources field to given value.


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


