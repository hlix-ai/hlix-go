# CreateDeal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientAccountId** | **string** |  | 
**Currency** | Pointer to **string** |  | [optional] 
**ExpectedCloseOn** | Pointer to **string** |  | [optional] 
**NextStep** | Pointer to **string** |  | [optional] 
**NextStepAt** | Pointer to **time.Time** |  | [optional] 
**OwnerUserId** | Pointer to **string** |  | [optional] 
**SourceKind** | **string** |  | 
**SourcePlayId** | Pointer to **string** |  | [optional] 
**Stage** | Pointer to **string** |  | [optional] 
**ValueMicros** | Pointer to **int64** |  | [optional] 

## Methods

### NewCreateDeal

`func NewCreateDeal(clientAccountId string, sourceKind string, ) *CreateDeal`

NewCreateDeal instantiates a new CreateDeal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDealWithDefaults

`func NewCreateDealWithDefaults() *CreateDeal`

NewCreateDealWithDefaults instantiates a new CreateDeal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientAccountId

`func (o *CreateDeal) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CreateDeal) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CreateDeal) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetCurrency

`func (o *CreateDeal) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateDeal) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateDeal) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateDeal) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetExpectedCloseOn

`func (o *CreateDeal) GetExpectedCloseOn() string`

GetExpectedCloseOn returns the ExpectedCloseOn field if non-nil, zero value otherwise.

### GetExpectedCloseOnOk

`func (o *CreateDeal) GetExpectedCloseOnOk() (*string, bool)`

GetExpectedCloseOnOk returns a tuple with the ExpectedCloseOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedCloseOn

`func (o *CreateDeal) SetExpectedCloseOn(v string)`

SetExpectedCloseOn sets ExpectedCloseOn field to given value.

### HasExpectedCloseOn

`func (o *CreateDeal) HasExpectedCloseOn() bool`

HasExpectedCloseOn returns a boolean if a field has been set.

### GetNextStep

`func (o *CreateDeal) GetNextStep() string`

GetNextStep returns the NextStep field if non-nil, zero value otherwise.

### GetNextStepOk

`func (o *CreateDeal) GetNextStepOk() (*string, bool)`

GetNextStepOk returns a tuple with the NextStep field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextStep

`func (o *CreateDeal) SetNextStep(v string)`

SetNextStep sets NextStep field to given value.

### HasNextStep

`func (o *CreateDeal) HasNextStep() bool`

HasNextStep returns a boolean if a field has been set.

### GetNextStepAt

`func (o *CreateDeal) GetNextStepAt() time.Time`

GetNextStepAt returns the NextStepAt field if non-nil, zero value otherwise.

### GetNextStepAtOk

`func (o *CreateDeal) GetNextStepAtOk() (*time.Time, bool)`

GetNextStepAtOk returns a tuple with the NextStepAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextStepAt

`func (o *CreateDeal) SetNextStepAt(v time.Time)`

SetNextStepAt sets NextStepAt field to given value.

### HasNextStepAt

`func (o *CreateDeal) HasNextStepAt() bool`

HasNextStepAt returns a boolean if a field has been set.

### GetOwnerUserId

`func (o *CreateDeal) GetOwnerUserId() string`

GetOwnerUserId returns the OwnerUserId field if non-nil, zero value otherwise.

### GetOwnerUserIdOk

`func (o *CreateDeal) GetOwnerUserIdOk() (*string, bool)`

GetOwnerUserIdOk returns a tuple with the OwnerUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerUserId

`func (o *CreateDeal) SetOwnerUserId(v string)`

SetOwnerUserId sets OwnerUserId field to given value.

### HasOwnerUserId

`func (o *CreateDeal) HasOwnerUserId() bool`

HasOwnerUserId returns a boolean if a field has been set.

### GetSourceKind

`func (o *CreateDeal) GetSourceKind() string`

GetSourceKind returns the SourceKind field if non-nil, zero value otherwise.

### GetSourceKindOk

`func (o *CreateDeal) GetSourceKindOk() (*string, bool)`

GetSourceKindOk returns a tuple with the SourceKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceKind

`func (o *CreateDeal) SetSourceKind(v string)`

SetSourceKind sets SourceKind field to given value.


### GetSourcePlayId

`func (o *CreateDeal) GetSourcePlayId() string`

GetSourcePlayId returns the SourcePlayId field if non-nil, zero value otherwise.

### GetSourcePlayIdOk

`func (o *CreateDeal) GetSourcePlayIdOk() (*string, bool)`

GetSourcePlayIdOk returns a tuple with the SourcePlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePlayId

`func (o *CreateDeal) SetSourcePlayId(v string)`

SetSourcePlayId sets SourcePlayId field to given value.

### HasSourcePlayId

`func (o *CreateDeal) HasSourcePlayId() bool`

HasSourcePlayId returns a boolean if a field has been set.

### GetStage

`func (o *CreateDeal) GetStage() string`

GetStage returns the Stage field if non-nil, zero value otherwise.

### GetStageOk

`func (o *CreateDeal) GetStageOk() (*string, bool)`

GetStageOk returns a tuple with the Stage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStage

`func (o *CreateDeal) SetStage(v string)`

SetStage sets Stage field to given value.

### HasStage

`func (o *CreateDeal) HasStage() bool`

HasStage returns a boolean if a field has been set.

### GetValueMicros

`func (o *CreateDeal) GetValueMicros() int64`

GetValueMicros returns the ValueMicros field if non-nil, zero value otherwise.

### GetValueMicrosOk

`func (o *CreateDeal) GetValueMicrosOk() (*int64, bool)`

GetValueMicrosOk returns a tuple with the ValueMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueMicros

`func (o *CreateDeal) SetValueMicros(v int64)`

SetValueMicros sets ValueMicros field to given value.

### HasValueMicros

`func (o *CreateDeal) HasValueMicros() bool`

HasValueMicros returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


