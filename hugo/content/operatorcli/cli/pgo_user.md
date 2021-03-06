---
title: "pgo_user"
---
## pgo user

Manage PostgreSQL users

### Synopsis

USER allows you to manage users and passwords across a set of clusters. For example:

	pgo user --selector=name=mycluster --update-passwords
	pgo user --change-password=bob --expired=300 --selector=name=mycluster --password=newpass

```
pgo user [flags]
```

### Options

```
      --change-password string   Updates the password for a user on selective clusters.
      --db string                Grants the user access to a database.
      --expired string           required flag when updating passwords that will expire in X days using --update-passwords flag.
  -h, --help                     help for user
      --password string          Specifies the user password when updating a user password or creating a new user.
      --password-length int      If no password is supplied, this is the length of the auto generated password (default 12)
  -s, --selector string          The selector to use for cluster filtering.
      --update-passwords         Performs password updating on expired passwords.
      --valid-days int           Sets passwords for new users to X days. (default 30)
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver.
      --debug                    Enable debugging when true.
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo](/operatorcli/cli/pgo/)	 - The pgo command line interface.

###### Auto generated by spf13/cobra on 3-Jun-2019
