# SecretEntries

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entries** | [**[]SecretEntriesEntriesInner**](SecretEntriesEntriesInner.md) |  | 
**Warnings** | **[]string** |  | 

## Methods

### NewSecretEntries

`func NewSecretEntries(entries []SecretEntriesEntriesInner, warnings []string, ) *SecretEntries`

NewSecretEntries instantiates a new SecretEntries object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecretEntriesWithDefaults

`func NewSecretEntriesWithDefaults() *SecretEntries`

NewSecretEntriesWithDefaults instantiates a new SecretEntries object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntries

`func (o *SecretEntries) GetEntries() []SecretEntriesEntriesInner`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *SecretEntries) GetEntriesOk() (*[]SecretEntriesEntriesInner, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *SecretEntries) SetEntries(v []SecretEntriesEntriesInner)`

SetEntries sets Entries field to given value.


### GetWarnings

`func (o *SecretEntries) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *SecretEntries) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *SecretEntries) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


