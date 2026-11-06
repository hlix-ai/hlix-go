# CoderAccountUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CapturedAt** | **string** |  | 
**Windows** | [**[]CoderAccountUsageWindowsInner**](CoderAccountUsageWindowsInner.md) |  | 

## Methods

### NewCoderAccountUsage

`func NewCoderAccountUsage(capturedAt string, windows []CoderAccountUsageWindowsInner, ) *CoderAccountUsage`

NewCoderAccountUsage instantiates a new CoderAccountUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCoderAccountUsageWithDefaults

`func NewCoderAccountUsageWithDefaults() *CoderAccountUsage`

NewCoderAccountUsageWithDefaults instantiates a new CoderAccountUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCapturedAt

`func (o *CoderAccountUsage) GetCapturedAt() string`

GetCapturedAt returns the CapturedAt field if non-nil, zero value otherwise.

### GetCapturedAtOk

`func (o *CoderAccountUsage) GetCapturedAtOk() (*string, bool)`

GetCapturedAtOk returns a tuple with the CapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapturedAt

`func (o *CoderAccountUsage) SetCapturedAt(v string)`

SetCapturedAt sets CapturedAt field to given value.


### GetWindows

`func (o *CoderAccountUsage) GetWindows() []CoderAccountUsageWindowsInner`

GetWindows returns the Windows field if non-nil, zero value otherwise.

### GetWindowsOk

`func (o *CoderAccountUsage) GetWindowsOk() (*[]CoderAccountUsageWindowsInner, bool)`

GetWindowsOk returns a tuple with the Windows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindows

`func (o *CoderAccountUsage) SetWindows(v []CoderAccountUsageWindowsInner)`

SetWindows sets Windows field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


