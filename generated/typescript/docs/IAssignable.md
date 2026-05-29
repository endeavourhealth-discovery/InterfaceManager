
# IAssignable


## Properties

Name | Type
------------ | -------------
`valueTerm` | string
`valueLabel` | string
`units` | [ITTIriRef](ITTIriRef.md)
`compare` | [ICompare](ICompare.md)
`description` | string
`operator` | [Operator](Operator.md)
`value` | string
`invalid` | boolean

## Example

```typescript
import type { IAssignable } from ''

// TODO: Update the object below with actual values
const example = {
  "valueTerm": null,
  "valueLabel": null,
  "units": null,
  "compare": null,
  "description": null,
  "operator": null,
  "value": null,
  "invalid": null,
} satisfies IAssignable

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IAssignable
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


