
# IReturnable


## Properties

Name | Type
------------ | -------------
`_return` | [Array&lt;IReturn&gt;](IReturn.md)

## Example

```typescript
import type { IReturnable } from ''

// TODO: Update the object below with actual values
const example = {
  "_return": null,
} satisfies IReturnable

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IReturnable
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


