# CreateCycle

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Attachments** | Pointer to [**[]AnalyzeMediaSourceAnyOf1**](AnalyzeMediaSourceAnyOf1.md) |  | [optional]
**Description** | **string** |  |
**ProjectId** | **string** |  |
**TargetBranch** | Pointer to **string** |  | [optional]
**Title** | **string** |  |

## Methods

### NewCreateCycle

`func NewCreateCycle(description string, projectId string, title string, ) *CreateCycle`

NewCreateCycle instantiates a new CreateCycle object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateCycleWithDefaults

`func NewCreateCycleWithDefaults() *CreateCycle`

NewCreateCycleWithDefaults instantiates a new CreateCycle object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAttachments

`func (o *CreateCycle) GetAttachments() []AnalyzeMediaSourceAnyOf1`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *CreateCycle) GetAttachmentsOk() (*[]AnalyzeMediaSourceAnyOf1, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *CreateCycle) SetAttachments(v []AnalyzeMediaSourceAnyOf1)`

SetAttachments sets Attachments field to given value.

### HasAttachments

`func (o *CreateCycle) HasAttachments() bool`

HasAttachments returns a boolean if a field has been set.

### GetDescription

`func (o *CreateCycle) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateCycle) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateCycle) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetProjectId

`func (o *CreateCycle) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateCycle) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateCycle) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetTargetBranch

`func (o *CreateCycle) GetTargetBranch() string`

GetTargetBranch returns the TargetBranch field if non-nil, zero value otherwise.

### GetTargetBranchOk

`func (o *CreateCycle) GetTargetBranchOk() (*string, bool)`

GetTargetBranchOk returns a tuple with the TargetBranch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetBranch

`func (o *CreateCycle) SetTargetBranch(v string)`

SetTargetBranch sets TargetBranch field to given value.

### HasTargetBranch

`func (o *CreateCycle) HasTargetBranch() bool`

HasTargetBranch returns a boolean if a field has been set.

### GetTitle

`func (o *CreateCycle) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateCycle) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateCycle) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


