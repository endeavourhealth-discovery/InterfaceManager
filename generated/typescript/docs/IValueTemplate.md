
# IValueTemplate


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
`label` | string
`parameter` | string
`order` | number
`valueType` | [ITTIriRef](ITTIriRef.md)
`defaultValue` | { [key: string]: any; }
`valueOption` | Array&lt;{ [key: string]: any; }&gt;

## Example

```typescript
import type { IValueTemplate } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "type": null,
  "status": null,
  "scheme": null,
  "isContainedIn": null,
  "name": null,
  "description": null,
  "label": null,
  "parameter": null,
  "order": null,
  "valueType": null,
  "defaultValue": null,
  "valueOption": null,
} satisfies IValueTemplate

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IValueTemplate
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


