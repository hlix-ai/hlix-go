# ClientBillable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AmountMicros** | **int64** |  |
**ClientAccountId** | **string** |  |
**CreatedAt** | **string** |  |
**CreatedBy** | **string** |  |
**Currency** | **string** |  |
**Description** | **string** |  |
**EntryType** | **string** |  |
**Id** | **string** |  |
**OccurredAt** | **string** |  |
**OrganizationId** | **string** |  |
**ProjectId** | **NullableString** |  |
**Quantity** | **string** |  |
**RateSnapshot** | [**ClientBillableRateSnapshot**](ClientBillableRateSnapshot.md) |  |
**ReplacesBillableId** | **NullableString** |  |
**Source** | **string** |  |
**SourceEntityId** | **NullableString** |  |
**SourceEntityType** | **NullableString** |  |
**SourceEvidence** | **map[string]interface{}** |  |
**TaxClass** | **string** |  |
**Unit** | **string** |  |
**UnitPriceMicros** | **int64** |  |

## Methods

### NewClientBillable

`func NewClientBillable(amountMicros int64, clientAccountId string, createdAt string, createdBy string, currency string, description string, entryType string, id string, occurredAt string, organizationId string, projectId NullableString, quantity string, rateSnapshot ClientBillableRateSnapshot, replacesBillableId NullableString, source string, sourceEntityId NullableString, sourceEntityType NullableString, sourceEvidence map[string]interface{}, taxClass string, unit string, unitPriceMicros int64, ) *ClientBillable`

NewClientBillable instantiates a new ClientBillable object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientBillableWithDefaults

`func NewClientBillableWithDefaults() *ClientBillable`

NewClientBillableWithDefaults instantiates a new ClientBillable object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAmountMicros

`func (o *ClientBillable) GetAmountMicros() int64`

GetAmountMicros returns the AmountMicros field if non-nil, zero value otherwise.

### GetAmountMicrosOk

`func (o *ClientBillable) GetAmountMicrosOk() (*int64, bool)`

GetAmountMicrosOk returns a tuple with the AmountMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountMicros

`func (o *ClientBillable) SetAmountMicros(v int64)`

SetAmountMicros sets AmountMicros field to given value.


### GetClientAccountId

`func (o *ClientBillable) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *ClientBillable) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *ClientBillable) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetCreatedAt

`func (o *ClientBillable) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientBillable) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientBillable) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedBy

`func (o *ClientBillable) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ClientBillable) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ClientBillable) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetCurrency

`func (o *ClientBillable) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ClientBillable) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ClientBillable) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *ClientBillable) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ClientBillable) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ClientBillable) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEntryType

`func (o *ClientBillable) GetEntryType() string`

GetEntryType returns the EntryType field if non-nil, zero value otherwise.

### GetEntryTypeOk

`func (o *ClientBillable) GetEntryTypeOk() (*string, bool)`

GetEntryTypeOk returns a tuple with the EntryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryType

`func (o *ClientBillable) SetEntryType(v string)`

SetEntryType sets EntryType field to given value.


### GetId

`func (o *ClientBillable) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientBillable) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientBillable) SetId(v string)`

SetId sets Id field to given value.


### GetOccurredAt

`func (o *ClientBillable) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *ClientBillable) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *ClientBillable) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.


### GetOrganizationId

`func (o *ClientBillable) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ClientBillable) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ClientBillable) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *ClientBillable) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ClientBillable) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ClientBillable) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *ClientBillable) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ClientBillable) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetQuantity

`func (o *ClientBillable) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ClientBillable) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ClientBillable) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetRateSnapshot

`func (o *ClientBillable) GetRateSnapshot() ClientBillableRateSnapshot`

GetRateSnapshot returns the RateSnapshot field if non-nil, zero value otherwise.

### GetRateSnapshotOk

`func (o *ClientBillable) GetRateSnapshotOk() (*ClientBillableRateSnapshot, bool)`

GetRateSnapshotOk returns a tuple with the RateSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRateSnapshot

`func (o *ClientBillable) SetRateSnapshot(v ClientBillableRateSnapshot)`

SetRateSnapshot sets RateSnapshot field to given value.


### GetReplacesBillableId

`func (o *ClientBillable) GetReplacesBillableId() string`

GetReplacesBillableId returns the ReplacesBillableId field if non-nil, zero value otherwise.

### GetReplacesBillableIdOk

`func (o *ClientBillable) GetReplacesBillableIdOk() (*string, bool)`

GetReplacesBillableIdOk returns a tuple with the ReplacesBillableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacesBillableId

`func (o *ClientBillable) SetReplacesBillableId(v string)`

SetReplacesBillableId sets ReplacesBillableId field to given value.


### SetReplacesBillableIdNil

`func (o *ClientBillable) SetReplacesBillableIdNil(b bool)`

 SetReplacesBillableIdNil sets the value for ReplacesBillableId to be an explicit nil

### UnsetReplacesBillableId
`func (o *ClientBillable) UnsetReplacesBillableId()`

UnsetReplacesBillableId ensures that no value is present for ReplacesBillableId, not even an explicit nil
### GetSource

`func (o *ClientBillable) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ClientBillable) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ClientBillable) SetSource(v string)`

SetSource sets Source field to given value.


### GetSourceEntityId

`func (o *ClientBillable) GetSourceEntityId() string`

GetSourceEntityId returns the SourceEntityId field if non-nil, zero value otherwise.

### GetSourceEntityIdOk

`func (o *ClientBillable) GetSourceEntityIdOk() (*string, bool)`

GetSourceEntityIdOk returns a tuple with the SourceEntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceEntityId

`func (o *ClientBillable) SetSourceEntityId(v string)`

SetSourceEntityId sets SourceEntityId field to given value.


### SetSourceEntityIdNil

`func (o *ClientBillable) SetSourceEntityIdNil(b bool)`

 SetSourceEntityIdNil sets the value for SourceEntityId to be an explicit nil

### UnsetSourceEntityId
`func (o *ClientBillable) UnsetSourceEntityId()`

UnsetSourceEntityId ensures that no value is present for SourceEntityId, not even an explicit nil
### GetSourceEntityType

`func (o *ClientBillable) GetSourceEntityType() string`

GetSourceEntityType returns the SourceEntityType field if non-nil, zero value otherwise.

### GetSourceEntityTypeOk

`func (o *ClientBillable) GetSourceEntityTypeOk() (*string, bool)`

GetSourceEntityTypeOk returns a tuple with the SourceEntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceEntityType

`func (o *ClientBillable) SetSourceEntityType(v string)`

SetSourceEntityType sets SourceEntityType field to given value.


### SetSourceEntityTypeNil

`func (o *ClientBillable) SetSourceEntityTypeNil(b bool)`

 SetSourceEntityTypeNil sets the value for SourceEntityType to be an explicit nil

### UnsetSourceEntityType
`func (o *ClientBillable) UnsetSourceEntityType()`

UnsetSourceEntityType ensures that no value is present for SourceEntityType, not even an explicit nil
### GetSourceEvidence

`func (o *ClientBillable) GetSourceEvidence() map[string]interface{}`

GetSourceEvidence returns the SourceEvidence field if non-nil, zero value otherwise.

### GetSourceEvidenceOk

`func (o *ClientBillable) GetSourceEvidenceOk() (*map[string]interface{}, bool)`

GetSourceEvidenceOk returns a tuple with the SourceEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceEvidence

`func (o *ClientBillable) SetSourceEvidence(v map[string]interface{})`

SetSourceEvidence sets SourceEvidence field to given value.


### GetTaxClass

`func (o *ClientBillable) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *ClientBillable) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *ClientBillable) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.


### GetUnit

`func (o *ClientBillable) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ClientBillable) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ClientBillable) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *ClientBillable) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *ClientBillable) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *ClientBillable) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


