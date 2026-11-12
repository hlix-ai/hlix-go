# DesignDecision

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comment** | Pointer to **string** |  | [optional]
**Decision** | **string** |  |
**RevisionId** | **string** |  |

## Methods

### NewDesignDecision

`func NewDesignDecision(decision string, revisionId string, ) *DesignDecision`

NewDesignDecision instantiates a new DesignDecision object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDesignDecisionWithDefaults

`func NewDesignDecisionWithDefaults() *DesignDecision`

NewDesignDecisionWithDefaults instantiates a new DesignDecision object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetComment

`func (o *DesignDecision) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *DesignDecision) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *DesignDecision) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *DesignDecision) HasComment() bool`

HasComment returns a boolean if a field has been set.

### GetDecision

`func (o *DesignDecision) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *DesignDecision) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *DesignDecision) SetDecision(v string)`

SetDecision sets Decision field to given value.


### GetRevisionId

`func (o *DesignDecision) GetRevisionId() string`

GetRevisionId returns the RevisionId field if non-nil, zero value otherwise.

### GetRevisionIdOk

`func (o *DesignDecision) GetRevisionIdOk() (*string, bool)`

GetRevisionIdOk returns a tuple with the RevisionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisionId

`func (o *DesignDecision) SetRevisionId(v string)`

SetRevisionId sets RevisionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


