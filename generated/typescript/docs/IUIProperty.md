
# IUIProperty


## Properties

Name | Type
------------ | -------------
`iri` | string
`name` | string
`propertyType` | string
`valueType` | string
`valueTypeName` | string
`maxCount` | number
`number` | number
`intervalUnitIri` | string
`intervalUnitOptions` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`unitIri` | string
`unitOptions` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`operatorIri` | string
`operatorOptions` | Array&lt;string&gt;
`qualifierOptions` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`setMemberCount` | number

## Example

```typescript
import type { IUIProperty } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "name": null,
  "propertyType": null,
  "valueType": null,
  "valueTypeName": null,
  "maxCount": null,
  "number": null,
  "intervalUnitIri": null,
  "intervalUnitOptions": null,
  "unitIri": null,
  "unitOptions": null,
  "operatorIri": null,
  "operatorOptions": null,
  "qualifierOptions": null,
  "setMemberCount": null,
} satisfies IUIProperty

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IUIProperty
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


