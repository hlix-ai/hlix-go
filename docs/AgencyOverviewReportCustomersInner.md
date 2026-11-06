# AgencyOverviewReportCustomersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveProjectCount** | **int32** |  | 
**AtRiskProjectCount** | **int32** |  | 
**Billed** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**Id** | **string** |  | 
**LastActivityAt** | **NullableString** |  | 
**Name** | **string** |  | 
**Outstanding** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**Overdue** | [**[]AgencyBillingReportBillingCollectedInner**](AgencyBillingReportBillingCollectedInner.md) |  | 
**PendingClientDecisions** | **int32** |  | 
**ProjectCount** | **int32** |  | 
**Status** | **string** |  | 

## Methods

### NewAgencyOverviewReportCustomersInner

`func NewAgencyOverviewReportCustomersInner(activeProjectCount int32, atRiskProjectCount int32, billed []AgencyBillingReportBillingCollectedInner, id string, lastActivityAt NullableString, name string, outstanding []AgencyBillingReportBillingCollectedInner, overdue []AgencyBillingReportBillingCollectedInner, pendingClientDecisions int32, projectCount int32, status string, ) *AgencyOverviewReportCustomersInner`

NewAgencyOverviewReportCustomersInner instantiates a new AgencyOverviewReportCustomersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgencyOverviewReportCustomersInnerWithDefaults

`func NewAgencyOverviewReportCustomersInnerWithDefaults() *AgencyOverviewReportCustomersInner`

NewAgencyOverviewReportCustomersInnerWithDefaults instantiates a new AgencyOverviewReportCustomersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActiveProjectCount

`func (o *AgencyOverviewReportCustomersInner) GetActiveProjectCount() int32`

GetActiveProjectCount returns the ActiveProjectCount field if non-nil, zero value otherwise.

### GetActiveProjectCountOk

`func (o *AgencyOverviewReportCustomersInner) GetActiveProjectCountOk() (*int32, bool)`

GetActiveProjectCountOk returns a tuple with the ActiveProjectCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveProjectCount

`func (o *AgencyOverviewReportCustomersInner) SetActiveProjectCount(v int32)`

SetActiveProjectCount sets ActiveProjectCount field to given value.


### GetAtRiskProjectCount

`func (o *AgencyOverviewReportCustomersInner) GetAtRiskProjectCount() int32`

GetAtRiskProjectCount returns the AtRiskProjectCount field if non-nil, zero value otherwise.

### GetAtRiskProjectCountOk

`func (o *AgencyOverviewReportCustomersInner) GetAtRiskProjectCountOk() (*int32, bool)`

GetAtRiskProjectCountOk returns a tuple with the AtRiskProjectCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAtRiskProjectCount

`func (o *AgencyOverviewReportCustomersInner) SetAtRiskProjectCount(v int32)`

SetAtRiskProjectCount sets AtRiskProjectCount field to given value.


### GetBilled

`func (o *AgencyOverviewReportCustomersInner) GetBilled() []AgencyBillingReportBillingCollectedInner`

GetBilled returns the Billed field if non-nil, zero value otherwise.

### GetBilledOk

`func (o *AgencyOverviewReportCustomersInner) GetBilledOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetBilledOk returns a tuple with the Billed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilled

`func (o *AgencyOverviewReportCustomersInner) SetBilled(v []AgencyBillingReportBillingCollectedInner)`

SetBilled sets Billed field to given value.


### GetId

`func (o *AgencyOverviewReportCustomersInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgencyOverviewReportCustomersInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgencyOverviewReportCustomersInner) SetId(v string)`

SetId sets Id field to given value.


### GetLastActivityAt

`func (o *AgencyOverviewReportCustomersInner) GetLastActivityAt() string`

GetLastActivityAt returns the LastActivityAt field if non-nil, zero value otherwise.

### GetLastActivityAtOk

`func (o *AgencyOverviewReportCustomersInner) GetLastActivityAtOk() (*string, bool)`

GetLastActivityAtOk returns a tuple with the LastActivityAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActivityAt

`func (o *AgencyOverviewReportCustomersInner) SetLastActivityAt(v string)`

SetLastActivityAt sets LastActivityAt field to given value.


### SetLastActivityAtNil

`func (o *AgencyOverviewReportCustomersInner) SetLastActivityAtNil(b bool)`

 SetLastActivityAtNil sets the value for LastActivityAt to be an explicit nil

### UnsetLastActivityAt
`func (o *AgencyOverviewReportCustomersInner) UnsetLastActivityAt()`

UnsetLastActivityAt ensures that no value is present for LastActivityAt, not even an explicit nil
### GetName

`func (o *AgencyOverviewReportCustomersInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AgencyOverviewReportCustomersInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AgencyOverviewReportCustomersInner) SetName(v string)`

SetName sets Name field to given value.


### GetOutstanding

`func (o *AgencyOverviewReportCustomersInner) GetOutstanding() []AgencyBillingReportBillingCollectedInner`

GetOutstanding returns the Outstanding field if non-nil, zero value otherwise.

### GetOutstandingOk

`func (o *AgencyOverviewReportCustomersInner) GetOutstandingOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetOutstandingOk returns a tuple with the Outstanding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutstanding

`func (o *AgencyOverviewReportCustomersInner) SetOutstanding(v []AgencyBillingReportBillingCollectedInner)`

SetOutstanding sets Outstanding field to given value.


### GetOverdue

`func (o *AgencyOverviewReportCustomersInner) GetOverdue() []AgencyBillingReportBillingCollectedInner`

GetOverdue returns the Overdue field if non-nil, zero value otherwise.

### GetOverdueOk

`func (o *AgencyOverviewReportCustomersInner) GetOverdueOk() (*[]AgencyBillingReportBillingCollectedInner, bool)`

GetOverdueOk returns a tuple with the Overdue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverdue

`func (o *AgencyOverviewReportCustomersInner) SetOverdue(v []AgencyBillingReportBillingCollectedInner)`

SetOverdue sets Overdue field to given value.


### GetPendingClientDecisions

`func (o *AgencyOverviewReportCustomersInner) GetPendingClientDecisions() int32`

GetPendingClientDecisions returns the PendingClientDecisions field if non-nil, zero value otherwise.

### GetPendingClientDecisionsOk

`func (o *AgencyOverviewReportCustomersInner) GetPendingClientDecisionsOk() (*int32, bool)`

GetPendingClientDecisionsOk returns a tuple with the PendingClientDecisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingClientDecisions

`func (o *AgencyOverviewReportCustomersInner) SetPendingClientDecisions(v int32)`

SetPendingClientDecisions sets PendingClientDecisions field to given value.


### GetProjectCount

`func (o *AgencyOverviewReportCustomersInner) GetProjectCount() int32`

GetProjectCount returns the ProjectCount field if non-nil, zero value otherwise.

### GetProjectCountOk

`func (o *AgencyOverviewReportCustomersInner) GetProjectCountOk() (*int32, bool)`

GetProjectCountOk returns a tuple with the ProjectCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectCount

`func (o *AgencyOverviewReportCustomersInner) SetProjectCount(v int32)`

SetProjectCount sets ProjectCount field to given value.


### GetStatus

`func (o *AgencyOverviewReportCustomersInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AgencyOverviewReportCustomersInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AgencyOverviewReportCustomersInner) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


