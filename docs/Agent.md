# Agent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AvatarImageKey** | **NullableString** |  | 
**AvatarKey** | **NullableString** |  | 
**AvatarUrl** | **NullableString** |  | 
**ContextOverlay** | **interface{}** |  | 
**CreatedAt** | **string** |  | 
**CreatedByUserId** | **NullableString** |  | 
**Description** | **NullableString** |  | 
**Duty** | **string** |  | 
**Id** | **string** |  | 
**Instructions** | **NullableString** |  | 
**IsActive** | **bool** |  | 
**ModelOverride** | **NullableString** |  | 
**Name** | **string** |  | 
**OrganizationId** | **string** |  | 
**Pipeline** | **string** |  | 
**PreRunHooks** | **interface{}** |  | 
**ProjectId** | **NullableString** |  | 
**RuntimeKind** | **NullableString** |  | 
**RuntimeVersion** | **NullableString** |  | 
**ToolConfig** | **interface{}** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewAgent

`func NewAgent(avatarImageKey NullableString, avatarKey NullableString, avatarUrl NullableString, contextOverlay interface{}, createdAt string, createdByUserId NullableString, description NullableString, duty string, id string, instructions NullableString, isActive bool, modelOverride NullableString, name string, organizationId string, pipeline string, preRunHooks interface{}, projectId NullableString, runtimeKind NullableString, runtimeVersion NullableString, toolConfig interface{}, updatedAt string, ) *Agent`

NewAgent instantiates a new Agent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentWithDefaults

`func NewAgentWithDefaults() *Agent`

NewAgentWithDefaults instantiates a new Agent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatarImageKey

`func (o *Agent) GetAvatarImageKey() string`

GetAvatarImageKey returns the AvatarImageKey field if non-nil, zero value otherwise.

### GetAvatarImageKeyOk

`func (o *Agent) GetAvatarImageKeyOk() (*string, bool)`

GetAvatarImageKeyOk returns a tuple with the AvatarImageKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarImageKey

`func (o *Agent) SetAvatarImageKey(v string)`

SetAvatarImageKey sets AvatarImageKey field to given value.


### SetAvatarImageKeyNil

`func (o *Agent) SetAvatarImageKeyNil(b bool)`

 SetAvatarImageKeyNil sets the value for AvatarImageKey to be an explicit nil

### UnsetAvatarImageKey
`func (o *Agent) UnsetAvatarImageKey()`

UnsetAvatarImageKey ensures that no value is present for AvatarImageKey, not even an explicit nil
### GetAvatarKey

`func (o *Agent) GetAvatarKey() string`

GetAvatarKey returns the AvatarKey field if non-nil, zero value otherwise.

### GetAvatarKeyOk

`func (o *Agent) GetAvatarKeyOk() (*string, bool)`

GetAvatarKeyOk returns a tuple with the AvatarKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarKey

`func (o *Agent) SetAvatarKey(v string)`

SetAvatarKey sets AvatarKey field to given value.


### SetAvatarKeyNil

`func (o *Agent) SetAvatarKeyNil(b bool)`

 SetAvatarKeyNil sets the value for AvatarKey to be an explicit nil

### UnsetAvatarKey
`func (o *Agent) UnsetAvatarKey()`

UnsetAvatarKey ensures that no value is present for AvatarKey, not even an explicit nil
### GetAvatarUrl

`func (o *Agent) GetAvatarUrl() string`

GetAvatarUrl returns the AvatarUrl field if non-nil, zero value otherwise.

### GetAvatarUrlOk

`func (o *Agent) GetAvatarUrlOk() (*string, bool)`

GetAvatarUrlOk returns a tuple with the AvatarUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatarUrl

`func (o *Agent) SetAvatarUrl(v string)`

SetAvatarUrl sets AvatarUrl field to given value.


### SetAvatarUrlNil

`func (o *Agent) SetAvatarUrlNil(b bool)`

 SetAvatarUrlNil sets the value for AvatarUrl to be an explicit nil

### UnsetAvatarUrl
`func (o *Agent) UnsetAvatarUrl()`

UnsetAvatarUrl ensures that no value is present for AvatarUrl, not even an explicit nil
### GetContextOverlay

`func (o *Agent) GetContextOverlay() interface{}`

GetContextOverlay returns the ContextOverlay field if non-nil, zero value otherwise.

### GetContextOverlayOk

`func (o *Agent) GetContextOverlayOk() (*interface{}, bool)`

GetContextOverlayOk returns a tuple with the ContextOverlay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextOverlay

`func (o *Agent) SetContextOverlay(v interface{})`

SetContextOverlay sets ContextOverlay field to given value.


### SetContextOverlayNil

`func (o *Agent) SetContextOverlayNil(b bool)`

 SetContextOverlayNil sets the value for ContextOverlay to be an explicit nil

### UnsetContextOverlay
`func (o *Agent) UnsetContextOverlay()`

UnsetContextOverlay ensures that no value is present for ContextOverlay, not even an explicit nil
### GetCreatedAt

`func (o *Agent) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Agent) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Agent) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedByUserId

`func (o *Agent) GetCreatedByUserId() string`

GetCreatedByUserId returns the CreatedByUserId field if non-nil, zero value otherwise.

### GetCreatedByUserIdOk

`func (o *Agent) GetCreatedByUserIdOk() (*string, bool)`

GetCreatedByUserIdOk returns a tuple with the CreatedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByUserId

`func (o *Agent) SetCreatedByUserId(v string)`

SetCreatedByUserId sets CreatedByUserId field to given value.


### SetCreatedByUserIdNil

`func (o *Agent) SetCreatedByUserIdNil(b bool)`

 SetCreatedByUserIdNil sets the value for CreatedByUserId to be an explicit nil

### UnsetCreatedByUserId
`func (o *Agent) UnsetCreatedByUserId()`

UnsetCreatedByUserId ensures that no value is present for CreatedByUserId, not even an explicit nil
### GetDescription

`func (o *Agent) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Agent) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Agent) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *Agent) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Agent) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDuty

`func (o *Agent) GetDuty() string`

GetDuty returns the Duty field if non-nil, zero value otherwise.

### GetDutyOk

`func (o *Agent) GetDutyOk() (*string, bool)`

GetDutyOk returns a tuple with the Duty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuty

`func (o *Agent) SetDuty(v string)`

SetDuty sets Duty field to given value.


### GetId

`func (o *Agent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Agent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Agent) SetId(v string)`

SetId sets Id field to given value.


### GetInstructions

`func (o *Agent) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *Agent) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *Agent) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.


### SetInstructionsNil

`func (o *Agent) SetInstructionsNil(b bool)`

 SetInstructionsNil sets the value for Instructions to be an explicit nil

### UnsetInstructions
`func (o *Agent) UnsetInstructions()`

UnsetInstructions ensures that no value is present for Instructions, not even an explicit nil
### GetIsActive

`func (o *Agent) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *Agent) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *Agent) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetModelOverride

`func (o *Agent) GetModelOverride() string`

GetModelOverride returns the ModelOverride field if non-nil, zero value otherwise.

### GetModelOverrideOk

`func (o *Agent) GetModelOverrideOk() (*string, bool)`

GetModelOverrideOk returns a tuple with the ModelOverride field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelOverride

`func (o *Agent) SetModelOverride(v string)`

SetModelOverride sets ModelOverride field to given value.


### SetModelOverrideNil

`func (o *Agent) SetModelOverrideNil(b bool)`

 SetModelOverrideNil sets the value for ModelOverride to be an explicit nil

### UnsetModelOverride
`func (o *Agent) UnsetModelOverride()`

UnsetModelOverride ensures that no value is present for ModelOverride, not even an explicit nil
### GetName

`func (o *Agent) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Agent) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Agent) SetName(v string)`

SetName sets Name field to given value.


### GetOrganizationId

`func (o *Agent) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Agent) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Agent) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPipeline

`func (o *Agent) GetPipeline() string`

GetPipeline returns the Pipeline field if non-nil, zero value otherwise.

### GetPipelineOk

`func (o *Agent) GetPipelineOk() (*string, bool)`

GetPipelineOk returns a tuple with the Pipeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipeline

`func (o *Agent) SetPipeline(v string)`

SetPipeline sets Pipeline field to given value.


### GetPreRunHooks

`func (o *Agent) GetPreRunHooks() interface{}`

GetPreRunHooks returns the PreRunHooks field if non-nil, zero value otherwise.

### GetPreRunHooksOk

`func (o *Agent) GetPreRunHooksOk() (*interface{}, bool)`

GetPreRunHooksOk returns a tuple with the PreRunHooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreRunHooks

`func (o *Agent) SetPreRunHooks(v interface{})`

SetPreRunHooks sets PreRunHooks field to given value.


### SetPreRunHooksNil

`func (o *Agent) SetPreRunHooksNil(b bool)`

 SetPreRunHooksNil sets the value for PreRunHooks to be an explicit nil

### UnsetPreRunHooks
`func (o *Agent) UnsetPreRunHooks()`

UnsetPreRunHooks ensures that no value is present for PreRunHooks, not even an explicit nil
### GetProjectId

`func (o *Agent) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Agent) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Agent) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *Agent) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *Agent) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetRuntimeKind

`func (o *Agent) GetRuntimeKind() string`

GetRuntimeKind returns the RuntimeKind field if non-nil, zero value otherwise.

### GetRuntimeKindOk

`func (o *Agent) GetRuntimeKindOk() (*string, bool)`

GetRuntimeKindOk returns a tuple with the RuntimeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeKind

`func (o *Agent) SetRuntimeKind(v string)`

SetRuntimeKind sets RuntimeKind field to given value.


### SetRuntimeKindNil

`func (o *Agent) SetRuntimeKindNil(b bool)`

 SetRuntimeKindNil sets the value for RuntimeKind to be an explicit nil

### UnsetRuntimeKind
`func (o *Agent) UnsetRuntimeKind()`

UnsetRuntimeKind ensures that no value is present for RuntimeKind, not even an explicit nil
### GetRuntimeVersion

`func (o *Agent) GetRuntimeVersion() string`

GetRuntimeVersion returns the RuntimeVersion field if non-nil, zero value otherwise.

### GetRuntimeVersionOk

`func (o *Agent) GetRuntimeVersionOk() (*string, bool)`

GetRuntimeVersionOk returns a tuple with the RuntimeVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeVersion

`func (o *Agent) SetRuntimeVersion(v string)`

SetRuntimeVersion sets RuntimeVersion field to given value.


### SetRuntimeVersionNil

`func (o *Agent) SetRuntimeVersionNil(b bool)`

 SetRuntimeVersionNil sets the value for RuntimeVersion to be an explicit nil

### UnsetRuntimeVersion
`func (o *Agent) UnsetRuntimeVersion()`

UnsetRuntimeVersion ensures that no value is present for RuntimeVersion, not even an explicit nil
### GetToolConfig

`func (o *Agent) GetToolConfig() interface{}`

GetToolConfig returns the ToolConfig field if non-nil, zero value otherwise.

### GetToolConfigOk

`func (o *Agent) GetToolConfigOk() (*interface{}, bool)`

GetToolConfigOk returns a tuple with the ToolConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolConfig

`func (o *Agent) SetToolConfig(v interface{})`

SetToolConfig sets ToolConfig field to given value.


### SetToolConfigNil

`func (o *Agent) SetToolConfigNil(b bool)`

 SetToolConfigNil sets the value for ToolConfig to be an explicit nil

### UnsetToolConfig
`func (o *Agent) UnsetToolConfig()`

UnsetToolConfig ensures that no value is present for ToolConfig, not even an explicit nil
### GetUpdatedAt

`func (o *Agent) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Agent) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Agent) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


