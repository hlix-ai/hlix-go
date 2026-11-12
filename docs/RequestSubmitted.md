# RequestSubmitted

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Adopted** | **bool** |  |
**CycleId** | **NullableString** |  |
**RequestId** | **NullableString** |  |
**Submitted** | **bool** |  | [default to true]

## Methods

### NewRequestSubmitted

`func NewRequestSubmitted(adopted bool, cycleId NullableString, requestId NullableString, submitted bool, ) *RequestSubmitted`

NewRequestSubmitted instantiates a new RequestSubmitted object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewRequestSubmittedWithDefaults

`func NewRequestSubmittedWithDefaults() *RequestSubmitted`

NewRequestSubmittedWithDefaults instantiates a new RequestSubmitted object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAdopted

`func (o *RequestSubmitted) GetAdopted() bool`

GetAdopted returns the Adopted field if non-nil, zero value otherwise.

### GetAdoptedOk

`func (o *RequestSubmitted) GetAdoptedOk() (*bool, bool)`

GetAdoptedOk returns a tuple with the Adopted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdopted

`func (o *RequestSubmitted) SetAdopted(v bool)`

SetAdopted sets Adopted field to given value.


### GetCycleId

`func (o *RequestSubmitted) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *RequestSubmitted) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *RequestSubmitted) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *RequestSubmitted) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *RequestSubmitted) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetRequestId

`func (o *RequestSubmitted) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *RequestSubmitted) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *RequestSubmitted) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### SetRequestIdNil

`func (o *RequestSubmitted) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *RequestSubmitted) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil
### GetSubmitted

`func (o *RequestSubmitted) GetSubmitted() bool`

GetSubmitted returns the Submitted field if non-nil, zero value otherwise.

### GetSubmittedOk

`func (o *RequestSubmitted) GetSubmittedOk() (*bool, bool)`

GetSubmittedOk returns a tuple with the Submitted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubmitted

`func (o *RequestSubmitted) SetSubmitted(v bool)`

SetSubmitted sets Submitted field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


