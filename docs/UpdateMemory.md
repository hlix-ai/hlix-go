# UpdateMemory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Confidence** | Pointer to **float32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SupersededById** | Pointer to **NullableString** |  | [optional] 
**SupersededReason** | Pointer to **NullableString** |  | [optional] 
**Value** | Pointer to **string** |  | [optional] 

## Methods

### NewUpdateMemory

`func NewUpdateMemory() *UpdateMemory`

NewUpdateMemory instantiates a new UpdateMemory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateMemoryWithDefaults

`func NewUpdateMemoryWithDefaults() *UpdateMemory`

NewUpdateMemoryWithDefaults instantiates a new UpdateMemory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfidence

`func (o *UpdateMemory) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *UpdateMemory) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *UpdateMemory) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *UpdateMemory) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetStatus

`func (o *UpdateMemory) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateMemory) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateMemory) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateMemory) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSupersededById

`func (o *UpdateMemory) GetSupersededById() string`

GetSupersededById returns the SupersededById field if non-nil, zero value otherwise.

### GetSupersededByIdOk

`func (o *UpdateMemory) GetSupersededByIdOk() (*string, bool)`

GetSupersededByIdOk returns a tuple with the SupersededById field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupersededById

`func (o *UpdateMemory) SetSupersededById(v string)`

SetSupersededById sets SupersededById field to given value.

### HasSupersededById

`func (o *UpdateMemory) HasSupersededById() bool`

HasSupersededById returns a boolean if a field has been set.

### SetSupersededByIdNil

`func (o *UpdateMemory) SetSupersededByIdNil(b bool)`

 SetSupersededByIdNil sets the value for SupersededById to be an explicit nil

### UnsetSupersededById
`func (o *UpdateMemory) UnsetSupersededById()`

UnsetSupersededById ensures that no value is present for SupersededById, not even an explicit nil
### GetSupersededReason

`func (o *UpdateMemory) GetSupersededReason() string`

GetSupersededReason returns the SupersededReason field if non-nil, zero value otherwise.

### GetSupersededReasonOk

`func (o *UpdateMemory) GetSupersededReasonOk() (*string, bool)`

GetSupersededReasonOk returns a tuple with the SupersededReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupersededReason

`func (o *UpdateMemory) SetSupersededReason(v string)`

SetSupersededReason sets SupersededReason field to given value.

### HasSupersededReason

`func (o *UpdateMemory) HasSupersededReason() bool`

HasSupersededReason returns a boolean if a field has been set.

### SetSupersededReasonNil

`func (o *UpdateMemory) SetSupersededReasonNil(b bool)`

 SetSupersededReasonNil sets the value for SupersededReason to be an explicit nil

### UnsetSupersededReason
`func (o *UpdateMemory) UnsetSupersededReason()`

UnsetSupersededReason ensures that no value is present for SupersededReason, not even an explicit nil
### GetValue

`func (o *UpdateMemory) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateMemory) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateMemory) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateMemory) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


