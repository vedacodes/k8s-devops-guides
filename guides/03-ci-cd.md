# CI/CD patterns for Kubernetes

CI responsibilities:
- Build artifacts, run tests, produce container images.

CD responsibilities:
- Promote images to environments, update manifests, trigger Argo/Flux syncs.

Patterns:
- Image tagging (semver, build metadata)
- Image promotion vs manifest promotion
- Canary and blue/green deployments using service proxies or traffic splitters

Tools examples: GitHub Actions, GitLab CI, Tekton, Jenkins X.
