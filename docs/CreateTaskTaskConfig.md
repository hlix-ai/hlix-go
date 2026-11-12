# CreateTaskTaskConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Agent** | Pointer to **string** |  | [optional]
**Funding** | Pointer to [**CreateTaskTaskConfigFunding**](CreateTaskTaskConfigFunding.md) |  | [optional]

## Methods

### NewCreateTaskTaskConfig

`func NewCreateTaskTaskConfig() *CreateTaskTaskConfig`

NewCreateTaskTaskConfig instantiates a new CreateTaskTaskConfig object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateTaskTaskConfigWithDefaults

`func NewCreateTaskTaskConfigWithDefaults() *CreateTaskTaskConfig`

NewCreateTaskTaskConfigWithDefaults instantiates a new CreateTaskTaskConfig object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgent

`func (o *CreateTaskTaskConfig) GetAgent() string`

GetAgent returns the Agent field if non-nil, zero value otherwise.

### GetAgentOk

`func (o *CreateTaskTaskConfig) GetAgentOk() (*string, bool)`

GetAgentOk returns a tuple with the Agent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgent

`func (o *CreateTaskTaskConfig) SetAgent(v string)`

SetAgent sets Agent field to given value.

### HasAgent

`func (o *CreateTaskTaskConfig) HasAgent() bool`

HasAgent returns a boolean if a field has been set.

### GetFunding

`func (o *CreateTaskTaskConfig) GetFunding() CreateTaskTaskConfigFunding`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *CreateTaskTaskConfig) GetFundingOk() (*CreateTaskTaskConfigFunding, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *CreateTaskTaskConfig) SetFunding(v CreateTaskTaskConfigFunding)`

SetFunding sets Funding field to given value.

### HasFunding

`func (o *CreateTaskTaskConfig) HasFunding() bool`

HasFunding returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


