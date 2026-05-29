
# IValue


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
`valueParameter` | string
`isInvalid` | boolean

## Example

```typescript
import type { IValue } from ''

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
  "valueParameter": null,
  "isInvalid": null,
} satisfies IValue

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IValue
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


