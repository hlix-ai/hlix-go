# ProjectWorkspaceFs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | Pointer to **string** |  | [optional] 
**Dest** | Pointer to **string** |  | [optional] 
**Encoding** | Pointer to **string** |  | [optional] [default to "utf8"]
**Op** | **string** |  | 
**Options** | Pointer to [**ProjectWorkspaceFsOptions**](ProjectWorkspaceFsOptions.md) |  | [optional] 
**Path** | **string** |  | 

## Methods

### NewProjectWorkspaceFs

`func NewProjectWorkspaceFs(op string, path string, ) *ProjectWorkspaceFs`

NewProjectWorkspaceFs instantiates a new ProjectWorkspaceFs object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectWorkspaceFsWithDefaults

`func NewProjectWorkspaceFsWithDefaults() *ProjectWorkspaceFs`

NewProjectWorkspaceFsWithDefaults instantiates a new ProjectWorkspaceFs object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *ProjectWorkspaceFs) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ProjectWorkspaceFs) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ProjectWorkspaceFs) SetContent(v string)`

SetContent sets Content field to given value.

### HasContent

`func (o *ProjectWorkspaceFs) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetDest

`func (o *ProjectWorkspaceFs) GetDest() string`

GetDest returns the Dest field if non-nil, zero value otherwise.

### GetDestOk

`func (o *ProjectWorkspaceFs) GetDestOk() (*string, bool)`

GetDestOk returns a tuple with the Dest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDest

`func (o *ProjectWorkspaceFs) SetDest(v string)`

SetDest sets Dest field to given value.

### HasDest

`func (o *ProjectWorkspaceFs) HasDest() bool`

HasDest returns a boolean if a field has been set.

### GetEncoding

`func (o *ProjectWorkspaceFs) GetEncoding() string`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *ProjectWorkspaceFs) GetEncodingOk() (*string, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *ProjectWorkspaceFs) SetEncoding(v string)`

SetEncoding sets Encoding field to given value.

### HasEncoding

`func (o *ProjectWorkspaceFs) HasEncoding() bool`

HasEncoding returns a boolean if a field has been set.

### GetOp

`func (o *ProjectWorkspaceFs) GetOp() string`

GetOp returns the Op field if non-nil, zero value otherwise.

### GetOpOk

`func (o *ProjectWorkspaceFs) GetOpOk() (*string, bool)`

GetOpOk returns a tuple with the Op field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOp

`func (o *ProjectWorkspaceFs) SetOp(v string)`

SetOp sets Op field to given value.


### GetOptions

`func (o *ProjectWorkspaceFs) GetOptions() ProjectWorkspaceFsOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ProjectWorkspaceFs) GetOptionsOk() (*ProjectWorkspaceFsOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ProjectWorkspaceFs) SetOptions(v ProjectWorkspaceFsOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *ProjectWorkspaceFs) HasOptions() bool`

HasOptions returns a boolean if a field has been set.

### GetPath

`func (o *ProjectWorkspaceFs) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ProjectWorkspaceFs) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ProjectWorkspaceFs) SetPath(v string)`

SetPath sets Path field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


