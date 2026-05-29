
# IEntityDocument


## Properties

Name | Type
------------ | -------------
`id` | number
`iri` | string
`name` | string
`length` | number
`preferredName` | string
`code` | string
`alternativeCode` | string
`scheme` | [ITTIriRef](ITTIriRef.md)
`type` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`status` | [ITTIriRef](ITTIriRef.md)
`termCode` | [Array&lt;ISearchTermCode&gt;](ISearchTermCode.md)
`usageTotal` | number
`match` | string
`isA` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`memberOf` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`subsumptionCount` | number
`binding` | Array&lt;string&gt;
`isDescendentOf` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)

## Example

```typescript
import type { IEntityDocument } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "iri": null,
  "name": null,
  "length": null,
  "preferredName": null,
  "code": null,
  "alternativeCode": null,
  "scheme": null,
  "type": null,
  "status": null,
  "termCode": null,
  "usageTotal": null,
  "match": null,
  "isA": null,
  "memberOf": null,
  "subsumptionCount": null,
  "binding": null,
  "isDescendentOf": null,
} satisfies IEntityDocument

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IEntityDocument
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


