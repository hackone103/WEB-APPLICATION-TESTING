# GitHub Dorks
##### GitHub Dorks
Demo: `"targe.com" admin` 

#### GitHub Dorks for Finding Files
```
filename:manifest.xml
filename:travis.yml
filename:vim_settings.xml
filename:database
filename:prod.exs NOT prod.secret.exs
filename:prod.secret.exs
filename:.npmrc _auth
filename:.dockercfg auth
filename:WebServers.xml
filename:.bash_history <Domain name>
filename:sftp-config.json
filename:sftp.json path:.vscode
filename:secrets.yml password
filename:.esmtprc password
filename:passwd path:etc
filename:dbeaver-data-sources.xml
path:sites databases password
filename:config.php dbpasswd
filename:prod.secret.exs
filename:configuration.php JConfig password
filename:.sh_history
shodan_api_key language:python
filename:shadow path:etc
JEKYLL_GITHUB_TOKEN
filename:proftpdpasswd
filename:.pgpass
filename:idea14.key
filename:hub oauth_token
HEROKU_API_KEY language:json
HEROKU_API_KEY language:shell
SF_USERNAME salesforce
filename:.bash_profile aws
extension:json api.forecast.io
filename:.env MAIL_HOST=smtp.gmail.com
filename:wp-config.php
extension:sql mysql dump
filename:credentials aws_access_key_id
filename:id_rsa or filename:id_dsa
```
### GitHub Dorks for Finding Languages
``` 
language:python username
language:php username
language:sql username
language:html password
language:perl password
language:shell username
language:java api
HOMEBREW_GITHUB_API_TOKEN language:shell

```
### GiHub Dorks for Finding API Keys, Tokens and Passwords

``` 
api_key
“api keys”
authorization_bearer:
oauth
auth
authentication
client_secret
api_token:
“api token”
client_id
password
user_password
user_pass
passcode
client_secret
secret
password hash
OTP
user auth
```
### GitHub Dorks for Finding Usernames
``` 
user:name (user:admin)
org:name (org:google type:users)
in:login (<username> in:login)
in:name (<username> in:name)
fullname:firstname lastname (fullname:<name> <surname>)
in:email (data in:email)

```
### GitHub Dorks for Finding Information using Dates
```  
created:<2012–04–05
created:>=2011–06–12
created:2016–02–07 location:iceland
created:2011–04–06..2013–01–14 <user> in:username
```

### GitHub Dorks for Finding Information using Extension
``` 
extension:pem private
extension:ppk private
extension:sql mysql dump
extension:sql mysql dump password
extension:json api.forecast.io
extension:json mongolab.com
extension:yaml mongolab.com
[WFClient] Password= extension:ica
extension:avastlic “support.avast.com”
extension:json googleusercontent client_secret
```


#### GitHub Dork Resource
```
# Github Email Dorks
googlemail.com
emailaddress
mailaddress
outlook.com
mail
mailaddress
mailto

# Github Mysql Dork
mysql filename:database password
mysql filename:database pw
mysql filename:database secret 
mysql path:sites databases password
mysql filename:config dbpasswd
filename:conf database
filename:.env DB_USERNAME NOT homestead
mysql password

# Github Misspelled Dorks
filename:conffig
filename:seting 
usser
pasword
passsword
passoword
seccret 
secred
sicret
datebase
databasse
setttings
acccess
accout
acount
htacess
mesql
mysqql
bassword
filename:konfig
htaccess_file
.htaccess
htacces
.htacess
konfig

# Github Htaccess Dorks 
htaccess RewriteEngine On
htaccess General Apache options
htaccess AddOutputFilterByType 
htaccess RewriteCond 
path:**/htaccess
path:**/htaccess language:Text

# Github DB Dorks
filename:database password
filename:database pw
filename:database secret 
filename:db.sql password 
path:sites databases password
filename:config dbpasswd
filename:conf database
filename:.env DB_USERNAME NOT homestead
mysql password

# Github Config Dork
filename:config password
filename:config secret
filename:config apiKey
filename:cfg apiKey
filename:cfg password
filename:cfg secret
filename:wp-config.php
filename:config.json auths
filename:configuration password
filename:config dbpasswd
filename:config pass
filename:master.key path:config
filename:jupyter_notebook_config.json

# Github AWS Secret Sorks
filename:credentials aws_access_key_id
filename:.bash_profile aws
rds.amazonaws.com password
filename:.s3cfg
ARTIFACTS_AWS_ACCESS_KEY_ID=
ARTIFACTS_AWS_SECRET_ACCESS_KEY=
AWS-ACCT-ID=
AWS-KEY=
AWS-SECRETS=
AWS
AWS.config.accessKeyId=
AWS.config.secretAccessKey=
AWSACCESSKEYID=
AWSCN_ACCESS_KEY_ID=
AWSCN_SECRET_ACCESS_KEY=
AWSSECRETKEY=
AWS_ACCESS=
AWS_ACCESS_KEY=
AWS_ACCESS_KEY_ID=
AWS_CF_DIST_ID=
AWS_DEFAULT
AWS_DEFAULT_REGION=
AWS_S3_BUCKET=
AWS_SECRET=
AWS_SECRET_ACCESS_KEY=
AWS_SECRET_KEY=
AWS_SES_ACCESS_KEY_ID=
AWS_SES_SECRET_ACCESS_KEY=
BUCKETEER_AWS_ACCESS_KEY_ID=
BUCKETEER_AWS_SECRET_ACCESS_KEY=
SANDBOX_AWS_ACCESS_KEY_ID=
SANDBOX_AWS_SECRET_ACCESS_KEY=
S3-EXTERNAL-3.AMAZONAWS.COM=
S3.AMAZONAWS.COM=
filename:.bash_profile aws
rds.amazonaws.com password

# Best Github Dork
filename:config key NOT test
filename:setting key NOT test
filename:env key NOT test
filename:config password NOT test
filename:setting password NOT test
filename:env password NOT test
filename:config secret NOT test
filename:setting secret NOT test
filename:env secret NOT test
filename:config passwort NOT test
filename:setting passwort NOT test
filename:env passwort NOT test
filename:config pwd NOT test
filename:setting pwd NOT test
filename:env pwd NOT test
filename:config hostname 
```