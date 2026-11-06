# PortalIdentityBrand

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Colors** | [**InitialProposalDetailResponseRevisionContentBrandKitColors**](InitialProposalDetailResponseRevisionContentBrandKitColors.md) |  | 
**HeaderMode** | Pointer to **string** |  | [optional] 
**IconTone** | Pointer to **NullableString** |  | [optional] 
**IconUrl** | Pointer to **NullableString** |  | [optional] 
**LogoTone** | Pointer to **NullableString** |  | [optional] 
**LogoUrl** | **NullableString** |  | 
**Name** | **string** |  | 
**Tagline** | **NullableString** |  | 
**Typography** | [**InitialProposalDetailResponseRevisionContentBrandKitTypography**](InitialProposalDetailResponseRevisionContentBrandKitTypography.md) |  | 

## Methods

### NewPortalIdentityBrand

`func NewPortalIdentityBrand(colors InitialProposalDetailResponseRevisionContentBrandKitColors, logoUrl NullableString, name string, tagline NullableString, typography InitialProposalDetailResponseRevisionContentBrandKitTypography, ) *PortalIdentityBrand`

NewPortalIdentityBrand instantiates a new PortalIdentityBrand object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPortalIdentityBrandWithDefaults

`func NewPortalIdentityBrandWithDefaults() *PortalIdentityBrand`

NewPortalIdentityBrandWithDefaults instantiates a new PortalIdentityBrand object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColors

`func (o *PortalIdentityBrand) GetColors() InitialProposalDetailResponseRevisionContentBrandKitColors`

GetColors returns the Colors field if non-nil, zero value otherwise.

### GetColorsOk

`func (o *PortalIdentityBrand) GetColorsOk() (*InitialProposalDetailResponseRevisionContentBrandKitColors, bool)`

GetColorsOk returns a tuple with the Colors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColors

`func (o *PortalIdentityBrand) SetColors(v InitialProposalDetailResponseRevisionContentBrandKitColors)`

SetColors sets Colors field to given value.


### GetHeaderMode

`func (o *PortalIdentityBrand) GetHeaderMode() string`

GetHeaderMode returns the HeaderMode field if non-nil, zero value otherwise.

### GetHeaderModeOk

`func (o *PortalIdentityBrand) GetHeaderModeOk() (*string, bool)`

GetHeaderModeOk returns a tuple with the HeaderMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaderMode

`func (o *PortalIdentityBrand) SetHeaderMode(v string)`

SetHeaderMode sets HeaderMode field to given value.

### HasHeaderMode

`func (o *PortalIdentityBrand) HasHeaderMode() bool`

HasHeaderMode returns a boolean if a field has been set.

### GetIconTone

`func (o *PortalIdentityBrand) GetIconTone() string`

GetIconTone returns the IconTone field if non-nil, zero value otherwise.

### GetIconToneOk

`func (o *PortalIdentityBrand) GetIconToneOk() (*string, bool)`

GetIconToneOk returns a tuple with the IconTone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconTone

`func (o *PortalIdentityBrand) SetIconTone(v string)`

SetIconTone sets IconTone field to given value.

### HasIconTone

`func (o *PortalIdentityBrand) HasIconTone() bool`

HasIconTone returns a boolean if a field has been set.

### SetIconToneNil

`func (o *PortalIdentityBrand) SetIconToneNil(b bool)`

 SetIconToneNil sets the value for IconTone to be an explicit nil

### UnsetIconTone
`func (o *PortalIdentityBrand) UnsetIconTone()`

UnsetIconTone ensures that no value is present for IconTone, not even an explicit nil
### GetIconUrl

`func (o *PortalIdentityBrand) GetIconUrl() string`

GetIconUrl returns the IconUrl field if non-nil, zero value otherwise.

### GetIconUrlOk

`func (o *PortalIdentityBrand) GetIconUrlOk() (*string, bool)`

GetIconUrlOk returns a tuple with the IconUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconUrl

`func (o *PortalIdentityBrand) SetIconUrl(v string)`

SetIconUrl sets IconUrl field to given value.

### HasIconUrl

`func (o *PortalIdentityBrand) HasIconUrl() bool`

HasIconUrl returns a boolean if a field has been set.

### SetIconUrlNil

`func (o *PortalIdentityBrand) SetIconUrlNil(b bool)`

 SetIconUrlNil sets the value for IconUrl to be an explicit nil

### UnsetIconUrl
`func (o *PortalIdentityBrand) UnsetIconUrl()`

UnsetIconUrl ensures that no value is present for IconUrl, not even an explicit nil
### GetLogoTone

`func (o *PortalIdentityBrand) GetLogoTone() string`

GetLogoTone returns the LogoTone field if non-nil, zero value otherwise.

### GetLogoToneOk

`func (o *PortalIdentityBrand) GetLogoToneOk() (*string, bool)`

GetLogoToneOk returns a tuple with the LogoTone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoTone

`func (o *PortalIdentityBrand) SetLogoTone(v string)`

SetLogoTone sets LogoTone field to given value.

### HasLogoTone

`func (o *PortalIdentityBrand) HasLogoTone() bool`

HasLogoTone returns a boolean if a field has been set.

### SetLogoToneNil

`func (o *PortalIdentityBrand) SetLogoToneNil(b bool)`

 SetLogoToneNil sets the value for LogoTone to be an explicit nil

### UnsetLogoTone
`func (o *PortalIdentityBrand) UnsetLogoTone()`

UnsetLogoTone ensures that no value is present for LogoTone, not even an explicit nil
### GetLogoUrl

`func (o *PortalIdentityBrand) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *PortalIdentityBrand) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *PortalIdentityBrand) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.


### SetLogoUrlNil

`func (o *PortalIdentityBrand) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *PortalIdentityBrand) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetName

`func (o *PortalIdentityBrand) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PortalIdentityBrand) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PortalIdentityBrand) SetName(v string)`

SetName sets Name field to given value.


### GetTagline

`func (o *PortalIdentityBrand) GetTagline() string`

GetTagline returns the Tagline field if non-nil, zero value otherwise.

### GetTaglineOk

`func (o *PortalIdentityBrand) GetTaglineOk() (*string, bool)`

GetTaglineOk returns a tuple with the Tagline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagline

`func (o *PortalIdentityBrand) SetTagline(v string)`

SetTagline sets Tagline field to given value.


### SetTaglineNil

`func (o *PortalIdentityBrand) SetTaglineNil(b bool)`

 SetTaglineNil sets the value for Tagline to be an explicit nil

### UnsetTagline
`func (o *PortalIdentityBrand) UnsetTagline()`

UnsetTagline ensures that no value is present for Tagline, not even an explicit nil
### GetTypography

`func (o *PortalIdentityBrand) GetTypography() InitialProposalDetailResponseRevisionContentBrandKitTypography`

GetTypography returns the Typography field if non-nil, zero value otherwise.

### GetTypographyOk

`func (o *PortalIdentityBrand) GetTypographyOk() (*InitialProposalDetailResponseRevisionContentBrandKitTypography, bool)`

GetTypographyOk returns a tuple with the Typography field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypography

`func (o *PortalIdentityBrand) SetTypography(v InitialProposalDetailResponseRevisionContentBrandKitTypography)`

SetTypography sets Typography field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


