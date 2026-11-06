# FileContentRef

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ref** | **string** |  | 
**Sha** | **NullableString** |  | 

## Methods

### NewFileContentRef

`func NewFileContentRef(ref string, sha NullableString, ) *FileContentRef`

NewFileContentRef instantiates a new FileContentRef object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileContentRefWithDefaults

`func NewFileContentRefWithDefaults() *FileContentRef`

NewFileContentRefWithDefaults instantiates a new FileContentRef object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRef

`func (o *FileContentRef) GetRef() string`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *FileContentRef) GetRefOk() (*string, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *FileContentRef) SetRef(v string)`

SetRef sets Ref field to given value.


### GetSha

`func (o *FileContentRef) GetSha() string`

GetSha returns the Sha field if non-nil, zero value otherwise.

### GetShaOk

`func (o *FileContentRef) GetShaOk() (*string, bool)`

GetShaOk returns a tuple with the Sha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha

`func (o *FileContentRef) SetSha(v string)`

SetSha sets Sha field to given value.


### SetShaNil

`func (o *FileContentRef) SetShaNil(b bool)`

 SetShaNil sets the value for Sha to be an explicit nil

### UnsetSha
`func (o *FileContentRef) UnsetSha()`

UnsetSha ensures that no value is present for Sha, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


