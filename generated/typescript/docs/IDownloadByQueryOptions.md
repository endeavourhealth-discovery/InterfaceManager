
# IDownloadByQueryOptions


## Properties

Name | Type
------------ | -------------
`queryRequest` | [IQueryRequest](IQueryRequest.md)
`eclSearchRequest` | [IECLQueryRequest](IECLQueryRequest.md)
`totalCount` | number
`format` | string
`includeDefinition` | boolean
`includeCore` | boolean
`includeLegacy` | boolean
`includeSubsets` | boolean
`subsetsOnOwnRow` | boolean
`im1id` | boolean

## Example

```typescript
import type { IDownloadByQueryOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "queryRequest": null,
  "eclSearchRequest": null,
  "totalCount": null,
  "format": null,
  "includeDefinition": null,
  "includeCore": null,
  "includeLegacy": null,
  "includeSubsets": null,
  "subsetsOnOwnRow": null,
  "im1id": null,
} satisfies IDownloadByQueryOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IDownloadByQueryOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


