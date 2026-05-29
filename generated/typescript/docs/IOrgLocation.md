
# IOrgLocation


## Properties

Name | Type
------------ | -------------
`addrLn1` | string
`addrLn2` | string
`addrLn3` | string
`town` | string
`county` | string
`postCode` | string
`country` | string
`uPRN` | string

## Example

```typescript
import type { IOrgLocation } from ''

// TODO: Update the object below with actual values
const example = {
  "addrLn1": null,
  "addrLn2": null,
  "addrLn3": null,
  "town": null,
  "county": null,
  "postCode": null,
  "country": null,
  "uPRN": null,
} satisfies IOrgLocation

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IOrgLocation
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


