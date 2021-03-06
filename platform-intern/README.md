# Platform Backend Intern Role

### 1. API Gateway
Vernacular.ai offers lots of tools for its CCA and ASR products. For example Reporting Bad Calls, ASR Tuning Interface, etc. Users accessing these tools needs to be authorized for security purposes.

#### Problem Statement
Your task is to create an application to secure the frontend by providing [OAuth2.0](https://tools.ietf.org/html/rfc6749) for  Authentication for the users.

These are the following tables in the DB.
- User
    - id
    - name
    - email
    - password

If you add or remove any field from the table or add new tables, please add proper explanation. Do not store plain text password in the database.

Create two APIs:
- `POST /oauth/`
Implement this API for authenticating users and returning proper access tokens. Use     `email` and `password` to authenticate users.
- `GET /home/`
Implement this API such that it is accessible only to authenticated users.

If using python you should use Django framework for developing the backend. If using GoLang you can use any http framework and [GORM](http://gorm.io/).

#### Reading Links
- https://dzone.com/articles/deep-dive-to-oauth20-amp-jwt-part-1-setting-the-st
- https://www.djangoproject.com/
- https://github.com/gin-gonic/gin
- https://jinzhu.me/gorm/