
# IArgument


## Properties

Name | Type
------------ | -------------
`parameter` | string
`valueData` | string
`valueParameter` | string
`valueIri` | [ITTIriRef](ITTIriRef.md)
`valueIriList` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`valueDataList` | Array&lt;string&gt;
`valuePath` | [IPath](IPath.md)
`valueNodeRef` | string
`dataType` | [ITTIriRef](ITTIriRef.md)
`valueObject` | { [key: string]: any; }
`valueVariable` | string
`qualifier` | [ITTIriRef](ITTIriRef.md)

## Example

```typescript
import type { IArgument } from ''

// TODO: Update the object below with actual values
const example = {
  "parameter": null,
  "valueData": null,
  "valueParameter": null,
  "valueIri": null,
  "valueIriList": null,
  "valueDataList": null,
  "valuePath": null,
  "valueNodeRef": null,
  "dataType": null,
  "valueObject": null,
  "valueVariable": null,
  "qualifier": null,
} satisfies IArgument

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IArgument
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


