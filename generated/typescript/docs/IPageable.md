
# IPageable


## Properties

Name | Type
------------ | -------------
`totalCount` | number
`currentPage` | number
`pageSize` | number
`result` | Array&lt;any&gt;

## Example

```typescript
import type { IPageable } from ''

// TODO: Update the object below with actual values
const example = {
  "totalCount": null,
  "currentPage": null,
  "pageSize": null,
  "result": null,
} satisfies IPageable

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IPageable
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


