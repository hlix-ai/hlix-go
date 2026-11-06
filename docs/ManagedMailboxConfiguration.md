# ManagedMailboxConfiguration

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Blockers** | **[]string** |  | 
**Configured** | **bool** |  | 
**GoogleSupported** | **bool** |  | 
**MicrosoftSupported** | **bool** |  | 
**WarmupAvailable** | **bool** |  | 

## Methods

### NewManagedMailboxConfiguration

`func NewManagedMailboxConfiguration(blockers []string, configured bool, googleSupported bool, microsoftSupported bool, warmupAvailable bool, ) *ManagedMailboxConfiguration`

NewManagedMailboxConfiguration instantiates a new ManagedMailboxConfiguration object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedMailboxConfigurationWithDefaults

`func NewManagedMailboxConfigurationWithDefaults() *ManagedMailboxConfiguration`

NewManagedMailboxConfigurationWithDefaults instantiates a new ManagedMailboxConfiguration object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


