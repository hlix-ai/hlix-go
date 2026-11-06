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
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubmitBatchPolicyWithDefaults

`func NewSubmitBatchPolicyWithDefaults() *SubmitBatchPolicy`

NewSubmitBatchPolicyWithDefaults instantiates a new SubmitBatchPolicy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

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


