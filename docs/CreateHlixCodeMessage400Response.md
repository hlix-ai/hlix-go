# CreateHlixCodeMessage400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | [**AnthropicErrorError**](AnthropicErrorError.md) |  | 
**Success** | **bool** |  | 
**Type** | **string** |  | 

## Methods

### NewCreateHlixCodeMessage400Response

`func NewCreateHlixCodeMessage400Response(error_ AnthropicErrorError, success bool, type_ string, ) *CreateHlixCodeMessage400Response`

NewCreateHlixCodeMessage400Response instantiates a new CreateHlixCodeMessage400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateHlixCodeMessage400ResponseWithDefaults

`func NewCreateHlixCodeMessage400ResponseWithDefaults() *CreateHlixCodeMessage400Response`

NewCreateHlixCodeMessage400ResponseWithDefaults instantiates a new CreateHlixCodeMessage400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *CreateHlixCodeMessage400Response) GetError() AnthropicErrorError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CreateHlixCodeMessage400Response) GetErrorOk() (*AnthropicErrorError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CreateHlixCodeMessage400Response) SetError(v AnthropicErrorError)`

SetError sets Error field to given value.


### GetSuccess

`func (o *CreateHlixCodeMessage400Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateHlixCodeMessage400Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateHlixCodeMessage400Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetType

`func (o *CreateHlixCodeMessage400Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateHlixCodeMessage400Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateHlixCodeMessage400Response) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


