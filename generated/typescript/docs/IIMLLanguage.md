
# IIMLLanguage


## Properties

Name | Type
------------ | -------------
`text` | string
`lang` | string
`info` | { [key: string]: string; }
`definitions` | { [key: string]: string; }
`prefixes` | { [key: string]: string; }
`keywords` | Set&lt;string&gt;
`booleans` | Set&lt;string&gt;
`alerts` | Set&lt;string&gt;
`iriVariables` | { [key: string]: Array&lt;string&gt;; }

## Example

```typescript
import type { IIMLLanguage } from ''

// TODO: Update the object below with actual values
const example = {
  "text": null,
  "lang": null,
  "info": null,
  "definitions": null,
  "prefixes": null,
  "keywords": null,
  "booleans": null,
  "alerts": null,
  "iriVariables": null,
} satisfies IIMLLanguage

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IIMLLanguage
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


