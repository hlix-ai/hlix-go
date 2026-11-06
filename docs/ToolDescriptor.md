# ToolDescriptor

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

### NewToolDescriptor

`func NewToolDescriptor(accountingOwner string, availability ToolDescriptorAvailability, description string, fundingModes []string, id string, inputSchema map[string]interface{}, name string, provider string, retry ToolDescriptorRetry, ) *ToolDescriptor`

NewToolDescriptor instantiates a new ToolDescriptor object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolDescriptorWithDefaults

`func NewToolDescriptorWithDefaults() *ToolDescriptor`

NewToolDescriptorWithDefaults instantiates a new ToolDescriptor object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountingOwner

`func (o *ToolDescriptor) GetAccountingOwner() string`

GetAccountingOwner returns the AccountingOwner field if non-nil, zero value otherwise.

### GetAccountingOwnerOk

`func (o *ToolDescriptor) GetAccountingOwnerOk() (*string, bool)`

GetAccountingOwnerOk returns a tuple with the AccountingOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountingOwner

`func (o *ToolDescriptor) SetAccountingOwner(v string)`

SetAccountingOwner sets AccountingOwner field to given value.


### GetAvailability

`func (o *ToolDescriptor) GetAvailability() ToolDescriptorAvailability`

GetAvailability returns the Availability field if non-nil, zero value otherwise.

### GetAvailabilityOk

`func (o *ToolDescriptor) GetAvailabilityOk() (*ToolDescriptorAvailability, bool)`

GetAvailabilityOk returns a tuple with the Availability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailability

`func (o *ToolDescriptor) SetAvailability(v ToolDescriptorAvailability)`

SetAvailability sets Availability field to given value.


### GetDescription

`func (o *ToolDescriptor) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ToolDescriptor) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ToolDescriptor) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetFundingModes

`func (o *ToolDescriptor) GetFundingModes() []string`

GetFundingModes returns the FundingModes field if non-nil, zero value otherwise.

### GetFundingModesOk

`func (o *ToolDescriptor) GetFundingModesOk() (*[]string, bool)`

GetFundingModesOk returns a tuple with the FundingModes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFundingModes

`func (o *ToolDescriptor) SetFundingModes(v []string)`

SetFundingModes sets FundingModes field to given value.


### GetId

`func (o *ToolDescriptor) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ToolDescriptor) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ToolDescriptor) SetId(v string)`

SetId sets Id field to given value.


### GetInputSchema

`func (o *ToolDescriptor) GetInputSchema() map[string]interface{}`

GetInputSchema returns the InputSchema field if non-nil, zero value otherwise.

### GetInputSchemaOk

`func (o *ToolDescriptor) GetInputSchemaOk() (*map[string]interface{}, bool)`

GetInputSchemaOk returns a tuple with the InputSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputSchema

`func (o *ToolDescriptor) SetInputSchema(v map[string]interface{})`

SetInputSchema sets InputSchema field to given value.


### GetName

`func (o *ToolDescriptor) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ToolDescriptor) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ToolDescriptor) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *ToolDescriptor) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ToolDescriptor) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ToolDescriptor) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetRetry

`func (o *ToolDescriptor) GetRetry() ToolDescriptorRetry`

GetRetry returns the Retry field if non-nil, zero value otherwise.

### GetRetryOk

`func (o *ToolDescriptor) GetRetryOk() (*ToolDescriptorRetry, bool)`

GetRetryOk returns a tuple with the Retry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetry

`func (o *ToolDescriptor) SetRetry(v ToolDescriptorRetry)`

SetRetry sets Retry field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


