
# IDelete


## Properties

Name | Type
------------ | -------------
`property` | [IWhere](IWhere.md)
`subject` | [INode](INode.md)
`inverse` | boolean
`predicate` | [INode](INode.md)
`object` | [INode](INode.md)
`_delete` | [Array&lt;IDelete&gt;](IDelete.md)

## Example

```typescript
import type { IDelete } from ''

// TODO: Update the object below with actual values
const example = {
  "property": null,
  "subject": null,
  "inverse": null,
  "predicate": null,
  "object": null,
  "_delete": null,
} satisfies IDelete

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IDelete
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


