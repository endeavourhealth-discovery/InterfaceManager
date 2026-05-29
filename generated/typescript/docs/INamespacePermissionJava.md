
# INamespacePermissionJava


## Properties

Name | Type
------------ | -------------
`iri` | [NAMESPACE](NAMESPACE.md)
`read` | boolean
`write` | boolean

## Example

```typescript
import type { INamespacePermissionJava } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "read": null,
  "write": null,
} satisfies INamespacePermissionJava

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as INamespacePermissionJava
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


