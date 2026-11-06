# CreateHlixCodeMessage403Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | [**AnthropicErrorError**](AnthropicErrorError.md) |  | 
**Type** | **string** |  | 

## Methods

### NewCreateHlixCodeMessage403Response

`func NewCreateHlixCodeMessage403Response(error_ AnthropicErrorError, type_ string, ) *CreateHlixCodeMessage403Response`

NewCreateHlixCodeMessage403Response instantiates a new CreateHlixCodeMessage403Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateHlixCodeMessage403ResponseWithDefaults

`func NewCreateHlixCodeMessage403ResponseWithDefaults() *CreateHlixCodeMessage403Response`

NewCreateHlixCodeMessage403ResponseWithDefaults instantiates a new CreateHlixCodeMessage403Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *CreateHlixCodeMessage403Response) GetError() AnthropicErrorError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *CreateHlixCodeMessage403Response) GetErrorOk() (*AnthropicErrorError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *CreateHlixCodeMessage403Response) SetError(v AnthropicErrorError)`

SetError sets Error field to given value.


### GetType

`func (o *CreateHlixCodeMessage403Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateHlixCodeMessage403Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateHlixCodeMessage403Response) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


