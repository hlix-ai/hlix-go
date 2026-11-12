# McpConnectServer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Args** | **[]string** |  |
**Authentication** | **string** |  |
**Command** | **NullableString** |  |
**Connection** | [**McpConnectServerConnection**](McpConnectServerConnection.md) |  |
**CreatedAt** | **string** |  |
**Description** | **NullableString** |  |
**Enabled** | **bool** |  |
**Env** | **map[string]string** |  |
**HasOauthClientSecret** | **bool** |  |
**Id** | **string** |  |
**Name** | **string** |  |
**OauthClientId** | **NullableString** |  |
**OrganizationId** | **string** |  |
**ProjectId** | **NullableString** |  |
**Transport** | **string** |  |
**UpdatedAt** | **string** |  |
**Url** | **NullableString** |  |

## Methods

### NewMcpConnectServer

`func NewMcpConnectServer(args []string, authentication string, command NullableString, connection McpConnectServerConnection, createdAt string, description NullableString, enabled bool, env map[string]string, hasOauthClientSecret bool, id string, name string, oauthClientId NullableString, organizationId string, projectId NullableString, transport string, updatedAt string, url NullableString, ) *McpConnectServer`

NewMcpConnectServer instantiates a new McpConnectServer object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMcpConnectServerWithDefaults

`func NewMcpConnectServerWithDefaults() *McpConnectServer`

NewMcpConnectServerWithDefaults instantiates a new McpConnectServer object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetArgs

`func (o *McpConnectServer) GetArgs() []string`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *McpConnectServer) GetArgsOk() (*[]string, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *McpConnectServer) SetArgs(v []string)`

SetArgs sets Args field to given value.


### SetArgsNil

`func (o *McpConnectServer) SetArgsNil(b bool)`

 SetArgsNil sets the value for Args to be an explicit nil

### UnsetArgs
`func (o *McpConnectServer) UnsetArgs()`

UnsetArgs ensures that no value is present for Args, not even an explicit nil
### GetAuthentication

`func (o *McpConnectServer) GetAuthentication() string`

GetAuthentication returns the Authentication field if non-nil, zero value otherwise.

### GetAuthenticationOk

`func (o *McpConnectServer) GetAuthenticationOk() (*string, bool)`

GetAuthenticationOk returns a tuple with the Authentication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthentication

`func (o *McpConnectServer) SetAuthentication(v string)`

SetAuthentication sets Authentication field to given value.


### GetCommand

`func (o *McpConnectServer) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *McpConnectServer) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *McpConnectServer) SetCommand(v string)`

SetCommand sets Command field to given value.


### SetCommandNil

`func (o *McpConnectServer) SetCommandNil(b bool)`

 SetCommandNil sets the value for Command to be an explicit nil

### UnsetCommand
`func (o *McpConnectServer) UnsetCommand()`

UnsetCommand ensures that no value is present for Command, not even an explicit nil
### GetConnection

`func (o *McpConnectServer) GetConnection() McpConnectServerConnection`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *McpConnectServer) GetConnectionOk() (*McpConnectServerConnection, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *McpConnectServer) SetConnection(v McpConnectServerConnection)`

SetConnection sets Connection field to given value.


### GetCreatedAt

`func (o *McpConnectServer) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *McpConnectServer) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *McpConnectServer) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *McpConnectServer) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *McpConnectServer) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *McpConnectServer) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *McpConnectServer) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *McpConnectServer) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEnabled

`func (o *McpConnectServer) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *McpConnectServer) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *McpConnectServer) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetEnv

`func (o *McpConnectServer) GetEnv() map[string]string`

GetEnv returns the Env field if non-nil, zero value otherwise.

### GetEnvOk

`func (o *McpConnectServer) GetEnvOk() (*map[string]string, bool)`

GetEnvOk returns a tuple with the Env field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnv

`func (o *McpConnectServer) SetEnv(v map[string]string)`

SetEnv sets Env field to given value.


### SetEnvNil

`func (o *McpConnectServer) SetEnvNil(b bool)`

 SetEnvNil sets the value for Env to be an explicit nil

### UnsetEnv
`func (o *McpConnectServer) UnsetEnv()`

UnsetEnv ensures that no value is present for Env, not even an explicit nil
### GetHasOauthClientSecret

`func (o *McpConnectServer) GetHasOauthClientSecret() bool`

GetHasOauthClientSecret returns the HasOauthClientSecret field if non-nil, zero value otherwise.

### GetHasOauthClientSecretOk

`func (o *McpConnectServer) GetHasOauthClientSecretOk() (*bool, bool)`

GetHasOauthClientSecretOk returns a tuple with the HasOauthClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasOauthClientSecret

`func (o *McpConnectServer) SetHasOauthClientSecret(v bool)`

SetHasOauthClientSecret sets HasOauthClientSecret field to given value.


### GetId

`func (o *McpConnectServer) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *McpConnectServer) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *McpConnectServer) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *McpConnectServer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *McpConnectServer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *McpConnectServer) SetName(v string)`

SetName sets Name field to given value.


### GetOauthClientId

`func (o *McpConnectServer) GetOauthClientId() string`

GetOauthClientId returns the OauthClientId field if non-nil, zero value otherwise.

### GetOauthClientIdOk

`func (o *McpConnectServer) GetOauthClientIdOk() (*string, bool)`

GetOauthClientIdOk returns a tuple with the OauthClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthClientId

`func (o *McpConnectServer) SetOauthClientId(v string)`

SetOauthClientId sets OauthClientId field to given value.


### SetOauthClientIdNil

`func (o *McpConnectServer) SetOauthClientIdNil(b bool)`

 SetOauthClientIdNil sets the value for OauthClientId to be an explicit nil

### UnsetOauthClientId
`func (o *McpConnectServer) UnsetOauthClientId()`

UnsetOauthClientId ensures that no value is present for OauthClientId, not even an explicit nil
### GetOrganizationId

`func (o *McpConnectServer) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *McpConnectServer) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *McpConnectServer) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *McpConnectServer) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *McpConnectServer) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *McpConnectServer) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *McpConnectServer) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *McpConnectServer) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetTransport

`func (o *McpConnectServer) GetTransport() string`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *McpConnectServer) GetTransportOk() (*string, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *McpConnectServer) SetTransport(v string)`

SetTransport sets Transport field to given value.


### GetUpdatedAt

`func (o *McpConnectServer) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *McpConnectServer) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *McpConnectServer) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUrl

`func (o *McpConnectServer) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *McpConnectServer) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *McpConnectServer) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *McpConnectServer) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *McpConnectServer) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


