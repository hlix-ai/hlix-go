# CrmActivity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActorId** | **NullableString** |  | 
**ActorType** | **string** |  | 
**ClientAccountId** | **NullableString** |  | 
**ContactId** | **NullableString** |  | 
**CreatedAt** | **string** |  | 
**DealId** | **NullableString** |  | 
**Id** | **string** |  | 
**Kind** | **string** |  | 
**OccurredAt** | **string** |  | 
**OrganizationId** | **string** |  | 
**Ref** | **map[string]interface{}** |  | 
**Summary** | **string** |  | 

## Methods

### NewCrmActivity

`func NewCrmActivity(actorId NullableString, actorType string, clientAccountId NullableString, contactId NullableString, createdAt string, dealId NullableString, id string, kind string, occurredAt string, organizationId string, ref map[string]interface{}, summary string, ) *CrmActivity`

NewCrmActivity instantiates a new CrmActivity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCrmActivityWithDefaults

`func NewCrmActivityWithDefaults() *CrmActivity`

NewCrmActivityWithDefaults instantiates a new CrmActivity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActorId

`func (o *CrmActivity) GetActorId() string`

GetActorId returns the ActorId field if non-nil, zero value otherwise.

### GetActorIdOk

`func (o *CrmActivity) GetActorIdOk() (*string, bool)`

GetActorIdOk returns a tuple with the ActorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorId

`func (o *CrmActivity) SetActorId(v string)`

SetActorId sets ActorId field to given value.


### SetActorIdNil

`func (o *CrmActivity) SetActorIdNil(b bool)`

 SetActorIdNil sets the value for ActorId to be an explicit nil

### UnsetActorId
`func (o *CrmActivity) UnsetActorId()`

UnsetActorId ensures that no value is present for ActorId, not even an explicit nil
### GetActorType

`func (o *CrmActivity) GetActorType() string`

GetActorType returns the ActorType field if non-nil, zero value otherwise.

### GetActorTypeOk

`func (o *CrmActivity) GetActorTypeOk() (*string, bool)`

GetActorTypeOk returns a tuple with the ActorType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorType

`func (o *CrmActivity) SetActorType(v string)`

SetActorType sets ActorType field to given value.


### GetClientAccountId

`func (o *CrmActivity) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *CrmActivity) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *CrmActivity) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *CrmActivity) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *CrmActivity) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetContactId

`func (o *CrmActivity) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *CrmActivity) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *CrmActivity) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### SetContactIdNil

`func (o *CrmActivity) SetContactIdNil(b bool)`

 SetContactIdNil sets the value for ContactId to be an explicit nil

### UnsetContactId
`func (o *CrmActivity) UnsetContactId()`

UnsetContactId ensures that no value is present for ContactId, not even an explicit nil
### GetCreatedAt

`func (o *CrmActivity) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CrmActivity) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CrmActivity) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDealId

`func (o *CrmActivity) GetDealId() string`

GetDealId returns the DealId field if non-nil, zero value otherwise.

### GetDealIdOk

`func (o *CrmActivity) GetDealIdOk() (*string, bool)`

GetDealIdOk returns a tuple with the DealId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDealId

`func (o *CrmActivity) SetDealId(v string)`

SetDealId sets DealId field to given value.


### SetDealIdNil

`func (o *CrmActivity) SetDealIdNil(b bool)`

 SetDealIdNil sets the value for DealId to be an explicit nil

### UnsetDealId
`func (o *CrmActivity) UnsetDealId()`

UnsetDealId ensures that no value is present for DealId, not even an explicit nil
### GetId

`func (o *CrmActivity) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CrmActivity) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CrmActivity) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *CrmActivity) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CrmActivity) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CrmActivity) SetKind(v string)`

SetKind sets Kind field to given value.


### GetOccurredAt

`func (o *CrmActivity) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *CrmActivity) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *CrmActivity) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.


### GetOrganizationId

`func (o *CrmActivity) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CrmActivity) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CrmActivity) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRef

`func (o *CrmActivity) GetRef() map[string]interface{}`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *CrmActivity) GetRefOk() (*map[string]interface{}, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *CrmActivity) SetRef(v map[string]interface{})`

SetRef sets Ref field to given value.


### GetSummary

`func (o *CrmActivity) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *CrmActivity) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *CrmActivity) SetSummary(v string)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


