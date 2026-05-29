
# IPropertyRange


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`pattern` | string
`intervalUnit` | [ITTIriRef](ITTIriRef.md)
`qualifier` | [Array&lt;IPropertyRange&gt;](IPropertyRange.md)
`type` | [ITTIriRef](ITTIriRef.md)
`units` | [ITTIriRef](ITTIriRef.md)
`operator` | [ITTIriRef](ITTIriRef.md)
`relativeValue` | boolean

## Example

```typescript
import type { IPropertyRange } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "pattern": null,
  "intervalUnit": null,
  "qualifier": null,
  "type": null,
  "units": null,
  "operator": null,
  "relativeValue": null,
} satisfies IPropertyRange

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IPropertyRange
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


