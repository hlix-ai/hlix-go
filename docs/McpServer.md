# McpServer

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

### NewMcpServer

`func NewMcpServer(args []string, authentication string, command NullableString, connection McpConnectServerConnection, createdAt string, description NullableString, enabled bool, env map[string]string, hasOauthClientSecret bool, id string, name string, oauthClientId NullableString, organizationId string, projectId NullableString, transport string, updatedAt string, url NullableString, ) *McpServer`

NewMcpServer instantiates a new McpServer object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMcpServerWithDefaults

`func NewMcpServerWithDefaults() *McpServer`

NewMcpServerWithDefaults instantiates a new McpServer object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetArgs

`func (o *McpServer) GetArgs() []string`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *McpServer) GetArgsOk() (*[]string, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *McpServer) SetArgs(v []string)`

SetArgs sets Args field to given value.


### SetArgsNil

`func (o *McpServer) SetArgsNil(b bool)`

 SetArgsNil sets the value for Args to be an explicit nil

### UnsetArgs
`func (o *McpServer) UnsetArgs()`

UnsetArgs ensures that no value is present for Args, not even an explicit nil
### GetAuthentication

`func (o *McpServer) GetAuthentication() string`

GetAuthentication returns the Authentication field if non-nil, zero value otherwise.

### GetAuthenticationOk

`func (o *McpServer) GetAuthenticationOk() (*string, bool)`

GetAuthenticationOk returns a tuple with the Authentication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthentication

`func (o *McpServer) SetAuthentication(v string)`

SetAuthentication sets Authentication field to given value.


### GetCommand

`func (o *McpServer) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *McpServer) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *McpServer) SetCommand(v string)`

SetCommand sets Command field to given value.


### SetCommandNil

`func (o *McpServer) SetCommandNil(b bool)`

 SetCommandNil sets the value for Command to be an explicit nil

### UnsetCommand
`func (o *McpServer) UnsetCommand()`

UnsetCommand ensures that no value is present for Command, not even an explicit nil
### GetConnection

`func (o *McpServer) GetConnection() McpConnectServerConnection`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *McpServer) GetConnectionOk() (*McpConnectServerConnection, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *McpServer) SetConnection(v McpConnectServerConnection)`

SetConnection sets Connection field to given value.


### GetCreatedAt

`func (o *McpServer) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *McpServer) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *McpServer) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *McpServer) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *McpServer) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *McpServer) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *McpServer) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *McpServer) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEnabled

`func (o *McpServer) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *McpServer) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *McpServer) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetEnv

`func (o *McpServer) GetEnv() map[string]string`

GetEnv returns the Env field if non-nil, zero value otherwise.

### GetEnvOk

`func (o *McpServer) GetEnvOk() (*map[string]string, bool)`

GetEnvOk returns a tuple with the Env field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnv

`func (o *McpServer) SetEnv(v map[string]string)`

SetEnv sets Env field to given value.


### SetEnvNil

`func (o *McpServer) SetEnvNil(b bool)`

 SetEnvNil sets the value for Env to be an explicit nil

### UnsetEnv
`func (o *McpServer) UnsetEnv()`

UnsetEnv ensures that no value is present for Env, not even an explicit nil
### GetHasOauthClientSecret

`func (o *McpServer) GetHasOauthClientSecret() bool`

GetHasOauthClientSecret returns the HasOauthClientSecret field if non-nil, zero value otherwise.

### GetHasOauthClientSecretOk

`func (o *McpServer) GetHasOauthClientSecretOk() (*bool, bool)`

GetHasOauthClientSecretOk returns a tuple with the HasOauthClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasOauthClientSecret

`func (o *McpServer) SetHasOauthClientSecret(v bool)`

SetHasOauthClientSecret sets HasOauthClientSecret field to given value.


### GetId

`func (o *McpServer) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *McpServer) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *McpServer) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *McpServer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *McpServer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *McpServer) SetName(v string)`

SetName sets Name field to given value.


### GetOauthClientId

`func (o *McpServer) GetOauthClientId() string`

GetOauthClientId returns the OauthClientId field if non-nil, zero value otherwise.

### GetOauthClientIdOk

`func (o *McpServer) GetOauthClientIdOk() (*string, bool)`

GetOauthClientIdOk returns a tuple with the OauthClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthClientId

`func (o *McpServer) SetOauthClientId(v string)`

SetOauthClientId sets OauthClientId field to given value.


### SetOauthClientIdNil

`func (o *McpServer) SetOauthClientIdNil(b bool)`

 SetOauthClientIdNil sets the value for OauthClientId to be an explicit nil

### UnsetOauthClientId
`func (o *McpServer) UnsetOauthClientId()`

UnsetOauthClientId ensures that no value is present for OauthClientId, not even an explicit nil
### GetOrganizationId

`func (o *McpServer) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *McpServer) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *McpServer) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *McpServer) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *McpServer) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *McpServer) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *McpServer) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *McpServer) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetTransport

`func (o *McpServer) GetTransport() string`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *McpServer) GetTransportOk() (*string, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *McpServer) SetTransport(v string)`

SetTransport sets Transport field to given value.


### GetUpdatedAt

`func (o *McpServer) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *McpServer) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *McpServer) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetUrl

`func (o *McpServer) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *McpServer) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *McpServer) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *McpServer) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *McpServer) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


