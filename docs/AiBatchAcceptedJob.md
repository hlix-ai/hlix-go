# AiBatchAcceptedJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedCount** | **int32** |  | 
**CorrelationId** | **string** |  | 
**CostMicros** | **NullableInt64** |  | 
**CreatedAt** | **string** |  | 
**Endpoint** | **string** |  | 
**Error** | **NullableString** |  | 
**FailedCount** | **int32** |  | 
**FinalizedAt** | **NullableString** |  | 
**Id** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Kind** | **string** |  | 
**Model** | **string** |  | 
**OrganizationId** | **string** |  | 
**ProviderBatchId** | **NullableString** |  | 
**RequestCount** | **int32** |  | 
**SensitiveDataApproved** | **bool** |  | 
**Status** | **string** |  | 
**SubmittedAt** | **NullableString** |  | 
**Usage** | **map[string]interface{}** |  | 

## Methods

### NewAiBatchAcceptedJob

`func NewAiBatchAcceptedJob(completedCount int32, correlationId string, costMicros NullableInt64, createdAt string, endpoint string, error_ NullableString, failedCount int32, finalizedAt NullableString, id string, idempotencyKey string, kind string, model string, organizationId string, providerBatchId NullableString, requestCount int32, sensitiveDataApproved bool, status string, submittedAt NullableString, usage map[string]interface{}, ) *AiBatchAcceptedJob`

NewAiBatchAcceptedJob instantiates a new AiBatchAcceptedJob object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiBatchAcceptedJobWithDefaults

`func NewAiBatchAcceptedJobWithDefaults() *AiBatchAcceptedJob`

NewAiBatchAcceptedJobWithDefaults instantiates a new AiBatchAcceptedJob object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedCount

`func (o *AiBatchAcceptedJob) GetCompletedCount() int32`

GetCompletedCount returns the CompletedCount field if non-nil, zero value otherwise.

### GetCompletedCountOk

`func (o *AiBatchAcceptedJob) GetCompletedCountOk() (*int32, bool)`

GetCompletedCountOk returns a tuple with the CompletedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedCount

`func (o *AiBatchAcceptedJob) SetCompletedCount(v int32)`

SetCompletedCount sets CompletedCount field to given value.


### GetCorrelationId

`func (o *AiBatchAcceptedJob) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AiBatchAcceptedJob) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AiBatchAcceptedJob) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetCostMicros

`func (o *AiBatchAcceptedJob) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AiBatchAcceptedJob) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AiBatchAcceptedJob) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AiBatchAcceptedJob) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AiBatchAcceptedJob) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCreatedAt

`func (o *AiBatchAcceptedJob) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AiBatchAcceptedJob) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AiBatchAcceptedJob) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetEndpoint

`func (o *AiBatchAcceptedJob) GetEndpoint() string`

GetEndpoint returns the Endpoint field if non-nil, zero value otherwise.

### GetEndpointOk

`func (o *AiBatchAcceptedJob) GetEndpointOk() (*string, bool)`

GetEndpointOk returns a tuple with the Endpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpoint

`func (o *AiBatchAcceptedJob) SetEndpoint(v string)`

SetEndpoint sets Endpoint field to given value.


### GetError

`func (o *AiBatchAcceptedJob) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AiBatchAcceptedJob) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AiBatchAcceptedJob) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *AiBatchAcceptedJob) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AiBatchAcceptedJob) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetFailedCount

`func (o *AiBatchAcceptedJob) GetFailedCount() int32`

GetFailedCount returns the FailedCount field if non-nil, zero value otherwise.

### GetFailedCountOk

`func (o *AiBatchAcceptedJob) GetFailedCountOk() (*int32, bool)`

GetFailedCountOk returns a tuple with the FailedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedCount

`func (o *AiBatchAcceptedJob) SetFailedCount(v int32)`

SetFailedCount sets FailedCount field to given value.


### GetFinalizedAt

`func (o *AiBatchAcceptedJob) GetFinalizedAt() string`

GetFinalizedAt returns the FinalizedAt field if non-nil, zero value otherwise.

### GetFinalizedAtOk

`func (o *AiBatchAcceptedJob) GetFinalizedAtOk() (*string, bool)`

GetFinalizedAtOk returns a tuple with the FinalizedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalizedAt

`func (o *AiBatchAcceptedJob) SetFinalizedAt(v string)`

SetFinalizedAt sets FinalizedAt field to given value.


### SetFinalizedAtNil

`func (o *AiBatchAcceptedJob) SetFinalizedAtNil(b bool)`

 SetFinalizedAtNil sets the value for FinalizedAt to be an explicit nil

### UnsetFinalizedAt
`func (o *AiBatchAcceptedJob) UnsetFinalizedAt()`

UnsetFinalizedAt ensures that no value is present for FinalizedAt, not even an explicit nil
### GetId

`func (o *AiBatchAcceptedJob) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiBatchAcceptedJob) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiBatchAcceptedJob) SetId(v string)`

SetId sets Id field to given value.


### GetIdempotencyKey

`func (o *AiBatchAcceptedJob) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *AiBatchAcceptedJob) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *AiBatchAcceptedJob) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetKind

`func (o *AiBatchAcceptedJob) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AiBatchAcceptedJob) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AiBatchAcceptedJob) SetKind(v string)`

SetKind sets Kind field to given value.


### GetModel

`func (o *AiBatchAcceptedJob) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiBatchAcceptedJob) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiBatchAcceptedJob) SetModel(v string)`

SetModel sets Model field to given value.


### GetOrganizationId

`func (o *AiBatchAcceptedJob) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AiBatchAcceptedJob) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AiBatchAcceptedJob) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProviderBatchId

`func (o *AiBatchAcceptedJob) GetProviderBatchId() string`

GetProviderBatchId returns the ProviderBatchId field if non-nil, zero value otherwise.

### GetProviderBatchIdOk

`func (o *AiBatchAcceptedJob) GetProviderBatchIdOk() (*string, bool)`

GetProviderBatchIdOk returns a tuple with the ProviderBatchId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderBatchId

`func (o *AiBatchAcceptedJob) SetProviderBatchId(v string)`

SetProviderBatchId sets ProviderBatchId field to given value.


### SetProviderBatchIdNil

`func (o *AiBatchAcceptedJob) SetProviderBatchIdNil(b bool)`

 SetProviderBatchIdNil sets the value for ProviderBatchId to be an explicit nil

### UnsetProviderBatchId
`func (o *AiBatchAcceptedJob) UnsetProviderBatchId()`

UnsetProviderBatchId ensures that no value is present for ProviderBatchId, not even an explicit nil
### GetRequestCount

`func (o *AiBatchAcceptedJob) GetRequestCount() int32`

GetRequestCount returns the RequestCount field if non-nil, zero value otherwise.

### GetRequestCountOk

`func (o *AiBatchAcceptedJob) GetRequestCountOk() (*int32, bool)`

GetRequestCountOk returns a tuple with the RequestCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCount

`func (o *AiBatchAcceptedJob) SetRequestCount(v int32)`

SetRequestCount sets RequestCount field to given value.


### GetSensitiveDataApproved

`func (o *AiBatchAcceptedJob) GetSensitiveDataApproved() bool`

GetSensitiveDataApproved returns the SensitiveDataApproved field if non-nil, zero value otherwise.

### GetSensitiveDataApprovedOk

`func (o *AiBatchAcceptedJob) GetSensitiveDataApprovedOk() (*bool, bool)`

GetSensitiveDataApprovedOk returns a tuple with the SensitiveDataApproved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSensitiveDataApproved

`func (o *AiBatchAcceptedJob) SetSensitiveDataApproved(v bool)`

SetSensitiveDataApproved sets SensitiveDataApproved field to given value.


### GetStatus

`func (o *AiBatchAcceptedJob) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AiBatchAcceptedJob) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AiBatchAcceptedJob) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSubmittedAt

`func (o *AiBatchAcceptedJob) GetSubmittedAt() string`

GetSubmittedAt returns the SubmittedAt field if non-nil, zero value otherwise.

### GetSubmittedAtOk

`func (o *AiBatchAcceptedJob) GetSubmittedAtOk() (*string, bool)`

GetSubmittedAtOk returns a tuple with the SubmittedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmittedAt

`func (o *AiBatchAcceptedJob) SetSubmittedAt(v string)`

SetSubmittedAt sets SubmittedAt field to given value.


### SetSubmittedAtNil

`func (o *AiBatchAcceptedJob) SetSubmittedAtNil(b bool)`

 SetSubmittedAtNil sets the value for SubmittedAt to be an explicit nil

### UnsetSubmittedAt
`func (o *AiBatchAcceptedJob) UnsetSubmittedAt()`

UnsetSubmittedAt ensures that no value is present for SubmittedAt, not even an explicit nil
### GetUsage

`func (o *AiBatchAcceptedJob) GetUsage() map[string]interface{}`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AiBatchAcceptedJob) GetUsageOk() (*map[string]interface{}, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AiBatchAcceptedJob) SetUsage(v map[string]interface{})`

SetUsage sets Usage field to given value.


### SetUsageNil

`func (o *AiBatchAcceptedJob) SetUsageNil(b bool)`

 SetUsageNil sets the value for Usage to be an explicit nil

### UnsetUsage
`func (o *AiBatchAcceptedJob) UnsetUsage()`

UnsetUsage ensures that no value is present for Usage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


