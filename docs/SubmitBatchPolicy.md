# SubmitBatchPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApprovalRef** | Pointer to **string** |  | [optional]
**SensitiveDataApproved** | **bool** |  |

## Methods

### NewSubmitBatchPolicy

`func NewSubmitBatchPolicy(sensitiveDataApproved bool, ) *SubmitBatchPolicy`

NewSubmitBatchPolicy instantiates a new SubmitBatchPolicy object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewSubmitBatchPolicyWithDefaults

`func NewSubmitBatchPolicyWithDefaults() *SubmitBatchPolicy`

NewSubmitBatchPolicyWithDefaults instantiates a new SubmitBatchPolicy object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetApprovalRef

`func (o *SubmitBatchPolicy) GetApprovalRef() string`

GetApprovalRef returns the ApprovalRef field if non-nil, zero value otherwise.

### GetApprovalRefOk

`func (o *SubmitBatchPolicy) GetApprovalRefOk() (*string, bool)`

GetApprovalRefOk returns a tuple with the ApprovalRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalRef

`func (o *SubmitBatchPolicy) SetApprovalRef(v string)`

SetApprovalRef sets ApprovalRef field to given value.

### HasApprovalRef

`func (o *SubmitBatchPolicy) HasApprovalRef() bool`

HasApprovalRef returns a boolean if a field has been set.

### GetSensitiveDataApproved

`func (o *SubmitBatchPolicy) GetSensitiveDataApproved() bool`

GetSensitiveDataApproved returns the SensitiveDataApproved field if non-nil, zero value otherwise.

### GetSensitiveDataApprovedOk

`func (o *SubmitBatchPolicy) GetSensitiveDataApprovedOk() (*bool, bool)`

GetSensitiveDataApprovedOk returns a tuple with the SensitiveDataApproved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSensitiveDataApproved

`func (o *SubmitBatchPolicy) SetSensitiveDataApproved(v bool)`

SetSensitiveDataApproved sets SensitiveDataApproved field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


