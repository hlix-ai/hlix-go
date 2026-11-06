# PendingRequest

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
**RequestType** | **string** |  | 
**RequiredActor** | **string** |  | 
**ResultingAction** | **interface{}** |  | 
**Status** | **string** |  | 
**TaskId** | **NullableString** |  | 
**Title** | **string** |  | 
**UpdatedAt** | **string** |  | 

## Methods

### NewPendingRequest

`func NewPendingRequest(blocking bool, context interface{}, createdAt string, cycleId NullableString, deadline NullableString, decidedAt NullableString, decidedBy NullableString, decision NullableString, description string, id string, organizationId string, requestType string, requiredActor string, resultingAction interface{}, status string, taskId NullableString, title string, updatedAt string, ) *PendingRequest`

NewPendingRequest instantiates a new PendingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPendingRequestWithDefaults

`func NewPendingRequestWithDefaults() *PendingRequest`

NewPendingRequestWithDefaults instantiates a new PendingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlocking

`func (o *PendingRequest) GetBlocking() bool`

GetBlocking returns the Blocking field if non-nil, zero value otherwise.

### GetBlockingOk

`func (o *PendingRequest) GetBlockingOk() (*bool, bool)`

GetBlockingOk returns a tuple with the Blocking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocking

`func (o *PendingRequest) SetBlocking(v bool)`

SetBlocking sets Blocking field to given value.


### GetContext

`func (o *PendingRequest) GetContext() interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *PendingRequest) GetContextOk() (*interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *PendingRequest) SetContext(v interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *PendingRequest) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *PendingRequest) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCreatedAt

`func (o *PendingRequest) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PendingRequest) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PendingRequest) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCycleId

`func (o *PendingRequest) GetCycleId() string`

GetCycleId returns the CycleId field if non-nil, zero value otherwise.

### GetCycleIdOk

`func (o *PendingRequest) GetCycleIdOk() (*string, bool)`

GetCycleIdOk returns a tuple with the CycleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleId

`func (o *PendingRequest) SetCycleId(v string)`

SetCycleId sets CycleId field to given value.


### SetCycleIdNil

`func (o *PendingRequest) SetCycleIdNil(b bool)`

 SetCycleIdNil sets the value for CycleId to be an explicit nil

### UnsetCycleId
`func (o *PendingRequest) UnsetCycleId()`

UnsetCycleId ensures that no value is present for CycleId, not even an explicit nil
### GetDeadline

`func (o *PendingRequest) GetDeadline() string`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *PendingRequest) GetDeadlineOk() (*string, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *PendingRequest) SetDeadline(v string)`

SetDeadline sets Deadline field to given value.


### SetDeadlineNil

`func (o *PendingRequest) SetDeadlineNil(b bool)`

 SetDeadlineNil sets the value for Deadline to be an explicit nil

### UnsetDeadline
`func (o *PendingRequest) UnsetDeadline()`

UnsetDeadline ensures that no value is present for Deadline, not even an explicit nil
### GetDecidedAt

`func (o *PendingRequest) GetDecidedAt() string`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *PendingRequest) GetDecidedAtOk() (*string, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *PendingRequest) SetDecidedAt(v string)`

SetDecidedAt sets DecidedAt field to given value.


### SetDecidedAtNil

`func (o *PendingRequest) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *PendingRequest) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetDecidedBy

`func (o *PendingRequest) GetDecidedBy() string`

GetDecidedBy returns the DecidedBy field if non-nil, zero value otherwise.

### GetDecidedByOk

`func (o *PendingRequest) GetDecidedByOk() (*string, bool)`

GetDecidedByOk returns a tuple with the DecidedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedBy

`func (o *PendingRequest) SetDecidedBy(v string)`

SetDecidedBy sets DecidedBy field to given value.


### SetDecidedByNil

`func (o *PendingRequest) SetDecidedByNil(b bool)`

 SetDecidedByNil sets the value for DecidedBy to be an explicit nil

### UnsetDecidedBy
`func (o *PendingRequest) UnsetDecidedBy()`

UnsetDecidedBy ensures that no value is present for DecidedBy, not even an explicit nil
### GetDecision

`func (o *PendingRequest) GetDecision() string`

GetDecision returns the Decision field if non-nil, zero value otherwise.

### GetDecisionOk

`func (o *PendingRequest) GetDecisionOk() (*string, bool)`

GetDecisionOk returns a tuple with the Decision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecision

`func (o *PendingRequest) SetDecision(v string)`

SetDecision sets Decision field to given value.


### SetDecisionNil

`func (o *PendingRequest) SetDecisionNil(b bool)`

 SetDecisionNil sets the value for Decision to be an explicit nil

### UnsetDecision
`func (o *PendingRequest) UnsetDecision()`

UnsetDecision ensures that no value is present for Decision, not even an explicit nil
### GetDescription

`func (o *PendingRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PendingRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PendingRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *PendingRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PendingRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PendingRequest) SetId(v string)`

SetId sets Id field to given value.


### GetOrganizationId

`func (o *PendingRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *PendingRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *PendingRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetRequestType

`func (o *PendingRequest) GetRequestType() string`

GetRequestType returns the RequestType field if non-nil, zero value otherwise.

### GetRequestTypeOk

`func (o *PendingRequest) GetRequestTypeOk() (*string, bool)`

GetRequestTypeOk returns a tuple with the RequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestType

`func (o *PendingRequest) SetRequestType(v string)`

SetRequestType sets RequestType field to given value.


### GetRequiredActor

`func (o *PendingRequest) GetRequiredActor() string`

GetRequiredActor returns the RequiredActor field if non-nil, zero value otherwise.

### GetRequiredActorOk

`func (o *PendingRequest) GetRequiredActorOk() (*string, bool)`

GetRequiredActorOk returns a tuple with the RequiredActor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredActor

`func (o *PendingRequest) SetRequiredActor(v string)`

SetRequiredActor sets RequiredActor field to given value.


### GetResultingAction

`func (o *PendingRequest) GetResultingAction() interface{}`

GetResultingAction returns the ResultingAction field if non-nil, zero value otherwise.

### GetResultingActionOk

`func (o *PendingRequest) GetResultingActionOk() (*interface{}, bool)`

GetResultingActionOk returns a tuple with the ResultingAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultingAction

`func (o *PendingRequest) SetResultingAction(v interface{})`

SetResultingAction sets ResultingAction field to given value.


### SetResultingActionNil

`func (o *PendingRequest) SetResultingActionNil(b bool)`

 SetResultingActionNil sets the value for ResultingAction to be an explicit nil

### UnsetResultingAction
`func (o *PendingRequest) UnsetResultingAction()`

UnsetResultingAction ensures that no value is present for ResultingAction, not even an explicit nil
### GetStatus

`func (o *PendingRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PendingRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PendingRequest) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetTaskId

`func (o *PendingRequest) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *PendingRequest) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *PendingRequest) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### SetTaskIdNil

`func (o *PendingRequest) SetTaskIdNil(b bool)`

 SetTaskIdNil sets the value for TaskId to be an explicit nil

### UnsetTaskId
`func (o *PendingRequest) UnsetTaskId()`

UnsetTaskId ensures that no value is present for TaskId, not even an explicit nil
### GetTitle

`func (o *PendingRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PendingRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PendingRequest) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *PendingRequest) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PendingRequest) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PendingRequest) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


