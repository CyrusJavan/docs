## netauth auth

Use and set authentication data

### Synopsis


The auth subystem deals in authentication information.  This includes
secrets and tokens.  Here you'll find the commands to change secrets,
chec them, get and destroy tokens and other intesting tasks around
authentication.

### Options

```
  -h, --help   help for auth
```

### Options inherited from parent commands

```
      --config string   Use an alternate config file
      --entity string   Specify a non-default entity to make requests as
      --secret string   Specify the request secret on the command line
```

### SEE ALSO

* [netauth](netauth.md)	 - Interact with the NetAuth system.
* [netauth auth change-secret](netauth_auth_change-secret.md)	 - Change an entity secret
* [netauth auth check](netauth_auth_check.md)	 - Check authentication credentials
* [netauth auth destroy-token](netauth_auth_destroy-token.md)	 - Destroy an existing local token
* [netauth auth get-token](netauth_auth_get-token.md)	 - Request a new token from the server
* [netauth auth inspect-token](netauth_auth_inspect-token.md)	 - Inspect a token locally
* [netauth auth validate-token](netauth_auth_validate-token.md)	 - Validate a token with the server

###### Auto generated by spf13/cobra on 18-Aug-2019
