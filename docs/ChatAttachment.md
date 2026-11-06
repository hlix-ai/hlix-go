# ChatAttachment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArtifactKey** | **string** |  | 
**MimeType** | **string** |  | 
**Name** | **string** |  | 
**Size** | **float32** |  | 
**Transcript** | Pointer to **string** |  | [optional] 

## Methods

### NewChatAttachment

`func NewChatAttachment(artifactKey string, mimeType string, name string, size float32, ) *ChatAttachment`

NewChatAttachment instantiates a new ChatAttachment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatAttachmentWithDefaults

`func NewChatAttachmentWithDefaults() *ChatAttachment`

NewChatAttachmentWithDefaults instantiates a new ChatAttachment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArtifactKey

`func (o *ChatAttachment) GetArtifactKey() string`

GetArtifactKey returns the ArtifactKey field if non-nil, zero value otherwise.

### GetArtifactKeyOk

`func (o *ChatAttachment) GetArtifactKeyOk() (*string, bool)`

GetArtifactKeyOk returns a tuple with the ArtifactKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactKey

`func (o *ChatAttachment) SetArtifactKey(v string)`

SetArtifactKey sets ArtifactKey field to given value.


### GetMimeType

`func (o *ChatAttachment) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *ChatAttachment) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *ChatAttachment) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetName

`func (o *ChatAttachment) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ChatAttachment) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ChatAttachment) SetName(v string)`

SetName sets Name field to given value.


### GetSize

`func (o *ChatAttachment) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ChatAttachment) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ChatAttachment) SetSize(v float32)`

SetSize sets Size field to given value.


### GetTranscript

`func (o *ChatAttachment) GetTranscript() string`

GetTranscript returns the Transcript field if non-nil, zero value otherwise.

### GetTranscriptOk

`func (o *ChatAttachment) GetTranscriptOk() (*string, bool)`

GetTranscriptOk returns a tuple with the Transcript field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranscript

`func (o *ChatAttachment) SetTranscript(v string)`

SetTranscript sets Transcript field to given value.

### HasTranscript

`func (o *ChatAttachment) HasTranscript() bool`

HasTranscript returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


