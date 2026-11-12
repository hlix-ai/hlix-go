# OrgBillingState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActiveMeters** | [**[]OrgBillingStateActiveMetersInner**](OrgBillingStateActiveMetersInner.md) |  |
**ActiveSubscriptions** | [**[]OrgBillingStateActiveSubscriptionsInner**](OrgBillingStateActiveSubscriptionsInner.md) |  |
**BillingMode** | **string** |  |
**Configured** | **bool** |  |
**Credits** | [**NullableOrgBillingStateCredits**](OrgBillingStateCredits.md) |  |
**Entitlement** | [**OrgBillingStateEntitlement**](OrgBillingStateEntitlement.md) |  |
**Orders** | [**[]OrgBillingStateOrdersInner**](OrgBillingStateOrdersInner.md) |  |

## Methods

### NewOrgBillingState

`func NewOrgBillingState(activeMeters []OrgBillingStateActiveMetersInner, activeSubscriptions []OrgBillingStateActiveSubscriptionsInner, billingMode string, configured bool, credits NullableOrgBillingStateCredits, entitlement OrgBillingStateEntitlement, orders []OrgBillingStateOrdersInner, ) *OrgBillingState`

NewOrgBillingState instantiates a new OrgBillingState object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewOrgBillingStateWithDefaults

`func NewOrgBillingStateWithDefaults() *OrgBillingState`

NewOrgBillingStateWithDefaults instantiates a new OrgBillingState object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetActiveMeters

`func (o *OrgBillingState) GetActiveMeters() []OrgBillingStateActiveMetersInner`

GetActiveMeters returns the ActiveMeters field if non-nil, zero value otherwise.

### GetActiveMetersOk

`func (o *OrgBillingState) GetActiveMetersOk() (*[]OrgBillingStateActiveMetersInner, bool)`

GetActiveMetersOk returns a tuple with the ActiveMeters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveMeters

`func (o *OrgBillingState) SetActiveMeters(v []OrgBillingStateActiveMetersInner)`

SetActiveMeters sets ActiveMeters field to given value.


### GetActiveSubscriptions

`func (o *OrgBillingState) GetActiveSubscriptions() []OrgBillingStateActiveSubscriptionsInner`

GetActiveSubscriptions returns the ActiveSubscriptions field if non-nil, zero value otherwise.

### GetActiveSubscriptionsOk

`func (o *OrgBillingState) GetActiveSubscriptionsOk() (*[]OrgBillingStateActiveSubscriptionsInner, bool)`

GetActiveSubscriptionsOk returns a tuple with the ActiveSubscriptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveSubscriptions

`func (o *OrgBillingState) SetActiveSubscriptions(v []OrgBillingStateActiveSubscriptionsInner)`

SetActiveSubscriptions sets ActiveSubscriptions field to given value.


### GetBillingMode

`func (o *OrgBillingState) GetBillingMode() string`

GetBillingMode returns the BillingMode field if non-nil, zero value otherwise.

### GetBillingModeOk

`func (o *OrgBillingState) GetBillingModeOk() (*string, bool)`

GetBillingModeOk returns a tuple with the BillingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMode

`func (o *OrgBillingState) SetBillingMode(v string)`

SetBillingMode sets BillingMode field to given value.


### GetConfigured

`func (o *OrgBillingState) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *OrgBillingState) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *OrgBillingState) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetCredits

`func (o *OrgBillingState) GetCredits() OrgBillingStateCredits`

GetCredits returns the Credits field if non-nil, zero value otherwise.

### GetCreditsOk

`func (o *OrgBillingState) GetCreditsOk() (*OrgBillingStateCredits, bool)`

GetCreditsOk returns a tuple with the Credits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredits

`func (o *OrgBillingState) SetCredits(v OrgBillingStateCredits)`

SetCredits sets Credits field to given value.


### SetCreditsNil

`func (o *OrgBillingState) SetCreditsNil(b bool)`

 SetCreditsNil sets the value for Credits to be an explicit nil

### UnsetCredits
`func (o *OrgBillingState) UnsetCredits()`

UnsetCredits ensures that no value is present for Credits, not even an explicit nil
### GetEntitlement

`func (o *OrgBillingState) GetEntitlement() OrgBillingStateEntitlement`

GetEntitlement returns the Entitlement field if non-nil, zero value otherwise.

### GetEntitlementOk

`func (o *OrgBillingState) GetEntitlementOk() (*OrgBillingStateEntitlement, bool)`

GetEntitlementOk returns a tuple with the Entitlement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlement

`func (o *OrgBillingState) SetEntitlement(v OrgBillingStateEntitlement)`

SetEntitlement sets Entitlement field to given value.


### GetOrders

`func (o *OrgBillingState) GetOrders() []OrgBillingStateOrdersInner`

GetOrders returns the Orders field if non-nil, zero value otherwise.

### GetOrdersOk

`func (o *OrgBillingState) GetOrdersOk() (*[]OrgBillingStateOrdersInner, bool)`

GetOrdersOk returns a tuple with the Orders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrders

`func (o *OrgBillingState) SetOrders(v []OrgBillingStateOrdersInner)`

SetOrders sets Orders field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


