## OAuth 2.0
OAuth is not about authentication (who I am)

OAuth is about authorization (what I can do)

### client types
confidential clients
- Web API

public clients
- mobile phone applications
- user agnet based applications: SPA

### Cliet Credential Flow (Web API)
- machine to machine
- save token in cookie
```c#
HttpContext.Current.Response.Cookies["OnePoint"]["Access_Token"] = accessToken
```

### Implicit Flow (SPA)
- save token in localstorage
