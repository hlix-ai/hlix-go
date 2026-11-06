# ProjectReview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanMerge** | **bool** |  | 
**Journeys** | [**[]ProjectReviewJourneysInner**](ProjectReviewJourneysInner.md) |  | 
**PassedJourneys** | **int32** |  | 
**PullRequests** | [**[]ProjectReviewPullRequestsInner**](ProjectReviewPullRequestsInner.md) |  | 
**TotalJourneys** | **int32** |  | 
**VerifiedCycles** | **int32** |  | 

## Methods

### NewProjectReview

`func NewProjectReview(canMerge bool, journeys []ProjectReviewJourneysInner, passedJourneys int32, pullRequests []ProjectReviewPullRequestsInner, totalJourneys int32, verifiedCycles int32, ) *ProjectReview`

NewProjectReview instantiates a new ProjectReview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProjectReviewWithDefaults

`func NewProjectReviewWithDefaults() *ProjectReview`

NewProjectReviewWithDefaults instantiates a new ProjectReview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCanMerge

`func (o *ProjectReview) GetCanMerge() bool`

GetCanMerge returns the CanMerge field if non-nil, zero value otherwise.

### GetCanMergeOk

`func (o *ProjectReview) GetCanMergeOk() (*bool, bool)`

GetCanMergeOk returns a tuple with the CanMerge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanMerge

`func (o *ProjectReview) SetCanMerge(v bool)`

SetCanMerge sets CanMerge field to given value.


### GetJourneys

`func (o *ProjectReview) GetJourneys() []ProjectReviewJourneysInner`

GetJourneys returns the Journeys field if non-nil, zero value otherwise.

### GetJourneysOk

`func (o *ProjectReview) GetJourneysOk() (*[]ProjectReviewJourneysInner, bool)`

GetJourneysOk returns a tuple with the Journeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJourneys

`func (o *ProjectReview) SetJourneys(v []ProjectReviewJourneysInner)`

SetJourneys sets Journeys field to given value.


### GetPassedJourneys

`func (o *ProjectReview) GetPassedJourneys() int32`

GetPassedJourneys returns the PassedJourneys field if non-nil, zero value otherwise.

### GetPassedJourneysOk

`func (o *ProjectReview) GetPassedJourneysOk() (*int32, bool)`

GetPassedJourneysOk returns a tuple with the PassedJourneys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassedJourneys

`func (o *ProjectReview) SetPassedJourneys(v int32)`

SetPassedJourneys sets PassedJourneys field to given value.


### GetPullRequests

`func (o *ProjectReview) GetPullRequests() []ProjectReviewPullRequestsInner`

GetPullRequests returns the PullRequests field if non-nil, zero value otherwise.

### GetPullRequestsOk

`func (o *ProjectReview) GetPullRequestsOk() (*[]ProjectReviewPullRequestsInner, bool)`

GetPullRequestsOk returns a tuple with the PullRequests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPullRequests

`func (o *ProjectReview) SetPullRequests(v []ProjectReviewPullRequestsInner)`

SetPullRequests sets PullRequests field to given value.


### GetTotalJourneys

`func (o *ProjectReview) GetTotalJourneys() int32`

GetTotalJourneys returns the TotalJourneys field if non-nil, zero value otherwise.

### GetTotalJourneysOk

`func (o *ProjectReview) GetTotalJourneysOk() (*int32, bool)`

GetTotalJourneysOk returns a tuple with the TotalJourneys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalJourneys

`func (o *ProjectReview) SetTotalJourneys(v int32)`

SetTotalJourneys sets TotalJourneys field to given value.


### GetVerifiedCycles

`func (o *ProjectReview) GetVerifiedCycles() int32`

GetVerifiedCycles returns the VerifiedCycles field if non-nil, zero value otherwise.

### GetVerifiedCyclesOk

`func (o *ProjectReview) GetVerifiedCyclesOk() (*int32, bool)`

GetVerifiedCyclesOk returns a tuple with the VerifiedCycles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedCycles

`func (o *ProjectReview) SetVerifiedCycles(v int32)`

SetVerifiedCycles sets VerifiedCycles field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


