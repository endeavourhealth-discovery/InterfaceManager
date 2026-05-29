
# IWhere


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
`valueTerm` | string
`valueLabel` | string
`units` | [ITTIriRef](ITTIriRef.md)
`compare` | [ICompare](ICompare.md)
`operator` | [Operator](Operator.md)
`value` | string
`invalid` | boolean
`nodeRef` | string
`range` | [IRange](IRange.md)
`isNull` | boolean
`is` | [Array&lt;INode&gt;](INode.md)
`anyRoleGroup` | boolean
`parameter` | string
`childOrSelfOf` | boolean
`childOf` | boolean
`cohort` | boolean
`resultSet` | boolean
`inverse` | boolean
`typeOf` | [INode](INode.md)
`subjectVariable` | string
`subjectParameter` | string
`not` | boolean
`roleGroup` | boolean
`isNotNull` | boolean
`or` | [Array&lt;IWhere&gt;](IWhere.md)
`and` | [Array&lt;IWhere&gt;](IWhere.md)
`propertyRef` | string
`shortLabel` | string
`qualifier` | [ITTIriRef](ITTIriRef.md)
`propertyList` | [Array&lt;INode&gt;](INode.md)
`propertyVariable` | string
`node` | string
`excludeProperty` | [Array&lt;IIriLD&gt;](IIriLD.md)
`_exists` | boolean
`linked` | boolean
`notNull` | boolean
`isInvalid` | boolean
`isResultSet` | boolean
`isCohort` | boolean

## Example

```typescript
import type { IWhere } from ''

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
  "valueTerm": null,
  "valueLabel": null,
  "units": null,
  "compare": null,
  "operator": null,
  "value": null,
  "invalid": null,
  "nodeRef": null,
  "range": null,
  "isNull": null,
  "is": null,
  "anyRoleGroup": null,
  "parameter": null,
  "childOrSelfOf": null,
  "childOf": null,
  "cohort": null,
  "resultSet": null,
  "inverse": null,
  "typeOf": null,
  "subjectVariable": null,
  "subjectParameter": null,
  "not": null,
  "roleGroup": null,
  "isNotNull": null,
  "or": null,
  "and": null,
  "propertyRef": null,
  "shortLabel": null,
  "qualifier": null,
  "propertyList": null,
  "propertyVariable": null,
  "node": null,
  "excludeProperty": null,
  "_exists": null,
  "linked": null,
  "notNull": null,
  "isInvalid": null,
  "isResultSet": null,
  "isCohort": null,
} satisfies IWhere

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IWhere
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


