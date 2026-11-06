# CanvasAgentOps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ops** | [**[]CanvasAgentOpsOpsInner**](CanvasAgentOpsOpsInner.md) |  | 
**Reason** | Pointer to **string** |  | [optional] 

## Methods

### NewCanvasAgentOps

`func NewCanvasAgentOps(ops []CanvasAgentOpsOpsInner, ) *CanvasAgentOps`

NewCanvasAgentOps instantiates a new CanvasAgentOps object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCanvasAgentOpsWithDefaults

`func NewCanvasAgentOpsWithDefaults() *CanvasAgentOps`

NewCanvasAgentOpsWithDefaults instantiates a new CanvasAgentOps object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOps

`func (o *CanvasAgentOps) GetOps() []CanvasAgentOpsOpsInner`

GetOps returns the Ops field if non-nil, zero value otherwise.

### GetOpsOk

`func (o *CanvasAgentOps) GetOpsOk() (*[]CanvasAgentOpsOpsInner, bool)`

GetOpsOk returns a tuple with the Ops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOps

`func (o *CanvasAgentOps) SetOps(v []CanvasAgentOpsOpsInner)`

SetOps sets Ops field to given value.


### GetReason

`func (o *CanvasAgentOps) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CanvasAgentOps) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CanvasAgentOps) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CanvasAgentOps) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


