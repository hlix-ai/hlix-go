# ProjectRoadmapCyclesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Agents** | Pointer to [**[]ProjectRoadmapCyclesInnerAgentsInner**](ProjectRoadmapCyclesInnerAgentsInner.md) |  | [optional] 
**CostMicros** | **NullableInt64** |  | 
**CycleId** | **NullableString** |  | 
**DisplayId** | Pointer to **string** |  | [optional] 
**ElapsedMs** | Pointer to **NullableFloat32** |  | [optional] 
**Lane** | **NullableString** |  | 
**LinearIssueIdentifier** | **NullableString** |  | 
**LinearIssueUrl** | **NullableString** |  | 
**Order** | **int32** |  | 
**Owner** | Pointer to [**NullableProjectRoadmapCyclesInnerOwner**](ProjectRoadmapCyclesInnerOwner.md) |  | [optional] 
**Quick** | **bool** |  | 
**RequestedByUserId** | **NullableString** |  | 
**Setup** | **bool** |  | 
**Source** | **NullableString** |  | 
**Status** | **string** |  | 
**TaskDone** | **int32** |  | 
**TaskTotal** | **int32** |  | 
**Title** | **string** |  | 

## Methods

### NewProjectRoadmapCyclesInner

`func NewProjectRoadmapCyclesInner(costMicros NullableInt64, cycleId NullableString, lane NullableString, linearIssueIdentifier NullableString, linearIssueUrl NullableString, order int32, quick bool, requestedByUserId NullableString, setup bool, source NullableString, status string, taskDone int32, taskTotal int32, title string, ) *ProjectRoadmapCyclesInner`

NewProjectRoadmapCyclesInner instantiates a new ProjectRoadmapCyclesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectRoadmapCyclesInnerWithDefaults

`func NewProjectRoadmapCyclesInnerWithDefaults() *ProjectRoadmapCyclesInner`

NewProjectRoadmapCyclesInnerWithDefaults instantiates a new ProjectRoadmapCyclesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgents

`func (o *ProjectRoadmapCyclesInner) GetAgents() []ProjectRoadmapCyclesInnerAgentsInner`

GetAgents returns the Agents field if non-nil, zero value otherwise.

### GetAgentsOk

`func (o *ProjectRoadmapCyclesInner) GetAgentsOk() (*[]ProjectRoadmapCyclesInnerAgentsInner, bool)`

GetAgentsOk returns a tuple with the Agents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgents

`func (o *ProjectRoadmapCyclesInner) SetAgents(v []ProjectRoadmapCyclesInnerAgentsInner)`

SetAgents sets Agents field to given value.

### HasAgents

`func (o *ProjectRoadmapCyclesInner) HasAgents() bool`

HasAgents returns a boolean if a field has been set.

### GetCostMicros

`func (o *ProjectRoadmapCyclesInner) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *ProjectRoadmapCyclesInner) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *ProjectRoadmapCyclesInner) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *ProjectRoadmapCyclesInner) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *ProjectRoadmapCyclesInner) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCycleId

`func (o *ProjectRoadmapCyclesInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ProjectRoadmapCyclesInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ProjectRoadmapCyclesInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ProjectRoadmapCyclesInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ProjectRoadmapCyclesInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDisplayId

`func (o *ProjectRoadmapCyclesInner) GetDisplayId() string`

GetDisplayId returns the DisplayId field if non-nil, zero value otherwise.

### GetDisplayIdOk

`func (o *ProjectRoadmapCyclesInner) GetDisplayIdOk() (*string, bool)`

GetDisplayIdOk returns a tuple with the DisplayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayId

`func (o *ProjectRoadmapCyclesInner) SetDisplayId(v string)`

SetDisplayId sets DisplayId field to given value.

### HasDisplayId

`func (o *ProjectRoadmapCyclesInner) HasDisplayId() bool`

HasDisplayId returns a boolean if a field has been set.

### GetElapsedMs

`func (o *ProjectRoadmapCyclesInner) GetElapsedMs() float32`

GetElapsedMs returns the ElapsedMs field if non-nil, zero value otherwise.

### GetElapsedMsOk

`func (o *ProjectRoadmapCyclesInner) GetElapsedMsOk() (*float32, bool)`

GetElapsedMsOk returns a tuple with the ElapsedMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElapsedMs

`func (o *ProjectRoadmapCyclesInner) SetElapsedMs(v float32)`

SetElapsedMs sets ElapsedMs field to given value.

### HasElapsedMs

`func (o *ProjectRoadmapCyclesInner) HasElapsedMs() bool`

HasElapsedMs returns a boolean if a field has been set.

### SetElapsedMsNil

`func (o *ProjectRoadmapCyclesInner) SetElapsedMsNil(b bool)`

 SetElapsedMsNil sets the value for ElapsedMs to be an explicit nil

### UnsetElapsedMs
`func (o *ProjectRoadmapCyclesInner) UnsetElapsedMs()`

UnsetElapsedMs ensures that no value is present for ElapsedMs, not even an explicit nil
### GetLane

`func (o *ProjectRoadmapCyclesInner) GetLane() string`

GetLane returns the Lane field if non-nil, zero value otherwise.

### GetLaneOk

`func (o *ProjectRoadmapCyclesInner) GetLaneOk() (*string, bool)`

GetLaneOk returns a tuple with the Lane field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLane

`func (o *ProjectRoadmapCyclesInner) SetLane(v string)`

SetLane sets Lane field to given value.


### SetLaneNil

`func (o *ProjectRoadmapCyclesInner) SetLaneNil(b bool)`

 SetLaneNil sets the value for Lane to be an explicit nil

### UnsetLane
`func (o *ProjectRoadmapCyclesInner) UnsetLane()`

UnsetLane ensures that no value is present for Lane, not even an explicit nil
### GetLinearIssueIdentifier

`func (o *ProjectRoadmapCyclesInner) GetLinearIssueIdentifier() string`

GetLinearIssueIdentifier returns the LinearIssueIdentifier field if non-nil, zero value otherwise.

### GetLinearIssueIdentifierOk

`func (o *ProjectRoadmapCyclesInner) GetLinearIssueIdentifierOk() (*string, bool)`

GetLinearIssueIdentifierOk returns a tuple with the LinearIssueIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueIdentifier

`func (o *ProjectRoadmapCyclesInner) SetLinearIssueIdentifier(v string)`

SetLinearIssueIdentifier sets LinearIssueIdentifier field to given value.


### SetLinearIssueIdentifierNil

`func (o *ProjectRoadmapCyclesInner) SetLinearIssueIdentifierNil(b bool)`

 SetLinearIssueIdentifierNil sets the value for LinearIssueIdentifier to be an explicit nil

### UnsetLinearIssueIdentifier
`func (o *ProjectRoadmapCyclesInner) UnsetLinearIssueIdentifier()`

UnsetLinearIssueIdentifier ensures that no value is present for LinearIssueIdentifier, not even an explicit nil
### GetLinearIssueUrl

`func (o *ProjectRoadmapCyclesInner) GetLinearIssueUrl() string`

GetLinearIssueUrl returns the LinearIssueUrl field if non-nil, zero value otherwise.

### GetLinearIssueUrlOk

`func (o *ProjectRoadmapCyclesInner) GetLinearIssueUrlOk() (*string, bool)`

GetLinearIssueUrlOk returns a tuple with the LinearIssueUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinearIssueUrl

`func (o *ProjectRoadmapCyclesInner) SetLinearIssueUrl(v string)`

SetLinearIssueUrl sets LinearIssueUrl field to given value.


### SetLinearIssueUrlNil

`func (o *ProjectRoadmapCyclesInner) SetLinearIssueUrlNil(b bool)`

 SetLinearIssueUrlNil sets the value for LinearIssueUrl to be an explicit nil

### UnsetLinearIssueUrl
`func (o *ProjectRoadmapCyclesInner) UnsetLinearIssueUrl()`

UnsetLinearIssueUrl ensures that no value is present for LinearIssueUrl, not even an explicit nil
### GetOrder

`func (o *ProjectRoadmapCyclesInner) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ProjectRoadmapCyclesInner) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ProjectRoadmapCyclesInner) SetOrder(v int32)`

SetOrder sets Order field to given value.


### GetOwner

`func (o *ProjectRoadmapCyclesInner) GetOwner() ProjectRoadmapCyclesInnerOwner`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *ProjectRoadmapCyclesInner) GetOwnerOk() (*ProjectRoadmapCyclesInnerOwner, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *ProjectRoadmapCyclesInner) SetOwner(v ProjectRoadmapCyclesInnerOwner)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *ProjectRoadmapCyclesInner) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### SetOwnerNil

`func (o *ProjectRoadmapCyclesInner) SetOwnerNil(b bool)`

 SetOwnerNil sets the value for Owner to be an explicit nil

### UnsetOwner
`func (o *ProjectRoadmapCyclesInner) UnsetOwner()`

UnsetOwner ensures that no value is present for Owner, not even an explicit nil
### GetQuick

`func (o *ProjectRoadmapCyclesInner) GetQuick() bool`

GetQuick returns the Quick field if non-nil, zero value otherwise.

### GetQuickOk

`func (o *ProjectRoadmapCyclesInner) GetQuickOk() (*bool, bool)`

GetQuickOk returns a tuple with the Quick field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuick

`func (o *ProjectRoadmapCyclesInner) SetQuick(v bool)`

SetQuick sets Quick field to given value.


### GetRequestedByUserId

`func (o *ProjectRoadmapCyclesInner) GetRequestedByUserId() string`

GetRequestedByUserId returns the RequestedByUserId field if non-nil, zero value otherwise.

### GetRequestedByUserIdOk

`func (o *ProjectRoadmapCyclesInner) GetRequestedByUserIdOk() (*string, bool)`

GetRequestedByUserIdOk returns a tuple with the RequestedByUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedByUserId

`func (o *ProjectRoadmapCyclesInner) SetRequestedByUserId(v string)`

SetRequestedByUserId sets RequestedByUserId field to given value.


### SetRequestedByUserIdNil

`func (o *ProjectRoadmapCyclesInner) SetRequestedByUserIdNil(b bool)`

 SetRequestedByUserIdNil sets the value for RequestedByUserId to be an explicit nil

### UnsetRequestedByUserId
`func (o *ProjectRoadmapCyclesInner) UnsetRequestedByUserId()`

UnsetRequestedByUserId ensures that no value is present for RequestedByUserId, not even an explicit nil
### GetSetup

`func (o *ProjectRoadmapCyclesInner) GetSetup() bool`

GetSetup returns the Setup field if non-nil, zero value otherwise.

### GetSetupOk

`func (o *ProjectRoadmapCyclesInner) GetSetupOk() (*bool, bool)`

GetSetupOk returns a tuple with the Setup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetup

`func (o *ProjectRoadmapCyclesInner) SetSetup(v bool)`

SetSetup sets Setup field to given value.


### GetSource

`func (o *ProjectRoadmapCyclesInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ProjectRoadmapCyclesInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ProjectRoadmapCyclesInner) SetSource(v string)`

SetSource sets Source field to given value.


### SetSourceNil

`func (o *ProjectRoadmapCyclesInner) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *ProjectRoadmapCyclesInner) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetStatus

`func (o *ProjectRoadmapCyclesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectRoadmapCyclesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectRoadmapCyclesInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskDone

`func (o *ProjectRoadmapCyclesInner) GetTaskDone() int32`

GetTaskDone returns the TaskDone field if non-nil, zero value otherwise.

### GetTaskDoneOk

`func (o *ProjectRoadmapCyclesInner) GetTaskDoneOk() (*int32, bool)`

GetTaskDoneOk returns a tuple with the TaskDone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskDone

`func (o *ProjectRoadmapCyclesInner) SetTaskDone(v int32)`

SetTaskDone sets TaskDone field to given value.


### GetTaskTotal

`func (o *ProjectRoadmapCyclesInner) GetTaskTotal() int32`

GetTaskTotal returns the TaskTotal field if non-nil, zero value otherwise.

### GetTaskTotalOk

`func (o *ProjectRoadmapCyclesInner) GetTaskTotalOk() (*int32, bool)`

GetTaskTotalOk returns a tuple with the TaskTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskTotal

`func (o *ProjectRoadmapCyclesInner) SetTaskTotal(v int32)`

SetTaskTotal sets TaskTotal field to given value.


### GetTitle

`func (o *ProjectRoadmapCyclesInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ProjectRoadmapCyclesInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ProjectRoadmapCyclesInner) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


