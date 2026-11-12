# AttentionSummaryItemsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CycleId** | **NullableString** |  |
**Detail** | **NullableString** |  |
**Id** | **string** |  |
**Kind** | **string** |  |
**LeadId** | Pointer to **string** |  | [optional]
**OccurredAt** | **string** |  |
**ProjectId** | **NullableString** |  |
**ProjectName** | **NullableString** |  |
**Source** | [**AttentionSummaryItemsInnerSource**](AttentionSummaryItemsInnerSource.md) |  |
**Subject** | **NullableString** |  |
**TaskId** | **NullableString** |  |
**TaskName** | **NullableString** |  |
**Title** | **string** |  |
**Vault** | Pointer to [**AttentionSummaryItemsInnerVault**](AttentionSummaryItemsInnerVault.md) |  | [optional]

## Methods

### NewAttentionSummaryItemsInner

`func NewAttentionSummaryItemsInner(cycleId NullableString, detail NullableString, id string, kind string, occurredAt string, projectId NullableString, projectName NullableString, source AttentionSummaryItemsInnerSource, subject NullableString, taskId NullableString, taskName NullableString, title string, ) *AttentionSummaryItemsInner`

NewAttentionSummaryItemsInner instantiates a new AttentionSummaryItemsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAttentionSummaryItemsInnerWithDefaults

`func NewAttentionSummaryItemsInnerWithDefaults() *AttentionSummaryItemsInner`

NewAttentionSummaryItemsInnerWithDefaults instantiates a new AttentionSummaryItemsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCycleId

`func (o *AttentionSummaryItemsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *AttentionSummaryItemsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *AttentionSummaryItemsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *AttentionSummaryItemsInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *AttentionSummaryItemsInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDetail

`func (o *AttentionSummaryItemsInner) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *AttentionSummaryItemsInner) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *AttentionSummaryItemsInner) SetDetail(v string)`

SetDetail sets Detail field to given value.


### SetDetailNil

`func (o *AttentionSummaryItemsInner) SetDetailNil(b bool)`

 SetDetailNil sets the value for Detail to be an explicit nil

### UnsetDetail
`func (o *AttentionSummaryItemsInner) UnsetDetail()`

UnsetDetail ensures that no value is present for Detail, not even an explicit nil
### GetId

`func (o *AttentionSummaryItemsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AttentionSummaryItemsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AttentionSummaryItemsInner) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *AttentionSummaryItemsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AttentionSummaryItemsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AttentionSummaryItemsInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLeadId

`func (o *AttentionSummaryItemsInner) GetLeadId() string`

GetLeadId returns the LeadId field if non-nil, zero value otherwise.

### GetLeadIdOk

`func (o *AttentionSummaryItemsInner) GetLeadIdOk() (*string, bool)`

GetLeadIdOk returns a tuple with the LeadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeadId

`func (o *AttentionSummaryItemsInner) SetLeadId(v string)`

SetLeadId sets LeadId field to given value.

### HasLeadId

`func (o *AttentionSummaryItemsInner) HasLeadId() bool`

HasLeadId returns a boolean if a field has been set.

### GetOccurredAt

`func (o *AttentionSummaryItemsInner) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *AttentionSummaryItemsInner) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *AttentionSummaryItemsInner) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.


### GetProjectId

`func (o *AttentionSummaryItemsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AttentionSummaryItemsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AttentionSummaryItemsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *AttentionSummaryItemsInner) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *AttentionSummaryItemsInner) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetProjectName

`func (o *AttentionSummaryItemsInner) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *AttentionSummaryItemsInner) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *AttentionSummaryItemsInner) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### SetProjectNameNil

`func (o *AttentionSummaryItemsInner) SetProjectNameNil(b bool)`

 SetProjectNameNil sets the value for ProjectName to be an explicit nil

### UnsetProjectName
`func (o *AttentionSummaryItemsInner) UnsetProjectName()`

UnsetProjectName ensures that no value is present for ProjectName, not even an explicit nil
### GetSource

`func (o *AttentionSummaryItemsInner) GetSource() AttentionSummaryItemsInnerSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AttentionSummaryItemsInner) GetSourceOk() (*AttentionSummaryItemsInnerSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AttentionSummaryItemsInner) SetSource(v AttentionSummaryItemsInnerSource)`

SetSource sets Source field to given value.


### GetSubject

`func (o *AttentionSummaryItemsInner) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *AttentionSummaryItemsInner) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *AttentionSummaryItemsInner) SetSubject(v string)`

SetSubject sets Subject field to given value.


### SetSubjectNil

`func (o *AttentionSummaryItemsInner) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *AttentionSummaryItemsInner) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetTaskId

`func (o *AttentionSummaryItemsInner) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *AttentionSummaryItemsInner) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *AttentionSummaryItemsInner) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *AttentionSummaryItemsInner) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *AttentionSummaryItemsInner) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTaskName

`func (o *AttentionSummaryItemsInner) GetTaskName() string`

GetTaskName returns the TaskName field if non-nil, zero value otherwise.

### GetTaskNameOk

`func (o *AttentionSummaryItemsInner) GetTaskNameOk() (*string, bool)`

GetTaskNameOk returns a tuple with the TaskName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskName

`func (o *AttentionSummaryItemsInner) SetTaskName(v string)`

SetTaskName sets TaskName field to given value.


### SetTaskNameNil

`func (o *AttentionSummaryItemsInner) SetTaskNameNil(b bool)`

 SetTaskNameNil sets the value for TaskName to be an explicit nil

### UnsetTaskName
`func (o *AttentionSummaryItemsInner) UnsetTaskName()`

UnsetTaskName ensures that no value is present for TaskName, not even an explicit nil
### GetTitle

`func (o *AttentionSummaryItemsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AttentionSummaryItemsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AttentionSummaryItemsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetVault

`func (o *AttentionSummaryItemsInner) GetVault() AttentionSummaryItemsInnerVault`

GetVault returns the Vault field if non-nil, zero value otherwise.

### GetVaultOk

`func (o *AttentionSummaryItemsInner) GetVaultOk() (*AttentionSummaryItemsInnerVault, bool)`

GetVaultOk returns a tuple with the Vault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVault

`func (o *AttentionSummaryItemsInner) SetVault(v AttentionSummaryItemsInnerVault)`

SetVault sets Vault field to given value.

### HasVault

`func (o *AttentionSummaryItemsInner) HasVault() bool`

HasVault returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


