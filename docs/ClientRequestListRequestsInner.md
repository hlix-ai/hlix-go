# ClientRequestListRequestsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApprovedRevision** | **NullableInt32** |  | 
**Attachments** | [**[]ClientRequestDetailAttachmentsInner**](ClientRequestDetailAttachmentsInner.md) |  | 
**CanApprove** | **bool** |  | 
**CanRespond** | **bool** |  | 
**CreatedAt** | **string** |  | 
**CurrentPlan** | [**NullableClientRequestDetailCurrentPlan**](ClientRequestDetailCurrentPlan.md) |  | 
**CycleId** | **NullableString** |  | 
**Id** | **string** |  | 
**ProjectId** | **string** |  | 
**ProposalId** | **NullableString** |  | 
**RequesterUserId** | **string** |  | 
**Status** | **string** |  | 
**Title** | **string** |  | 
**TurnPending** | **bool** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewClientRequestListRequestsInner

`func NewClientRequestListRequestsInner(approvedRevision NullableInt32, attachments []ClientRequestDetailAttachmentsInner, canApprove bool, canRespond bool, createdAt string, currentPlan NullableClientRequestDetailCurrentPlan, cycleId NullableString, id string, projectId string, proposalId NullableString, requesterUserId string, status string, title string, turnPending bool, updatedAt string, ) *ClientRequestListRequestsInner`

NewClientRequestListRequestsInner instantiates a new ClientRequestListRequestsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientRequestListRequestsInnerWithDefaults

`func NewClientRequestListRequestsInnerWithDefaults() *ClientRequestListRequestsInner`

NewClientRequestListRequestsInnerWithDefaults instantiates a new ClientRequestListRequestsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApprovedRevision

`func (o *ClientRequestListRequestsInner) GetApprovedRevision() int32`

GetApprovedRevision returns the ApprovedRevision field if non-nil, zero value otherwise.

### GetApprovedRevisionOk

`func (o *ClientRequestListRequestsInner) GetApprovedRevisionOk() (*int32, bool)`

GetApprovedRevisionOk returns a tuple with the ApprovedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedRevision

`func (o *ClientRequestListRequestsInner) SetApprovedRevision(v int32)`

SetApprovedRevision sets ApprovedRevision field to given value.


### SetApprovedRevisionNil

`func (o *ClientRequestListRequestsInner) SetApprovedRevisionNil(b bool)`

 SetApprovedRevisionNil sets the value for ApprovedRevision to be an explicit nil

### UnsetApprovedRevision
`func (o *ClientRequestListRequestsInner) UnsetApprovedRevision()`

UnsetApprovedRevision ensures that no value is present for ApprovedRevision, not even an explicit nil
### GetAttachments

`func (o *ClientRequestListRequestsInner) GetAttachments() []ClientRequestDetailAttachmentsInner`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ClientRequestListRequestsInner) GetAttachmentsOk() (*[]ClientRequestDetailAttachmentsInner, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ClientRequestListRequestsInner) SetAttachments(v []ClientRequestDetailAttachmentsInner)`

SetAttachments sets Attachments field to given value.


### GetCanApprove

`func (o *ClientRequestListRequestsInner) GetCanApprove() bool`

GetCanApprove returns the CanApprove field if non-nil, zero value otherwise.

### GetCanApproveOk

`func (o *ClientRequestListRequestsInner) GetCanApproveOk() (*bool, bool)`

GetCanApproveOk returns a tuple with the CanApprove field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanApprove

`func (o *ClientRequestListRequestsInner) SetCanApprove(v bool)`

SetCanApprove sets CanApprove field to given value.


### GetCanRespond

`func (o *ClientRequestListRequestsInner) GetCanRespond() bool`

GetCanRespond returns the CanRespond field if non-nil, zero value otherwise.

### GetCanRespondOk

`func (o *ClientRequestListRequestsInner) GetCanRespondOk() (*bool, bool)`

GetCanRespondOk returns a tuple with the CanRespond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRespond

`func (o *ClientRequestListRequestsInner) SetCanRespond(v bool)`

SetCanRespond sets CanRespond field to given value.


### GetCreatedAt

`func (o *ClientRequestListRequestsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientRequestListRequestsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientRequestListRequestsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrentPlan

`func (o *ClientRequestListRequestsInner) GetCurrentPlan() ClientRequestDetailCurrentPlan`

GetCurrentPlan returns the CurrentPlan field if non-nil, zero value otherwise.

### GetCurrentPlanOk

`func (o *ClientRequestListRequestsInner) GetCurrentPlanOk() (*ClientRequestDetailCurrentPlan, bool)`

GetCurrentPlanOk returns a tuple with the CurrentPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPlan

`func (o *ClientRequestListRequestsInner) SetCurrentPlan(v ClientRequestDetailCurrentPlan)`

SetCurrentPlan sets CurrentPlan field to given value.


### SetCurrentPlanNil

`func (o *ClientRequestListRequestsInner) SetCurrentPlanNil(b bool)`

 SetCurrentPlanNil sets the value for CurrentPlan to be an explicit nil

### UnsetCurrentPlan
`func (o *ClientRequestListRequestsInner) UnsetCurrentPlan()`

UnsetCurrentPlan ensures that no value is present for CurrentPlan, not even an explicit nil
### GetCycleId

`func (o *ClientRequestListRequestsInner) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ClientRequestListRequestsInner) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ClientRequestListRequestsInner) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ClientRequestListRequestsInner) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ClientRequestListRequestsInner) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetId

`func (o *ClientRequestListRequestsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientRequestListRequestsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientRequestListRequestsInner) SetId(v string)`

SetId sets Id field to given value.


### GetProjectId

`func (o *ClientRequestListRequestsInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ClientRequestListRequestsInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ClientRequestListRequestsInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetProposalId

`func (o *ClientRequestListRequestsInner) GetProposalId() string`

GetProposalId returns the ProposalId field if non-nil, zero value otherwise.

### GetProposalIdOk

`func (o *ClientRequestListRequestsInner) GetProposalIdOk() (*string, bool)`

GetProposalIdOk returns a tuple with the ProposalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalId

`func (o *ClientRequestListRequestsInner) SetProposalId(v string)`

SetProposalId sets ProposalId field to given value.


### SetProposalIdNil

`func (o *ClientRequestListRequestsInner) SetProposalIdNil(b bool)`

 SetProposalIdNil sets the value for ProposalId to be an explicit nil

### UnsetProposalId
`func (o *ClientRequestListRequestsInner) UnsetProposalId()`

UnsetProposalId ensures that no value is present for ProposalId, not even an explicit nil
### GetRequesterUserId

`func (o *ClientRequestListRequestsInner) GetRequesterUserId() string`

GetRequesterUserId returns the RequesterUserId field if non-nil, zero value otherwise.

### GetRequesterUserIdOk

`func (o *ClientRequestListRequestsInner) GetRequesterUserIdOk() (*string, bool)`

GetRequesterUserIdOk returns a tuple with the RequesterUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequesterUserId

`func (o *ClientRequestListRequestsInner) SetRequesterUserId(v string)`

SetRequesterUserId sets RequesterUserId field to given value.


### GetStatus

`func (o *ClientRequestListRequestsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientRequestListRequestsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientRequestListRequestsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *ClientRequestListRequestsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ClientRequestListRequestsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ClientRequestListRequestsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTurnPending

`func (o *ClientRequestListRequestsInner) GetTurnPending() bool`

GetTurnPending returns the TurnPending field if non-nil, zero value otherwise.

### GetTurnPendingOk

`func (o *ClientRequestListRequestsInner) GetTurnPendingOk() (*bool, bool)`

GetTurnPendingOk returns a tuple with the TurnPending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTurnPending

`func (o *ClientRequestListRequestsInner) SetTurnPending(v bool)`

SetTurnPending sets TurnPending field to given value.


### GetUpdatedAt

`func (o *ClientRequestListRequestsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ClientRequestListRequestsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ClientRequestListRequestsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


