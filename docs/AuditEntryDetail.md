# AuditEntryDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Correlated** | [**AuditEntryDetailCorrelated**](AuditEntryDetailCorrelated.md) |  | 
**Entry** | [**AuditEntryDetailEntry**](AuditEntryDetailEntry.md) |  | 

## Methods

### NewAuditEntryDetail

`func NewAuditEntryDetail(correlated AuditEntryDetailCorrelated, entry AuditEntryDetailEntry, ) *AuditEntryDetail`

NewAuditEntryDetail instantiates a new AuditEntryDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuditEntryDetailWithDefaults

`func NewAuditEntryDetailWithDefaults() *AuditEntryDetail`

NewAuditEntryDetailWithDefaults instantiates a new AuditEntryDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCorrelated

`func (o *AuditEntryDetail) GetCorrelated() AuditEntryDetailCorrelated`

GetCorrelated returns the Correlated field if non-nil, zero value otherwise.

### GetCorrelatedOk

`func (o *AuditEntryDetail) GetCorrelatedOk() (*AuditEntryDetailCorrelated, bool)`

GetCorrelatedOk returns a tuple with the Correlated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelated

`func (o *AuditEntryDetail) SetCorrelated(v AuditEntryDetailCorrelated)`

SetCorrelated sets Correlated field to given value.


### GetEntry

`func (o *AuditEntryDetail) GetEntry() AuditEntryDetailEntry`

GetEntry returns the Entry field if non-nil, zero value otherwise.

### GetEntryOk

`func (o *AuditEntryDetail) GetEntryOk() (*AuditEntryDetailEntry, bool)`

GetEntryOk returns a tuple with the Entry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntry

`func (o *AuditEntryDetail) SetEntry(v AuditEntryDetailEntry)`

SetEntry sets Entry field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


