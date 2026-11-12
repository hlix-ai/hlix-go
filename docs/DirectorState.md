# DirectorState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Clips** | [**[]DirectorStateClipsInner**](DirectorStateClipsInner.md) |  |
**Error** | **NullableString** |  |
**Status** | **string** |  |

## Methods

### NewDirectorState

`func NewDirectorState(clips []DirectorStateClipsInner, error_ NullableString, status string, ) *DirectorState`

NewDirectorState instantiates a new DirectorState object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDirectorStateWithDefaults

`func NewDirectorStateWithDefaults() *DirectorState`

NewDirectorStateWithDefaults instantiates a new DirectorState object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetClips

`func (o *DirectorState) GetClips() []DirectorStateClipsInner`

GetClips returns the Clips field if non-nil, zero value otherwise.

### GetClipsOk

`func (o *DirectorState) GetClipsOk() (*[]DirectorStateClipsInner, bool)`

GetClipsOk returns a tuple with the Clips field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClips

`func (o *DirectorState) SetClips(v []DirectorStateClipsInner)`

SetClips sets Clips field to given value.


### GetError

`func (o *DirectorState) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DirectorState) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DirectorState) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *DirectorState) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *DirectorState) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetStatus

`func (o *DirectorState) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DirectorState) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DirectorState) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


