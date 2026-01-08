# Helm: packaging and releases

Use Helm to templatize Kubernetes resources and manage releases.

Guidance:
- Keep values.yaml small; use overrides for environment-specific configs.
- Use chartmuseum or OCI registries for chart storage.
- Lock chart versions for reproducible deployments.

Security: scan charts and images; enable imagePullSecrets when needed.
