## netauth group create

Create a new group

### Synopsis


Create an group with the specified name.  Though there are no strict
requirements on the name beyond it being a single word that is
globally unique, it is strongly encouraged to make it exclusively of
lower case letters and numbers.  For the best compatibility, it is
recommended to start with a letter only.

Additional fields can be specified on the command line such as the
display name, or a group to defer management capability to.  If
desired a custom number can be provided, but the default behavior is
sufficient to select a valid unallocated number for the new group.

The caller must posess the CREATE_GROUP capability or be a GLOBAL_ROOT
operator for this command to succeed.

```
netauth group create <name> [flags]
```

### Examples

```
$ netauth group create demo-group
New group created successfully
```

### Options

```
      --display-name string   Group display name
  -h, --help                  help for create
      --managed-by string     Delegate management to this group
      --number int            Number to assign. (default -1)
```

### Options inherited from parent commands

```
      --config string   Use an alternate config file
      --entity string   Specify a non-default entity to make requests as
      --secret string   Specify the request secret on the command line
```

### SEE ALSO

* [netauth group](netauth_group.md)	 - Manage groups and associated data

###### Auto generated by spf13/cobra on 18-Aug-2019
