# GrowthPlaySpend

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | **string** |  | 
**DailyBudgetMicros** | **int64** |  | 
**Last30BilledMicros** | **int64** |  | 
**Last30Calls** | **int32** |  | 
**Last30CostMicros** | **int64** |  | 
**Name** | **string** |  | 
**PlayId** | **string** |  | 
**Status** | **string** |  | 
**TodayBilledMicros** | **int64** |  | 
**TodayCostMicros** | **int64** |  | 

## Methods

### NewGrowthPlaySpend

`func NewGrowthPlaySpend(currency string, dailyBudgetMicros int64, last30BilledMicros int64, last30Calls int32, last30CostMicros int64, name string, playId string, status string, todayBilledMicros int64, todayCostMicros int64, ) *GrowthPlaySpend`

NewGrowthPlaySpend instantiates a new GrowthPlaySpend object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthPlaySpendWithDefaults

`func NewGrowthPlaySpendWithDefaults() *GrowthPlaySpend`

NewGrowthPlaySpendWithDefaults instantiates a new GrowthPlaySpend object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *GrowthPlaySpend) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *GrowthPlaySpend) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *GrowthPlaySpend) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDailyBudgetMicros

`func (o *GrowthPlaySpend) GetDailyBudgetMicros() int64`

GetDailyBudgetMicros returns the DailyBudgetMicros field if non-nil, zero value otherwise.

### GetDailyBudgetMicrosOk

`func (o *GrowthPlaySpend) GetDailyBudgetMicrosOk() (*int64, bool)`

GetDailyBudgetMicrosOk returns a tuple with the DailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyBudgetMicros

`func (o *GrowthPlaySpend) SetDailyBudgetMicros(v int64)`

SetDailyBudgetMicros sets DailyBudgetMicros field to given value.


### GetLast30BilledMicros

`func (o *GrowthPlaySpend) GetLast30BilledMicros() int64`

GetLast30BilledMicros returns the Last30BilledMicros field if non-nil, zero value otherwise.

### GetLast30BilledMicrosOk

`func (o *GrowthPlaySpend) GetLast30BilledMicrosOk() (*int64, bool)`

GetLast30BilledMicrosOk returns a tuple with the Last30BilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast30BilledMicros

`func (o *GrowthPlaySpend) SetLast30BilledMicros(v int64)`

SetLast30BilledMicros sets Last30BilledMicros field to given value.


### GetLast30Calls

`func (o *GrowthPlaySpend) GetLast30Calls() int32`

GetLast30Calls returns the Last30Calls field if non-nil, zero value otherwise.

### GetLast30CallsOk

`func (o *GrowthPlaySpend) GetLast30CallsOk() (*int32, bool)`

GetLast30CallsOk returns a tuple with the Last30Calls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast30Calls

`func (o *GrowthPlaySpend) SetLast30Calls(v int32)`

SetLast30Calls sets Last30Calls field to given value.


### GetLast30CostMicros

`func (o *GrowthPlaySpend) GetLast30CostMicros() int64`

GetLast30CostMicros returns the Last30CostMicros field if non-nil, zero value otherwise.

### GetLast30CostMicrosOk

`func (o *GrowthPlaySpend) GetLast30CostMicrosOk() (*int64, bool)`

GetLast30CostMicrosOk returns a tuple with the Last30CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLast30CostMicros

`func (o *GrowthPlaySpend) SetLast30CostMicros(v int64)`

SetLast30CostMicros sets Last30CostMicros field to given value.


### GetName

`func (o *GrowthPlaySpend) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GrowthPlaySpend) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GrowthPlaySpend) SetName(v string)`

SetName sets Name field to given value.


### GetPlayId

`func (o *GrowthPlaySpend) GetPlayId() string`

GetPlayId returns the PlayId field if non-nil, zero value otherwise.

### GetPlayIdOk

`func (o *GrowthPlaySpend) GetPlayIdOk() (*string, bool)`

GetPlayIdOk returns a tuple with the PlayId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayId

`func (o *GrowthPlaySpend) SetPlayId(v string)`

SetPlayId sets PlayId field to given value.


### GetStatus

`func (o *GrowthPlaySpend) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GrowthPlaySpend) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GrowthPlaySpend) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTodayBilledMicros

`func (o *GrowthPlaySpend) GetTodayBilledMicros() int64`

GetTodayBilledMicros returns the TodayBilledMicros field if non-nil, zero value otherwise.

### GetTodayBilledMicrosOk

`func (o *GrowthPlaySpend) GetTodayBilledMicrosOk() (*int64, bool)`

GetTodayBilledMicrosOk returns a tuple with the TodayBilledMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTodayBilledMicros

`func (o *GrowthPlaySpend) SetTodayBilledMicros(v int64)`

SetTodayBilledMicros sets TodayBilledMicros field to given value.


### GetTodayCostMicros

`func (o *GrowthPlaySpend) GetTodayCostMicros() int64`

GetTodayCostMicros returns the TodayCostMicros field if non-nil, zero value otherwise.

### GetTodayCostMicrosOk

`func (o *GrowthPlaySpend) GetTodayCostMicrosOk() (*int64, bool)`

GetTodayCostMicrosOk returns a tuple with the TodayCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTodayCostMicros

`func (o *GrowthPlaySpend) SetTodayCostMicros(v int64)`

SetTodayCostMicros sets TodayCostMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


