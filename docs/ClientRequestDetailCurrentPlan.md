# ClientRequestDetailCurrentPlan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AttachmentIds** | **[]string** |  | 
**CreatedAt** | **string** |  | 
**Hash** | **string** |  | 
**Plan** | [**ClientRequestDetailCurrentPlanPlan**](ClientRequestDetailCurrentPlanPlan.md) |  | 
**Revision** | **int32** |  | 

## Methods

### NewClientRequestDetailCurrentPlan

`func NewClientRequestDetailCurrentPlan(attachmentIds []string, createdAt string, hash string, plan ClientRequestDetailCurrentPlanPlan, revision int32, ) *ClientRequestDetailCurrentPlan`

NewClientRequestDetailCurrentPlan instantiates a new ClientRequestDetailCurrentPlan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientRequestDetailCurrentPlanWithDefaults

`func NewClientRequestDetailCurrentPlanWithDefaults() *ClientRequestDetailCurrentPlan`

NewClientRequestDetailCurrentPlanWithDefaults instantiates a new ClientRequestDetailCurrentPlan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAttachmentIds

`func (o *ClientRequestDetailCurrentPlan) GetAttachmentIds() []string`

GetAttachmentIds returns the AttachmentIds field if non-nil, zero value otherwise.

### GetAttachmentIdsOk

`func (o *ClientRequestDetailCurrentPlan) GetAttachmentIdsOk() (*[]string, bool)`

GetAttachmentIdsOk returns a tuple with the AttachmentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentIds

`func (o *ClientRequestDetailCurrentPlan) SetAttachmentIds(v []string)`

SetAttachmentIds sets AttachmentIds field to given value.


### GetCreatedAt

`func (o *ClientRequestDetailCurrentPlan) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientRequestDetailCurrentPlan) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientRequestDetailCurrentPlan) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetHash

`func (o *ClientRequestDetailCurrentPlan) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *ClientRequestDetailCurrentPlan) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *ClientRequestDetailCurrentPlan) SetHash(v string)`

SetHash sets Hash field to given value.


### GetPlan

`func (o *ClientRequestDetailCurrentPlan) GetPlan() ClientRequestDetailCurrentPlanPlan`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *ClientRequestDetailCurrentPlan) GetPlanOk() (*ClientRequestDetailCurrentPlanPlan, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *ClientRequestDetailCurrentPlan) SetPlan(v ClientRequestDetailCurrentPlanPlan)`

SetPlan sets Plan field to given value.


### GetRevision

`func (o *ClientRequestDetailCurrentPlan) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *ClientRequestDetailCurrentPlan) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *ClientRequestDetailCurrentPlan) SetRevision(v int32)`

SetRevision sets Revision field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


