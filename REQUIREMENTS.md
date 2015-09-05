Backends
 - google oauth - see [racket-google](https://github.com/tonyg/racket-google)
 - github oauth - see [octokit.rkt](https://github.com/tonyg/octokit.rkt)
 - facebook oauth
 - twitter oauth or whatever
 - local user database (sqlite probably? or just a pickled hashtable even??)
    - confirmed via email

Support for reassociating identities with an account
 - e.g. changing email address
 - or deleting the association between, say, twitter and an account, and replacing it with straightforward email confirmation, or with google login, or ...
 - implies having a long-term user identifier that is not derived from the identity authentication mechanism used
    - support for user names freely chosen, then?

Support for two-factor authentication

Support for session tokens, needed to implement authentication via oauth which is an authorization protocol
 - utilities for cookie, Auth-header, & parameter-based token retrieval
