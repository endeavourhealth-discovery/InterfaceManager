
# ITTEntity


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`predicateMap` | [{ [key: string]: ITTArray; }](ITTArray.md)
`context` | [ITTContext](ITTContext.md)
`crud` | [ITTIriRef](ITTIriRef.md)
`description` | string
`version` | number
`types` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`code` | string
`prefixes` | [Array&lt;ITTPrefix&gt;](ITTPrefix.md)
`scheme` | [ITTIriRef](ITTIriRef.md)
`name` | string
`type` | [ITTArray](ITTArray.md)
`status` | [ITTIriRef](ITTIriRef.md)

## Example

```typescript
import type { ITTEntity } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "predicateMap": null,
  "context": null,
  "crud": null,
  "description": null,
  "version": null,
  "types": null,
  "code": null,
  "prefixes": null,
  "scheme": null,
  "name": null,
  "type": null,
  "status": null,
} satisfies ITTEntity

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ITTEntity
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


