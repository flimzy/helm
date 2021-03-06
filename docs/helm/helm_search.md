## helm search

search for a keyword in charts

### Synopsis



Search reads through all of the repositories configured on the system, and
looks for matches.

Repositories are managed with 'helm repo' commands.


```
helm search [keyword]
```

### Options

```
  -r, --regexp           use regular expressions for searching
  -v, --version string   search using semantic versioning constraints
  -l, --versions         show the long listing, with each version of each chart on its own line
```

### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string               address of Tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of Tiller (default "kube-system")
```

### SEE ALSO
* [helm](helm.md)	 - The Helm package manager for Kubernetes.

###### Auto generated by spf13/cobra on 25-Jan-2018
