
# TTValueDTO

Base value type (extends Serializable)

## Properties

Name | Type
------------ | -------------
`tests` | string

## Example

```typescript
import type { TTValueDTO } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
} satisfies TTValueDTO

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as TTValueDTO
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


