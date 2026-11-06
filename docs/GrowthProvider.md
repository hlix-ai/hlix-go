# GrowthProvider

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AcceptsKey** | **bool** |  | 
**ByokOnly** | **bool** |  | 
**Capabilities** | **[]string** |  | 
**EuHosted** | [**GrowthProviderEuHosted**](GrowthProviderEuHosted.md) |  | 
**HlixKeyConfigured** | **bool** |  | 
**ManagedAvailable** | **bool** |  | 
**ManagedUnavailableReason** | **NullableString** |  | 
**OptionalSettings** | **[]string** |  | 
**Organization** | [**NullableGrowthProviderOrganization**](GrowthProviderOrganization.md) |  | 
**PersonalData** | **bool** |  | 
**Provider** | **string** |  | 
**RequiredSettings** | **[]string** |  | 
**Risk** | **string** |  | 
**UnitPriceMicros** | **map[string]int64** |  | 

## Methods

### NewGrowthProvider

`func NewGrowthProvider(acceptsKey bool, byokOnly bool, capabilities []string, euHosted GrowthProviderEuHosted, hlixKeyConfigured bool, managedAvailable bool, managedUnavailableReason NullableString, optionalSettings []string, organization NullableGrowthProviderOrganization, personalData bool, provider string, requiredSettings []string, risk string, unitPriceMicros map[string]int64, ) *GrowthProvider`

NewGrowthProvider instantiates a new GrowthProvider object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGrowthProviderWithDefaults

`func NewGrowthProviderWithDefaults() *GrowthProvider`

NewGrowthProviderWithDefaults instantiates a new GrowthProvider object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAcceptsKey

`func (o *GrowthProvider) GetAcceptsKey() bool`

GetAcceptsKey returns the AcceptsKey field if non-nil, zero value otherwise.

### GetAcceptsKeyOk

`func (o *GrowthProvider) GetAcceptsKeyOk() (*bool, bool)`

GetAcceptsKeyOk returns a tuple with the AcceptsKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptsKey

`func (o *GrowthProvider) SetAcceptsKey(v bool)`

SetAcceptsKey sets AcceptsKey field to given value.


### GetByokOnly

`func (o *GrowthProvider) GetByokOnly() bool`

GetByokOnly returns the ByokOnly field if non-nil, zero value otherwise.

### GetByokOnlyOk

`func (o *GrowthProvider) GetByokOnlyOk() (*bool, bool)`

GetByokOnlyOk returns a tuple with the ByokOnly field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByokOnly

`func (o *GrowthProvider) SetByokOnly(v bool)`

SetByokOnly sets ByokOnly field to given value.


### GetCapabilities

`func (o *GrowthProvider) GetCapabilities() []string`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *GrowthProvider) GetCapabilitiesOk() (*[]string, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *GrowthProvider) SetCapabilities(v []string)`

SetCapabilities sets Capabilities field to given value.


### GetEuHosted

`func (o *GrowthProvider) GetEuHosted() GrowthProviderEuHosted`

GetEuHosted returns the EuHosted field if non-nil, zero value otherwise.

### GetEuHostedOk

`func (o *GrowthProvider) GetEuHostedOk() (*GrowthProviderEuHosted, bool)`

GetEuHostedOk returns a tuple with the EuHosted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEuHosted

`func (o *GrowthProvider) SetEuHosted(v GrowthProviderEuHosted)`

SetEuHosted sets EuHosted field to given value.


### GetHlixKeyConfigured

`func (o *GrowthProvider) GetHlixKeyConfigured() bool`

GetHlixKeyConfigured returns the HlixKeyConfigured field if non-nil, zero value otherwise.

### GetHlixKeyConfiguredOk

`func (o *GrowthProvider) GetHlixKeyConfiguredOk() (*bool, bool)`

GetHlixKeyConfiguredOk returns a tuple with the HlixKeyConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHlixKeyConfigured

`func (o *GrowthProvider) SetHlixKeyConfigured(v bool)`

SetHlixKeyConfigured sets HlixKeyConfigured field to given value.


### GetManagedAvailable

`func (o *GrowthProvider) GetManagedAvailable() bool`

GetManagedAvailable returns the ManagedAvailable field if non-nil, zero value otherwise.

### GetManagedAvailableOk

`func (o *GrowthProvider) GetManagedAvailableOk() (*bool, bool)`

GetManagedAvailableOk returns a tuple with the ManagedAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedAvailable

`func (o *GrowthProvider) SetManagedAvailable(v bool)`

SetManagedAvailable sets ManagedAvailable field to given value.


### GetManagedUnavailableReason

`func (o *GrowthProvider) GetManagedUnavailableReason() string`

GetManagedUnavailableReason returns the ManagedUnavailableReason field if non-nil, zero value otherwise.

### GetManagedUnavailableReasonOk

`func (o *GrowthProvider) GetManagedUnavailableReasonOk() (*string, bool)`

GetManagedUnavailableReasonOk returns a tuple with the ManagedUnavailableReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUnavailableReason

`func (o *GrowthProvider) SetManagedUnavailableReason(v string)`

SetManagedUnavailableReason sets ManagedUnavailableReason field to given value.


### SetManagedUnavailableReasonNil

`func (o *GrowthProvider) SetManagedUnavailableReasonNil(b bool)`

 SetManagedUnavailableReasonNil sets the value for ManagedUnavailableReason to be an explicit nil

### UnsetManagedUnavailableReason
`func (o *GrowthProvider) UnsetManagedUnavailableReason()`

UnsetManagedUnavailableReason ensures that no value is present for ManagedUnavailableReason, not even an explicit nil
### GetOptionalSettings

`func (o *GrowthProvider) GetOptionalSettings() []string`

GetOptionalSettings returns the OptionalSettings field if non-nil, zero value otherwise.

### GetOptionalSettingsOk

`func (o *GrowthProvider) GetOptionalSettingsOk() (*[]string, bool)`

GetOptionalSettingsOk returns a tuple with the OptionalSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptionalSettings

`func (o *GrowthProvider) SetOptionalSettings(v []string)`

SetOptionalSettings sets OptionalSettings field to given value.


### GetOrganization

`func (o *GrowthProvider) GetOrganization() GrowthProviderOrganization`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *GrowthProvider) GetOrganizationOk() (*GrowthProviderOrganization, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *GrowthProvider) SetOrganization(v GrowthProviderOrganization)`

SetOrganization sets Organization field to given value.


### SetOrganizationNil

`func (o *GrowthProvider) SetOrganizationNil(b bool)`

 SetOrganizationNil sets the value for Organization to be an explicit nil

### UnsetOrganization
`func (o *GrowthProvider) UnsetOrganization()`

UnsetOrganization ensures that no value is present for Organization, not even an explicit nil
### GetPersonalData

`func (o *GrowthProvider) GetPersonalData() bool`

GetPersonalData returns the PersonalData field if non-nil, zero value otherwise.

### GetPersonalDataOk

`func (o *GrowthProvider) GetPersonalDataOk() (*bool, bool)`

GetPersonalDataOk returns a tuple with the PersonalData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonalData

`func (o *GrowthProvider) SetPersonalData(v bool)`

SetPersonalData sets PersonalData field to given value.


### GetProvider

`func (o *GrowthProvider) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *GrowthProvider) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *GrowthProvider) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetRequiredSettings

`func (o *GrowthProvider) GetRequiredSettings() []string`

GetRequiredSettings returns the RequiredSettings field if non-nil, zero value otherwise.

### GetRequiredSettingsOk

`func (o *GrowthProvider) GetRequiredSettingsOk() (*[]string, bool)`

GetRequiredSettingsOk returns a tuple with the RequiredSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredSettings

`func (o *GrowthProvider) SetRequiredSettings(v []string)`

SetRequiredSettings sets RequiredSettings field to given value.


### GetRisk

`func (o *GrowthProvider) GetRisk() string`

GetRisk returns the Risk field if non-nil, zero value otherwise.

### GetRiskOk

`func (o *GrowthProvider) GetRiskOk() (*string, bool)`

GetRiskOk returns a tuple with the Risk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRisk

`func (o *GrowthProvider) SetRisk(v string)`

SetRisk sets Risk field to given value.


### GetUnitPriceMicros

`func (o *GrowthProvider) GetUnitPriceMicros() map[string]int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *GrowthProvider) GetUnitPriceMicrosOk() (*map[string]int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *GrowthProvider) SetUnitPriceMicros(v map[string]int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


