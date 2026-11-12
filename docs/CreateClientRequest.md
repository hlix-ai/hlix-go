# CreateClientRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProjectId** | **string** |  |
**Title** | Pointer to **string** |  | [optional]

## Methods

### NewCreateClientRequest

`func NewCreateClientRequest(projectId string, ) *CreateClientRequest`

NewCreateClientRequest instantiates a new CreateClientRequest object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateClientRequestWithDefaults

`func NewCreateClientRequestWithDefaults() *CreateClientRequest`

NewCreateClientRequestWithDefaults instantiates a new CreateClientRequest object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetProjectId

`func (o *CreateClientRequest) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateClientRequest) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateClientRequest) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetTitle

`func (o *CreateClientRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateClientRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateClientRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreateClientRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


