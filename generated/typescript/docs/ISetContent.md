
# ISetContent


## Properties

Name | Type
------------ | -------------
`name` | string
`description` | string
`status` | string
`version` | number
`setDefinition` | string
`subsets` | Array&lt;string&gt;
`concepts` | [Array&lt;IConcept&gt;](IConcept.md)

## Example

```typescript
import type { ISetContent } from ''

// TODO: Update the object below with actual values
const example = {
  "name": null,
  "description": null,
  "status": null,
  "version": null,
  "setDefinition": null,
  "subsets": null,
  "concepts": null,
} satisfies ISetContent

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ISetContent
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


