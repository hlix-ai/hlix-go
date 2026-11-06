# ListPlugins400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | [**ValidationErrorError**](ValidationErrorError.md) |  | 
**Success** | **bool** |  | 

## Methods

### NewListPlugins400Response

`func NewListPlugins400Response(error_ ValidationErrorError, success bool, ) *ListPlugins400Response`

NewListPlugins400Response instantiates a new ListPlugins400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListPlugins400ResponseWithDefaults

`func NewListPlugins400ResponseWithDefaults() *ListPlugins400Response`

NewListPlugins400ResponseWithDefaults instantiates a new ListPlugins400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ListPlugins400Response) GetError() ValidationErrorError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListPlugins400Response) GetErrorOk() (*ValidationErrorError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListPlugins400Response) SetError(v ValidationErrorError)`

SetError sets Error field to given value.


### GetSuccess

`func (o *ListPlugins400Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListPlugins400Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListPlugins400Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


