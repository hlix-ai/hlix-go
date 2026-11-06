# SecretEntriesWritten

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rejected** | **[]string** |  | 
**Written** | **int32** |  | 

## Methods

### NewSecretEntriesWritten

`func NewSecretEntriesWritten(rejected []string, written int32, ) *SecretEntriesWritten`

NewSecretEntriesWritten instantiates a new SecretEntriesWritten object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecretEntriesWrittenWithDefaults

`func NewSecretEntriesWrittenWithDefaults() *SecretEntriesWritten`

NewSecretEntriesWrittenWithDefaults instantiates a new SecretEntriesWritten object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRejected

`func (o *SecretEntriesWritten) GetRejected() []string`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *SecretEntriesWritten) GetRejectedOk() (*[]string, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *SecretEntriesWritten) SetRejected(v []string)`

SetRejected sets Rejected field to given value.


### GetWritten

`func (o *SecretEntriesWritten) GetWritten() int32`

GetWritten returns the Written field if non-nil, zero value otherwise.

### GetWrittenOk

`func (o *SecretEntriesWritten) GetWrittenOk() (*int32, bool)`

GetWrittenOk returns a tuple with the Written field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWritten

`func (o *SecretEntriesWritten) SetWritten(v int32)`

SetWritten sets Written field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


