
# IThrowable


## Properties

Name | Type
------------ | -------------
`cause` | [IThrowable](IThrowable.md)
`stackTrace` | [Array&lt;IStackTraceElement&gt;](IStackTraceElement.md)
`message` | string
`suppressed` | [Array&lt;IThrowable&gt;](IThrowable.md)
`localizedMessage` | string

## Example

```typescript
import type { IThrowable } from ''

// TODO: Update the object below with actual values
const example = {
  "cause": null,
  "stackTrace": null,
  "message": null,
  "suppressed": null,
  "localizedMessage": null,
} satisfies IThrowable

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IThrowable
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


