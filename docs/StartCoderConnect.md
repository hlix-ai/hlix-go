# StartCoderConnect

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **string** |  | [optional] 
**CallbackPort** | Pointer to **int32** |  | [optional] 
**Coder** | **string** |  | 
**Label** | **string** |  | 
**Shared** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewStartCoderConnect

`func NewStartCoderConnect(coder string, label string, ) *StartCoderConnect`

NewStartCoderConnect instantiates a new StartCoderConnect object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStartCoderConnectWithDefaults

`func NewStartCoderConnectWithDefaults() *StartCoderConnect`

NewStartCoderConnectWithDefaults instantiates a new StartCoderConnect object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *StartCoderConnect) GetAccountId() string`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *StartCoderConnect) GetAccountIdOk() (*string, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *StartCoderConnect) SetAccountId(v string)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *StartCoderConnect) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetCallbackPort

`func (o *StartCoderConnect) GetCallbackPort() int32`

GetCallbackPort returns the CallbackPort field if non-nil, zero value otherwise.

### GetCallbackPortOk

`func (o *StartCoderConnect) GetCallbackPortOk() (*int32, bool)`

GetCallbackPortOk returns a tuple with the CallbackPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackPort

`func (o *StartCoderConnect) SetCallbackPort(v int32)`

SetCallbackPort sets CallbackPort field to given value.

### HasCallbackPort

`func (o *StartCoderConnect) HasCallbackPort() bool`

HasCallbackPort returns a boolean if a field has been set.

### GetCoder

`func (o *StartCoderConnect) GetCoder() string`

GetCoder returns the Coder field if non-nil, zero value otherwise.

### GetCoderOk

`func (o *StartCoderConnect) GetCoderOk() (*string, bool)`

GetCoderOk returns a tuple with the Coder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoder

`func (o *StartCoderConnect) SetCoder(v string)`

SetCoder sets Coder field to given value.


### GetLabel

`func (o *StartCoderConnect) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *StartCoderConnect) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *StartCoderConnect) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetShared

`func (o *StartCoderConnect) GetShared() bool`

GetShared returns the Shared field if non-nil, zero value otherwise.

### GetSharedOk

`func (o *StartCoderConnect) GetSharedOk() (*bool, bool)`

GetSharedOk returns a tuple with the Shared field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShared

`func (o *StartCoderConnect) SetShared(v bool)`

SetShared sets Shared field to given value.

### HasShared

`func (o *StartCoderConnect) HasShared() bool`

HasShared returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


