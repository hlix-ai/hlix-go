# ProjectDiagnostics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CostCapMicros** | **NullableInt64** |  | 
**CostToDateMicros** | **NullableInt64** |  | 
**InFlightCycleIds** | **[]string** |  | 
**Iteration** | **float32** |  | 
**MaxRevisions** | **float32** |  | 
**NextDecision** | **string** |  | 
**Roadmap** | [**[]ProjectDiagnosticsRoadmapInner**](ProjectDiagnosticsRoadmapInner.md) |  | 
**Status** | **string** |  | 

## Methods

### NewProjectDiagnostics

`func NewProjectDiagnostics(costCapMicros NullableInt64, costToDateMicros NullableInt64, inFlightCycleIds []string, iteration float32, maxRevisions float32, nextDecision string, roadmap []ProjectDiagnosticsRoadmapInner, status string, ) *ProjectDiagnostics`

NewProjectDiagnostics instantiates a new ProjectDiagnostics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectDiagnosticsWithDefaults

`func NewProjectDiagnosticsWithDefaults() *ProjectDiagnostics`

NewProjectDiagnosticsWithDefaults instantiates a new ProjectDiagnostics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCostCapMicros

`func (o *ProjectDiagnostics) GetCostCapMicros() int64`

GetCostCapMicros returns the CostCapMicros field if non-nil, zero value otherwise.

### GetCostCapMicrosOk

`func (o *ProjectDiagnostics) GetCostCapMicrosOk() (*int64, bool)`

GetCostCapMicrosOk returns a tuple with the CostCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCapMicros

`func (o *ProjectDiagnostics) SetCostCapMicros(v int64)`

SetCostCapMicros sets CostCapMicros field to given value.


### SetCostCapMicrosNil

`func (o *ProjectDiagnostics) SetCostCapMicrosNil(b bool)`

 SetCostCapMicrosNil sets the value for CostCapMicros to be an explicit nil

### UnsetCostCapMicros
`func (o *ProjectDiagnostics) UnsetCostCapMicros()`

UnsetCostCapMicros ensures that no value is present for CostCapMicros, not even an explicit nil
### GetCostToDateMicros

`func (o *ProjectDiagnostics) GetCostToDateMicros() int64`

GetCostToDateMicros returns the CostToDateMicros field if non-nil, zero value otherwise.

### GetCostToDateMicrosOk

`func (o *ProjectDiagnostics) GetCostToDateMicrosOk() (*int64, bool)`

GetCostToDateMicrosOk returns a tuple with the CostToDateMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostToDateMicros

`func (o *ProjectDiagnostics) SetCostToDateMicros(v int64)`

SetCostToDateMicros sets CostToDateMicros field to given value.


### SetCostToDateMicrosNil

`func (o *ProjectDiagnostics) SetCostToDateMicrosNil(b bool)`

 SetCostToDateMicrosNil sets the value for CostToDateMicros to be an explicit nil

### UnsetCostToDateMicros
`func (o *ProjectDiagnostics) UnsetCostToDateMicros()`

UnsetCostToDateMicros ensures that no value is present for CostToDateMicros, not even an explicit nil
### GetInFlightCycleIds

`func (o *ProjectDiagnostics) GetInFlightCycleIds() []string`

GetInFlightCycleIds returns the InFlightCycleIds field if non-nil, zero value otherwise.

### GetInFlightCycleIdsOk

`func (o *ProjectDiagnostics) GetInFlightCycleIdsOk() (*[]string, bool)`

GetInFlightCycleIdsOk returns a tuple with the InFlightCycleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInFlightCycleIds

`func (o *ProjectDiagnostics) SetInFlightCycleIds(v []string)`

SetInFlightCycleIds sets InFlightCycleIds field to given value.


### GetIteration

`func (o *ProjectDiagnostics) GetIteration() float32`

GetIteration returns the Iteration field if non-nil, zero value otherwise.

### GetIterationOk

`func (o *ProjectDiagnostics) GetIterationOk() (*float32, bool)`

GetIterationOk returns a tuple with the Iteration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIteration

`func (o *ProjectDiagnostics) SetIteration(v float32)`

SetIteration sets Iteration field to given value.


### GetMaxRevisions

`func (o *ProjectDiagnostics) GetMaxRevisions() float32`

GetMaxRevisions returns the MaxRevisions field if non-nil, zero value otherwise.

### GetMaxRevisionsOk

`func (o *ProjectDiagnostics) GetMaxRevisionsOk() (*float32, bool)`

GetMaxRevisionsOk returns a tuple with the MaxRevisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRevisions

`func (o *ProjectDiagnostics) SetMaxRevisions(v float32)`

SetMaxRevisions sets MaxRevisions field to given value.


### GetNextDecision

`func (o *ProjectDiagnostics) GetNextDecision() string`

GetNextDecision returns the NextDecision field if non-nil, zero value otherwise.

### GetNextDecisionOk

`func (o *ProjectDiagnostics) GetNextDecisionOk() (*string, bool)`

GetNextDecisionOk returns a tuple with the NextDecision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextDecision

`func (o *ProjectDiagnostics) SetNextDecision(v string)`

SetNextDecision sets NextDecision field to given value.


### GetRoadmap

`func (o *ProjectDiagnostics) GetRoadmap() []ProjectDiagnosticsRoadmapInner`

GetRoadmap returns the Roadmap field if non-nil, zero value otherwise.

### GetRoadmapOk

`func (o *ProjectDiagnostics) GetRoadmapOk() (*[]ProjectDiagnosticsRoadmapInner, bool)`

GetRoadmapOk returns a tuple with the Roadmap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoadmap

`func (o *ProjectDiagnostics) SetRoadmap(v []ProjectDiagnosticsRoadmapInner)`

SetRoadmap sets Roadmap field to given value.


### GetStatus

`func (o *ProjectDiagnostics) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectDiagnostics) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectDiagnostics) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


