
# ITTContext


## Properties

Name | Type
------------ | -------------
`nameSpaces` | [Array&lt;ITTPrefix&gt;](ITTPrefix.md)
`prefixes` | [Array&lt;ITTPrefix&gt;](ITTPrefix.md)

## Example

```typescript
import type { ITTContext } from ''

// TODO: Update the object below with actual values
const example = {
  "nameSpaces": null,
  "prefixes": null,
} satisfies ITTContext

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ITTContext
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


