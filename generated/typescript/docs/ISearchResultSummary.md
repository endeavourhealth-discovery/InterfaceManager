
# ISearchResultSummary


## Properties

Name | Type
------------ | -------------
`name` | string
`code` | string
`description` | string
`status` | [ITTIriRef](ITTIriRef.md)
`scheme` | [ITTIriRef](ITTIriRef.md)
`type` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`usageTotal` | number
`bestMatch` | string
`preferredName` | string
`key` | Array&lt;string&gt;
`isA` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`termCode` | [Array&lt;ISearchTermCode&gt;](ISearchTermCode.md)
`unit` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`qualifier` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`iri` | string

## Example

```typescript
import type { ISearchResultSummary } from ''

// TODO: Update the object below with actual values
const example = {
  "name": null,
  "code": null,
  "description": null,
  "status": null,
  "scheme": null,
  "type": null,
  "usageTotal": null,
  "bestMatch": null,
  "preferredName": null,
  "key": null,
  "isA": null,
  "termCode": null,
  "unit": null,
  "qualifier": null,
  "iri": null,
} satisfies ISearchResultSummary

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ISearchResultSummary
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


