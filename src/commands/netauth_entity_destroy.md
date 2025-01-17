## netauth entity destroy

Destroy an existing entity

### Synopsis


Destroy the entity with the specified ID.  The entity is deleted
immediately and without confirmation, please ensure you have typed the
ID correctly.

It is possible to remove the entity running the command, but this is
not recommended and may leave your system without any administrative
users.

The caller must posess the DESTROY_ENTITY capability or be a
GLOBAL_ROOT operator for this command to succeed.

```
netauth entity destroy <ID> [flags]
```

### Options

```
  -h, --help   help for destroy
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
