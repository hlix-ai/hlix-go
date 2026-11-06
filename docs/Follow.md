# Follow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **string** |  | 
**Id** | **string** |  | 
**Target** | [**NullableFollowedTarget**](FollowedTarget.md) |  | 
**TargetId** | **string** |  | 
**TargetType** | **string** |  | 

## Methods

### NewFollow

`func NewFollow(createdAt string, id string, target NullableFollowedTarget, targetId string, targetType string, ) *Follow`

NewFollow instantiates a new Follow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFollowWithDefaults

`func NewFollowWithDefaults() *Follow`

NewFollowWithDefaults instantiates a new Follow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *Follow) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Follow) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Follow) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *Follow) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Follow) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Follow) SetId(v string)`

SetId sets Id field to given value.


### GetTarget

`func (o *Follow) GetTarget() FollowedTarget`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *Follow) GetTargetOk() (*FollowedTarget, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *Follow) SetTarget(v FollowedTarget)`

SetTarget sets Target field to given value.


### SetTargetNil

`func (o *Follow) SetTargetNil(b bool)`

 SetTargetNil sets the value for Target to be an explicit nil

### UnsetTarget
`func (o *Follow) UnsetTarget()`

UnsetTarget ensures that no value is present for Target, not even an explicit nil
### GetTargetId

`func (o *Follow) GetTargetId() string`

GetTargetId returns the TargetId field if non-nil, zero value otherwise.

### GetTargetIdOk

`func (o *Follow) GetTargetIdOk() (*string, bool)`

GetTargetIdOk returns a tuple with the TargetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetId

`func (o *Follow) SetTargetId(v string)`

SetTargetId sets TargetId field to given value.


### GetTargetType

`func (o *Follow) GetTargetType() string`

GetTargetType returns the TargetType field if non-nil, zero value otherwise.

### GetTargetTypeOk

`func (o *Follow) GetTargetTypeOk() (*string, bool)`

GetTargetTypeOk returns a tuple with the TargetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetType

`func (o *Follow) SetTargetType(v string)`

SetTargetType sets TargetType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


