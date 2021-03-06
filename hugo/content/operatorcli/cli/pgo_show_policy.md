---
title: "pgo_show_policy"
---
## pgo show policy

Show policy information

### Synopsis

Show policy information. For example:

	pgo show policy --all
	pgo show policy policy1

```
pgo show policy [flags]
```

### Options

```
      --all    show all resources.
  -h, --help   help for policy
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

* [pgo show](/operatorcli/cli/pgo_show/)	 - Show the description of a cluster

###### Auto generated by spf13/cobra on 3-Jun-2019
