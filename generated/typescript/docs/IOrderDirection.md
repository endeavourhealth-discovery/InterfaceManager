
# IOrderDirection


## Properties

Name | Type
------------ | -------------
`iri` | string
`name` | string
`description` | string
`uuid` | string
`direction` | [Order](Order.md)
`_function` | [IFunctionClause](IFunctionClause.md)
`nodeRef` | string
`variable` | string

## Example

```typescript
import type { IOrderDirection } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "name": null,
  "description": null,
  "uuid": null,
  "direction": null,
  "_function": null,
  "nodeRef": null,
  "variable": null,
} satisfies IOrderDirection

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IOrderDirection
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


