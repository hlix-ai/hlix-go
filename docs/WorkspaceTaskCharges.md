# WorkspaceTaskCharges

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillingMode** | **string** |  | 
**Charges** | [**[]WorkspaceTaskChargesChargesInner**](WorkspaceTaskChargesChargesInner.md) |  | 

## Methods

### NewWorkspaceTaskCharges

`func NewWorkspaceTaskCharges(billingMode string, charges []WorkspaceTaskChargesChargesInner, ) *WorkspaceTaskCharges`

NewWorkspaceTaskCharges instantiates a new WorkspaceTaskCharges object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceTaskChargesWithDefaults

`func NewWorkspaceTaskChargesWithDefaults() *WorkspaceTaskCharges`

NewWorkspaceTaskChargesWithDefaults instantiates a new WorkspaceTaskCharges object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBillingMode

`func (o *WorkspaceTaskCharges) GetBillingMode() string`

GetBillingMode returns the BillingMode field if non-nil, zero value otherwise.

### GetBillingModeOk

`func (o *WorkspaceTaskCharges) GetBillingModeOk() (*string, bool)`

GetBillingModeOk returns a tuple with the BillingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMode

`func (o *WorkspaceTaskCharges) SetBillingMode(v string)`

SetBillingMode sets BillingMode field to given value.


### GetCharges

`func (o *WorkspaceTaskCharges) GetCharges() []WorkspaceTaskChargesChargesInner`

GetCharges returns the Charges field if non-nil, zero value otherwise.

### GetChargesOk

`func (o *WorkspaceTaskCharges) GetChargesOk() (*[]WorkspaceTaskChargesChargesInner, bool)`

GetChargesOk returns a tuple with the Charges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharges

`func (o *WorkspaceTaskCharges) SetCharges(v []WorkspaceTaskChargesChargesInner)`

SetCharges sets Charges field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


