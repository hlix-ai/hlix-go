# CrmPipeline

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientAccountId** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**Id** | **string** |  | 
**Name** | **string** |  | 
**OrganizationId** | **string** |  | 
**StageProbabilities** | **map[string]int32** |  | 
**Stages** | **[]string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewCrmPipeline

`func NewCrmPipeline(clientAccountId NullableString, createdAt string, id string, name string, organizationId string, stageProbabilities map[string]int32, stages []string, updatedAt string, ) *CrmPipeline`

NewCrmPipeline instantiates a new CrmPipeline object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCrmPipelineWithDefaults

`func NewCrmPipelineWithDefaults() *CrmPipeline`

NewCrmPipelineWithDefaults instantiates a new CrmPipeline object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientAccountId

`func (o *CrmPipeline) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CrmPipeline) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CrmPipeline) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *CrmPipeline) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *CrmPipeline) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetCreatedAt

`func (o *CrmPipeline) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CrmPipeline) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CrmPipeline) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *CrmPipeline) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CrmPipeline) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CrmPipeline) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *CrmPipeline) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CrmPipeline) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CrmPipeline) SetName(v string)`

SetName sets Name field to given value.


### GetOrganizationId

`func (o *CrmPipeline) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CrmPipeline) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CrmPipeline) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetStageProbabilities

`func (o *CrmPipeline) GetStageProbabilities() map[string]int32`

GetStageProbabilities returns the StageProbabilities field if non-nil, zero value otherwise.

### GetStageProbabilitiesOk

`func (o *CrmPipeline) GetStageProbabilitiesOk() (*map[string]int32, bool)`

GetStageProbabilitiesOk returns a tuple with the StageProbabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStageProbabilities

`func (o *CrmPipeline) SetStageProbabilities(v map[string]int32)`

SetStageProbabilities sets StageProbabilities field to given value.


### GetStages

`func (o *CrmPipeline) GetStages() []string`

GetStages returns the Stages field if non-nil, zero value otherwise.

### GetStagesOk

`func (o *CrmPipeline) GetStagesOk() (*[]string, bool)`

GetStagesOk returns a tuple with the Stages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStages

`func (o *CrmPipeline) SetStages(v []string)`

SetStages sets Stages field to given value.


### GetUpdatedAt

`func (o *CrmPipeline) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CrmPipeline) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CrmPipeline) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


