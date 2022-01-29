# rancher-desktop-notes

## Install ArgoCD

[How to install ArgoCD](https://operatorhub.io/operator/argocd-operator)

``` bash
Install on Kubernetes

    Install Operator Lifecycle Manager (OLM), a tool to help manage the Operators running on your cluster.
    $ curl -sL https://github.com/operator-framework/operator-lifecycle-manager/releases/download/v0.20.0/install.sh | bash -s v0.20.0
    Copy to Clipboard

    Install the operator by running the following command:
    What happens when I execute this command?
    $ kubectl create -f https://operatorhub.io/install/argocd-operator.yaml
    Copy to Clipboard

    This Operator will be installed in the "operators" namespace and will be usable from all namespaces in the cluster.

    After install, watch your operator come up using next command.
    $ kubectl get csv -n operators
    Copy to Clipboard

    To use it, checkout the custom resource definitions (CRDs) introduced by this operator to start using it.
```

## Install Kubernetes desktop

[How to install Kubernetes Desktop](https://rancher.com/docs/k3s/latest/en/installation/kube-dashboard/)
