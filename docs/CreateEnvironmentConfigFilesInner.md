# CreateEnvironmentConfigFilesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** |  | 
**Encoding** | Pointer to **string** |  | [optional] 
**Executable** | Pointer to **bool** |  | [optional] 
**Path** | **string** |  | 

## Methods

### NewCreateEnvironmentConfigFilesInner

`func NewCreateEnvironmentConfigFilesInner(content string, path string, ) *CreateEnvironmentConfigFilesInner`

NewCreateEnvironmentConfigFilesInner instantiates a new CreateEnvironmentConfigFilesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateEnvironmentConfigFilesInnerWithDefaults

`func NewCreateEnvironmentConfigFilesInnerWithDefaults() *CreateEnvironmentConfigFilesInner`

NewCreateEnvironmentConfigFilesInnerWithDefaults instantiates a new CreateEnvironmentConfigFilesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *CreateEnvironmentConfigFilesInner) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateEnvironmentConfigFilesInner) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateEnvironmentConfigFilesInner) SetContent(v string)`

SetContent sets Content field to given value.


### GetEncoding

`func (o *CreateEnvironmentConfigFilesInner) GetEncoding() string`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *CreateEnvironmentConfigFilesInner) GetEncodingOk() (*string, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *CreateEnvironmentConfigFilesInner) SetEncoding(v string)`

SetEncoding sets Encoding field to given value.

### HasEncoding

`func (o *CreateEnvironmentConfigFilesInner) HasEncoding() bool`

HasEncoding returns a boolean if a field has been set.

### GetExecutable

`func (o *CreateEnvironmentConfigFilesInner) GetExecutable() bool`

GetExecutable returns the Executable field if non-nil, zero value otherwise.

### GetExecutableOk

`func (o *CreateEnvironmentConfigFilesInner) GetExecutableOk() (*bool, bool)`

GetExecutableOk returns a tuple with the Executable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutable

`func (o *CreateEnvironmentConfigFilesInner) SetExecutable(v bool)`

SetExecutable sets Executable field to given value.

### HasExecutable

`func (o *CreateEnvironmentConfigFilesInner) HasExecutable() bool`

HasExecutable returns a boolean if a field has been set.

### GetPath

`func (o *CreateEnvironmentConfigFilesInner) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *CreateEnvironmentConfigFilesInner) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *CreateEnvironmentConfigFilesInner) SetPath(v string)`

SetPath sets Path field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


