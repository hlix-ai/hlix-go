# ManagedMailboxConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Blockers** | **[]string** |  |
**Configured** | **bool** |  |
**ConnectionBlockers** | Pointer to **[]string** |  | [optional]
**ConnectionConfigured** | Pointer to **bool** |  | [optional]
**GoogleSupported** | **bool** |  | [default to true]
**ImportAvailable** | Pointer to **bool** |  | [optional]
**MicrosoftSupported** | **bool** |  | [default to false]
**WarmupAvailable** | **bool** |  |

## Methods

### NewManagedMailboxConfiguration

`func NewManagedMailboxConfiguration(blockers []string, configured bool, googleSupported bool, microsoftSupported bool, warmupAvailable bool, ) *ManagedMailboxConfiguration`

NewManagedMailboxConfiguration instantiates a new ManagedMailboxConfiguration object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewManagedMailboxConfigurationWithDefaults

`func NewManagedMailboxConfigurationWithDefaults() *ManagedMailboxConfiguration`

NewManagedMailboxConfigurationWithDefaults instantiates a new ManagedMailboxConfiguration object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBlockers

`func (o *ManagedMailboxConfiguration) GetBlockers() []string`

GetBlockers returns the Blockers field if non-nil, zero value otherwise.

### GetBlockersOk

`func (o *ManagedMailboxConfiguration) GetBlockersOk() (*[]string, bool)`

GetBlockersOk returns a tuple with the Blockers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockers

`func (o *ManagedMailboxConfiguration) SetBlockers(v []string)`

SetBlockers sets Blockers field to given value.


### GetConfigured

`func (o *ManagedMailboxConfiguration) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *ManagedMailboxConfiguration) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *ManagedMailboxConfiguration) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetConnectionBlockers

`func (o *ManagedMailboxConfiguration) GetConnectionBlockers() []string`

GetConnectionBlockers returns the ConnectionBlockers field if non-nil, zero value otherwise.

### GetConnectionBlockersOk

`func (o *ManagedMailboxConfiguration) GetConnectionBlockersOk() (*[]string, bool)`

GetConnectionBlockersOk returns a tuple with the ConnectionBlockers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionBlockers

`func (o *ManagedMailboxConfiguration) SetConnectionBlockers(v []string)`

SetConnectionBlockers sets ConnectionBlockers field to given value.

### HasConnectionBlockers

`func (o *ManagedMailboxConfiguration) HasConnectionBlockers() bool`

HasConnectionBlockers returns a boolean if a field has been set.

### GetConnectionConfigured

`func (o *ManagedMailboxConfiguration) GetConnectionConfigured() bool`

GetConnectionConfigured returns the ConnectionConfigured field if non-nil, zero value otherwise.

### GetConnectionConfiguredOk

`func (o *ManagedMailboxConfiguration) GetConnectionConfiguredOk() (*bool, bool)`

GetConnectionConfiguredOk returns a tuple with the ConnectionConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionConfigured

`func (o *ManagedMailboxConfiguration) SetConnectionConfigured(v bool)`

SetConnectionConfigured sets ConnectionConfigured field to given value.

### HasConnectionConfigured

`func (o *ManagedMailboxConfiguration) HasConnectionConfigured() bool`

HasConnectionConfigured returns a boolean if a field has been set.

### GetGoogleSupported

`func (o *ManagedMailboxConfiguration) GetGoogleSupported() bool`

GetGoogleSupported returns the GoogleSupported field if non-nil, zero value otherwise.

### GetGoogleSupportedOk

`func (o *ManagedMailboxConfiguration) GetGoogleSupportedOk() (*bool, bool)`

GetGoogleSupportedOk returns a tuple with the GoogleSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoogleSupported

`func (o *ManagedMailboxConfiguration) SetGoogleSupported(v bool)`

SetGoogleSupported sets GoogleSupported field to given value.


### GetImportAvailable

`func (o *ManagedMailboxConfiguration) GetImportAvailable() bool`

GetImportAvailable returns the ImportAvailable field if non-nil, zero value otherwise.

### GetImportAvailableOk

`func (o *ManagedMailboxConfiguration) GetImportAvailableOk() (*bool, bool)`

GetImportAvailableOk returns a tuple with the ImportAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportAvailable

`func (o *ManagedMailboxConfiguration) SetImportAvailable(v bool)`

SetImportAvailable sets ImportAvailable field to given value.

### HasImportAvailable

`func (o *ManagedMailboxConfiguration) HasImportAvailable() bool`

HasImportAvailable returns a boolean if a field has been set.

### GetMicrosoftSupported

`func (o *ManagedMailboxConfiguration) GetMicrosoftSupported() bool`

GetMicrosoftSupported returns the MicrosoftSupported field if non-nil, zero value otherwise.

### GetMicrosoftSupportedOk

`func (o *ManagedMailboxConfiguration) GetMicrosoftSupportedOk() (*bool, bool)`

GetMicrosoftSupportedOk returns a tuple with the MicrosoftSupported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMicrosoftSupported

`func (o *ManagedMailboxConfiguration) SetMicrosoftSupported(v bool)`

SetMicrosoftSupported sets MicrosoftSupported field to given value.


### GetWarmupAvailable

`func (o *ManagedMailboxConfiguration) GetWarmupAvailable() bool`

GetWarmupAvailable returns the WarmupAvailable field if non-nil, zero value otherwise.

### GetWarmupAvailableOk

`func (o *ManagedMailboxConfiguration) GetWarmupAvailableOk() (*bool, bool)`

GetWarmupAvailableOk returns a tuple with the WarmupAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarmupAvailable

`func (o *ManagedMailboxConfiguration) SetWarmupAvailable(v bool)`

SetWarmupAvailable sets WarmupAvailable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


