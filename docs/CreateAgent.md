# CreateAgent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarImageKey** | Pointer to **NullableString** |  | [optional] 
**AvatarKey** | Pointer to **NullableString** |  | [optional] 
**AvatarUrl** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Duty** | Pointer to **string** |  | [optional] 
**Instructions** | Pointer to **NullableString** |  | [optional] 
**ModelOverride** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Pipeline** | Pointer to **string** |  | [optional] 
**ProjectId** | Pointer to **NullableString** |  | [optional] 
**RuntimeKind** | Pointer to **NullableString** |  | [optional] 
**RuntimeVersion** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateAgent

`func NewCreateAgent(name string, ) *CreateAgent`

NewCreateAgent instantiates a new CreateAgent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAgentWithDefaults

`func NewCreateAgentWithDefaults() *CreateAgent`

NewCreateAgentWithDefaults instantiates a new CreateAgent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarImageKey

`func (o *CreateAgent) GetAvatarImageKey() string`

GetAvatarImageKey returns the AvatarImageKey field if non-nil, zero value otherwise.

### GetAvatarImageKeyOk

`func (o *CreateAgent) GetAvatarImageKeyOk() (*string, bool)`

GetAvatarImageKeyOk returns a tuple with the AvatarImageKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarImageKey

`func (o *CreateAgent) SetAvatarImageKey(v string)`

SetAvatarImageKey sets AvatarImageKey field to given value.

### HasAvatarImageKey

`func (o *CreateAgent) HasAvatarImageKey() bool`

HasAvatarImageKey returns a boolean if a field has been set.

### SetAvatarImageKeyNil

`func (o *CreateAgent) SetAvatarImageKeyNil(b bool)`

 SetAvatarImageKeyNil sets the value for AvatarImageKey to be an explicit nil

### UnsetAvatarImageKey
`func (o *CreateAgent) UnsetAvatarImageKey()`

UnsetAvatarImageKey ensures that no value is present for AvatarImageKey, not even an explicit nil
### GetAvatarKey

`func (o *CreateAgent) GetAvatarKey() string`

GetAvatarKey returns the AvatarKey field if non-nil, zero value otherwise.

### GetAvatarKeyOk

`func (o *CreateAgent) GetAvatarKeyOk() (*string, bool)`

GetAvatarKeyOk returns a tuple with the AvatarKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarKey

`func (o *CreateAgent) SetAvatarKey(v string)`

SetAvatarKey sets AvatarKey field to given value.

### HasAvatarKey

`func (o *CreateAgent) HasAvatarKey() bool`

HasAvatarKey returns a boolean if a field has been set.

### SetAvatarKeyNil

`func (o *CreateAgent) SetAvatarKeyNil(b bool)`

 SetAvatarKeyNil sets the value for AvatarKey to be an explicit nil

### UnsetAvatarKey
`func (o *CreateAgent) UnsetAvatarKey()`

UnsetAvatarKey ensures that no value is present for AvatarKey, not even an explicit nil
### GetAvatarUrl

`func (o *CreateAgent) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *CreateAgent) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *CreateAgent) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.

### HasAvatarUrl

`func (o *CreateAgent) HasAvatarUrl() bool`

HasAvatarUrl returns a boolean if a field has been set.

### SetAvatarUrlNil

`func (o *CreateAgent) SetAvatarUrlNil(b bool)`

 SetAvatarUrlNil sets the value for AvatarUrl to be an explicit nil

### UnsetAvatarUrl
`func (o *CreateAgent) UnsetAvatarUrl()`

UnsetAvatarUrl ensures that no value is present for AvatarUrl, not even an explicit nil
### GetDescription

`func (o *CreateAgent) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateAgent) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateAgent) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateAgent) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateAgent) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateAgent) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDuty

`func (o *CreateAgent) GetDuty() string`

GetDuty returns the Duty field if non-nil, zero value otherwise.

### GetDutyOk

`func (o *CreateAgent) GetDutyOk() (*string, bool)`

GetDutyOk returns a tuple with the Duty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuty

`func (o *CreateAgent) SetDuty(v string)`

SetDuty sets Duty field to given value.

### HasDuty

`func (o *CreateAgent) HasDuty() bool`

HasDuty returns a boolean if a field has been set.

### GetInstructions

`func (o *CreateAgent) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *CreateAgent) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *CreateAgent) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *CreateAgent) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### SetInstructionsNil

`func (o *CreateAgent) SetInstructionsNil(b bool)`

 SetInstructionsNil sets the value for Instructions to be an explicit nil

### UnsetInstructions
`func (o *CreateAgent) UnsetInstructions()`

UnsetInstructions ensures that no value is present for Instructions, not even an explicit nil
### GetModelOverride

`func (o *CreateAgent) GetModelOverride() string`

GetModelOverride returns the ModelOverride field if non-nil, zero value otherwise.

### GetModelOverrideOk

`func (o *CreateAgent) GetModelOverrideOk() (*string, bool)`

GetModelOverrideOk returns a tuple with the ModelOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelOverride

`func (o *CreateAgent) SetModelOverride(v string)`

SetModelOverride sets ModelOverride field to given value.

### HasModelOverride

`func (o *CreateAgent) HasModelOverride() bool`

HasModelOverride returns a boolean if a field has been set.

### SetModelOverrideNil

`func (o *CreateAgent) SetModelOverrideNil(b bool)`

 SetModelOverrideNil sets the value for ModelOverride to be an explicit nil

### UnsetModelOverride
`func (o *CreateAgent) UnsetModelOverride()`

UnsetModelOverride ensures that no value is present for ModelOverride, not even an explicit nil
### GetName

`func (o *CreateAgent) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateAgent) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateAgent) SetName(v string)`

SetName sets Name field to given value.


### GetPipeline

`func (o *CreateAgent) GetPipeline() string`

GetPipeline returns the Pipeline field if non-nil, zero value otherwise.

### GetPipelineOk

`func (o *CreateAgent) GetPipelineOk() (*string, bool)`

GetPipelineOk returns a tuple with the Pipeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipeline

`func (o *CreateAgent) SetPipeline(v string)`

SetPipeline sets Pipeline field to given value.

### HasPipeline

`func (o *CreateAgent) HasPipeline() bool`

HasPipeline returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateAgent) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateAgent) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateAgent) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateAgent) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *CreateAgent) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *CreateAgent) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetRuntimeKind

`func (o *CreateAgent) GetRuntimeKind() string`

GetRuntimeKind returns the RuntimeKind field if non-nil, zero value otherwise.

### GetRuntimeKindOk

`func (o *CreateAgent) GetRuntimeKindOk() (*string, bool)`

GetRuntimeKindOk returns a tuple with the RuntimeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeKind

`func (o *CreateAgent) SetRuntimeKind(v string)`

SetRuntimeKind sets RuntimeKind field to given value.

### HasRuntimeKind

`func (o *CreateAgent) HasRuntimeKind() bool`

HasRuntimeKind returns a boolean if a field has been set.

### SetRuntimeKindNil

`func (o *CreateAgent) SetRuntimeKindNil(b bool)`

 SetRuntimeKindNil sets the value for RuntimeKind to be an explicit nil

### UnsetRuntimeKind
`func (o *CreateAgent) UnsetRuntimeKind()`

UnsetRuntimeKind ensures that no value is present for RuntimeKind, not even an explicit nil
### GetRuntimeVersion

`func (o *CreateAgent) GetRuntimeVersion() string`

GetRuntimeVersion returns the RuntimeVersion field if non-nil, zero value otherwise.

### GetRuntimeVersionOk

`func (o *CreateAgent) GetRuntimeVersionOk() (*string, bool)`

GetRuntimeVersionOk returns a tuple with the RuntimeVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeVersion

`func (o *CreateAgent) SetRuntimeVersion(v string)`

SetRuntimeVersion sets RuntimeVersion field to given value.

### HasRuntimeVersion

`func (o *CreateAgent) HasRuntimeVersion() bool`

HasRuntimeVersion returns a boolean if a field has been set.

### SetRuntimeVersionNil

`func (o *CreateAgent) SetRuntimeVersionNil(b bool)`

 SetRuntimeVersionNil sets the value for RuntimeVersion to be an explicit nil

### UnsetRuntimeVersion
`func (o *CreateAgent) UnsetRuntimeVersion()`

UnsetRuntimeVersion ensures that no value is present for RuntimeVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


