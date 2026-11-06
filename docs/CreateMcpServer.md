# CreateMcpServer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Args** | Pointer to **[]string** |  | [optional] 
**Authentication** | Pointer to **string** |  | [optional] 
**Command** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Env** | Pointer to **map[string]string** |  | [optional] 
**Name** | **string** |  | 
**OauthClientId** | Pointer to **NullableString** |  | [optional] 
**OauthClientSecret** | Pointer to **NullableString** |  | [optional] 
**ProjectId** | Pointer to **NullableString** |  | [optional] 
**Transport** | **string** |  | 
**Url** | Pointer to [**NullableCreateMcpServerUrl**](CreateMcpServerUrl.md) |  | [optional] 

## Methods

### NewCreateMcpServer

`func NewCreateMcpServer(name string, transport string, ) *CreateMcpServer`

NewCreateMcpServer instantiates a new CreateMcpServer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateMcpServerWithDefaults

`func NewCreateMcpServerWithDefaults() *CreateMcpServer`

NewCreateMcpServerWithDefaults instantiates a new CreateMcpServer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArgs

`func (o *CreateMcpServer) GetArgs() []string`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *CreateMcpServer) GetArgsOk() (*[]string, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *CreateMcpServer) SetArgs(v []string)`

SetArgs sets Args field to given value.

### HasArgs

`func (o *CreateMcpServer) HasArgs() bool`

HasArgs returns a boolean if a field has been set.

### SetArgsNil

`func (o *CreateMcpServer) SetArgsNil(b bool)`

 SetArgsNil sets the value for Args to be an explicit nil

### UnsetArgs
`func (o *CreateMcpServer) UnsetArgs()`

UnsetArgs ensures that no value is present for Args, not even an explicit nil
### GetAuthentication

`func (o *CreateMcpServer) GetAuthentication() string`

GetAuthentication returns the Authentication field if non-nil, zero value otherwise.

### GetAuthenticationOk

`func (o *CreateMcpServer) GetAuthenticationOk() (*string, bool)`

GetAuthenticationOk returns a tuple with the Authentication field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthentication

`func (o *CreateMcpServer) SetAuthentication(v string)`

SetAuthentication sets Authentication field to given value.

### HasAuthentication

`func (o *CreateMcpServer) HasAuthentication() bool`

HasAuthentication returns a boolean if a field has been set.

### GetCommand

`func (o *CreateMcpServer) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *CreateMcpServer) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *CreateMcpServer) SetCommand(v string)`

SetCommand sets Command field to given value.

### HasCommand

`func (o *CreateMcpServer) HasCommand() bool`

HasCommand returns a boolean if a field has been set.

### SetCommandNil

`func (o *CreateMcpServer) SetCommandNil(b bool)`

 SetCommandNil sets the value for Command to be an explicit nil

### UnsetCommand
`func (o *CreateMcpServer) UnsetCommand()`

UnsetCommand ensures that no value is present for Command, not even an explicit nil
### GetDescription

`func (o *CreateMcpServer) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateMcpServer) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateMcpServer) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateMcpServer) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateMcpServer) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateMcpServer) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEnabled

`func (o *CreateMcpServer) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateMcpServer) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateMcpServer) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateMcpServer) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetEnv

`func (o *CreateMcpServer) GetEnv() map[string]string`

GetEnv returns the Env field if non-nil, zero value otherwise.

### GetEnvOk

`func (o *CreateMcpServer) GetEnvOk() (*map[string]string, bool)`

GetEnvOk returns a tuple with the Env field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnv

`func (o *CreateMcpServer) SetEnv(v map[string]string)`

SetEnv sets Env field to given value.

### HasEnv

`func (o *CreateMcpServer) HasEnv() bool`

HasEnv returns a boolean if a field has been set.

### SetEnvNil

`func (o *CreateMcpServer) SetEnvNil(b bool)`

 SetEnvNil sets the value for Env to be an explicit nil

### UnsetEnv
`func (o *CreateMcpServer) UnsetEnv()`

UnsetEnv ensures that no value is present for Env, not even an explicit nil
### GetName

`func (o *CreateMcpServer) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateMcpServer) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateMcpServer) SetName(v string)`

SetName sets Name field to given value.


### GetOauthClientId

`func (o *CreateMcpServer) GetOauthClientId() string`

GetOauthClientId returns the OauthClientId field if non-nil, zero value otherwise.

### GetOauthClientIdOk

`func (o *CreateMcpServer) GetOauthClientIdOk() (*string, bool)`

GetOauthClientIdOk returns a tuple with the OauthClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthClientId

`func (o *CreateMcpServer) SetOauthClientId(v string)`

SetOauthClientId sets OauthClientId field to given value.

### HasOauthClientId

`func (o *CreateMcpServer) HasOauthClientId() bool`

HasOauthClientId returns a boolean if a field has been set.

### SetOauthClientIdNil

`func (o *CreateMcpServer) SetOauthClientIdNil(b bool)`

 SetOauthClientIdNil sets the value for OauthClientId to be an explicit nil

### UnsetOauthClientId
`func (o *CreateMcpServer) UnsetOauthClientId()`

UnsetOauthClientId ensures that no value is present for OauthClientId, not even an explicit nil
### GetOauthClientSecret

`func (o *CreateMcpServer) GetOauthClientSecret() string`

GetOauthClientSecret returns the OauthClientSecret field if non-nil, zero value otherwise.

### GetOauthClientSecretOk

`func (o *CreateMcpServer) GetOauthClientSecretOk() (*string, bool)`

GetOauthClientSecretOk returns a tuple with the OauthClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthClientSecret

`func (o *CreateMcpServer) SetOauthClientSecret(v string)`

SetOauthClientSecret sets OauthClientSecret field to given value.

### HasOauthClientSecret

`func (o *CreateMcpServer) HasOauthClientSecret() bool`

HasOauthClientSecret returns a boolean if a field has been set.

### SetOauthClientSecretNil

`func (o *CreateMcpServer) SetOauthClientSecretNil(b bool)`

 SetOauthClientSecretNil sets the value for OauthClientSecret to be an explicit nil

### UnsetOauthClientSecret
`func (o *CreateMcpServer) UnsetOauthClientSecret()`

UnsetOauthClientSecret ensures that no value is present for OauthClientSecret, not even an explicit nil
### GetProjectId

`func (o *CreateMcpServer) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateMcpServer) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateMcpServer) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateMcpServer) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *CreateMcpServer) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *CreateMcpServer) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetTransport

`func (o *CreateMcpServer) GetTransport() string`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *CreateMcpServer) GetTransportOk() (*string, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *CreateMcpServer) SetTransport(v string)`

SetTransport sets Transport field to given value.


### GetUrl

`func (o *CreateMcpServer) GetUrl() CreateMcpServerUrl`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateMcpServer) GetUrlOk() (*CreateMcpServerUrl, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateMcpServer) SetUrl(v CreateMcpServerUrl)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CreateMcpServer) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *CreateMcpServer) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CreateMcpServer) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


