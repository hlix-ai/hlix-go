# AgencyOverviewReportAttentionInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActionPath** | Pointer to **string** |  | [optional]
**AttentionItem** | Pointer to [**AgencyOverviewReportAttentionInnerAttentionItem**](AgencyOverviewReportAttentionInnerAttentionItem.md) |  | [optional]
**CreatedAt** | **string** |  |
**CustomerId** | Pointer to **string** |  | [optional]
**Detail** | **string** |  |
**Id** | **string** |  |
**InvoiceId** | Pointer to **string** |  | [optional]
**Kind** | **string** |  |
**ProjectId** | Pointer to **string** |  | [optional]
**Severity** | **string** |  |
**Title** | **string** |  |

## Methods

### NewAgencyOverviewReportAttentionInner

`func NewAgencyOverviewReportAttentionInner(createdAt string, detail string, id string, kind string, severity string, title string, ) *AgencyOverviewReportAttentionInner`

NewAgencyOverviewReportAttentionInner instantiates a new AgencyOverviewReportAttentionInner object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewAgencyOverviewReportAttentionInnerWithDefaults

`func NewAgencyOverviewReportAttentionInnerWithDefaults() *AgencyOverviewReportAttentionInner`

NewAgencyOverviewReportAttentionInnerWithDefaults instantiates a new AgencyOverviewReportAttentionInner object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetActionPath

`func (o *AgencyOverviewReportAttentionInner) GetActionPath() string`

GetActionPath returns the ActionPath field if non-nil, zero value otherwise.

### GetActionPathOk

`func (o *AgencyOverviewReportAttentionInner) GetActionPathOk() (*string, bool)`

GetActionPathOk returns a tuple with the ActionPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionPath

`func (o *AgencyOverviewReportAttentionInner) SetActionPath(v string)`

SetActionPath sets ActionPath field to given value.

### HasActionPath

`func (o *AgencyOverviewReportAttentionInner) HasActionPath() bool`

HasActionPath returns a boolean if a field has been set.

### GetAttentionItem

`func (o *AgencyOverviewReportAttentionInner) GetAttentionItem() AgencyOverviewReportAttentionInnerAttentionItem`

GetAttentionItem returns the AttentionItem field if non-nil, zero value otherwise.

### GetAttentionItemOk

`func (o *AgencyOverviewReportAttentionInner) GetAttentionItemOk() (*AgencyOverviewReportAttentionInnerAttentionItem, bool)`

GetAttentionItemOk returns a tuple with the AttentionItem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttentionItem

`func (o *AgencyOverviewReportAttentionInner) SetAttentionItem(v AgencyOverviewReportAttentionInnerAttentionItem)`

SetAttentionItem sets AttentionItem field to given value.

### HasAttentionItem

`func (o *AgencyOverviewReportAttentionInner) HasAttentionItem() bool`

HasAttentionItem returns a boolean if a field has been set.

### GetCreatedAt

`func (o *AgencyOverviewReportAttentionInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AgencyOverviewReportAttentionInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AgencyOverviewReportAttentionInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCustomerId

`func (o *AgencyOverviewReportAttentionInner) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *AgencyOverviewReportAttentionInner) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *AgencyOverviewReportAttentionInner) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *AgencyOverviewReportAttentionInner) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDetail

`func (o *AgencyOverviewReportAttentionInner) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *AgencyOverviewReportAttentionInner) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *AgencyOverviewReportAttentionInner) SetDetail(v string)`

SetDetail sets Detail field to given value.


### GetId

`func (o *AgencyOverviewReportAttentionInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AgencyOverviewReportAttentionInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AgencyOverviewReportAttentionInner) SetId(v string)`

SetId sets Id field to given value.


### GetInvoiceId

`func (o *AgencyOverviewReportAttentionInner) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *AgencyOverviewReportAttentionInner) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *AgencyOverviewReportAttentionInner) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.

### HasInvoiceId

`func (o *AgencyOverviewReportAttentionInner) HasInvoiceId() bool`

HasInvoiceId returns a boolean if a field has been set.

### GetKind

`func (o *AgencyOverviewReportAttentionInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AgencyOverviewReportAttentionInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AgencyOverviewReportAttentionInner) SetKind(v string)`

SetKind sets Kind field to given value.


### GetProjectId

`func (o *AgencyOverviewReportAttentionInner) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *AgencyOverviewReportAttentionInner) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *AgencyOverviewReportAttentionInner) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *AgencyOverviewReportAttentionInner) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetSeverity

`func (o *AgencyOverviewReportAttentionInner) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *AgencyOverviewReportAttentionInner) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *AgencyOverviewReportAttentionInner) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetTitle

`func (o *AgencyOverviewReportAttentionInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AgencyOverviewReportAttentionInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AgencyOverviewReportAttentionInner) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


