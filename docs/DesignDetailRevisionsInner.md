# DesignDetailRevisionsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BuildRequestedAt** | **NullableString** |  |
**ContentHash** | **string** |  |
**Context** | [**DesignDetailRevisionContext**](DesignDetailRevisionContext.md) |  |
**CreatedAt** | **string** |  |
**DecidedAt** | **NullableString** |  |
**DecidedBy** | **NullableString** |  |
**DecisionComment** | **NullableString** |  |
**DesignId** | **string** |  |
**Evidence** | [**[]DesignDetailRevisionEvidenceInner**](DesignDetailRevisionEvidenceInner.md) |  |
**Flows** | [**[]DesignDetailRevisionFlowsInner**](DesignDetailRevisionFlowsInner.md) |  |
**Frames** | [**[]DesignDetailRevisionFramesInner**](DesignDetailRevisionFramesInner.md) |  |
**Id** | **string** |  |
**Number** | **float32** |  |
**SourcePath** | **NullableString** |  |
**SourceTaskId** | **NullableString** |  |
**Status** | **string** |  |

## Methods

### NewDesignDetailRevisionsInner

`func NewDesignDetailRevisionsInner(buildRequestedAt NullableString, contentHash string, context DesignDetailRevisionContext, createdAt string, decidedAt NullableString, decidedBy NullableString, decisionComment NullableString, designId string, evidence []DesignDetailRevisionEvidenceInner, flows []DesignDetailRevisionFlowsInner, frames []DesignDetailRevisionFramesInner, id string, number float32, sourcePath NullableString, sourceTaskId NullableString, status string, ) *DesignDetailRevisionsInner`

NewDesignDetailRevisionsInner instantiates a new DesignDetailRevisionsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDesignDetailRevisionsInnerWithDefaults

`func NewDesignDetailRevisionsInnerWithDefaults() *DesignDetailRevisionsInner`

NewDesignDetailRevisionsInnerWithDefaults instantiates a new DesignDetailRevisionsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBuildRequestedAt

`func (o *DesignDetailRevisionsInner) GetBuildRequestedAt() string`

GetBuildRequestedAt returns the BuildRequestedAt field if non-nil, zero value otherwise.

### GetBuildRequestedAtOk

`func (o *DesignDetailRevisionsInner) GetBuildRequestedAtOk() (*string, bool)`

GetBuildRequestedAtOk returns a tuple with the BuildRequestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildRequestedAt

`func (o *DesignDetailRevisionsInner) SetBuildRequestedAt(v string)`

SetBuildRequestedAt sets BuildRequestedAt field to given value.


### SetBuildRequestedAtNil

`func (o *DesignDetailRevisionsInner) SetBuildRequestedAtNil(b bool)`

 SetBuildRequestedAtNil sets the value for BuildRequestedAt to be an explicit nil

### UnsetBuildRequestedAt
`func (o *DesignDetailRevisionsInner) UnsetBuildRequestedAt()`

UnsetBuildRequestedAt ensures that no value is present for BuildRequestedAt, not even an explicit nil
### GetContentHash

`func (o *DesignDetailRevisionsInner) GetContentHash() string`

GetContentHash returns the ContentHash field if non-nil, zero value otherwise.

### GetContentHashOk

`func (o *DesignDetailRevisionsInner) GetContentHashOk() (*string, bool)`

GetContentHashOk returns a tuple with the ContentHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentHash

`func (o *DesignDetailRevisionsInner) SetContentHash(v string)`

SetContentHash sets ContentHash field to given value.


### GetContext

`func (o *DesignDetailRevisionsInner) GetContext() DesignDetailRevisionContext`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *DesignDetailRevisionsInner) GetContextOk() (*DesignDetailRevisionContext, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *DesignDetailRevisionsInner) SetContext(v DesignDetailRevisionContext)`

SetContext sets Context field to given value.


### GetCreatedAt

`func (o *DesignDetailRevisionsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DesignDetailRevisionsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DesignDetailRevisionsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDecidedAt

`func (o *DesignDetailRevisionsInner) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *DesignDetailRevisionsInner) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *DesignDetailRevisionsInner) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *DesignDetailRevisionsInner) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *DesignDetailRevisionsInner) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *DesignDetailRevisionsInner) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *DesignDetailRevisionsInner) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *DesignDetailRevisionsInner) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *DesignDetailRevisionsInner) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *DesignDetailRevisionsInner) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDecisionComment

`func (o *DesignDetailRevisionsInner) GetDecisionComment() string`

GetDecisionComment returns the DecisionComment field if non-nil, zero value otherwise.

### GetDecisionCommentOk

`func (o *DesignDetailRevisionsInner) GetDecisionCommentOk() (*string, bool)`

GetDecisionCommentOk returns a tuple with the DecisionComment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecisionComment

`func (o *DesignDetailRevisionsInner) SetDecisionComment(v string)`

SetDecisionComment sets DecisionComment field to given value.


### SetDecisionCommentNil

`func (o *DesignDetailRevisionsInner) SetDecisionCommentNil(b bool)`

 SetDecisionCommentNil sets the value for DecisionComment to be an explicit nil

### UnsetDecisionComment
`func (o *DesignDetailRevisionsInner) UnsetDecisionComment()`

UnsetDecisionComment ensures that no value is present for DecisionComment, not even an explicit nil
### GetDesignId

`func (o *DesignDetailRevisionsInner) GetDesignId() string`

GetDesignId returns the DesignId field if non-nil, zero value otherwise.

### GetDesignIdOk

`func (o *DesignDetailRevisionsInner) GetDesignIdOk() (*string, bool)`

GetDesignIdOk returns a tuple with the DesignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesignId

`func (o *DesignDetailRevisionsInner) SetDesignId(v string)`

SetDesignId sets DesignId field to given value.


### GetEvidence

`func (o *DesignDetailRevisionsInner) GetEvidence() []DesignDetailRevisionEvidenceInner`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *DesignDetailRevisionsInner) GetEvidenceOk() (*[]DesignDetailRevisionEvidenceInner, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *DesignDetailRevisionsInner) SetEvidence(v []DesignDetailRevisionEvidenceInner)`

SetEvidence sets Evidence field to given value.


### GetFlows

`func (o *DesignDetailRevisionsInner) GetFlows() []DesignDetailRevisionFlowsInner`

GetFlows returns the Flows field if non-nil, zero value otherwise.

### GetFlowsOk

`func (o *DesignDetailRevisionsInner) GetFlowsOk() (*[]DesignDetailRevisionFlowsInner, bool)`

GetFlowsOk returns a tuple with the Flows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlows

`func (o *DesignDetailRevisionsInner) SetFlows(v []DesignDetailRevisionFlowsInner)`

SetFlows sets Flows field to given value.


### GetFrames

`func (o *DesignDetailRevisionsInner) GetFrames() []DesignDetailRevisionFramesInner`

GetFrames returns the Frames field if non-nil, zero value otherwise.

### GetFramesOk

`func (o *DesignDetailRevisionsInner) GetFramesOk() (*[]DesignDetailRevisionFramesInner, bool)`

GetFramesOk returns a tuple with the Frames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrames

`func (o *DesignDetailRevisionsInner) SetFrames(v []DesignDetailRevisionFramesInner)`

SetFrames sets Frames field to given value.


### GetId

`func (o *DesignDetailRevisionsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DesignDetailRevisionsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DesignDetailRevisionsInner) SetId(v string)`

SetId sets Id field to given value.


### GetNumber

`func (o *DesignDetailRevisionsInner) GetNumber() float32`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *DesignDetailRevisionsInner) GetNumberOk() (*float32, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *DesignDetailRevisionsInner) SetNumber(v float32)`

SetNumber sets Number field to given value.


### GetSourcePath

`func (o *DesignDetailRevisionsInner) GetSourcePath() string`

GetSourcePath returns the SourcePath field if non-nil, zero value otherwise.

### GetSourcePathOk

`func (o *DesignDetailRevisionsInner) GetSourcePathOk() (*string, bool)`

GetSourcePathOk returns a tuple with the SourcePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePath

`func (o *DesignDetailRevisionsInner) SetSourcePath(v string)`

SetSourcePath sets SourcePath field to given value.


### SetSourcePathNil

`func (o *DesignDetailRevisionsInner) SetSourcePathNil(b bool)`

 SetSourcePathNil sets the value for SourcePath to be an explicit nil

### UnsetSourcePath
`func (o *DesignDetailRevisionsInner) UnsetSourcePath()`

UnsetSourcePath ensures that no value is present for SourcePath, not even an explicit nil
### GetSourceTaskId

`func (o *DesignDetailRevisionsInner) GetSourceTaskId() string`

GetSourceTaskId returns the SourceTaskId field if non-nil, zero value otherwise.

### GetSourceTaskIdOk

`func (o *DesignDetailRevisionsInner) GetSourceTaskIdOk() (*string, bool)`

GetSourceTaskIdOk returns a tuple with the SourceTaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceTaskId

`func (o *DesignDetailRevisionsInner) SetSourceTaskId(v string)`

SetSourceTaskId sets SourceTaskId field to given value.


### SetSourceTaskIdNil

`func (o *DesignDetailRevisionsInner) SetSourceTaskIdNil(b bool)`

 SetSourceTaskIdNil sets the value for SourceTaskId to be an explicit nil

### UnsetSourceTaskId
`func (o *DesignDetailRevisionsInner) UnsetSourceTaskId()`

UnsetSourceTaskId ensures that no value is present for SourceTaskId, not even an explicit nil
### GetStatus

`func (o *DesignDetailRevisionsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DesignDetailRevisionsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DesignDetailRevisionsInner) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


