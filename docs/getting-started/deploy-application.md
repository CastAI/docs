---
description: Once you create a cluster, you're ready to deploy your CAST AI-managed Kubernetes application. Here's how you can do it.
---

# 3. Deploy application

CAST AI managed cluster runs on Kubernetes. Once you [create a cluster](../getting-started/create-cluster.md) - you can download a **`kubeconfig` file** of the cluster and deploy your application using **`kubectl`** command-line tool.

![](screenshots/downloadkubeconfig.png)

For more information please refer to [Kubernetes documentation](https://kubernetes.io/docs/home/).

Relevant for this section:

- [Kubernetes docs - Organizing cluster access using kubeconfig files](https://kubernetes.io/docs/concepts/configuration/organize-cluster-access-kubeconfig/)

- [Kubernetes docs - Deploy an app using kubectl](https://kubernetes.io/docs/tutorials/kubernetes-basics/deploy-app/deploy-intro/)

## Demo multi-cloud

You can use our example application for a quick deployment and showcase of multi-cloud. The widget on the left will display which cloud the application is currently running on.

[Github - Boutique eshop example](https://github.com/castai/examples/tree/main/boutique-eshop)

![](screenshots/boutique.png)
