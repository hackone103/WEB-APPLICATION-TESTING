# Google Dorks
  
  Google hacking, also named Google dorking, is a hacker technique that uses Google Search and other Google applications to find security holes in the configuration and computer code that websites are using.
## Google Dork
   Demo:
   `site: targe.com "admin"` `site: targe.com -site:www.targe.com` `site: targe.com allintext:password filetype:log after:200`
   `site: targe.com -site:www.targe.com`


### Search Operators :
```
# cache:
cache:www.google.com web 

# link:
# link:www.google.com

# related:
related:www.google.com

# info:
info:www.google.com

# define:
define:google

# site:
site:www.google.com

# -site:
-site:www.google.com

# allintitle:
allintitle: google search

# intitle:
intitle:google search

# allintext
allintext : passwod

# allintitle:
intitle:google 

# filetype:
filetype:log

# allinurl:
allinurl: google search

# inurl:
inurl:google 
```

### Using special search string to find vulnerable websites:
```inurl:php?=id1
inurl:index.php?id=
inurl:trainers.php?id=
inurl:buy.php?category=
inurl:article.php?ID=
inurl:play_old.php?id=
inurl:declaration_more.php?decl_id=
inurl:pageid=
inurl:games.php?id=
inurl:page.php?file=
inurl:newsDetail.php?id=
inurl:gallery.php?id=
inurl:article.php?id=
inurl:show.php?id=
inurl:staff_id=
inurl:newsitem.php?num= andinurl:index.php?id=
inurl:trainers.php?id=
inurl:buy.php?category=
inurl:article.php?ID=
inurl:play_old.php?id=
inurl:declaration_more.php?decl_id=
inurl:pageid=
inurl:games.php?id=
inurl:page.php?file=
inurl:newsDetail.php?id=
inurl:gallery.php?id=
inurl:article.php?id=
inurl:show.php?id=
inurl:staff_id=
inurl:newsitem.php?num=
inurl: 1051/viewer/live/index.html?lang=en
inurl: inurl:"view.shtml" ext:shtml
inurl:"/?q=user/password/"
inurl:"/cgi-bin/guestimage.html" "Menu"
inurl:"/php/info.php" "PHP Version"
inurl:"/phpmyadmin/user_password.php
inurl:"servicedesk/customer/user/login"
inurl:"view.shtml" "Network"
inurl:"view.shtml" "camera"
inurl:"woocommerce-exporter"
inurl:/?op=register
inurl:/Jview.htm + "View Video - Java Mode"
inurl:/Jview.htm + intext:"Zoom :"
inurl:/adfs/ls/?SAMLRequest
inurl:/adfs/ls/idpinitiatedsignon
inurl:/adfs/oauth2/authorize
inurl:/cgi-bin/manlist?section
inurl:/eftclient/account/login.htm
inurl:/homej.html?
inurl:/index.html?size=2&mode=4
inurl:/pro_users/login
inurl:/wp-content/themes/altair/
inurl:/xprober ext:php
inurl:RichWidgets/Popup_Upload.aspx
inurl:Sitefinity/Authenticate/SWT
inurl:adfs inurl:wctx inurl:wtrealm -microsoft.com
inurl:authorization.ping
inurl:https://trello.com AND intext:@gmail.com AND intext:password
inurl:idp/Authn/UserPassword
inurl:idp/prp.wsf
inurl:login.seam
inurl:nidp/idff/sso
inurl:oidc/authorize
inurl:opac_css
inurl:weblogin intitle:("USG20-VPN"|"USG20W-VPN"|USG40|USG40W|USG60|
```

### List for Special Search characters
  `(+)`  Force inclusion of something common;\
  `(-)`  Exclude a search term;\
  `(')`  Use quotes around search;\
  `(.)`  A single-charactor wildcard;\
  `(*)`  Any word;\
  `(&)`  Boolean 'AND';\
  `(|)`  Boolean 'OR'; 









## Google Dork Resources
   1. GHDB : <a href="https://www.exploit-db.com/google-hacking-database">GHDB</a>
   2. DEFCONE 13 : <a href="https://jaimelightfoot.com/images/2018/05/google-directives.png">DEFCONE 13 PNG</a>