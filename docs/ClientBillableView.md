# ClientBillableView

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
**NetAmountMicros** | **int64** |  |
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
**VoidedByBillableId** | **NullableString** |  |

## Methods

### NewClientBillableView

`func NewClientBillableView(amountMicros int64, clientAccountId string, createdAt string, createdBy string, currency string, description string, entryType string, id string, netAmountMicros int64, occurredAt string, organizationId string, projectId NullableString, quantity string, rateSnapshot ClientBillableRateSnapshot, replacesBillableId NullableString, source string, sourceEntityId NullableString, sourceEntityType NullableString, sourceEvidence map[string]interface{}, taxClass string, unit string, unitPriceMicros int64, voidedByBillableId NullableString, ) *ClientBillableView`

NewClientBillableView instantiates a new ClientBillableView object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewClientBillableViewWithDefaults

`func NewClientBillableViewWithDefaults() *ClientBillableView`

NewClientBillableViewWithDefaults instantiates a new ClientBillableView object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAmountMicros

`func (o *ClientBillableView) GetAmountMicros() int64`

GetAmountMicros returns the AmountMicros field if non-nil, zero value otherwise.

### GetAmountMicrosOk

`func (o *ClientBillableView) GetAmountMicrosOk() (*int64, bool)`

GetAmountMicrosOk returns a tuple with the AmountMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountMicros

`func (o *ClientBillableView) SetAmountMicros(v int64)`

SetAmountMicros sets AmountMicros field to given value.


### GetClientAccountId

`func (o *ClientBillableView) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *ClientBillableView) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *ClientBillableView) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### GetCreatedAt

`func (o *ClientBillableView) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientBillableView) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientBillableView) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreatedBy

`func (o *ClientBillableView) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *ClientBillableView) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *ClientBillableView) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.


### GetCurrency

`func (o *ClientBillableView) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ClientBillableView) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ClientBillableView) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *ClientBillableView) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ClientBillableView) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ClientBillableView) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetEntryType

`func (o *ClientBillableView) GetEntryType() string`

GetEntryType returns the EntryType field if non-nil, zero value otherwise.

### GetEntryTypeOk

`func (o *ClientBillableView) GetEntryTypeOk() (*string, bool)`

GetEntryTypeOk returns a tuple with the EntryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryType

`func (o *ClientBillableView) SetEntryType(v string)`

SetEntryType sets EntryType field to given value.


### GetId

`func (o *ClientBillableView) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientBillableView) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientBillableView) SetId(v string)`

SetId sets Id field to given value.


### GetNetAmountMicros

`func (o *ClientBillableView) GetNetAmountMicros() int64`

GetNetAmountMicros returns the NetAmountMicros field if non-nil, zero value otherwise.

### GetNetAmountMicrosOk

`func (o *ClientBillableView) GetNetAmountMicrosOk() (*int64, bool)`

GetNetAmountMicrosOk returns a tuple with the NetAmountMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetAmountMicros

`func (o *ClientBillableView) SetNetAmountMicros(v int64)`

SetNetAmountMicros sets NetAmountMicros field to given value.


### GetOccurredAt

`func (o *ClientBillableView) GetOccurredAt() string`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *ClientBillableView) GetOccurredAtOk() (*string, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *ClientBillableView) SetOccurredAt(v string)`

SetOccurredAt sets OccurredAt field to given value.


### GetOrganizationId

`func (o *ClientBillableView) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ClientBillableView) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ClientBillableView) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetProjectId

`func (o *ClientBillableView) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *ClientBillableView) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *ClientBillableView) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.


### SetProjectIdNil

`func (o *ClientBillableView) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *ClientBillableView) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil
### GetQuantity

`func (o *ClientBillableView) GetQuantity() string`

GetQuantity returns the Quantity field if non-nil, zero value otherwise.

### GetQuantityOk

`func (o *ClientBillableView) GetQuantityOk() (*string, bool)`

GetQuantityOk returns a tuple with the Quantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuantity

`func (o *ClientBillableView) SetQuantity(v string)`

SetQuantity sets Quantity field to given value.


### GetRateSnapshot

`func (o *ClientBillableView) GetRateSnapshot() ClientBillableRateSnapshot`

GetRateSnapshot returns the RateSnapshot field if non-nil, zero value otherwise.

### GetRateSnapshotOk

`func (o *ClientBillableView) GetRateSnapshotOk() (*ClientBillableRateSnapshot, bool)`

GetRateSnapshotOk returns a tuple with the RateSnapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRateSnapshot

`func (o *ClientBillableView) SetRateSnapshot(v ClientBillableRateSnapshot)`

SetRateSnapshot sets RateSnapshot field to given value.


### GetReplacesBillableId

`func (o *ClientBillableView) GetReplacesBillableId() string`

GetReplacesBillableId returns the ReplacesBillableId field if non-nil, zero value otherwise.

### GetReplacesBillableIdOk

`func (o *ClientBillableView) GetReplacesBillableIdOk() (*string, bool)`

GetReplacesBillableIdOk returns a tuple with the ReplacesBillableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacesBillableId

`func (o *ClientBillableView) SetReplacesBillableId(v string)`

SetReplacesBillableId sets ReplacesBillableId field to given value.


### SetReplacesBillableIdNil

`func (o *ClientBillableView) SetReplacesBillableIdNil(b bool)`

 SetReplacesBillableIdNil sets the value for ReplacesBillableId to be an explicit nil

### UnsetReplacesBillableId
`func (o *ClientBillableView) UnsetReplacesBillableId()`

UnsetReplacesBillableId ensures that no value is present for ReplacesBillableId, not even an explicit nil
### GetSource

`func (o *ClientBillableView) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ClientBillableView) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ClientBillableView) SetSource(v string)`

SetSource sets Source field to given value.


### GetSourceEntityId

`func (o *ClientBillableView) GetSourceEntityId() string`

GetSourceEntityId returns the SourceEntityId field if non-nil, zero value otherwise.

### GetSourceEntityIdOk

`func (o *ClientBillableView) GetSourceEntityIdOk() (*string, bool)`

GetSourceEntityIdOk returns a tuple with the SourceEntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceEntityId

`func (o *ClientBillableView) SetSourceEntityId(v string)`

SetSourceEntityId sets SourceEntityId field to given value.


### SetSourceEntityIdNil

`func (o *ClientBillableView) SetSourceEntityIdNil(b bool)`

 SetSourceEntityIdNil sets the value for SourceEntityId to be an explicit nil

### UnsetSourceEntityId
`func (o *ClientBillableView) UnsetSourceEntityId()`

UnsetSourceEntityId ensures that no value is present for SourceEntityId, not even an explicit nil
### GetSourceEntityType

`func (o *ClientBillableView) GetSourceEntityType() string`

GetSourceEntityType returns the SourceEntityType field if non-nil, zero value otherwise.

### GetSourceEntityTypeOk

`func (o *ClientBillableView) GetSourceEntityTypeOk() (*string, bool)`

GetSourceEntityTypeOk returns a tuple with the SourceEntityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceEntityType

`func (o *ClientBillableView) SetSourceEntityType(v string)`

SetSourceEntityType sets SourceEntityType field to given value.


### SetSourceEntityTypeNil

`func (o *ClientBillableView) SetSourceEntityTypeNil(b bool)`

 SetSourceEntityTypeNil sets the value for SourceEntityType to be an explicit nil

### UnsetSourceEntityType
`func (o *ClientBillableView) UnsetSourceEntityType()`

UnsetSourceEntityType ensures that no value is present for SourceEntityType, not even an explicit nil
### GetSourceEvidence

`func (o *ClientBillableView) GetSourceEvidence() map[string]interface{}`

GetSourceEvidence returns the SourceEvidence field if non-nil, zero value otherwise.

### GetSourceEvidenceOk

`func (o *ClientBillableView) GetSourceEvidenceOk() (*map[string]interface{}, bool)`

GetSourceEvidenceOk returns a tuple with the SourceEvidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceEvidence

`func (o *ClientBillableView) SetSourceEvidence(v map[string]interface{})`

SetSourceEvidence sets SourceEvidence field to given value.


### GetTaxClass

`func (o *ClientBillableView) GetTaxClass() string`

GetTaxClass returns the TaxClass field if non-nil, zero value otherwise.

### GetTaxClassOk

`func (o *ClientBillableView) GetTaxClassOk() (*string, bool)`

GetTaxClassOk returns a tuple with the TaxClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxClass

`func (o *ClientBillableView) SetTaxClass(v string)`

SetTaxClass sets TaxClass field to given value.


### GetUnit

`func (o *ClientBillableView) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *ClientBillableView) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *ClientBillableView) SetUnit(v string)`

SetUnit sets Unit field to given value.


### GetUnitPriceMicros

`func (o *ClientBillableView) GetUnitPriceMicros() int64`

GetUnitPriceMicros returns the UnitPriceMicros field if non-nil, zero value otherwise.

### GetUnitPriceMicrosOk

`func (o *ClientBillableView) GetUnitPriceMicrosOk() (*int64, bool)`

GetUnitPriceMicrosOk returns a tuple with the UnitPriceMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitPriceMicros

`func (o *ClientBillableView) SetUnitPriceMicros(v int64)`

SetUnitPriceMicros sets UnitPriceMicros field to given value.


### GetVoidedByBillableId

`func (o *ClientBillableView) GetVoidedByBillableId() string`

GetVoidedByBillableId returns the VoidedByBillableId field if non-nil, zero value otherwise.

### GetVoidedByBillableIdOk

`func (o *ClientBillableView) GetVoidedByBillableIdOk() (*string, bool)`

GetVoidedByBillableIdOk returns a tuple with the VoidedByBillableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoidedByBillableId

`func (o *ClientBillableView) SetVoidedByBillableId(v string)`

SetVoidedByBillableId sets VoidedByBillableId field to given value.


### SetVoidedByBillableIdNil

`func (o *ClientBillableView) SetVoidedByBillableIdNil(b bool)`

 SetVoidedByBillableIdNil sets the value for VoidedByBillableId to be an explicit nil

### UnsetVoidedByBillableId
`func (o *ClientBillableView) UnsetVoidedByBillableId()`

UnsetVoidedByBillableId ensures that no value is present for VoidedByBillableId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


