## OAuth 2.0
OAuth is not about authentication (who I am)

OAuth is about authorization (what I can do)

### Client types
confidential clients
- Web API
- ASP.NET WebForm

public clients
- mobile phone applications
- user agnet based applications: SPA

### Cliet Credential Flow (Web API)
- machine to machine
- response_type = code

### Hybrid Cliet Credential Flow (WebFrom)
- machine to machine
- response_type = code id_token token

### Implicit Flow (SPA)
- response_type = id_token token
- save token in localstorage [pic1]
![pic1](https://github.com/pinghohoho/sso/raw/master/2018-06-04_16-49-05.png)

