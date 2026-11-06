# ImportMcp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Args** | Pointer to **[]string** |  | [optional] 
**Command** | Pointer to **string** |  | [optional] 
**EnvKeys** | Pointer to **[]string** |  | [optional] 
**Headers** | Pointer to **map[string]string** |  | [optional] 
**Name** | **string** |  | 
**Transport** | **string** |  | 
**Url** | Pointer to **string** |  | [optional] 

## Methods

### NewImportMcp

`func NewImportMcp(name string, transport string, ) *ImportMcp`

NewImportMcp instantiates a new ImportMcp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImportMcpWithDefaults

`func NewImportMcpWithDefaults() *ImportMcp`

NewImportMcpWithDefaults instantiates a new ImportMcp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArgs

`func (o *ImportMcp) GetArgs() []string`

GetArgs returns the Args field if non-nil, zero value otherwise.

### GetArgsOk

`func (o *ImportMcp) GetArgsOk() (*[]string, bool)`

GetArgsOk returns a tuple with the Args field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArgs

`func (o *ImportMcp) SetArgs(v []string)`

SetArgs sets Args field to given value.

### HasArgs

`func (o *ImportMcp) HasArgs() bool`

HasArgs returns a boolean if a field has been set.

### GetCommand

`func (o *ImportMcp) GetCommand() string`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *ImportMcp) GetCommandOk() (*string, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *ImportMcp) SetCommand(v string)`

SetCommand sets Command field to given value.

### HasCommand

`func (o *ImportMcp) HasCommand() bool`

HasCommand returns a boolean if a field has been set.

### GetEnvKeys

`func (o *ImportMcp) GetEnvKeys() []string`

GetEnvKeys returns the EnvKeys field if non-nil, zero value otherwise.

### GetEnvKeysOk

`func (o *ImportMcp) GetEnvKeysOk() (*[]string, bool)`

GetEnvKeysOk returns a tuple with the EnvKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvKeys

`func (o *ImportMcp) SetEnvKeys(v []string)`

SetEnvKeys sets EnvKeys field to given value.

### HasEnvKeys

`func (o *ImportMcp) HasEnvKeys() bool`

HasEnvKeys returns a boolean if a field has been set.

### GetHeaders

`func (o *ImportMcp) GetHeaders() map[string]string`

GetHeaders returns the Headers field if non-nil, zero value otherwise.

### GetHeadersOk

`func (o *ImportMcp) GetHeadersOk() (*map[string]string, bool)`

GetHeadersOk returns a tuple with the Headers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaders

`func (o *ImportMcp) SetHeaders(v map[string]string)`

SetHeaders sets Headers field to given value.

### HasHeaders

`func (o *ImportMcp) HasHeaders() bool`

HasHeaders returns a boolean if a field has been set.

### GetName

`func (o *ImportMcp) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ImportMcp) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ImportMcp) SetName(v string)`

SetName sets Name field to given value.


### GetTransport

`func (o *ImportMcp) GetTransport() string`

GetTransport returns the Transport field if non-nil, zero value otherwise.

### GetTransportOk

`func (o *ImportMcp) GetTransportOk() (*string, bool)`

GetTransportOk returns a tuple with the Transport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransport

`func (o *ImportMcp) SetTransport(v string)`

SetTransport sets Transport field to given value.


### GetUrl

`func (o *ImportMcp) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ImportMcp) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ImportMcp) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ImportMcp) HasUrl() bool`

HasUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


