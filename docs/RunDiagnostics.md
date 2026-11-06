# RunDiagnostics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to [**RunDiagnosticsError**](RunDiagnosticsError.md) |  | [optional] 
**RawStatus** | Pointer to **string** |  | [optional] 
**Status** | **string** |  | 
**Suspended** | [**[]RunDiagnosticsSuspendedInner**](RunDiagnosticsSuspendedInner.md) |  | 

## Methods

### NewRunDiagnostics

`func NewRunDiagnostics(status string, suspended []RunDiagnosticsSuspendedInner, ) *RunDiagnostics`

NewRunDiagnostics instantiates a new RunDiagnostics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunDiagnosticsWithDefaults

`func NewRunDiagnosticsWithDefaults() *RunDiagnostics`

NewRunDiagnosticsWithDefaults instantiates a new RunDiagnostics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *RunDiagnostics) GetError() RunDiagnosticsError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *RunDiagnostics) GetErrorOk() (*RunDiagnosticsError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *RunDiagnostics) SetError(v RunDiagnosticsError)`

SetError sets Error field to given value.

### HasError

`func (o *RunDiagnostics) HasError() bool`

HasError returns a boolean if a field has been set.

### GetRawStatus

`func (o *RunDiagnostics) GetRawStatus() string`

GetRawStatus returns the RawStatus field if non-nil, zero value otherwise.

### GetRawStatusOk

`func (o *RunDiagnostics) GetRawStatusOk() (*string, bool)`

GetRawStatusOk returns a tuple with the RawStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawStatus

`func (o *RunDiagnostics) SetRawStatus(v string)`

SetRawStatus sets RawStatus field to given value.

### HasRawStatus

`func (o *RunDiagnostics) HasRawStatus() bool`

HasRawStatus returns a boolean if a field has been set.

### GetStatus

`func (o *RunDiagnostics) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RunDiagnostics) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RunDiagnostics) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetSuspended

`func (o *RunDiagnostics) GetSuspended() []RunDiagnosticsSuspendedInner`

GetSuspended returns the Suspended field if non-nil, zero value otherwise.

### GetSuspendedOk

`func (o *RunDiagnostics) GetSuspendedOk() (*[]RunDiagnosticsSuspendedInner, bool)`

GetSuspendedOk returns a tuple with the Suspended field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspended

`func (o *RunDiagnostics) SetSuspended(v []RunDiagnosticsSuspendedInner)`

SetSuspended sets Suspended field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


