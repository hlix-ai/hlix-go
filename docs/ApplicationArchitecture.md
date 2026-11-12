# ApplicationArchitecture

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Coverage** | [**ApplicationArchitectureCoverage**](ApplicationArchitectureCoverage.md) |  |
**Cycle** | [**NullableApplicationArchitectureCycle**](ApplicationArchitectureCycle.md) |  |
**Edges** | [**[]ApplicationArchitectureEdgesInner**](ApplicationArchitectureEdgesInner.md) |  |
**Nodes** | [**[]ApplicationArchitectureNodesInner**](ApplicationArchitectureNodesInner.md) |  |
**ObservedAt** | **string** |  |
**Repositories** | [**[]ApplicationArchitectureRepositoriesInner**](ApplicationArchitectureRepositoriesInner.md) |  |
**Status** | **string** |  |
**Warnings** | **[]string** |  |

## Methods

### NewApplicationArchitecture

`func NewApplicationArchitecture(coverage ApplicationArchitectureCoverage, cycle NullableApplicationArchitectureCycle, edges []ApplicationArchitectureEdgesInner, nodes []ApplicationArchitectureNodesInner, observedAt string, repositories []ApplicationArchitectureRepositoriesInner, status string, warnings []string, ) *ApplicationArchitecture`

NewApplicationArchitecture instantiates a new ApplicationArchitecture object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewApplicationArchitectureWithDefaults

`func NewApplicationArchitectureWithDefaults() *ApplicationArchitecture`

NewApplicationArchitectureWithDefaults instantiates a new ApplicationArchitecture object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCoverage

`func (o *ApplicationArchitecture) GetCoverage() ApplicationArchitectureCoverage`

GetCoverage returns the Coverage field if non-nil, zero value otherwise.

### GetCoverageOk

`func (o *ApplicationArchitecture) GetCoverageOk() (*ApplicationArchitectureCoverage, bool)`

GetCoverageOk returns a tuple with the Coverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoverage

`func (o *ApplicationArchitecture) SetCoverage(v ApplicationArchitectureCoverage)`

SetCoverage sets Coverage field to given value.


### GetCycle

`func (o *ApplicationArchitecture) GetCycle() ApplicationArchitectureCycle`

GetCycle returns the Cycle field if non-nil, zero value otherwise.

### GetCycleOk

`func (o *ApplicationArchitecture) GetCycleOk() (*ApplicationArchitectureCycle, bool)`

GetCycleOk returns a tuple with the Cycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycle

`func (o *ApplicationArchitecture) SetCycle(v ApplicationArchitectureCycle)`

SetCycle sets Cycle field to given value.


### SetCycleNil

`func (o *ApplicationArchitecture) SetCycleNil(b bool)`

 SetCycleNil sets the value for Cycle to be an explicit nil

### UnsetCycle
`func (o *ApplicationArchitecture) UnsetCycle()`

UnsetCycle ensures that no value is present for Cycle, not even an explicit nil
### GetEdges

`func (o *ApplicationArchitecture) GetEdges() []ApplicationArchitectureEdgesInner`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *ApplicationArchitecture) GetEdgesOk() (*[]ApplicationArchitectureEdgesInner, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *ApplicationArchitecture) SetEdges(v []ApplicationArchitectureEdgesInner)`

SetEdges sets Edges field to given value.


### GetNodes

`func (o *ApplicationArchitecture) GetNodes() []ApplicationArchitectureNodesInner`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *ApplicationArchitecture) GetNodesOk() (*[]ApplicationArchitectureNodesInner, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *ApplicationArchitecture) SetNodes(v []ApplicationArchitectureNodesInner)`

SetNodes sets Nodes field to given value.


### GetObservedAt

`func (o *ApplicationArchitecture) GetObservedAt() string`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *ApplicationArchitecture) GetObservedAtOk() (*string, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *ApplicationArchitecture) SetObservedAt(v string)`

SetObservedAt sets ObservedAt field to given value.


### GetRepositories

`func (o *ApplicationArchitecture) GetRepositories() []ApplicationArchitectureRepositoriesInner`

GetRepositories returns the Repositories field if non-nil, zero value otherwise.

### GetRepositoriesOk

`func (o *ApplicationArchitecture) GetRepositoriesOk() (*[]ApplicationArchitectureRepositoriesInner, bool)`

GetRepositoriesOk returns a tuple with the Repositories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepositories

`func (o *ApplicationArchitecture) SetRepositories(v []ApplicationArchitectureRepositoriesInner)`

SetRepositories sets Repositories field to given value.


### GetStatus

`func (o *ApplicationArchitecture) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ApplicationArchitecture) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ApplicationArchitecture) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetWarnings

`func (o *ApplicationArchitecture) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *ApplicationArchitecture) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *ApplicationArchitecture) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


