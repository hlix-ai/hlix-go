# TreeListing

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ignored** | Pointer to **[]string** |  | [optional]
**Paths** | **[]string** |  |
**Ref** | [**FileContentRef**](FileContentRef.md) |  |
**RepoKey** | **string** |  |
**Tree** | **NullableString** |  |
**Truncated** | **bool** |  |

## Methods

### NewTreeListing

`func NewTreeListing(paths []string, ref FileContentRef, repoKey string, tree NullableString, truncated bool, ) *TreeListing`

NewTreeListing instantiates a new TreeListing object
This constructor sets required properties and applies declared defaults.
Its arguments change when the model's required properties change.

### NewTreeListingWithDefaults

`func NewTreeListingWithDefaults() *TreeListing`

NewTreeListingWithDefaults instantiates a new TreeListing object
This constructor applies declared defaults. It does not ensure required properties are set.

### GetIgnored

`func (o *TreeListing) GetIgnored() []string`

GetIgnored returns the Ignored field if non-nil, zero value otherwise.

### GetIgnoredOk

`func (o *TreeListing) GetIgnoredOk() (*[]string, bool)`

GetIgnoredOk returns a tuple with the Ignored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIgnored

`func (o *TreeListing) SetIgnored(v []string)`

SetIgnored sets Ignored field to given value.

### HasIgnored

`func (o *TreeListing) HasIgnored() bool`

HasIgnored returns a boolean if a field has been set.

### GetPaths

`func (o *TreeListing) GetPaths() []string`

GetPaths returns the Paths field if non-nil, zero value otherwise.

### GetPathsOk

`func (o *TreeListing) GetPathsOk() (*[]string, bool)`

GetPathsOk returns a tuple with the Paths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaths

`func (o *TreeListing) SetPaths(v []string)`

SetPaths sets Paths field to given value.


### GetRef

`func (o *TreeListing) GetRef() FileContentRef`

GetRef returns the Ref field if non-nil, zero value otherwise.

### GetRefOk

`func (o *TreeListing) GetRefOk() (*FileContentRef, bool)`

GetRefOk returns a tuple with the Ref field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRef

`func (o *TreeListing) SetRef(v FileContentRef)`

SetRef sets Ref field to given value.


### GetRepoKey

`func (o *TreeListing) GetRepoKey() string`

GetRepoKey returns the RepoKey field if non-nil, zero value otherwise.

### GetRepoKeyOk

`func (o *TreeListing) GetRepoKeyOk() (*string, bool)`

GetRepoKeyOk returns a tuple with the RepoKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoKey

`func (o *TreeListing) SetRepoKey(v string)`

SetRepoKey sets RepoKey field to given value.


### GetTree

`func (o *TreeListing) GetTree() string`

GetTree returns the Tree field if non-nil, zero value otherwise.

### GetTreeOk

`func (o *TreeListing) GetTreeOk() (*string, bool)`

GetTreeOk returns a tuple with the Tree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTree

`func (o *TreeListing) SetTree(v string)`

SetTree sets Tree field to given value.


### SetTreeNil

`func (o *TreeListing) SetTreeNil(b bool)`

 SetTreeNil sets the value for Tree to be an explicit nil

### UnsetTree
`func (o *TreeListing) UnsetTree()`

UnsetTree ensures that no value is present for Tree, not even an explicit nil
### GetTruncated

`func (o *TreeListing) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *TreeListing) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *TreeListing) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


