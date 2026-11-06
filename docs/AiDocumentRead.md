# AiDocumentRead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Document** | [**AiDocumentParsedDocument**](AiDocumentParsedDocument.md) |  | 
**ExtractedUrl** | **NullableString** |  | 

## Methods

### NewAiDocumentRead

`func NewAiDocumentRead(document AiDocumentParsedDocument, extractedUrl NullableString, ) *AiDocumentRead`

NewAiDocumentRead instantiates a new AiDocumentRead object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiDocumentReadWithDefaults

`func NewAiDocumentReadWithDefaults() *AiDocumentRead`

NewAiDocumentReadWithDefaults instantiates a new AiDocumentRead object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocument

`func (o *AiDocumentRead) GetDocument() AiDocumentParsedDocument`

GetDocument returns the Document field if non-nil, zero value otherwise.

### GetDocumentOk

`func (o *AiDocumentRead) GetDocumentOk() (*AiDocumentParsedDocument, bool)`

GetDocumentOk returns a tuple with the Document field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocument

`func (o *AiDocumentRead) SetDocument(v AiDocumentParsedDocument)`

SetDocument sets Document field to given value.


### GetExtractedUrl

`func (o *AiDocumentRead) GetExtractedUrl() string`

GetExtractedUrl returns the ExtractedUrl field if non-nil, zero value otherwise.

### GetExtractedUrlOk

`func (o *AiDocumentRead) GetExtractedUrlOk() (*string, bool)`

GetExtractedUrlOk returns a tuple with the ExtractedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedUrl

`func (o *AiDocumentRead) SetExtractedUrl(v string)`

SetExtractedUrl sets ExtractedUrl field to given value.


### SetExtractedUrlNil

`func (o *AiDocumentRead) SetExtractedUrlNil(b bool)`

 SetExtractedUrlNil sets the value for ExtractedUrl to be an explicit nil

### UnsetExtractedUrl
`func (o *AiDocumentRead) UnsetExtractedUrl()`

UnsetExtractedUrl ensures that no value is present for ExtractedUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


