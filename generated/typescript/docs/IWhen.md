
# IWhen


## Properties

Name | Type
------------ | -------------
`where` | [IWhere](IWhere.md)
`then` | string
`_exists` | boolean
`_case` | [ICase](ICase.md)

## Example

```typescript
import type { IWhen } from ''

// TODO: Update the object below with actual values
const example = {
  "where": null,
  "then": null,
  "_exists": null,
  "_case": null,
} satisfies IWhen

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IWhen
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


