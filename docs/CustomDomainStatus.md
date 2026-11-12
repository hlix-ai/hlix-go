# CustomDomainStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Domain** | **NullableString** |  |
**Errors** | Pointer to **[]string** |  | [optional]
**Records** | Pointer to [**[]CustomDomainStatusRecordsInner**](CustomDomainStatusRecordsInner.md) |  | [optional]
**State** | Pointer to **string** |  | [optional]

## Methods

### NewCustomDomainStatus

`func NewCustomDomainStatus(domain NullableString, ) *CustomDomainStatus`

NewCustomDomainStatus instantiates a new CustomDomainStatus object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCustomDomainStatusWithDefaults

`func NewCustomDomainStatusWithDefaults() *CustomDomainStatus`

NewCustomDomainStatusWithDefaults instantiates a new CustomDomainStatus object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDomain

`func (o *CustomDomainStatus) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *CustomDomainStatus) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *CustomDomainStatus) SetDomain(v string)`

SetDomain sets Domain field to given value.


### SetDomainNil

`func (o *CustomDomainStatus) SetDomainNil(b bool)`

 SetDomainNil sets the value for Domain to be an explicit nil

### UnsetDomain
`func (o *CustomDomainStatus) UnsetDomain()`

UnsetDomain ensures that no value is present for Domain, not even an explicit nil
### GetErrors

`func (o *CustomDomainStatus) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CustomDomainStatus) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CustomDomainStatus) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *CustomDomainStatus) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetRecords

`func (o *CustomDomainStatus) GetRecords() []CustomDomainStatusRecordsInner`

GetRecords returns the Records field if non-nil, zero value otherwise.

### GetRecordsOk

`func (o *CustomDomainStatus) GetRecordsOk() (*[]CustomDomainStatusRecordsInner, bool)`

GetRecordsOk returns a tuple with the Records field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecords

`func (o *CustomDomainStatus) SetRecords(v []CustomDomainStatusRecordsInner)`

SetRecords sets Records field to given value.

### HasRecords

`func (o *CustomDomainStatus) HasRecords() bool`

HasRecords returns a boolean if a field has been set.

### GetState

`func (o *CustomDomainStatus) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *CustomDomainStatus) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *CustomDomainStatus) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *CustomDomainStatus) HasState() bool`

HasState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


