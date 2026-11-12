# ProjectTeamInsights

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentRuns** | **int32** |  |
**CloudMachines** | **int32** |  |
**EtaBasis** | **int32** |  |
**EtaHighHours** | **NullableFloat32** |  |
**EtaLowHours** | **NullableFloat32** |  |
**EtaScope** | **NullableString** |  |
**FinishedCycles** | **int32** |  |
**MachineHours** | **float32** |  |
**OpenCycles** | **int32** |  |

## Methods

### NewProjectTeamInsights

`func NewProjectTeamInsights(agentRuns int32, cloudMachines int32, etaBasis int32, etaHighHours NullableFloat32, etaLowHours NullableFloat32, etaScope NullableString, finishedCycles int32, machineHours float32, openCycles int32, ) *ProjectTeamInsights`

NewProjectTeamInsights instantiates a new ProjectTeamInsights object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectTeamInsightsWithDefaults

`func NewProjectTeamInsightsWithDefaults() *ProjectTeamInsights`

NewProjectTeamInsightsWithDefaults instantiates a new ProjectTeamInsights object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAgentRuns

`func (o *ProjectTeamInsights) GetAgentRuns() int32`

GetAgentRuns returns the AgentRuns field if non-nil, zero value otherwise.

### GetAgentRunsOk

`func (o *ProjectTeamInsights) GetAgentRunsOk() (*int32, bool)`

GetAgentRunsOk returns a tuple with the AgentRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentRuns

`func (o *ProjectTeamInsights) SetAgentRuns(v int32)`

SetAgentRuns sets AgentRuns field to given value.


### GetCloudMachines

`func (o *ProjectTeamInsights) GetCloudMachines() int32`

GetCloudMachines returns the CloudMachines field if non-nil, zero value otherwise.

### GetCloudMachinesOk

`func (o *ProjectTeamInsights) GetCloudMachinesOk() (*int32, bool)`

GetCloudMachinesOk returns a tuple with the CloudMachines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCloudMachines

`func (o *ProjectTeamInsights) SetCloudMachines(v int32)`

SetCloudMachines sets CloudMachines field to given value.


### GetEtaBasis

`func (o *ProjectTeamInsights) GetEtaBasis() int32`

GetEtaBasis returns the EtaBasis field if non-nil, zero value otherwise.

### GetEtaBasisOk

`func (o *ProjectTeamInsights) GetEtaBasisOk() (*int32, bool)`

GetEtaBasisOk returns a tuple with the EtaBasis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEtaBasis

`func (o *ProjectTeamInsights) SetEtaBasis(v int32)`

SetEtaBasis sets EtaBasis field to given value.


### GetEtaHighHours

`func (o *ProjectTeamInsights) GetEtaHighHours() float32`

GetEtaHighHours returns the EtaHighHours field if non-nil, zero value otherwise.

### GetEtaHighHoursOk

`func (o *ProjectTeamInsights) GetEtaHighHoursOk() (*float32, bool)`

GetEtaHighHoursOk returns a tuple with the EtaHighHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEtaHighHours

`func (o *ProjectTeamInsights) SetEtaHighHours(v float32)`

SetEtaHighHours sets EtaHighHours field to given value.


### SetEtaHighHoursNil

`func (o *ProjectTeamInsights) SetEtaHighHoursNil(b bool)`

 SetEtaHighHoursNil sets the value for EtaHighHours to be an explicit nil

### UnsetEtaHighHours
`func (o *ProjectTeamInsights) UnsetEtaHighHours()`

UnsetEtaHighHours ensures that no value is present for EtaHighHours, not even an explicit nil
### GetEtaLowHours

`func (o *ProjectTeamInsights) GetEtaLowHours() float32`

GetEtaLowHours returns the EtaLowHours field if non-nil, zero value otherwise.

### GetEtaLowHoursOk

`func (o *ProjectTeamInsights) GetEtaLowHoursOk() (*float32, bool)`

GetEtaLowHoursOk returns a tuple with the EtaLowHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEtaLowHours

`func (o *ProjectTeamInsights) SetEtaLowHours(v float32)`

SetEtaLowHours sets EtaLowHours field to given value.


### SetEtaLowHoursNil

`func (o *ProjectTeamInsights) SetEtaLowHoursNil(b bool)`

 SetEtaLowHoursNil sets the value for EtaLowHours to be an explicit nil

### UnsetEtaLowHours
`func (o *ProjectTeamInsights) UnsetEtaLowHours()`

UnsetEtaLowHours ensures that no value is present for EtaLowHours, not even an explicit nil
### GetEtaScope

`func (o *ProjectTeamInsights) GetEtaScope() string`

GetEtaScope returns the EtaScope field if non-nil, zero value otherwise.

### GetEtaScopeOk

`func (o *ProjectTeamInsights) GetEtaScopeOk() (*string, bool)`

GetEtaScopeOk returns a tuple with the EtaScope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEtaScope

`func (o *ProjectTeamInsights) SetEtaScope(v string)`

SetEtaScope sets EtaScope field to given value.


### SetEtaScopeNil

`func (o *ProjectTeamInsights) SetEtaScopeNil(b bool)`

 SetEtaScopeNil sets the value for EtaScope to be an explicit nil

### UnsetEtaScope
`func (o *ProjectTeamInsights) UnsetEtaScope()`

UnsetEtaScope ensures that no value is present for EtaScope, not even an explicit nil
### GetFinishedCycles

`func (o *ProjectTeamInsights) GetFinishedCycles() int32`

GetFinishedCycles returns the FinishedCycles field if non-nil, zero value otherwise.

### GetFinishedCyclesOk

`func (o *ProjectTeamInsights) GetFinishedCyclesOk() (*int32, bool)`

GetFinishedCyclesOk returns a tuple with the FinishedCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedCycles

`func (o *ProjectTeamInsights) SetFinishedCycles(v int32)`

SetFinishedCycles sets FinishedCycles field to given value.


### GetMachineHours

`func (o *ProjectTeamInsights) GetMachineHours() float32`

GetMachineHours returns the MachineHours field if non-nil, zero value otherwise.

### GetMachineHoursOk

`func (o *ProjectTeamInsights) GetMachineHoursOk() (*float32, bool)`

GetMachineHoursOk returns a tuple with the MachineHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineHours

`func (o *ProjectTeamInsights) SetMachineHours(v float32)`

SetMachineHours sets MachineHours field to given value.


### GetOpenCycles

`func (o *ProjectTeamInsights) GetOpenCycles() int32`

GetOpenCycles returns the OpenCycles field if non-nil, zero value otherwise.

### GetOpenCyclesOk

`func (o *ProjectTeamInsights) GetOpenCyclesOk() (*int32, bool)`

GetOpenCyclesOk returns a tuple with the OpenCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenCycles

`func (o *ProjectTeamInsights) SetOpenCycles(v int32)`

SetOpenCycles sets OpenCycles field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


