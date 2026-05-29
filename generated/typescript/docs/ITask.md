
# ITask


## Properties

Name | Type
------------ | -------------
`id` | [ITTIriRef](ITTIriRef.md)
`createdBy` | string
`type` | [TaskType](TaskType.md)
`state` | [TaskState](TaskState.md)
`assignedTo` | string
`dateCreated` | Date
`history` | [Array&lt;ITaskHistory&gt;](ITaskHistory.md)
`hostUrl` | string

## Example

```typescript
import type { ITask } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "createdBy": null,
  "type": null,
  "state": null,
  "assignedTo": null,
  "dateCreated": null,
  "history": null,
  "hostUrl": null,
} satisfies ITask

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as ITask
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


