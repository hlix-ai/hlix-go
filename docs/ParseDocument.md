# ParseDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Critical** | Pointer to **bool** |  | [optional] 
**Engine** | Pointer to **string** | How to read the PDF. Omit unless you know: &#x60;text&#x60; (the default) converts a PDF whose words are already text. Use &#x60;ocr&#x60; when the pages are images of a document, and &#x60;native&#x60; when the meaning is in the layout or the figures rather than the words. | [optional] 
**ProjectId** | Pointer to **string** |  | [optional] 
**Scanned** | Pointer to **bool** |  | [optional] 
**Source** | [**ParseDocumentSource**](ParseDocumentSource.md) |  | 
**Visual** | Pointer to **bool** |  | [optional] 

## Methods

### NewParseDocument

`func NewParseDocument(source ParseDocumentSource, ) *ParseDocument`

NewParseDocument instantiates a new ParseDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParseDocumentWithDefaults

`func NewParseDocumentWithDefaults() *ParseDocument`

NewParseDocumentWithDefaults instantiates a new ParseDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCritical

`func (o *ParseDocument) GetCritical() bool`

GetCritical returns the Critical field if non-nil, zero value otherwise.

### GetCriticalOk

`func (o *ParseDocument) GetCriticalOk() (*bool, bool)`

GetCriticalOk returns a tuple with the Critical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCritical

`func (o *ParseDocument) SetCritical(v bool)`

SetCritical sets Critical field to given value.

### HasCritical

`func (o *ParseDocument) HasCritical() bool`

HasCritical returns a boolean if a field has been set.

### GetEngine

`func (o *ParseDocument) GetEngine() string`

GetEngine returns the Engine field if non-nil, zero value otherwise.

### GetEngineOk

`func (o *ParseDocument) GetEngineOk() (*string, bool)`

GetEngineOk returns a tuple with the Engine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngine

`func (o *ParseDocument) SetEngine(v string)`

SetEngine sets Engine field to given value.

### HasEngine

`func (o *ParseDocument) HasEngine() bool`

HasEngine returns a boolean if a field has been set.

### GetProjectId

`func (o *ParseDocument) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ParseDocument) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ParseDocument) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *ParseDocument) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetScanned

`func (o *ParseDocument) GetScanned() bool`

GetScanned returns the Scanned field if non-nil, zero value otherwise.

### GetScannedOk

`func (o *ParseDocument) GetScannedOk() (*bool, bool)`

GetScannedOk returns a tuple with the Scanned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScanned

`func (o *ParseDocument) SetScanned(v bool)`

SetScanned sets Scanned field to given value.

### HasScanned

`func (o *ParseDocument) HasScanned() bool`

HasScanned returns a boolean if a field has been set.

### GetSource

`func (o *ParseDocument) GetSource() ParseDocumentSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ParseDocument) GetSourceOk() (*ParseDocumentSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ParseDocument) SetSource(v ParseDocumentSource)`

SetSource sets Source field to given value.


### GetVisual

`func (o *ParseDocument) GetVisual() bool`

GetVisual returns the Visual field if non-nil, zero value otherwise.

### GetVisualOk

`func (o *ParseDocument) GetVisualOk() (*bool, bool)`

GetVisualOk returns a tuple with the Visual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisual

`func (o *ParseDocument) SetVisual(v bool)`

SetVisual sets Visual field to given value.

### HasVisual

`func (o *ParseDocument) HasVisual() bool`

HasVisual returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


