
# IContext


## Properties

Name | Type
------------ | -------------
`publisher` | string
`system` | string
`schema` | string
`table` | string
`field` | string

## Example

```typescript
import type { IContext } from ''

// TODO: Update the object below with actual values
const example = {
  "publisher": null,
  "system": null,
  "schema": null,
  "table": null,
  "field": null,
} satisfies IContext

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IContext
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


