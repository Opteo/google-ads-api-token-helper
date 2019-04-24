# Google Ads API token helper

A tiny web interface to help you get started with a refresh token for your Google Ads API project.

It will grant you a `refresh_token` with the `https//www.googleapis.com/auth/adwords` scope.

Hosted on https://refresh-token-helper.opteo.com. 

Front-end only -- Only a browser is needed. All network requests are directed towards Google's OAuth services. It will make requests to:
- https://accounts.google.com/o/oauth2/auth (GET request)
- https://accounts.google.com/o/oauth2/token (POST request)

The source code has been kept deliberately simplistic to maintain clarity.
