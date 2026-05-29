
# IWorkflowRequest


## Properties

Name | Type
------------ | -------------
`securityService` | { [key: string]: any; }
`page` | number
`size` | number
`userId` | string

## Example

```typescript
import type { IWorkflowRequest } from ''

// TODO: Update the object below with actual values
const example = {
  "securityService": null,
  "page": null,
  "size": null,
  "userId": null,
} satisfies IWorkflowRequest

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IWorkflowRequest
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


