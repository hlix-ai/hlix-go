# ManagedMailboxImportInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cursor** | Pointer to **string** |  | [optional]
**Domains** | Pointer to **[]string** |  | [optional]
**Limit** | Pointer to **int32** |  | [optional] [default to 10]

## Methods

### NewManagedMailboxImportInput

`func NewManagedMailboxImportInput() *ManagedMailboxImportInput`

NewManagedMailboxImportInput instantiates a new ManagedMailboxImportInput object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewManagedMailboxImportInputWithDefaults

`func NewManagedMailboxImportInputWithDefaults() *ManagedMailboxImportInput`

NewManagedMailboxImportInputWithDefaults instantiates a new ManagedMailboxImportInput object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCursor

`func (o *ManagedMailboxImportInput) GetCursor() string`

GetCursor returns the Cursor field if non-nil, zero value otherwise.

### GetCursorOk

`func (o *ManagedMailboxImportInput) GetCursorOk() (*string, bool)`

GetCursorOk returns a tuple with the Cursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCursor

`func (o *ManagedMailboxImportInput) SetCursor(v string)`

SetCursor sets Cursor field to given value.

### HasCursor

`func (o *ManagedMailboxImportInput) HasCursor() bool`

HasCursor returns a boolean if a field has been set.

### GetDomains

`func (o *ManagedMailboxImportInput) GetDomains() []string`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *ManagedMailboxImportInput) GetDomainsOk() (*[]string, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *ManagedMailboxImportInput) SetDomains(v []string)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *ManagedMailboxImportInput) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### GetLimit

`func (o *ManagedMailboxImportInput) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ManagedMailboxImportInput) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ManagedMailboxImportInput) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ManagedMailboxImportInput) HasLimit() bool`

HasLimit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


