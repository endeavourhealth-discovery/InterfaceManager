
# IQueryEntity


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

## Example

```typescript
import type { IQueryEntity } from ''

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
} satisfies IQueryEntity

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IQueryEntity
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


