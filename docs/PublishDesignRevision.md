# PublishDesignRevision

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Context** | [**DesignDetailRevisionContext**](DesignDetailRevisionContext.md) |  | 
**Evidence** | [**[]DesignDetailRevisionEvidenceInner**](DesignDetailRevisionEvidenceInner.md) |  | 
**ExpectedRevisionId** | **NullableString** |  | 
**Flows** | [**[]DesignDetailRevisionFlowsInner**](DesignDetailRevisionFlowsInner.md) |  | 
**Frames** | [**[]DesignDetailRevisionFramesInner**](DesignDetailRevisionFramesInner.md) |  | 
**Html** | **string** |  | 
**SourcePath** | Pointer to **string** |  | [optional] 

## Methods

### NewPublishDesignRevision

`func NewPublishDesignRevision(context DesignDetailRevisionContext, evidence []DesignDetailRevisionEvidenceInner, expectedRevisionId NullableString, flows []DesignDetailRevisionFlowsInner, frames []DesignDetailRevisionFramesInner, html string, ) *PublishDesignRevision`

NewPublishDesignRevision instantiates a new PublishDesignRevision object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishDesignRevisionWithDefaults

`func NewPublishDesignRevisionWithDefaults() *PublishDesignRevision`

NewPublishDesignRevisionWithDefaults instantiates a new PublishDesignRevision object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContext

`func (o *PublishDesignRevision) GetContext() DesignDetailRevisionContext`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *PublishDesignRevision) GetContextOk() (*DesignDetailRevisionContext, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *PublishDesignRevision) SetContext(v DesignDetailRevisionContext)`

SetContext sets Context field to given value.


### GetEvidence

`func (o *PublishDesignRevision) GetEvidence() []DesignDetailRevisionEvidenceInner`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *PublishDesignRevision) GetEvidenceOk() (*[]DesignDetailRevisionEvidenceInner, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *PublishDesignRevision) SetEvidence(v []DesignDetailRevisionEvidenceInner)`

SetEvidence sets Evidence field to given value.


### GetExpectedRevisionId

`func (o *PublishDesignRevision) GetExpectedRevisionId() string`

GetExpectedRevisionId returns the ExpectedRevisionId field if non-nil, zero value otherwise.

### GetExpectedRevisionIdOk

`func (o *PublishDesignRevision) GetExpectedRevisionIdOk() (*string, bool)`

GetExpectedRevisionIdOk returns a tuple with the ExpectedRevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedRevisionId

`func (o *PublishDesignRevision) SetExpectedRevisionId(v string)`

SetExpectedRevisionId sets ExpectedRevisionId field to given value.


### SetExpectedRevisionIdNil

`func (o *PublishDesignRevision) SetExpectedRevisionIdNil(b bool)`

 SetExpectedRevisionIdNil sets the value for ExpectedRevisionId to be an explicit nil

### UnsetExpectedRevisionId
`func (o *PublishDesignRevision) UnsetExpectedRevisionId()`

UnsetExpectedRevisionId ensures that no value is present for ExpectedRevisionId, not even an explicit nil
### GetFlows

`func (o *PublishDesignRevision) GetFlows() []DesignDetailRevisionFlowsInner`

GetFlows returns the Flows field if non-nil, zero value otherwise.

### GetFlowsOk

`func (o *PublishDesignRevision) GetFlowsOk() (*[]DesignDetailRevisionFlowsInner, bool)`

GetFlowsOk returns a tuple with the Flows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlows

`func (o *PublishDesignRevision) SetFlows(v []DesignDetailRevisionFlowsInner)`

SetFlows sets Flows field to given value.


### GetFrames

`func (o *PublishDesignRevision) GetFrames() []DesignDetailRevisionFramesInner`

GetFrames returns the Frames field if non-nil, zero value otherwise.

### GetFramesOk

`func (o *PublishDesignRevision) GetFramesOk() (*[]DesignDetailRevisionFramesInner, bool)`

GetFramesOk returns a tuple with the Frames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrames

`func (o *PublishDesignRevision) SetFrames(v []DesignDetailRevisionFramesInner)`

SetFrames sets Frames field to given value.


### GetHtml

`func (o *PublishDesignRevision) GetHtml() string`

GetHtml returns the Html field if non-nil, zero value otherwise.

### GetHtmlOk

`func (o *PublishDesignRevision) GetHtmlOk() (*string, bool)`

GetHtmlOk returns a tuple with the Html field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHtml

`func (o *PublishDesignRevision) SetHtml(v string)`

SetHtml sets Html field to given value.


### GetSourcePath

`func (o *PublishDesignRevision) GetSourcePath() string`

GetSourcePath returns the SourcePath field if non-nil, zero value otherwise.

### GetSourcePathOk

`func (o *PublishDesignRevision) GetSourcePathOk() (*string, bool)`

GetSourcePathOk returns a tuple with the SourcePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePath

`func (o *PublishDesignRevision) SetSourcePath(v string)`

SetSourcePath sets SourcePath field to given value.

### HasSourcePath

`func (o *PublishDesignRevision) HasSourcePath() bool`

HasSourcePath returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


