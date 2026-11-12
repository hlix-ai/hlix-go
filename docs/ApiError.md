# ApiError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **string** |  |

## Methods

### NewApiError

`func NewApiError(error_ string, ) *ApiError`

NewApiError instantiates a new ApiError object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewApiErrorWithDefaults

`func NewApiErrorWithDefaults() *ApiError`

NewApiErrorWithDefaults instantiates a new ApiError object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetError

`func (o *ApiError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ApiError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ApiError) SetError(v string)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


