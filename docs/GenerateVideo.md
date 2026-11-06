# GenerateVideo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AspectRatio** | Pointer to **string** |  | [optional] 
**Duration** | Pointer to **int32** |  | [optional] 
**IdempotencyKey** | **string** |  | 
**ProjectId** | Pointer to **string** |  | [optional] 
**Prompt** | **string** |  | 
**Resolution** | Pointer to **string** |  | [optional] 
**UseWorkspaceBrand** | Pointer to **bool** |  | [optional] 

## Methods

### NewGenerateVideo

`func NewGenerateVideo(idempotencyKey string, prompt string, ) *GenerateVideo`

NewGenerateVideo instantiates a new GenerateVideo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGenerateVideoWithDefaults

`func NewGenerateVideoWithDefaults() *GenerateVideo`

NewGenerateVideoWithDefaults instantiates a new GenerateVideo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAspectRatio

`func (o *GenerateVideo) GetAspectRatio() string`

GetAspectRatio returns the AspectRatio field if non-nil, zero value otherwise.

### GetAspectRatioOk

`func (o *GenerateVideo) GetAspectRatioOk() (*string, bool)`

GetAspectRatioOk returns a tuple with the AspectRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspectRatio

`func (o *GenerateVideo) SetAspectRatio(v string)`

SetAspectRatio sets AspectRatio field to given value.

### HasAspectRatio

`func (o *GenerateVideo) HasAspectRatio() bool`

HasAspectRatio returns a boolean if a field has been set.

### GetDuration

`func (o *GenerateVideo) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *GenerateVideo) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *GenerateVideo) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *GenerateVideo) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *GenerateVideo) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *GenerateVideo) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *GenerateVideo) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetProjectId

`func (o *GenerateVideo) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *GenerateVideo) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *GenerateVideo) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *GenerateVideo) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetPrompt

`func (o *GenerateVideo) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *GenerateVideo) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *GenerateVideo) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetResolution

`func (o *GenerateVideo) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *GenerateVideo) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *GenerateVideo) SetResolution(v string)`

SetResolution sets Resolution field to given value.

### HasResolution

`func (o *GenerateVideo) HasResolution() bool`

HasResolution returns a boolean if a field has been set.

### GetUseWorkspaceBrand

`func (o *GenerateVideo) GetUseWorkspaceBrand() bool`

GetUseWorkspaceBrand returns the UseWorkspaceBrand field if non-nil, zero value otherwise.

### GetUseWorkspaceBrandOk

`func (o *GenerateVideo) GetUseWorkspaceBrandOk() (*bool, bool)`

GetUseWorkspaceBrandOk returns a tuple with the UseWorkspaceBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWorkspaceBrand

`func (o *GenerateVideo) SetUseWorkspaceBrand(v bool)`

SetUseWorkspaceBrand sets UseWorkspaceBrand field to given value.

### HasUseWorkspaceBrand

`func (o *GenerateVideo) HasUseWorkspaceBrand() bool`

HasUseWorkspaceBrand returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


