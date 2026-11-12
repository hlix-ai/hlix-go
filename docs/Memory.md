# Memory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Category** | **string** |  |
**Confidence** | **float32** |  |
**CreatedAt** | **string** |  |
**Id** | **string** |  |
**Key** | **string** |  |
**OrganizationId** | **string** |  |
**Scope** | **string** |  |
**ScopeId** | **string** |  |
**Score** | Pointer to **float32** |  | [optional]
**Source** | **string** |  |
**Status** | **string** |  |
**UpdatedAt** | **string** |  |
**Value** | **string** |  |

## Methods

### NewMemory

`func NewMemory(category string, confidence float32, createdAt string, id string, key string, organizationId string, scope string, scopeId string, source string, status string, updatedAt string, value string, ) *Memory`

NewMemory instantiates a new Memory object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMemoryWithDefaults

`func NewMemoryWithDefaults() *Memory`

NewMemoryWithDefaults instantiates a new Memory object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCategory

`func (o *Memory) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Memory) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Memory) SetCategory(v string)`

SetCategory sets Category field to given value.


### GetConfidence

`func (o *Memory) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *Memory) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *Memory) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.


### GetCreatedAt

`func (o *Memory) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Memory) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Memory) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *Memory) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Memory) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Memory) SetId(v string)`

SetId sets Id field to given value.


### GetKey

`func (o *Memory) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *Memory) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *Memory) SetKey(v string)`

SetKey sets Key field to given value.


### GetOrganizationId

`func (o *Memory) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Memory) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Memory) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetScope

`func (o *Memory) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *Memory) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *Memory) SetScope(v string)`

SetScope sets Scope field to given value.


### GetScopeId

`func (o *Memory) GetScopeId() string`

GetScopeId returns the ScopeId field if non-nil, zero value otherwise.

### GetScopeIdOk

`func (o *Memory) GetScopeIdOk() (*string, bool)`

GetScopeIdOk returns a tuple with the ScopeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeId

`func (o *Memory) SetScopeId(v string)`

SetScopeId sets ScopeId field to given value.


### GetScore

`func (o *Memory) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *Memory) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *Memory) SetScore(v float32)`

SetScore sets Score field to given value.

### HasScore

`func (o *Memory) HasScore() bool`

HasScore returns a boolean if a field has been set.

### GetSource

`func (o *Memory) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Memory) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Memory) SetSource(v string)`

SetSource sets Source field to given value.


### GetStatus

`func (o *Memory) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Memory) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Memory) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *Memory) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Memory) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Memory) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetValue

`func (o *Memory) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *Memory) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *Memory) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


