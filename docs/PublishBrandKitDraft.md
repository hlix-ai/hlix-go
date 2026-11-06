# PublishBrandKitDraft

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

### NewPublishBrandKitDraft

`func NewPublishBrandKitDraft(colors InitialProposalDetailResponseRevisionContentBrandKitColors, description NullableString, extractedAt NullableTime, logoUrl NullableString, name string, sourceUrl NullableString, tagline NullableString, typography InitialProposalDetailResponseRevisionContentBrandKitTypography, voice NullableString, warnings []string, ) *PublishBrandKitDraft`

NewPublishBrandKitDraft instantiates a new PublishBrandKitDraft object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishBrandKitDraftWithDefaults

`func NewPublishBrandKitDraftWithDefaults() *PublishBrandKitDraft`

NewPublishBrandKitDraftWithDefaults instantiates a new PublishBrandKitDraft object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColors

`func (o *PublishBrandKitDraft) GetColors() InitialProposalDetailResponseRevisionContentBrandKitColors`

GetColors returns the Colors field if non-nil, zero value otherwise.

### GetColorsOk

`func (o *PublishBrandKitDraft) GetColorsOk() (*InitialProposalDetailResponseRevisionContentBrandKitColors, bool)`

GetColorsOk returns a tuple with the Colors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColors

`func (o *PublishBrandKitDraft) SetColors(v InitialProposalDetailResponseRevisionContentBrandKitColors)`

SetColors sets Colors field to given value.


### GetDescription

`func (o *PublishBrandKitDraft) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PublishBrandKitDraft) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PublishBrandKitDraft) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *PublishBrandKitDraft) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PublishBrandKitDraft) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetExtractedAt

`func (o *PublishBrandKitDraft) GetExtractedAt() time.Time`

GetExtractedAt returns the ExtractedAt field if non-nil, zero value otherwise.

### GetExtractedAtOk

`func (o *PublishBrandKitDraft) GetExtractedAtOk() (*time.Time, bool)`

GetExtractedAtOk returns a tuple with the ExtractedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedAt

`func (o *PublishBrandKitDraft) SetExtractedAt(v time.Time)`

SetExtractedAt sets ExtractedAt field to given value.


### SetExtractedAtNil

`func (o *PublishBrandKitDraft) SetExtractedAtNil(b bool)`

 SetExtractedAtNil sets the value for ExtractedAt to be an explicit nil

### UnsetExtractedAt
`func (o *PublishBrandKitDraft) UnsetExtractedAt()`

UnsetExtractedAt ensures that no value is present for ExtractedAt, not even an explicit nil
### GetHeaderMode

`func (o *PublishBrandKitDraft) GetHeaderMode() string`

GetHeaderMode returns the HeaderMode field if non-nil, zero value otherwise.

### GetHeaderModeOk

`func (o *PublishBrandKitDraft) GetHeaderModeOk() (*string, bool)`

GetHeaderModeOk returns a tuple with the HeaderMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeaderMode

`func (o *PublishBrandKitDraft) SetHeaderMode(v string)`

SetHeaderMode sets HeaderMode field to given value.

### HasHeaderMode

`func (o *PublishBrandKitDraft) HasHeaderMode() bool`

HasHeaderMode returns a boolean if a field has been set.

### GetIconTone

`func (o *PublishBrandKitDraft) GetIconTone() string`

GetIconTone returns the IconTone field if non-nil, zero value otherwise.

### GetIconToneOk

`func (o *PublishBrandKitDraft) GetIconToneOk() (*string, bool)`

GetIconToneOk returns a tuple with the IconTone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconTone

`func (o *PublishBrandKitDraft) SetIconTone(v string)`

SetIconTone sets IconTone field to given value.

### HasIconTone

`func (o *PublishBrandKitDraft) HasIconTone() bool`

HasIconTone returns a boolean if a field has been set.

### SetIconToneNil

`func (o *PublishBrandKitDraft) SetIconToneNil(b bool)`

 SetIconToneNil sets the value for IconTone to be an explicit nil

### UnsetIconTone
`func (o *PublishBrandKitDraft) UnsetIconTone()`

UnsetIconTone ensures that no value is present for IconTone, not even an explicit nil
### GetIconUrl

`func (o *PublishBrandKitDraft) GetIconUrl() string`

GetIconUrl returns the IconUrl field if non-nil, zero value otherwise.

### GetIconUrlOk

`func (o *PublishBrandKitDraft) GetIconUrlOk() (*string, bool)`

GetIconUrlOk returns a tuple with the IconUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconUrl

`func (o *PublishBrandKitDraft) SetIconUrl(v string)`

SetIconUrl sets IconUrl field to given value.

### HasIconUrl

`func (o *PublishBrandKitDraft) HasIconUrl() bool`

HasIconUrl returns a boolean if a field has been set.

### SetIconUrlNil

`func (o *PublishBrandKitDraft) SetIconUrlNil(b bool)`

 SetIconUrlNil sets the value for IconUrl to be an explicit nil

### UnsetIconUrl
`func (o *PublishBrandKitDraft) UnsetIconUrl()`

UnsetIconUrl ensures that no value is present for IconUrl, not even an explicit nil
### GetLogoTone

`func (o *PublishBrandKitDraft) GetLogoTone() string`

GetLogoTone returns the LogoTone field if non-nil, zero value otherwise.

### GetLogoToneOk

`func (o *PublishBrandKitDraft) GetLogoToneOk() (*string, bool)`

GetLogoToneOk returns a tuple with the LogoTone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoTone

`func (o *PublishBrandKitDraft) SetLogoTone(v string)`

SetLogoTone sets LogoTone field to given value.

### HasLogoTone

`func (o *PublishBrandKitDraft) HasLogoTone() bool`

HasLogoTone returns a boolean if a field has been set.

### SetLogoToneNil

`func (o *PublishBrandKitDraft) SetLogoToneNil(b bool)`

 SetLogoToneNil sets the value for LogoTone to be an explicit nil

### UnsetLogoTone
`func (o *PublishBrandKitDraft) UnsetLogoTone()`

UnsetLogoTone ensures that no value is present for LogoTone, not even an explicit nil
### GetLogoUrl

`func (o *PublishBrandKitDraft) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *PublishBrandKitDraft) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *PublishBrandKitDraft) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.


### SetLogoUrlNil

`func (o *PublishBrandKitDraft) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *PublishBrandKitDraft) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetName

`func (o *PublishBrandKitDraft) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PublishBrandKitDraft) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PublishBrandKitDraft) SetName(v string)`

SetName sets Name field to given value.


### GetProvenance

`func (o *PublishBrandKitDraft) GetProvenance() map[string]string`

GetProvenance returns the Provenance field if non-nil, zero value otherwise.

### GetProvenanceOk

`func (o *PublishBrandKitDraft) GetProvenanceOk() (*map[string]string, bool)`

GetProvenanceOk returns a tuple with the Provenance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenance

`func (o *PublishBrandKitDraft) SetProvenance(v map[string]string)`

SetProvenance sets Provenance field to given value.

### HasProvenance

`func (o *PublishBrandKitDraft) HasProvenance() bool`

HasProvenance returns a boolean if a field has been set.

### GetSourceUrl

`func (o *PublishBrandKitDraft) GetSourceUrl() string`

GetSourceUrl returns the SourceUrl field if non-nil, zero value otherwise.

### GetSourceUrlOk

`func (o *PublishBrandKitDraft) GetSourceUrlOk() (*string, bool)`

GetSourceUrlOk returns a tuple with the SourceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceUrl

`func (o *PublishBrandKitDraft) SetSourceUrl(v string)`

SetSourceUrl sets SourceUrl field to given value.


### SetSourceUrlNil

`func (o *PublishBrandKitDraft) SetSourceUrlNil(b bool)`

 SetSourceUrlNil sets the value for SourceUrl to be an explicit nil

### UnsetSourceUrl
`func (o *PublishBrandKitDraft) UnsetSourceUrl()`

UnsetSourceUrl ensures that no value is present for SourceUrl, not even an explicit nil
### GetTagline

`func (o *PublishBrandKitDraft) GetTagline() string`

GetTagline returns the Tagline field if non-nil, zero value otherwise.

### GetTaglineOk

`func (o *PublishBrandKitDraft) GetTaglineOk() (*string, bool)`

GetTaglineOk returns a tuple with the Tagline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagline

`func (o *PublishBrandKitDraft) SetTagline(v string)`

SetTagline sets Tagline field to given value.


### SetTaglineNil

`func (o *PublishBrandKitDraft) SetTaglineNil(b bool)`

 SetTaglineNil sets the value for Tagline to be an explicit nil

### UnsetTagline
`func (o *PublishBrandKitDraft) UnsetTagline()`

UnsetTagline ensures that no value is present for Tagline, not even an explicit nil
### GetTypography

`func (o *PublishBrandKitDraft) GetTypography() InitialProposalDetailResponseRevisionContentBrandKitTypography`

GetTypography returns the Typography field if non-nil, zero value otherwise.

### GetTypographyOk

`func (o *PublishBrandKitDraft) GetTypographyOk() (*InitialProposalDetailResponseRevisionContentBrandKitTypography, bool)`

GetTypographyOk returns a tuple with the Typography field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypography

`func (o *PublishBrandKitDraft) SetTypography(v InitialProposalDetailResponseRevisionContentBrandKitTypography)`

SetTypography sets Typography field to given value.


### GetVoice

`func (o *PublishBrandKitDraft) GetVoice() string`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *PublishBrandKitDraft) GetVoiceOk() (*string, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *PublishBrandKitDraft) SetVoice(v string)`

SetVoice sets Voice field to given value.


### SetVoiceNil

`func (o *PublishBrandKitDraft) SetVoiceNil(b bool)`

 SetVoiceNil sets the value for Voice to be an explicit nil

### UnsetVoice
`func (o *PublishBrandKitDraft) UnsetVoice()`

UnsetVoice ensures that no value is present for Voice, not even an explicit nil
### GetWarnings

`func (o *PublishBrandKitDraft) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PublishBrandKitDraft) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PublishBrandKitDraft) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


