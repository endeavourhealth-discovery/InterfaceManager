
# IConceptSet


## Properties

Name | Type
------------ | -------------
`iri` | string
`type` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`status` | [ITTIriRef](ITTIriRef.md)
`scheme` | [ITTIriRef](ITTIriRef.md)
`isContainedIn` | [Array&lt;ITTEntity&gt;](ITTEntity.md)
`name` | string
`description` | string
`definition` | [IQuery](IQuery.md)
`hasMember` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`usedIn` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`avoidReplacedBy` | boolean

## Example

```typescript
import type { IConceptSet } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "type": null,
  "status": null,
  "scheme": null,
  "isContainedIn": null,
  "name": null,
  "description": null,
  "definition": null,
  "hasMember": null,
  "usedIn": null,
  "avoidReplacedBy": null,
} satisfies IConceptSet

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IConceptSet
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


