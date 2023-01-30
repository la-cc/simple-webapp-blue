# Demo-Repo 

*_NOTE:_* The repository is just a demo that is used to demonstrate Tenant Dedicated Cluster Multi-tenancy with flux.

## Preventing Cross-Team Deployments with GitOps and Flux in a Shared Kubernetes Clusters

If you have a shared kubernetes cluster for multiple teams, but still choose the GitOps approach with flux to deploy. 
Then the teams might be restricted to namespaces via RBAC, but not flux. So team A can deploy to team B's namespaces via flux. 

How to prevent this, keep the declarative deployment and still use the RBAC of kubernetes. 
I wrote an article ["GitOps: Multi-Tenancy with Flux and Kubernetes"](https://medium.com/@artem.lajko/gitops-multi-tenancy-with-flux-and-kubernetes-1fa4ff0b9c79) with a sample implementation how to use “Tenant Dedicated Cluster Multi-tenancy” with flux.
