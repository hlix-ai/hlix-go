# SubmitBatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Endpoint** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Items** | [**[]SubmitBatchItemsInner**](SubmitBatchItemsInner.md) |  | 
**Kind** | **string** |  | 
**Model** | **string** |  | 
**Policy** | [**SubmitBatchPolicy**](SubmitBatchPolicy.md) |  | 
**ProjectId** | Pointer to **string** |  | [optional] 

## Methods

### NewSubmitBatch

`func NewSubmitBatch(endpoint string, idempotencyKey string, items []SubmitBatchItemsInner, kind string, model string, policy SubmitBatchPolicy, ) *SubmitBatch`

NewSubmitBatch instantiates a new SubmitBatch object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitBatchWithDefaults

`func NewSubmitBatchWithDefaults() *SubmitBatch`

NewSubmitBatchWithDefaults instantiates a new SubmitBatch object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEndpoint

`func (o *SubmitBatch) GetEndpoint() string`

GetEndpoint returns the Endpoint field if non-nil, zero value otherwise.

### GetEndpointOk

`func (o *SubmitBatch) GetEndpointOk() (*string, bool)`

GetEndpointOk returns a tuple with the Endpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpoint

`func (o *SubmitBatch) SetEndpoint(v string)`

SetEndpoint sets Endpoint field to given value.


### GetIdempotencyKey

`func (o *SubmitBatch) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *SubmitBatch) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *SubmitBatch) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetItems

`func (o *SubmitBatch) GetItems() []SubmitBatchItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SubmitBatch) GetItemsOk() (*[]SubmitBatchItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SubmitBatch) SetItems(v []SubmitBatchItemsInner)`

SetItems sets Items field to given value.


### GetKind

`func (o *SubmitBatch) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *SubmitBatch) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *SubmitBatch) SetKind(v string)`

SetKind sets Kind field to given value.


### GetModel

`func (o *SubmitBatch) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SubmitBatch) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SubmitBatch) SetModel(v string)`

SetModel sets Model field to given value.


### GetPolicy

`func (o *SubmitBatch) GetPolicy() SubmitBatchPolicy`

GetPolicy returns the Policy field if non-nil, zero value otherwise.

### GetPolicyOk

`func (o *SubmitBatch) GetPolicyOk() (*SubmitBatchPolicy, bool)`

GetPolicyOk returns a tuple with the Policy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicy

`func (o *SubmitBatch) SetPolicy(v SubmitBatchPolicy)`

SetPolicy sets Policy field to given value.


### GetProjectId

`func (o *SubmitBatch) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *SubmitBatch) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *SubmitBatch) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *SubmitBatch) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


