# CanvasAgentUndo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Revision** | **NullableInt32** |  | 
**Undone** | **bool** |  | 

## Methods

### NewCanvasAgentUndo

`func NewCanvasAgentUndo(revision NullableInt32, undone bool, ) *CanvasAgentUndo`

NewCanvasAgentUndo instantiates a new CanvasAgentUndo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCanvasAgentUndoWithDefaults

`func NewCanvasAgentUndoWithDefaults() *CanvasAgentUndo`

NewCanvasAgentUndoWithDefaults instantiates a new CanvasAgentUndo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRevision

`func (o *CanvasAgentUndo) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *CanvasAgentUndo) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *CanvasAgentUndo) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### SetRevisionNil

`func (o *CanvasAgentUndo) SetRevisionNil(b bool)`

 SetRevisionNil sets the value for Revision to be an explicit nil

### UnsetRevision
`func (o *CanvasAgentUndo) UnsetRevision()`

UnsetRevision ensures that no value is present for Revision, not even an explicit nil
### GetUndone

`func (o *CanvasAgentUndo) GetUndone() bool`

GetUndone returns the Undone field if non-nil, zero value otherwise.

### GetUndoneOk

`func (o *CanvasAgentUndo) GetUndoneOk() (*bool, bool)`

GetUndoneOk returns a tuple with the Undone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUndone

`func (o *CanvasAgentUndo) SetUndone(v bool)`

SetUndone sets Undone field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


