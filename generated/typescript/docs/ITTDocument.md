
# ITTDocument


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`predicateMap` | [{ [key: string]: ITTArray; }](ITTArray.md)
`context` | [ITTContext](ITTContext.md)
`entities` | [Array&lt;ITTEntity&gt;](ITTEntity.md)
`crud` | [ITTIriRef](ITTIriRef.md)
`predicates` | { [key: string]: string; }
`prefixes` | [Array&lt;ITTPrefix&gt;](ITTPrefix.md)

## Example

```typescript
import type { ITTDocument } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "predicateMap": null,
  "context": null,
  "entities": null,
  "crud": null,
  "predicates": null,
  "prefixes": null,
} satisfies ITTDocument

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ITTDocument
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


