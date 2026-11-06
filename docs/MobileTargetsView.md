# MobileTargetsView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Configured** | **bool** |  | 
**Targets** | [**[]MobileTargetsInputTargetsInner**](MobileTargetsInputTargetsInner.md) |  | 

## Methods

### NewMobileTargetsView

`func NewMobileTargetsView(configured bool, targets []MobileTargetsInputTargetsInner, ) *MobileTargetsView`

NewMobileTargetsView instantiates a new MobileTargetsView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMobileTargetsViewWithDefaults

`func NewMobileTargetsViewWithDefaults() *MobileTargetsView`

NewMobileTargetsViewWithDefaults instantiates a new MobileTargetsView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigured

`func (o *MobileTargetsView) GetConfigured() bool`

GetConfigured returns the Configured field if non-nil, zero value otherwise.

### GetConfiguredOk

`func (o *MobileTargetsView) GetConfiguredOk() (*bool, bool)`

GetConfiguredOk returns a tuple with the Configured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigured

`func (o *MobileTargetsView) SetConfigured(v bool)`

SetConfigured sets Configured field to given value.


### GetTargets

`func (o *MobileTargetsView) GetTargets() []MobileTargetsInputTargetsInner`

GetTargets returns the Targets field if non-nil, zero value otherwise.

### GetTargetsOk

`func (o *MobileTargetsView) GetTargetsOk() (*[]MobileTargetsInputTargetsInner, bool)`

GetTargetsOk returns a tuple with the Targets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargets

`func (o *MobileTargetsView) SetTargets(v []MobileTargetsInputTargetsInner)`

SetTargets sets Targets field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


