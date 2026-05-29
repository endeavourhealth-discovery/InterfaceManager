
# IQuery


## Properties

Name | Type
------------ | -------------
`iri` | string
`name` | string
`description` | string
`uuid` | string
`path` | [Array&lt;IPath&gt;](IPath.md)
`node` | string
`_return` | [Array&lt;IReturn&gt;](IReturn.md)
`notExists` | boolean
`ifTrue` | [RuleAction](RuleAction.md)
`ifFalse` | [RuleAction](RuleAction.md)
`nodeRef` | string
`typeOf` | [INode](INode.md)
`is` | [INode](INode.md)
`and` | [Array&lt;IMatch&gt;](IMatch.md)
`or` | [Array&lt;IMatch&gt;](IMatch.md)
`where` | [IWhere](IWhere.md)
`then` | [IWhere](IWhere.md)
`graph` | [INode](INode.md)
`optional` | boolean
`parameter` | string
`_function` | [IFunctionClause](IFunctionClause.md)
`entailment` | [Entail](Entail.md)
`baseRule` | boolean
`ruleNumber` | number
`inverse` | boolean
`activeOnly` | boolean
`rule` | [Array&lt;IMatch&gt;](IMatch.md)
`any` | [Array&lt;IMatch&gt;](IMatch.md)
`libraryItem` | string
`invalid` | boolean
`groupBy` | [Array&lt;IGroupBy&gt;](IGroupBy.md)
`orderBy` | [IOrderLimit](IOrderLimit.md)
`asDescription` | string
`errorMessage` | string
`draft` | boolean
`having` | [IHaving](IHaving.md)
`prefixes` | [Array&lt;IPrefix&gt;](IPrefix.md)
`columnGroup` | [Array&lt;IMatch&gt;](IMatch.md)
`imQuery` | string
`parentResult` | { [key: string]: any; }
`persistentIri` | [ITTIriRef](ITTIriRef.md)
`bindAs` | string
`queryType` | [IMQType](IMQType.md)

## Example

```typescript
import type { IQuery } from ''

// TODO: Update the object below with actual values
const example = {
  "iri": null,
  "name": null,
  "description": null,
  "uuid": null,
  "path": null,
  "node": null,
  "_return": null,
  "notExists": null,
  "ifTrue": null,
  "ifFalse": null,
  "nodeRef": null,
  "typeOf": null,
  "is": null,
  "and": null,
  "or": null,
  "where": null,
  "then": null,
  "graph": null,
  "optional": null,
  "parameter": null,
  "_function": null,
  "entailment": null,
  "baseRule": null,
  "ruleNumber": null,
  "inverse": null,
  "activeOnly": null,
  "rule": null,
  "any": null,
  "libraryItem": null,
  "invalid": null,
  "groupBy": null,
  "orderBy": null,
  "asDescription": null,
  "errorMessage": null,
  "draft": null,
  "having": null,
  "prefixes": null,
  "columnGroup": null,
  "imQuery": null,
  "parentResult": null,
  "persistentIri": null,
  "bindAs": null,
  "queryType": null,
} satisfies IQuery

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IQuery
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


