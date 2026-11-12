# Approval

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApprovalType** | **string** |  |
**Blocking** | **bool** |  |
**Context** | **interface{}** |  |
**CreatedAt** | **string** |  |
**CycleId** | **NullableString** |  |
**Deadline** | **NullableString** |  |
**DecidedAt** | **NullableString** |  |
**DecidedBy** | **NullableString** |  |
**Decision** | **NullableString** |  |
**Description** | **string** |  |
**Id** | **string** |  |
**OrganizationId** | **string** |  |
**RequiredActor** | **string** |  |
**ResultingAction** | **interface{}** |  |
**Status** | **string** |  |
**TaskId** | **NullableString** |  |
**Title** | **string** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewApproval

`func NewApproval(approvalType string, blocking bool, context interface{}, createdAt string, cycleId NullableString, deadline NullableString, decidedAt NullableString, decidedBy NullableString, decision NullableString, description string, id string, organizationId string, requiredActor string, resultingAction interface{}, status string, taskId NullableString, title string, updatedAt string, ) *Approval`

NewApproval instantiates a new Approval object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewApprovalWithDefaults

`func NewApprovalWithDefaults() *Approval`

NewApprovalWithDefaults instantiates a new Approval object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovalType

`func (o *Approval) GetApprovalType() string`

GetApprovalType returns the ApprovalType field if non-nil, zero value otherwise.

### GetApprovalTypeOk

`func (o *Approval) GetApprovalTypeOk() (*string, bool)`

GetApprovalTypeOk returns a tuple with the ApprovalType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalType

`func (o *Approval) SetApprovalType(v string)`

SetApprovalType sets ApprovalType field to given value.


### GetBlocking

`func (o *Approval) GetBlocking() bool`

GetBlocking returns the Blocking field if non-nil, zero value otherwise.

### GetBlockingOk

`func (o *Approval) GetBlockingOk() (*bool, bool)`

GetBlockingOk returns a tuple with the Blocking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocking

`func (o *Approval) SetBlocking(v bool)`

SetBlocking sets Blocking field to given value.


### GetContext

`func (o *Approval) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *Approval) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *Approval) SetContext(v interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *Approval) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *Approval) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCreatedAt

`func (o *Approval) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Approval) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Approval) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *Approval) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *Approval) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *Approval) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *Approval) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *Approval) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDeadline

`func (o *Approval) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *Approval) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *Approval) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.


### SetDeadlineNil

`func (o *Approval) SetDeadlineNil(b bool)`

 SetDeadlineNil sets the value for Deadline to be an explicit nil

### UnsetDeadline
`func (o *Approval) UnsetDeadline()`

UnsetDeadline ensures that no value is present for Deadline, not even an explicit nil
### GetDecidedAt

`func (o *Approval) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *Approval) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *Approval) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *Approval) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *Approval) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *Approval) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *Approval) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *Approval) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *Approval) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *Approval) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDecision

`func (o *Approval) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *Approval) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *Approval) SetDecision(v string)`

SetDecision sets Decision field to given value.


### SetDecisionNil

`func (o *Approval) SetDecisionNil(b bool)`

 SetDecisionNil sets the value for Decision to be an explicit nil

### UnsetDecision
`func (o *Approval) UnsetDecision()`

UnsetDecision ensures that no value is present for Decision, not even an explicit nil
### GetDescription

`func (o *Approval) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Approval) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Approval) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *Approval) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Approval) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Approval) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *Approval) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Approval) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Approval) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRequiredActor

`func (o *Approval) GetRequiredActor() string`

GetRequiredActor returns the RequiredActor field if non-nil, zero value otherwise.

### GetRequiredActorOk

`func (o *Approval) GetRequiredActorOk() (*string, bool)`

GetRequiredActorOk returns a tuple with the RequiredActor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredActor

`func (o *Approval) SetRequiredActor(v string)`

SetRequiredActor sets RequiredActor field to given value.


### GetResultingAction

`func (o *Approval) GetResultingAction() interface{}`

GetResultingAction returns the ResultingAction field if non-nil, zero value otherwise.

### GetResultingActionOk

`func (o *Approval) GetResultingActionOk() (*interface{}, bool)`

GetResultingActionOk returns a tuple with the ResultingAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingAction

`func (o *Approval) SetResultingAction(v interface{})`

SetResultingAction sets ResultingAction field to given value.


### SetResultingActionNil

`func (o *Approval) SetResultingActionNil(b bool)`

 SetResultingActionNil sets the value for ResultingAction to be an explicit nil

### UnsetResultingAction
`func (o *Approval) UnsetResultingAction()`

UnsetResultingAction ensures that no value is present for ResultingAction, not even an explicit nil
### GetStatus

`func (o *Approval) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Approval) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Approval) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *Approval) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *Approval) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *Approval) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *Approval) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *Approval) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTitle

`func (o *Approval) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Approval) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Approval) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *Approval) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Approval) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Approval) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


