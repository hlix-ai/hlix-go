# ProjectCanvasPreview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Journeys** | [**[]ProjectCanvasPreviewJourneysInner**](ProjectCanvasPreviewJourneysInner.md) |  |
**Status** | **string** |  |
**Thumbnail** | [**NullableProjectCanvasPreviewThumbnail**](ProjectCanvasPreviewThumbnail.md) |  |
**Url** | **NullableString** |  |

## Methods

### NewProjectCanvasPreview

`func NewProjectCanvasPreview(journeys []ProjectCanvasPreviewJourneysInner, status string, thumbnail NullableProjectCanvasPreviewThumbnail, url NullableString, ) *ProjectCanvasPreview`

NewProjectCanvasPreview instantiates a new ProjectCanvasPreview object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewProjectCanvasPreviewWithDefaults

`func NewProjectCanvasPreviewWithDefaults() *ProjectCanvasPreview`

NewProjectCanvasPreviewWithDefaults instantiates a new ProjectCanvasPreview object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetJourneys

`func (o *ProjectCanvasPreview) GetJourneys() []ProjectCanvasPreviewJourneysInner`

GetJourneys returns the Journeys field if non-nil, zero value otherwise.

### GetJourneysOk

`func (o *ProjectCanvasPreview) GetJourneysOk() (*[]ProjectCanvasPreviewJourneysInner, bool)`

GetJourneysOk returns a tuple with the Journeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJourneys

`func (o *ProjectCanvasPreview) SetJourneys(v []ProjectCanvasPreviewJourneysInner)`

SetJourneys sets Journeys field to given value.


### GetStatus

`func (o *ProjectCanvasPreview) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ProjectCanvasPreview) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ProjectCanvasPreview) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetThumbnail

`func (o *ProjectCanvasPreview) GetThumbnail() ProjectCanvasPreviewThumbnail`

GetThumbnail returns the Thumbnail field if non-nil, zero value otherwise.

### GetThumbnailOk

`func (o *ProjectCanvasPreview) GetThumbnailOk() (*ProjectCanvasPreviewThumbnail, bool)`

GetThumbnailOk returns a tuple with the Thumbnail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnail

`func (o *ProjectCanvasPreview) SetThumbnail(v ProjectCanvasPreviewThumbnail)`

SetThumbnail sets Thumbnail field to given value.


### SetThumbnailNil

`func (o *ProjectCanvasPreview) SetThumbnailNil(b bool)`

 SetThumbnailNil sets the value for Thumbnail to be an explicit nil

### UnsetThumbnail
`func (o *ProjectCanvasPreview) UnsetThumbnail()`

UnsetThumbnail ensures that no value is present for Thumbnail, not even an explicit nil
### GetUrl

`func (o *ProjectCanvasPreview) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ProjectCanvasPreview) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ProjectCanvasPreview) SetUrl(v string)`

SetUrl sets Url field to given value.


### SetUrlNil

`func (o *ProjectCanvasPreview) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *ProjectCanvasPreview) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


