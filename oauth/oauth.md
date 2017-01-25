### Получение Oauth2 токена для общеие я api

POST https:///api.alol.io/oauth/2.0/access-token

Request

```
{
  "app_key":"{your_app_key}",
  "app_secret":"{your_app_secret}",
  "grant_type":"client_credentials"
}
```

Response: 200 OK

```
{
  "access_token": "a1ccd7a361473814e90c804134ba3e8c11f40647",
  "expires_in": 3600,
  "token_type": "bearer",
  "scope": "auth-external-user, etc..",
  "refresh_token": "783b0af4e514deb31f337e83309fd588228bf51b"
}
```