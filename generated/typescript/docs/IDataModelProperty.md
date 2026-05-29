
# IDataModelProperty


## Properties

Name | Type
------------ | -------------
`property` | [ITTIriRef](ITTIriRef.md)
`type` | [ITTIriRef](ITTIriRef.md)
`minInclusive` | string
`minExclusive` | string
`maxInclusive` | string
`maxExclusive` | string
`pattern` | string
`inheritedFrom` | [ITTIriRef](ITTIriRef.md)
`order` | number

## Example

```typescript
import type { IDataModelProperty } from ''

// TODO: Update the object below with actual values
const example = {
  "property": null,
  "type": null,
  "minInclusive": null,
  "minExclusive": null,
  "maxInclusive": null,
  "maxExclusive": null,
  "pattern": null,
  "inheritedFrom": null,
  "order": null,
} satisfies IDataModelProperty

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IDataModelProperty
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


