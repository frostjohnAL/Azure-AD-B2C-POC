# Azure-AD-B2C-POC

URL: https://arkosetest2.b2clogin.com/arkosetest2.onmicrosoft.com/oauth2/v2.0/authorize?p=B2C_1A_SigninArkose&client_id=96392ea3-c9ca-49c2-b670-e3bb80512cc8&nonce=defaultNonce&redirect_uri=https%3A%2F%2Farkosetest2.onmicrosoft.com%2Freply&scope=openid&response_type=id_token&prompt=login

## Notes 

For the file named B2C_1A_Captcha_TrustFrameworkExtensions.xml 
 - Uncomment the following lines 86, 88 and 90, 103
 - Line 95 update this URL https://youraccount.azurewebsites.net/api/validatetoken which you host,
 
For the validate-token.php file
- make sure to hit the fc_api_url with your private key 

## Arkose Developer Docs 
Reference our standard setup developer docs here - https://arkoselabs.atlassian.net/wiki/spaces/DG/pages/214176229/Standard+Setup 
and view the repo here 
https://github.com/frostjohnAL/StandardSetup
