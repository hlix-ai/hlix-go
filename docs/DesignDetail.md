# DesignDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comments** | [**[]DesignDetailCommentsInner**](DesignDetailCommentsInner.md) |  | 
**Design** | [**DesignDetailDesign**](DesignDetailDesign.md) |  | 
**Link** | **string** |  | 
**Revision** | [**NullableDesignDetailRevision**](DesignDetailRevision.md) |  | 
**Revisions** | [**[]DesignDetailRevisionsInner**](DesignDetailRevisionsInner.md) |  | 

## Methods

### NewDesignDetail

`func NewDesignDetail(comments []DesignDetailCommentsInner, design DesignDetailDesign, link string, revision NullableDesignDetailRevision, revisions []DesignDetailRevisionsInner, ) *DesignDetail`

NewDesignDetail instantiates a new DesignDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDesignDetailWithDefaults

`func NewDesignDetailWithDefaults() *DesignDetail`

NewDesignDetailWithDefaults instantiates a new DesignDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComments

`func (o *DesignDetail) GetComments() []DesignDetailCommentsInner`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *DesignDetail) GetCommentsOk() (*[]DesignDetailCommentsInner, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *DesignDetail) SetComments(v []DesignDetailCommentsInner)`

SetComments sets Comments field to given value.


### GetDesign

`func (o *DesignDetail) GetDesign() DesignDetailDesign`

GetDesign returns the Design field if non-nil, zero value otherwise.

### GetDesignOk

`func (o *DesignDetail) GetDesignOk() (*DesignDetailDesign, bool)`

GetDesignOk returns a tuple with the Design field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesign

`func (o *DesignDetail) SetDesign(v DesignDetailDesign)`

SetDesign sets Design field to given value.


### GetLink

`func (o *DesignDetail) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *DesignDetail) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *DesignDetail) SetLink(v string)`

SetLink sets Link field to given value.


### GetRevision

`func (o *DesignDetail) GetRevision() DesignDetailRevision`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *DesignDetail) GetRevisionOk() (*DesignDetailRevision, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *DesignDetail) SetRevision(v DesignDetailRevision)`

SetRevision sets Revision field to given value.


### SetRevisionNil

`func (o *DesignDetail) SetRevisionNil(b bool)`

 SetRevisionNil sets the value for Revision to be an explicit nil

### UnsetRevision
`func (o *DesignDetail) UnsetRevision()`

UnsetRevision ensures that no value is present for Revision, not even an explicit nil
### GetRevisions

`func (o *DesignDetail) GetRevisions() []DesignDetailRevisionsInner`

GetRevisions returns the Revisions field if non-nil, zero value otherwise.

### GetRevisionsOk

`func (o *DesignDetail) GetRevisionsOk() (*[]DesignDetailRevisionsInner, bool)`

GetRevisionsOk returns a tuple with the Revisions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisions

`func (o *DesignDetail) SetRevisions(v []DesignDetailRevisionsInner)`

SetRevisions sets Revisions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


