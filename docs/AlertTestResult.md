# AlertTestResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delivered** | **bool** |  |
**Error** | **NullableString** |  |
**Route** | [**NullableAlertSettingsSlackRoute**](AlertSettingsSlackRoute.md) |  |

## Methods

### NewAlertTestResult

`func NewAlertTestResult(delivered bool, error_ NullableString, route NullableAlertSettingsSlackRoute, ) *AlertTestResult`

NewAlertTestResult instantiates a new AlertTestResult object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAlertTestResultWithDefaults

`func NewAlertTestResultWithDefaults() *AlertTestResult`

NewAlertTestResultWithDefaults instantiates a new AlertTestResult object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDelivered

`func (o *AlertTestResult) GetDelivered() bool`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *AlertTestResult) GetDeliveredOk() (*bool, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *AlertTestResult) SetDelivered(v bool)`

SetDelivered sets Delivered field to given value.


### GetError

`func (o *AlertTestResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AlertTestResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AlertTestResult) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *AlertTestResult) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AlertTestResult) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetRoute

`func (o *AlertTestResult) GetRoute() AlertSettingsSlackRoute`

GetRoute returns the Route field if non-nil, zero value otherwise.

### GetRouteOk

`func (o *AlertTestResult) GetRouteOk() (*AlertSettingsSlackRoute, bool)`

GetRouteOk returns a tuple with the Route field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoute

`func (o *AlertTestResult) SetRoute(v AlertSettingsSlackRoute)`

SetRoute sets Route field to given value.


### SetRouteNil

`func (o *AlertTestResult) SetRouteNil(b bool)`

 SetRouteNil sets the value for Route to be an explicit nil

### UnsetRoute
`func (o *AlertTestResult) UnsetRoute()`

UnsetRoute ensures that no value is present for Route, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


