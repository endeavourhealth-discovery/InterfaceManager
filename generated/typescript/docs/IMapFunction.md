
# IMapFunction


## Properties

Name | Type
------------ | -------------
`tests` | string
`iri` | string
`name` | string
`description` | string
`argument` | [Array&lt;IArgument&gt;](IArgument.md)
`conceptMap` | { [key: string]: string; }
`defaultValue` | [ITTIriRef](ITTIriRef.md)

## Example

```typescript
import type { IMapFunction } from ''

// TODO: Update the object below with actual values
const example = {
  "tests": null,
  "iri": null,
  "name": null,
  "description": null,
  "argument": null,
  "conceptMap": null,
  "defaultValue": null,
} satisfies IMapFunction

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IMapFunction
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


