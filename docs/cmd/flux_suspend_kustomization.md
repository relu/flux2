## flux suspend kustomization

Suspend reconciliation of Kustomization

### Synopsis

The suspend command disables the reconciliation of a Kustomization resource.

```
flux suspend kustomization [name] [flags]
```

### Examples

```
  # Suspend reconciliation for an existing Kustomization
  flux suspend ks podinfo

```

### Options

```
  -h, --help   help for kustomization
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

