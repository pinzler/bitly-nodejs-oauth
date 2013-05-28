# Bitly Authentication Node.JS & Express Quick Template
=======================================================

## Setup on bitly

Go to http://bitly.com/a/oauth_apps and follow the steps to register a new application.

The "App Link" must be the same domain as where you put oauth.php for your redirect.  (Example: if your redirect_uri is http://www.domain.com/app/oauth.php then your "App Link" can be "http://www.domain.com/" or "http://www.domain.com/app/" but NOT "http://www.domain.com/info/"

Copy down your Client ID and Client Secret and insert them into the server.js file. 


## The files

server.js - This will setup a /login URL that take the user to a bitly login page and then after the user logs in they will be redirected back to /callback for more of the oauth process and to get the user access token.

##Links

[bitly Developer Website](http://dev.bitly.com/)

[More on bitly Authentication](http://dev.bitly.com/authentication.html)
