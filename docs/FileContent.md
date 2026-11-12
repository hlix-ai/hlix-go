# FileContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Binary** | **bool** |  |
**Content** | **NullableString** |  |
**Data** | **NullableString** |  |
**MediaType** | **NullableString** |  |
**Path** | **string** |  |
**Ref** | [**FileContentRef**](FileContentRef.md) |  |
**RepoKey** | **string** |  |
**Sha** | **NullableString** |  |
**Size** | **NullableFloat32** |  |
**Truncated** | **bool** |  |

## Methods

### NewFileContent

`func NewFileContent(binary bool, content NullableString, data NullableString, mediaType NullableString, path string, ref FileContentRef, repoKey string, sha NullableString, size NullableFloat32, truncated bool, ) *FileContent`

NewFileContent instantiates a new FileContent object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewFileContentWithDefaults

`func NewFileContentWithDefaults() *FileContent`

NewFileContentWithDefaults instantiates a new FileContent object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBinary

`func (o *FileContent) GetBinary() bool`

GetBinary returns the Binary field if non-nil, zero value otherwise.

### GetBinaryOk

`func (o *FileContent) GetBinaryOk() (*bool, bool)`

GetBinaryOk returns a tuple with the Binary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBinary

`func (o *FileContent) SetBinary(v bool)`

SetBinary sets Binary field to given value.


### GetContent

`func (o *FileContent) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *FileContent) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *FileContent) SetContent(v string)`

SetContent sets Content field to given value.


### SetContentNil

`func (o *FileContent) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *FileContent) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetData

`func (o *FileContent) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FileContent) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FileContent) SetData(v string)`

SetData sets Data field to given value.


### SetDataNil

`func (o *FileContent) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *FileContent) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetMediaType

`func (o *FileContent) GetMediaType() string`

GetMediaType returns the MediaType field if non-nil, zero value otherwise.

### GetMediaTypeOk

`func (o *FileContent) GetMediaTypeOk() (*string, bool)`

GetMediaTypeOk returns a tuple with the MediaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaType

`func (o *FileContent) SetMediaType(v string)`

SetMediaType sets MediaType field to given value.


### SetMediaTypeNil

`func (o *FileContent) SetMediaTypeNil(b bool)`

 SetMediaTypeNil sets the value for MediaType to be an explicit nil

### UnsetMediaType
`func (o *FileContent) UnsetMediaType()`

UnsetMediaType ensures that no value is present for MediaType, not even an explicit nil
### GetPath

`func (o *FileContent) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *FileContent) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *FileContent) SetPath(v string)`

SetPath sets Path field to given value.


### GetRef

`func (o *FileContent) GetRef() FileContentRef`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *FileContent) GetRefOk() (*FileContentRef, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *FileContent) SetRef(v FileContentRef)`

SetRef sets Ref field to given value.


### GetRepoKey

`func (o *FileContent) GetRepoKey() string`

GetRepoKey returns the RepoKey field if non-nil, zero value otherwise.

### GetRepoKeyOk

`func (o *FileContent) GetRepoKeyOk() (*string, bool)`

GetRepoKeyOk returns a tuple with the RepoKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoKey

`func (o *FileContent) SetRepoKey(v string)`

SetRepoKey sets RepoKey field to given value.


### GetSha

`func (o *FileContent) GetSha() string`

GetSha returns the Sha field if non-nil, zero value otherwise.

### GetShaOk

`func (o *FileContent) GetShaOk() (*string, bool)`

GetShaOk returns a tuple with the Sha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha

`func (o *FileContent) SetSha(v string)`

SetSha sets Sha field to given value.


### SetShaNil

`func (o *FileContent) SetShaNil(b bool)`

 SetShaNil sets the value for Sha to be an explicit nil

### UnsetSha
`func (o *FileContent) UnsetSha()`

UnsetSha ensures that no value is present for Sha, not even an explicit nil
### GetSize

`func (o *FileContent) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FileContent) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FileContent) SetSize(v float32)`

SetSize sets Size field to given value.


### SetSizeNil

`func (o *FileContent) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *FileContent) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetTruncated

`func (o *FileContent) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *FileContent) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *FileContent) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


