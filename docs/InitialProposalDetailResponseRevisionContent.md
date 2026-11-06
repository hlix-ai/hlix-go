# InitialProposalDetailResponseRevisionContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Blocks** | [**[]InitialProposalDetailResponseRevisionContentBlocksInner**](InitialProposalDetailResponseRevisionContentBlocksInner.md) |  | 
**Brand** | [**InitialProposalDetailResponseRevisionContentBrand**](InitialProposalDetailResponseRevisionContentBrand.md) |  | 
**CustomerName** | **NullableString** |  | 
**Cycles** | [**[]InitialProposalDetailResponseRevisionContentCyclesInner**](InitialProposalDetailResponseRevisionContentCyclesInner.md) |  | 
**InitialScopeCredits** | **NullableInt32** |  | 
**QuoteComplete** | **bool** |  | 
**Title** | **string** |  | 

## Methods

### NewInitialProposalDetailResponseRevisionContent

`func NewInitialProposalDetailResponseRevisionContent(blocks []InitialProposalDetailResponseRevisionContentBlocksInner, brand InitialProposalDetailResponseRevisionContentBrand, customerName NullableString, cycles []InitialProposalDetailResponseRevisionContentCyclesInner, initialScopeCredits NullableInt32, quoteComplete bool, title string, ) *InitialProposalDetailResponseRevisionContent`

NewInitialProposalDetailResponseRevisionContent instantiates a new InitialProposalDetailResponseRevisionContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitialProposalDetailResponseRevisionContentWithDefaults

`func NewInitialProposalDetailResponseRevisionContentWithDefaults() *InitialProposalDetailResponseRevisionContent`

NewInitialProposalDetailResponseRevisionContentWithDefaults instantiates a new InitialProposalDetailResponseRevisionContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlocks

`func (o *InitialProposalDetailResponseRevisionContent) GetBlocks() []InitialProposalDetailResponseRevisionContentBlocksInner`

GetBlocks returns the Blocks field if non-nil, zero value otherwise.

### GetBlocksOk

`func (o *InitialProposalDetailResponseRevisionContent) GetBlocksOk() (*[]InitialProposalDetailResponseRevisionContentBlocksInner, bool)`

GetBlocksOk returns a tuple with the Blocks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlocks

`func (o *InitialProposalDetailResponseRevisionContent) SetBlocks(v []InitialProposalDetailResponseRevisionContentBlocksInner)`

SetBlocks sets Blocks field to given value.


### GetBrand

`func (o *InitialProposalDetailResponseRevisionContent) GetBrand() InitialProposalDetailResponseRevisionContentBrand`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *InitialProposalDetailResponseRevisionContent) GetBrandOk() (*InitialProposalDetailResponseRevisionContentBrand, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *InitialProposalDetailResponseRevisionContent) SetBrand(v InitialProposalDetailResponseRevisionContentBrand)`

SetBrand sets Brand field to given value.


### GetCustomerName

`func (o *InitialProposalDetailResponseRevisionContent) GetCustomerName() string`

GetCustomerName returns the CustomerName field if non-nil, zero value otherwise.

### GetCustomerNameOk

`func (o *InitialProposalDetailResponseRevisionContent) GetCustomerNameOk() (*string, bool)`

GetCustomerNameOk returns a tuple with the CustomerName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerName

`func (o *InitialProposalDetailResponseRevisionContent) SetCustomerName(v string)`

SetCustomerName sets CustomerName field to given value.


### SetCustomerNameNil

`func (o *InitialProposalDetailResponseRevisionContent) SetCustomerNameNil(b bool)`

 SetCustomerNameNil sets the value for CustomerName to be an explicit nil

### UnsetCustomerName
`func (o *InitialProposalDetailResponseRevisionContent) UnsetCustomerName()`

UnsetCustomerName ensures that no value is present for CustomerName, not even an explicit nil
### GetCycles

`func (o *InitialProposalDetailResponseRevisionContent) GetCycles() []InitialProposalDetailResponseRevisionContentCyclesInner`

GetCycles returns the Cycles field if non-nil, zero value otherwise.

### GetCyclesOk

`func (o *InitialProposalDetailResponseRevisionContent) GetCyclesOk() (*[]InitialProposalDetailResponseRevisionContentCyclesInner, bool)`

GetCyclesOk returns a tuple with the Cycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycles

`func (o *InitialProposalDetailResponseRevisionContent) SetCycles(v []InitialProposalDetailResponseRevisionContentCyclesInner)`

SetCycles sets Cycles field to given value.


### GetInitialScopeCredits

`func (o *InitialProposalDetailResponseRevisionContent) GetInitialScopeCredits() int32`

GetInitialScopeCredits returns the InitialScopeCredits field if non-nil, zero value otherwise.

### GetInitialScopeCreditsOk

`func (o *InitialProposalDetailResponseRevisionContent) GetInitialScopeCreditsOk() (*int32, bool)`

GetInitialScopeCreditsOk returns a tuple with the InitialScopeCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialScopeCredits

`func (o *InitialProposalDetailResponseRevisionContent) SetInitialScopeCredits(v int32)`

SetInitialScopeCredits sets InitialScopeCredits field to given value.


### SetInitialScopeCreditsNil

`func (o *InitialProposalDetailResponseRevisionContent) SetInitialScopeCreditsNil(b bool)`

 SetInitialScopeCreditsNil sets the value for InitialScopeCredits to be an explicit nil

### UnsetInitialScopeCredits
`func (o *InitialProposalDetailResponseRevisionContent) UnsetInitialScopeCredits()`

UnsetInitialScopeCredits ensures that no value is present for InitialScopeCredits, not even an explicit nil
### GetQuoteComplete

`func (o *InitialProposalDetailResponseRevisionContent) GetQuoteComplete() bool`

GetQuoteComplete returns the QuoteComplete field if non-nil, zero value otherwise.

### GetQuoteCompleteOk

`func (o *InitialProposalDetailResponseRevisionContent) GetQuoteCompleteOk() (*bool, bool)`

GetQuoteCompleteOk returns a tuple with the QuoteComplete field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuoteComplete

`func (o *InitialProposalDetailResponseRevisionContent) SetQuoteComplete(v bool)`

SetQuoteComplete sets QuoteComplete field to given value.


### GetTitle

`func (o *InitialProposalDetailResponseRevisionContent) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *InitialProposalDetailResponseRevisionContent) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *InitialProposalDetailResponseRevisionContent) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


