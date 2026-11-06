# CycleTurn

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delivery** | **string** |  | 
**Replayed** | Pointer to **bool** |  | [optional] 
**Stored** | **bool** |  | 

## Methods

### NewCycleTurn

`func NewCycleTurn(delivery string, stored bool, ) *CycleTurn`

NewCycleTurn instantiates a new CycleTurn object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCycleTurnWithDefaults

`func NewCycleTurnWithDefaults() *CycleTurn`

NewCycleTurnWithDefaults instantiates a new CycleTurn object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelivery

`func (o *CycleTurn) GetDelivery() string`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *CycleTurn) GetDeliveryOk() (*string, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *CycleTurn) SetDelivery(v string)`

SetDelivery sets Delivery field to given value.


### GetReplayed

`func (o *CycleTurn) GetReplayed() bool`

GetReplayed returns the Replayed field if non-nil, zero value otherwise.

### GetReplayedOk

`func (o *CycleTurn) GetReplayedOk() (*bool, bool)`

GetReplayedOk returns a tuple with the Replayed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplayed

`func (o *CycleTurn) SetReplayed(v bool)`

SetReplayed sets Replayed field to given value.

### HasReplayed

`func (o *CycleTurn) HasReplayed() bool`

HasReplayed returns a boolean if a field has been set.

### GetStored

`func (o *CycleTurn) GetStored() bool`

GetStored returns the Stored field if non-nil, zero value otherwise.

### GetStoredOk

`func (o *CycleTurn) GetStoredOk() (*bool, bool)`

GetStoredOk returns a tuple with the Stored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStored

`func (o *CycleTurn) SetStored(v bool)`

SetStored sets Stored field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


