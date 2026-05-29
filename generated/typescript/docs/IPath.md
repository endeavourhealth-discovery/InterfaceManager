
# IPath


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
`path` | [Array&lt;IPath&gt;](IPath.md)
`node` | string
`parameter` | string
`childOrSelfOf` | boolean
`childOf` | boolean
`cohort` | boolean
`nodeRef` | string
`invalid` | boolean
`resultSet` | boolean
`inverse` | boolean
`optional` | boolean
`pathVariable` | string
`typeOf` | [INode](INode.md)
`qualifier` | [ITTIriRef](ITTIriRef.md)
`isResultSet` | boolean
`isCohort` | boolean

## Example

```typescript
import type { IPath } from ''

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
  "path": null,
  "node": null,
  "parameter": null,
  "childOrSelfOf": null,
  "childOf": null,
  "cohort": null,
  "nodeRef": null,
  "invalid": null,
  "resultSet": null,
  "inverse": null,
  "optional": null,
  "pathVariable": null,
  "typeOf": null,
  "qualifier": null,
  "isResultSet": null,
  "isCohort": null,
} satisfies IPath

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IPath
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


