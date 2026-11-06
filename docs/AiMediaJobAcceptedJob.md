# AiMediaJobAcceptedJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedAt** | **NullableString** |  | 
**CorrelationId** | **string** |  | 
**CostMicros** | **NullableInt64** |  | 
**CreatedAt** | **string** |  | 
**Error** | **NullableString** |  | 
**Id** | **string** |  | 
**IdempotencyKey** | **string** |  | 
**Kind** | **string** |  | 
**Model** | **string** |  | 
**OrganizationId** | **string** |  | 
**OutputKey** | **NullableString** |  | 
**Params** | **map[string]interface{}** |  | 
**ProjectId** | **NullableString** |  | 
**PromptHash** | **string** |  | 
**PromptPolicyVersion** | **string** |  | 
**Provider** | **NullableString** |  | 
**ProviderJobId** | **NullableString** |  | 
**ReviewState** | **string** |  | 
**Status** | **string** |  | 
**SubmittedAt** | **NullableString** |  | 

## Methods

### NewAiMediaJobAcceptedJob

`func NewAiMediaJobAcceptedJob(completedAt NullableString, correlationId string, costMicros NullableInt64, createdAt string, error_ NullableString, id string, idempotencyKey string, kind string, model string, organizationId string, outputKey NullableString, params map[string]interface{}, projectId NullableString, promptHash string, promptPolicyVersion string, provider NullableString, providerJobId NullableString, reviewState string, status string, submittedAt NullableString, ) *AiMediaJobAcceptedJob`

NewAiMediaJobAcceptedJob instantiates a new AiMediaJobAcceptedJob object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiMediaJobAcceptedJobWithDefaults

`func NewAiMediaJobAcceptedJobWithDefaults() *AiMediaJobAcceptedJob`

NewAiMediaJobAcceptedJobWithDefaults instantiates a new AiMediaJobAcceptedJob object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedAt

`func (o *AiMediaJobAcceptedJob) GetCompletedAt() string`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AiMediaJobAcceptedJob) GetCompletedAtOk() (*string, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AiMediaJobAcceptedJob) SetCompletedAt(v string)`

SetCompletedAt sets CompletedAt field to given value.


### SetCompletedAtNil

`func (o *AiMediaJobAcceptedJob) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AiMediaJobAcceptedJob) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCorrelationId

`func (o *AiMediaJobAcceptedJob) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AiMediaJobAcceptedJob) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AiMediaJobAcceptedJob) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetCostMicros

`func (o *AiMediaJobAcceptedJob) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AiMediaJobAcceptedJob) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AiMediaJobAcceptedJob) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AiMediaJobAcceptedJob) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AiMediaJobAcceptedJob) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCreatedAt

`func (o *AiMediaJobAcceptedJob) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AiMediaJobAcceptedJob) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AiMediaJobAcceptedJob) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetError

`func (o *AiMediaJobAcceptedJob) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AiMediaJobAcceptedJob) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AiMediaJobAcceptedJob) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *AiMediaJobAcceptedJob) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AiMediaJobAcceptedJob) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetId

`func (o *AiMediaJobAcceptedJob) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiMediaJobAcceptedJob) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiMediaJobAcceptedJob) SetId(v string)`

SetId sets Id field to given value.


### GetIdempotencyKey

`func (o *AiMediaJobAcceptedJob) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *AiMediaJobAcceptedJob) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *AiMediaJobAcceptedJob) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetKind

`func (o *AiMediaJobAcceptedJob) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AiMediaJobAcceptedJob) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AiMediaJobAcceptedJob) SetKind(v string)`

SetKind sets Kind field to given value.


### GetModel

`func (o *AiMediaJobAcceptedJob) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiMediaJobAcceptedJob) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiMediaJobAcceptedJob) SetModel(v string)`

SetModel sets Model field to given value.


### GetOrganizationId

`func (o *AiMediaJobAcceptedJob) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AiMediaJobAcceptedJob) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AiMediaJobAcceptedJob) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetOutputKey

`func (o *AiMediaJobAcceptedJob) GetOutputKey() string`

GetOutputKey returns the OutputKey field if non-nil, zero value otherwise.

### GetOutputKeyOk

`func (o *AiMediaJobAcceptedJob) GetOutputKeyOk() (*string, bool)`

GetOutputKeyOk returns a tuple with the OutputKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputKey

`func (o *AiMediaJobAcceptedJob) SetOutputKey(v string)`

SetOutputKey sets OutputKey field to given value.


### SetOutputKeyNil

`func (o *AiMediaJobAcceptedJob) SetOutputKeyNil(b bool)`

 SetOutputKeyNil sets the value for OutputKey to be an explicit nil

### UnsetOutputKey
`func (o *AiMediaJobAcceptedJob) UnsetOutputKey()`

UnsetOutputKey ensures that no value is present for OutputKey, not even an explicit nil
### GetParams

`func (o *AiMediaJobAcceptedJob) GetParams() map[string]interface{}`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *AiMediaJobAcceptedJob) GetParamsOk() (*map[string]interface{}, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *AiMediaJobAcceptedJob) SetParams(v map[string]interface{})`

SetParams sets Params field to given value.


### GetProjectId

`func (o *AiMediaJobAcceptedJob) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiMediaJobAcceptedJob) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiMediaJobAcceptedJob) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *AiMediaJobAcceptedJob) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *AiMediaJobAcceptedJob) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetPromptHash

`func (o *AiMediaJobAcceptedJob) GetPromptHash() string`

GetPromptHash returns the PromptHash field if non-nil, zero value otherwise.

### GetPromptHashOk

`func (o *AiMediaJobAcceptedJob) GetPromptHashOk() (*string, bool)`

GetPromptHashOk returns a tuple with the PromptHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptHash

`func (o *AiMediaJobAcceptedJob) SetPromptHash(v string)`

SetPromptHash sets PromptHash field to given value.


### GetPromptPolicyVersion

`func (o *AiMediaJobAcceptedJob) GetPromptPolicyVersion() string`

GetPromptPolicyVersion returns the PromptPolicyVersion field if non-nil, zero value otherwise.

### GetPromptPolicyVersionOk

`func (o *AiMediaJobAcceptedJob) GetPromptPolicyVersionOk() (*string, bool)`

GetPromptPolicyVersionOk returns a tuple with the PromptPolicyVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptPolicyVersion

`func (o *AiMediaJobAcceptedJob) SetPromptPolicyVersion(v string)`

SetPromptPolicyVersion sets PromptPolicyVersion field to given value.


### GetProvider

`func (o *AiMediaJobAcceptedJob) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AiMediaJobAcceptedJob) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AiMediaJobAcceptedJob) SetProvider(v string)`

SetProvider sets Provider field to given value.


### SetProviderNil

`func (o *AiMediaJobAcceptedJob) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *AiMediaJobAcceptedJob) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetProviderJobId

`func (o *AiMediaJobAcceptedJob) GetProviderJobId() string`

GetProviderJobId returns the ProviderJobId field if non-nil, zero value otherwise.

### GetProviderJobIdOk

`func (o *AiMediaJobAcceptedJob) GetProviderJobIdOk() (*string, bool)`

GetProviderJobIdOk returns a tuple with the ProviderJobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderJobId

`func (o *AiMediaJobAcceptedJob) SetProviderJobId(v string)`

SetProviderJobId sets ProviderJobId field to given value.


### SetProviderJobIdNil

`func (o *AiMediaJobAcceptedJob) SetProviderJobIdNil(b bool)`

 SetProviderJobIdNil sets the value for ProviderJobId to be an explicit nil

### UnsetProviderJobId
`func (o *AiMediaJobAcceptedJob) UnsetProviderJobId()`

UnsetProviderJobId ensures that no value is present for ProviderJobId, not even an explicit nil
### GetReviewState

`func (o *AiMediaJobAcceptedJob) GetReviewState() string`

GetReviewState returns the ReviewState field if non-nil, zero value otherwise.

### GetReviewStateOk

`func (o *AiMediaJobAcceptedJob) GetReviewStateOk() (*string, bool)`

GetReviewStateOk returns a tuple with the ReviewState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewState

`func (o *AiMediaJobAcceptedJob) SetReviewState(v string)`

SetReviewState sets ReviewState field to given value.


### GetStatus

`func (o *AiMediaJobAcceptedJob) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AiMediaJobAcceptedJob) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AiMediaJobAcceptedJob) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSubmittedAt

`func (o *AiMediaJobAcceptedJob) GetSubmittedAt() string`

GetSubmittedAt returns the SubmittedAt field if non-nil, zero value otherwise.

### GetSubmittedAtOk

`func (o *AiMediaJobAcceptedJob) GetSubmittedAtOk() (*string, bool)`

GetSubmittedAtOk returns a tuple with the SubmittedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmittedAt

`func (o *AiMediaJobAcceptedJob) SetSubmittedAt(v string)`

SetSubmittedAt sets SubmittedAt field to given value.


### SetSubmittedAtNil

`func (o *AiMediaJobAcceptedJob) SetSubmittedAtNil(b bool)`

 SetSubmittedAtNil sets the value for SubmittedAt to be an explicit nil

### UnsetSubmittedAt
`func (o *AiMediaJobAcceptedJob) UnsetSubmittedAt()`

UnsetSubmittedAt ensures that no value is present for SubmittedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


