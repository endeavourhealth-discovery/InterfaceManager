
# IQueryRequest


## Properties

Name | Type
------------ | -------------
`context` | { [key: string]: string; }
`textSearch` | string
`argument` | [Array&lt;IArgument&gt;](IArgument.md)
`query` | [IQuery](IQuery.md)
`pathQuery` | [IPathQuery](IPathQuery.md)
`update` | [IUpdate](IUpdate.md)
`name` | string
`page` | [IPage](IPage.md)
`queryStringDefinition` | string
`askIri` | string
`timings` | Array&lt;{ [key: string]: string; }&gt;
`cohort` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`includeNames` | boolean
`textSearchStyle` | [TextSearchStyle](TextSearchStyle.md)
`language` | [DatabaseOption](DatabaseOption.md)

## Example

```typescript
import type { IQueryRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "context": null,
  "textSearch": null,
  "argument": null,
  "query": null,
  "pathQuery": null,
  "update": null,
  "name": null,
  "page": null,
  "queryStringDefinition": null,
  "askIri": null,
  "timings": null,
  "cohort": null,
  "includeNames": null,
  "textSearchStyle": null,
  "language": null,
} satisfies IQueryRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IQueryRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


