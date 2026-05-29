
# IPropertyShape


## Properties

Name | Type
------------ | -------------
`label` | string
`comment` | string
`name` | string
`order` | number
`minCount` | number
`maxCount` | number
`componentType` | [ITTIriRef](ITTIriRef.md)
`path` | [ITTIriRef](ITTIriRef.md)
`datatype` | [IPropertyRange](IPropertyRange.md)
`node` | [IPropertyRange](IPropertyRange.md)
`validation` | [ITTIriRef](ITTIriRef.md)
`search` | [ITTIriRef](ITTIriRef.md)
`select` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`argument` | [Array&lt;IArgument&gt;](IArgument.md)
`valueVariable` | string
`isIri` | [ITTIriRef](ITTIriRef.md)
`isTextValue` | string
`isNumericValue` | string
`forceIsValue` | boolean
`builderChild` | boolean
`showTitle` | boolean
`group` | [ITTIriRef](ITTIriRef.md)
`property` | [Array&lt;IPropertyShape&gt;](IPropertyShape.md)
`clazz` | [IPropertyRange](IPropertyRange.md)
`validationErrorMessage` | string
`_function` | [ITTIriRef](ITTIriRef.md)
`parameter` | [Array&lt;IParameterShape&gt;](IParameterShape.md)
`valueIri` | [ITTIriRef](ITTIriRef.md)
`expression` | [INodeShape](INodeShape.md)
`arrayButtons` | [IArrayButtons](IArrayButtons.md)
`hasValue` | { [key: string]: any; }
`hasValueType` | [ITTIriRef](ITTIriRef.md)
`definition` | string
`ascending` | string
`descending` | string
`orderable` | boolean
`hasValueSet` | [ITTIriRef](ITTIriRef.md)
`definingProperty` | boolean
`isValidEntity` | [ITTIriRef](ITTIriRef.md)
`highCardinality` | boolean
`isValidArguments` | [Array&lt;IArgument&gt;](IArgument.md)
`inversePath` | [ITTIriRef](ITTIriRef.md)
`generic` | boolean

## Example

```typescript
import type { IPropertyShape } from ''

// TODO: Update the object below with actual values
const example = {
  "label": null,
  "comment": null,
  "name": null,
  "order": null,
  "minCount": null,
  "maxCount": null,
  "componentType": null,
  "path": null,
  "datatype": null,
  "node": null,
  "validation": null,
  "search": null,
  "select": null,
  "argument": null,
  "valueVariable": null,
  "isIri": null,
  "isTextValue": null,
  "isNumericValue": null,
  "forceIsValue": null,
  "builderChild": null,
  "showTitle": null,
  "group": null,
  "property": null,
  "clazz": null,
  "validationErrorMessage": null,
  "_function": null,
  "parameter": null,
  "valueIri": null,
  "expression": null,
  "arrayButtons": null,
  "hasValue": null,
  "hasValueType": null,
  "definition": null,
  "ascending": null,
  "descending": null,
  "orderable": null,
  "hasValueSet": null,
  "definingProperty": null,
  "isValidEntity": null,
  "highCardinality": null,
  "isValidArguments": null,
  "inversePath": null,
  "generic": null,
} satisfies IPropertyShape

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IPropertyShape
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


