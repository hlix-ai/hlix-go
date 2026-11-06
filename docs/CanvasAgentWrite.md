# CanvasAgentWrite

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Applied** | **bool** |  | 
**ContextChanged** | **bool** |  | 
**ContextRevision** | **int32** |  | 
**Ops** | [**[]CanvasAgentWriteOpsInner**](CanvasAgentWriteOpsInner.md) |  | 
**ProposalId** | **NullableString** |  | 
**Revision** | **int32** |  | 

## Methods

### NewCanvasAgentWrite

`func NewCanvasAgentWrite(applied bool, contextChanged bool, contextRevision int32, ops []CanvasAgentWriteOpsInner, proposalId NullableString, revision int32, ) *CanvasAgentWrite`

NewCanvasAgentWrite instantiates a new CanvasAgentWrite object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCanvasAgentWriteWithDefaults

`func NewCanvasAgentWriteWithDefaults() *CanvasAgentWrite`

NewCanvasAgentWriteWithDefaults instantiates a new CanvasAgentWrite object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


### GetProposalId

`func (o *CanvasAgentWrite) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *CanvasAgentWrite) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *CanvasAgentWrite) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### SetProposalIdNil

`func (o *CanvasAgentWrite) SetProposalIdNil(b bool)`

 SetProposalIdNil sets the value for ProposalId to be an explicit nil

### UnsetProposalId
`func (o *CanvasAgentWrite) UnsetProposalId()`

UnsetProposalId ensures that no value is present for ProposalId, not even an explicit nil
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


