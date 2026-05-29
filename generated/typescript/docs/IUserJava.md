
# IUserJava


## Properties

Name | Type
------------ | -------------
`id` | string
`username` | string
`email` | string
`displayName` | string
`password` | string
`avatar` | string
`roles` | [Array&lt;UserRole&gt;](UserRole.md)
`organisations` | Array&lt;string&gt;
`theme` | [PrimeVuePresetThemes](PrimeVuePresetThemes.md)
`primaryColor` | [PrimeVueColors](PrimeVueColors.md)
`surfaceColor` | [PrimeVueColors](PrimeVueColors.md)
`darkMode` | boolean
`fontSize` | [FontSize](FontSize.md)
`favourites` | Array&lt;string&gt;
`recentActivity` | [Array&lt;IRecentActivityItemDto&gt;](IRecentActivityItemDto.md)
`namespaces` | [Array&lt;INamespacePermissionJava&gt;](INamespacePermissionJava.md)

## Example

```typescript
import type { IUserJava } from ''

// TODO: Update the object below with actual values
const example = {
  "id": null,
  "username": null,
  "email": null,
  "displayName": null,
  "password": null,
  "avatar": null,
  "roles": null,
  "organisations": null,
  "theme": null,
  "primaryColor": null,
  "surfaceColor": null,
  "darkMode": null,
  "fontSize": null,
  "favourites": null,
  "recentActivity": null,
  "namespaces": null,
} satisfies IUserJava

console.log(example)

// Convert the instance to a JSON string
const exampleJSON: string = JSON.stringify(example)
console.log(exampleJSON)

// Parse the JSON string back to an object
const exampleParsed = JSON.parse(exampleJSON) as IUserJava
console.log(exampleParsed)
```

[[Back to top]](#) [[Back to API list]](../README.md#api-endpoints) [[Back to Model list]](../README.md#models) [[Back to README]](../README.md)


