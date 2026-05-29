
# ISearchRequest

## Properties
| Name | Type | Description | Notes |
| ------------ | ------------- | ------------- | ------------- |
| **termFilter** | **kotlin.String** | Plain text, space separated list of terms |  [optional] |
| **index** | **kotlin.String** |  |  [optional] |
| **statusFilter** | **kotlin.collections.List&lt;kotlin.String&gt;** | List of entity status IRI&#39;s |  [optional] |
| **typeFilter** | **kotlin.collections.List&lt;kotlin.String&gt;** | List of entity type IRI&#39;s |  [optional] |
| **schemeFilter** | **kotlin.collections.List&lt;kotlin.String&gt;** | List of code scheme IRI&#39;s |  [optional] |
| **bindingFilter** | [**kotlin.collections.List&lt;ISearchBinding&gt;**](ISearchBinding.md) | List of binding node and path IRI&#39;s |  [optional] |
| **markIfDescendentOf** | **kotlin.collections.List&lt;kotlin.String&gt;** | Marks the results if they are descendants of any of these entities, but does not filter by them |  [optional] |
| **isA** | **kotlin.collections.List&lt;kotlin.String&gt;** | List of IRIs that must be supertypes of the matches |  [optional] |
| **memberOf** | **kotlin.collections.List&lt;kotlin.String&gt;** | List of set IRIs that the match must be a member of |  [optional] |
| **page** | **kotlin.Int** | The search result page number to retrieve |  [optional] |
| **propertySize** | **kotlin.Int** | The number of results to retrieve per page |  [optional] |
| **from** | **kotlin.Int** |  |  [optional] |
| **select** | **kotlin.collections.List&lt;kotlin.String&gt;** | list of fields or property paths from search result summary to return |  [optional] |
| **orderBy** | [**kotlin.collections.List&lt;IOrderBy&gt;**](IOrderBy.md) |  |  [optional] |
| **filter** | [**kotlin.collections.List&lt;IFilter&gt;**](IFilter.md) |  |  [optional] |
| **timings** | **kotlin.collections.List&lt;kotlin.collections.Map&lt;kotlin.String, kotlin.String&gt;&gt;** |  |  [optional] |



