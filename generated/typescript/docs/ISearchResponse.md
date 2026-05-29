
# ISearchResponse


## Properties

Name | Type
------------ | -------------
`page` | number
`count` | number
`totalCount` | number
`highestUsage` | number
`term` | string
`entities` | [Array&lt;ISearchResultSummary&gt;](ISearchResultSummary.md)
`exactMatch` | boolean

## Example

```typescript
import type { ISearchResponse } from ''

// TODO: Update the object below with actual values
const example = {
  "page": null,
  "count": null,
  "totalCount": null,
  "highestUsage": null,
  "term": null,
  "entities": null,
  "exactMatch": null,
} satisfies ISearchResponse

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ISearchResponse
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


