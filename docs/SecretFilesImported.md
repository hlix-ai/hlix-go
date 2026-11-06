# SecretFilesImported

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Imported** | [**[]SecretFilesImportedImportedInner**](SecretFilesImportedImportedInner.md) |  | 
**Rejected** | **[]string** |  | 
**Skipped** | [**[]SecretFilesImportedSkippedInner**](SecretFilesImportedSkippedInner.md) |  | 
**Warnings** | **[]string** |  | 
**Written** | **int32** |  | 

## Methods

### NewSecretFilesImported

`func NewSecretFilesImported(imported []SecretFilesImportedImportedInner, rejected []string, skipped []SecretFilesImportedSkippedInner, warnings []string, written int32, ) *SecretFilesImported`

NewSecretFilesImported instantiates a new SecretFilesImported object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecretFilesImportedWithDefaults

`func NewSecretFilesImportedWithDefaults() *SecretFilesImported`

NewSecretFilesImportedWithDefaults instantiates a new SecretFilesImported object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImported

`func (o *SecretFilesImported) GetImported() []SecretFilesImportedImportedInner`

GetImported returns the Imported field if non-nil, zero value otherwise.

### GetImportedOk

`func (o *SecretFilesImported) GetImportedOk() (*[]SecretFilesImportedImportedInner, bool)`

GetImportedOk returns a tuple with the Imported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImported

`func (o *SecretFilesImported) SetImported(v []SecretFilesImportedImportedInner)`

SetImported sets Imported field to given value.


### GetRejected

`func (o *SecretFilesImported) GetRejected() []string`

GetRejected returns the Rejected field if non-nil, zero value otherwise.

### GetRejectedOk

`func (o *SecretFilesImported) GetRejectedOk() (*[]string, bool)`

GetRejectedOk returns a tuple with the Rejected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRejected

`func (o *SecretFilesImported) SetRejected(v []string)`

SetRejected sets Rejected field to given value.


### GetSkipped

`func (o *SecretFilesImported) GetSkipped() []SecretFilesImportedSkippedInner`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *SecretFilesImported) GetSkippedOk() (*[]SecretFilesImportedSkippedInner, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *SecretFilesImported) SetSkipped(v []SecretFilesImportedSkippedInner)`

SetSkipped sets Skipped field to given value.


### GetWarnings

`func (o *SecretFilesImported) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *SecretFilesImported) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *SecretFilesImported) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.


### GetWritten

`func (o *SecretFilesImported) GetWritten() int32`

GetWritten returns the Written field if non-nil, zero value otherwise.

### GetWrittenOk

`func (o *SecretFilesImported) GetWrittenOk() (*int32, bool)`

GetWrittenOk returns a tuple with the Written field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWritten

`func (o *SecretFilesImported) SetWritten(v int32)`

SetWritten sets Written field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


