# UpdateTask

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional]
**DoneWhen** | Pointer to **NullableString** |  | [optional]
**Status** | Pointer to **string** |  | [optional]
**Title** | Pointer to **string** |  | [optional]

## Methods

### NewUpdateTask

`func NewUpdateTask() *UpdateTask`

NewUpdateTask instantiates a new UpdateTask object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUpdateTaskWithDefaults

`func NewUpdateTaskWithDefaults() *UpdateTask`

NewUpdateTaskWithDefaults instantiates a new UpdateTask object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDescription

`func (o *UpdateTask) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateTask) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateTask) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateTask) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDoneWhen

`func (o *UpdateTask) GetDoneWhen() string`

GetDoneWhen returns the DoneWhen field if non-nil, zero value otherwise.

### GetDoneWhenOk

`func (o *UpdateTask) GetDoneWhenOk() (*string, bool)`

GetDoneWhenOk returns a tuple with the DoneWhen field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDoneWhen

`func (o *UpdateTask) SetDoneWhen(v string)`

SetDoneWhen sets DoneWhen field to given value.

### HasDoneWhen

`func (o *UpdateTask) HasDoneWhen() bool`

HasDoneWhen returns a boolean if a field has been set.

### SetDoneWhenNil

`func (o *UpdateTask) SetDoneWhenNil(b bool)`

 SetDoneWhenNil sets the value for DoneWhen to be an explicit nil

### UnsetDoneWhen
`func (o *UpdateTask) UnsetDoneWhen()`

UnsetDoneWhen ensures that no value is present for DoneWhen, not even an explicit nil
### GetStatus

`func (o *UpdateTask) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateTask) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateTask) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateTask) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTitle

`func (o *UpdateTask) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *UpdateTask) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *UpdateTask) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *UpdateTask) HasTitle() bool`

HasTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


