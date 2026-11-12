# AiDocumentParsed

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Document** | [**AiDocumentParsedDocument**](AiDocumentParsedDocument.md) |  |
**ExtractedUrl** | **NullableString** |  |
**Reused** | **bool** |  |

## Methods

### NewAiDocumentParsed

`func NewAiDocumentParsed(document AiDocumentParsedDocument, extractedUrl NullableString, reused bool, ) *AiDocumentParsed`

NewAiDocumentParsed instantiates a new AiDocumentParsed object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAiDocumentParsedWithDefaults

`func NewAiDocumentParsedWithDefaults() *AiDocumentParsed`

NewAiDocumentParsedWithDefaults instantiates a new AiDocumentParsed object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetDocument

`func (o *AiDocumentParsed) GetDocument() AiDocumentParsedDocument`

GetDocument returns the Document field if non-nil, zero value otherwise.

### GetDocumentOk

`func (o *AiDocumentParsed) GetDocumentOk() (*AiDocumentParsedDocument, bool)`

GetDocumentOk returns a tuple with the Document field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocument

`func (o *AiDocumentParsed) SetDocument(v AiDocumentParsedDocument)`

SetDocument sets Document field to given value.


### GetExtractedUrl

`func (o *AiDocumentParsed) GetExtractedUrl() string`

GetExtractedUrl returns the ExtractedUrl field if non-nil, zero value otherwise.

### GetExtractedUrlOk

`func (o *AiDocumentParsed) GetExtractedUrlOk() (*string, bool)`

GetExtractedUrlOk returns a tuple with the ExtractedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedUrl

`func (o *AiDocumentParsed) SetExtractedUrl(v string)`

SetExtractedUrl sets ExtractedUrl field to given value.


### SetExtractedUrlNil

`func (o *AiDocumentParsed) SetExtractedUrlNil(b bool)`

 SetExtractedUrlNil sets the value for ExtractedUrl to be an explicit nil

### UnsetExtractedUrl
`func (o *AiDocumentParsed) UnsetExtractedUrl()`

UnsetExtractedUrl ensures that no value is present for ExtractedUrl, not even an explicit nil
### GetReused

`func (o *AiDocumentParsed) GetReused() bool`

GetReused returns the Reused field if non-nil, zero value otherwise.

### GetReusedOk

`func (o *AiDocumentParsed) GetReusedOk() (*bool, bool)`

GetReusedOk returns a tuple with the Reused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReused

`func (o *AiDocumentParsed) SetReused(v bool)`

SetReused sets Reused field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


