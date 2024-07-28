# Macia Indiweb

Hugo Module for adding the header for the WebMention and other stuff for the Indiweb Open Standard

## Shortcode

For adding the urls in the head for the webmentions you can use this shortcode

~~~ html
{{ partial "macia-indiweb/indiweb.html" . }}
~~~

For the auth for the indiweb logins you can use this shortcode in the head

~~~ html
{{ partial "maciawebmention/auth.html" . }}
~~~

## Configs

The config for params for the indiweb are

~~~ yaml
params:
  maciaindiweb:
    webmention: 
    pingback: 
    micropub: 
    microsub: 
    authorization_endpoint: 
    token_endpoint: 
~~~

For the auth indiweb the config are

~~~yaml
params:
  auth:
    x:
    mastodon:
    twitter:

~~~
And here can set the url for the indiweb authentication.

You can set any of them.
