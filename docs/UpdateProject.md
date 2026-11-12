# UpdateProject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BranchPrefix** | Pointer to **NullableString** |  | [optional]
**Brief** | Pointer to **NullableString** |  | [optional]
**ClaudeMd** | Pointer to **string** |  | [optional]
**CostCapMicros** | Pointer to **NullableInt64** |  | [optional]
**CycleCap** | Pointer to **NullableInt32** |  | [optional]
**InitialProposalRequired** | Pointer to **bool** |  | [optional]
**MachineSize** | Pointer to **NullableString** |  | [optional]
**MaxRevisions** | Pointer to **NullableInt32** |  | [optional]
**Name** | Pointer to **string** |  | [optional]
**PreviewCommand** | Pointer to **NullableString** |  | [optional]
**PreviewPort** | Pointer to **NullableInt32** |  | [optional]
**Runtime** | Pointer to [**CreateProjectRuntime**](CreateProjectRuntime.md) |  | [optional]
**Sources** | Pointer to [**UpdateProjectSources**](UpdateProjectSources.md) |  | [optional]
**Stack** | Pointer to **string** |  | [optional]
**Tier** | Pointer to **NullableString** |  | [optional]
**UseWorkspaceBrand** | Pointer to **bool** |  | [optional]
**VerifyCommand** | Pointer to **NullableString** |  | [optional]

## Methods

### NewUpdateProject

`func NewUpdateProject() *UpdateProject`

NewUpdateProject instantiates a new UpdateProject object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpdateProjectWithDefaults

`func NewUpdateProjectWithDefaults() *UpdateProject`

NewUpdateProjectWithDefaults instantiates a new UpdateProject object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBranchPrefix

`func (o *UpdateProject) GetBranchPrefix() string`

GetBranchPrefix returns the BranchPrefix field if non-nil, zero value otherwise.

### GetBranchPrefixOk

`func (o *UpdateProject) GetBranchPrefixOk() (*string, bool)`

GetBranchPrefixOk returns a tuple with the BranchPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranchPrefix

`func (o *UpdateProject) SetBranchPrefix(v string)`

SetBranchPrefix sets BranchPrefix field to given value.

### HasBranchPrefix

`func (o *UpdateProject) HasBranchPrefix() bool`

HasBranchPrefix returns a boolean if a field has been set.

### SetBranchPrefixNil

`func (o *UpdateProject) SetBranchPrefixNil(b bool)`

 SetBranchPrefixNil sets the value for BranchPrefix to be an explicit nil

### UnsetBranchPrefix
`func (o *UpdateProject) UnsetBranchPrefix()`

UnsetBranchPrefix ensures that no value is present for BranchPrefix, not even an explicit nil
### GetBrief

`func (o *UpdateProject) GetBrief() string`

GetBrief returns the Brief field if non-nil, zero value otherwise.

### GetBriefOk

`func (o *UpdateProject) GetBriefOk() (*string, bool)`

GetBriefOk returns a tuple with the Brief field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrief

`func (o *UpdateProject) SetBrief(v string)`

SetBrief sets Brief field to given value.

### HasBrief

`func (o *UpdateProject) HasBrief() bool`

HasBrief returns a boolean if a field has been set.

### SetBriefNil

`func (o *UpdateProject) SetBriefNil(b bool)`

 SetBriefNil sets the value for Brief to be an explicit nil

### UnsetBrief
`func (o *UpdateProject) UnsetBrief()`

UnsetBrief ensures that no value is present for Brief, not even an explicit nil
### GetClaudeMd

`func (o *UpdateProject) GetClaudeMd() string`

GetClaudeMd returns the ClaudeMd field if non-nil, zero value otherwise.

### GetClaudeMdOk

`func (o *UpdateProject) GetClaudeMdOk() (*string, bool)`

GetClaudeMdOk returns a tuple with the ClaudeMd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaudeMd

`func (o *UpdateProject) SetClaudeMd(v string)`

SetClaudeMd sets ClaudeMd field to given value.

### HasClaudeMd

`func (o *UpdateProject) HasClaudeMd() bool`

HasClaudeMd returns a boolean if a field has been set.

### GetCostCapMicros

`func (o *UpdateProject) GetCostCapMicros() int64`

GetCostCapMicros returns the CostCapMicros field if non-nil, zero value otherwise.

### GetCostCapMicrosOk

`func (o *UpdateProject) GetCostCapMicrosOk() (*int64, bool)`

GetCostCapMicrosOk returns a tuple with the CostCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCapMicros

`func (o *UpdateProject) SetCostCapMicros(v int64)`

SetCostCapMicros sets CostCapMicros field to given value.

### HasCostCapMicros

`func (o *UpdateProject) HasCostCapMicros() bool`

HasCostCapMicros returns a boolean if a field has been set.

### SetCostCapMicrosNil

`func (o *UpdateProject) SetCostCapMicrosNil(b bool)`

 SetCostCapMicrosNil sets the value for CostCapMicros to be an explicit nil

### UnsetCostCapMicros
`func (o *UpdateProject) UnsetCostCapMicros()`

UnsetCostCapMicros ensures that no value is present for CostCapMicros, not even an explicit nil
### GetCycleCap

`func (o *UpdateProject) GetCycleCap() int32`

GetCycleCap returns the CycleCap field if non-nil, zero value otherwise.

### GetCycleCapOk

`func (o *UpdateProject) GetCycleCapOk() (*int32, bool)`

GetCycleCapOk returns a tuple with the CycleCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleCap

`func (o *UpdateProject) SetCycleCap(v int32)`

SetCycleCap sets CycleCap field to given value.

### HasCycleCap

`func (o *UpdateProject) HasCycleCap() bool`

HasCycleCap returns a boolean if a field has been set.

### SetCycleCapNil

`func (o *UpdateProject) SetCycleCapNil(b bool)`

 SetCycleCapNil sets the value for CycleCap to be an explicit nil

### UnsetCycleCap
`func (o *UpdateProject) UnsetCycleCap()`

UnsetCycleCap ensures that no value is present for CycleCap, not even an explicit nil
### GetInitialProposalRequired

`func (o *UpdateProject) GetInitialProposalRequired() bool`

GetInitialProposalRequired returns the InitialProposalRequired field if non-nil, zero value otherwise.

### GetInitialProposalRequiredOk

`func (o *UpdateProject) GetInitialProposalRequiredOk() (*bool, bool)`

GetInitialProposalRequiredOk returns a tuple with the InitialProposalRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialProposalRequired

`func (o *UpdateProject) SetInitialProposalRequired(v bool)`

SetInitialProposalRequired sets InitialProposalRequired field to given value.

### HasInitialProposalRequired

`func (o *UpdateProject) HasInitialProposalRequired() bool`

HasInitialProposalRequired returns a boolean if a field has been set.

### GetMachineSize

`func (o *UpdateProject) GetMachineSize() string`

GetMachineSize returns the MachineSize field if non-nil, zero value otherwise.

### GetMachineSizeOk

`func (o *UpdateProject) GetMachineSizeOk() (*string, bool)`

GetMachineSizeOk returns a tuple with the MachineSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineSize

`func (o *UpdateProject) SetMachineSize(v string)`

SetMachineSize sets MachineSize field to given value.

### HasMachineSize

`func (o *UpdateProject) HasMachineSize() bool`

HasMachineSize returns a boolean if a field has been set.

### SetMachineSizeNil

`func (o *UpdateProject) SetMachineSizeNil(b bool)`

 SetMachineSizeNil sets the value for MachineSize to be an explicit nil

### UnsetMachineSize
`func (o *UpdateProject) UnsetMachineSize()`

UnsetMachineSize ensures that no value is present for MachineSize, not even an explicit nil
### GetMaxRevisions

`func (o *UpdateProject) GetMaxRevisions() int32`

GetMaxRevisions returns the MaxRevisions field if non-nil, zero value otherwise.

### GetMaxRevisionsOk

`func (o *UpdateProject) GetMaxRevisionsOk() (*int32, bool)`

GetMaxRevisionsOk returns a tuple with the MaxRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRevisions

`func (o *UpdateProject) SetMaxRevisions(v int32)`

SetMaxRevisions sets MaxRevisions field to given value.

### HasMaxRevisions

`func (o *UpdateProject) HasMaxRevisions() bool`

HasMaxRevisions returns a boolean if a field has been set.

### SetMaxRevisionsNil

`func (o *UpdateProject) SetMaxRevisionsNil(b bool)`

 SetMaxRevisionsNil sets the value for MaxRevisions to be an explicit nil

### UnsetMaxRevisions
`func (o *UpdateProject) UnsetMaxRevisions()`

UnsetMaxRevisions ensures that no value is present for MaxRevisions, not even an explicit nil
### GetName

`func (o *UpdateProject) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateProject) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateProject) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateProject) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPreviewCommand

`func (o *UpdateProject) GetPreviewCommand() string`

GetPreviewCommand returns the PreviewCommand field if non-nil, zero value otherwise.

### GetPreviewCommandOk

`func (o *UpdateProject) GetPreviewCommandOk() (*string, bool)`

GetPreviewCommandOk returns a tuple with the PreviewCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewCommand

`func (o *UpdateProject) SetPreviewCommand(v string)`

SetPreviewCommand sets PreviewCommand field to given value.

### HasPreviewCommand

`func (o *UpdateProject) HasPreviewCommand() bool`

HasPreviewCommand returns a boolean if a field has been set.

### SetPreviewCommandNil

`func (o *UpdateProject) SetPreviewCommandNil(b bool)`

 SetPreviewCommandNil sets the value for PreviewCommand to be an explicit nil

### UnsetPreviewCommand
`func (o *UpdateProject) UnsetPreviewCommand()`

UnsetPreviewCommand ensures that no value is present for PreviewCommand, not even an explicit nil
### GetPreviewPort

`func (o *UpdateProject) GetPreviewPort() int32`

GetPreviewPort returns the PreviewPort field if non-nil, zero value otherwise.

### GetPreviewPortOk

`func (o *UpdateProject) GetPreviewPortOk() (*int32, bool)`

GetPreviewPortOk returns a tuple with the PreviewPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPort

`func (o *UpdateProject) SetPreviewPort(v int32)`

SetPreviewPort sets PreviewPort field to given value.

### HasPreviewPort

`func (o *UpdateProject) HasPreviewPort() bool`

HasPreviewPort returns a boolean if a field has been set.

### SetPreviewPortNil

`func (o *UpdateProject) SetPreviewPortNil(b bool)`

 SetPreviewPortNil sets the value for PreviewPort to be an explicit nil

### UnsetPreviewPort
`func (o *UpdateProject) UnsetPreviewPort()`

UnsetPreviewPort ensures that no value is present for PreviewPort, not even an explicit nil
### GetRuntime

`func (o *UpdateProject) GetRuntime() CreateProjectRuntime`

GetRuntime returns the Runtime field if non-nil, zero value otherwise.

### GetRuntimeOk

`func (o *UpdateProject) GetRuntimeOk() (*CreateProjectRuntime, bool)`

GetRuntimeOk returns a tuple with the Runtime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntime

`func (o *UpdateProject) SetRuntime(v CreateProjectRuntime)`

SetRuntime sets Runtime field to given value.

### HasRuntime

`func (o *UpdateProject) HasRuntime() bool`

HasRuntime returns a boolean if a field has been set.

### GetSources

`func (o *UpdateProject) GetSources() UpdateProjectSources`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *UpdateProject) GetSourcesOk() (*UpdateProjectSources, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *UpdateProject) SetSources(v UpdateProjectSources)`

SetSources sets Sources field to given value.

### HasSources

`func (o *UpdateProject) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetStack

`func (o *UpdateProject) GetStack() string`

GetStack returns the Stack field if non-nil, zero value otherwise.

### GetStackOk

`func (o *UpdateProject) GetStackOk() (*string, bool)`

GetStackOk returns a tuple with the Stack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStack

`func (o *UpdateProject) SetStack(v string)`

SetStack sets Stack field to given value.

### HasStack

`func (o *UpdateProject) HasStack() bool`

HasStack returns a boolean if a field has been set.

### GetTier

`func (o *UpdateProject) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *UpdateProject) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *UpdateProject) SetTier(v string)`

SetTier sets Tier field to given value.

### HasTier

`func (o *UpdateProject) HasTier() bool`

HasTier returns a boolean if a field has been set.

### SetTierNil

`func (o *UpdateProject) SetTierNil(b bool)`

 SetTierNil sets the value for Tier to be an explicit nil

### UnsetTier
`func (o *UpdateProject) UnsetTier()`

UnsetTier ensures that no value is present for Tier, not even an explicit nil
### GetUseWorkspaceBrand

`func (o *UpdateProject) GetUseWorkspaceBrand() bool`

GetUseWorkspaceBrand returns the UseWorkspaceBrand field if non-nil, zero value otherwise.

### GetUseWorkspaceBrandOk

`func (o *UpdateProject) GetUseWorkspaceBrandOk() (*bool, bool)`

GetUseWorkspaceBrandOk returns a tuple with the UseWorkspaceBrand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseWorkspaceBrand

`func (o *UpdateProject) SetUseWorkspaceBrand(v bool)`

SetUseWorkspaceBrand sets UseWorkspaceBrand field to given value.

### HasUseWorkspaceBrand

`func (o *UpdateProject) HasUseWorkspaceBrand() bool`

HasUseWorkspaceBrand returns a boolean if a field has been set.

### GetVerifyCommand

`func (o *UpdateProject) GetVerifyCommand() string`

GetVerifyCommand returns the VerifyCommand field if non-nil, zero value otherwise.

### GetVerifyCommandOk

`func (o *UpdateProject) GetVerifyCommandOk() (*string, bool)`

GetVerifyCommandOk returns a tuple with the VerifyCommand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifyCommand

`func (o *UpdateProject) SetVerifyCommand(v string)`

SetVerifyCommand sets VerifyCommand field to given value.

### HasVerifyCommand

`func (o *UpdateProject) HasVerifyCommand() bool`

HasVerifyCommand returns a boolean if a field has been set.

### SetVerifyCommandNil

`func (o *UpdateProject) SetVerifyCommandNil(b bool)`

 SetVerifyCommandNil sets the value for VerifyCommand to be an explicit nil

### UnsetVerifyCommand
`func (o *UpdateProject) UnsetVerifyCommand()`

UnsetVerifyCommand ensures that no value is present for VerifyCommand, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


