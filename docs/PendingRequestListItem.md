# PendingRequestListItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
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
**RequestType** | **string** |  | 
**RequiredActor** | **string** |  | 
**ResultingAction** | **interface{}** |  | 
**Status** | **string** |  | 
**TaskId** | **NullableString** |  | 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewPendingRequestListItem

`func NewPendingRequestListItem(blocking bool, context interface{}, createdAt string, cycleId NullableString, deadline NullableString, decidedAt NullableString, decidedBy NullableString, decision NullableString, description string, id string, organizationId string, projectId NullableString, projectName NullableString, requestType string, requiredActor string, resultingAction interface{}, status string, taskId NullableString, title string, updatedAt string, ) *PendingRequestListItem`

NewPendingRequestListItem instantiates a new PendingRequestListItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPendingRequestListItemWithDefaults

`func NewPendingRequestListItemWithDefaults() *PendingRequestListItem`

NewPendingRequestListItemWithDefaults instantiates a new PendingRequestListItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlocking

`func (o *PendingRequestListItem) GetBlocking() bool`

GetBlocking returns the Blocking field if non-nil, zero value otherwise.

### GetBlockingOk

`func (o *PendingRequestListItem) GetBlockingOk() (*bool, bool)`

GetBlockingOk returns a tuple with the Blocking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocking

`func (o *PendingRequestListItem) SetBlocking(v bool)`

SetBlocking sets Blocking field to given value.


### GetContext

`func (o *PendingRequestListItem) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *PendingRequestListItem) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *PendingRequestListItem) SetContext(v interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *PendingRequestListItem) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *PendingRequestListItem) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCreatedAt

`func (o *PendingRequestListItem) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PendingRequestListItem) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PendingRequestListItem) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *PendingRequestListItem) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *PendingRequestListItem) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *PendingRequestListItem) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *PendingRequestListItem) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *PendingRequestListItem) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDeadline

`func (o *PendingRequestListItem) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *PendingRequestListItem) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *PendingRequestListItem) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.


### SetDeadlineNil

`func (o *PendingRequestListItem) SetDeadlineNil(b bool)`

 SetDeadlineNil sets the value for Deadline to be an explicit nil

### UnsetDeadline
`func (o *PendingRequestListItem) UnsetDeadline()`

UnsetDeadline ensures that no value is present for Deadline, not even an explicit nil
### GetDecidedAt

`func (o *PendingRequestListItem) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *PendingRequestListItem) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *PendingRequestListItem) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *PendingRequestListItem) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *PendingRequestListItem) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *PendingRequestListItem) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *PendingRequestListItem) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *PendingRequestListItem) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *PendingRequestListItem) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *PendingRequestListItem) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDecision

`func (o *PendingRequestListItem) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *PendingRequestListItem) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *PendingRequestListItem) SetDecision(v string)`

SetDecision sets Decision field to given value.


### SetDecisionNil

`func (o *PendingRequestListItem) SetDecisionNil(b bool)`

 SetDecisionNil sets the value for Decision to be an explicit nil

### UnsetDecision
`func (o *PendingRequestListItem) UnsetDecision()`

UnsetDecision ensures that no value is present for Decision, not even an explicit nil
### GetDescription

`func (o *PendingRequestListItem) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PendingRequestListItem) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PendingRequestListItem) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *PendingRequestListItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PendingRequestListItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PendingRequestListItem) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *PendingRequestListItem) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *PendingRequestListItem) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *PendingRequestListItem) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *PendingRequestListItem) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *PendingRequestListItem) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *PendingRequestListItem) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *PendingRequestListItem) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *PendingRequestListItem) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetProjectName

`func (o *PendingRequestListItem) GetProjectName() string`

GetProjectName returns the ProjectName field if non-nil, zero value otherwise.

### GetProjectNameOk

`func (o *PendingRequestListItem) GetProjectNameOk() (*string, bool)`

GetProjectNameOk returns a tuple with the ProjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectName

`func (o *PendingRequestListItem) SetProjectName(v string)`

SetProjectName sets ProjectName field to given value.


### SetProjectNameNil

`func (o *PendingRequestListItem) SetProjectNameNil(b bool)`

 SetProjectNameNil sets the value for ProjectName to be an explicit nil

### UnsetProjectName
`func (o *PendingRequestListItem) UnsetProjectName()`

UnsetProjectName ensures that no value is present for ProjectName, not even an explicit nil
### GetRequestType

`func (o *PendingRequestListItem) GetRequestType() string`

GetRequestType returns the RequestType field if non-nil, zero value otherwise.

### GetRequestTypeOk

`func (o *PendingRequestListItem) GetRequestTypeOk() (*string, bool)`

GetRequestTypeOk returns a tuple with the RequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestType

`func (o *PendingRequestListItem) SetRequestType(v string)`

SetRequestType sets RequestType field to given value.


### GetRequiredActor

`func (o *PendingRequestListItem) GetRequiredActor() string`

GetRequiredActor returns the RequiredActor field if non-nil, zero value otherwise.

### GetRequiredActorOk

`func (o *PendingRequestListItem) GetRequiredActorOk() (*string, bool)`

GetRequiredActorOk returns a tuple with the RequiredActor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredActor

`func (o *PendingRequestListItem) SetRequiredActor(v string)`

SetRequiredActor sets RequiredActor field to given value.


### GetResultingAction

`func (o *PendingRequestListItem) GetResultingAction() interface{}`

GetResultingAction returns the ResultingAction field if non-nil, zero value otherwise.

### GetResultingActionOk

`func (o *PendingRequestListItem) GetResultingActionOk() (*interface{}, bool)`

GetResultingActionOk returns a tuple with the ResultingAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingAction

`func (o *PendingRequestListItem) SetResultingAction(v interface{})`

SetResultingAction sets ResultingAction field to given value.


### SetResultingActionNil

`func (o *PendingRequestListItem) SetResultingActionNil(b bool)`

 SetResultingActionNil sets the value for ResultingAction to be an explicit nil

### UnsetResultingAction
`func (o *PendingRequestListItem) UnsetResultingAction()`

UnsetResultingAction ensures that no value is present for ResultingAction, not even an explicit nil
### GetStatus

`func (o *PendingRequestListItem) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PendingRequestListItem) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PendingRequestListItem) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *PendingRequestListItem) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *PendingRequestListItem) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *PendingRequestListItem) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *PendingRequestListItem) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *PendingRequestListItem) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTitle

`func (o *PendingRequestListItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PendingRequestListItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PendingRequestListItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *PendingRequestListItem) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PendingRequestListItem) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PendingRequestListItem) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


