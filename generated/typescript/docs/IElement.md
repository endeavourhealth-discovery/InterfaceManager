
# IElement


## Properties

Name | Type
------------ | -------------
`iri` | string
`name` | string
`description` | string
`uuid` | string
`memberOf` | boolean
`ancestorsOf` | boolean
`descendantsOrSelfOf` | boolean
`descendantsOf` | boolean

## Example

```typescript
import type { IElement } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "name": null,
  "description": null,
  "uuid": null,
  "memberOf": null,
  "ancestorsOf": null,
  "descendantsOrSelfOf": null,
  "descendantsOf": null,
} satisfies IElement

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IElement
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


