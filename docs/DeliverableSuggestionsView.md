# DeliverableSuggestionsView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Generated** | **bool** |  |
**SourceFingerprint** | **string** |  |
**Suggestions** | [**[]DeliverableSuggestionsViewSuggestionsInner**](DeliverableSuggestionsViewSuggestionsInner.md) |  |

## Methods

### NewDeliverableSuggestionsView

`func NewDeliverableSuggestionsView(generated bool, sourceFingerprint string, suggestions []DeliverableSuggestionsViewSuggestionsInner, ) *DeliverableSuggestionsView`

NewDeliverableSuggestionsView instantiates a new DeliverableSuggestionsView object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewDeliverableSuggestionsViewWithDefaults

`func NewDeliverableSuggestionsViewWithDefaults() *DeliverableSuggestionsView`

NewDeliverableSuggestionsViewWithDefaults instantiates a new DeliverableSuggestionsView object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetGenerated

`func (o *DeliverableSuggestionsView) GetGenerated() bool`

GetGenerated returns the Generated field if non-nil, zero value otherwise.

### GetGeneratedOk

`func (o *DeliverableSuggestionsView) GetGeneratedOk() (*bool, bool)`

GetGeneratedOk returns a tuple with the Generated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerated

`func (o *DeliverableSuggestionsView) SetGenerated(v bool)`

SetGenerated sets Generated field to given value.


### GetSourceFingerprint

`func (o *DeliverableSuggestionsView) GetSourceFingerprint() string`

GetSourceFingerprint returns the SourceFingerprint field if non-nil, zero value otherwise.

### GetSourceFingerprintOk

`func (o *DeliverableSuggestionsView) GetSourceFingerprintOk() (*string, bool)`

GetSourceFingerprintOk returns a tuple with the SourceFingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceFingerprint

`func (o *DeliverableSuggestionsView) SetSourceFingerprint(v string)`

SetSourceFingerprint sets SourceFingerprint field to given value.


### GetSuggestions

`func (o *DeliverableSuggestionsView) GetSuggestions() []DeliverableSuggestionsViewSuggestionsInner`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *DeliverableSuggestionsView) GetSuggestionsOk() (*[]DeliverableSuggestionsViewSuggestionsInner, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *DeliverableSuggestionsView) SetSuggestions(v []DeliverableSuggestionsViewSuggestionsInner)`

SetSuggestions sets Suggestions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


