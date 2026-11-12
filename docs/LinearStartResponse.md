# LinearStartResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CycleId** | **NullableString** |  |
**Ok** | **bool** |  | [default to true]
**RequestId** | **string** |  |

## Methods

### NewLinearStartResponse

`func NewLinearStartResponse(cycleId NullableString, ok bool, requestId string, ) *LinearStartResponse`

NewLinearStartResponse instantiates a new LinearStartResponse object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewLinearStartResponseWithDefaults

`func NewLinearStartResponseWithDefaults() *LinearStartResponse`

NewLinearStartResponseWithDefaults instantiates a new LinearStartResponse object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCycleId

`func (o *LinearStartResponse) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *LinearStartResponse) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *LinearStartResponse) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *LinearStartResponse) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *LinearStartResponse) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetOk

`func (o *LinearStartResponse) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *LinearStartResponse) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *LinearStartResponse) SetOk(v bool)`

SetOk sets Ok field to given value.


### GetRequestId

`func (o *LinearStartResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *LinearStartResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *LinearStartResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


