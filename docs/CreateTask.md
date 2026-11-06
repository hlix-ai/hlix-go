# CreateTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** |  | 
**DoneWhen** | Pointer to **string** |  | [optional] 
**ProjectId** | **string** |  | 
**TaskConfig** | Pointer to [**CreateTaskTaskConfig**](CreateTaskTaskConfig.md) |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateTask

`func NewCreateTask(description string, projectId string, ) *CreateTask`

NewCreateTask instantiates a new CreateTask object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTaskWithDefaults

`func NewCreateTaskWithDefaults() *CreateTask`

NewCreateTaskWithDefaults instantiates a new CreateTask object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *CreateTask) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateTask) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateTask) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetDoneWhen

`func (o *CreateTask) GetDoneWhen() string`

GetDoneWhen returns the DoneWhen field if non-nil, zero value otherwise.

### GetDoneWhenOk

`func (o *CreateTask) GetDoneWhenOk() (*string, bool)`

GetDoneWhenOk returns a tuple with the DoneWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoneWhen

`func (o *CreateTask) SetDoneWhen(v string)`

SetDoneWhen sets DoneWhen field to given value.

### HasDoneWhen

`func (o *CreateTask) HasDoneWhen() bool`

HasDoneWhen returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateTask) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateTask) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateTask) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetTaskConfig

`func (o *CreateTask) GetTaskConfig() CreateTaskTaskConfig`

GetTaskConfig returns the TaskConfig field if non-nil, zero value otherwise.

### GetTaskConfigOk

`func (o *CreateTask) GetTaskConfigOk() (*CreateTaskTaskConfig, bool)`

GetTaskConfigOk returns a tuple with the TaskConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskConfig

`func (o *CreateTask) SetTaskConfig(v CreateTaskTaskConfig)`

SetTaskConfig sets TaskConfig field to given value.

### HasTaskConfig

`func (o *CreateTask) HasTaskConfig() bool`

HasTaskConfig returns a boolean if a field has been set.

### GetTitle

`func (o *CreateTask) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateTask) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateTask) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreateTask) HasTitle() bool`

HasTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


