# ToolCallListCallsInner

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

### NewToolCallListCallsInner

`func NewToolCallListCallsInner(accountingOwner string, billedMicros NullableInt64, costStatus string, createdAt string, error_ NullableToolCallError, funding string, id string, projectId NullableString, providerCostMicros NullableInt64, reservedMicros int64, result interface{}, status string, toolId string, updatedAt string, ) *ToolCallListCallsInner`

NewToolCallListCallsInner instantiates a new ToolCallListCallsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolCallListCallsInnerWithDefaults

`func NewToolCallListCallsInnerWithDefaults() *ToolCallListCallsInner`

NewToolCallListCallsInnerWithDefaults instantiates a new ToolCallListCallsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingOwner

`func (o *ToolCallListCallsInner) GetAccountingOwner() string`

GetAccountingOwner returns the AccountingOwner field if non-nil, zero value otherwise.

### GetAccountingOwnerOk

`func (o *ToolCallListCallsInner) GetAccountingOwnerOk() (*string, bool)`

GetAccountingOwnerOk returns a tuple with the AccountingOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingOwner

`func (o *ToolCallListCallsInner) SetAccountingOwner(v string)`

SetAccountingOwner sets AccountingOwner field to given value.


### GetBilledMicros

`func (o *ToolCallListCallsInner) GetBilledMicros() int64`

GetBilledMicros returns the BilledMicros field if non-nil, zero value otherwise.

### GetBilledMicrosOk

`func (o *ToolCallListCallsInner) GetBilledMicrosOk() (*int64, bool)`

GetBilledMicrosOk returns a tuple with the BilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilledMicros

`func (o *ToolCallListCallsInner) SetBilledMicros(v int64)`

SetBilledMicros sets BilledMicros field to given value.


### SetBilledMicrosNil

`func (o *ToolCallListCallsInner) SetBilledMicrosNil(b bool)`

 SetBilledMicrosNil sets the value for BilledMicros to be an explicit nil

### UnsetBilledMicros
`func (o *ToolCallListCallsInner) UnsetBilledMicros()`

UnsetBilledMicros ensures that no value is present for BilledMicros, not even an explicit nil
### GetCostStatus

`func (o *ToolCallListCallsInner) GetCostStatus() string`

GetCostStatus returns the CostStatus field if non-nil, zero value otherwise.

### GetCostStatusOk

`func (o *ToolCallListCallsInner) GetCostStatusOk() (*string, bool)`

GetCostStatusOk returns a tuple with the CostStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostStatus

`func (o *ToolCallListCallsInner) SetCostStatus(v string)`

SetCostStatus sets CostStatus field to given value.


### GetCreatedAt

`func (o *ToolCallListCallsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ToolCallListCallsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ToolCallListCallsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *ToolCallListCallsInner) GetError() ToolCallError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ToolCallListCallsInner) GetErrorOk() (*ToolCallError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ToolCallListCallsInner) SetError(v ToolCallError)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *ToolCallListCallsInner) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ToolCallListCallsInner) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFunding

`func (o *ToolCallListCallsInner) GetFunding() string`

GetFunding returns the Funding field if non-nil, zero value otherwise.

### GetFundingOk

`func (o *ToolCallListCallsInner) GetFundingOk() (*string, bool)`

GetFundingOk returns a tuple with the Funding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunding

`func (o *ToolCallListCallsInner) SetFunding(v string)`

SetFunding sets Funding field to given value.


### GetId

`func (o *ToolCallListCallsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ToolCallListCallsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ToolCallListCallsInner) SetId(v string)`

SetId sets Id field to given value.


### GetProjectId

`func (o *ToolCallListCallsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ToolCallListCallsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ToolCallListCallsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *ToolCallListCallsInner) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ToolCallListCallsInner) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetProviderCostMicros

`func (o *ToolCallListCallsInner) GetProviderCostMicros() int64`

GetProviderCostMicros returns the ProviderCostMicros field if non-nil, zero value otherwise.

### GetProviderCostMicrosOk

`func (o *ToolCallListCallsInner) GetProviderCostMicrosOk() (*int64, bool)`

GetProviderCostMicrosOk returns a tuple with the ProviderCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderCostMicros

`func (o *ToolCallListCallsInner) SetProviderCostMicros(v int64)`

SetProviderCostMicros sets ProviderCostMicros field to given value.


### SetProviderCostMicrosNil

`func (o *ToolCallListCallsInner) SetProviderCostMicrosNil(b bool)`

 SetProviderCostMicrosNil sets the value for ProviderCostMicros to be an explicit nil

### UnsetProviderCostMicros
`func (o *ToolCallListCallsInner) UnsetProviderCostMicros()`

UnsetProviderCostMicros ensures that no value is present for ProviderCostMicros, not even an explicit nil
### GetReservedMicros

`func (o *ToolCallListCallsInner) GetReservedMicros() int64`

GetReservedMicros returns the ReservedMicros field if non-nil, zero value otherwise.

### GetReservedMicrosOk

`func (o *ToolCallListCallsInner) GetReservedMicrosOk() (*int64, bool)`

GetReservedMicrosOk returns a tuple with the ReservedMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedMicros

`func (o *ToolCallListCallsInner) SetReservedMicros(v int64)`

SetReservedMicros sets ReservedMicros field to given value.


### GetResult

`func (o *ToolCallListCallsInner) GetResult() interface{}`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ToolCallListCallsInner) GetResultOk() (*interface{}, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ToolCallListCallsInner) SetResult(v interface{})`

SetResult sets Result field to given value.


### SetResultNil

`func (o *ToolCallListCallsInner) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *ToolCallListCallsInner) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetStatus

`func (o *ToolCallListCallsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ToolCallListCallsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ToolCallListCallsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetToolId

`func (o *ToolCallListCallsInner) GetToolId() string`

GetToolId returns the ToolId field if non-nil, zero value otherwise.

### GetToolIdOk

`func (o *ToolCallListCallsInner) GetToolIdOk() (*string, bool)`

GetToolIdOk returns a tuple with the ToolId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolId

`func (o *ToolCallListCallsInner) SetToolId(v string)`

SetToolId sets ToolId field to given value.


### GetToolName

`func (o *ToolCallListCallsInner) GetToolName() string`

GetToolName returns the ToolName field if non-nil, zero value otherwise.

### GetToolNameOk

`func (o *ToolCallListCallsInner) GetToolNameOk() (*string, bool)`

GetToolNameOk returns a tuple with the ToolName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolName

`func (o *ToolCallListCallsInner) SetToolName(v string)`

SetToolName sets ToolName field to given value.

### HasToolName

`func (o *ToolCallListCallsInner) HasToolName() bool`

HasToolName returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ToolCallListCallsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ToolCallListCallsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ToolCallListCallsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


