
# ISetOptions


## Properties

Name | Type
------------ | -------------
`setIri` | string
`schemes` | Array&lt;string&gt;
`includeIM1id` | boolean
`subsumptions` | Array&lt;string&gt;
`includeDefinition` | boolean
`includeCore` | boolean
`includeLegacy` | boolean
`includeSubsets` | boolean

## Example

```typescript
import type { ISetOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "setIri": null,
  "schemes": null,
  "includeIM1id": null,
  "subsumptions": null,
  "includeDefinition": null,
  "includeCore": null,
  "includeLegacy": null,
  "includeSubsets": null,
} satisfies ISetOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ISetOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


