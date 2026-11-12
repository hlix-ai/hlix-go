# MobileBuildStart

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedCommitSha** | Pointer to **string** | Require this exact published revision. An unpublished revision returns 409 source_not_published without creating a build. | [optional]
**TargetId** | **string** |  |

## Methods

### NewMobileBuildStart

`func NewMobileBuildStart(targetId string, ) *MobileBuildStart`

NewMobileBuildStart instantiates a new MobileBuildStart object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMobileBuildStartWithDefaults

`func NewMobileBuildStartWithDefaults() *MobileBuildStart`

NewMobileBuildStartWithDefaults instantiates a new MobileBuildStart object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetExpectedCommitSha

`func (o *MobileBuildStart) GetExpectedCommitSha() string`

GetExpectedCommitSha returns the ExpectedCommitSha field if non-nil, zero value otherwise.

### GetExpectedCommitShaOk

`func (o *MobileBuildStart) GetExpectedCommitShaOk() (*string, bool)`

GetExpectedCommitShaOk returns a tuple with the ExpectedCommitSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedCommitSha

`func (o *MobileBuildStart) SetExpectedCommitSha(v string)`

SetExpectedCommitSha sets ExpectedCommitSha field to given value.

### HasExpectedCommitSha

`func (o *MobileBuildStart) HasExpectedCommitSha() bool`

HasExpectedCommitSha returns a boolean if a field has been set.

### GetTargetId

`func (o *MobileBuildStart) GetTargetId() string`

GetTargetId returns the TargetId field if non-nil, zero value otherwise.

### GetTargetIdOk

`func (o *MobileBuildStart) GetTargetIdOk() (*string, bool)`

GetTargetIdOk returns a tuple with the TargetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetId

`func (o *MobileBuildStart) SetTargetId(v string)`

SetTargetId sets TargetId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


