
# IFunctionRequest


## Properties

Name | Type
------------ | -------------
`functionIri` | string
`arguments` | [Array&lt;IArgument&gt;](IArgument.md)
`page` | [IPage](IPage.md)
`graph` | [GRAPH](GRAPH.md)

## Example

```typescript
import type { IFunctionRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "functionIri": null,
  "arguments": null,
  "page": null,
  "graph": null,
} satisfies IFunctionRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IFunctionRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


