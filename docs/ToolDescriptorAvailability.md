# ToolDescriptorAvailability

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ready** | **bool** |  | 
**Reason** | **NullableString** |  | 

## Methods

### NewToolDescriptorAvailability

`func NewToolDescriptorAvailability(ready bool, reason NullableString, ) *ToolDescriptorAvailability`

NewToolDescriptorAvailability instantiates a new ToolDescriptorAvailability object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolDescriptorAvailabilityWithDefaults

`func NewToolDescriptorAvailabilityWithDefaults() *ToolDescriptorAvailability`

NewToolDescriptorAvailabilityWithDefaults instantiates a new ToolDescriptorAvailability object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReady

`func (o *ToolDescriptorAvailability) GetReady() bool`

GetReady returns the Ready field if non-nil, zero value otherwise.

### GetReadyOk

`func (o *ToolDescriptorAvailability) GetReadyOk() (*bool, bool)`

GetReadyOk returns a tuple with the Ready field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReady

`func (o *ToolDescriptorAvailability) SetReady(v bool)`

SetReady sets Ready field to given value.


### GetReason

`func (o *ToolDescriptorAvailability) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ToolDescriptorAvailability) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ToolDescriptorAvailability) SetReason(v string)`

SetReason sets Reason field to given value.


### SetReasonNil

`func (o *ToolDescriptorAvailability) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *ToolDescriptorAvailability) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


