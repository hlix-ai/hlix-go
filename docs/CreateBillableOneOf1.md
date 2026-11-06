# CreateBillableOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | **string** |  | 
**CycleId** | **string** |  | 
**Description** | **string** |  | 
**Note** | Pointer to **NullableString** |  | [optional] 
**Quantity** | **float32** |  | 
**Source** | **string** |  | 
**TaxClass** | Pointer to **string** |  | [optional] 
**Unit** | **string** |  | 
**UnitPriceMicros** | **int64** |  | 

## Methods

### NewCreateBillableOneOf1

`func NewCreateBillableOneOf1(currency string, cycleId string, description string, quantity float32, source string, unit string, unitPriceMicros int64, ) *CreateBillableOneOf1`

NewCreateBillableOneOf1 instantiates a new CreateBillableOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateBillableOneOf1WithDefaults

`func NewCreateBillableOneOf1WithDefaults() *CreateBillableOneOf1`

NewCreateBillableOneOf1WithDefaults instantiates a new CreateBillableOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *CreateBillableOneOf1) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateBillableOneOf1) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateBillableOneOf1) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCycleId

`func (o *CreateBillableOneOf1) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *CreateBillableOneOf1) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *CreateBillableOneOf1) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### GetDescription

`func (o *CreateBillableOneOf1) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateBillableOneOf1) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateBillableOneOf1) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetNote

`func (o *CreateBillableOneOf1) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *CreateBillableOneOf1) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *CreateBillableOneOf1) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *CreateBillableOneOf1) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *CreateBillableOneOf1) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *CreateBillableOneOf1) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetQuantity

`func (o *CreateBillableOneOf1) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *CreateBillableOneOf1) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *CreateBillableOneOf1) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetSource

`func (o *CreateBillableOneOf1) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateBillableOneOf1) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateBillableOneOf1) SetSource(v string)`

SetSource sets Source field to given value.


### GetTaxClass

`func (o *CreateBillableOneOf1) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *CreateBillableOneOf1) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *CreateBillableOneOf1) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.

### HasTaxClass

`func (o *CreateBillableOneOf1) HasTaxClass() bool`

HasTaxClass returns a boolean if a field has been set.

### GetUnit

`func (o *CreateBillableOneOf1) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *CreateBillableOneOf1) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *CreateBillableOneOf1) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *CreateBillableOneOf1) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *CreateBillableOneOf1) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *CreateBillableOneOf1) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


