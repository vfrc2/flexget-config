# flexget-config
##trakt 2.0 api update

The trakt plugins have been updated to use the newest API (v2). Authorization is now handled by tokens. You can generate a pin for Flexget by visiting ​https://trakt.tv/pin/346. Use this pin to generate an access token by issuing the cli command <code>flexget trakt auth <account> <pin></code>, where <account> is a local identifier that the access token is assigned to. We recommend that you use your Trakt username.
