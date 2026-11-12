# CanvasAgentWrite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Applied** | **bool** |  |
**ApprovalId** | **NullableString** |  |
**ContextChanged** | **bool** |  |
**ContextRevision** | **int32** |  |
**Ops** | [**[]CanvasAgentWriteOpsInner**](CanvasAgentWriteOpsInner.md) |  |
**Revision** | **int32** |  |

## Methods

### NewCanvasAgentWrite

`func NewCanvasAgentWrite(applied bool, approvalId NullableString, contextChanged bool, contextRevision int32, ops []CanvasAgentWriteOpsInner, revision int32, ) *CanvasAgentWrite`

NewCanvasAgentWrite instantiates a new CanvasAgentWrite object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewCanvasAgentWriteWithDefaults

`func NewCanvasAgentWriteWithDefaults() *CanvasAgentWrite`

NewCanvasAgentWriteWithDefaults instantiates a new CanvasAgentWrite object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApplied

`func (o *CanvasAgentWrite) GetApplied() bool`

GetApplied returns the Applied field if non-nil, zero value otherwise.

### GetAppliedOk

`func (o *CanvasAgentWrite) GetAppliedOk() (*bool, bool)`

GetAppliedOk returns a tuple with the Applied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplied

`func (o *CanvasAgentWrite) SetApplied(v bool)`

SetApplied sets Applied field to given value.


### GetApprovalId

`func (o *CanvasAgentWrite) GetApprovalId() string`

GetApprovalId returns the ApprovalId field if non-nil, zero value otherwise.

### GetApprovalIdOk

`func (o *CanvasAgentWrite) GetApprovalIdOk() (*string, bool)`

GetApprovalIdOk returns a tuple with the ApprovalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalId

`func (o *CanvasAgentWrite) SetApprovalId(v string)`

SetApprovalId sets ApprovalId field to given value.


### SetApprovalIdNil

`func (o *CanvasAgentWrite) SetApprovalIdNil(b bool)`

 SetApprovalIdNil sets the value for ApprovalId to be an explicit nil

### UnsetApprovalId
`func (o *CanvasAgentWrite) UnsetApprovalId()`

UnsetApprovalId ensures that no value is present for ApprovalId, not even an explicit nil
### GetContextChanged

`func (o *CanvasAgentWrite) GetContextChanged() bool`

GetContextChanged returns the ContextChanged field if non-nil, zero value otherwise.

### GetContextChangedOk

`func (o *CanvasAgentWrite) GetContextChangedOk() (*bool, bool)`

GetContextChangedOk returns a tuple with the ContextChanged field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextChanged

`func (o *CanvasAgentWrite) SetContextChanged(v bool)`

SetContextChanged sets ContextChanged field to given value.


### GetContextRevision

`func (o *CanvasAgentWrite) GetContextRevision() int32`

GetContextRevision returns the ContextRevision field if non-nil, zero value otherwise.

### GetContextRevisionOk

`func (o *CanvasAgentWrite) GetContextRevisionOk() (*int32, bool)`

GetContextRevisionOk returns a tuple with the ContextRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextRevision

`func (o *CanvasAgentWrite) SetContextRevision(v int32)`

SetContextRevision sets ContextRevision field to given value.


### GetOps

`func (o *CanvasAgentWrite) GetOps() []CanvasAgentWriteOpsInner`

GetOps returns the Ops field if non-nil, zero value otherwise.

### GetOpsOk

`func (o *CanvasAgentWrite) GetOpsOk() (*[]CanvasAgentWriteOpsInner, bool)`

GetOpsOk returns a tuple with the Ops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOps

`func (o *CanvasAgentWrite) SetOps(v []CanvasAgentWriteOpsInner)`

SetOps sets Ops field to given value.


### GetRevision

`func (o *CanvasAgentWrite) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CanvasAgentWrite) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CanvasAgentWrite) SetRevision(v int32)`

SetRevision sets Revision field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


