## netauth entity create

Create a new entity with the specified ID

### Synopsis


Create an entity with the specified ID.  Though there are no strict
requirements on the ID beyond it being a single word that is globally
unique, it is strongly encouraged to make it exclusively of lower case
letters and numbers.  For the best compatibility, it is recommended to
start with a letter only.

Additional fields can be specified on the command line such as the
number to assign or the initial secret to set.  If left blank the
number will be chosen as the next unassigned number, and the secret
will be prompted for.  To create an entity with an unset secret,
specify the empty string as the initial secret.

The caller must posess the CREATE_ENTITY capability or be a
GLOBAL_ROOT operator for this command to succeed.

```
netauth entity create <ID> [flags]
```

### Options

```
  -h, --help                    help for create
      --initial-secret string   Initial secret.
      --number int              Number to assign. (default -1)
```

### Options inherited from parent commands

```
      --config string   Use an alternate config file
      --entity string   Specify a non-default entity to make requests as
      --secret string   Specify the request secret on the command line
```

### SEE ALSO

* [netauth entity](netauth_entity.md)	 - Manage entities and associated data

###### Auto generated by spf13/cobra on 18-Aug-2019
