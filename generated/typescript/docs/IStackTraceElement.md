
# IStackTraceElement


## Properties

Name | Type
------------ | -------------
`classLoaderName` | string
`moduleName` | string
`moduleVersion` | string
`methodName` | string
`fileName` | string
`lineNumber` | number
`className` | string
`nativeMethod` | boolean

## Example

```typescript
import type { IStackTraceElement } from ''

// TODO: Update the object below with actual values
const example = {
  "classLoaderName": null,
  "moduleName": null,
  "moduleVersion": null,
  "methodName": null,
  "fileName": null,
  "lineNumber": null,
  "className": null,
  "nativeMethod": null,
} satisfies IStackTraceElement

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IStackTraceElement
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


