h2.事前に必要なもの

Redirect Uri : [REDIRECT_URI]
Client Id : [CLIENT_ID]
Registration Access Token : [REG_TOKEN]

これらは、連携パートナー様むけにA-SaaSサイドで作成し、送付いたします

https://api.a-saas.com/paas-oauth2/authorize?response_type=code&client_id=[CLIENT_ID]&redirect_uri=[REDIRECT_URI]

連携パートナー様は次のページで各種情報を入手できます。
https://api.a-saas.com/paas-oauth2/client/[CLIENT_ID]

[CLIENT_ID] と [REG_TOKEN] でログインください


h2.認可とAuthorization Codeの入手

クライアントアプリケーション側から，次のURLを開いてください

https://api.a-saas.com/paas-oauth2/authorize

|code||
|client_id|[CLIENT_ID]|
|redirect_uri|[REDIRECT_URI]|

例
https://api.a-saas.com/paas-oauth2/authorize?response_type=code&client_id=[CLIENT_ID]&redirect_uri=[REDIRECT_URI]
