# ToolCall

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingOwner** | **string** |  | 
**BilledMicros** | **NullableInt64** |  | 
**CostStatus** | **string** |  | 
**CreatedAt** | **string** |  | 
**Error** | [**NullableToolCallError**](ToolCallError.md) |  | 
**Funding** | **string** |  | 
**Id** | **string** |  | 
**ProjectId** | **NullableString** |  | 
**ProviderCostMicros** | **NullableInt64** |  | 
**ReservedMicros** | **int64** |  | 
**Result** | **interface{}** |  | 
**Status** | **string** |  | 
**ToolId** | **string** |  | 
**ToolName** | Pointer to **string** |  | [optional] 
**UpdatedAt** | **string** |  | 

## Methods

### NewToolCall

`func NewToolCall(accountingOwner string, billedMicros NullableInt64, costStatus string, createdAt string, error_ NullableToolCallError, funding string, id string, projectId NullableString, providerCostMicros NullableInt64, reservedMicros int64, result interface{}, status string, toolId string, updatedAt string, ) *ToolCall`

NewToolCall instantiates a new ToolCall object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolCallWithDefaults

`func NewToolCallWithDefaults() *ToolCall`

NewToolCallWithDefaults instantiates a new ToolCall object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingOwner

`func (o *ToolCall) GetAccountingOwner() string`

GetAccountingOwner returns the AccountingOwner field if non-nil, zero value otherwise.

### GetAccountingOwnerOk

`func (o *ToolCall) GetAccountingOwnerOk() (*string, bool)`

GetAccountingOwnerOk returns a tuple with the AccountingOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingOwner

`func (o *ToolCall) SetAccountingOwner(v string)`

SetAccountingOwner sets AccountingOwner field to given value.


### GetBilledMicros

`func (o *ToolCall) GetBilledMicros() int64`

GetBilledMicros returns the BilledMicros field if non-nil, zero value otherwise.

### GetBilledMicrosOk

`func (o *ToolCall) GetBilledMicrosOk() (*int64, bool)`

GetBilledMicrosOk returns a tuple with the BilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledMicros

`func (o *ToolCall) SetBilledMicros(v int64)`

SetBilledMicros sets BilledMicros field to given value.


### SetBilledMicrosNil

`func (o *ToolCall) SetBilledMicrosNil(b bool)`

 SetBilledMicrosNil sets the value for BilledMicros to be an explicit nil

### UnsetBilledMicros
`func (o *ToolCall) UnsetBilledMicros()`

UnsetBilledMicros ensures that no value is present for BilledMicros, not even an explicit nil
### GetCostStatus

`func (o *ToolCall) GetCostStatus() string`

GetCostStatus returns the CostStatus field if non-nil, zero value otherwise.

### GetCostStatusOk

`func (o *ToolCall) GetCostStatusOk() (*string, bool)`

GetCostStatusOk returns a tuple with the CostStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostStatus

`func (o *ToolCall) SetCostStatus(v string)`

SetCostStatus sets CostStatus field to given value.


### GetCreatedAt

`func (o *ToolCall) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ToolCall) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ToolCall) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *ToolCall) GetError() ToolCallError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ToolCall) GetErrorOk() (*ToolCallError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ToolCall) SetError(v ToolCallError)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *ToolCall) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ToolCall) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFunding

`func (o *ToolCall) GetFunding() string`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *ToolCall) GetFundingOk() (*string, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *ToolCall) SetFunding(v string)`

SetFunding sets Funding field to given value.


### GetId

`func (o *ToolCall) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ToolCall) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ToolCall) SetId(v string)`

SetId sets Id field to given value.


### GetProjectId

`func (o *ToolCall) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ToolCall) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ToolCall) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *ToolCall) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ToolCall) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetProviderCostMicros

`func (o *ToolCall) GetProviderCostMicros() int64`

GetProviderCostMicros returns the ProviderCostMicros field if non-nil, zero value otherwise.

### GetProviderCostMicrosOk

`func (o *ToolCall) GetProviderCostMicrosOk() (*int64, bool)`

GetProviderCostMicrosOk returns a tuple with the ProviderCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderCostMicros

`func (o *ToolCall) SetProviderCostMicros(v int64)`

SetProviderCostMicros sets ProviderCostMicros field to given value.


### SetProviderCostMicrosNil

`func (o *ToolCall) SetProviderCostMicrosNil(b bool)`

 SetProviderCostMicrosNil sets the value for ProviderCostMicros to be an explicit nil

### UnsetProviderCostMicros
`func (o *ToolCall) UnsetProviderCostMicros()`

UnsetProviderCostMicros ensures that no value is present for ProviderCostMicros, not even an explicit nil
### GetReservedMicros

`func (o *ToolCall) GetReservedMicros() int64`

GetReservedMicros returns the ReservedMicros field if non-nil, zero value otherwise.

### GetReservedMicrosOk

`func (o *ToolCall) GetReservedMicrosOk() (*int64, bool)`

GetReservedMicrosOk returns a tuple with the ReservedMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedMicros

`func (o *ToolCall) SetReservedMicros(v int64)`

SetReservedMicros sets ReservedMicros field to given value.


### GetResult

`func (o *ToolCall) GetResult() interface{}`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ToolCall) GetResultOk() (*interface{}, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ToolCall) SetResult(v interface{})`

SetResult sets Result field to given value.


### SetResultNil

`func (o *ToolCall) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *ToolCall) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetStatus

`func (o *ToolCall) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ToolCall) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ToolCall) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetToolId

`func (o *ToolCall) GetToolId() string`

GetToolId returns the ToolId field if non-nil, zero value otherwise.

### GetToolIdOk

`func (o *ToolCall) GetToolIdOk() (*string, bool)`

GetToolIdOk returns a tuple with the ToolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolId

`func (o *ToolCall) SetToolId(v string)`

SetToolId sets ToolId field to given value.


### GetToolName

`func (o *ToolCall) GetToolName() string`

GetToolName returns the ToolName field if non-nil, zero value otherwise.

### GetToolNameOk

`func (o *ToolCall) GetToolNameOk() (*string, bool)`

GetToolNameOk returns a tuple with the ToolName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolName

`func (o *ToolCall) SetToolName(v string)`

SetToolName sets ToolName field to given value.

### HasToolName

`func (o *ToolCall) HasToolName() bool`

HasToolName returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ToolCall) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ToolCall) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ToolCall) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


