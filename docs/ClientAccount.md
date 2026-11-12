# ClientAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillingEmail** | **NullableString** |  |
**Branding** | **map[string]string** |  |
**CreatedAt** | **string** |  |
**Currency** | **NullableString** |  |
**DisplayName** | **string** |  |
**Id** | **string** |  |
**LegalName** | **NullableString** |  |
**OrganizationId** | **string** |  |
**PortalSlug** | **string** |  |
**Status** | **string** |  |
**UpdatedAt** | **string** |  |

## Methods

### NewClientAccount

`func NewClientAccount(billingEmail NullableString, branding map[string]string, createdAt string, currency NullableString, displayName string, id string, legalName NullableString, organizationId string, portalSlug string, status string, updatedAt string, ) *ClientAccount`

NewClientAccount instantiates a new ClientAccount object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientAccountWithDefaults

`func NewClientAccountWithDefaults() *ClientAccount`

NewClientAccountWithDefaults instantiates a new ClientAccount object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetBillingEmail

`func (o *ClientAccount) GetBillingEmail() string`

GetBillingEmail returns the BillingEmail field if non-nil, zero value otherwise.

### GetBillingEmailOk

`func (o *ClientAccount) GetBillingEmailOk() (*string, bool)`

GetBillingEmailOk returns a tuple with the BillingEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingEmail

`func (o *ClientAccount) SetBillingEmail(v string)`

SetBillingEmail sets BillingEmail field to given value.


### SetBillingEmailNil

`func (o *ClientAccount) SetBillingEmailNil(b bool)`

 SetBillingEmailNil sets the value for BillingEmail to be an explicit nil

### UnsetBillingEmail
`func (o *ClientAccount) UnsetBillingEmail()`

UnsetBillingEmail ensures that no value is present for BillingEmail, not even an explicit nil
### GetBranding

`func (o *ClientAccount) GetBranding() map[string]string`

GetBranding returns the Branding field if non-nil, zero value otherwise.

### GetBrandingOk

`func (o *ClientAccount) GetBrandingOk() (*map[string]string, bool)`

GetBrandingOk returns a tuple with the Branding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranding

`func (o *ClientAccount) SetBranding(v map[string]string)`

SetBranding sets Branding field to given value.


### GetCreatedAt

`func (o *ClientAccount) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientAccount) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientAccount) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrency

`func (o *ClientAccount) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ClientAccount) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ClientAccount) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### SetCurrencyNil

`func (o *ClientAccount) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ClientAccount) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetDisplayName

`func (o *ClientAccount) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *ClientAccount) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *ClientAccount) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetId

`func (o *ClientAccount) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientAccount) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientAccount) SetId(v string)`

SetId sets Id field to given value.


### GetLegalName

`func (o *ClientAccount) GetLegalName() string`

GetLegalName returns the LegalName field if non-nil, zero value otherwise.

### GetLegalNameOk

`func (o *ClientAccount) GetLegalNameOk() (*string, bool)`

GetLegalNameOk returns a tuple with the LegalName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLegalName

`func (o *ClientAccount) SetLegalName(v string)`

SetLegalName sets LegalName field to given value.


### SetLegalNameNil

`func (o *ClientAccount) SetLegalNameNil(b bool)`

 SetLegalNameNil sets the value for LegalName to be an explicit nil

### UnsetLegalName
`func (o *ClientAccount) UnsetLegalName()`

UnsetLegalName ensures that no value is present for LegalName, not even an explicit nil
### GetOrganizationId

`func (o *ClientAccount) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ClientAccount) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ClientAccount) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPortalSlug

`func (o *ClientAccount) GetPortalSlug() string`

GetPortalSlug returns the PortalSlug field if non-nil, zero value otherwise.

### GetPortalSlugOk

`func (o *ClientAccount) GetPortalSlugOk() (*string, bool)`

GetPortalSlugOk returns a tuple with the PortalSlug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPortalSlug

`func (o *ClientAccount) SetPortalSlug(v string)`

SetPortalSlug sets PortalSlug field to given value.


### GetStatus

`func (o *ClientAccount) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientAccount) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientAccount) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUpdatedAt

`func (o *ClientAccount) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ClientAccount) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ClientAccount) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


