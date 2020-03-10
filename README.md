## สร้าง File .env
OAUTH_APP_ID=[ใส่ APPID]
OAUTH_APP_PASSWORD=[ ใส่ APP PASSWORD]
OAUTH_REDIRECT_URI=http://localhost:3000/auth/callback
OAUTH_SCOPES='openid profile offline_access User.Read Mail.Read Calendars.Read Contacts.Read People.Read'
OAUTH_AUTHORITY=https://login.microsoftonline.com/common
OAUTH_ID_METADATA=/v2.0/.well-known/openid-configuration
OAUTH_AUTHORIZE_ENDPOINT=/oauth2/v2.0/authorize
OAUTH_TOKEN_ENDPOINT=/oauth2/v2.0/token