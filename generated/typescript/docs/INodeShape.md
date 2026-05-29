
# INodeShape


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`property` | [Array&lt;IPropertyShape&gt;](IPropertyShape.md)
`subType` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`definingProperty` | [ITTIriRef](ITTIriRef.md)
`inverseProperty` | [ITTIriRef](ITTIriRef.md)
`folder` | [Array&lt;INodeShape&gt;](INodeShape.md)
`type` | [Array&lt;INodeShape&gt;](INodeShape.md)

## Example

```typescript
import type { INodeShape } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "property": null,
  "subType": null,
  "definingProperty": null,
  "inverseProperty": null,
  "folder": null,
  "type": null,
} satisfies INodeShape

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as INodeShape
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


