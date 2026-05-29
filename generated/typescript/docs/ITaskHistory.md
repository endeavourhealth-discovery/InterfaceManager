
# ITaskHistory


## Properties

Name | Type
------------ | -------------
`predicate` | string
`originalObject` | string
`newObject` | string
`changeDate` | Date
`modifiedBy` | string
`dateTime` | Date

## Example

```typescript
import type { ITaskHistory } from ''

// TODO: Update the object below with actual values
const example = {
  "predicate": null,
  "originalObject": null,
  "newObject": null,
  "changeDate": null,
  "modifiedBy": null,
  "dateTime": null,
} satisfies ITaskHistory

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ITaskHistory
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


