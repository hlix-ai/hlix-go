# AgencyBillingProfileState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Branded** | **bool** |  | 
**Profile** | [**NullableAgencyBillingProfileStateProfile**](AgencyBillingProfileStateProfile.md) |  | 

## Methods

### NewAgencyBillingProfileState

`func NewAgencyBillingProfileState(branded bool, profile NullableAgencyBillingProfileStateProfile, ) *AgencyBillingProfileState`

NewAgencyBillingProfileState instantiates a new AgencyBillingProfileState object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgencyBillingProfileStateWithDefaults

`func NewAgencyBillingProfileStateWithDefaults() *AgencyBillingProfileState`

NewAgencyBillingProfileStateWithDefaults instantiates a new AgencyBillingProfileState object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBranded

`func (o *AgencyBillingProfileState) GetBranded() bool`

GetBranded returns the Branded field if non-nil, zero value otherwise.

### GetBrandedOk

`func (o *AgencyBillingProfileState) GetBrandedOk() (*bool, bool)`

GetBrandedOk returns a tuple with the Branded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranded

`func (o *AgencyBillingProfileState) SetBranded(v bool)`

SetBranded sets Branded field to given value.


### GetProfile

`func (o *AgencyBillingProfileState) GetProfile() AgencyBillingProfileStateProfile`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *AgencyBillingProfileState) GetProfileOk() (*AgencyBillingProfileStateProfile, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *AgencyBillingProfileState) SetProfile(v AgencyBillingProfileStateProfile)`

SetProfile sets Profile field to given value.


### SetProfileNil

`func (o *AgencyBillingProfileState) SetProfileNil(b bool)`

 SetProfileNil sets the value for Profile to be an explicit nil

### UnsetProfile
`func (o *AgencyBillingProfileState) UnsetProfile()`

UnsetProfile ensures that no value is present for Profile, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


