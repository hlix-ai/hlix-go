# ImportAgent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Coder** | Pointer to **NullableString** |  | [optional]
**Description** | Pointer to **string** |  | [optional]
**Duty** | Pointer to **string** |  | [optional]
**Instructions** | **string** |  |
**Name** | **string** |  |

## Methods

### NewImportAgent

`func NewImportAgent(instructions string, name string, ) *ImportAgent`

NewImportAgent instantiates a new ImportAgent object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewImportAgentWithDefaults

`func NewImportAgentWithDefaults() *ImportAgent`

NewImportAgentWithDefaults instantiates a new ImportAgent object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetCoder

`func (o *ImportAgent) GetCoder() string`

GetCoder returns the Coder field if non-nil, zero value otherwise.

### GetCoderOk

`func (o *ImportAgent) GetCoderOk() (*string, bool)`

GetCoderOk returns a tuple with the Coder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoder

`func (o *ImportAgent) SetCoder(v string)`

SetCoder sets Coder field to given value.

### HasCoder

`func (o *ImportAgent) HasCoder() bool`

HasCoder returns a boolean if a field has been set.

### SetCoderNil

`func (o *ImportAgent) SetCoderNil(b bool)`

 SetCoderNil sets the value for Coder to be an explicit nil

### UnsetCoder
`func (o *ImportAgent) UnsetCoder()`

UnsetCoder ensures that no value is present for Coder, not even an explicit nil
### GetDescription

`func (o *ImportAgent) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ImportAgent) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ImportAgent) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ImportAgent) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDuty

`func (o *ImportAgent) GetDuty() string`

GetDuty returns the Duty field if non-nil, zero value otherwise.

### GetDutyOk

`func (o *ImportAgent) GetDutyOk() (*string, bool)`

GetDutyOk returns a tuple with the Duty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuty

`func (o *ImportAgent) SetDuty(v string)`

SetDuty sets Duty field to given value.

### HasDuty

`func (o *ImportAgent) HasDuty() bool`

HasDuty returns a boolean if a field has been set.

### GetInstructions

`func (o *ImportAgent) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *ImportAgent) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *ImportAgent) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.


### GetName

`func (o *ImportAgent) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ImportAgent) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ImportAgent) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


