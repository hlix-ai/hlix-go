# InitialProposalDetailResponseRevisionContentBrandKit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Colors** | [**InitialProposalDetailResponseRevisionContentBrandKitColors**](InitialProposalDetailResponseRevisionContentBrandKitColors.md) |  |
**Description** | **NullableString** |  |
**ExtractedAt** | **NullableTime** |  |
**HeaderMode** | Pointer to **string** |  | [optional]
**IconTone** | Pointer to **NullableString** |  | [optional]
**IconUrl** | Pointer to **NullableString** |  | [optional]
**LogoTone** | Pointer to **NullableString** |  | [optional]
**LogoUrl** | **NullableString** |  |
**Name** | **string** |  |
**Provenance** | Pointer to **map[string]string** |  | [optional]
**SourceUrl** | **NullableString** |  |
**Tagline** | **NullableString** |  |
**Typography** | [**InitialProposalDetailResponseRevisionContentBrandKitTypography**](InitialProposalDetailResponseRevisionContentBrandKitTypography.md) |  |
**Voice** | **NullableString** |  |
**Warnings** | **[]string** |  |

## Methods

### NewInitialProposalDetailResponseRevisionContentBrandKit

`func NewInitialProposalDetailResponseRevisionContentBrandKit(colors InitialProposalDetailResponseRevisionContentBrandKitColors, description NullableString, extractedAt NullableTime, logoUrl NullableString, name string, sourceUrl NullableString, tagline NullableString, typography InitialProposalDetailResponseRevisionContentBrandKitTypography, voice NullableString, warnings []string, ) *InitialProposalDetailResponseRevisionContentBrandKit`

NewInitialProposalDetailResponseRevisionContentBrandKit instantiates a new InitialProposalDetailResponseRevisionContentBrandKit object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewInitialProposalDetailResponseRevisionContentBrandKitWithDefaults

`func NewInitialProposalDetailResponseRevisionContentBrandKitWithDefaults() *InitialProposalDetailResponseRevisionContentBrandKit`

NewInitialProposalDetailResponseRevisionContentBrandKitWithDefaults instantiates a new InitialProposalDetailResponseRevisionContentBrandKit object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetColors

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetColors() InitialProposalDetailResponseRevisionContentBrandKitColors`

GetColors returns the Colors field if non-nil, zero value otherwise.

### GetColorsOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetColorsOk() (*InitialProposalDetailResponseRevisionContentBrandKitColors, bool)`

GetColorsOk returns a tuple with the Colors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColors

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetColors(v InitialProposalDetailResponseRevisionContentBrandKitColors)`

SetColors sets Colors field to given value.


### GetDescription

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExtractedAt

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetExtractedAt() time.Time`

GetExtractedAt returns the ExtractedAt field if non-nil, zero value otherwise.

### GetExtractedAtOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetExtractedAtOk() (*time.Time, bool)`

GetExtractedAtOk returns a tuple with the ExtractedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedAt

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetExtractedAt(v time.Time)`

SetExtractedAt sets ExtractedAt field to given value.


### SetExtractedAtNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetExtractedAtNil(b bool)`

 SetExtractedAtNil sets the value for ExtractedAt to be an explicit nil

### UnsetExtractedAt
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetExtractedAt()`

UnsetExtractedAt ensures that no value is present for ExtractedAt, not even an explicit nil
### GetHeaderMode

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetHeaderMode() string`

GetHeaderMode returns the HeaderMode field if non-nil, zero value otherwise.

### GetHeaderModeOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetHeaderModeOk() (*string, bool)`

GetHeaderModeOk returns a tuple with the HeaderMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaderMode

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetHeaderMode(v string)`

SetHeaderMode sets HeaderMode field to given value.

### HasHeaderMode

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) HasHeaderMode() bool`

HasHeaderMode returns a boolean if a field has been set.

### GetIconTone

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetIconTone() string`

GetIconTone returns the IconTone field if non-nil, zero value otherwise.

### GetIconToneOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetIconToneOk() (*string, bool)`

GetIconToneOk returns a tuple with the IconTone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconTone

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetIconTone(v string)`

SetIconTone sets IconTone field to given value.

### HasIconTone

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) HasIconTone() bool`

HasIconTone returns a boolean if a field has been set.

### SetIconToneNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetIconToneNil(b bool)`

 SetIconToneNil sets the value for IconTone to be an explicit nil

### UnsetIconTone
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetIconTone()`

UnsetIconTone ensures that no value is present for IconTone, not even an explicit nil
### GetIconUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetIconUrl() string`

GetIconUrl returns the IconUrl field if non-nil, zero value otherwise.

### GetIconUrlOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetIconUrlOk() (*string, bool)`

GetIconUrlOk returns a tuple with the IconUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetIconUrl(v string)`

SetIconUrl sets IconUrl field to given value.

### HasIconUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) HasIconUrl() bool`

HasIconUrl returns a boolean if a field has been set.

### SetIconUrlNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetIconUrlNil(b bool)`

 SetIconUrlNil sets the value for IconUrl to be an explicit nil

### UnsetIconUrl
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetIconUrl()`

UnsetIconUrl ensures that no value is present for IconUrl, not even an explicit nil
### GetLogoTone

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetLogoTone() string`

GetLogoTone returns the LogoTone field if non-nil, zero value otherwise.

### GetLogoToneOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetLogoToneOk() (*string, bool)`

GetLogoToneOk returns a tuple with the LogoTone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoTone

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetLogoTone(v string)`

SetLogoTone sets LogoTone field to given value.

### HasLogoTone

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) HasLogoTone() bool`

HasLogoTone returns a boolean if a field has been set.

### SetLogoToneNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetLogoToneNil(b bool)`

 SetLogoToneNil sets the value for LogoTone to be an explicit nil

### UnsetLogoTone
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetLogoTone()`

UnsetLogoTone ensures that no value is present for LogoTone, not even an explicit nil
### GetLogoUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.


### SetLogoUrlNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetName

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetName(v string)`

SetName sets Name field to given value.


### GetProvenance

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetProvenance() map[string]string`

GetProvenance returns the Provenance field if non-nil, zero value otherwise.

### GetProvenanceOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetProvenanceOk() (*map[string]string, bool)`

GetProvenanceOk returns a tuple with the Provenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenance

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetProvenance(v map[string]string)`

SetProvenance sets Provenance field to given value.

### HasProvenance

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) HasProvenance() bool`

HasProvenance returns a boolean if a field has been set.

### GetSourceUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetSourceUrl() string`

GetSourceUrl returns the SourceUrl field if non-nil, zero value otherwise.

### GetSourceUrlOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetSourceUrlOk() (*string, bool)`

GetSourceUrlOk returns a tuple with the SourceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceUrl

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetSourceUrl(v string)`

SetSourceUrl sets SourceUrl field to given value.


### SetSourceUrlNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetSourceUrlNil(b bool)`

 SetSourceUrlNil sets the value for SourceUrl to be an explicit nil

### UnsetSourceUrl
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetSourceUrl()`

UnsetSourceUrl ensures that no value is present for SourceUrl, not even an explicit nil
### GetTagline

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetTagline() string`

GetTagline returns the Tagline field if non-nil, zero value otherwise.

### GetTaglineOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetTaglineOk() (*string, bool)`

GetTaglineOk returns a tuple with the Tagline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagline

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetTagline(v string)`

SetTagline sets Tagline field to given value.


### SetTaglineNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetTaglineNil(b bool)`

 SetTaglineNil sets the value for Tagline to be an explicit nil

### UnsetTagline
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetTagline()`

UnsetTagline ensures that no value is present for Tagline, not even an explicit nil
### GetTypography

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetTypography() InitialProposalDetailResponseRevisionContentBrandKitTypography`

GetTypography returns the Typography field if non-nil, zero value otherwise.

### GetTypographyOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetTypographyOk() (*InitialProposalDetailResponseRevisionContentBrandKitTypography, bool)`

GetTypographyOk returns a tuple with the Typography field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypography

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetTypography(v InitialProposalDetailResponseRevisionContentBrandKitTypography)`

SetTypography sets Typography field to given value.


### GetVoice

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetVoice(v string)`

SetVoice sets Voice field to given value.


### SetVoiceNil

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetVoiceNil(b bool)`

 SetVoiceNil sets the value for Voice to be an explicit nil

### UnsetVoice
`func (o *InitialProposalDetailResponseRevisionContentBrandKit) UnsetVoice()`

UnsetVoice ensures that no value is present for Voice, not even an explicit nil
### GetWarnings

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *InitialProposalDetailResponseRevisionContentBrandKit) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


