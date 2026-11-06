# AiDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CorrelationId** | **string** |  | 
**CostMicros** | **NullableInt64** |  | 
**CreatedAt** | **string** |  | 
**Critical** | **bool** |  | 
**Error** | **NullableString** |  | 
**ExtractedAt** | **NullableString** |  | 
**ExtractedChars** | **NullableInt32** |  | 
**ExtractedKey** | **NullableString** |  | 
**Id** | **string** |  | 
**Model** | **NullableString** |  | 
**OrganizationId** | **string** |  | 
**PageCount** | **NullableInt32** |  | 
**ParserEngine** | **string** |  | 
**ParserHash** | **NullableString** |  | 
**ParserVersion** | **NullableString** |  | 
**ProjectId** | **NullableString** |  | 
**Quality** | **map[string]interface{}** |  | 
**SourceHash** | **string** |  | 
**SourceKey** | **NullableString** |  | 
**SourceKind** | **string** |  | 
**SourceRef** | **string** |  | 
**Status** | **string** |  | 
**Validation** | **map[string]interface{}** |  | 

## Methods

### NewAiDocument

`func NewAiDocument(correlationId string, costMicros NullableInt64, createdAt string, critical bool, error_ NullableString, extractedAt NullableString, extractedChars NullableInt32, extractedKey NullableString, id string, model NullableString, organizationId string, pageCount NullableInt32, parserEngine string, parserHash NullableString, parserVersion NullableString, projectId NullableString, quality map[string]interface{}, sourceHash string, sourceKey NullableString, sourceKind string, sourceRef string, status string, validation map[string]interface{}, ) *AiDocument`

NewAiDocument instantiates a new AiDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiDocumentWithDefaults

`func NewAiDocumentWithDefaults() *AiDocument`

NewAiDocumentWithDefaults instantiates a new AiDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCorrelationId

`func (o *AiDocument) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *AiDocument) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *AiDocument) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.


### GetCostMicros

`func (o *AiDocument) GetCostMicros() int64`

GetCostMicros returns the CostMicros field if non-nil, zero value otherwise.

### GetCostMicrosOk

`func (o *AiDocument) GetCostMicrosOk() (*int64, bool)`

GetCostMicrosOk returns a tuple with the CostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostMicros

`func (o *AiDocument) SetCostMicros(v int64)`

SetCostMicros sets CostMicros field to given value.


### SetCostMicrosNil

`func (o *AiDocument) SetCostMicrosNil(b bool)`

 SetCostMicrosNil sets the value for CostMicros to be an explicit nil

### UnsetCostMicros
`func (o *AiDocument) UnsetCostMicros()`

UnsetCostMicros ensures that no value is present for CostMicros, not even an explicit nil
### GetCreatedAt

`func (o *AiDocument) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AiDocument) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AiDocument) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCritical

`func (o *AiDocument) GetCritical() bool`

GetCritical returns the Critical field if non-nil, zero value otherwise.

### GetCriticalOk

`func (o *AiDocument) GetCriticalOk() (*bool, bool)`

GetCriticalOk returns a tuple with the Critical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCritical

`func (o *AiDocument) SetCritical(v bool)`

SetCritical sets Critical field to given value.


### GetError

`func (o *AiDocument) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AiDocument) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AiDocument) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *AiDocument) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AiDocument) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetExtractedAt

`func (o *AiDocument) GetExtractedAt() string`

GetExtractedAt returns the ExtractedAt field if non-nil, zero value otherwise.

### GetExtractedAtOk

`func (o *AiDocument) GetExtractedAtOk() (*string, bool)`

GetExtractedAtOk returns a tuple with the ExtractedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedAt

`func (o *AiDocument) SetExtractedAt(v string)`

SetExtractedAt sets ExtractedAt field to given value.


### SetExtractedAtNil

`func (o *AiDocument) SetExtractedAtNil(b bool)`

 SetExtractedAtNil sets the value for ExtractedAt to be an explicit nil

### UnsetExtractedAt
`func (o *AiDocument) UnsetExtractedAt()`

UnsetExtractedAt ensures that no value is present for ExtractedAt, not even an explicit nil
### GetExtractedChars

`func (o *AiDocument) GetExtractedChars() int32`

GetExtractedChars returns the ExtractedChars field if non-nil, zero value otherwise.

### GetExtractedCharsOk

`func (o *AiDocument) GetExtractedCharsOk() (*int32, bool)`

GetExtractedCharsOk returns a tuple with the ExtractedChars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedChars

`func (o *AiDocument) SetExtractedChars(v int32)`

SetExtractedChars sets ExtractedChars field to given value.


### SetExtractedCharsNil

`func (o *AiDocument) SetExtractedCharsNil(b bool)`

 SetExtractedCharsNil sets the value for ExtractedChars to be an explicit nil

### UnsetExtractedChars
`func (o *AiDocument) UnsetExtractedChars()`

UnsetExtractedChars ensures that no value is present for ExtractedChars, not even an explicit nil
### GetExtractedKey

`func (o *AiDocument) GetExtractedKey() string`

GetExtractedKey returns the ExtractedKey field if non-nil, zero value otherwise.

### GetExtractedKeyOk

`func (o *AiDocument) GetExtractedKeyOk() (*string, bool)`

GetExtractedKeyOk returns a tuple with the ExtractedKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractedKey

`func (o *AiDocument) SetExtractedKey(v string)`

SetExtractedKey sets ExtractedKey field to given value.


### SetExtractedKeyNil

`func (o *AiDocument) SetExtractedKeyNil(b bool)`

 SetExtractedKeyNil sets the value for ExtractedKey to be an explicit nil

### UnsetExtractedKey
`func (o *AiDocument) UnsetExtractedKey()`

UnsetExtractedKey ensures that no value is present for ExtractedKey, not even an explicit nil
### GetId

`func (o *AiDocument) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiDocument) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiDocument) SetId(v string)`

SetId sets Id field to given value.


### GetModel

`func (o *AiDocument) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiDocument) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiDocument) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *AiDocument) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *AiDocument) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetOrganizationId

`func (o *AiDocument) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *AiDocument) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *AiDocument) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetPageCount

`func (o *AiDocument) GetPageCount() int32`

GetPageCount returns the PageCount field if non-nil, zero value otherwise.

### GetPageCountOk

`func (o *AiDocument) GetPageCountOk() (*int32, bool)`

GetPageCountOk returns a tuple with the PageCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageCount

`func (o *AiDocument) SetPageCount(v int32)`

SetPageCount sets PageCount field to given value.


### SetPageCountNil

`func (o *AiDocument) SetPageCountNil(b bool)`

 SetPageCountNil sets the value for PageCount to be an explicit nil

### UnsetPageCount
`func (o *AiDocument) UnsetPageCount()`

UnsetPageCount ensures that no value is present for PageCount, not even an explicit nil
### GetParserEngine

`func (o *AiDocument) GetParserEngine() string`

GetParserEngine returns the ParserEngine field if non-nil, zero value otherwise.

### GetParserEngineOk

`func (o *AiDocument) GetParserEngineOk() (*string, bool)`

GetParserEngineOk returns a tuple with the ParserEngine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParserEngine

`func (o *AiDocument) SetParserEngine(v string)`

SetParserEngine sets ParserEngine field to given value.


### GetParserHash

`func (o *AiDocument) GetParserHash() string`

GetParserHash returns the ParserHash field if non-nil, zero value otherwise.

### GetParserHashOk

`func (o *AiDocument) GetParserHashOk() (*string, bool)`

GetParserHashOk returns a tuple with the ParserHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParserHash

`func (o *AiDocument) SetParserHash(v string)`

SetParserHash sets ParserHash field to given value.


### SetParserHashNil

`func (o *AiDocument) SetParserHashNil(b bool)`

 SetParserHashNil sets the value for ParserHash to be an explicit nil

### UnsetParserHash
`func (o *AiDocument) UnsetParserHash()`

UnsetParserHash ensures that no value is present for ParserHash, not even an explicit nil
### GetParserVersion

`func (o *AiDocument) GetParserVersion() string`

GetParserVersion returns the ParserVersion field if non-nil, zero value otherwise.

### GetParserVersionOk

`func (o *AiDocument) GetParserVersionOk() (*string, bool)`

GetParserVersionOk returns a tuple with the ParserVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParserVersion

`func (o *AiDocument) SetParserVersion(v string)`

SetParserVersion sets ParserVersion field to given value.


### SetParserVersionNil

`func (o *AiDocument) SetParserVersionNil(b bool)`

 SetParserVersionNil sets the value for ParserVersion to be an explicit nil

### UnsetParserVersion
`func (o *AiDocument) UnsetParserVersion()`

UnsetParserVersion ensures that no value is present for ParserVersion, not even an explicit nil
### GetProjectId

`func (o *AiDocument) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AiDocument) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AiDocument) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *AiDocument) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *AiDocument) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetQuality

`func (o *AiDocument) GetQuality() map[string]interface{}`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *AiDocument) GetQualityOk() (*map[string]interface{}, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *AiDocument) SetQuality(v map[string]interface{})`

SetQuality sets Quality field to given value.


### SetQualityNil

`func (o *AiDocument) SetQualityNil(b bool)`

 SetQualityNil sets the value for Quality to be an explicit nil

### UnsetQuality
`func (o *AiDocument) UnsetQuality()`

UnsetQuality ensures that no value is present for Quality, not even an explicit nil
### GetSourceHash

`func (o *AiDocument) GetSourceHash() string`

GetSourceHash returns the SourceHash field if non-nil, zero value otherwise.

### GetSourceHashOk

`func (o *AiDocument) GetSourceHashOk() (*string, bool)`

GetSourceHashOk returns a tuple with the SourceHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceHash

`func (o *AiDocument) SetSourceHash(v string)`

SetSourceHash sets SourceHash field to given value.


### GetSourceKey

`func (o *AiDocument) GetSourceKey() string`

GetSourceKey returns the SourceKey field if non-nil, zero value otherwise.

### GetSourceKeyOk

`func (o *AiDocument) GetSourceKeyOk() (*string, bool)`

GetSourceKeyOk returns a tuple with the SourceKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceKey

`func (o *AiDocument) SetSourceKey(v string)`

SetSourceKey sets SourceKey field to given value.


### SetSourceKeyNil

`func (o *AiDocument) SetSourceKeyNil(b bool)`

 SetSourceKeyNil sets the value for SourceKey to be an explicit nil

### UnsetSourceKey
`func (o *AiDocument) UnsetSourceKey()`

UnsetSourceKey ensures that no value is present for SourceKey, not even an explicit nil
### GetSourceKind

`func (o *AiDocument) GetSourceKind() string`

GetSourceKind returns the SourceKind field if non-nil, zero value otherwise.

### GetSourceKindOk

`func (o *AiDocument) GetSourceKindOk() (*string, bool)`

GetSourceKindOk returns a tuple with the SourceKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceKind

`func (o *AiDocument) SetSourceKind(v string)`

SetSourceKind sets SourceKind field to given value.


### GetSourceRef

`func (o *AiDocument) GetSourceRef() string`

GetSourceRef returns the SourceRef field if non-nil, zero value otherwise.

### GetSourceRefOk

`func (o *AiDocument) GetSourceRefOk() (*string, bool)`

GetSourceRefOk returns a tuple with the SourceRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRef

`func (o *AiDocument) SetSourceRef(v string)`

SetSourceRef sets SourceRef field to given value.


### GetStatus

`func (o *AiDocument) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AiDocument) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AiDocument) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetValidation

`func (o *AiDocument) GetValidation() map[string]interface{}`

GetValidation returns the Validation field if non-nil, zero value otherwise.

### GetValidationOk

`func (o *AiDocument) GetValidationOk() (*map[string]interface{}, bool)`

GetValidationOk returns a tuple with the Validation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidation

`func (o *AiDocument) SetValidation(v map[string]interface{})`

SetValidation sets Validation field to given value.


### SetValidationNil

`func (o *AiDocument) SetValidationNil(b bool)`

 SetValidationNil sets the value for Validation to be an explicit nil

### UnsetValidation
`func (o *AiDocument) UnsetValidation()`

UnsetValidation ensures that no value is present for Validation, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


