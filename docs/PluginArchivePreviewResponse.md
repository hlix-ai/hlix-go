# PluginArchivePreviewResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | **string** |  |
**Manifest** | [**CreatePluginManifest**](CreatePluginManifest.md) |  |
**Warnings** | **[]string** |  |

## Methods

### NewPluginArchivePreviewResponse

`func NewPluginArchivePreviewResponse(format string, manifest CreatePluginManifest, warnings []string, ) *PluginArchivePreviewResponse`

NewPluginArchivePreviewResponse instantiates a new PluginArchivePreviewResponse object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewPluginArchivePreviewResponseWithDefaults

`func NewPluginArchivePreviewResponseWithDefaults() *PluginArchivePreviewResponse`

NewPluginArchivePreviewResponseWithDefaults instantiates a new PluginArchivePreviewResponse object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetFormat

`func (o *PluginArchivePreviewResponse) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *PluginArchivePreviewResponse) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *PluginArchivePreviewResponse) SetFormat(v string)`

SetFormat sets Format field to given value.


### GetManifest

`func (o *PluginArchivePreviewResponse) GetManifest() CreatePluginManifest`

GetManifest returns the Manifest field if non-nil, zero value otherwise.

### GetManifestOk

`func (o *PluginArchivePreviewResponse) GetManifestOk() (*CreatePluginManifest, bool)`

GetManifestOk returns a tuple with the Manifest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManifest

`func (o *PluginArchivePreviewResponse) SetManifest(v CreatePluginManifest)`

SetManifest sets Manifest field to given value.


### GetWarnings

`func (o *PluginArchivePreviewResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PluginArchivePreviewResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PluginArchivePreviewResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


