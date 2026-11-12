# ClientRequestDetail

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
**Messages** | [**[]ClientRequestDetailMessagesInner**](ClientRequestDetailMessagesInner.md) |  |
**ProjectId** | **string** |  |
**RequestId** | **NullableString** |  |
**RequesterUserId** | **string** |  |
**Status** | **string** |  |
**Title** | **string** |  |
**TurnPending** | **bool** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewClientRequestDetail

`func NewClientRequestDetail(approvedRevision NullableInt32, attachments []ClientRequestDetailAttachmentsInner, canApprove bool, canRespond bool, createdAt string, currentPlan NullableClientRequestDetailCurrentPlan, cycleId NullableString, id string, messages []ClientRequestDetailMessagesInner, projectId string, requestId NullableString, requesterUserId string, status string, title string, turnPending bool, updatedAt string, ) *ClientRequestDetail`

NewClientRequestDetail instantiates a new ClientRequestDetail object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientRequestDetailWithDefaults

`func NewClientRequestDetailWithDefaults() *ClientRequestDetail`

NewClientRequestDetailWithDefaults instantiates a new ClientRequestDetail object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovedRevision

`func (o *ClientRequestDetail) GetApprovedRevision() int32`

GetApprovedRevision returns the ApprovedRevision field if non-nil, zero value otherwise.

### GetApprovedRevisionOk

`func (o *ClientRequestDetail) GetApprovedRevisionOk() (*int32, bool)`

GetApprovedRevisionOk returns a tuple with the ApprovedRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovedRevision

`func (o *ClientRequestDetail) SetApprovedRevision(v int32)`

SetApprovedRevision sets ApprovedRevision field to given value.


### SetApprovedRevisionNil

`func (o *ClientRequestDetail) SetApprovedRevisionNil(b bool)`

 SetApprovedRevisionNil sets the value for ApprovedRevision to be an explicit nil

### UnsetApprovedRevision
`func (o *ClientRequestDetail) UnsetApprovedRevision()`

UnsetApprovedRevision ensures that no value is present for ApprovedRevision, not even an explicit nil
### GetAttachments

`func (o *ClientRequestDetail) GetAttachments() []ClientRequestDetailAttachmentsInner`

GetAttachments returns the Attachments field if non-nil, zero value otherwise.

### GetAttachmentsOk

`func (o *ClientRequestDetail) GetAttachmentsOk() (*[]ClientRequestDetailAttachmentsInner, bool)`

GetAttachmentsOk returns a tuple with the Attachments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachments

`func (o *ClientRequestDetail) SetAttachments(v []ClientRequestDetailAttachmentsInner)`

SetAttachments sets Attachments field to given value.


### GetCanApprove

`func (o *ClientRequestDetail) GetCanApprove() bool`

GetCanApprove returns the CanApprove field if non-nil, zero value otherwise.

### GetCanApproveOk

`func (o *ClientRequestDetail) GetCanApproveOk() (*bool, bool)`

GetCanApproveOk returns a tuple with the CanApprove field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanApprove

`func (o *ClientRequestDetail) SetCanApprove(v bool)`

SetCanApprove sets CanApprove field to given value.


### GetCanRespond

`func (o *ClientRequestDetail) GetCanRespond() bool`

GetCanRespond returns the CanRespond field if non-nil, zero value otherwise.

### GetCanRespondOk

`func (o *ClientRequestDetail) GetCanRespondOk() (*bool, bool)`

GetCanRespondOk returns a tuple with the CanRespond field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanRespond

`func (o *ClientRequestDetail) SetCanRespond(v bool)`

SetCanRespond sets CanRespond field to given value.


### GetCreatedAt

`func (o *ClientRequestDetail) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientRequestDetail) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientRequestDetail) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrentPlan

`func (o *ClientRequestDetail) GetCurrentPlan() ClientRequestDetailCurrentPlan`

GetCurrentPlan returns the CurrentPlan field if non-nil, zero value otherwise.

### GetCurrentPlanOk

`func (o *ClientRequestDetail) GetCurrentPlanOk() (*ClientRequestDetailCurrentPlan, bool)`

GetCurrentPlanOk returns a tuple with the CurrentPlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPlan

`func (o *ClientRequestDetail) SetCurrentPlan(v ClientRequestDetailCurrentPlan)`

SetCurrentPlan sets CurrentPlan field to given value.


### SetCurrentPlanNil

`func (o *ClientRequestDetail) SetCurrentPlanNil(b bool)`

 SetCurrentPlanNil sets the value for CurrentPlan to be an explicit nil

### UnsetCurrentPlan
`func (o *ClientRequestDetail) UnsetCurrentPlan()`

UnsetCurrentPlan ensures that no value is present for CurrentPlan, not even an explicit nil
### GetCycleId

`func (o *ClientRequestDetail) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ClientRequestDetail) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ClientRequestDetail) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ClientRequestDetail) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ClientRequestDetail) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetId

`func (o *ClientRequestDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientRequestDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientRequestDetail) SetId(v string)`

SetId sets Id field to given value.


### GetMessages

`func (o *ClientRequestDetail) GetMessages() []ClientRequestDetailMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ClientRequestDetail) GetMessagesOk() (*[]ClientRequestDetailMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ClientRequestDetail) SetMessages(v []ClientRequestDetailMessagesInner)`

SetMessages sets Messages field to given value.


### GetProjectId

`func (o *ClientRequestDetail) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ClientRequestDetail) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ClientRequestDetail) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### GetRequestId

`func (o *ClientRequestDetail) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ClientRequestDetail) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ClientRequestDetail) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### SetRequestIdNil

`func (o *ClientRequestDetail) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *ClientRequestDetail) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil
### GetRequesterUserId

`func (o *ClientRequestDetail) GetRequesterUserId() string`

GetRequesterUserId returns the RequesterUserId field if non-nil, zero value otherwise.

### GetRequesterUserIdOk

`func (o *ClientRequestDetail) GetRequesterUserIdOk() (*string, bool)`

GetRequesterUserIdOk returns a tuple with the RequesterUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequesterUserId

`func (o *ClientRequestDetail) SetRequesterUserId(v string)`

SetRequesterUserId sets RequesterUserId field to given value.


### GetStatus

`func (o *ClientRequestDetail) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientRequestDetail) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientRequestDetail) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTitle

`func (o *ClientRequestDetail) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ClientRequestDetail) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ClientRequestDetail) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTurnPending

`func (o *ClientRequestDetail) GetTurnPending() bool`

GetTurnPending returns the TurnPending field if non-nil, zero value otherwise.

### GetTurnPendingOk

`func (o *ClientRequestDetail) GetTurnPendingOk() (*bool, bool)`

GetTurnPendingOk returns a tuple with the TurnPending field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTurnPending

`func (o *ClientRequestDetail) SetTurnPending(v bool)`

SetTurnPending sets TurnPending field to given value.


### GetUpdatedAt

`func (o *ClientRequestDetail) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ClientRequestDetail) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ClientRequestDetail) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


