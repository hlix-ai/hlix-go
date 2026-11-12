# ValidationError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | [**ValidationErrorError**](ValidationErrorError.md) |  |
**Success** | **bool** |  | [default to false]

## Methods

### NewValidationError

`func NewValidationError(error_ ValidationErrorError, success bool, ) *ValidationError`

NewValidationError instantiates a new ValidationError object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewValidationErrorWithDefaults

`func NewValidationErrorWithDefaults() *ValidationError`

NewValidationErrorWithDefaults instantiates a new ValidationError object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetError

`func (o *ValidationError) GetError() ValidationErrorError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ValidationError) GetErrorOk() (*ValidationErrorError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ValidationError) SetError(v ValidationErrorError)`

SetError sets Error field to given value.


### GetSuccess

`func (o *ValidationError) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ValidationError) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ValidationError) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


