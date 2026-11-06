# ProjectKnowledgeMemoryAvailabilitySourcesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Current** | **bool** |  | 
**Kind** | **string** |  | 
**LatestMessageAt** | **NullableString** |  | 
**MessageCount** | **NullableFloat32** |  | 
**Observation** | [**NullableProjectKnowledgeMemoryAvailabilitySourcesInnerObservation**](ProjectKnowledgeMemoryAvailabilitySourcesInnerObservation.md) |  | 
**State** | **string** |  | 
**TaskId** | **NullableString** |  | 

## Methods

### NewProjectKnowledgeMemoryAvailabilitySourcesInner

`func NewProjectKnowledgeMemoryAvailabilitySourcesInner(current bool, kind string, latestMessageAt NullableString, messageCount NullableFloat32, observation NullableProjectKnowledgeMemoryAvailabilitySourcesInnerObservation, state string, taskId NullableString, ) *ProjectKnowledgeMemoryAvailabilitySourcesInner`

NewProjectKnowledgeMemoryAvailabilitySourcesInner instantiates a new ProjectKnowledgeMemoryAvailabilitySourcesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectKnowledgeMemoryAvailabilitySourcesInnerWithDefaults

`func NewProjectKnowledgeMemoryAvailabilitySourcesInnerWithDefaults() *ProjectKnowledgeMemoryAvailabilitySourcesInner`

NewProjectKnowledgeMemoryAvailabilitySourcesInnerWithDefaults instantiates a new ProjectKnowledgeMemoryAvailabilitySourcesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrent

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetCurrent() bool`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetCurrentOk() (*bool, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetCurrent(v bool)`

SetCurrent sets Current field to given value.


### GetKind

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetLatestMessageAt

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetLatestMessageAt() string`

GetLatestMessageAt returns the LatestMessageAt field if non-nil, zero value otherwise.

### GetLatestMessageAtOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetLatestMessageAtOk() (*string, bool)`

GetLatestMessageAtOk returns a tuple with the LatestMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestMessageAt

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetLatestMessageAt(v string)`

SetLatestMessageAt sets LatestMessageAt field to given value.


### SetLatestMessageAtNil

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetLatestMessageAtNil(b bool)`

 SetLatestMessageAtNil sets the value for LatestMessageAt to be an explicit nil

### UnsetLatestMessageAt
`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) UnsetLatestMessageAt()`

UnsetLatestMessageAt ensures that no value is present for LatestMessageAt, not even an explicit nil
### GetMessageCount

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetMessageCount() float32`

GetMessageCount returns the MessageCount field if non-nil, zero value otherwise.

### GetMessageCountOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetMessageCountOk() (*float32, bool)`

GetMessageCountOk returns a tuple with the MessageCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageCount

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetMessageCount(v float32)`

SetMessageCount sets MessageCount field to given value.


### SetMessageCountNil

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetMessageCountNil(b bool)`

 SetMessageCountNil sets the value for MessageCount to be an explicit nil

### UnsetMessageCount
`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) UnsetMessageCount()`

UnsetMessageCount ensures that no value is present for MessageCount, not even an explicit nil
### GetObservation

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetObservation() ProjectKnowledgeMemoryAvailabilitySourcesInnerObservation`

GetObservation returns the Observation field if non-nil, zero value otherwise.

### GetObservationOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetObservationOk() (*ProjectKnowledgeMemoryAvailabilitySourcesInnerObservation, bool)`

GetObservationOk returns a tuple with the Observation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservation

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetObservation(v ProjectKnowledgeMemoryAvailabilitySourcesInnerObservation)`

SetObservation sets Observation field to given value.


### SetObservationNil

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetObservationNil(b bool)`

 SetObservationNil sets the value for Observation to be an explicit nil

### UnsetObservation
`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) UnsetObservation()`

UnsetObservation ensures that no value is present for Observation, not even an explicit nil
### GetState

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetState(v string)`

SetState sets State field to given value.


### GetTaskId

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *ProjectKnowledgeMemoryAvailabilitySourcesInner) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


