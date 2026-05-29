
# IIndicator


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`isSubIndicatorOf` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`numerator` | [ITTIriRef](ITTIriRef.md)
`dataset` | [ITTIriRef](ITTIriRef.md)
`actionIfFalse` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`actionIfTrue` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`denominator` | [ITTIriRef](ITTIriRef.md)

## Example

```typescript
import type { IIndicator } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "isSubIndicatorOf": null,
  "numerator": null,
  "dataset": null,
  "actionIfFalse": null,
  "actionIfTrue": null,
  "denominator": null,
} satisfies IIndicator

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IIndicator
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


