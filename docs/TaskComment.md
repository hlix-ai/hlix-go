# TaskComment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Author** | **NullableString** |  | 
**Body** | **string** |  | 
**CreatedAt** | **string** |  | 
**Id** | **string** |  | 
**Parts** | Pointer to [**[]ClientRequestDetailMessagesInnerPartsInner**](ClientRequestDetailMessagesInnerPartsInner.md) |  | [optional] 
**ReplyTo** | Pointer to **string** |  | [optional] 
**Role** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewTaskComment

`func NewTaskComment(author NullableString, body string, createdAt string, id string, role string, ) *TaskComment`

NewTaskComment instantiates a new TaskComment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskCommentWithDefaults

`func NewTaskCommentWithDefaults() *TaskComment`

NewTaskCommentWithDefaults instantiates a new TaskComment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthor

`func (o *TaskComment) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *TaskComment) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *TaskComment) SetAuthor(v string)`

SetAuthor sets Author field to given value.


### SetAuthorNil

`func (o *TaskComment) SetAuthorNil(b bool)`

 SetAuthorNil sets the value for Author to be an explicit nil

### UnsetAuthor
`func (o *TaskComment) UnsetAuthor()`

UnsetAuthor ensures that no value is present for Author, not even an explicit nil
### GetBody

`func (o *TaskComment) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *TaskComment) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *TaskComment) SetBody(v string)`

SetBody sets Body field to given value.


### GetCreatedAt

`func (o *TaskComment) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TaskComment) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TaskComment) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *TaskComment) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TaskComment) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TaskComment) SetId(v string)`

SetId sets Id field to given value.


### GetParts

`func (o *TaskComment) GetParts() []ClientRequestDetailMessagesInnerPartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *TaskComment) GetPartsOk() (*[]ClientRequestDetailMessagesInnerPartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *TaskComment) SetParts(v []ClientRequestDetailMessagesInnerPartsInner)`

SetParts sets Parts field to given value.

### HasParts

`func (o *TaskComment) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetReplyTo

`func (o *TaskComment) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *TaskComment) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *TaskComment) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *TaskComment) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### GetRole

`func (o *TaskComment) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *TaskComment) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *TaskComment) SetRole(v string)`

SetRole sets Role field to given value.


### GetStatus

`func (o *TaskComment) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TaskComment) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TaskComment) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TaskComment) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


