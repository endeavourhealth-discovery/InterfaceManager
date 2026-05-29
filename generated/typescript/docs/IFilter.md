
# IFilter


## Properties

Name | Type
------------ | -------------
`field` | string
`iriValue` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`and` | [Array&lt;IFilter&gt;](IFilter.md)
`not` | boolean
`textValue` | Array&lt;string&gt;
`startsWithTerm` | boolean

## Example

```typescript
import type { IFilter } from ''

// TODO: Update the object below with actual values
const example = {
  "field": null,
  "iriValue": null,
  "and": null,
  "not": null,
  "textValue": null,
  "startsWithTerm": null,
} satisfies IFilter

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IFilter
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


