# google-auth-scopes-list


This repo is an array of google authorization scopes 

It was obtained from the google documentation page here:
https://developers.google.com/identity/protocols/oauth2/scopes

Easily setup auto suggest when typed as `ScopeListType`

![auto suggest](scopesSuggest.png)

## Basic Code Example:

```typescript
// example.ts

import { ScopeListType } from "./scopesList";

const scopes: ScopeListType = [
  "https://www.googleapis.com/auth/userinfo.email",
  "https://www.googleapis.com/auth/userinfo.profile",
];
```
