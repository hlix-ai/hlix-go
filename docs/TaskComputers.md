# TaskComputers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Computers** | [**[]TaskComputersComputersInner**](TaskComputersComputersInner.md) |  | 
**Environment** | [**TaskComputersEnvironment**](TaskComputersEnvironment.md) |  | 

## Methods

### NewTaskComputers

`func NewTaskComputers(computers []TaskComputersComputersInner, environment TaskComputersEnvironment, ) *TaskComputers`

NewTaskComputers instantiates a new TaskComputers object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskComputersWithDefaults

`func NewTaskComputersWithDefaults() *TaskComputers`

NewTaskComputersWithDefaults instantiates a new TaskComputers object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComputers

`func (o *TaskComputers) GetComputers() []TaskComputersComputersInner`

GetComputers returns the Computers field if non-nil, zero value otherwise.

### GetComputersOk

`func (o *TaskComputers) GetComputersOk() (*[]TaskComputersComputersInner, bool)`

GetComputersOk returns a tuple with the Computers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComputers

`func (o *TaskComputers) SetComputers(v []TaskComputersComputersInner)`

SetComputers sets Computers field to given value.


### GetEnvironment

`func (o *TaskComputers) GetEnvironment() TaskComputersEnvironment`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *TaskComputers) GetEnvironmentOk() (*TaskComputersEnvironment, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *TaskComputers) SetEnvironment(v TaskComputersEnvironment)`

SetEnvironment sets Environment field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


