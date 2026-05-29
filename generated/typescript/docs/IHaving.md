
# IHaving


## Properties

Name | Type
------------ | -------------
`_function` | [Aggregate](Aggregate.md)
`identifier` | string
`range` | [IRange](IRange.md)
`operator` | [Operator](Operator.md)
`value` | string
`and` | [Array&lt;IHaving&gt;](IHaving.md)
`or` | [Array&lt;IHaving&gt;](IHaving.md)
`not` | boolean

## Example

```typescript
import type { IHaving } from ''

// TODO: Update the object below with actual values
const example = {
  "_function": null,
  "identifier": null,
  "range": null,
  "operator": null,
  "value": null,
  "and": null,
  "or": null,
  "not": null,
} satisfies IHaving

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IHaving
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


