# ToolSearchResultToolsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountingOwner** | **string** |  |
**Availability** | [**ToolDescriptorAvailability**](ToolDescriptorAvailability.md) |  |
**Description** | **string** |  |
**FundingModes** | **[]string** |  |
**Id** | **string** |  |
**InputSchema** | **map[string]interface{}** |  |
**Name** | **string** |  |
**Provider** | **string** |  |
**Retry** | [**ToolDescriptorRetry**](ToolDescriptorRetry.md) |  |

## Methods

### NewToolSearchResultToolsInner

`func NewToolSearchResultToolsInner(accountingOwner string, availability ToolDescriptorAvailability, description string, fundingModes []string, id string, inputSchema map[string]interface{}, name string, provider string, retry ToolDescriptorRetry, ) *ToolSearchResultToolsInner`

NewToolSearchResultToolsInner instantiates a new ToolSearchResultToolsInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewToolSearchResultToolsInnerWithDefaults

`func NewToolSearchResultToolsInnerWithDefaults() *ToolSearchResultToolsInner`

NewToolSearchResultToolsInnerWithDefaults instantiates a new ToolSearchResultToolsInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAccountingOwner

`func (o *ToolSearchResultToolsInner) GetAccountingOwner() string`

GetAccountingOwner returns the AccountingOwner field if non-nil, zero value otherwise.

### GetAccountingOwnerOk

`func (o *ToolSearchResultToolsInner) GetAccountingOwnerOk() (*string, bool)`

GetAccountingOwnerOk returns a tuple with the AccountingOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingOwner

`func (o *ToolSearchResultToolsInner) SetAccountingOwner(v string)`

SetAccountingOwner sets AccountingOwner field to given value.


### GetAvailability

`func (o *ToolSearchResultToolsInner) GetAvailability() ToolDescriptorAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ToolSearchResultToolsInner) GetAvailabilityOk() (*ToolDescriptorAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ToolSearchResultToolsInner) SetAvailability(v ToolDescriptorAvailability)`

SetAvailability sets Availability field to given value.


### GetDescription

`func (o *ToolSearchResultToolsInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ToolSearchResultToolsInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ToolSearchResultToolsInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetFundingModes

`func (o *ToolSearchResultToolsInner) GetFundingModes() []string`

GetFundingModes returns the FundingModes field if non-nil, zero value otherwise.

### GetFundingModesOk

`func (o *ToolSearchResultToolsInner) GetFundingModesOk() (*[]string, bool)`

GetFundingModesOk returns a tuple with the FundingModes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundingModes

`func (o *ToolSearchResultToolsInner) SetFundingModes(v []string)`

SetFundingModes sets FundingModes field to given value.


### GetId

`func (o *ToolSearchResultToolsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ToolSearchResultToolsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ToolSearchResultToolsInner) SetId(v string)`

SetId sets Id field to given value.


### GetInputSchema

`func (o *ToolSearchResultToolsInner) GetInputSchema() map[string]interface{}`

GetInputSchema returns the InputSchema field if non-nil, zero value otherwise.

### GetInputSchemaOk

`func (o *ToolSearchResultToolsInner) GetInputSchemaOk() (*map[string]interface{}, bool)`

GetInputSchemaOk returns a tuple with the InputSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputSchema

`func (o *ToolSearchResultToolsInner) SetInputSchema(v map[string]interface{})`

SetInputSchema sets InputSchema field to given value.


### GetName

`func (o *ToolSearchResultToolsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ToolSearchResultToolsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ToolSearchResultToolsInner) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *ToolSearchResultToolsInner) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ToolSearchResultToolsInner) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ToolSearchResultToolsInner) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetRetry

`func (o *ToolSearchResultToolsInner) GetRetry() ToolDescriptorRetry`

GetRetry returns the Retry field if non-nil, zero value otherwise.

### GetRetryOk

`func (o *ToolSearchResultToolsInner) GetRetryOk() (*ToolDescriptorRetry, bool)`

GetRetryOk returns a tuple with the Retry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetry

`func (o *ToolSearchResultToolsInner) SetRetry(v ToolDescriptorRetry)`

SetRetry sets Retry field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


