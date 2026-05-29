
# IPathQuery


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`source` | [ITTIriRef](ITTIriRef.md)
`target` | [ITTIriRef](ITTIriRef.md)
`depth` | number

## Example

```typescript
import type { IPathQuery } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "source": null,
  "target": null,
  "depth": null,
} satisfies IPathQuery

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IPathQuery
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


