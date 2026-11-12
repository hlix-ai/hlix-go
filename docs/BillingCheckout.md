# BillingCheckout

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plan** | **string** |  |
**SuccessUrl** | Pointer to **string** |  | [optional]

## Methods

### NewBillingCheckout

`func NewBillingCheckout(plan string, ) *BillingCheckout`

NewBillingCheckout instantiates a new BillingCheckout object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewBillingCheckoutWithDefaults

`func NewBillingCheckoutWithDefaults() *BillingCheckout`

NewBillingCheckoutWithDefaults instantiates a new BillingCheckout object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetPlan

`func (o *BillingCheckout) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *BillingCheckout) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *BillingCheckout) SetPlan(v string)`

SetPlan sets Plan field to given value.


### GetSuccessUrl

`func (o *BillingCheckout) GetSuccessUrl() string`

GetSuccessUrl returns the SuccessUrl field if non-nil, zero value otherwise.

### GetSuccessUrlOk

`func (o *BillingCheckout) GetSuccessUrlOk() (*string, bool)`

GetSuccessUrlOk returns a tuple with the SuccessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessUrl

`func (o *BillingCheckout) SetSuccessUrl(v string)`

SetSuccessUrl sets SuccessUrl field to given value.

### HasSuccessUrl

`func (o *BillingCheckout) HasSuccessUrl() bool`

HasSuccessUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


