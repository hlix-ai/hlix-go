# ModelProviderProbe

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Detail** | Pointer to **string** |  | [optional]
**Ok** | **bool** |  |
**Status** | Pointer to **float32** |  | [optional]

## Methods

### NewModelProviderProbe

`func NewModelProviderProbe(ok bool, ) *ModelProviderProbe`

NewModelProviderProbe instantiates a new ModelProviderProbe object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewModelProviderProbeWithDefaults

`func NewModelProviderProbeWithDefaults() *ModelProviderProbe`

NewModelProviderProbeWithDefaults instantiates a new ModelProviderProbe object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDetail

`func (o *ModelProviderProbe) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *ModelProviderProbe) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *ModelProviderProbe) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *ModelProviderProbe) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### GetOk

`func (o *ModelProviderProbe) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *ModelProviderProbe) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *ModelProviderProbe) SetOk(v bool)`

SetOk sets Ok field to given value.


### GetStatus

`func (o *ModelProviderProbe) GetStatus() float32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ModelProviderProbe) GetStatusOk() (*float32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ModelProviderProbe) SetStatus(v float32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ModelProviderProbe) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


