# GardeningManual

This pattern helps manage multiple microservices and environments using a single root app in Git.

- **What is App of Apps?**  
    A pattern in Argo CD where a **parent Application** deploys and manages multiple **child Applications**, all defined declaratively in Git.
    
- A **parent ArgoCD app** deploys and manages multiple **child apps** (like app configs, namespaces, ingress, SSO, etc.).
    
- Ideal for microservices, multi-cluster setups, and environment separation (dev/staging/prod).
