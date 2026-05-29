
# INode


## Properties

Name | Type
------------ | -------------
`iri` | string
`name` | string
`description` | string
`uuid` | string
`memberOf` | boolean
`ancestorsOf` | boolean
`descendantsOrSelfOf` | boolean
`descendantsOf` | boolean
`parameter` | string
`type` | string
`qualifier` | string
`match` | [IMatch](IMatch.md)
`childOrSelfOf` | boolean
`childOf` | boolean
`cohort` | boolean
`nodeRef` | string
`invalid` | boolean
`resultSet` | boolean
`exclude` | boolean
`code` | string
`inverse` | boolean
`node` | string
`isResultSet` | boolean
`isCohort` | boolean

## Example

```typescript
import type { INode } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "name": null,
  "description": null,
  "uuid": null,
  "memberOf": null,
  "ancestorsOf": null,
  "descendantsOrSelfOf": null,
  "descendantsOf": null,
  "parameter": null,
  "type": null,
  "qualifier": null,
  "match": null,
  "childOrSelfOf": null,
  "childOf": null,
  "cohort": null,
  "nodeRef": null,
  "invalid": null,
  "resultSet": null,
  "exclude": null,
  "code": null,
  "inverse": null,
  "node": null,
  "isResultSet": null,
  "isCohort": null,
} satisfies INode

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as INode
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


