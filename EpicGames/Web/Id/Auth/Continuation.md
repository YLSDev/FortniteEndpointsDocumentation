## Id Web - Continuation Info

URL: https://www.epicgames.com/id/api/continuation/:continuationToken \
Method: GET \
Auth Required: No

## Path Parameters

`continuationToken`: The Continuation Token

---

_Example Response_

```json
{
  "accountId": "94b1569506b04f9f8557af611e8c5e47",
  "clientId": "xyza7891atVNaa9a4cJxNwHMzLUO65Ad"
}
```

_Example Response (External Auth)_
```json
{
    "accountId": "d7f64575d96b44e0abb61b2b36b17aea",
    "clientId": "xyza7891343Fr4ZSPkQZ3kaL3I2sX8B5",
    "provider": "nintendo",
    "externalDisplayName": "sectest-nintendo"
}
```
