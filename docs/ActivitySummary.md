# ActivitySummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actors** | [**[]ActivitySummaryActorsInner**](ActivitySummaryActorsInner.md) |  | 
**Daily** | [**[]ActivitySummaryDailyInner**](ActivitySummaryDailyInner.md) |  | 
**EventTypes** | [**[]ActivitySummaryEventTypesInner**](ActivitySummaryEventTypesInner.md) |  | 
**Period** | [**ActivitySummaryPeriod**](ActivitySummaryPeriod.md) |  | 
**Total** | **int32** |  | 

## Methods

### NewActivitySummary

`func NewActivitySummary(actors []ActivitySummaryActorsInner, daily []ActivitySummaryDailyInner, eventTypes []ActivitySummaryEventTypesInner, period ActivitySummaryPeriod, total int32, ) *ActivitySummary`

NewActivitySummary instantiates a new ActivitySummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivitySummaryWithDefaults

`func NewActivitySummaryWithDefaults() *ActivitySummary`

NewActivitySummaryWithDefaults instantiates a new ActivitySummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActors

`func (o *ActivitySummary) GetActors() []ActivitySummaryActorsInner`

GetActors returns the Actors field if non-nil, zero value otherwise.

### GetActorsOk

`func (o *ActivitySummary) GetActorsOk() (*[]ActivitySummaryActorsInner, bool)`

GetActorsOk returns a tuple with the Actors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActors

`func (o *ActivitySummary) SetActors(v []ActivitySummaryActorsInner)`

SetActors sets Actors field to given value.


### GetDaily

`func (o *ActivitySummary) GetDaily() []ActivitySummaryDailyInner`

GetDaily returns the Daily field if non-nil, zero value otherwise.

### GetDailyOk

`func (o *ActivitySummary) GetDailyOk() (*[]ActivitySummaryDailyInner, bool)`

GetDailyOk returns a tuple with the Daily field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaily

`func (o *ActivitySummary) SetDaily(v []ActivitySummaryDailyInner)`

SetDaily sets Daily field to given value.


### GetEventTypes

`func (o *ActivitySummary) GetEventTypes() []ActivitySummaryEventTypesInner`

GetEventTypes returns the EventTypes field if non-nil, zero value otherwise.

### GetEventTypesOk

`func (o *ActivitySummary) GetEventTypesOk() (*[]ActivitySummaryEventTypesInner, bool)`

GetEventTypesOk returns a tuple with the EventTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventTypes

`func (o *ActivitySummary) SetEventTypes(v []ActivitySummaryEventTypesInner)`

SetEventTypes sets EventTypes field to given value.


### GetPeriod

`func (o *ActivitySummary) GetPeriod() ActivitySummaryPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *ActivitySummary) GetPeriodOk() (*ActivitySummaryPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *ActivitySummary) SetPeriod(v ActivitySummaryPeriod)`

SetPeriod sets Period field to given value.


### GetTotal

`func (o *ActivitySummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ActivitySummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ActivitySummary) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


