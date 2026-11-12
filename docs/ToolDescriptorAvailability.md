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
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewToolDescriptorAvailabilityWithDefaults

`func NewToolDescriptorAvailabilityWithDefaults() *ToolDescriptorAvailability`

NewToolDescriptorAvailabilityWithDefaults instantiates a new ToolDescriptorAvailability object
This constructor applies declared defaults. It does not ensure required properties are set.

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


