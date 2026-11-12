# WorkspaceUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ByDay** | [**[]WorkspaceUsageByDayInner**](WorkspaceUsageByDayInner.md) |  |
**ByModel** | [**[]WorkspaceUsageByModelInner**](WorkspaceUsageByModelInner.md) |  |
**ByProject** | [**[]WorkspaceUsageByProjectInner**](WorkspaceUsageByProjectInner.md) |  |
**Entitlement** | [**OrgBillingStateEntitlement**](OrgBillingStateEntitlement.md) |  |
**EnvironmentRuntimeCostMicros** | **NullableInt64** | The price in micros of machine time and environment storage in the window (cost plus markup). In metered billing it is what the workspace is charged and what the meter is sent; in task billing the workspace pays per accepted task, so it is the price equivalent of the usage, not a charge. |
**Runs** | [**[]WorkspaceUsageRunsInner**](WorkspaceUsageRunsInner.md) |  |
**Totals** | [**WorkspaceUsageTotals**](WorkspaceUsageTotals.md) |  |

## Methods

### NewWorkspaceUsage

`func NewWorkspaceUsage(byDay []WorkspaceUsageByDayInner, byModel []WorkspaceUsageByModelInner, byProject []WorkspaceUsageByProjectInner, entitlement OrgBillingStateEntitlement, environmentRuntimeCostMicros NullableInt64, runs []WorkspaceUsageRunsInner, totals WorkspaceUsageTotals, ) *WorkspaceUsage`

NewWorkspaceUsage instantiates a new WorkspaceUsage object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewWorkspaceUsageWithDefaults

`func NewWorkspaceUsageWithDefaults() *WorkspaceUsage`

NewWorkspaceUsageWithDefaults instantiates a new WorkspaceUsage object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetByDay

`func (o *WorkspaceUsage) GetByDay() []WorkspaceUsageByDayInner`

GetByDay returns the ByDay field if non-nil, zero value otherwise.

### GetByDayOk

`func (o *WorkspaceUsage) GetByDayOk() (*[]WorkspaceUsageByDayInner, bool)`

GetByDayOk returns a tuple with the ByDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByDay

`func (o *WorkspaceUsage) SetByDay(v []WorkspaceUsageByDayInner)`

SetByDay sets ByDay field to given value.


### GetByModel

`func (o *WorkspaceUsage) GetByModel() []WorkspaceUsageByModelInner`

GetByModel returns the ByModel field if non-nil, zero value otherwise.

### GetByModelOk

`func (o *WorkspaceUsage) GetByModelOk() (*[]WorkspaceUsageByModelInner, bool)`

GetByModelOk returns a tuple with the ByModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByModel

`func (o *WorkspaceUsage) SetByModel(v []WorkspaceUsageByModelInner)`

SetByModel sets ByModel field to given value.


### GetByProject

`func (o *WorkspaceUsage) GetByProject() []WorkspaceUsageByProjectInner`

GetByProject returns the ByProject field if non-nil, zero value otherwise.

### GetByProjectOk

`func (o *WorkspaceUsage) GetByProjectOk() (*[]WorkspaceUsageByProjectInner, bool)`

GetByProjectOk returns a tuple with the ByProject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByProject

`func (o *WorkspaceUsage) SetByProject(v []WorkspaceUsageByProjectInner)`

SetByProject sets ByProject field to given value.


### GetEntitlement

`func (o *WorkspaceUsage) GetEntitlement() OrgBillingStateEntitlement`

GetEntitlement returns the Entitlement field if non-nil, zero value otherwise.

### GetEntitlementOk

`func (o *WorkspaceUsage) GetEntitlementOk() (*OrgBillingStateEntitlement, bool)`

GetEntitlementOk returns a tuple with the Entitlement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlement

`func (o *WorkspaceUsage) SetEntitlement(v OrgBillingStateEntitlement)`

SetEntitlement sets Entitlement field to given value.


### GetEnvironmentRuntimeCostMicros

`func (o *WorkspaceUsage) GetEnvironmentRuntimeCostMicros() int64`

GetEnvironmentRuntimeCostMicros returns the EnvironmentRuntimeCostMicros field if non-nil, zero value otherwise.

### GetEnvironmentRuntimeCostMicrosOk

`func (o *WorkspaceUsage) GetEnvironmentRuntimeCostMicrosOk() (*int64, bool)`

GetEnvironmentRuntimeCostMicrosOk returns a tuple with the EnvironmentRuntimeCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironmentRuntimeCostMicros

`func (o *WorkspaceUsage) SetEnvironmentRuntimeCostMicros(v int64)`

SetEnvironmentRuntimeCostMicros sets EnvironmentRuntimeCostMicros field to given value.


### SetEnvironmentRuntimeCostMicrosNil

`func (o *WorkspaceUsage) SetEnvironmentRuntimeCostMicrosNil(b bool)`

 SetEnvironmentRuntimeCostMicrosNil sets the value for EnvironmentRuntimeCostMicros to be an explicit nil

### UnsetEnvironmentRuntimeCostMicros
`func (o *WorkspaceUsage) UnsetEnvironmentRuntimeCostMicros()`

UnsetEnvironmentRuntimeCostMicros ensures that no value is present for EnvironmentRuntimeCostMicros, not even an explicit nil
### GetRuns

`func (o *WorkspaceUsage) GetRuns() []WorkspaceUsageRunsInner`

GetRuns returns the Runs field if non-nil, zero value otherwise.

### GetRunsOk

`func (o *WorkspaceUsage) GetRunsOk() (*[]WorkspaceUsageRunsInner, bool)`

GetRunsOk returns a tuple with the Runs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuns

`func (o *WorkspaceUsage) SetRuns(v []WorkspaceUsageRunsInner)`

SetRuns sets Runs field to given value.


### GetTotals

`func (o *WorkspaceUsage) GetTotals() WorkspaceUsageTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *WorkspaceUsage) GetTotalsOk() (*WorkspaceUsageTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *WorkspaceUsage) SetTotals(v WorkspaceUsageTotals)`

SetTotals sets Totals field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


