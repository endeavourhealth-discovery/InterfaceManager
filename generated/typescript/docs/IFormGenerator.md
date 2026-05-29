
# IFormGenerator


## Properties

Name | Type
------------ | -------------
`iri` | string
`status` | [ITTIriRef](ITTIriRef.md)
`label` | string
`comment` | string
`targetShape` | [ITTIriRef](ITTIriRef.md)
`type` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`isContainedIn` | [Array&lt;ITTEntity&gt;](ITTEntity.md)
`subClassOf` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`scheme` | [ITTIriRef](ITTIriRef.md)
`property` | [Array&lt;IPropertyShape&gt;](IPropertyShape.md)

## Example

```typescript
import type { IFormGenerator } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "status": null,
  "label": null,
  "comment": null,
  "targetShape": null,
  "type": null,
  "isContainedIn": null,
  "subClassOf": null,
  "scheme": null,
  "property": null,
} satisfies IFormGenerator

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IFormGenerator
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


