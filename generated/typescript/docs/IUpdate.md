
# IUpdate


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`match` | [Array&lt;IMatch&gt;](IMatch.md)
`_delete` | [Array&lt;IDelete&gt;](IDelete.md)

## Example

```typescript
import type { IUpdate } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "match": null,
  "_delete": null,
} satisfies IUpdate

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IUpdate
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


