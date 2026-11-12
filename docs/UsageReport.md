# UsageReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GeneratedAt** | **string** |  |
**Period** | [**AgencyBillingReportPeriod**](AgencyBillingReportPeriod.md) |  |
**Usage** | [**AgencyOverviewReportUsage**](AgencyOverviewReportUsage.md) |  |

## Methods

### NewUsageReport

`func NewUsageReport(generatedAt string, period AgencyBillingReportPeriod, usage AgencyOverviewReportUsage, ) *UsageReport`

NewUsageReport instantiates a new UsageReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewUsageReportWithDefaults

`func NewUsageReportWithDefaults() *UsageReport`

NewUsageReportWithDefaults instantiates a new UsageReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGeneratedAt

`func (o *UsageReport) GetGeneratedAt() string`

GetGeneratedAt returns the GeneratedAt field if non-nil, zero value otherwise.

### GetGeneratedAtOk

`func (o *UsageReport) GetGeneratedAtOk() (*string, bool)`

GetGeneratedAtOk returns a tuple with the GeneratedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedAt

`func (o *UsageReport) SetGeneratedAt(v string)`

SetGeneratedAt sets GeneratedAt field to given value.


### GetPeriod

`func (o *UsageReport) GetPeriod() AgencyBillingReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *UsageReport) GetPeriodOk() (*AgencyBillingReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *UsageReport) SetPeriod(v AgencyBillingReportPeriod)`

SetPeriod sets Period field to given value.


### GetUsage

`func (o *UsageReport) GetUsage() AgencyOverviewReportUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *UsageReport) GetUsageOk() (*AgencyOverviewReportUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *UsageReport) SetUsage(v AgencyOverviewReportUsage)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


