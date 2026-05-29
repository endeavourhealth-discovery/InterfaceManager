
# IOrderBy


## Properties

Name | Type
------------ | -------------
`field` | string
`direction` | [Order](Order.md)
`iriValue` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`and` | [Array&lt;IOrderBy&gt;](IOrderBy.md)
`textValue` | Array&lt;string&gt;
`not` | boolean
`startsWithTerm` | boolean

## Example

```typescript
import type { IOrderBy } from ''

// TODO: Update the object below with actual values
const example = {
  "field": null,
  "direction": null,
  "iriValue": null,
  "and": null,
  "textValue": null,
  "not": null,
  "startsWithTerm": null,
} satisfies IOrderBy

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IOrderBy
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


