This repo is a demonstration of cloud-native testing workflows combining Testkube, vCluster, and ArgoCD for automated, ephemeral testing environments in Kubernetes.

## 🎯 Use Case

This demo showcases how to create ephemeral testing environments that automatically:

1. **Spin up isolated vClusters** for each PR/test run
2. **Deploy applications via ArgoCD** to the vCluster
3. **Run comprehensive tests using Testkube** with different testing tools
4. **Clean up automatically** when done

Perfect for GitOps workflows where you want to test deployments in isolation without affecting your main cluster.

## 🔗 Learn More

- [Testkube Documentation](https://docs.testkube.io/)
- [vCluster Documentation](https://www.vcluster.com/docs)
- [ArgoCD Documentation](https://argo-cd.readthedocs.io/)
- [Chainsaw Testing](https://kyverno.github.io/chainsaw/)

have fun!
