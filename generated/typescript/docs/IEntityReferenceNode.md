
# IEntityReferenceNode


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`parents` | [Array&lt;IEntityReferenceNode&gt;](IEntityReferenceNode.md)
`children` | [Array&lt;IEntityReferenceNode&gt;](IEntityReferenceNode.md)
`moduleId` | string
`hasChildren` | boolean
`hasGrandChildren` | boolean
`type` | [ITTArray](ITTArray.md)
`orderNumber` | number

## Example

```typescript
import type { IEntityReferenceNode } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "parents": null,
  "children": null,
  "moduleId": null,
  "hasChildren": null,
  "hasGrandChildren": null,
  "type": null,
  "orderNumber": null,
} satisfies IEntityReferenceNode

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IEntityReferenceNode
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


