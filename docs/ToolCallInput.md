# ToolCallInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Funding** | Pointer to **string** |  | [optional] [default to "auto"]
**IdempotencyKey** | **string** |  | 
**Input** | **map[string]interface{}** |  | 
**MaxCostMicros** | Pointer to **int64** | Provider reservation budget in USD micros. Actual settlement may exceed this amount. | [optional] 
**ProjectId** | Pointer to **string** |  | [optional] 

## Methods

### NewToolCallInput

`func NewToolCallInput(idempotencyKey string, input map[string]interface{}, ) *ToolCallInput`

NewToolCallInput instantiates a new ToolCallInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolCallInputWithDefaults

`func NewToolCallInputWithDefaults() *ToolCallInput`

NewToolCallInputWithDefaults instantiates a new ToolCallInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFunding

`func (o *ToolCallInput) GetFunding() string`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *ToolCallInput) GetFundingOk() (*string, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *ToolCallInput) SetFunding(v string)`

SetFunding sets Funding field to given value.

### HasFunding

`func (o *ToolCallInput) HasFunding() bool`

HasFunding returns a boolean if a field has been set.

### GetIdempotencyKey

`func (o *ToolCallInput) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *ToolCallInput) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *ToolCallInput) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetInput

`func (o *ToolCallInput) GetInput() map[string]interface{}`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *ToolCallInput) GetInputOk() (*map[string]interface{}, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *ToolCallInput) SetInput(v map[string]interface{})`

SetInput sets Input field to given value.


### GetMaxCostMicros

`func (o *ToolCallInput) GetMaxCostMicros() int64`

GetMaxCostMicros returns the MaxCostMicros field if non-nil, zero value otherwise.

### GetMaxCostMicrosOk

`func (o *ToolCallInput) GetMaxCostMicrosOk() (*int64, bool)`

GetMaxCostMicrosOk returns a tuple with the MaxCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCostMicros

`func (o *ToolCallInput) SetMaxCostMicros(v int64)`

SetMaxCostMicros sets MaxCostMicros field to given value.

### HasMaxCostMicros

`func (o *ToolCallInput) HasMaxCostMicros() bool`

HasMaxCostMicros returns a boolean if a field has been set.

### GetProjectId

`func (o *ToolCallInput) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ToolCallInput) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ToolCallInput) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ToolCallInput) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


