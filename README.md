This repo is a demonstration of cloud-native testing workflows combining Testkube and vCluster for automated, ephemeral testing environments in Kubernetes.

## 🎯 Use Case

This demo showcases how to create ephemeral testing environments that automatically:

1. **Connects to GKE cluster** using your GCP credentials
2. **Spin up isolated vClusters** for each PR/test run on GKE cluster
2. **Deploy applications using your manifests** to the vCluster
3. **Run comprehensive tests using Testkube** with different testing tools for the application
4. **Clean up automatically** when test completes

Perfect for GitOps workflows where you want to test deployments in isolation without affecting your main cluster.

## 🔗 Learn More

- [Testkube Documentation](https://docs.testkube.io/)
- [vCluster Documentation](https://www.vcluster.com/docs)
