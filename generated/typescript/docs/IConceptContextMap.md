
# IConceptContextMap


## Properties

Name | Type
------------ | -------------
`id` | string
`node` | string
`value` | string
`regex` | string
`property` | string
`context` | [Array&lt;IContext&gt;](IContext.md)

## Example

```typescript
import type { IConceptContextMap } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "node": null,
  "value": null,
  "regex": null,
  "property": null,
  "context": null,
} satisfies IConceptContextMap

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IConceptContextMap
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


