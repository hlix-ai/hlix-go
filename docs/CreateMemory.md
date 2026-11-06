# CreateMemory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | **string** |  | 
**Confidence** | Pointer to **float32** |  | [optional] 
**Key** | **string** |  | 
**Scope** | **string** |  | 
**ScopeId** | **string** |  | 
**Source** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SupersededReason** | Pointer to **string** |  | [optional] 
**SupersedesId** | Pointer to **string** |  | [optional] 
**Value** | **string** |  | 

## Methods

### NewCreateMemory

`func NewCreateMemory(category string, key string, scope string, scopeId string, value string, ) *CreateMemory`

NewCreateMemory instantiates a new CreateMemory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateMemoryWithDefaults

`func NewCreateMemoryWithDefaults() *CreateMemory`

NewCreateMemoryWithDefaults instantiates a new CreateMemory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategory

`func (o *CreateMemory) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *CreateMemory) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *CreateMemory) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetConfidence

`func (o *CreateMemory) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *CreateMemory) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *CreateMemory) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *CreateMemory) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetKey

`func (o *CreateMemory) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateMemory) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateMemory) SetKey(v string)`

SetKey sets Key field to given value.


### GetScope

`func (o *CreateMemory) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *CreateMemory) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *CreateMemory) SetScope(v string)`

SetScope sets Scope field to given value.


### GetScopeId

`func (o *CreateMemory) GetScopeId() string`

GetScopeId returns the ScopeId field if non-nil, zero value otherwise.

### GetScopeIdOk

`func (o *CreateMemory) GetScopeIdOk() (*string, bool)`

GetScopeIdOk returns a tuple with the ScopeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeId

`func (o *CreateMemory) SetScopeId(v string)`

SetScopeId sets ScopeId field to given value.


### GetSource

`func (o *CreateMemory) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateMemory) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateMemory) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *CreateMemory) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetStatus

`func (o *CreateMemory) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateMemory) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateMemory) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateMemory) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSupersededReason

`func (o *CreateMemory) GetSupersededReason() string`

GetSupersededReason returns the SupersededReason field if non-nil, zero value otherwise.

### GetSupersededReasonOk

`func (o *CreateMemory) GetSupersededReasonOk() (*string, bool)`

GetSupersededReasonOk returns a tuple with the SupersededReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupersededReason

`func (o *CreateMemory) SetSupersededReason(v string)`

SetSupersededReason sets SupersededReason field to given value.

### HasSupersededReason

`func (o *CreateMemory) HasSupersededReason() bool`

HasSupersededReason returns a boolean if a field has been set.

### GetSupersedesId

`func (o *CreateMemory) GetSupersedesId() string`

GetSupersedesId returns the SupersedesId field if non-nil, zero value otherwise.

### GetSupersedesIdOk

`func (o *CreateMemory) GetSupersedesIdOk() (*string, bool)`

GetSupersedesIdOk returns a tuple with the SupersedesId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupersedesId

`func (o *CreateMemory) SetSupersedesId(v string)`

SetSupersedesId sets SupersedesId field to given value.

### HasSupersedesId

`func (o *CreateMemory) HasSupersedesId() bool`

HasSupersedesId returns a boolean if a field has been set.

### GetValue

`func (o *CreateMemory) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *CreateMemory) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *CreateMemory) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


