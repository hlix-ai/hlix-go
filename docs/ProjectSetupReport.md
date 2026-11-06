# ProjectSetupReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FinishedAt** | Pointer to **string** |  | [optional] 
**StartedAt** | **string** |  | 
**Status** | **string** |  | 
**Steps** | [**[]ProjectSetupReportStepsInner**](ProjectSetupReportStepsInner.md) |  | 

## Methods

### NewProjectSetupReport

`func NewProjectSetupReport(startedAt string, status string, steps []ProjectSetupReportStepsInner, ) *ProjectSetupReport`

NewProjectSetupReport instantiates a new ProjectSetupReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectSetupReportWithDefaults

`func NewProjectSetupReportWithDefaults() *ProjectSetupReport`

NewProjectSetupReportWithDefaults instantiates a new ProjectSetupReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFinishedAt

`func (o *ProjectSetupReport) GetFinishedAt() string`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *ProjectSetupReport) GetFinishedAtOk() (*string, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *ProjectSetupReport) SetFinishedAt(v string)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *ProjectSetupReport) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### GetStartedAt

`func (o *ProjectSetupReport) GetStartedAt() string`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *ProjectSetupReport) GetStartedAtOk() (*string, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *ProjectSetupReport) SetStartedAt(v string)`

SetStartedAt sets StartedAt field to given value.


### GetStatus

`func (o *ProjectSetupReport) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectSetupReport) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectSetupReport) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSteps

`func (o *ProjectSetupReport) GetSteps() []ProjectSetupReportStepsInner`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *ProjectSetupReport) GetStepsOk() (*[]ProjectSetupReportStepsInner, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *ProjectSetupReport) SetSteps(v []ProjectSetupReportStepsInner)`

SetSteps sets Steps field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


