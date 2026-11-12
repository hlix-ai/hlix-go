# GrowthSendkitReadiness

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Blocker** | **string** |  |
**Configured** | **bool** |  |
**Connected** | **bool** |  |
**ExecutionReady** | **bool** |  | [default to false]
**Mailboxes** | [**[]GrowthSendkitReadinessMailboxesInner**](GrowthSendkitReadinessMailboxesInner.md) |  |
**WorkspaceName** | Pointer to **string** |  | [optional]

## Methods

### NewGrowthSendkitReadiness

`func NewGrowthSendkitReadiness(blocker string, configured bool, connected bool, executionReady bool, mailboxes []GrowthSendkitReadinessMailboxesInner, ) *GrowthSendkitReadiness`

NewGrowthSendkitReadiness instantiates a new GrowthSendkitReadiness object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthSendkitReadinessWithDefaults

`func NewGrowthSendkitReadinessWithDefaults() *GrowthSendkitReadiness`

NewGrowthSendkitReadinessWithDefaults instantiates a new GrowthSendkitReadiness object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBlocker

`func (o *GrowthSendkitReadiness) GetBlocker() string`

GetBlocker returns the Blocker field if non-nil, zero value otherwise.

### GetBlockerOk

`func (o *GrowthSendkitReadiness) GetBlockerOk() (*string, bool)`

GetBlockerOk returns a tuple with the Blocker field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocker

`func (o *GrowthSendkitReadiness) SetBlocker(v string)`

SetBlocker sets Blocker field to given value.


### GetConfigured

`func (o *GrowthSendkitReadiness) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *GrowthSendkitReadiness) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *GrowthSendkitReadiness) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetConnected

`func (o *GrowthSendkitReadiness) GetConnected() bool`

GetConnected returns the Connected field if non-nil, zero value otherwise.

### GetConnectedOk

`func (o *GrowthSendkitReadiness) GetConnectedOk() (*bool, bool)`

GetConnectedOk returns a tuple with the Connected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnected

`func (o *GrowthSendkitReadiness) SetConnected(v bool)`

SetConnected sets Connected field to given value.


### GetExecutionReady

`func (o *GrowthSendkitReadiness) GetExecutionReady() bool`

GetExecutionReady returns the ExecutionReady field if non-nil, zero value otherwise.

### GetExecutionReadyOk

`func (o *GrowthSendkitReadiness) GetExecutionReadyOk() (*bool, bool)`

GetExecutionReadyOk returns a tuple with the ExecutionReady field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExecutionReady

`func (o *GrowthSendkitReadiness) SetExecutionReady(v bool)`

SetExecutionReady sets ExecutionReady field to given value.


### GetMailboxes

`func (o *GrowthSendkitReadiness) GetMailboxes() []GrowthSendkitReadinessMailboxesInner`

GetMailboxes returns the Mailboxes field if non-nil, zero value otherwise.

### GetMailboxesOk

`func (o *GrowthSendkitReadiness) GetMailboxesOk() (*[]GrowthSendkitReadinessMailboxesInner, bool)`

GetMailboxesOk returns a tuple with the Mailboxes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMailboxes

`func (o *GrowthSendkitReadiness) SetMailboxes(v []GrowthSendkitReadinessMailboxesInner)`

SetMailboxes sets Mailboxes field to given value.


### GetWorkspaceName

`func (o *GrowthSendkitReadiness) GetWorkspaceName() string`

GetWorkspaceName returns the WorkspaceName field if non-nil, zero value otherwise.

### GetWorkspaceNameOk

`func (o *GrowthSendkitReadiness) GetWorkspaceNameOk() (*string, bool)`

GetWorkspaceNameOk returns a tuple with the WorkspaceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceName

`func (o *GrowthSendkitReadiness) SetWorkspaceName(v string)`

SetWorkspaceName sets WorkspaceName field to given value.

### HasWorkspaceName

`func (o *GrowthSendkitReadiness) HasWorkspaceName() bool`

HasWorkspaceName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


