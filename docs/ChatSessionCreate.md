# ChatSessionCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AgentId** | Pointer to **string** |  | [optional] 
**Fork** | Pointer to [**ChatSessionCreateFork**](ChatSessionCreateFork.md) |  | [optional] 
**Private** | Pointer to **bool** |  | [optional] 
**ProjectId** | Pointer to **string** |  | [optional] 
**SessionId** | **string** |  | 

## Methods

### NewChatSessionCreate

`func NewChatSessionCreate(sessionId string, ) *ChatSessionCreate`

NewChatSessionCreate instantiates a new ChatSessionCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatSessionCreateWithDefaults

`func NewChatSessionCreateWithDefaults() *ChatSessionCreate`

NewChatSessionCreateWithDefaults instantiates a new ChatSessionCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAgentId

`func (o *ChatSessionCreate) GetAgentId() string`

GetAgentId returns the AgentId field if non-nil, zero value otherwise.

### GetAgentIdOk

`func (o *ChatSessionCreate) GetAgentIdOk() (*string, bool)`

GetAgentIdOk returns a tuple with the AgentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentId

`func (o *ChatSessionCreate) SetAgentId(v string)`

SetAgentId sets AgentId field to given value.

### HasAgentId

`func (o *ChatSessionCreate) HasAgentId() bool`

HasAgentId returns a boolean if a field has been set.

### GetFork

`func (o *ChatSessionCreate) GetFork() ChatSessionCreateFork`

GetFork returns the Fork field if non-nil, zero value otherwise.

### GetForkOk

`func (o *ChatSessionCreate) GetForkOk() (*ChatSessionCreateFork, bool)`

GetForkOk returns a tuple with the Fork field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFork

`func (o *ChatSessionCreate) SetFork(v ChatSessionCreateFork)`

SetFork sets Fork field to given value.

### HasFork

`func (o *ChatSessionCreate) HasFork() bool`

HasFork returns a boolean if a field has been set.

### GetPrivate

`func (o *ChatSessionCreate) GetPrivate() bool`

GetPrivate returns the Private field if non-nil, zero value otherwise.

### GetPrivateOk

`func (o *ChatSessionCreate) GetPrivateOk() (*bool, bool)`

GetPrivateOk returns a tuple with the Private field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivate

`func (o *ChatSessionCreate) SetPrivate(v bool)`

SetPrivate sets Private field to given value.

### HasPrivate

`func (o *ChatSessionCreate) HasPrivate() bool`

HasPrivate returns a boolean if a field has been set.

### GetProjectId

`func (o *ChatSessionCreate) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ChatSessionCreate) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ChatSessionCreate) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ChatSessionCreate) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSessionId

`func (o *ChatSessionCreate) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *ChatSessionCreate) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *ChatSessionCreate) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


