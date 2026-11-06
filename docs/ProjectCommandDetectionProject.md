# ProjectCommandDetectionProject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Detected** | [**NullableProjectCommandDetectionProjectDetected**](ProjectCommandDetectionProjectDetected.md) |  | 
**Reason** | **string** |  | 

## Methods

### NewProjectCommandDetectionProject

`func NewProjectCommandDetectionProject(detected NullableProjectCommandDetectionProjectDetected, reason string, ) *ProjectCommandDetectionProject`

NewProjectCommandDetectionProject instantiates a new ProjectCommandDetectionProject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectCommandDetectionProjectWithDefaults

`func NewProjectCommandDetectionProjectWithDefaults() *ProjectCommandDetectionProject`

NewProjectCommandDetectionProjectWithDefaults instantiates a new ProjectCommandDetectionProject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDetected

`func (o *ProjectCommandDetectionProject) GetDetected() ProjectCommandDetectionProjectDetected`

GetDetected returns the Detected field if non-nil, zero value otherwise.

### GetDetectedOk

`func (o *ProjectCommandDetectionProject) GetDetectedOk() (*ProjectCommandDetectionProjectDetected, bool)`

GetDetectedOk returns a tuple with the Detected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetected

`func (o *ProjectCommandDetectionProject) SetDetected(v ProjectCommandDetectionProjectDetected)`

SetDetected sets Detected field to given value.


### SetDetectedNil

`func (o *ProjectCommandDetectionProject) SetDetectedNil(b bool)`

 SetDetectedNil sets the value for Detected to be an explicit nil

### UnsetDetected
`func (o *ProjectCommandDetectionProject) UnsetDetected()`

UnsetDetected ensures that no value is present for Detected, not even an explicit nil
### GetReason

`func (o *ProjectCommandDetectionProject) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *ProjectCommandDetectionProject) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *ProjectCommandDetectionProject) SetReason(v string)`

SetReason sets Reason field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


