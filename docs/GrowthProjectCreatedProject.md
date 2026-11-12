# GrowthProjectCreatedProject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArchivedAt** | **NullableString** |  |
**ClientAccountId** | **NullableString** |  |
**CreatedAt** | **string** |  |
**GrowthAutopilot** | **bool** |  |
**GrowthDailyBudgetMicros** | **NullableInt64** |  |
**GrowthSendingSchedule** | [**NullableCreateGrowthPlaySendingSchedule**](CreateGrowthPlaySendingSchedule.md) |  |
**Id** | **string** |  |
**Kind** | **string** |  |
**Name** | **string** |  |
**Slug** | **string** |  |

## Methods

### NewGrowthProjectCreatedProject

`func NewGrowthProjectCreatedProject(archivedAt NullableString, clientAccountId NullableString, createdAt string, growthAutopilot bool, growthDailyBudgetMicros NullableInt64, growthSendingSchedule NullableCreateGrowthPlaySendingSchedule, id string, kind string, name string, slug string, ) *GrowthProjectCreatedProject`

NewGrowthProjectCreatedProject instantiates a new GrowthProjectCreatedProject object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewGrowthProjectCreatedProjectWithDefaults

`func NewGrowthProjectCreatedProjectWithDefaults() *GrowthProjectCreatedProject`

NewGrowthProjectCreatedProjectWithDefaults instantiates a new GrowthProjectCreatedProject object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetArchivedAt

`func (o *GrowthProjectCreatedProject) GetArchivedAt() string`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *GrowthProjectCreatedProject) GetArchivedAtOk() (*string, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *GrowthProjectCreatedProject) SetArchivedAt(v string)`

SetArchivedAt sets ArchivedAt field to given value.


### SetArchivedAtNil

`func (o *GrowthProjectCreatedProject) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *GrowthProjectCreatedProject) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetClientAccountId

`func (o *GrowthProjectCreatedProject) GetClientAccountId() string`

GetClientAccountId returns the ClientAccountId field if non-nil, zero value otherwise.

### GetClientAccountIdOk

`func (o *GrowthProjectCreatedProject) GetClientAccountIdOk() (*string, bool)`

GetClientAccountIdOk returns a tuple with the ClientAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientAccountId

`func (o *GrowthProjectCreatedProject) SetClientAccountId(v string)`

SetClientAccountId sets ClientAccountId field to given value.


### SetClientAccountIdNil

`func (o *GrowthProjectCreatedProject) SetClientAccountIdNil(b bool)`

 SetClientAccountIdNil sets the value for ClientAccountId to be an explicit nil

### UnsetClientAccountId
`func (o *GrowthProjectCreatedProject) UnsetClientAccountId()`

UnsetClientAccountId ensures that no value is present for ClientAccountId, not even an explicit nil
### GetCreatedAt

`func (o *GrowthProjectCreatedProject) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GrowthProjectCreatedProject) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GrowthProjectCreatedProject) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetGrowthAutopilot

`func (o *GrowthProjectCreatedProject) GetGrowthAutopilot() bool`

GetGrowthAutopilot returns the GrowthAutopilot field if non-nil, zero value otherwise.

### GetGrowthAutopilotOk

`func (o *GrowthProjectCreatedProject) GetGrowthAutopilotOk() (*bool, bool)`

GetGrowthAutopilotOk returns a tuple with the GrowthAutopilot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthAutopilot

`func (o *GrowthProjectCreatedProject) SetGrowthAutopilot(v bool)`

SetGrowthAutopilot sets GrowthAutopilot field to given value.


### GetGrowthDailyBudgetMicros

`func (o *GrowthProjectCreatedProject) GetGrowthDailyBudgetMicros() int64`

GetGrowthDailyBudgetMicros returns the GrowthDailyBudgetMicros field if non-nil, zero value otherwise.

### GetGrowthDailyBudgetMicrosOk

`func (o *GrowthProjectCreatedProject) GetGrowthDailyBudgetMicrosOk() (*int64, bool)`

GetGrowthDailyBudgetMicrosOk returns a tuple with the GrowthDailyBudgetMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthDailyBudgetMicros

`func (o *GrowthProjectCreatedProject) SetGrowthDailyBudgetMicros(v int64)`

SetGrowthDailyBudgetMicros sets GrowthDailyBudgetMicros field to given value.


### SetGrowthDailyBudgetMicrosNil

`func (o *GrowthProjectCreatedProject) SetGrowthDailyBudgetMicrosNil(b bool)`

 SetGrowthDailyBudgetMicrosNil sets the value for GrowthDailyBudgetMicros to be an explicit nil

### UnsetGrowthDailyBudgetMicros
`func (o *GrowthProjectCreatedProject) UnsetGrowthDailyBudgetMicros()`

UnsetGrowthDailyBudgetMicros ensures that no value is present for GrowthDailyBudgetMicros, not even an explicit nil
### GetGrowthSendingSchedule

`func (o *GrowthProjectCreatedProject) GetGrowthSendingSchedule() CreateGrowthPlaySendingSchedule`

GetGrowthSendingSchedule returns the GrowthSendingSchedule field if non-nil, zero value otherwise.

### GetGrowthSendingScheduleOk

`func (o *GrowthProjectCreatedProject) GetGrowthSendingScheduleOk() (*CreateGrowthPlaySendingSchedule, bool)`

GetGrowthSendingScheduleOk returns a tuple with the GrowthSendingSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrowthSendingSchedule

`func (o *GrowthProjectCreatedProject) SetGrowthSendingSchedule(v CreateGrowthPlaySendingSchedule)`

SetGrowthSendingSchedule sets GrowthSendingSchedule field to given value.


### SetGrowthSendingScheduleNil

`func (o *GrowthProjectCreatedProject) SetGrowthSendingScheduleNil(b bool)`

 SetGrowthSendingScheduleNil sets the value for GrowthSendingSchedule to be an explicit nil

### UnsetGrowthSendingSchedule
`func (o *GrowthProjectCreatedProject) UnsetGrowthSendingSchedule()`

UnsetGrowthSendingSchedule ensures that no value is present for GrowthSendingSchedule, not even an explicit nil
### GetId

`func (o *GrowthProjectCreatedProject) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GrowthProjectCreatedProject) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GrowthProjectCreatedProject) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *GrowthProjectCreatedProject) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *GrowthProjectCreatedProject) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *GrowthProjectCreatedProject) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *GrowthProjectCreatedProject) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GrowthProjectCreatedProject) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GrowthProjectCreatedProject) SetName(v string)`

SetName sets Name field to given value.


### GetSlug

`func (o *GrowthProjectCreatedProject) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *GrowthProjectCreatedProject) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *GrowthProjectCreatedProject) SetSlug(v string)`

SetSlug sets Slug field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


