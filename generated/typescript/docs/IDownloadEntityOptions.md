
# IDownloadEntityOptions


## Properties

Name | Type
------------ | -------------
`entityIri` | string
`format` | string
`includeHasSubtypes` | boolean
`includeInferred` | boolean
`includeProperties` | boolean
`includeMembers` | boolean
`expandMembers` | boolean
`expandSubsets` | boolean
`includeTerms` | boolean
`includeIsChildOf` | boolean
`includeHasChildren` | boolean
`includeInactive` | boolean

## Example

```typescript
import type { IDownloadEntityOptions } from ''

// TODO: Update the object below with actual values
const example = {
  "entityIri": null,
  "format": null,
  "includeHasSubtypes": null,
  "includeInferred": null,
  "includeProperties": null,
  "includeMembers": null,
  "expandMembers": null,
  "expandSubsets": null,
  "includeTerms": null,
  "includeIsChildOf": null,
  "includeHasChildren": null,
  "includeInactive": null,
} satisfies IDownloadEntityOptions

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IDownloadEntityOptions
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


