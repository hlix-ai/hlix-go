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
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewSecretEntriesWithDefaults

`func NewSecretEntriesWithDefaults() *SecretEntries`

NewSecretEntriesWithDefaults instantiates a new SecretEntries object
This constructor applies declared defaults. It does not ensure required properties are set.

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


