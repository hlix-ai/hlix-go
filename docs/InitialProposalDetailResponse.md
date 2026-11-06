# InitialProposalDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Complete** | **bool** |  | 
**ProjectId** | **string** |  | 
**Proposal** | [**InitialProposalDetailResponseProposal**](InitialProposalDetailResponseProposal.md) |  | 
**Revision** | [**NullableInitialProposalDetailResponseRevision**](InitialProposalDetailResponseRevision.md) |  | 

## Methods

### NewInitialProposalDetailResponse

`func NewInitialProposalDetailResponse(complete bool, projectId string, proposal InitialProposalDetailResponseProposal, revision NullableInitialProposalDetailResponseRevision, ) *InitialProposalDetailResponse`

NewInitialProposalDetailResponse instantiates a new InitialProposalDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitialProposalDetailResponseWithDefaults

`func NewInitialProposalDetailResponseWithDefaults() *InitialProposalDetailResponse`

NewInitialProposalDetailResponseWithDefaults instantiates a new InitialProposalDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComplete

`func (o *InitialProposalDetailResponse) GetComplete() bool`

GetComplete returns the Complete field if non-nil, zero value otherwise.

### GetCompleteOk

`func (o *InitialProposalDetailResponse) GetCompleteOk() (*bool, bool)`

GetCompleteOk returns a tuple with the Complete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplete

`func (o *InitialProposalDetailResponse) SetComplete(v bool)`

SetComplete sets Complete field to given value.


### GetProjectId

`func (o *InitialProposalDetailResponse) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *InitialProposalDetailResponse) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *InitialProposalDetailResponse) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProposal

`func (o *InitialProposalDetailResponse) GetProposal() InitialProposalDetailResponseProposal`

GetProposal returns the Proposal field if non-nil, zero value otherwise.

### GetProposalOk

`func (o *InitialProposalDetailResponse) GetProposalOk() (*InitialProposalDetailResponseProposal, bool)`

GetProposalOk returns a tuple with the Proposal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposal

`func (o *InitialProposalDetailResponse) SetProposal(v InitialProposalDetailResponseProposal)`

SetProposal sets Proposal field to given value.


### GetRevision

`func (o *InitialProposalDetailResponse) GetRevision() InitialProposalDetailResponseRevision`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *InitialProposalDetailResponse) GetRevisionOk() (*InitialProposalDetailResponseRevision, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *InitialProposalDetailResponse) SetRevision(v InitialProposalDetailResponseRevision)`

SetRevision sets Revision field to given value.


### SetRevisionNil

`func (o *InitialProposalDetailResponse) SetRevisionNil(b bool)`

 SetRevisionNil sets the value for Revision to be an explicit nil

### UnsetRevision
`func (o *InitialProposalDetailResponse) UnsetRevision()`

UnsetRevision ensures that no value is present for Revision, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


