## flux suspend helmrelease

Suspend reconciliation of HelmRelease

### Synopsis

The suspend command disables the reconciliation of a HelmRelease resource.

```
flux suspend helmrelease [name] [flags]
```

### Examples

```
  # Suspend reconciliation for an existing Helm release
  flux suspend hr podinfo

```

### Options

```
  -h, --help   help for helmrelease
```

### Options inherited from parent commands

```
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
  -n, --namespace string    the namespace scope for this operation (default "flux-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [flux suspend](flux_suspend.md)	 - Suspend resources

