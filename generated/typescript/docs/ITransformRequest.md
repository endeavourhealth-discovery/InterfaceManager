
# ITransformRequest


## Properties

Name | Type
------------ | -------------
`transformMap` | [ITTIriRef](ITTIriRef.md)
`sourceFormat` | string
`targetFormat` | string
`source` | { [key: string]: Array&lt;{ [key: string]: any; }&gt;; }

## Example

```typescript
import type { ITransformRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "transformMap": null,
  "sourceFormat": null,
  "targetFormat": null,
  "source": null,
} satisfies ITransformRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ITransformRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


