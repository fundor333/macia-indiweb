# Macia Indiweb

Hugo Module for adding the header for the WebMention and other stuff for the Indiweb Open Standard

## Shortcode

~~~ html
{{ partial "maciawebmention/webmention.html" . }}
~~~

## Configs

The config for params is this

~~~ yaml
maciawebmention:
  webmention: 
  pingback: 
  micropub: 
  microsub: 
  authorization_endpoint: 
  token_endpoint: 
~~~

You can set any of them.
