# ApprovalListItem

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
**ProjectId** | **NullableString** |  |
**ProjectName** | **NullableString** |  |
**RequiredActor** | **string** |  |
**ResultingAction** | **interface{}** |  |
**Status** | **string** |  |
**TaskId** | **NullableString** |  |
**Title** | **string** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewApprovalListItem

`func NewApprovalListItem(approvalType string, blocking bool, context interface{}, createdAt string, cycleId NullableString, deadline NullableString, decidedAt NullableString, decidedBy NullableString, decision NullableString, description string, id string, organizationId string, projectId NullableString, projectName NullableString, requiredActor string, resultingAction interface{}, status string, taskId NullableString, title string, updatedAt string, ) *ApprovalListItem`

NewApprovalListItem instantiates a new ApprovalListItem object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewApprovalListItemWithDefaults

`func NewApprovalListItemWithDefaults() *ApprovalListItem`

NewApprovalListItemWithDefaults instantiates a new ApprovalListItem object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovalType

`func (o *ApprovalListItem) GetApprovalType() string`

GetApprovalType returns the ApprovalType field if non-nil, zero value otherwise.

### GetApprovalTypeOk

`func (o *ApprovalListItem) GetApprovalTypeOk() (*string, bool)`

GetApprovalTypeOk returns a tuple with the ApprovalType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalType

`func (o *ApprovalListItem) SetApprovalType(v string)`

SetApprovalType sets ApprovalType field to given value.


### GetBlocking

`func (o *ApprovalListItem) GetBlocking() bool`

GetBlocking returns the Blocking field if non-nil, zero value otherwise.

### GetBlockingOk

`func (o *ApprovalListItem) GetBlockingOk() (*bool, bool)`

GetBlockingOk returns a tuple with the Blocking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocking

`func (o *ApprovalListItem) SetBlocking(v bool)`

SetBlocking sets Blocking field to given value.


### GetContext

`func (o *ApprovalListItem) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *ApprovalListItem) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *ApprovalListItem) SetContext(v interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *ApprovalListItem) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *ApprovalListItem) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCreatedAt

`func (o *ApprovalListItem) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ApprovalListItem) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ApprovalListItem) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *ApprovalListItem) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *ApprovalListItem) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *ApprovalListItem) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *ApprovalListItem) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *ApprovalListItem) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDeadline

`func (o *ApprovalListItem) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *ApprovalListItem) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *ApprovalListItem) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.


### SetDeadlineNil

`func (o *ApprovalListItem) SetDeadlineNil(b bool)`

 SetDeadlineNil sets the value for Deadline to be an explicit nil

### UnsetDeadline
`func (o *ApprovalListItem) UnsetDeadline()`

UnsetDeadline ensures that no value is present for Deadline, not even an explicit nil
### GetDecidedAt

`func (o *ApprovalListItem) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *ApprovalListItem) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *ApprovalListItem) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *ApprovalListItem) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *ApprovalListItem) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *ApprovalListItem) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *ApprovalListItem) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *ApprovalListItem) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *ApprovalListItem) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *ApprovalListItem) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDecision

`func (o *ApprovalListItem) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *ApprovalListItem) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *ApprovalListItem) SetDecision(v string)`

SetDecision sets Decision field to given value.


### SetDecisionNil

`func (o *ApprovalListItem) SetDecisionNil(b bool)`

 SetDecisionNil sets the value for Decision to be an explicit nil

### UnsetDecision
`func (o *ApprovalListItem) UnsetDecision()`

UnsetDecision ensures that no value is present for Decision, not even an explicit nil
### GetDescription

`func (o *ApprovalListItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ApprovalListItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ApprovalListItem) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *ApprovalListItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApprovalListItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApprovalListItem) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *ApprovalListItem) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ApprovalListItem) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ApprovalListItem) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *ApprovalListItem) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ApprovalListItem) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ApprovalListItem) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *ApprovalListItem) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ApprovalListItem) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetProjectName

`func (o *ApprovalListItem) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *ApprovalListItem) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *ApprovalListItem) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### SetProjectNameNil

`func (o *ApprovalListItem) SetProjectNameNil(b bool)`

 SetProjectNameNil sets the value for ProjectName to be an explicit nil

### UnsetProjectName
`func (o *ApprovalListItem) UnsetProjectName()`

UnsetProjectName ensures that no value is present for ProjectName, not even an explicit nil
### GetRequiredActor

`func (o *ApprovalListItem) GetRequiredActor() string`

GetRequiredActor returns the RequiredActor field if non-nil, zero value otherwise.

### GetRequiredActorOk

`func (o *ApprovalListItem) GetRequiredActorOk() (*string, bool)`

GetRequiredActorOk returns a tuple with the RequiredActor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredActor

`func (o *ApprovalListItem) SetRequiredActor(v string)`

SetRequiredActor sets RequiredActor field to given value.


### GetResultingAction

`func (o *ApprovalListItem) GetResultingAction() interface{}`

GetResultingAction returns the ResultingAction field if non-nil, zero value otherwise.

### GetResultingActionOk

`func (o *ApprovalListItem) GetResultingActionOk() (*interface{}, bool)`

GetResultingActionOk returns a tuple with the ResultingAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingAction

`func (o *ApprovalListItem) SetResultingAction(v interface{})`

SetResultingAction sets ResultingAction field to given value.


### SetResultingActionNil

`func (o *ApprovalListItem) SetResultingActionNil(b bool)`

 SetResultingActionNil sets the value for ResultingAction to be an explicit nil

### UnsetResultingAction
`func (o *ApprovalListItem) UnsetResultingAction()`

UnsetResultingAction ensures that no value is present for ResultingAction, not even an explicit nil
### GetStatus

`func (o *ApprovalListItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ApprovalListItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ApprovalListItem) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *ApprovalListItem) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *ApprovalListItem) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *ApprovalListItem) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *ApprovalListItem) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *ApprovalListItem) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTitle

`func (o *ApprovalListItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ApprovalListItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ApprovalListItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *ApprovalListItem) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ApprovalListItem) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ApprovalListItem) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


