# GitOps with Argo CD

Overview:
- Git as the single source of truth for cluster state.
- Argo CD for continuous delivery: sync, drift detection, rollbacks.

Steps:
1. Define app manifests in a repo (Helm charts or kustomize overlays).
2. Install Argo CD and create Applications pointing to those repos.
3. Use PR-based flows to promote changes across environments.

Best practices: automated health checks, RBAC for Argo, admit only signed commits for production.
