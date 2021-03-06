## flux reconcile alert-provider

Reconcile a Provider

### Synopsis

The reconcile alert-provider command triggers a reconciliation of a Provider resource and waits for it to finish.

```
flux reconcile alert-provider [name] [flags]
```

### Examples

```
  # Trigger a reconciliation for an existing provider
  flux reconcile alert-provider slack

```

### Options

```
  -h, --help   help for alert-provider
```

### Options inherited from parent commands

```
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
  -n, --namespace string    the namespace scope for this operation (default "flux-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [flux reconcile](flux_reconcile.md)	 - Reconcile sources and resources

