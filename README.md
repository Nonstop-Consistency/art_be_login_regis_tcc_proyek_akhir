Endpoint

```text
POST /api/auth/signup
```

Body

```json
{
  "username": "qwerty1234",
  "email": "qwerty1234@gmail.com",
  "password": "qwerty1234",
  "roles": ["user", "admin", "moderator"]
}
```

Endpoint

```text
POST /api/auth/signin
```

Body

```json
{
  "username": "qwerty1234",
  "password": "qwerty1234"
}
```

Endpoint

```text
POST /api/auth/signout
```

Endpoint

```text
GET /api/test/all
```

Endpoint

```text
GET /api/test/user
```

Endpoint

```text
GET /api/test/mod
```

Endpoint

```text
GET /api/test/admin
```
