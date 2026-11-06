# ProjectRoadmap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompletedCount** | **int32** |  | 
**CostToDateMicros** | **NullableInt64** |  | 
**Cycles** | [**[]ProjectRoadmapCyclesInner**](ProjectRoadmapCyclesInner.md) |  | 
**Proposals** | [**[]ProjectRoadmapProposalsInner**](ProjectRoadmapProposalsInner.md) |  | 
**TotalCount** | **int32** |  | 

## Methods

### NewProjectRoadmap

`func NewProjectRoadmap(completedCount int32, costToDateMicros NullableInt64, cycles []ProjectRoadmapCyclesInner, proposals []ProjectRoadmapProposalsInner, totalCount int32, ) *ProjectRoadmap`

NewProjectRoadmap instantiates a new ProjectRoadmap object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectRoadmapWithDefaults

`func NewProjectRoadmapWithDefaults() *ProjectRoadmap`

NewProjectRoadmapWithDefaults instantiates a new ProjectRoadmap object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompletedCount

`func (o *ProjectRoadmap) GetCompletedCount() int32`

GetCompletedCount returns the CompletedCount field if non-nil, zero value otherwise.

### GetCompletedCountOk

`func (o *ProjectRoadmap) GetCompletedCountOk() (*int32, bool)`

GetCompletedCountOk returns a tuple with the CompletedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedCount

`func (o *ProjectRoadmap) SetCompletedCount(v int32)`

SetCompletedCount sets CompletedCount field to given value.


### GetCostToDateMicros

`func (o *ProjectRoadmap) GetCostToDateMicros() int64`

GetCostToDateMicros returns the CostToDateMicros field if non-nil, zero value otherwise.

### GetCostToDateMicrosOk

`func (o *ProjectRoadmap) GetCostToDateMicrosOk() (*int64, bool)`

GetCostToDateMicrosOk returns a tuple with the CostToDateMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostToDateMicros

`func (o *ProjectRoadmap) SetCostToDateMicros(v int64)`

SetCostToDateMicros sets CostToDateMicros field to given value.


### SetCostToDateMicrosNil

`func (o *ProjectRoadmap) SetCostToDateMicrosNil(b bool)`

 SetCostToDateMicrosNil sets the value for CostToDateMicros to be an explicit nil

### UnsetCostToDateMicros
`func (o *ProjectRoadmap) UnsetCostToDateMicros()`

UnsetCostToDateMicros ensures that no value is present for CostToDateMicros, not even an explicit nil
### GetCycles

`func (o *ProjectRoadmap) GetCycles() []ProjectRoadmapCyclesInner`

GetCycles returns the Cycles field if non-nil, zero value otherwise.

### GetCyclesOk

`func (o *ProjectRoadmap) GetCyclesOk() (*[]ProjectRoadmapCyclesInner, bool)`

GetCyclesOk returns a tuple with the Cycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycles

`func (o *ProjectRoadmap) SetCycles(v []ProjectRoadmapCyclesInner)`

SetCycles sets Cycles field to given value.


### GetProposals

`func (o *ProjectRoadmap) GetProposals() []ProjectRoadmapProposalsInner`

GetProposals returns the Proposals field if non-nil, zero value otherwise.

### GetProposalsOk

`func (o *ProjectRoadmap) GetProposalsOk() (*[]ProjectRoadmapProposalsInner, bool)`

GetProposalsOk returns a tuple with the Proposals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposals

`func (o *ProjectRoadmap) SetProposals(v []ProjectRoadmapProposalsInner)`

SetProposals sets Proposals field to given value.


### GetTotalCount

`func (o *ProjectRoadmap) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *ProjectRoadmap) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *ProjectRoadmap) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


