
# IValueSource


## Properties

Name | Type
------------ | -------------
`parameter` | string
`iri` | string
`name` | string
`nodeRef` | string
`propertyRef` | string

## Example

```typescript
import type { IValueSource } from ''

// TODO: Update the object below with actual values
const example = {
  "parameter": null,
  "iri": null,
  "name": null,
  "nodeRef": null,
  "propertyRef": null,
} satisfies IValueSource

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IValueSource
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


