# CycleMetrics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgingWip** | [**[]CycleMetricsAgingWipInner**](CycleMetricsAgingWipInner.md) |  | 
**AutomationQuality** | [**CycleMetricsAutomationQuality**](CycleMetricsAutomationQuality.md) |  | 
**CycleTimeMs** | [**CycleMetricsCycleTimeMs**](CycleMetricsCycleTimeMs.md) |  | 
**PerCycle** | [**[]CycleMetricsPerCycleInner**](CycleMetricsPerCycleInner.md) |  | 
**PerStageMedians** | [**[]CycleMetricsPerStageMediansInner**](CycleMetricsPerStageMediansInner.md) |  | 
**Throughput** | [**CycleMetricsThroughput**](CycleMetricsThroughput.md) |  | 
**TotalCycles** | **int32** |  | 
**Wip** | [**CycleMetricsWip**](CycleMetricsWip.md) |  | 

## Methods

### NewCycleMetrics

`func NewCycleMetrics(agingWip []CycleMetricsAgingWipInner, automationQuality CycleMetricsAutomationQuality, cycleTimeMs CycleMetricsCycleTimeMs, perCycle []CycleMetricsPerCycleInner, perStageMedians []CycleMetricsPerStageMediansInner, throughput CycleMetricsThroughput, totalCycles int32, wip CycleMetricsWip, ) *CycleMetrics`

NewCycleMetrics instantiates a new CycleMetrics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleMetricsWithDefaults

`func NewCycleMetricsWithDefaults() *CycleMetrics`

NewCycleMetricsWithDefaults instantiates a new CycleMetrics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgingWip

`func (o *CycleMetrics) GetAgingWip() []CycleMetricsAgingWipInner`

GetAgingWip returns the AgingWip field if non-nil, zero value otherwise.

### GetAgingWipOk

`func (o *CycleMetrics) GetAgingWipOk() (*[]CycleMetricsAgingWipInner, bool)`

GetAgingWipOk returns a tuple with the AgingWip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgingWip

`func (o *CycleMetrics) SetAgingWip(v []CycleMetricsAgingWipInner)`

SetAgingWip sets AgingWip field to given value.


### GetAutomationQuality

`func (o *CycleMetrics) GetAutomationQuality() CycleMetricsAutomationQuality`

GetAutomationQuality returns the AutomationQuality field if non-nil, zero value otherwise.

### GetAutomationQualityOk

`func (o *CycleMetrics) GetAutomationQualityOk() (*CycleMetricsAutomationQuality, bool)`

GetAutomationQualityOk returns a tuple with the AutomationQuality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutomationQuality

`func (o *CycleMetrics) SetAutomationQuality(v CycleMetricsAutomationQuality)`

SetAutomationQuality sets AutomationQuality field to given value.


### GetCycleTimeMs

`func (o *CycleMetrics) GetCycleTimeMs() CycleMetricsCycleTimeMs`

GetCycleTimeMs returns the CycleTimeMs field if non-nil, zero value otherwise.

### GetCycleTimeMsOk

`func (o *CycleMetrics) GetCycleTimeMsOk() (*CycleMetricsCycleTimeMs, bool)`

GetCycleTimeMsOk returns a tuple with the CycleTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleTimeMs

`func (o *CycleMetrics) SetCycleTimeMs(v CycleMetricsCycleTimeMs)`

SetCycleTimeMs sets CycleTimeMs field to given value.


### GetPerCycle

`func (o *CycleMetrics) GetPerCycle() []CycleMetricsPerCycleInner`

GetPerCycle returns the PerCycle field if non-nil, zero value otherwise.

### GetPerCycleOk

`func (o *CycleMetrics) GetPerCycleOk() (*[]CycleMetricsPerCycleInner, bool)`

GetPerCycleOk returns a tuple with the PerCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerCycle

`func (o *CycleMetrics) SetPerCycle(v []CycleMetricsPerCycleInner)`

SetPerCycle sets PerCycle field to given value.


### GetPerStageMedians

`func (o *CycleMetrics) GetPerStageMedians() []CycleMetricsPerStageMediansInner`

GetPerStageMedians returns the PerStageMedians field if non-nil, zero value otherwise.

### GetPerStageMediansOk

`func (o *CycleMetrics) GetPerStageMediansOk() (*[]CycleMetricsPerStageMediansInner, bool)`

GetPerStageMediansOk returns a tuple with the PerStageMedians field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerStageMedians

`func (o *CycleMetrics) SetPerStageMedians(v []CycleMetricsPerStageMediansInner)`

SetPerStageMedians sets PerStageMedians field to given value.


### GetThroughput

`func (o *CycleMetrics) GetThroughput() CycleMetricsThroughput`

GetThroughput returns the Throughput field if non-nil, zero value otherwise.

### GetThroughputOk

`func (o *CycleMetrics) GetThroughputOk() (*CycleMetricsThroughput, bool)`

GetThroughputOk returns a tuple with the Throughput field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThroughput

`func (o *CycleMetrics) SetThroughput(v CycleMetricsThroughput)`

SetThroughput sets Throughput field to given value.


### GetTotalCycles

`func (o *CycleMetrics) GetTotalCycles() int32`

GetTotalCycles returns the TotalCycles field if non-nil, zero value otherwise.

### GetTotalCyclesOk

`func (o *CycleMetrics) GetTotalCyclesOk() (*int32, bool)`

GetTotalCyclesOk returns a tuple with the TotalCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCycles

`func (o *CycleMetrics) SetTotalCycles(v int32)`

SetTotalCycles sets TotalCycles field to given value.


### GetWip

`func (o *CycleMetrics) GetWip() CycleMetricsWip`

GetWip returns the Wip field if non-nil, zero value otherwise.

### GetWipOk

`func (o *CycleMetrics) GetWipOk() (*CycleMetricsWip, bool)`

GetWipOk returns a tuple with the Wip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWip

`func (o *CycleMetrics) SetWip(v CycleMetricsWip)`

SetWip sets Wip field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


