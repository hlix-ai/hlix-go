# MobileSession

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BuildId** | **string** |  |
**EndpointWebSocketUrl** | Pointer to **string** |  | [optional]
**ExpiresAt** | **string** |  |
**Id** | **string** |  |
**State** | **string** |  |
**StreamToken** | Pointer to **string** |  | [optional]

## Methods

### NewMobileSession

`func NewMobileSession(buildId string, expiresAt string, id string, state string, ) *MobileSession`

NewMobileSession instantiates a new MobileSession object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewMobileSessionWithDefaults

`func NewMobileSessionWithDefaults() *MobileSession`

NewMobileSessionWithDefaults instantiates a new MobileSession object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBuildId

`func (o *MobileSession) GetBuildId() string`

GetBuildId returns the BuildId field if non-nil, zero value otherwise.

### GetBuildIdOk

`func (o *MobileSession) GetBuildIdOk() (*string, bool)`

GetBuildIdOk returns a tuple with the BuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildId

`func (o *MobileSession) SetBuildId(v string)`

SetBuildId sets BuildId field to given value.


### GetEndpointWebSocketUrl

`func (o *MobileSession) GetEndpointWebSocketUrl() string`

GetEndpointWebSocketUrl returns the EndpointWebSocketUrl field if non-nil, zero value otherwise.

### GetEndpointWebSocketUrlOk

`func (o *MobileSession) GetEndpointWebSocketUrlOk() (*string, bool)`

GetEndpointWebSocketUrlOk returns a tuple with the EndpointWebSocketUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpointWebSocketUrl

`func (o *MobileSession) SetEndpointWebSocketUrl(v string)`

SetEndpointWebSocketUrl sets EndpointWebSocketUrl field to given value.

### HasEndpointWebSocketUrl

`func (o *MobileSession) HasEndpointWebSocketUrl() bool`

HasEndpointWebSocketUrl returns a boolean if a field has been set.

### GetExpiresAt

`func (o *MobileSession) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *MobileSession) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *MobileSession) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.


### GetId

`func (o *MobileSession) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MobileSession) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MobileSession) SetId(v string)`

SetId sets Id field to given value.


### GetState

`func (o *MobileSession) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *MobileSession) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *MobileSession) SetState(v string)`

SetState sets State field to given value.


### GetStreamToken

`func (o *MobileSession) GetStreamToken() string`

GetStreamToken returns the StreamToken field if non-nil, zero value otherwise.

### GetStreamTokenOk

`func (o *MobileSession) GetStreamTokenOk() (*string, bool)`

GetStreamTokenOk returns a tuple with the StreamToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreamToken

`func (o *MobileSession) SetStreamToken(v string)`

SetStreamToken sets StreamToken field to given value.

### HasStreamToken

`func (o *MobileSession) HasStreamToken() bool`

HasStreamToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


