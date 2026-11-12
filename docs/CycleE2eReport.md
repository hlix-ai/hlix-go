# CycleE2eReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FinishedAt** | Pointer to **string** |  | [optional]
**Journeys** | [**[]CycleE2eReportJourneysInner**](CycleE2eReportJourneysInner.md) |  |
**PreviewUrl** | Pointer to **string** |  | [optional]
**Status** | **string** |  |

## Methods

### NewCycleE2eReport

`func NewCycleE2eReport(journeys []CycleE2eReportJourneysInner, status string, ) *CycleE2eReport`

NewCycleE2eReport instantiates a new CycleE2eReport object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCycleE2eReportWithDefaults

`func NewCycleE2eReportWithDefaults() *CycleE2eReport`

NewCycleE2eReportWithDefaults instantiates a new CycleE2eReport object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetFinishedAt

`func (o *CycleE2eReport) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *CycleE2eReport) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *CycleE2eReport) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *CycleE2eReport) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### GetJourneys

`func (o *CycleE2eReport) GetJourneys() []CycleE2eReportJourneysInner`

GetJourneys returns the Journeys field if non-nil, zero value otherwise.

### GetJourneysOk

`func (o *CycleE2eReport) GetJourneysOk() (*[]CycleE2eReportJourneysInner, bool)`

GetJourneysOk returns a tuple with the Journeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJourneys

`func (o *CycleE2eReport) SetJourneys(v []CycleE2eReportJourneysInner)`

SetJourneys sets Journeys field to given value.


### GetPreviewUrl

`func (o *CycleE2eReport) GetPreviewUrl() string`

GetPreviewUrl returns the PreviewUrl field if non-nil, zero value otherwise.

### GetPreviewUrlOk

`func (o *CycleE2eReport) GetPreviewUrlOk() (*string, bool)`

GetPreviewUrlOk returns a tuple with the PreviewUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewUrl

`func (o *CycleE2eReport) SetPreviewUrl(v string)`

SetPreviewUrl sets PreviewUrl field to given value.

### HasPreviewUrl

`func (o *CycleE2eReport) HasPreviewUrl() bool`

HasPreviewUrl returns a boolean if a field has been set.

### GetStatus

`func (o *CycleE2eReport) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CycleE2eReport) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CycleE2eReport) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


