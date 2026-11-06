# PortalIdentity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Brand** | [**PortalIdentityBrand**](PortalIdentityBrand.md) |  | 
**Href** | **string** |  | 
**Logo** | **NullableString** |  | 
**Name** | **string** |  | 
**Slug** | **string** |  | 

## Methods

### NewPortalIdentity

`func NewPortalIdentity(brand PortalIdentityBrand, href string, logo NullableString, name string, slug string, ) *PortalIdentity`

NewPortalIdentity instantiates a new PortalIdentity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortalIdentityWithDefaults

`func NewPortalIdentityWithDefaults() *PortalIdentity`

NewPortalIdentityWithDefaults instantiates a new PortalIdentity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBrand

`func (o *PortalIdentity) GetBrand() PortalIdentityBrand`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *PortalIdentity) GetBrandOk() (*PortalIdentityBrand, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *PortalIdentity) SetBrand(v PortalIdentityBrand)`

SetBrand sets Brand field to given value.


### GetHref

`func (o *PortalIdentity) GetHref() string`

GetHref returns the Href field if non-nil, zero value otherwise.

### GetHrefOk

`func (o *PortalIdentity) GetHrefOk() (*string, bool)`

GetHrefOk returns a tuple with the Href field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHref

`func (o *PortalIdentity) SetHref(v string)`

SetHref sets Href field to given value.


### GetLogo

`func (o *PortalIdentity) GetLogo() string`

GetLogo returns the Logo field if non-nil, zero value otherwise.

### GetLogoOk

`func (o *PortalIdentity) GetLogoOk() (*string, bool)`

GetLogoOk returns a tuple with the Logo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogo

`func (o *PortalIdentity) SetLogo(v string)`

SetLogo sets Logo field to given value.


### SetLogoNil

`func (o *PortalIdentity) SetLogoNil(b bool)`

 SetLogoNil sets the value for Logo to be an explicit nil

### UnsetLogo
`func (o *PortalIdentity) UnsetLogo()`

UnsetLogo ensures that no value is present for Logo, not even an explicit nil
### GetName

`func (o *PortalIdentity) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PortalIdentity) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PortalIdentity) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *PortalIdentity) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *PortalIdentity) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *PortalIdentity) SetSlug(v string)`

SetSlug sets Slug field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


