
# IBugReport


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
`product` | string
`version` | string
`module` | [TaskModule](TaskModule.md)
`os` | [OperatingSystem](OperatingSystem.md)
`osOther` | string
`browser` | [Browser](Browser.md)
`browserOther` | string
`severity` | [Severity](Severity.md)
`status` | [Status](Status.md)
`error` | string
`description` | string
`reproduceSteps` | string
`expectedResult` | string
`actualResult` | string

## Example

```typescript
import type { IBugReport } from ''

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
  "product": null,
  "version": null,
  "module": null,
  "os": null,
  "osOther": null,
  "browser": null,
  "browserOther": null,
  "severity": null,
  "status": null,
  "error": null,
  "description": null,
  "reproduceSteps": null,
  "expectedResult": null,
  "actualResult": null,
} satisfies IBugReport

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IBugReport
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


