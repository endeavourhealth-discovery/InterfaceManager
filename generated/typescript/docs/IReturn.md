
# IReturn


## Properties

Name | Type
------------ | -------------
`_return` | [Array&lt;IReturn&gt;](IReturn.md)
`iri` | string
`name` | string
`_function` | [IFunctionClause](IFunctionClause.md)
`as` | string
`nodeRef` | string
`propertyRef` | string
`pathRef` | string
`inverse` | boolean
`units` | [ITTIriRef](ITTIriRef.md)
`dataType` | [ITTIriRef](ITTIriRef.md)
`description` | string
`_case` | [ICase](ICase.md)
`value` | string

## Example

```typescript
import type { IReturn } from ''

// TODO: Update the object below with actual values
const example = {
  "_return": null,
  "iri": null,
  "name": null,
  "_function": null,
  "as": null,
  "nodeRef": null,
  "propertyRef": null,
  "pathRef": null,
  "inverse": null,
  "units": null,
  "dataType": null,
  "description": null,
  "_case": null,
  "value": null,
} satisfies IReturn

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IReturn
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


