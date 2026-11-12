# CreateBillableOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientAccountId** | **string** |  |
**Currency** | **string** |  |
**Description** | **string** |  |
**Note** | Pointer to **NullableString** |  | [optional]
**OccurredAt** | Pointer to **time.Time** |  | [optional]
**ProjectId** | Pointer to **NullableString** |  | [optional]
**Quantity** | **float32** |  |
**Source** | **string** |  |
**TaxClass** | Pointer to **string** |  | [optional]
**Unit** | **string** |  |
**UnitPriceMicros** | **int64** |  |

## Methods

### NewCreateBillableOneOf

`func NewCreateBillableOneOf(clientAccountId string, currency string, description string, quantity float32, source string, unit string, unitPriceMicros int64, ) *CreateBillableOneOf`

NewCreateBillableOneOf instantiates a new CreateBillableOneOf object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCreateBillableOneOfWithDefaults

`func NewCreateBillableOneOfWithDefaults() *CreateBillableOneOf`

NewCreateBillableOneOfWithDefaults instantiates a new CreateBillableOneOf object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetClientAccountId

`func (o *CreateBillableOneOf) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CreateBillableOneOf) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CreateBillableOneOf) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetCurrency

`func (o *CreateBillableOneOf) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateBillableOneOf) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateBillableOneOf) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *CreateBillableOneOf) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateBillableOneOf) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateBillableOneOf) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetNote

`func (o *CreateBillableOneOf) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CreateBillableOneOf) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CreateBillableOneOf) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CreateBillableOneOf) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *CreateBillableOneOf) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *CreateBillableOneOf) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetOccurredAt

`func (o *CreateBillableOneOf) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *CreateBillableOneOf) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *CreateBillableOneOf) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.

### HasOccurredAt

`func (o *CreateBillableOneOf) HasOccurredAt() bool`

HasOccurredAt returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateBillableOneOf) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateBillableOneOf) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateBillableOneOf) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateBillableOneOf) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *CreateBillableOneOf) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *CreateBillableOneOf) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetQuantity

`func (o *CreateBillableOneOf) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateBillableOneOf) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateBillableOneOf) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetSource

`func (o *CreateBillableOneOf) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateBillableOneOf) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateBillableOneOf) SetSource(v string)`

SetSource sets Source field to given value.


### GetTaxClass

`func (o *CreateBillableOneOf) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *CreateBillableOneOf) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *CreateBillableOneOf) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.

### HasTaxClass

`func (o *CreateBillableOneOf) HasTaxClass() bool`

HasTaxClass returns a boolean if a field has been set.

### GetUnit

`func (o *CreateBillableOneOf) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *CreateBillableOneOf) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *CreateBillableOneOf) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *CreateBillableOneOf) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *CreateBillableOneOf) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *CreateBillableOneOf) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


