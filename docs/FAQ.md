# FAQ

## Why is it not possible to use PVC?

FixTheOps is a costly project, and to save resources the PVC are disabled by default (As each of them is a cost increase). So if you need to install some helm charts for a challenge, or Kubernetes resources using Persistent Volumes, you will need to disable them.

You can still use the `emptyDir` volume type if needed in the pods.

## How to connect to a cluster challenge?

[Go to page](https://github.com/FixTheOps/fixtheops-public/blob/main/docs/how-to-connect-with-kubeconfig.md)