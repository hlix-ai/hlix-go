# CreateClientAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillingEmail** | Pointer to **NullableString** |  | [optional] 
**Branding** | Pointer to **map[string]string** |  | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | **string** |  | 
**LegalName** | Pointer to **NullableString** |  | [optional] 
**PortalSlug** | **string** |  | 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateClientAccount

`func NewCreateClientAccount(displayName string, portalSlug string, ) *CreateClientAccount`

NewCreateClientAccount instantiates a new CreateClientAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateClientAccountWithDefaults

`func NewCreateClientAccountWithDefaults() *CreateClientAccount`

NewCreateClientAccountWithDefaults instantiates a new CreateClientAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBillingEmail

`func (o *CreateClientAccount) GetBillingEmail() string`

GetBillingEmail returns the BillingEmail field if non-nil, zero value otherwise.

### GetBillingEmailOk

`func (o *CreateClientAccount) GetBillingEmailOk() (*string, bool)`

GetBillingEmailOk returns a tuple with the BillingEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingEmail

`func (o *CreateClientAccount) SetBillingEmail(v string)`

SetBillingEmail sets BillingEmail field to given value.

### HasBillingEmail

`func (o *CreateClientAccount) HasBillingEmail() bool`

HasBillingEmail returns a boolean if a field has been set.

### SetBillingEmailNil

`func (o *CreateClientAccount) SetBillingEmailNil(b bool)`

 SetBillingEmailNil sets the value for BillingEmail to be an explicit nil

### UnsetBillingEmail
`func (o *CreateClientAccount) UnsetBillingEmail()`

UnsetBillingEmail ensures that no value is present for BillingEmail, not even an explicit nil
### GetBranding

`func (o *CreateClientAccount) GetBranding() map[string]string`

GetBranding returns the Branding field if non-nil, zero value otherwise.

### GetBrandingOk

`func (o *CreateClientAccount) GetBrandingOk() (*map[string]string, bool)`

GetBrandingOk returns a tuple with the Branding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranding

`func (o *CreateClientAccount) SetBranding(v map[string]string)`

SetBranding sets Branding field to given value.

### HasBranding

`func (o *CreateClientAccount) HasBranding() bool`

HasBranding returns a boolean if a field has been set.

### GetCurrency

`func (o *CreateClientAccount) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateClientAccount) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateClientAccount) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateClientAccount) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateClientAccount) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateClientAccount) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDisplayName

`func (o *CreateClientAccount) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *CreateClientAccount) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *CreateClientAccount) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetLegalName

`func (o *CreateClientAccount) GetLegalName() string`

GetLegalName returns the LegalName field if non-nil, zero value otherwise.

### GetLegalNameOk

`func (o *CreateClientAccount) GetLegalNameOk() (*string, bool)`

GetLegalNameOk returns a tuple with the LegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalName

`func (o *CreateClientAccount) SetLegalName(v string)`

SetLegalName sets LegalName field to given value.

### HasLegalName

`func (o *CreateClientAccount) HasLegalName() bool`

HasLegalName returns a boolean if a field has been set.

### SetLegalNameNil

`func (o *CreateClientAccount) SetLegalNameNil(b bool)`

 SetLegalNameNil sets the value for LegalName to be an explicit nil

### UnsetLegalName
`func (o *CreateClientAccount) UnsetLegalName()`

UnsetLegalName ensures that no value is present for LegalName, not even an explicit nil
### GetPortalSlug

`func (o *CreateClientAccount) GetPortalSlug() string`

GetPortalSlug returns the PortalSlug field if non-nil, zero value otherwise.

### GetPortalSlugOk

`func (o *CreateClientAccount) GetPortalSlugOk() (*string, bool)`

GetPortalSlugOk returns a tuple with the PortalSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortalSlug

`func (o *CreateClientAccount) SetPortalSlug(v string)`

SetPortalSlug sets PortalSlug field to given value.


### GetStatus

`func (o *CreateClientAccount) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateClientAccount) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateClientAccount) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateClientAccount) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


