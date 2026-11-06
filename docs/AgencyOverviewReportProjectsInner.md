# AgencyOverviewReportProjectsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveWork** | **bool** |  | 
**Agents** | [**AgencyOverviewReportProjectsInnerAgents**](AgencyOverviewReportProjectsInnerAgents.md) |  | 
**Approvals** | [**AgencyOverviewReportProjectsInnerApprovals**](AgencyOverviewReportProjectsInnerApprovals.md) |  | 
**ClientAccountId** | **NullableString** |  | 
**ClientName** | **NullableString** |  | 
**CostCapMicros** | **NullableInt64** |  | 
**Cycles** | [**AgencyOverviewReportProjectsInnerCycles**](AgencyOverviewReportProjectsInnerCycles.md) |  | 
**Deployments** | [**AgencyOverviewReportProjectsInnerDeployments**](AgencyOverviewReportProjectsInnerDeployments.md) |  | 
**Health** | [**AgencyOverviewReportProjectsInnerHealth**](AgencyOverviewReportProjectsInnerHealth.md) |  | 
**Id** | **string** |  | 
**LastActivityAt** | **NullableString** |  | 
**Name** | **string** |  | 
**Tasks** | [**AgencyOverviewReportProjectsInnerTasks**](AgencyOverviewReportProjectsInnerTasks.md) |  | 

## Methods

### NewAgencyOverviewReportProjectsInner

`func NewAgencyOverviewReportProjectsInner(activeWork bool, agents AgencyOverviewReportProjectsInnerAgents, approvals AgencyOverviewReportProjectsInnerApprovals, clientAccountId NullableString, clientName NullableString, costCapMicros NullableInt64, cycles AgencyOverviewReportProjectsInnerCycles, deployments AgencyOverviewReportProjectsInnerDeployments, health AgencyOverviewReportProjectsInnerHealth, id string, lastActivityAt NullableString, name string, tasks AgencyOverviewReportProjectsInnerTasks, ) *AgencyOverviewReportProjectsInner`

NewAgencyOverviewReportProjectsInner instantiates a new AgencyOverviewReportProjectsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgencyOverviewReportProjectsInnerWithDefaults

`func NewAgencyOverviewReportProjectsInnerWithDefaults() *AgencyOverviewReportProjectsInner`

NewAgencyOverviewReportProjectsInnerWithDefaults instantiates a new AgencyOverviewReportProjectsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveWork

`func (o *AgencyOverviewReportProjectsInner) GetActiveWork() bool`

GetActiveWork returns the ActiveWork field if non-nil, zero value otherwise.

### GetActiveWorkOk

`func (o *AgencyOverviewReportProjectsInner) GetActiveWorkOk() (*bool, bool)`

GetActiveWorkOk returns a tuple with the ActiveWork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveWork

`func (o *AgencyOverviewReportProjectsInner) SetActiveWork(v bool)`

SetActiveWork sets ActiveWork field to given value.


### GetAgents

`func (o *AgencyOverviewReportProjectsInner) GetAgents() AgencyOverviewReportProjectsInnerAgents`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *AgencyOverviewReportProjectsInner) GetAgentsOk() (*AgencyOverviewReportProjectsInnerAgents, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *AgencyOverviewReportProjectsInner) SetAgents(v AgencyOverviewReportProjectsInnerAgents)`

SetAgents sets Agents field to given value.


### GetApprovals

`func (o *AgencyOverviewReportProjectsInner) GetApprovals() AgencyOverviewReportProjectsInnerApprovals`

GetApprovals returns the Approvals field if non-nil, zero value otherwise.

### GetApprovalsOk

`func (o *AgencyOverviewReportProjectsInner) GetApprovalsOk() (*AgencyOverviewReportProjectsInnerApprovals, bool)`

GetApprovalsOk returns a tuple with the Approvals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovals

`func (o *AgencyOverviewReportProjectsInner) SetApprovals(v AgencyOverviewReportProjectsInnerApprovals)`

SetApprovals sets Approvals field to given value.


### GetClientAccountId

`func (o *AgencyOverviewReportProjectsInner) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *AgencyOverviewReportProjectsInner) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *AgencyOverviewReportProjectsInner) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *AgencyOverviewReportProjectsInner) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *AgencyOverviewReportProjectsInner) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetClientName

`func (o *AgencyOverviewReportProjectsInner) GetClientName() string`

GetClientName returns the ClientName field if non-nil, zero value otherwise.

### GetClientNameOk

`func (o *AgencyOverviewReportProjectsInner) GetClientNameOk() (*string, bool)`

GetClientNameOk returns a tuple with the ClientName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientName

`func (o *AgencyOverviewReportProjectsInner) SetClientName(v string)`

SetClientName sets ClientName field to given value.


### SetClientNameNil

`func (o *AgencyOverviewReportProjectsInner) SetClientNameNil(b bool)`

 SetClientNameNil sets the value for ClientName to be an explicit nil

### UnsetClientName
`func (o *AgencyOverviewReportProjectsInner) UnsetClientName()`

UnsetClientName ensures that no value is present for ClientName, not even an explicit nil
### GetCostCapMicros

`func (o *AgencyOverviewReportProjectsInner) GetCostCapMicros() int64`

GetCostCapMicros returns the CostCapMicros field if non-nil, zero value otherwise.

### GetCostCapMicrosOk

`func (o *AgencyOverviewReportProjectsInner) GetCostCapMicrosOk() (*int64, bool)`

GetCostCapMicrosOk returns a tuple with the CostCapMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostCapMicros

`func (o *AgencyOverviewReportProjectsInner) SetCostCapMicros(v int64)`

SetCostCapMicros sets CostCapMicros field to given value.


### SetCostCapMicrosNil

`func (o *AgencyOverviewReportProjectsInner) SetCostCapMicrosNil(b bool)`

 SetCostCapMicrosNil sets the value for CostCapMicros to be an explicit nil

### UnsetCostCapMicros
`func (o *AgencyOverviewReportProjectsInner) UnsetCostCapMicros()`

UnsetCostCapMicros ensures that no value is present for CostCapMicros, not even an explicit nil
### GetCycles

`func (o *AgencyOverviewReportProjectsInner) GetCycles() AgencyOverviewReportProjectsInnerCycles`

GetCycles returns the Cycles field if non-nil, zero value otherwise.

### GetCyclesOk

`func (o *AgencyOverviewReportProjectsInner) GetCyclesOk() (*AgencyOverviewReportProjectsInnerCycles, bool)`

GetCyclesOk returns a tuple with the Cycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycles

`func (o *AgencyOverviewReportProjectsInner) SetCycles(v AgencyOverviewReportProjectsInnerCycles)`

SetCycles sets Cycles field to given value.


### GetDeployments

`func (o *AgencyOverviewReportProjectsInner) GetDeployments() AgencyOverviewReportProjectsInnerDeployments`

GetDeployments returns the Deployments field if non-nil, zero value otherwise.

### GetDeploymentsOk

`func (o *AgencyOverviewReportProjectsInner) GetDeploymentsOk() (*AgencyOverviewReportProjectsInnerDeployments, bool)`

GetDeploymentsOk returns a tuple with the Deployments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployments

`func (o *AgencyOverviewReportProjectsInner) SetDeployments(v AgencyOverviewReportProjectsInnerDeployments)`

SetDeployments sets Deployments field to given value.


### GetHealth

`func (o *AgencyOverviewReportProjectsInner) GetHealth() AgencyOverviewReportProjectsInnerHealth`

GetHealth returns the Health field if non-nil, zero value otherwise.

### GetHealthOk

`func (o *AgencyOverviewReportProjectsInner) GetHealthOk() (*AgencyOverviewReportProjectsInnerHealth, bool)`

GetHealthOk returns a tuple with the Health field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealth

`func (o *AgencyOverviewReportProjectsInner) SetHealth(v AgencyOverviewReportProjectsInnerHealth)`

SetHealth sets Health field to given value.


### GetId

`func (o *AgencyOverviewReportProjectsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgencyOverviewReportProjectsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgencyOverviewReportProjectsInner) SetId(v string)`

SetId sets Id field to given value.


### GetLastActivityAt

`func (o *AgencyOverviewReportProjectsInner) GetLastActivityAt() string`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *AgencyOverviewReportProjectsInner) GetLastActivityAtOk() (*string, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *AgencyOverviewReportProjectsInner) SetLastActivityAt(v string)`

SetLastActivityAt sets LastActivityAt field to given value.


### SetLastActivityAtNil

`func (o *AgencyOverviewReportProjectsInner) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *AgencyOverviewReportProjectsInner) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetName

`func (o *AgencyOverviewReportProjectsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AgencyOverviewReportProjectsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AgencyOverviewReportProjectsInner) SetName(v string)`

SetName sets Name field to given value.


### GetTasks

`func (o *AgencyOverviewReportProjectsInner) GetTasks() AgencyOverviewReportProjectsInnerTasks`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *AgencyOverviewReportProjectsInner) GetTasksOk() (*AgencyOverviewReportProjectsInnerTasks, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *AgencyOverviewReportProjectsInner) SetTasks(v AgencyOverviewReportProjectsInnerTasks)`

SetTasks sets Tasks field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


