# TaskComputerInputInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** |  | 
**Button** | Pointer to **string** |  | [optional] [default to "left"]
**Double** | Pointer to **bool** |  | [optional] [default to false]
**X** | **int32** |  | 
**Y** | **int32** |  | 
**EndX** | **int32** |  | 
**EndY** | **int32** |  | 
**Amount** | Pointer to **int32** |  | [optional] [default to 3]
**Direction** | **string** |  | 
**Text** | **string** |  | 
**Key** | **string** |  | 
**Modifiers** | Pointer to **[]string** |  | [optional] 
**MaxDepth** | Pointer to **int32** |  | [optional] [default to 3]
**Name** | Pointer to **string** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**Id** | **string** |  | 
**NodeAction** | Pointer to **string** |  | [optional] 
**Value** | **string** |  | 

## Methods

### NewTaskComputerInputInput

`func NewTaskComputerInputInput(action string, x int32, y int32, endX int32, endY int32, direction string, text string, key string, id string, value string, ) *TaskComputerInputInput`

NewTaskComputerInputInput instantiates a new TaskComputerInputInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskComputerInputInputWithDefaults

`func NewTaskComputerInputInputWithDefaults() *TaskComputerInputInput`

NewTaskComputerInputInputWithDefaults instantiates a new TaskComputerInputInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *TaskComputerInputInput) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *TaskComputerInputInput) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *TaskComputerInputInput) SetAction(v string)`

SetAction sets Action field to given value.


### GetButton

`func (o *TaskComputerInputInput) GetButton() string`

GetButton returns the Button field if non-nil, zero value otherwise.

### GetButtonOk

`func (o *TaskComputerInputInput) GetButtonOk() (*string, bool)`

GetButtonOk returns a tuple with the Button field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButton

`func (o *TaskComputerInputInput) SetButton(v string)`

SetButton sets Button field to given value.

### HasButton

`func (o *TaskComputerInputInput) HasButton() bool`

HasButton returns a boolean if a field has been set.

### GetDouble

`func (o *TaskComputerInputInput) GetDouble() bool`

GetDouble returns the Double field if non-nil, zero value otherwise.

### GetDoubleOk

`func (o *TaskComputerInputInput) GetDoubleOk() (*bool, bool)`

GetDoubleOk returns a tuple with the Double field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDouble

`func (o *TaskComputerInputInput) SetDouble(v bool)`

SetDouble sets Double field to given value.

### HasDouble

`func (o *TaskComputerInputInput) HasDouble() bool`

HasDouble returns a boolean if a field has been set.

### GetX

`func (o *TaskComputerInputInput) GetX() int32`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *TaskComputerInputInput) GetXOk() (*int32, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *TaskComputerInputInput) SetX(v int32)`

SetX sets X field to given value.


### GetY

`func (o *TaskComputerInputInput) GetY() int32`

GetY returns the Y field if non-nil, zero value otherwise.

### GetYOk

`func (o *TaskComputerInputInput) GetYOk() (*int32, bool)`

GetYOk returns a tuple with the Y field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY

`func (o *TaskComputerInputInput) SetY(v int32)`

SetY sets Y field to given value.


### GetEndX

`func (o *TaskComputerInputInput) GetEndX() int32`

GetEndX returns the EndX field if non-nil, zero value otherwise.

### GetEndXOk

`func (o *TaskComputerInputInput) GetEndXOk() (*int32, bool)`

GetEndXOk returns a tuple with the EndX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndX

`func (o *TaskComputerInputInput) SetEndX(v int32)`

SetEndX sets EndX field to given value.


### GetEndY

`func (o *TaskComputerInputInput) GetEndY() int32`

GetEndY returns the EndY field if non-nil, zero value otherwise.

### GetEndYOk

`func (o *TaskComputerInputInput) GetEndYOk() (*int32, bool)`

GetEndYOk returns a tuple with the EndY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndY

`func (o *TaskComputerInputInput) SetEndY(v int32)`

SetEndY sets EndY field to given value.


### GetAmount

`func (o *TaskComputerInputInput) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *TaskComputerInputInput) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *TaskComputerInputInput) SetAmount(v int32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *TaskComputerInputInput) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetDirection

`func (o *TaskComputerInputInput) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *TaskComputerInputInput) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *TaskComputerInputInput) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetText

`func (o *TaskComputerInputInput) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TaskComputerInputInput) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TaskComputerInputInput) SetText(v string)`

SetText sets Text field to given value.


### GetKey

`func (o *TaskComputerInputInput) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *TaskComputerInputInput) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *TaskComputerInputInput) SetKey(v string)`

SetKey sets Key field to given value.


### GetModifiers

`func (o *TaskComputerInputInput) GetModifiers() []string`

GetModifiers returns the Modifiers field if non-nil, zero value otherwise.

### GetModifiersOk

`func (o *TaskComputerInputInput) GetModifiersOk() (*[]string, bool)`

GetModifiersOk returns a tuple with the Modifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModifiers

`func (o *TaskComputerInputInput) SetModifiers(v []string)`

SetModifiers sets Modifiers field to given value.

### HasModifiers

`func (o *TaskComputerInputInput) HasModifiers() bool`

HasModifiers returns a boolean if a field has been set.

### GetMaxDepth

`func (o *TaskComputerInputInput) GetMaxDepth() int32`

GetMaxDepth returns the MaxDepth field if non-nil, zero value otherwise.

### GetMaxDepthOk

`func (o *TaskComputerInputInput) GetMaxDepthOk() (*int32, bool)`

GetMaxDepthOk returns a tuple with the MaxDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDepth

`func (o *TaskComputerInputInput) SetMaxDepth(v int32)`

SetMaxDepth sets MaxDepth field to given value.

### HasMaxDepth

`func (o *TaskComputerInputInput) HasMaxDepth() bool`

HasMaxDepth returns a boolean if a field has been set.

### GetName

`func (o *TaskComputerInputInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TaskComputerInputInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TaskComputerInputInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TaskComputerInputInput) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRole

`func (o *TaskComputerInputInput) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *TaskComputerInputInput) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *TaskComputerInputInput) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *TaskComputerInputInput) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetId

`func (o *TaskComputerInputInput) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TaskComputerInputInput) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TaskComputerInputInput) SetId(v string)`

SetId sets Id field to given value.


### GetNodeAction

`func (o *TaskComputerInputInput) GetNodeAction() string`

GetNodeAction returns the NodeAction field if non-nil, zero value otherwise.

### GetNodeActionOk

`func (o *TaskComputerInputInput) GetNodeActionOk() (*string, bool)`

GetNodeActionOk returns a tuple with the NodeAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeAction

`func (o *TaskComputerInputInput) SetNodeAction(v string)`

SetNodeAction sets NodeAction field to given value.

### HasNodeAction

`func (o *TaskComputerInputInput) HasNodeAction() bool`

HasNodeAction returns a boolean if a field has been set.

### GetValue

`func (o *TaskComputerInputInput) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *TaskComputerInputInput) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *TaskComputerInputInput) SetValue(v string)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


