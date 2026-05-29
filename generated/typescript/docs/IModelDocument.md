
# IModelDocument


## Properties

Name | Type
------------ | -------------
`context` | [ITTContext](ITTContext.md)
`query` | [Array&lt;IQueryEntity&gt;](IQueryEntity.md)
`folder` | [Array&lt;IEntity&gt;](IEntity.md)
`conceptSet` | [Array&lt;IConceptSet&gt;](IConceptSet.md)
`_function` | [Array&lt;IMapFunction&gt;](IMapFunction.md)

## Example

```typescript
import type { IModelDocument } from ''

// TODO: Update the object below with actual values
const example = {
  "context": null,
  "query": null,
  "folder": null,
  "conceptSet": null,
  "_function": null,
} satisfies IModelDocument

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IModelDocument
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


