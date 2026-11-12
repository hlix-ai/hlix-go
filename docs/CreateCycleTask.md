# CreateCycleTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DependsOn** | Pointer to **[]string** |  | [optional]
**Description** | **string** |  |
**DoneWhen** | Pointer to **string** |  | [optional]
**Title** | **string** |  |

## Methods

### NewCreateCycleTask

`func NewCreateCycleTask(description string, title string, ) *CreateCycleTask`

NewCreateCycleTask instantiates a new CreateCycleTask object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateCycleTaskWithDefaults

`func NewCreateCycleTaskWithDefaults() *CreateCycleTask`

NewCreateCycleTaskWithDefaults instantiates a new CreateCycleTask object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDependsOn

`func (o *CreateCycleTask) GetDependsOn() []string`

GetDependsOn returns the DependsOn field if non-nil, zero value otherwise.

### GetDependsOnOk

`func (o *CreateCycleTask) GetDependsOnOk() (*[]string, bool)`

GetDependsOnOk returns a tuple with the DependsOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependsOn

`func (o *CreateCycleTask) SetDependsOn(v []string)`

SetDependsOn sets DependsOn field to given value.

### HasDependsOn

`func (o *CreateCycleTask) HasDependsOn() bool`

HasDependsOn returns a boolean if a field has been set.

### GetDescription

`func (o *CreateCycleTask) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateCycleTask) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateCycleTask) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetDoneWhen

`func (o *CreateCycleTask) GetDoneWhen() string`

GetDoneWhen returns the DoneWhen field if non-nil, zero value otherwise.

### GetDoneWhenOk

`func (o *CreateCycleTask) GetDoneWhenOk() (*string, bool)`

GetDoneWhenOk returns a tuple with the DoneWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoneWhen

`func (o *CreateCycleTask) SetDoneWhen(v string)`

SetDoneWhen sets DoneWhen field to given value.

### HasDoneWhen

`func (o *CreateCycleTask) HasDoneWhen() bool`

HasDoneWhen returns a boolean if a field has been set.

### GetTitle

`func (o *CreateCycleTask) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateCycleTask) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateCycleTask) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


