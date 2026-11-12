# OrgBillingStateOrdersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **NullableFloat32** |  |
**CreatedAt** | **string** |  |
**Currency** | **string** |  |
**Id** | **string** |  |
**Product** | [**OrgBillingStateActiveSubscriptionsInnerProduct**](OrgBillingStateActiveSubscriptionsInnerProduct.md) |  |
**Status** | **string** |  |

## Methods

### NewOrgBillingStateOrdersInner

`func NewOrgBillingStateOrdersInner(amount NullableFloat32, createdAt string, currency string, id string, product OrgBillingStateActiveSubscriptionsInnerProduct, status string, ) *OrgBillingStateOrdersInner`

NewOrgBillingStateOrdersInner instantiates a new OrgBillingStateOrdersInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewOrgBillingStateOrdersInnerWithDefaults

`func NewOrgBillingStateOrdersInnerWithDefaults() *OrgBillingStateOrdersInner`

NewOrgBillingStateOrdersInnerWithDefaults instantiates a new OrgBillingStateOrdersInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetAmount

`func (o *OrgBillingStateOrdersInner) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *OrgBillingStateOrdersInner) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *OrgBillingStateOrdersInner) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### SetAmountNil

`func (o *OrgBillingStateOrdersInner) SetAmountNil(b bool)`

 SetAmountNil sets the value for Amount to be an explicit nil

### UnsetAmount
`func (o *OrgBillingStateOrdersInner) UnsetAmount()`

UnsetAmount ensures that no value is present for Amount, not even an explicit nil
### GetCreatedAt

`func (o *OrgBillingStateOrdersInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OrgBillingStateOrdersInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OrgBillingStateOrdersInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCurrency

`func (o *OrgBillingStateOrdersInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *OrgBillingStateOrdersInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *OrgBillingStateOrdersInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetId

`func (o *OrgBillingStateOrdersInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OrgBillingStateOrdersInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OrgBillingStateOrdersInner) SetId(v string)`

SetId sets Id field to given value.


### GetProduct

`func (o *OrgBillingStateOrdersInner) GetProduct() OrgBillingStateActiveSubscriptionsInnerProduct`

GetProduct returns the Product field if non-nil, zero value otherwise.

### GetProductOk

`func (o *OrgBillingStateOrdersInner) GetProductOk() (*OrgBillingStateActiveSubscriptionsInnerProduct, bool)`

GetProductOk returns a tuple with the Product field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProduct

`func (o *OrgBillingStateOrdersInner) SetProduct(v OrgBillingStateActiveSubscriptionsInnerProduct)`

SetProduct sets Product field to given value.


### GetStatus

`func (o *OrgBillingStateOrdersInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrgBillingStateOrdersInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrgBillingStateOrdersInner) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


