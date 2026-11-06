# DeliverableViewProgress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Evidence** | [**DeliverableViewProgressEvidence**](DeliverableViewProgressEvidence.md) |  | 
**Percent** | **int32** |  | 

## Methods

### NewDeliverableViewProgress

`func NewDeliverableViewProgress(evidence DeliverableViewProgressEvidence, percent int32, ) *DeliverableViewProgress`

NewDeliverableViewProgress instantiates a new DeliverableViewProgress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeliverableViewProgressWithDefaults

`func NewDeliverableViewProgressWithDefaults() *DeliverableViewProgress`

NewDeliverableViewProgressWithDefaults instantiates a new DeliverableViewProgress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvidence

`func (o *DeliverableViewProgress) GetEvidence() DeliverableViewProgressEvidence`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *DeliverableViewProgress) GetEvidenceOk() (*DeliverableViewProgressEvidence, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *DeliverableViewProgress) SetEvidence(v DeliverableViewProgressEvidence)`

SetEvidence sets Evidence field to given value.


### GetPercent

`func (o *DeliverableViewProgress) GetPercent() int32`

GetPercent returns the Percent field if non-nil, zero value otherwise.

### GetPercentOk

`func (o *DeliverableViewProgress) GetPercentOk() (*int32, bool)`

GetPercentOk returns a tuple with the Percent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPercent

`func (o *DeliverableViewProgress) SetPercent(v int32)`

SetPercent sets Percent field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


