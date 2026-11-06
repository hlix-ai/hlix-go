# ImportAgent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **string** |  | [optional] 
**Duty** | Pointer to **string** |  | [optional] 
**Instructions** | **string** |  | 
**Name** | **string** |  | 
**RuntimeKind** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewImportAgent

`func NewImportAgent(instructions string, name string, ) *ImportAgent`

NewImportAgent instantiates a new ImportAgent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportAgentWithDefaults

`func NewImportAgentWithDefaults() *ImportAgent`

NewImportAgentWithDefaults instantiates a new ImportAgent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


### GetRuntimeKind

`func (o *ImportAgent) GetRuntimeKind() string`

GetRuntimeKind returns the RuntimeKind field if non-nil, zero value otherwise.

### GetRuntimeKindOk

`func (o *ImportAgent) GetRuntimeKindOk() (*string, bool)`

GetRuntimeKindOk returns a tuple with the RuntimeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeKind

`func (o *ImportAgent) SetRuntimeKind(v string)`

SetRuntimeKind sets RuntimeKind field to given value.

### HasRuntimeKind

`func (o *ImportAgent) HasRuntimeKind() bool`

HasRuntimeKind returns a boolean if a field has been set.

### SetRuntimeKindNil

`func (o *ImportAgent) SetRuntimeKindNil(b bool)`

 SetRuntimeKindNil sets the value for RuntimeKind to be an explicit nil

### UnsetRuntimeKind
`func (o *ImportAgent) UnsetRuntimeKind()`

UnsetRuntimeKind ensures that no value is present for RuntimeKind, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


