
# ISearchRequest


## Properties

Name | Type
------------ | -------------
`termFilter` | string
`index` | string
`statusFilter` | Array&lt;string&gt;
`typeFilter` | Array&lt;string&gt;
`schemeFilter` | Array&lt;string&gt;
`bindingFilter` | [Array&lt;ISearchBinding&gt;](ISearchBinding.md)
`markIfDescendentOf` | Array&lt;string&gt;
`isA` | Array&lt;string&gt;
`memberOf` | Array&lt;string&gt;
`page` | number
`size` | number
`from` | number
`select` | Array&lt;string&gt;
`orderBy` | [Array&lt;IOrderBy&gt;](IOrderBy.md)
`filter` | [Array&lt;IFilter&gt;](IFilter.md)
`timings` | Array&lt;{ [key: string]: string; }&gt;

## Example

```typescript
import type { ISearchRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "termFilter": null,
  "index": null,
  "statusFilter": null,
  "typeFilter": null,
  "schemeFilter": null,
  "bindingFilter": null,
  "markIfDescendentOf": null,
  "isA": null,
  "memberOf": null,
  "page": null,
  "size": null,
  "from": null,
  "select": null,
  "orderBy": null,
  "filter": null,
  "timings": null,
} satisfies ISearchRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ISearchRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


