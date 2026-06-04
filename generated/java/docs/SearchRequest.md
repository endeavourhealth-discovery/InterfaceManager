

# SearchRequest


## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
|**termFilter** | **String** | Plain text, space separated list of terms |  [optional] |
|**index** | **String** |  |  [optional] |
|**statusFilter** | **List&lt;String&gt;** | List of entity status IRI&#39;s |  [optional] |
|**typeFilter** | **List&lt;String&gt;** | List of entity type IRI&#39;s |  [optional] |
|**schemeFilter** | **List&lt;String&gt;** | List of code scheme IRI&#39;s |  [optional] |
|**bindingFilter** | [**List&lt;SearchBinding&gt;**](SearchBinding.md) | List of binding node and path IRI&#39;s |  [optional] |
|**markIfDescendentOf** | **List&lt;String&gt;** | Marks the results if they are descendants of any of these entities, but does not filter by them |  [optional] |
|**isA** | **List&lt;String&gt;** | List of IRIs that must be supertypes of the matches |  [optional] |
|**memberOf** | **List&lt;String&gt;** | List of set IRIs that the match must be a member of |  [optional] |
|**page** | **Integer** | The search result page number to retrieve |  [optional] |
|**size** | **Integer** | The number of results to retrieve per page |  [optional] |
|**from** | **Integer** |  |  [optional] |
|**select** | **List&lt;String&gt;** | list of fields or property paths from search result summary to return |  [optional] |
|**orderBy** | [**List&lt;OrderBy&gt;**](OrderBy.md) |  |  [optional] |
|**filter** | [**List&lt;Filter&gt;**](Filter.md) |  |  [optional] |
|**timings** | **List&lt;Map&lt;String, String&gt;&gt;** |  |  [optional] |



