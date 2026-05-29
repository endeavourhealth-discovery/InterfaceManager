
# ICodeGenDto


## Properties

Name | Type
------------ | -------------
`name` | string
`extension` | string
`collectionWrapper` | string
`datatypeMap` | { [key: string]: string; }
`template` | string
`complexTypes` | boolean

## Example

```typescript
import type { ICodeGenDto } from ''

// TODO: Update the object below with actual values
const example = {
  "name": null,
  "extension": null,
  "collectionWrapper": null,
  "datatypeMap": null,
  "template": null,
  "complexTypes": null,
} satisfies ICodeGenDto

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ICodeGenDto
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


