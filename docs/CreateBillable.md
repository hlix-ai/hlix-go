# CreateBillable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientAccountId** | **string** |  | 
**Currency** | **string** |  | 
**Description** | **string** |  | 
**Note** | Pointer to **string** |  | [optional] 
**OccurredAt** | Pointer to **time.Time** |  | [optional] 
**ProjectId** | Pointer to **string** |  | [optional] 
**Quantity** | **float32** |  | 
**Source** | **string** |  | 
**TaxClass** | Pointer to **string** |  | [optional] 
**Unit** | **string** |  | 
**UnitPriceMicros** | **int64** |  | 
**CycleId** | **string** |  | 
**AgentRunId** | **string** |  | 
**MarkupBps** | Pointer to **int32** |  | [optional] [default to 0]

## Methods

### NewCreateBillable

`func NewCreateBillable(clientAccountId string, currency string, description string, quantity float32, source string, unit string, unitPriceMicros int64, cycleId string, agentRunId string, ) *CreateBillable`

NewCreateBillable instantiates a new CreateBillable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateBillableWithDefaults

`func NewCreateBillableWithDefaults() *CreateBillable`

NewCreateBillableWithDefaults instantiates a new CreateBillable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientAccountId

`func (o *CreateBillable) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CreateBillable) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CreateBillable) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetCurrency

`func (o *CreateBillable) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateBillable) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateBillable) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *CreateBillable) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateBillable) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateBillable) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetNote

`func (o *CreateBillable) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CreateBillable) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CreateBillable) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CreateBillable) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetOccurredAt

`func (o *CreateBillable) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *CreateBillable) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *CreateBillable) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *CreateBillable) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateBillable) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateBillable) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateBillable) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateBillable) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetQuantity

`func (o *CreateBillable) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateBillable) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateBillable) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetSource

`func (o *CreateBillable) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateBillable) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateBillable) SetSource(v string)`

SetSource sets Source field to given value.


### GetTaxClass

`func (o *CreateBillable) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *CreateBillable) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *CreateBillable) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.

### HasTaxClass

`func (o *CreateBillable) HasTaxClass() bool`

HasTaxClass returns a boolean if a field has been set.

### GetUnit

`func (o *CreateBillable) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *CreateBillable) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *CreateBillable) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *CreateBillable) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *CreateBillable) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *CreateBillable) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.


### GetCycleId

`func (o *CreateBillable) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *CreateBillable) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *CreateBillable) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetAgentRunId

`func (o *CreateBillable) GetAgentRunId() string`

GetAgentRunId returns the AgentRunId field if non-nil, zero value otherwise.

### GetAgentRunIdOk

`func (o *CreateBillable) GetAgentRunIdOk() (*string, bool)`

GetAgentRunIdOk returns a tuple with the AgentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentRunId

`func (o *CreateBillable) SetAgentRunId(v string)`

SetAgentRunId sets AgentRunId field to given value.


### GetMarkupBps

`func (o *CreateBillable) GetMarkupBps() int32`

GetMarkupBps returns the MarkupBps field if non-nil, zero value otherwise.

### GetMarkupBpsOk

`func (o *CreateBillable) GetMarkupBpsOk() (*int32, bool)`

GetMarkupBpsOk returns a tuple with the MarkupBps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkupBps

`func (o *CreateBillable) SetMarkupBps(v int32)`

SetMarkupBps sets MarkupBps field to given value.

### HasMarkupBps

`func (o *CreateBillable) HasMarkupBps() bool`

HasMarkupBps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


