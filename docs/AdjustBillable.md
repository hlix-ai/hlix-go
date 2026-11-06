# AdjustBillable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** |  | 
**Note** | Pointer to **NullableString** |  | [optional] 
**Quantity** | **float32** |  | 
**Unit** | **string** |  | 
**UnitPriceMicros** | **int64** |  | 

## Methods

### NewAdjustBillable

`func NewAdjustBillable(description string, quantity float32, unit string, unitPriceMicros int64, ) *AdjustBillable`

NewAdjustBillable instantiates a new AdjustBillable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdjustBillableWithDefaults

`func NewAdjustBillableWithDefaults() *AdjustBillable`

NewAdjustBillableWithDefaults instantiates a new AdjustBillable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *AdjustBillable) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AdjustBillable) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AdjustBillable) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetNote

`func (o *AdjustBillable) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AdjustBillable) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AdjustBillable) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AdjustBillable) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *AdjustBillable) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *AdjustBillable) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetQuantity

`func (o *AdjustBillable) GetQuantity() float32`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *AdjustBillable) GetQuantityOk() (*float32, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *AdjustBillable) SetQuantity(v float32)`

SetQuantity sets Quantity field to given value.


### GetUnit

`func (o *AdjustBillable) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *AdjustBillable) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *AdjustBillable) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *AdjustBillable) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *AdjustBillable) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *AdjustBillable) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


