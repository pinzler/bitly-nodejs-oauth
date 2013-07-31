# Bitly Oauth Node.JS & Express Quick Template

## Setup on bitly

Go to http://bitly.com/a/oauth_apps and follow the steps to register a new application.

The "Redirect URI" must be the same link to where you put oauth.php for your redirect.  

Copy down your Client ID and Client Secret and insert them into the server.js file. 


## The files

server.js - This will setup a /login URL that take the user to a bitly login page and then after the user logs in they will be redirected back to /callback for more of the oauth process and to get the user access token.

##Links

[bitly Developer Website](http://dev.bitly.com/)

[More on bitly Authentication](http://dev.bitly.com/authentication.html)
