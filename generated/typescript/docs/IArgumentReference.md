
# IArgumentReference


## Properties

Name | Type
------------ | -------------
`parameter` | string
`referenceIri` | [ITTIriRef](ITTIriRef.md)
`dataType` | [ITTIriRef](ITTIriRef.md)

## Example

```typescript
import type { IArgumentReference } from ''

// TODO: Update the object below with actual values
const example = {
  "parameter": null,
  "referenceIri": null,
  "dataType": null,
} satisfies IArgumentReference

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IArgumentReference
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


