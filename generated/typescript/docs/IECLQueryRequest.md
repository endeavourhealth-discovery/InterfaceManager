
# IECLQueryRequest


## Properties

Name | Type
------------ | -------------
`ecl` | string
`query` | [IQuery](IQuery.md)
`showNames` | boolean
`status` | [IECLStatus](IECLStatus.md)
`includeLegacy` | boolean
`limit` | number
`statusFilter` | [Array&lt;ITTIriRef&gt;](ITTIriRef.md)
`page` | number
`size` | number

## Example

```typescript
import type { IECLQueryRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "ecl": null,
  "query": null,
  "showNames": null,
  "status": null,
  "includeLegacy": null,
  "limit": null,
  "statusFilter": null,
  "page": null,
  "size": null,
} satisfies IECLQueryRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IECLQueryRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


