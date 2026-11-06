# ActivitySummaryPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Days** | **float32** |  | 
**From** | **time.Time** |  | 
**To** | **time.Time** |  | 

## Methods

### NewActivitySummaryPeriod

`func NewActivitySummaryPeriod(days float32, from time.Time, to time.Time, ) *ActivitySummaryPeriod`

NewActivitySummaryPeriod instantiates a new ActivitySummaryPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivitySummaryPeriodWithDefaults

`func NewActivitySummaryPeriodWithDefaults() *ActivitySummaryPeriod`

NewActivitySummaryPeriodWithDefaults instantiates a new ActivitySummaryPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDays

`func (o *ActivitySummaryPeriod) GetDays() float32`

GetDays returns the Days field if non-nil, zero value otherwise.

### GetDaysOk

`func (o *ActivitySummaryPeriod) GetDaysOk() (*float32, bool)`

GetDaysOk returns a tuple with the Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDays

`func (o *ActivitySummaryPeriod) SetDays(v float32)`

SetDays sets Days field to given value.


### GetFrom

`func (o *ActivitySummaryPeriod) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *ActivitySummaryPeriod) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *ActivitySummaryPeriod) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *ActivitySummaryPeriod) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *ActivitySummaryPeriod) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *ActivitySummaryPeriod) SetTo(v time.Time)`

SetTo sets To field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


