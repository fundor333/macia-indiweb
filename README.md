# Macia WebMention

Hugo Module for adding the header for the WebMention

## Shortcode

~~~ html
{{ partial "macia-webmention/webmention.html" . }}
~~~

## Configs

The config for params is this

~~~ yaml
webmention:
  webmention: 
  pingback: 
  micropub: 
  microsub: 
  authorization_endpoint: 
  token_endpoint: 
~~~

You can set any of them.
