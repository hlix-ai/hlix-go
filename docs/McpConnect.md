# McpConnect

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthorizationUrl** | **NullableString** |  |
**Server** | [**McpConnectServer**](McpConnectServer.md) |  |

## Methods

### NewMcpConnect

`func NewMcpConnect(authorizationUrl NullableString, server McpConnectServer, ) *McpConnect`

NewMcpConnect instantiates a new McpConnect object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMcpConnectWithDefaults

`func NewMcpConnectWithDefaults() *McpConnect`

NewMcpConnectWithDefaults instantiates a new McpConnect object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAuthorizationUrl

`func (o *McpConnect) GetAuthorizationUrl() string`

GetAuthorizationUrl returns the AuthorizationUrl field if non-nil, zero value otherwise.

### GetAuthorizationUrlOk

`func (o *McpConnect) GetAuthorizationUrlOk() (*string, bool)`

GetAuthorizationUrlOk returns a tuple with the AuthorizationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizationUrl

`func (o *McpConnect) SetAuthorizationUrl(v string)`

SetAuthorizationUrl sets AuthorizationUrl field to given value.


### SetAuthorizationUrlNil

`func (o *McpConnect) SetAuthorizationUrlNil(b bool)`

 SetAuthorizationUrlNil sets the value for AuthorizationUrl to be an explicit nil

### UnsetAuthorizationUrl
`func (o *McpConnect) UnsetAuthorizationUrl()`

UnsetAuthorizationUrl ensures that no value is present for AuthorizationUrl, not even an explicit nil
### GetServer

`func (o *McpConnect) GetServer() McpConnectServer`

GetServer returns the Server field if non-nil, zero value otherwise.

### GetServerOk

`func (o *McpConnect) GetServerOk() (*McpConnectServer, bool)`

GetServerOk returns a tuple with the Server field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServer

`func (o *McpConnect) SetServer(v McpConnectServer)`

SetServer sets Server field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


