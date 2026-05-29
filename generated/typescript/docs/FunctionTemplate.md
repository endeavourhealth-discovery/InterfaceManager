
# FunctionTemplate


## Properties

Name | Type
------------ | -------------
`iri` | string
`type` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`status` | [ITTIriRef](ITTIriRef.md)
`scheme` | [ITTIriRef](ITTIriRef.md)
`isContainedIn` | [Array&lt;ITTEntity&gt;](ITTEntity.md)
`name` | string
`description` | string
`_function` | [ITTIriRef](ITTIriRef.md)
`parameterTemplate` | [Array&lt;IParameterTemplate&gt;](IParameterTemplate.md)

## Example

```typescript
import type { FunctionTemplate } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "type": null,
  "status": null,
  "scheme": null,
  "isContainedIn": null,
  "name": null,
  "description": null,
  "_function": null,
  "parameterTemplate": null,
} satisfies FunctionTemplate

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as FunctionTemplate
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


