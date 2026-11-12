# CreateBillableOneOf2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentRunId** | **string** |  |
**Currency** | **string** |  |
**Description** | **string** |  |
**MarkupBps** | Pointer to **int32** |  | [optional] [default to 0]
**Source** | **string** |  |
**TaxClass** | Pointer to **string** |  | [optional]

## Methods

### NewCreateBillableOneOf2

`func NewCreateBillableOneOf2(agentRunId string, currency string, description string, source string, ) *CreateBillableOneOf2`

NewCreateBillableOneOf2 instantiates a new CreateBillableOneOf2 object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateBillableOneOf2WithDefaults

`func NewCreateBillableOneOf2WithDefaults() *CreateBillableOneOf2`

NewCreateBillableOneOf2WithDefaults instantiates a new CreateBillableOneOf2 object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentRunId

`func (o *CreateBillableOneOf2) GetAgentRunId() string`

GetAgentRunId returns the AgentRunId field if non-nil, zero value otherwise.

### GetAgentRunIdOk

`func (o *CreateBillableOneOf2) GetAgentRunIdOk() (*string, bool)`

GetAgentRunIdOk returns a tuple with the AgentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentRunId

`func (o *CreateBillableOneOf2) SetAgentRunId(v string)`

SetAgentRunId sets AgentRunId field to given value.


### GetCurrency

`func (o *CreateBillableOneOf2) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateBillableOneOf2) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateBillableOneOf2) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *CreateBillableOneOf2) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateBillableOneOf2) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateBillableOneOf2) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetMarkupBps

`func (o *CreateBillableOneOf2) GetMarkupBps() int32`

GetMarkupBps returns the MarkupBps field if non-nil, zero value otherwise.

### GetMarkupBpsOk

`func (o *CreateBillableOneOf2) GetMarkupBpsOk() (*int32, bool)`

GetMarkupBpsOk returns a tuple with the MarkupBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkupBps

`func (o *CreateBillableOneOf2) SetMarkupBps(v int32)`

SetMarkupBps sets MarkupBps field to given value.

### HasMarkupBps

`func (o *CreateBillableOneOf2) HasMarkupBps() bool`

HasMarkupBps returns a boolean if a field has been set.

### GetSource

`func (o *CreateBillableOneOf2) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateBillableOneOf2) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateBillableOneOf2) SetSource(v string)`

SetSource sets Source field to given value.


### GetTaxClass

`func (o *CreateBillableOneOf2) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *CreateBillableOneOf2) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *CreateBillableOneOf2) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.

### HasTaxClass

`func (o *CreateBillableOneOf2) HasTaxClass() bool`

HasTaxClass returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


